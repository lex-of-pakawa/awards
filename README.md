# Awards

A web application where developers can submit their projects and have their peers review these projects. Projects are reviewed based on usability, design and content.

## Author

Alex Ogola

## Description

#### This application allows its users to do the following

* View posted projects and their details.
* Post a project to be rated/reviewed.
* Rate/review other users' projects.
* Search for projects.
* View projects overall score.
* View my profile page Projects will be rated/reviewed based on the following criteria.
* Design - This is the overall appearance of the project.
* Usability - This can be translated to the user experience and how responsive the project is.
* Content - This includes the technologies used.


## Prerequisites
* Python3.6

## Installation steps
* $ git clone https://github.com/lex-of-pakawa/awards
* $ cd gallery
* $ source virtual/bin/activate
* Install all the necessary requirements by running pip install -r requirements.txt (Python 3).

## create a database

* psql
* CREATE DATABASE gallery
* connect to the database \c awards
* check if tables have been created \dt

## Run migrations

* python3.6 manage.py migrate
* python3.6 manage.py makemigrations awards

## Running the app

* python3.6 manage.py runserver

## testing

* python3.6 manage.py test awards


## Technologies Used

#### This project uses major technologies which are :
* HTML5
* CSS
* Bootstrap4
* Python3.6
* django
* jQuery

## Behaviour driven development
| Behaviour   |      Input     |  Output |
|----------|:-------------:|------:|
| User Sign In | Enter user details on sign in page |   Account and profile created |
| Edit profile | Click "Edit profile" button on profile page |   Enter details |
| User Log In | Enter user details on log in page |   User redirected to the profiles page upon successful log in |
| Follow other users | Visit profiles page |   Click "follow" button |
| Display Images | Visit the timeline page |   User can view Images in cronological order |
| Like Image | Click on the "heart shaped" icon at the bootom of a picture |   Like is recorded |
| Expand Image | Click on image |   Expanded Image on an individual page |
| View More Details | Expand Image |  More details appear on the right side of the expanded image |


## License

* MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.*
