# Thesis

Investigation and Insights into Terrorism in Nigeria.
This research aims to develop a predictive model using machine learning techniques to analyze terrorism patterns and predict terrorist attacks’ success or failure. The proposed methodology involves data collection, preprocessing, exploratory data analysis, and machine learning model training and testing. The evaluation of model performance will provide insights into the effectiveness of various machine learning algorithms in predicting terrorism attacks success or failure.
The study's findings will contribute to a deeper understanding of terrorism patterns and provide valuable insights for counterterrorism efforts. The predictive model developed in this research may aid in identifying and addressing emerging threats, ultimately enhancing Nigeria's counter-terrorism measures.


# Data Source
The data sources for this thesis are the Global Terrorism Database (GTD) and the Armed Conflict Location and Event Data Project (ACLED). The GTD, managed by the University of Maryland's National Consortium for the Study of Terrorism and Responses to Terrorism (START), serves as an extensive repository of information on over 200,000 terrorist incidents worldwide spanning from 1970 to 2020. It encompasses diverse forms of terrorist attacks and offers more than 50 variables to characterize each event, drawing from publicly available sources like news articles, official records, and academic publications. The database maintains rigorous standards, with a comprehensive codebook defining the criteria for each variable and confidence ratings reflecting the reliability of incident information. 

In parallel, ACLED stands as a vital resource providing comprehensive data on political violence and protests globally since its establishment in 1997. The project's data encompasses a broad spectrum of events, including armed conflicts, riots, protests, and violence against civilians. ACLED employs a meticulous methodology, sourcing information from multiple channels such as news reports, humanitarian organizations, and local observers. Each event undergoes thorough verification and geocoding, ensuring precise spatial data for analysis. Notably, ACLED's commitment to transparency and accessibility sets it apart, with its data freely accessible to the public via an interactive online platform. This democratization of information empowers stakeholders across various sectors to analyze trends, assess risks, and inform decision-making processes at both global and local levels.

# Exploratory Data Analysis

The Global Terrorism Database (GTD), covering incidents from 1970 to 2020 but streamlined to 1997-2020, and the Armed Conflict Location and Event Data Project (ACLED), encompassing data from 1997 to 2024. GTD focuses on terrorism-related incidents, while ACLED centers on armed conflict-related events. The analysis specifically targeted nearly three decades of attacks occurring within Nigeria, utilizing a combination of Excel, Microsoft Power BI, and Google Colab to generate insights into the patterns and dynamics of violence in the region. 

Fatalies by States
![image](https://github.com/4hmadmb/Thesis/assets/116957999/7fa56bd2-63ed-438a-ba59-5cea2e965e68)
![image](https://github.com/4hmadmb/Thesis/assets/116957999/d9574503-aff4-41ad-9b4b-6d3f4c2aa904)

Fatalities by Year
![image](https://github.com/4hmadmb/Thesis/assets/116957999/c44aff92-0e57-45a4-b367-da94dc94c848)
![image](https://github.com/4hmadmb/Thesis/assets/116957999/74c1702a-d785-4100-811b-54f5b9b3d14c)

Fatalities by Attack Type
![image](https://github.com/4hmadmb/Thesis/assets/116957999/166f0ad4-b5ec-4717-8b8f-9682f67da30b)
![image](https://github.com/4hmadmb/Thesis/assets/116957999/e9c4453f-b5e7-4128-abdd-76348ef4cbce)

Top Ten Groups responsible for fatalities
![image](https://github.com/4hmadmb/Thesis/assets/116957999/3ffb7120-3520-4dd0-a794-7933fc4795fe)
![image](https://github.com/4hmadmb/Thesis/assets/116957999/fda5d8e8-4a17-4929-9f0e-57859481485a)

# ML

The dataset gotten is divided into two sets: a training and test set. The training set is used to train machine learning models, while the test set is used to evaluate the model's performance on unseen data. Three machine learning classifiers are applied to the dataset: Decision Tree, Random Forest and Logistic Regression. 
The performance of the machine learning models is evaluated using relevant assessment metrics, including accuracy, precision, recall, and F1 score. Confusion matrices are employed to measure accuracy, and these metrics help gauge the effectiveness of the classifiers. The machine learning models aim to provide insights into patterns and predictive capabilities related to terrorism data.

