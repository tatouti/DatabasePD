# Database II PADOVA
Respository for the database II project  
Link of the dataset Erasmus Mobility : https://www.kaggle.com/datasets/donjoeml/erasmus-mobility-statistics-2014-2019/data  
Link of the dataset Global Cost of Living : https://www.kaggle.com/datasets/mvieira101/global-cost-of-living  
Link of the World University Rankings : https://www.kaggle.com/datasets/r1chardson/the-world-university-rankings-2011-2023  

## Project description
The project is about the Erasmus mobility in Europe. The Erasmus program is a European Union student exchange program established in 1987. It forms a major part of the EU Lifelong Learning Programme 2007–2013, and is the operational framework for the European Commission's initiatives in higher education. The Erasmus+ program is a new version of the Erasmus program, which started in 2014. The Erasmus+ program aims to boost skills and employability, as well as modernizing Education, Training, and Youth work. We chose this topic because we are three french students doing our ERASMUS in Padua this semester.

## Dataset description
The dataset is composed of 3 datasets. The first one is about the Erasmus mobility in Europe. The second one is about the cost of living in the world. The third one is about the world university rankings.

The Erasmus dataset contains over 600000 rows (after we restricted the dataset to the academic year 2018-2019). It is important to note that this dataset contains data that isn't always accurate (for example, sometimes an entire adress is written in the "city" column).

## Content of the repository
The repository contains 2 folders :
- The folder "Datasets" contains the datasets used for the project.
- The folder "RDF_files" contains the RDF files generated throught Protégé.
  
At the root of the repository, you can find the following files :
- The notebook "Erasmus_Data_Analysis.ipynb" contains the code used to analyse the Erasmus dataset, and the HTML version of this notebook.
- The file "erasmus.ttl" contains the serialized RDF data in Turtle format generated throught the notebook "Erasmus_Data_Analysis.ipynb" (only the 170000 first rows of the erasmus dataset, and the two other datasets).
- The file "Erasmus Ontology Graph.png", visual graph of the ontology.
- This file "README.md".

## How to run the notebook

To serialize the RDF data in Turtle format, you need to run the notebook "Erasmus_Data_Analysis.ipynb", parts I and IV. 
The part II and III are used to analyse the dataset.
The part V provides some SPARQL queries and the summary of the results obtained.

## Authors

- Lou GOUBIN
- Théo JAOUDET 
- Clément DELRIEUX
