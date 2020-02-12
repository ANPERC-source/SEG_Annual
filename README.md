This repository includes data for the words and phrases frequency of occurrence analysis. The database "SEGgrams.sqlite" consists of the words and phrases that occurred during the 38 Society of Explorational Geophysicists Annual Conferences (1982 - 2019). In the database, we have only words that appear more than 15 times during the observation period. Python program "words_retrieve.py" can be used to retrieve words from the database and plot the graph, which will be saved as "figure.png" in the folder with the "SEGgrams.sqlite" and "words_retrieve.py."

To run the program "words_retrieve.py," you need to install Python 3.7.2. To browse the data in the "SEGgrams.sqlite," you need to install DB Browser for SQLite.

How to use the database:
1.	To use the database, please download files "SEGgrams.sqlite" and "words_retrieve.py" in one folder.
2.	Run the file "words_retrieve.py" using the command prompt (>python words_retrieve.py) and follow the instructions.

The database "SEG_affiliations_data.sqlite" consists of the industry companies and different countries academy that presented their research during the 38 Society of Explorational Geophysicists Annual Conferences (1982 - 2019). Python program "SEG_org_retrieve.py" can be used to retrieve companies/countries from the database and plot the graph, which will be saved as "figure.png" in the folder with the "SEG_affiliations_data.sqlite" and "SEG_org_retrieve.py."

To run the program "SEG_org_retrieve.py," you need to install Python 3.7.2. To browse the data in the "SEG_affiliations_data.sqlite," you need to install DB Browser for SQLite.

How to use the database of affiliations:
1.	To use the database, please download files "SEG_affiliations_data.sqlite" and "SEG_org_retrieve.py" in one folder.
2.	Run the file "SEG_org_retrieve.py" using the command prompt (>python SEG_org_retrieve.py) and follow the instructions.
