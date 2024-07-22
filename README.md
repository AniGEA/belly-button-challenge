# belly-button-challenge

## Background

Welcome to the Belly Button Biodiversity Challenge! 
This project explores the microbial ecosystems living in human navels—a unique and mostly unexplored part of our bodies. The goal is to catalog and understand the different microorganisms, called operational taxonomic units (OTUs). The dataset shows that while a few OTUs are found in more than 70% of people, most OTUs are relatively rare.

For more details on the study, visit [Belly Button Biodiversity](https://robdunnlab.com/projects/belly-button-biodiversity/). 

## Interactive Dashboard
This project features an interactive dashboard that enables users to:

+ **View Demographic Information:**
  + Select a test subject ID for their demographic details.
+ **Explore Top 10 Bacterial Cultures:**
    + Analyze the top 10 bacterial cultures found in the selected test subject.
+ **Examine Bacteria Abundance:**
    + View the number of bacterial cultures per sample.
    
<img width="663" alt="Screenshot 2024-07-22 at 23 50 45" src="https://github.com/user-attachments/assets/ff393a89-edd6-4f53-a7c3-de243cb95527">

---------------
**Belly Button Biodiversity Dashboard**

## Tools Used
+ **JavaScript:** Powers the app's behavior and dynamically updates the HTML, including demographics data, dropdown menu options, and graph attributes.
+ **Plotly:** Used for rendering the bubble chart and bar graphs.
+ **D3:** Extracts data from the dataset URL and dynamically renders it within the dashboard, including setting up event listeners for updating data based on dropdown selections.
+ **HTML:** Structures the webpage content and layout, which is dynamically updated by JavaScript.
