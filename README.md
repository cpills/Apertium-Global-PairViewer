# Ling073-Final

Welcome to the repo for my 3D Apertium Pairviewer! This project was made as a final for my Computation Linguistics class. The page is a simple way of visualizing the language pairs currently in Apertium (and also the language pairs worked on for the class).

Information about each of the files:
apertium-languages.tsv -- This file contains the coordinates of certain languages in Apertium.
apertiumPairs.json -- Contains all of the pair data and point data used
index.html -- HTML and CSS
languages.json -- Contains mappings from ISO language codes to full language names
ling073Pairs.json -- Contains the data for only the pairs created in-class
pairs.json.txt -- Contains the information used by the Apertium pairviewer
pairviewer.js -- Body of the page
places.json -- Example data that I used when starting out
trimpairs.py -- Short Python script that scrapes the pairs.json.txt and the apertium-languages.tsv file. Creates a trimmed set of the Apertium data (only the language pairs that have coordinates in the tsv file). Writes the information to the apertiumPairs.json file
world-110m.json -- Country data used for generating the globe



To learn more about the project, you can look at the wiki page https://wikis.swarthmore.edu/ling073/User:Cpillsb1/Final_project

To learn more about Apertium, visit the Apertium website https://www.apertium.org/
