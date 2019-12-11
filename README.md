# SEG_Annual
This repository includes data for the words and phrases frequency of occurrence analysis.
The database "grams.sqlite" includes the words and phrases that occurred during 38 Society of Explorational Geophysicists Annual Conferences (1982 - 2019). In the database we have only words that appear more than 15 times during the observatoin period.
Python programm "words_retrieve.py" can be used to retrieve necessary words from the database and plot the graph, wich will be saved as "figure.png" in the folder with the "grams.sqlite" and "words_retrieve.py".

To run the programm "words_retrieve.py" you need to install Python 3.7.2 
To browse the data in the "grams.sqlite" you need to install DB Browser for SQLite

How to use the database:
1) To use the database, please download files "grams.sqlite" and "words_retrieve.py" in one folder.
2) Run the file "words_retrieve.py" using command promt (>python words_retrieve.py) and follow the instructions.
