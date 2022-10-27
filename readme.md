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

## Activity 6 - US1
#### User Story: As a student, I want to have detailed and relevant course information for a specific course so that I can make informed decisions on what courses I want to take.

![444_Lab5_Activity6_VisibleCourseInfoUserStory](https://user-images.githubusercontent.com/50860386/198172818-18fdcb27-5404-45c3-83d1-3ba3b91c3027.JPG)

## Activity 6 - US2
#### User Story: As a student, I want to know which courses are relevant for certain minors so that I can make course selection decisions based off the minor I want to complete.

![444_Lab5_Activity6_MinorUserStory](https://user-images.githubusercontent.com/50860386/198172925-0d89ca4b-ad0e-4185-a338-71f9b29bf3e8.JPG)

## Activity 6 - US3
#### User Story: As an adminstrator, I want the ability to edit the information that is present on the webpage for a specific course so that students have the most accurate and up-to-date information.

![444_Lab5_Activity6-AdminAccess](https://user-images.githubusercontent.com/59378799/198186919-0f7d3ac0-fcef-4b56-844d-b66ad7cf5904.png)


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
