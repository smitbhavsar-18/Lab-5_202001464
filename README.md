# Lab-5_202001464
# IT314 - Software Engineering

Name : Smit P. Bhavsar

Student id : 202001464

## **LAB 5 : Static Analysis**

- I used tool mypy for static analysis.
- installation of mypy code pip install mypy

![image](https://user-images.githubusercontent.com/107932317/227485267-188e32fb-5398-4e1a-9951-51a3152985b2.png)


## Static analysis

- github repository :  https://github.com/cs91chris/flask_errors_handler
- Static analysis on any file using mypy.
- Code:python -m mypy filename

1.File name : version.py

output: 

![image](https://user-images.githubusercontent.com/107932317/227483937-f766a67a-7845-4ff1-bf7d-9ee156534b9e.png)

2.File name : normalize.py

output:

![image](https://user-images.githubusercontent.com/107932317/227484299-236dfd5d-3de5-462e-8837-c7aece834118.png)

3.File Name : exception.py

output:

![image](https://user-images.githubusercontent.com/107932317/227484496-37aa9ef0-f189-4072-8942-37c64cf1a619.png)

4.File Name : handler.py

output:

![image](https://user-images.githubusercontent.com/107932317/227484782-d3f4350c-32d0-4165-8d42-aa87f96252d6.png)

5.File Name : dispatchers.py

output:

![image](https://user-images.githubusercontent.com/107932317/227484938-fbcd4f7e-4ea1-4e29-9557-93c5b42c4291.png)

- Most of the errors are of missing libraries. So whenever we use that library that is not present then it gives an error of no module found.

## About mypy tool

- mypy is a static type checker for Python. It acts as a linter that allows you to write statically typed code, and verify the soundness of your types.
- Mypy has a strict mode that enables a number of additional checks.
- It is very useful in analyzing python code. It shows errors and warnings so we can solve the problem.
