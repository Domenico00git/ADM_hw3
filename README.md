Algorithmic Methods of Data Mining (Sc.M. in Data Science) - Homework 3
Team Members
Riccardo Corrente (ID: 1964746)
Branescu Ana Carina (ID: 2125078)
Saif Ali (ID: 1936419)
Repository Contents
The repository contains the submission for the third homework of the "Algorithmic Methods of Data Mining" course, Group #22.

Files
main.ipynb

Jupyter notebook with solutions to all the questions. Cells are pre-executed.
functions/

A folder containing all the .py files used in main.ipynb to enhance readability and code deployment efficiency. Includes:
crawler.py: Web crawler sending HTTP requests.
parser.py: Bot scraping information from the website to create the working dataframe.
engine.py: Module with functions creating the search engine for Q2.
functions.py: Module with functions imported into main.ipynb to solve the questions.
map_courses.html

The map obtained as the result of Q4, displaying universities filtered through Q3 using the query 'data science'.
CommandLine.sh

Command line scripts used to answer the questions.
CommandLine_output.png

Image showing the outputs of the command line scripts.
Outputs
Q1
Q1 outputs/
A folder containing outputs of Q1:
course_links.txt: File with 6000 URLs of Master Degrees, scraped from the MSc Degrees Website.
file_tsv.zip: Zip file containing 6000 .tsv files for each Master Degree with scraped information.
unique_tsv_file.tsv: Merged .tsv file from the 6000 files. Importing this file in main.ipynb creates the dataframe used for subsequent questions.
master_programs_html.7z: Zip file containing 6000 HTML pages of Master Courses, organized in 400 folders with 15 pages each.
Q2
Q2 outputs/
Folder containing outputs of Q2, including vocabularies used to solve Q2 and enable the engine to work:
inverted_index_1.json
inverted_index_tfidf.json
vocabulary.json
Suddivision of Exercises
Q1: Riccardo
Q2: Saif
Q3: Riccardo
Q4: Riccardo
Q5: Ana
Q6: Saif
Q7: Ana
Notebook and Repository Organization
Riccardo
