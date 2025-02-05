# Module 14 (Belly-Button Challenge)

## **Overview**
This project involves building a interactive dashboard that explores the **Belly Button Biodiversity** dataset, cataloging the microbes that colonize human navels. The dataset reveals that some microbial species (OTUs - Operational Taxonomic Units) are common across individuals, while others are rare.
The challenge covers:
1. Build an interactive dashboard using D3.js and Plotly.js 
2. Create a horizontal bar char to display the top 10 OTUs for selected samples
3. Create a bubble chart to visualize bacterial cultures per sample
4. Display demographic information for each sample 
5. Update the dashboard when a new sample is selected 
6. Deploy the application using GitHub Pages.  

## **Technologies Used**
- JavaScript (D3.js, Plotly.js)
- HTML/CSS (Bootstrap)
- GitHub Pages for deployment
- JSON datset for analysis 

Module 14 Challenge/
    index.html              # Main dashboard structure 
│   static/js/app.js        # JavaScript file for fetching data and generating charts
│   samples.json            # Dataset with bacterial samples 
│   README.md           # Project documentation (this file)

## **Setup Instructions**
1. **Install the Dependencies:**
D3.js, Plotly.js, and Bootstrap are installed 

2. **Clone the Repository:**
Clone the GitHub repository and navigate into the project directory

3. **Run the Local Server :**
Open index.html in a web browser

5. **Verify Outputs:** 
- Ensure the dropdown menu updates the charts and plots dynamically from the dataset.
- The bar chart should correctly display the top 10 OTUs.
- The bubble chart visualizes bacteria cultures per sample. 
- The metadata panel updates demographic information based on the selected subject. 
