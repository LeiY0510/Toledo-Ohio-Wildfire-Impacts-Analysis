# Toledo-Ohio-Wildfire-Impacts-Analysis
The project will require to analysis of wildfire impacts on a specific city in the US. The end goal is to be able to inform policymakers, city managers, city councils, or other civic institutions, to make an informed plan for how they could or whether they should make plans to mitigate future impacts from wildfires.
README 
v1.0 11/02/2024

****Project Title****
Common Analysis

****Project Description & Objective****
Common Analysis is the first part of the assignment. It sets the stage for the subsequent assignments. In Part 1 you conduct a base analysis. All of the students in the class will conduct the same analysis, but with a slightly different data subset.

The course project consists of the rest four parts: 
Part 2 - Extension Plan will require you to ask a human-centered data science question that extends the work in Course Project Part 1 - Common Analysis. 
Part 3 - Presentation will require you to give a modified (shorter) PechaKucha presentation of your completed project.
Part 4 - Project Repository, creation of a fully documented repository and also requires the submission of a written project report.
Part 5 - Peer Feedback, complete semi-structured evaluation and feedback on in-class presentations of your peers.


****Table of Contents****
Step 1: Data acquisition
Step 2: Create fire smoke estimates: This step is to create an annual estimate of wildfire smoke in your assigned city. 
	In this step, the smoke estimate should adhere to the following conditions:
		a. The estimate only considers the last 60 years of wildland fire data (1961-2021).
		b. The estimate only considers fires that are within 650 miles of your assigned city.
		c. Defines the annual fire season as running from May 1st through October 31st.

Step 3: Access the US EPA Air Quality System (AQS) API
Step 4: Analysis & Results: This step aims at comparing the smoke estimate to the estimate you create from the EPA AQS
Step 5: Visualize aspects of your analysis: Three graphics were created in this step:
		a. Produce a histogram showing the number of fires occurring every 50-mile distance from your assigned city for all fires ranging up to 1800 miles away from your assigned city. Your histogram should indicate the distance cut-off for your modeling work as specified in Step 1.
		b. Produce a time series graph of total acres burned per year for the fires occurring in the specified distance from your city.
		c. Produce a time series graph containing your fire smoke estimates for your city and the AQI estimates for your city.

****Raw Data****
1. Combined wildland fire datasets for the United States and certain territories, 1800s-Present (combined wildland fire polygons): https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81
2. US EPA Air Quality System (AQS): https://www.airnow.gov/sites/default/files/2020-05/aqi-technical-assistance-document-sept2018.pdf

****Final Results****
1. Number of Fires by Distance, Toledo OH
2. Total Acres Burned Per Year, Toledo OH
3. Fire Smoke and AQI Estimates Relationships, Toledo OH (1999 - 2020)


****License****
This code example was developed by Lay(Lei) Yang for use in DATA 512, a course in the UW MS Data Science degree program. Some part of this code is provided under the Creative Commons CC-BY license. Revision 1.0 - August 15, 2023

****API****
This analysis uses the API:US EPA Air Quality System (AQS) API (https://www.airnow.gov/sites/default/files/2020-05/aqi-technical-assistance-document-sept2018.pdf) to request to get a range of AQI data.

