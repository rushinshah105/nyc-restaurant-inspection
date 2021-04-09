# NYC Restaurant Inspection Results Analysis

* Analyzed dataset containing every sustained or not yet adjudicated violation citation from every full or special program inspection conducted up to three years prior to the most recent inspection for restaurants and college cafeterias in an active status.

* I was specifically interested in finding out answers to following questions for Manhattan
  *	Identify restaurants with “no violations” and restaurants with “most violations”
  *	Identify best and worst restaurants by cuisine (see if anything surprises you)
  *	Identify how inspection and grading have changed over time (2017 - 2019) for different cuisines

* For this analysis, I performed following steps
  * Data Extraction
      * Downloaded and loaded data NYC Restaurant Inspection Data from NYC Opendata    
  * Data Cleaning/Feature Engineering
      * Replaced spaces with underscores in column names
      * Cleaned up special characters
      * Updating Data Types
      * Cleaned and feature engineered variables assocaited with cuisine
  * Exploratory Data Analysis
      * Reviewed the dataset 
      * Flitered records and dropped columns based on exploratory data analysis and null values review 
  * Data Visualizations for final findings
      * Created maps, sunburst and barcharts to answer various questions  


# Code and Dataset Details

* **Python Version**: 3.7

* **Packages**: pandas, numpy, folium, matplotlib, seaborn

* **Dataset** : https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j

* **Data Dictionary** : https://data.cityofnewyork.us/api/views/43nn-pn8j/files/ec33d2c8-81f5-499a-a238-0213a38239cd?download=true&filename=RestaurantInspectionDataDictionary_09242018.xlsx

* **Data Provided by** : Department of Health and Mental Hygiene (DOHMH)

* **Dataset Owner** : NYC OpenData

* **Detailed Code (Interactive Version via nbviewer)** : https://nbviewer.jupyter.org/github/rushinshah105/nyc-restaurant-inspection/blob/main/NYC_Restaurant_Inspection.ipynb

* **Detailed Code (Github Version)** : https://github.com/rushinshah105/nyc-restaurant-inspection/blob/main/NYC_Restaurant_Inspection.ipynb

* **Main Findings** : 
