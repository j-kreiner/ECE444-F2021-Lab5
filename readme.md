Justin Kreiner

This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
![alt text](./screenshots/activity1.png)

## Activity 2-5

Home Page:
![alt text](./screenshots/home-page.png)

Results Page:
![alt text](./screenshots/results-page.png)

Results Table:
![alt text](./screenshots/results-table.png)

## Activity 6

The new results table is significantly more usable than the old one. By adding borders, it is clear which row and column each field belongs to. Also, the small addition that locks the table header fields will prevent the user from having to scroll up and down to match items to a particular header.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
