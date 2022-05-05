# Team_MATRIX

This is a capstone project and objective is to predict the arrest status of crime in Chicago using chicago crime dataset (https://drive.google.com/file/d/1VKYacv-qq1lLcsnRSTIaXQPXOmt76sm9/view?usp=sharing)

Brewlytics: Brewlytics is a self-service data analytics software platform that allows users to manage, process, and refine the analytic workflows using an easy-to-use, drag and drop web-based interface. 
Users can create all kinds of workflows for their analytic tasks which are reusable. The workflows in the Brewlytics are made up of functions.
To reproduce our result download jupyter notebook named Chicago.ipynb.

Following are some packages that are must to run the code.
•	Sklearn – To predict arrest status of crime
•	Pandas – To handle data.
•	Matplotlib – To perform visualization
•	Folium – To perform spatial analysis

OVERVIEW OF THE PROJECT
This project is performing data analytics leveraging Brewlytics to determine patterns of Crime in Chicago as it relates to Chicago Community Areas and geographic distance away from police stations. 
Build a workflow in brewlytics tool to make use of visualization technology and machine learning algorithm to predict the distribution of crime across Chicago. 
Our goal is to identify and explore the dataset for a better understanding of spatial distribution characteristics of crime occurrence by methods of neighbourhood repetition and spatial analysis.

We would be visualizing and analyzing the distribution of the heat map, crime hotspots, crime patterns, and predict future ones. 
Data pre-processing will be done and propose a solution that would facilitate effective distribution of police forces in a city among multiple districts based on the extent to which each district is prone to crime.
We retrieved the data using the Socrata API into brewlytics functional table and performed all the above-mentioned operations. Same code has been replicated here in jupyter notebook.
HOW WAS IT DONE?
The data will be retrieved using the ‘query Chicago crime data’ functional. This will be done by retrieving the API into the brewlytics workspace. 
Another query relating to Chicago police station data will be performed. 
The patterns of crimes taking place in Chicago using Chicago crime data will be developed and then they will be related to the distance from the crime incident to the nearest police station using the Chicago police station by plotting the data geographically.

Data analysis of Patterns of Chicago crime will be given to the users. 
Users can see the insights like peak time of crime, frequent type of crime and location of highest crimes occurred and many more from the analysis and can access the geographical maps of the nearest police station from the crime incident. 
This analysis can be used by the Police to keep track of the patterns of crimes happening and the users to stay alert on the same.  


