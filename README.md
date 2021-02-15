# An Analysis of Federally Regulated Pipelines Incidents


## Background Information
The Canada Energy Regulator (CER) quarterly publishes a pipeline incidents dataset (ranges from 2008 to current). As with any dataset, it required some cleaning, so I wrote a python script that parsed the entire file and removed unnecessary columns. This same cleaning phase was also done more efficiently in an Alteryx workflow. 


## Data Source
The Open Government website provides access to dataset and can be viewed [here](https://open.canada.ca/data/en/dataset/7dffedc4-23fa-440c-a36d-adf5a6cc09f1).


## Addition of Alteryx Workflow
Alteryx provides an intuitive (intuitive for me because I have an Engineering background) way of analyzing data. The datastream (called workflow in Alteryx) provides an efficient way of importing, cleaning, and exporting data—Extract, Transform and Load (ETL) all in one tool! 

Using Alteryx saved a massive amount of data preparation time—about 90%! 

Alteryx Workflow is shown below.

![Workflow](https://github.com/gregwhyte3/pipeline_transportation_occurrences/blob/master/Alteryx%20Workflow/alteryx_pipeline.PNG)


## Data Visualization In Tableau
Below is a snapshot of the dashboard I recently uploaded to Tableau Public. It can be accessed [here](https://public.tableau.com/profile/greg.whyte#!/vizhome/PipelineIncidentsinCanada/final).


![Dashboard](https://github.com/gregwhyte3/pipeline_transportation_occurrences/blob/master/Tableau/Dashboard.png)



