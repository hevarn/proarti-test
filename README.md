# Test
## Introduction
The goal is to test your skills, and the way you approach development issues.

You must use Symfony5.4 php8.1 or newer and apply all best practice. (Pattern, code style, ...)

To achieve the project you must fork the project and create a pull request.

Good luck and have fun ;)

PS: To run the project, you can install docker + docker-compose and run "make reset"

## Exercise 1 - Load CSV file
Create a command line, and a web page that allow us to load CSV File in a database with doctrine.

bin/console app:csv-load data_exam.csv

(The model should be like : [diag_object.png](diag_object.png))

Then display all lines in the web page in html table.

behat test exercice_1.feature should pass to validate the exercise.

## Exercise 2 - Create an API
You have to create a rest API that allow to:

***GET***
* total amount donations
* ... fill free to expose what you know

***POST/PUT***
* project
* reward
* person
* donation

You have to use ApiPlatform.

all behat test exercice_2.feature should pass to validate the exercise.

## Exercise 3 - Create a front application
You have to create one or multiple page to display what you loaded from database through the API.

Bonus: use VueJS
