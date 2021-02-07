# unicef-ureport-polls

 Based on the publicly available data on U-Report- UNICEF's mobile platform to amplify the voices of underprivileged youth globally.
 The data collected was based on the date of download- May 29, 2020. 

 ## Motivation
The purpose of this research is to unify the different polls in different countries and languages to find comparable questions present across all these contexts. This allows for a more nuanced understanding of patterns of similarity and difference in cultural beliefs among the world's youth. 

### Installations


```pip install -r requirements.txt```

### How to Interact With the Project
Given the range of languages involved, this repository makes extensive use of NLP methods built on BERT and other deep learning approaches. 
The same code can be applied for data downloaded more recently from the U-Report servers. 

### Licensing, Authors, Acknowledgements, etc.
Special thanks to Christopher Brooks and Hira ur-Rahman at the UNICEF Innovation Office in New York for supporting this project in its initial stages. 

### Data sets:
Freely available on the [U-Report website].(https://ureport.in/)

### Key Findings:
=======
This notebook consists of two sections. The first experiments with a tiny percentage (1%) of the full dataset to understand the required approaches to building visualizations. The second section then conducts similar analyses for the full dataset (1 GB>) in PySpark. Finally, results are visualized using Plotly and Leaflet.js