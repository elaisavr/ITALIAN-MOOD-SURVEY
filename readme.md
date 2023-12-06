
# ITALIAN MOOD SURVEY

This challenge aimed to analyse and find some insights about a survey addressed to a sample of Italians between February - September 2023.
The survey questionned about moods, feelings, states of mind related to various aspects in personal life (feelings of the individual e.g. How are you today?) and the external context (feelings about the environment around the individual e.g. How do you feel about the current situation in Italy?)

From the multiple details about all the individuals, already fullfilled in the survey, more variables were extracted to conduct the analysis such as:  
-   Time variables  
-   Geographical information  
-   Other individual's information  

The steps followed for this project were:  
1)  Clean the CSV file containing the real/original survey  
2)  English translation of the datas  
3)  Datas integration from existing variables or external sources (e.g. CSV from Italian Statistics Institution or Web Scraping from Wikipedia)  
4)  Merge all new variables/details found  
5)  Create the CSV file to import into PowerBI for final Data Visualization  


## INSTRUCTIONS  

Download folders 'Data' and 'sources', the 5 .ipynb files and the .pbix document in the same directory, open it in your editor/interpreter and run Python notebooks. 

For data cleaning, wrangling, exploratory Python 3.9 and the following libraries were used:  
-   Pandas,  
-   Numpy,   
-   Datetatime and Datetime module,   
-   Calendar,   
-   Requests to connect to web page endpoints,   
-   Beautifoulsoup for Web Scraping,   
-   Xlrd to manage date and time from first excel file containing survey raw datas,   
-   Os to create folder to save cleaned tables into CSV format   


Please run Python notebooks in this order:
  
`01_data_cleaning_blueprint.ipynb` for cleaning raw survey datas provided at the origin  

`02_English Tranlsation.ipynb` columns translation from Ita to Eng

`03_data_update_details.ipynb` to extract all new variables/details and add them into survey initial datas

`04_Survey_merge_details.ipynb` to merge all new infos extracted in notebook n.03

`05_data_dashboard_csv.ipynb` to generate a final CSV file to be loaded in PowerBI for Data Visualization  

*Dashboard_Data_Visualization.pbix* to see the dasboards. If you have some problems take a look at CSV source in Power Query Editor 
