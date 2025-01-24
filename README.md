# Belly-button-challenge

## Background

In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity] (https://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

# Instructions

Complete the following steps:

1. Use the D3 library to read in `samples.json` from the URL `https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`.
2.  Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  * Use `sample_values` as the values for the bar chart.
  * Use `otu_ids` as the labels for the bar chart.
  * Use `otu_labels` as the hovertext for the chart.


   ![image](https://github.com/user-attachments/assets/e9722273-cb81-4d61-b77b-d61e98b996c0)

3. Create a bubble chart that displays each sample.
  * Use `otu_ids` for the x values.
  * Use `sample_values` for the y values.
  * Use `sample_values` for the marker size.
  * Use `otu_ids` for the marker colors.
  * Use `otu_labels` for the text values.

![image](https://github.com/user-attachments/assets/0e75b975-3664-43cf-83b0-128d252902aa)

4. Display the sample's metadata, i.e., an individual's demographic information.

 * Loop through each key-value pair from the metadata JSON object and create a text string.
 * Append an html tag with that text to the `#sample-metadata` panel.

  ![image](https://github.com/user-attachments/assets/b5de13d3-1d16-47b4-85ea-fa4c2013520a)

5. Update all the plots when a new sample is selected. You are also welcome to create any layout you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/user-attachments/assets/4776a8b9-9337-4712-a972-40bf044c80a7)



