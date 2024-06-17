## Why do we need Unit Testing?
As you begin to expand to larger multi-file projects it becomes important to have tests in place.
This way as you make changes to update your code, you can run test files to make sure previous code still runs as expected.

## Unit Testing Tools:
There are several testing tools, we will focus on two:

# pylint: 
This is a library that looks at your code and reports back possible issues like possible errors and styling.

# unittest:
This built-in library will allow to test your own programs and check you are getting desires outputs.


## Installation
Install pylint library by using cammand on Terminal or Window cmd window:

pip install pylint


## Usage for pylint

Save your file with some error on your code. Let say your file name "my_example.py"

# to run:
pylint my_example.py 
-above cammand list basic issues without report.
   
pylint my_example.py -r y
-above cammand list basic issues with report.

## Usage for unittest
Just run like regular python file.

python my_example.py



  



 
