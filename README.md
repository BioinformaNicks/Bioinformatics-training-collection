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
    - [Bash](#Bash)
    - [Web Development](#Web-Development)
        - [Web Dev IDE](#Web-Dev-IDE)
        - [Web Dev Courses](#Web-Dev-Courses)
        - [Web Dev Books](#Web-Dev-Books)
    - [SQL](#SQL)
        - Work in progress 
- [Machine Learning](#Machine-Learning)
    - Work in progress 
- [General Computational Skills](#General-Computational-Skills)

# Programming
## Python
Python is one of the most versatile, powerful and easy-to-use programming languages. It is very well suited for Bioinformatics because of it's versatile light-weight nature, and it's extendability in the form of different (Bioinformatics-related) packages. These packages extend the capabilities of the language, adding new functionality.
### Python IDE
When learning and applying Python, code should be developed within an Integrated Development Environment (IDE). This is dedicated software for editing code, and for running the code.

Some of the more popular dedicated IDE's include:
- [Pycharm](https://www.jetbrains.com/pycharm/)
- [Spyder](https://www.spyder-ide.org/)
- [VSCode](https://code.visualstudio.com/)

Aside from these options, a recently popular method for editing and running code exists in the form of Jupyter Notebooks, or Jupyter Lab.
These are different from the above mentioned dedicated IDE's in the sense that these create an interactive 'Notebook' environment in which code can be ran inside separate cells, at separate moments. This is highly recommended for Data Science purposes, and can be a useful tool for (exploratory) data analysis in Bioinformatics.
This is thus mostly recommended for data analysis, and not for general programming purposes or for project purposes.
- [Jupyter](https://jupyter.org/)
### Python Courses
There are numerous sources to learn from, both free and paid. In this section, I will recommend several tutorials or MOOC's (Massive Open Online Courses).
- Paid
    - Udemy (Only buy courses when in sale - which is very often. Courses are in sale about every two-three days, for < 13 euro)
        - [Complete Python Bootcamp: From Zero to Hero](https://www.udemy.com/course/complete-python-bootcamp/) - I highly recommend this one. This is a very extensive course, starting at a slow pace but teaching indepth material. 
        - [Learning Python for Data Analysis and Visualisation](https://www.udemy.com/course/learning-python-for-data-analysis-and-visualization/)
        - [Python from A-Z: Python for Data Science](https://www.udemy.com/course/python-coding/)
        - [The Complete Python Course: Learn Python By Doing](https://www.udemy.com/course/the-complete-python-course/)
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on R, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
- Free 
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on R, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
    - [EDx](https://www.edx.org/learn/python)
    - Coursera
        - [Python for Genomic Data Science](https://www.coursera.org/learn/python-genomics)
        - [Python for Applied Data Science and AI](https://www.coursera.org/learn/python-for-applied-data-science-ai)

It is to be noted that although Udemy's courses are mostly paid, these are not directly linked to academic institutions. This is an advantage, as it gives instructors the ability to freely design their own courses instead of being bound to academic regulations for the order and content of teaching. Teachers on Udemy are often from the academia, however, and often have a PhD and experience in the field.

### Python Books
In this section, several E-books (or hardcover, depending on your liking) will be listed that could be useful references for learning Python.
Personally, I prefer online courses for learning and having books as quick references for looking things up quickly.
It is worth noting that the [Humble Bundle](https://www.humblebundle.com/) periodically has a Programming E-books bundle available for low pricing. These bundles often include books from reputable publishers and authors such as O'Reilly or Wiley. These bundles can include e-books for every programming language, or they can be language-specific.
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Fluent Python](https://github.com/fluentpython)
- [Python Cookbook](https://www.oreilly.com/library/view/python-cookbook-3rd/9781449357337/)
- [Learning Python](https://www.oreilly.com/library/view/learning-python-5th/9781449355722/)
- [Python for Data Analysis](https://www.oreilly.com/library/view/python-for-data/9781491957653/)
- [Bioinformatics Programming Using Python](https://www.oreilly.com/library/view/bioinformatics-programming-using/9780596804725/)
- [Mastering Python for Bioinformatics](https://www.oreilly.com/library/view/mastering-python-for/9781098100872/)

### Python Packages
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


## R
R is a language developed for statistical computation and graphical visualisation, although it is currently being expanded into a more versatile programming language.
It is gaining popularity in Bioinformatics due to it's capabilities for data science.
### R IDE
When learning and applying R, code should be developed within an Integrated Development Environment (IDE). This is dedicated software for editing code, and for running the code.

It is to be noted here that RStudio is the only recommended dedicated IDE since it's capabilities are enormous, and the team backing it is incredibly good.

It is, however, also possible to use R in Jupyter Notebooks by installing the IRKernel.
- [RStudio](https://rstudio.com/)
- [Jupyer](https://jupyter.org/)
- [IRKernel](https://github.com/IRkernel/IRkernel)
### R Courses
There are numerous sources to learn from, both free and paid. In this section, I will recommend several tutorials or MOOC's (Massive Open Online Courses).

- Paid
    - Udemy (Only buy courses when in sale - which is very often. Courses are in sale about every two-three days, for < 13 euro)
        - [Data Science and Machine Learning Bootcamp with R](https://www.udemy.com/course/data-science-and-machine-learning-bootcamp-with-r/)
        - [R Programming A-Z: R for Data Science](https://www.udemy.com/course/r-programming/)
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on R, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
- Free
    - [RStudio Primers](https://rstudio.cloud/learn/primers)
    - [EDX: Data science R Basics](https://www.edx.org/course/data-science-r-basics)
    - Coursera
        - [Genomics Data Science with R](https://www.coursera.org/specializations/genomic-data-science)
        - [Data Science Foundations with R](https://www.coursera.org/specializations/data-science-foundations-r)
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on R, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
        
It is to be noted that although Udemy's courses are mostly paid, these are not directly linked to academic institutions. This is an advantage over EDx and Coursera, as it gives instructors the ability to freely design their own courses instead of being bound to academic regulations for the order and content of teaching. Teachers on Udemy are often from the academia, however, and often have a PhD and experience in the field.  
### R Books
In this section, several E-books (or hardcover, depending on your liking) will be listed that could be useful references for learning R.
Personally, I prefer online courses for learning and having books as quick references for looking things up quickly.
It is worth noting that the [Humble Bundle](https://www.humblebundle.com/) periodically has a Programming E-books bundle available for low pricing. These bundles often include books from reputable publishers and authors such as O'Reilly or Wiley. These bundles can include e-books for every programming language, or they can be language-specific.

The RStudio team lists several books in their [resources section](https://rstudio.com/resources/books/). 
Out of these books, the following are highly recommended.
- [R For Data Science](https://r4ds.had.co.nz/)
- [Hands-on Programming with R](https://rstudio-education.github.io/hopr/)
- [Advanced R](https://adv-r.hadley.nz/)
- [Hands-on Machine Learning with R](https://bradleyboehmke.github.io/HOML/)
### R Packages
These packages extend the capabilities of the language, adding new functionality.
In this section, I will first sum up some of the more specific and useful bioinformatics-related packages, and then link to a general list of great packages.

The [Tidyverse](https://www.tidyverse.org/) is a collection of packages that will make R life infinitely easier. These packages provide incredible functions for data science.
It is maintained by the RStudio team, and the RStudio team provides several [cheatsheets](https://rstudio.com/resources/cheatsheets/) that will make learning the use of these packages easier.
Although included in the Tidyverse, [GGPlot2](https://ggplot2.tidyverse.org/) deserves a special mention as this provides beautiful data visualisation and graphical plots that can be easily customized. Several extensions to this package exist. For example, [ggsci](https://cran.r-project.org/web/packages/ggsci/vignettes/ggsci.html) is an important one as it allows for colors used in scientific journals. This is by far not the only one, and I recommend you look up more.
Additionally, it is worth mentioning that [Reticulate](https://rstudio.github.io/reticulate/), from the same team, provides a package that enables the combination of both R and Python in RStudio.

The [Shiny](https://shiny.rstudio.com/) package provides easy web application development, mostly in dashboard format, without the need for prior HTML/CSS/Javascript knowledge. It will handle every aspect of web development: the layout, structure and graphics using Shiny code, and the computation using R code.

- Compilation of more specific R packages:
    - [Awesome R](https://github.com/qinwf/awesome-R)

# Web Development
Web development is split into front-end and back-end sides. The front-end is what is known as the layout and styling, and what the user sees in their browser. The back-end is focused on the computation behind the website.
For front-end development, HTML and CSS are the most popular languages. HTML gives basic functionality, and provides structure and layout to the website. It is the backbone to the website. CSS, however, performs the styling for the website. Another popular tool is JavaScript, which extends the functionality enormously.
For back-end development, more general purpose programming languages can be used (R, Python, Java, etc). SQL Databases are often used as well.

Currently, several methods exist to reduce the need for front-end development knowledge by using back-end languages to develop the front-end.
These include:
- [R Shiny](https://shiny.rstudio.com/) - This R package will allow the usage of R code to develop HTML+CSS+JavaScript elements, while the R code handles the back-end computations.
- [Django](https://www.djangoproject.com/) - This Python package is similar to Shiny, although it requires more HTML+CSS+JavaScript knowledge. It is, however, more scalable.
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - This Python package, although very similar to Django, is more lightweight and easy to use. It is, however, not as scalable.
### Web Dev IDE
When developing websites using HTML and CSS, code is written inside a text editor or Integrated Development Environment (IDE).
- [Atom](https://atom.io/)
- [VSCode](https://code.visualstudio.com/)
- For R Shiny, code can be written in RStudio (see above). Similar for Python, Python webapps can be developed in Python IDE's.
### Web Dev Courses
- Paid
    - Udemy (Only buy courses when in sale - which is very often. Courses are in sale about every two-three days, for < 13 euro)
        - [The Complete Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
### Web Dev Books

# General Computational Skills
Aside from just learning how to program, there are a couple of general (often also called DevOps) tools that make the life of a programmer easier. These tools often focus on reproducibility of results, and teach/improve best practices in coding. For example, these tools range from workflow languages that automate input/output across different programming languages, to easy-to-use package management systems.
