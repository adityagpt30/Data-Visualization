# Data Visualization on Global Terrorism Trends 
Terrorism is an act, which aims to create fear among ordinary people by illegal means. It is a threat to humanity. Yet compared to most types of crime, terrorism poses unique data collection challenges. As a result, even basic descriptive questions about terrorism have been difficult or impossible to answer like Terror attacks in each country, relationship between number of wounds and number of victims killed and the most commonly weapon type used. So, I am aiming to visualise these results so that it allows people to track and analyse the terrorism trends across the world. So, after exploring the dataset in an unstructured way to uncover initial patterns and characteristics I am aiming to visualise the terrorism trends across the world with the help of line chart and map in which I will be going to show the relationship between number of people killed and wounded that had occurred due to terror attack and also I am going to visualise the terror attack in each country from 1970 to 2018.

# Dataset
The data was taken from National Consortium for the Study of Terrorism and Responses to Terrorism website https://www.start.umd.edu/research-projects/global-terrorism-database-gtd. I just signed up on this webpage and downloaded the dataset or it can be downloaded from Kaggle as well. This Global Terrorism Dataset (GTD) include more than 190,000 international and domestic terrorist attacks that occurred worldwide from 1970 to 2018. The GTD defines terrorist attacks as religious, social goal through fear, coercion, intimidation or acts by non-state actors involving the threatened or actual use of illegal force or violence to attain a political. The size of dataset is 90Mb and the attributes such as weapon type, attack type, country, year, fatalities, number of persons wounded etc.

# Data Cleaning
After downloading the dataset, I just explored the large data in an unstructured way to uncover initial patterns, characteristics and point of interest. This helped me to create broad picture of important trends and major points to study and visualise it. I then further used OpenRefine (formerly called as Google Refine) tool to clean the messy dataset and get rid of unwanted columns. During cleaning of the dataset, I reduced the number of columns to one that are needed for visualising the important trends and trimmed the values to remove additional spaces. Furthermore, I removed the data which is erroneous and replaced NA values with 0 in numerical columns. Then finally using Tableau, I just uploaded the dataset and then further visualised it. 

# Tools Used: -
1.	OpenRefine
2.	Tableau 

# Conclusion

*Critically analyse the outcome of your visualisation.*

The visualisation is based on the terrorist attacks in every country based on different attributes like attack types, number of victims wounded or killed, etc. The outcome of the visualisation was to visualise the terrorist attacks from 1970 to 2018 and to analyse the relationship between number of kills and number of wounds in that time period. It supports mouse interaction to explore the data and is easily extendable to support different types of data. It has a drop-down filter through which one can easily filter out the results of that country and can explore more about number of victims killed or wounded.

*Were there aspects that you think could be improved upon?*

I also wanted to add the most active terrorism groups and their presence and activity in every city and wanted to show that on the world map also I would like to predict which of the cities will be the next target using my visualisation so as to make it more helpful and interesting for someone who wanted to study about Global Terrorism. And several improvements that may be made in the visualization, stripes that have wide region may be labelled. Comparing several attributes are not present and the solution for this is to have checkboxes through which user can select or deselect items to make stripes visible or not.
 
*Were there effects or functionality that you were technically unable to achieve?*

I tried the visualisation to look more user interactive, so I tried to add animations in the visualisations for example I wanted to show the top 15 most attack prone country with respect to kills and wounds that changes every year but was unable to achieve.

