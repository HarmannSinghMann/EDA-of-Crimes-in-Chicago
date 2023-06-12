## Analysis of Crimes in Chicago
This repository contains the code and data for the project "Analysis of Crimes in Chicago". The project was completed under the curriculum of Master of Science in Data Science in the course MSDSP-430, named Python for Data Science.
### Course Description
The course MSDSP-430 provides a comprehensive introduction to the core features of the Python programming language. The course demonstrates fundamental concepts in computer science, including data representation strategies and implementation of data structures in Python. Students learn about tools for data science and software engineering and work on data analysis problems employing various programming paradigms such as functional programming, object-oriented programming, and data stream processing. The course also pays special attention to the standard Python library and packages for analytics and modeling.
### Project Description
The project "Analysis of Crimes in Chicago" is a data analysis project that aims to explore the crime trends in Chicago over the past year. The project utilizes the data on crimes reported in Chicago from the past year, available from the Chicago Police Department's website. The project involves data cleaning, data wrangling, data visualization, and data analysis using Python and various Python packages.![ScreenShot2018-03-12at10 19 00AM](https://user-images.githubusercontent.com/65723872/225017633-d216eadd-6fe0-4e6f-9bc9-f04af4d7d7c1.png)

#### Case Scenario:
I have been contacted by the Police Department of Chicago to do in-depth analysis of the crimes happening in the city. A few questions they want me to answer are :

- Which was the most occuring crime in the city in the past year? Is there any prime location or time for it? Plot on map if possible.
- Are Streets still the primary location from where most of the Motor vehicles are stolen?
- Is there any seasonal trend to the type of crime? 

#### Data description
- The data used in the analysis can be found at: https://data.cityofchicago.org/Public-Safety/Crimes-One-year-prior-to-present/x2n5-8w5q 
- _About the data source_ : Chicago Data Portal is chicago's open data portal that lets us download the facts and data related to the city. Many of the datasets available are updated at least once a day, and many of them are updated several times a day.

##### Challenges
Exploratory data analysis (EDA) on public crime datasets can be challenging due to issues with data quality, privacy concerns, data size, data complexity, and bias in the data. Careful consideration of these challenges is necessary to ensure meaningful insights are derived while maintaining ethical and privacy considerations. It is important to evaluate data quality, take measures to protect privacy, reduce data size when necessary, identify important variables, account for biases in the data, and create effective visualizations to facilitate analysis.

##### Conclusion
Based on the analysis conducted, theft is identified as the most common crime in the city of Chicago, with N STATE ST being the location where it occurred most frequently. Motor vehicle theft, on the other hand, was found to primarily occur on the streets, with W 87TH ST being the location of most incidents in the past year. Additionally, there was a seasonal trend observed in the crimes, with a reduction of approximately 16% during the winter-spring period compared to the summer-fall period. The most prevalent crimes across all seasons were theft and battery.
<br>
Moreover, a heat map was generated to identify hot spots of crime in the city, which highlighted N STATE ST as a criminal hot spot in terms of crime occurrences. This analysis provides valuable insights into the nature and frequency of crimes in Chicago and can aid in developing targeted crime prevention strategies.
![heatmap_chicago](https://user-images.githubusercontent.com/65723872/225020604-77dfc457-b76f-4f33-b9a3-0e867b0a98e6.JPG)

##### Next Steps :
There are several potential next steps in the analysis that could provide additional insights into the patterns and trends of crime in Chicago. Here are a few examples:

- Temporal analysis: The current analysis has identified seasonal trends in crime occurrence. Further analysis can be done to understand how crime rates vary across different days of the week and different times of day. This could help identify the times when the police should be more vigilant in certain areas.

- Spatial analysis: In addition to the heat map generated, more sophisticated spatial analysis techniques can be used to identify crime hotspots, and the factors that contribute to the clustering of crimes in certain areas. For example, socioeconomic factors, population density, and access to public transportation can all be considered when analyzing crime hotspots.

- Categorization of crime: While the current analysis has identified the most common types of crime, it would be useful to categorize crime into more detailed subcategories. For example, theft can be further categorized into categories such as theft from a person, theft from a vehicle, and theft from a building. This would provide more specific information about the types of crime that occur most frequently.

- Predictive modeling: Based on the patterns and trends identified in the current analysis, predictive models can be developed to forecast the likelihood of different types of crime occurring in different areas of the city. This can help police and other law enforcement agencies to take proactive measures to prevent crime.

- Comparative analysis: It would be useful to compare the crime rates and patterns in Chicago with other cities of similar size and demographic characteristics to identify best practices and areas for improvement.

### Repository Structure
This repository contains the following files:
- **crime_analysis.ipynb**: This is the Jupyter notebook containing the Python code for data cleaning, data wrangling, data visualization, and data analysis.
- **README.md**: This file provides an overview of the project and repository.
### How to Use This Repository
To use this repository, you can simply clone or download the repository to your local machine. The crime_analysis.ipynb file can be opened using Jupyter Notebook or JupyterLab to view and run the Python code.
Dependencies
The project uses the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- folium

### Acknowledgments
The data used in this project was obtained from the Chicago Police Department's website. I would like to acknowledge their efforts in making this data publicly available.
