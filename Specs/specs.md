# Bubble Chart Tool Specification

## Iteration 1 ##

Implement a user-adjustable bubble chart similar to how you created the Marketing Campaign Performance Heatmap with the following specs:
- Must be an HTML and Typescript tool that runs in the browser from a local hard drive.
- Use the CSV provided for the typical data layout.
- Use the attached image as inspiration for the chart UI.
- X-axis should be “Legitimate %”
- Y-axis should be “Average Viewability %”
- Bubble size should be “Investment”
- Bubble label should be “Partner”
- Bubble color should correspond to “Partner Group”
- Implement an ability to set custom thresholds for different colors (for example, change color for specific partners)
- Similar to how you implemented the heatmap, allow the user to swap fields for the two axes, the bubble size, the color group, and the bubble label. Also allow a PNG export for PowerPoint presentations with 300dpi.



## Iteration 2 ##
Please make a new version of “Marketing Bubble Chart Tool” with the following adjustments:
- Add an input box to specify the chart Title, which will be customized and get reflected in 20pt font size.
- Add input boxes to specify the minimum and maximum of both x-axis and y-axis (new 4 input boxes total)
- Group Colors should update on Color Group change
- Custom Partner Colors should pull from the selected Color Group
- Make a button between “Update Chart” and “Export as PNG (300 DPI)” labeled “Export Embed”, and this button will download an HTML page that is an identical copy of the interactive chart, but without the options to modify the fields (no top portion) and the data should be embedded in this HTML exported page.
- Make the x-axis and y-axis labels 16pt font size.
- Make the x-axis and y-axis tick mark labels 14pt font size.
- Pull the default colors and colors available for selection from the following color specification: https://www.morganstanley.com/content/dam/msdotcom/en/assets/pdfs/FWUXDS_ColorChartsandAccessibility.pdf
- Follow this contrast guideline in your design: https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html

