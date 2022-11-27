R-PROJECT Datavisualization--CRIMEAGAINSTWOMEN

INTRODUCTION  

#The country where we worship goddess is also the worst country for women. Crime against women reported every two minutes over the last decade.
The main agenda of this project is to analyze crime data by following all the steps required for the complete data visualization.
Throughout this project,we will try to see if at all there is a reduction in crimes as the year count increases. We will visualize each column of data (mentioned above) state-wise & year-wise, and thus visualize it in a much better way. 

Data Source → Crimes Against Women - kaggle.com

CHARTS AND GRAPHS SUPPORTED
• Pie chart
• Bar chart
• Box plots
• Historams
• Line graphs
• Scatter plots


DOWNLOADING THE DATASET
Dataset is from Kaggle: View it here. This dataset contains statistics of various crimes cases against women from the year 2018–2020 with State or Union Territories.
The dataset contains the various crimes stats like Rape, Domestic Violence, Dowry, etc. with the year and place of the crime.

CLEANING THE DATASET
There were many repeated rows. In some places, different letter cases were used for the same word as in Assam and ASSAM. Other places have improper spacing, and shorthands were used for the State/UT. Delhi was repeated with the suffix UT.
Some rows contain the total for that particular district which we don’t want. So we are dropping all the columns which contain the word TOTAL.
After cleaning, this is how our final dataset will look like.

ANALYSING EACH CRIME BY YEAR
We group all the rows in the dataset by years.
With this data frame, we were able to find the total number of cases which was more than 26 lakh and they were registered between 2018 and 2020
With the help of plotly, an open-source interactive graphing library for charts to present each type of crime by years.

ANALYSING CRIMES BY STATES/UT
We are also analysing the data based on State/UT. So, we can find out which State/UT is the worst to live in for women.
