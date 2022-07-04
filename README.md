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
        - [Bash Courses](#Bash-Courses)
        - [Bash Books](#Bash-Books)
    - [Web Development](#Web-Development)
        - [Web Dev IDE](#Web-Dev-IDE)
        - [Web Dev Courses](#Web-Dev-Courses)
        - [Web Dev Books](#Web-Dev-Books)
    - [SQL](#SQL)
        - Work in progress 
- [Machine Learning](#Machine-Learning)
    - [Machine Learning in R](#Machine-Learning-in-R)
        - [ML in R Courses](#ML-in-R-Courses)
        - [ML in R Books](#ML-in-R-Books)
        - [ML in R Packages](#ML-in-R-Packages)
    - [Machine Learning in Python](#Machine-Learning-in-Python)
- [General Computational Skills](#General-Computational-Skills)
- [Bioinformatics Tools and Resources](#Bioinformatics-Tools-and-Resources)

# Programming
## Python
[Python](https://www.python.org/) is one of the most versatile, powerful and easy-to-use programming languages. It is very well suited for Bioinformatics because of it's versatile light-weight nature, and it's extendability in the form of different (Bioinformatics-related) packages. These packages extend the capabilities of the language, adding new functionality.

To program using [Python](https://www.python.org/), you will first need to download an [Python](https://www.python.org/) distribution and then (preferably) download an Integrated Development Environment (IDE) to write code in. Alternatively, if using [conda](https://docs.conda.io/en/latest/) (see [Environment and package management systems](#Environment-and-package-management-systems)), [Python](https://www.python.org/) comes pre-installed.

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
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on Python, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
- Free 
    - [Datacamp](https://www.datacamp.com/) has a lot of courses on Python, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
    - edX
        - [Learn Python](https://www.edx.org/learn/python)
        - [Using Python for research](http://rafalab.github.io/pages/harvardx.html)
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
- [Biopython](https://biopython.org/) - Biopython is a comprehensive set/repository of freely available packages for biological computation written in Python by an international team of developers.

- Compilation of more specific Python packages:
    - [Awesome Python Packages](https://github.com/vinta/awesome-python#readme)


## R
[R](https://www.r-project.org/) is a language developed for statistical computation and graphical visualisation, although it is currently being expanded into a more versatile programming language.
It is gaining popularity in Bioinformatics due to it's capabilities for data science.

To program using [R](https://www.r-project.org/), you will first need to download an [R](https://www.r-project.org/) distribution and then (preferably) download an Integrated Development Environment (IDE) to write code in. Alternatively, if using [conda](https://docs.conda.io/en/latest/) (see [Environment and package management systems](#Environment-and-package-management-systems)), you can install R through this.

### R IDE
When learning and applying R, code should be developed within an IDE This is dedicated software for editing code, and for running the code.

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
    - [STAT447 by the University of Illinois](https://stat447.com/lectures/03-rbasics/). A recent course by [Dirk Eddelbuettel](https://stat.illinois.edu/directory/profile/deddel) of the Department of Statistics, University of Illinois which provides a dive into R basics and beyond, in addition to providing some information on the RStudio environment and [General Computational Skills](#General-Computational-Skills).
    - edX
        - [Data science R Basics](https://www.edx.org/course/data-science-r-basics)
        - [Data Analysis for the Life Sciences](http://rafalab.github.io/pages/harvardx.html)
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

The [Big Book of R](https://www.bigbookofr.com/) by [Oscar Baruffa](https://twitter.com/OscarBaruffa) is a comprehensive repository of **free** books for R, divided into different subjects and fields (thanks for the suggestion [Mikhael Dito Manurung](https://twitter.com/mikhaeldito313))

In addition, these bioinformatics domain-specific books could be of use:
- [Hands-on Machine Learning with R](https://bradleyboehmke.github.io/HOML/)  
- [PH525x series - Biomedical Data Science](http://genomicsclass.github.io/book/). This is a course about learning R, basic statistics and genomics by Prof. Rafael Irizarry and Prof. Michael Love. 
- [DIY.transcriptomics](https://diytranscriptomics.com/). Another great learning material about R and transcripomics by Prof. Dan Beiting.
### R Packages
These packages extend the capabilities of the language, adding new functionality.
In this section, I will first sum up some of the more specific and useful bioinformatics-related packages, and then link to a general list of great packages.

- The [Tidyverse](https://www.tidyverse.org/) is a collection of packages that will make R life infinitely easier. These packages provide incredible functions for data science.
It is maintained by the RStudio team, and the RStudio team provides several [cheatsheets](https://rstudio.com/resources/cheatsheets/) that will make learning the use of these packages easier.
Although included in the Tidyverse, [GGPlot2](https://ggplot2.tidyverse.org/) deserves a special mention as this provides beautiful data visualisation and graphical plots that can be easily customized. Several extensions to this package exist. For example, [ggsci](https://cran.r-project.org/web/packages/ggsci/vignettes/ggsci.html) is an important one as it allows for colors used in scientific journals. This is by far not the only one, and I recommend you look up more.
Additionally, it is worth mentioning that [Reticulate](https://rstudio.github.io/reticulate/), from the same team, provides a package that enables the combination of both R and Python in RStudio.
- Similar to [Biopython](https://biopython.org/), there is also an extensive repository for open-source computational biology software packages curated by the [Bioconductor](https://www.bioconductor.org/) initiative.
- [naniar](https://cran.r-project.org/web/packages/naniar/vignettes/getting-started-w-naniar.html). This package is very useful for exploring your data, and checking missingness of your data.
- [patchwork](https://patchwork.data-imaginist.com/). This package allows combining and arranging separate ggplots in an easy manner.
- The [Shiny](https://shiny.rstudio.com/) package provides easy web application development, mostly in dashboard format, without the need for prior HTML/CSS/Javascript knowledge. It will handle every aspect of web development: the layout, structure and graphics using Shiny code, and the computation using R code.  
- The [ggpubr](https://rpkgs.datanovia.com/ggpubr/) package provides some easy-to-use functions for creating and customizing ggplot2- based publication ready plots.  
- Compilation of more specific R packages:
    - [Awesome R](https://github.com/qinwf/awesome-R)

# Bash
Although some will hate me for this, I usually refer to Bash as both a Unix/Linux terminal and as a 'form' of a programming language, or rather, 'a command language'.
So first things first: what is a terminal? A terminal, or shell, is a program that takes commands and sends them to the operating system to perform. If you're familiar with Microsoft Windows CMD or PowerShell, this is an example of a shell or terminal, although much less powerful and easy to use as Bash. Now Bash (Bourne Again Shell) is the default terminal shell for most Linux/Unix-based operating systems, and it is very very powerful. There are some alternatives, such as Zsh, which are gaining popularity (due to amazing plugins for it, google it), however bash is still the most commonly used. Most Bioinformatics or Computational Biology programs have been written to be executable on a command line interface (the terminal, or shell), usually often in bash. In addition, bash comes with a lot of pre-installed applications that might be considered command languages by itself as well (awk, sed, for example), making it very powerful. Furthermore, it's functionality is extendable with other software packages.

Most Linux/Unix distributions come pre-installed with bash, and MacOS used to have bash as the default terminal as well, although it switched to Zsh.
Microsoft Windows, however, is an exception. It does not come pre-installed with bash at all. In fact, until quite recently, users had to find workarounds on using it (Dual booting, for example). Currently, however, the Microsoft-supported [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install) feature enables Microsoft Windows users to run a Linux kernel that supports the usage of Bash.

To install Bash on a Microsoft Windows OS, users will be first required to install [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install). Next, users will be required to install the [Ubuntu terminal](https://www.microsoft.com/en-us/store/p/ubuntu/9nblggh4msv6) from the Microsoft Store. Interested readers can check out this small [guide](https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview). Once Ubuntu is installed, and set up, users are free to use the bash-default Ubuntu terminal.

### Bash Courses
There are numerous sources to learn from, both free and paid. In this section, I will recommend several tutorials or MOOC's (Massive Open Online Courses).
- Paid
    - Udemy (Only buy courses when in sale - which is very often. Courses are in sale about every two-three days, for < 13 euro)
        - [Linux Shell Scripting: A Project-Based Approach to Learning](https://www.udemy.com/course/linux-shell-scripting-projects/)
        - [Linux Administration: The Complete Linux Bootcamp for 2022](https://www.udemy.com/course/master-linux-administration/). This course goes far beyond the required knowledge on bash that is usually necessary for computational biology, but is an exceptional resource for those that want to learn Linux (system) administration.
    - [Datacamp](https://www.datacamp.com/) has some courses on Bash, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.
- Free 
    - [Sandbox.bio](https://sandbox.bio/). This webbrowser-based application lets users interactively learn the use of several common Bioinformatics tools, without requiring an installation. Aside from that, it lets you learn the terminal / bash commands in an interactive manner. Similar webbrowser-based applications might exist, and might be worth a google-fu.
    - [Linuxjourney](https://linuxjourney.com/). This is a small text-based course, and for learning Bash, it is advisable to complete the Grasshopper section.
    - [Ryan's Linux tutorial](https://ryanstutorials.net/linuxtutorial/). Great resource for beginners.
    - Coursera
        - [IBM's Hands-on Introduction to Linux Commands and Shell Scripting](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting). It should be noted that this course is offered by IBM, a major computer hardware and software company. This might possibly be one of the better courses out there.
    - edX
        - [Introduction to Linux](https://www.edx.org/course/introduction-to-linux)
        - [Linux Commands & Shell Scripting](https://www.edx.org/course/linux-commands-shell-scripting)
        - [Shell Programming - A necessity for all Programmers](https://www.edx.org/course/shell-programming-a-necessity-for-all-programmers)
     - [Datacamp](https://www.datacamp.com/) has some courses on Bash, and you can get a free 3 months premium through a Github Educational account. Use at own moral risk: DataCamp has been implicated in a sexual harassment scandal.

It is to be noted that although Udemy's courses are mostly paid, these are not directly linked to academic institutions. This is an advantage, as it gives instructors the ability to freely design their own courses instead of being bound to academic regulations for the order and content of teaching. Teachers on Udemy are often from the academia, however, and often have a PhD and experience in the field.

### Bash Books
In this section, several E-books (or hardcover, depending on your liking) will be listed that could be useful references for learning Bash.
Personally, I prefer online courses for learning and having books as quick references for looking things up quickly.
It is worth noting that the [Humble Bundle](https://www.humblebundle.com/) periodically has a Programming E-books bundle available for low pricing. These bundles often include books from reputable publishers and authors such as O'Reilly or Wiley. These bundles can include e-books for every programming language, or they can be language-specific.

Good Bash or shell scripting books include:
- [Data Science at the Commandline](https://datascienceatthecommandline.com/). Free goodness.
- [Classic Shell Scripting](https://www.oreilly.com/library/view/classic-shell-scripting/0596005954/)
- [Learning the Bash Shell](https://www.oreilly.com/library/view/learning-the-bash/0596009658/)

# Web Development
Disclaimer: I'm not very well-versed in web development, and only have experience in using R Shiny. Approach this section with a grain of salt.
Web development is split into front-end and back-end sides. The front-end is what is known as the layout and styling, and what the user sees in their browser. The back-end is focused on the computation behind the website.
For front-end development, HTML and CSS are the most popular languages. HTML gives basic functionality, and provides structure and layout to the website. It is the backbone to the website. CSS, however, performs the styling for the website. Another popular tool is JavaScript, which extends the functionality enormously.
For back-end development, more general purpose programming languages can be used (R, Python, Java, etc). SQL Databases are often used as well.

Currently, several methods exist to reduce the need for front-end development knowledge by using back-end languages to develop the front-end.
These include:
- [R Shiny](https://shiny.rstudio.com/) - This R package will allow the usage of R code to develop HTML+CSS+JavaScript elements, while the R code handles the back-end computations.
- [Dash](https://github.com/plotly/dash) - This Python package is similar to Shiny, and enables users to build a dashboard app without too much HTML+CSS+JS knowledge. Thanks to [heyyyjude](https://github.com/heyyyjude) for adding.
- [Streamlit](https://github.com/streamlit/streamlit) - Another Python package to build a dashboard app (similar to Shiny). Thanks to [heyyyjude](https://github.com/heyyyjude) for adding.
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

# Machine Learning
## Machine Learning in R

## Machine Learning in Python

# General Computational Skills
Aside from just learning how to program, there are a couple of general (often also called DevOps) tools that make the life of a programmer easier. These tools often focus on reproducibility of results, and teach/improve best practices in coding. For example, these tools range from workflow languages that automate input/output across different programming languages, to easy-to-use package management systems.

While this repo will introduce you to several tools and concepts, for further reading I encourage you to take a look at the following resources:
- [Pieter Moris's Computational Primer](https://pmoris.github.io/computational-skills/#/). This includes several of the topics introduced in the [General Computational Skills](#General-Computational-Skills) section.
- [Ming Tommy Tang's Github repo for computational biology](https://github.com/crazyhottommy/getting-started-with-genomics-tools-and-resources)

Aside from these resources, there is actually a highly recommendable course that includes some of these computational skills:
- [The Missing Semester of Your Computer Science Education](https://missing.csail.mit.edu/)
In addition, the following book is Bioinformatics-specific and is a very comprehensive resource for some of these computational skills:
- [Bioinformatics Data Skills](https://www.oreilly.com/library/view/bioinformatics-data-skills/9781449367480/)

A recent course by [Dirk Eddelbuettel](https://stat.illinois.edu/directory/profile/deddel) of the Department of Statistics, University of Illinois provides an R-focused dive into some computational skills:
- https://stat447.com/lectures/

## Project-based workflows
Every coding project will of course be saved in a directory, and often divided into multiple subdirectories. However, unless you structure it properly, it can get quite messy. Luckily, there are several recommendations for optimal project structure. It should be noted, however, that you are of course free to adapt and improvise as you see fit. This is often in your best interest, as this allows you to easily find back important files.

### Recommendations
- [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)
- [Structuring R Projects](https://www.r-bloggers.com/2018/08/structuring-r-projects/)

### Templates
- [Data Science Project Template for R](https://community.rstudio.com/t/data-science-project-template-for-r/3230)

## Reproducibility and automated workflows
In addition to working in a project-based workflow, a reproducible workflow language could be of benefit. This means creating reproducible and automated pipelines with languages such as Make, Snakemake, Nextflow, etc. 

- [Bioinformatics pipeline from the bottom up](https://ricomnl.com/blog/bottom-up-bioinformatics-pipeline/). This post gives a great example of how to go from scripts to fully automated and reproducible pipeline. From scripts, to Make, to Nextflow.

## Environment and package management systems
- [conda](https://docs.conda.io/en/latest/). This is a 'package and environment management system', which basicly means it lets you create 'virtual environments'. This lets you easily switch between versions of installed packages or versions of Python/R/any other supported languagge. In addition, it allows the management of version conflicts (program A might depend on a version of program B, but program C might depend on a different version of program B), by creating two different environments (one where program A and B are installed, one where program B and C are installed). The conda website itself hosts a short tutorial on how to get started with [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html). Conda comes in two versions:
    - [Miniconda](https://docs.conda.io/en/latest/miniconda.html). This is a minimal install, including only the barebones of conda (conda, Python and dependents).
    - [Anaconda](https://docs.conda.io/projects/conda/en/latest/glossary.html#anaconda-glossary). Anaconda includes conda, Python, several open-source scientific packages that are included in the Anaconda Repository and also the Anaconda Navigator (a Graphical User Interface), enabling you to interact with conda without a command line interface.
- [renv](https://rstudio.github.io/renv/articles/renv.html). Unlike conda, this is not a system-wide package and environment manager, and also does not include any Python or R distribution. No, renv is specifically focused on being a package dependency manager for the R programming language. Similar to conda, it will create virtual environments, however, it does this only for R on a project-linked manner.

## Version control
Have you ever dealt with the problem of updating features in a programming script, and having to save it as a new file called script_v2.py, only to end up having version 9001 and not knowing what was changed in each version? Or have you ever broken a function in a script, and now you can not figure out how to restore it? That's where version control systems come in. In brief, you can ask a version control system to takes snapshots of a repository (a project folder you want to track for updates). This will get saved, and you are able to restore and move between versions of a file easily. Think of this as the Microsoft Office or Google Docs version control, but on steroids. For a better explanation, I refer the reader to [Atlassian](https://www.atlassian.com/git/tutorials/what-is-version-control).

Although there are multiple version control systems, the most popular one is definitely [Git](https://git-scm.com/). This should not be confused with GitHub (on which this repository is hosted). Git is the version control system, and GitHub is basicly just an online hoster of Git repositories. Think of GitHub as OneDrive or Google Drive, but for Git repositories.

Some resources on learning how to use [Git](https://git-scm.com/) are:
- [Short GitHub Git Intro](https://docs.github.com/en/get-started/using-git/about-git)
- [Pro Git Book hosted on Git website itself](https://git-scm.com/book/en/v2)
- [Tutorial by Atlassian](https://www.atlassian.com/git/tutorials/setting-up-a-repository)
- [Git Gud Primer by Pieter Moris](https://pmoris.github.io/git-gud/#/)

## Containerization
Briefly, containerization tools allow you to package (and run) a script (or software tool) in a container (duh). This container is an isolated sandbox that runs on your host (local) operating system (OS). The container will not only contain the application itself, but also all of its dependencies, including a (stripped-down) operating system. There are several benefits to this. Firstly, this enables you to run software without installing it or the dependencies. Next, it also allows you to transfer applications across operating systems, and makes your script or application reproducible on other machines than your own.

The most popular containerization tool is [Docker](https://www.docker.com/).

Some resources on learning how to use [Docker](https://www.docker.com/) are:
- [Pieter Moris's Primer on Docker](https://pmoris.github.io/docker-primer/)
- [Docker Curriculum for Beginners](https://docker-curriculum.com/)

## Cloud Computing for Bioinformatics
This section was added per suggestion by [Lynn Langit](https://github.com/lynnlangit).

- [Lynnlangit's Google Cloud Platform for Bioinformatics](https://github.com/lynnlangit/gcp-for-bioinformatics)
- [Public Clouds for Genomics](https://github.com/lynnlangit/TeamTeri/tree/master/5_Public_Cloud_Genomics)

# Bioinformatics Tools and Resources
While it would be an impossible(!) task to introduce all Bioinformatics tools in this section, I will refer the reader to some tutorials for common Bioinformatics applications.

Resources:
- [Harvard Bioinformatics Core](https://hbctraining.github.io/main/). Collection of training resources for bioinformatics, including R/Python/Bash workshops and Next Generation Sequencing stuff.
- [Sandbox.bio](https://sandbox.bio/). This webbrowser-based application lets users interactively learn the use of several common Bioinformatics tools, without requiring an installation.
- [An Introduction to Applied Bioinformatics](http://readiab.org/introduction.html). This book gives users a brief introduction to Bioinformatics.
- [A Primer for Computational Biology](https://open.oregonstate.education/computationalbiology/). This book teaches Unix/Linux (Bash), Python and R to Computational Biologists in a very concise manner.
- [Twitter Thread on Bioinformatics Resources](https://twitter.com/randomdan1el/status/1392007202202865664)
- [Ming Tommy Tang's Bioinformatics One-Liner Repo](https://github.com/crazyhottommy/bioinformatics-one-liners). Useful list of one-liners that are highly functional.
