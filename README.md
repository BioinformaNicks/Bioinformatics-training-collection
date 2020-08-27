# Bioinformatics-training-collection
A collection of resources for learning about tools and languages related to Bioinformatics

This page contains a curated list of resources for learning bioinformatic tools and programming languages related to it.
- Programming
    - [Python](#Python)
        - [Python IDE](#Python-IDE)
        - [Python Courses](#Python-Courses)
        - [Python Books](#Python-Books)
        - [Python Packages](#Python-Packages)
    - [R](#R)
        - [R IDE](#R-IDE)
        - [R Courses](#R-Courses)
        - [R Books](#R-Books)
        - [R Packages](#R-Packages)
    - [Web Development](#Web-Development)
        - [Web Dev IDE](#Web-Dev-IDE)
        - [Web Dev Courses](#Web-Dev-Courses)
        - [Web Dev Books](#Web-Dev-Books)
    - [SQL](#SQL)
- [Machine Learning](#Machine-Learning)
- Bioinformatics Tools


# Python
Python is one of the most versatile, powerful and easy-to-use programming languages. It is very well suited for Bioinformatics because of it's versatile light-weight nature, and it's extendability in the form of different (Bioinformatics-related) packages. These packages extend the capabilities of the language, adding new functionality.
## Python IDE
When learning and applying Python, code should be developed within an Integrated Development Environment (IDE). This is dedicated software for editing code, and for running the code.

Some of the more popular dedicated IDE's include:
- [Pycharm](https://www.jetbrains.com/pycharm/)
- [Spyder](https://www.spyder-ide.org/)
- [VSCode](https://code.visualstudio.com/)

Aside from these options, a recently popular method for editing and running code exists in the form of Jupyter Notebooks, or Jupyter Lab.
These are different from the above mentioned dedicated IDE's in the sense that these create an interactive 'Notebook' environment in which code can be ran inside separate cells, at separate moments. This is highly recommended for Data Science purposes, and can be an useful tool for (exploratory) data analysis in Bioinformatics.
This is thus mostly recommended for data analysis, and not for general programming purposes or for project purposes.
- [Jupyter](https://jupyter.org/)
## Python Courses
There are numerous sources to learn from, both free and paid. In this section, I will recommend several tutorials or MOOC's (Massive Open Online Courses).
Courses for specific packages will be listed under the Python Packages section.
- Paid
    - Udemy (Only buy courses when in sale - which is very often. Courses are in sale about every two-three days, for < 13 euro)
        - [Complete Python Bootcamp: From Zero to Hero](https://www.udemy.com/course/complete-python-bootcamp/) - I highly recommend this one. This is a very extensive course, starting at a slow pace but teaching indepth material. 
        - [Learning Python for Data Analysis and Visualisation](https://www.udemy.com/course/learning-python-for-data-analysis-and-visualization/)
        - [Python from A-Z: Python for Data Science](https://www.udemy.com/course/python-coding/)
        - [The Complete Python Course: Learn Python By Doing](https://www.udemy.com/course/the-complete-python-course/)
- Free 
    - [EDx](https://www.edx.org/learn/python)
    - Coursera
        - [Python for Genomic Data Science](https://www.coursera.org/learn/python-genomics)
        - [Python for Applied Data Science and AI](https://www.coursera.org/learn/python-for-applied-data-science-ai)

It is to be noted that although Udemy's courses are mostly paid, these are not directly linked to academic institutions. This is an advantage, as it gives instructors the ability to freely design their own courses instead of being bound to academic regulations for the order and content of teaching. Teachers on Udemy are often from the academia, however, and often have a PhD and experience in the field.

## Python Books
In this section, several E-books (or hardcover, depending on your liking) will be listed that could be useful references for learning Python.
Personally, I prefer online courses for learning and having books as quick references for looking things up quickly.
It is worth noting that the [Humble Bundle](https://www.humblebundle.com/) periodically has a Programming E-books bundle available for low pricing. These bundles often include books from reputable publishers and authors such as O'Reilly or Wiley. These bundles can include e-books for every programming language, or they can be language-specific.
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Fluent Python](https://github.com/fluentpython)
- [Python Cookbook](https://www.oreilly.com/library/view/python-cookbook-3rd/9781449357337/)
- [Learning Python](https://www.oreilly.com/library/view/learning-python-5th/9781449355722/)
- [Python for Data Analysis](https://www.oreilly.com/library/view/python-for-data/9781491957653/)

## Python Packages
These packages extend the capabilities of the language, adding new functionality.
In this section, I will first sum up some of the more specific and useful bioinformatics-related packages, and then link to a general list of great packages.

- [Numpy](https://numpy.org/) - This package provides a way to handle vectorized data, and lends itself for incredibly fast code for scientific projects.
- [Pandas](https://pandas.pydata.org/) - This package provides a way to handle tabular data in a very efficient manner.
- [Scikit-Learn](https://scikit-learn.org/stable/) - This package provides several statistical functions, as well as being the primary package for machine learning purposes.
- [Statsmodels](https://github.com/statsmodels/statsmodels) - This package provides several important statistical functionality.
- [Matplotlib](https://matplotlib.org/) - This package provides extensive plotting and visualisation functionality, and it can be beautified with [Seaborn](https://seaborn.pydata.org/).
- [Biopython](https://biopython.org/) - Biopython is a set of freely available tools for biological computation written in Python by an international team of developers.

- Compilation of more specific Python packages:
    - [Awesome Python Packages](https://github.com/vinta/awesome-python#readme)


# R
## R IDE
When learning and applying R, code should be developed within an Integrated Development Environment (IDE). This is dedicated software for editing code, and for running the code.

It is to be noted here that RStudio is the only recommended dedicated IDE since it's capabilities are enormous, and the team backing it is incredibly good.
It is, however, possible to use R in Jupyter Notebooks by installing the IRKernel.
- [RStudio](https://rstudio.com/)
- [Jupyer](https://jupyter.org/)
- [IRKernel](https://github.com/IRkernel/IRkernel)
## R Courses
There are numerous sources to learn from, both free and paid. In this section, I will recommend several tutorials or MOOC's (Massive Open Online Courses).
Courses for specific packages will be listed under the R Packages section.

- Paid
    - Udemy
        - [R Programming A-Z: R for Data Science](https://www.udemy.com/course/r-programming/)
        - [Data Science and Machine Learning Bootcamp with R](https://www.udemy.com/course/data-science-and-machine-learning-bootcamp-with-r/)
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on R, and you can get a free 3 months premium through a Github Educational account.
- Free
    - [EDX: Data science R Basics](https://www.edx.org/course/data-science-r-basics)
    - Coursera
        - [Genomics Data Science with R](https://www.coursera.org/specializations/genomic-data-science)
        - [Data Science Foundations with R](https://www.coursera.org/specializations/data-science-foundations-r)
        
It is to be noted that although Udemy's courses are mostly paid, these are not directly linked to academic institutions. This is an advantage, as it gives instructors the ability to freely design their own courses instead of being bound to academic regulations for the order and content of teaching. Teachers on Udemy are often from the academia, however, and often have a PhD and experience in the field.  
## R Books

## R Packages

# Web Development
## Web Dev IDE

## Web Dev Courses

## Web Dev Books
