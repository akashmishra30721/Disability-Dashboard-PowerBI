# Disability-Dashboard-PowerBI

The project concerns the Analysis of the Disability Census of India 2001 and 2011.

Following are some of the key insights from the project:
1. Uttar Pradesh has the highest disability and Lakshwadeep has the lowest disability in India
2. Age group of 10-19 has the highest disability count
3. In 2001, 'In Seeing' disability accounted for about 48.55% of total disability, while in 2011 'In Movement' was the highest with about 20.28% of the total disability.
4. In 2001, 'In hearing' disability was only 5.76% of the total disability, but in 2011 it increased to 18.92% of the total disability
5. Out of the top 5 districts with disabilities 3 are from Maharashtra-Thane, Pune, Mumbai, one from Karnataka - Banglore and one from West Bengal- Medinipur.

The process of building the dashboard was as follows:

1. Defining problem statement: Visualize and analyze the data of the Disability Census of India 2001 and 2011 and find insights from the data. By presenting the data in a way that is easy to understand, you can help educate people about the challenges faced by people with disabilities and encourage them to take action to address these challenges.

2. Data Collection: Data was collected from the official website of the census in India. https://censusindia.gov.in/census.website/data/census-tables Data collection was automated using the Selenium Webdriver library of Python.

3. Data Transformation: The data collected was present within multiple Excel files. Hence we transformed and merged all the files into a single file with a defined schema for better processing. 

4. Data Modeling: Data is the backbone of the project. We first created a star schema by identifying the entities and their attributes. We then defined the keys & then created relationships between all the entities.

5. Designing & Visualization: We then performed wireframing of the dashboard to be created & charts to be used. And finally developed the respective dashboard from the data by displaying some of the features in power bi such as drill down, showing a chart on hover, and Dax calculation to show % change of disability. Etc.
