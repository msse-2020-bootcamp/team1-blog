---
layout: post
title: "Separating Code into Modules and Python Testing using pytest"
author: Jasmine Hakim-Elahi
---
In the first two days of the MSSE bootcamp, our team has written the first version of working Monte Carlo simulation code by using the Python Standard Library.  The first version of the Monte Carlo simulation code exists in a Jupyter notebook file and a simulation can be run by executing the code in the Jupyter notebook.  Today, we further expanded upon this project by moving the code into different modules and making it into a small python package.  We also checked the behavior of the functions in the Monte Carlo simulation code by using the pytest, the testing framework used for Python testing.

#Separating Code Into Modules
The first thing we did today was separate our Monte Carlo simulation code into modules.  We created a new .py file in which we listed the statements used to import our libraries at the top of the file and added the function definitions below the import statements.  We gathered all of this information in a single cell in a Jupyter notebook.  
We then moved the code from the Jupyter notebook into a text editor so that we could separate our Monte Carlo simulation code into three modules based on function types.  The first module contains functions concerning atomic coordinates, the second module contains functions concerning energy calculations, and the third module contains functions related to the Monte Carlo simulation.  
Separating the code into modules enables the Monte Carlo simulations to be run more cleanly.  

#Python Testing Using pytest
Another task our team undertook today was creating testing frameworks for the functions in our Monte Carlo code.  Software tests work by comparing the expected output of the code with the observed output, enabling us to check the behavior of the code.  Up until this point, we have tested our functions by using assert statements.  Although they can work in a pinch to check the behavior of a function, writing assert statements to test code is an inefficient and error prone process.  
We have successfully improved our function testing today by writing new tests and running them using pytest, the testing framework for Python.  
The pytest testing framework allows us to write all of our test and execute them all at once, creating a testing suite that allows us to easily test our code.
