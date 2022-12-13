# Predict Customer Churn with Clean Code Principles

## Introduction
- In this project, you will implement your learnings to identify credit card customers that are most likely to churn. The completed project will include a Python package for a machine learning project that follows coding (PEP8) and engineering best practices for implementing software (modular, documented, and tested). The package will also have the flexibility of being run interactively or from the command-line interface (CLI).

## Project Description
This project will give you practice using your skills for testing, logging, and best coding practices from this lesson. It will also introduce you to a problem data scientists across companies face all the time. How do we identify (and later intervene with) customers who are likely to churn?

This is a project to implement best coding practices. You will not need to code for this project entirely from scratch.

We have already provided you the churn_notebook.ipynb file containing the solution to identify credit card customers that are most likely to churn, but without implementing the engineering and software best practices.

You will need to refactor the given churn_notebook.ipynb file following the best coding practices to generate these files:

churn_library.py
churn_script_logging_and_tests.py
README.md
## Instructions
High-Level Instructions
These are the three files you will need to complete after refactoring the churn_notebook.ipynb file:

churn_library.py
The churn_library.py is a library of functions to find customers who are likely to churn. You may be able to complete this project by completing each of these functions, but you also have the flexibility to change or add functions to meet the rubric criteria.

The document strings have already been created for all the functions in the churn_library.py to assist with one potential solution. In addition, for a better understanding of the function call, see the Sequence diagram on the next page.

After you have defined all functions in the churn_library.py, you may choose to add an if __name__ == "__main__" block that allows you to run the code below and understand the results for each of the functions and refactored code associated with the original notebook.

ipython churn_library.py
churn_script_logging_and_tests.py
This file should:

Contain unit tests for the churn_library.py functions. You have to write test for each input function. Use the basic assert statements that test functions work properly. The goal of test functions is to checking the returned items aren't empty or folders where results should land have results after the function has been run.

Log any errors and INFO messages. You should log the info messages and errors in a .log file, so it can be viewed post the run of the script. The log messages should easily be understood and traceable.

Also, ensure that testing and logging can be completed on the command line, meaning, running the below code in the terminal should test each of the functions and provide any errors to a file stored in the /logs folder.

ipython churn_script_logging_and_tests.py
Testing framework: As long as you fulfil all the rubric criteria, the choice of testing framework rests with the student. For instance, you can use pytest for writing functional tests.


## Files and data description
Overview of the files and data present in the root directory. 

All files are included in this directory 

## Running Files
How do you run your files? What should happen when you run your files?
$ python churn_library


Running the Test file churn_script_logging_and_tests.py

pytest churn_script_logging_and_tests.py

we excetued the steps below

Collectes the different test of the churn library functions
Runs these test.
Saves the log message into ./logs/churn_library_test.log



## Clean code results

This version of our code yield the following result using pylint and autopep8 commands

```
pylint churn_library.py
....
Your code has been rated at 8.62/10
```

```
pylint churn_script_logging_and_tests.py
....
Your code has been rated at 9.66/10

