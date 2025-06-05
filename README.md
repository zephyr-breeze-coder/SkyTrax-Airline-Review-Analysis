# SkyTrax-Airline-Review-Analysis
Analysis of Airline Reviews Scraped from SkyTrax Website

## Project Overview
The purpose behind this project is to see from the data scraped from SkyTrax, which features of a flight are most significant in deciding a patron's overall experience and whether they would or would not recommend that experience to other travellers.  Air travel has changed over time along with the amenities available on flights or the size of seats, it is important for airline companies to understand the perspective of their clients in order to audit they're own performance as well as gaining insights in what services to invest in to gain market share over competitors. The site [SkyTrax](https://skytraxratings.com/about) was chosen as it is a one stop shop for international reviews of airlines offering reviews a wide range of services going back decades.

## Codes and Resources Used
* **Editor Used:** The editor used in the creation of this project is VisualStudio Code
* **Python Version:** Python3

## Python Packages Used
* **General Purpose**: requests, BeautifulSoup, time
* **Data Manipulation**: pandas, numpy
* **Data Visualization**: matplotlib, seaborn
* **Machine Learning**: wordcloud, sklearn, Ipython

## Methodology
### Data
Data was acquired by using BeautifulSoup to scrape html from the SkyTrax website for the desired airline. Data was transformed to be date, string, int data types to aid with analysis using pandas. Data needed extensive cleaning to remove inconsistent, missing, incomplete, and unnecessary that picked up during the scraping process. In addition, feedback, country_residence, among other variabes were feature engineered from the original scraped data to enhance the analysis.  

## Results and Evaluation
From preliminary analysis it would seem that as expected, the overall rating given by a passenger was the feature that best predicted whether that reviewer would recommend a particular airline. Extra ammenities such as wifi, in-flight entertainment were drastically underrepresented signalling that either a lot of flights do not include these services and/or these variables were not important when a reviewer sent feedback using SkyTrax. When reviewing the sentiment analysis directly from the comments it can be found that terms such as cleanliness, quick service timesm and price were important to a good portion of reviewers.

## Future
Future endeavors include increasing the amount of airlines included in the analysis, possibly looking for additional data sources to help tease out further insights from the analysis, and creating a database that can scale horizontally and vertically to accomodate addition to the amount of reviews and increased amount of air services available for reviewers to review.

## Acknowledgments/References
SkyTrax

## License
TBA
