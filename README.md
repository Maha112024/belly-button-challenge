# belly-button-challenge
Module 14 Challenge
##################################################################################################################
buildMetadata(sample): This function fetches metadata for the selected sample from the JSON file, filters it by the sample ID, and displays it in the metadata panel. It appends each key-value pair of metadata as a p tag for better readability.

buildCharts(sample): This function fetches sample data (including OTU IDs, labels, and sample values), and creates two types of charts:

Bubble Chart: Displays bacteria counts across samples with the OTU IDs on the x-axis, sample values on the y-axis, and a color scale representing OTU IDs.
Bar Chart: Displays the top 10 bacteria species found, showing the number of bacteria in a horizontal bar chart.
init(): This function initializes the dropdown menu with sample IDs from the JSON file and triggers the buildCharts and buildMetadata functions to render the initial charts and metadata for the first sample.

optionChanged(newSample): This function is called when a new sample is selected from the dropdown, and it re-renders the charts and metadata based on the selected sample.
