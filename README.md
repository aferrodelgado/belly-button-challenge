# belly-button-challenge
**Module 14 - Interactive Visualizations**

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset (https://robdunnlab.com/projects/belly-button-biodiversity/) to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
  
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  
  - Use sample_values as the values for the bar chart.
  
  - Use otu_ids as the labels for the bar chart.
  
  - Use otu_labels as the hovertext for the chart.

<img width="716" alt="Top 10 Bacteria Cultures" src="https://github.com/user-attachments/assets/3d46625e-4fd3-4d6d-a524-7906717227ef">

3. Create a bubble chart that displays each sample.

- Use otu_ids for the x values.

- Use sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.

<img width="1130" alt="Bacteria Cultures Per Sample" src="https://github.com/user-attachments/assets/a38cabf6-6714-49ca-b627-5ef1c024ee23">

4. Display the sample's metadata, i.e., an individual's demographic information.

- Loop through each key-value pair from the metadata JSON object and create a text string.

- Append an html tag with that text to the #sample-metadata panel.

<img width="273" alt="Demographic Info" src="https://github.com/user-attachments/assets/1bb5de96-bd4a-4de6-92b7-c7243bcd93c4">

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

<img width="948" alt="Belly Button Biodiversity Dashboard" src="https://github.com/user-attachments/assets/4054743e-5c4e-4217-b54d-74c25deccc73">

6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
