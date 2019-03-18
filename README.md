# Instagram Clone

This is a clone of the popular App Instagram, 11/03/2019

## Author

Alex Ogola

## Description

#### This application allows its users to do the following

* Sign in to the application to start using.
* Upload my pictures to the application.
* See my profile with all my pictures.
* Follow other users and see their pictures on my timeline.
* Like a picture and leave a comment on it.


## Prerequisites
* Python3.6

## Installation steps
* $ git clone https://github.com/lex-of-pakawa/instagram
* $ cd gallery
* $ source virtual/bin/activate
* Install all the necessary requirements by running pip install -r requirements.txt (Python 3).

## create a database

* psql
* CREATE DATABASE gallery
* connect to the database \c instagram
* check if tables have been created \dt

## Run migrations

* python3.6 manage.py migrate
* python3.6 manage.py makemigrations instagram

## Running the app

* python3.6 manage.py runserver

## testing

* python3.6 manage.py test instagram


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
