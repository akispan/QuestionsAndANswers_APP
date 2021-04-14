# QuestionsAndANswers_APP

## Description:

This is a basic App created with Flask for users to upload a question and get the answer from expert-users. A user can sign up for this app and the user infrormations, questions and answers are stored in a database.

## Prerequisites:
This app is created in Pycharm and Python 3.7 is used.

## Database
Sqlite3 library is used for this app. After sqlite3 installation in your operation system in order to create the database, you need to open the terminal and put the next command:
sqlite3 questions.db < schema.sql , where schema.sql includes the rules for the database creation.

### The modules need to be installed are:
Flask

### The modules need to be importeds are:
Flask, render_template, request, g, session, redirect, url_for, connect_db, get_db, generate_password_hash, check_password_hash ,os

## DATA:

The data consist of the username and password from every user, the questions made from users and the answers that expert-users uploaded back.

## Authors
Akis Panagiotou

## Project
Created for online course "The Ultimate Flask course" from Udemy