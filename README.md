# Identify-Customers-Segments
- thats my second project in Intro to machine learning with tensorflow Nanodegree program and was accepted succefully
-In this project 

In this projet  I have applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns

Data:
It is prohibited to share the data as it is a property to the company 
so  i will only describe how it looks like.


- `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891211      persons (rows) x 85 features (columns).

- `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191652    persons (rows) x 85 features (columns).

- `Data_Dictionary.md`: Detailed information file about the features in the provided datasets.

- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features      (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. You will use this information to cluster the general population into groups with similar demographic properties. Then, you will see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.

