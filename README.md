# DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall
This repository contains the final project of the course 
["Linked Open Data and Knowledge Graphs"](https://digital-sciences.de/en/modules/linked-open-data-and-knowledge-graphs/) under the Digital Sciences Master's Degree at TH Köln.

## Project Description

The goal of this project was to explore the creation of disease-symptom association health knowledge graphs from three datasets, and the feasibility of combining them into a single encompassing health knowledge graph.

This project was inspired by the paper: Rotmensch et al., 2017. Learning a health knowledge graph from electronic medical records. Scientific reports, 7(1), 1-11. [A presentation of this paper](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/'Learning%20a%20Health%20Knowledge%20Graph'%20Presentation.md) is also included.

The three datasets are:
1. Disease-symptom co-ocurrences in medical journal papers from PubMed. *Associated paper: Zhou, X., Menche, J., Barabási, AL. et al. Human symptoms–disease network. Nat Commun 5, 4212 (2014). https://doi.org/10.1038/ncomms5212.* Creative Commons Attribution 4.0 International license.
2. Disease entities and their dbo:symptom property in DBPedia.  (https://www.dbpedia.org/).  GNU General Public License.
3. Patient disease diagnosis and symptom reports at a New York Hospital. *Associated paper: Wang X, Chused A, Elhadad N, Friedman C, Markatou M. Automated knowledge acquisition from clinical narrative reports. AMIA Annu Symp Proc. 2008 Nov 6;2008:783-7.*

## Project Contents

The main code for the project is contained within Jupyter notebooks, released under the MIT licence.   

Importing, processing and fixing the three datasets:   
[1. DBPedia Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/1.%20DBPedia%20Dataset.ipynb)  
[2. PubMed Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/2.%20PubMed%20Dataset.ipynb)  
[3. Hospital Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/3.%20Hospital%20Dataset.ipynb)  

A supplemental exploration of an automated process to fix broken id codes:  
[4. Example Approach to Fixing Missing Codes](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/4.%20Example%20Approach%20to%20Fixing%20Missing%20Codes.ipynb)  

Comparing the three datasets and combining them:   
[5. Combining Datasets](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/5.%20Combining%20Datasets.ipynb)  
[6. Comparing the Health Knowledge Graphs](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/6.%20Comparing%20the%20Health%20Knowledge%20Graphs.ipynb)

The data are all contained in the relevant folders.
