# Lab 5
Fahim Rahman Talukder and Nafio Miah

This repo is a clone of https://github.com/nelaturuk/education_pathways. 

## Activity One 

Screenshot of the repository on GitHub:

![image](https://user-images.githubusercontent.com/59378799/197661669-cc37f127-d294-44aa-a35a-0f6f186306e2.png)

## Activity Two-Five

#### Home Page: 

![ECE444_Lab5_Act2_5_HomePage](https://user-images.githubusercontent.com/59378799/197919739-6622835b-c9ca-441c-a5f1-1ec6ffa9939a.JPG)

#### Results Page:

![ECE444_Lab5_Act2_5_ResultsPage](https://user-images.githubusercontent.com/59378799/197919758-131f9b64-217c-4d34-895e-92f4834d89c6.jpg)

#### Results Page Table:

![ECE444_Lab5_Act2_5_ResultsPageTable](https://user-images.githubusercontent.com/59378799/197919783-18cbbd8a-0428-4cb6-ad1f-b6599b3d178a.JPG)



# Contents from Original Clone

## CARTE Education Pathways

### Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

### Setup Instructions

#### With Docker



### Repository files:

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
