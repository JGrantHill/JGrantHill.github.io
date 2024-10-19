# Python

## What is Python?

Python is a free/open-source programming language, which is incredibly popular, partially because it is (relatively) easy to read and doesn't require the code compilation of some other languages, such as C. If you have 
a computer running macOS or Linux, it probably came with Python already installed. It can easily be installed on a Windows computer, and even if you're using it on Linux or macOS you may want to install a new version, rather than the system provided copy. More on that later. One of the reasons why Python is popular for data analysis is that it is interpreted (not compiled) and quick to use. If you're wanting to try things out by rapidly changing your code and visualising the data, Python is close to ideal.

This book doesn't aim to teach you the basics of Python. I will aim to find some resources that can help and link them here.

## Python Libraries/Packages

Another reason why Python sees a lot of use in analytics and data science is that there are many free libraries and/or packages that extend its capabilities for different applications. Some of these that are useful for sports analytics include:

| Package    | Brief summary                                                 |
|:-----------|:--------------------------------------------------------------|
| Pandas     | Used for working with data sets, a little like a spreadsheet. |
| Matplotlib | For plotting graphs.                                          |
| Selenium   | Tools for automating web-browser interactions.                |

## Installing Python and Libraries

There are loads of ways of installing Python and its most popular packages on to your computer, but perhaps the easiest is to use [Anaconda](https://anaconda.org). The Anaconda installer will provide you with a recent version of Python (make sure you select a Python 3 version of Anaconda) and most of the packages you will need. It also provides a convenient interface for installing most additional packages you might need.

Most experienced Python/Anaconda users will create an Anaconda environment specifically for the programming task they are working on. The Anaconda documentation has some information on how to [manage environments](https://docs.anaconda.com/navigator/tutorials/manage-environments/).

## Jupyter Notebooks

For the vast majority of my own basketball analytics, I use a Jupyter notebook within an Anaconda environment. A Jupyter notebook is an electronic document that provides you with an interactive Python environment. Not only does it give you somewhere to write and run your code, but it can also include explanatory text (including equations) and provides you with the output of your code, such as data and plots, all in one place. Typically, you will interact with a Jupyter notebook in your web-browser, but note this isn't some external website, it's all running on your computer and is not accessible to the outside world.

```{note}
It is possible to use Jupyter notebooks with programming languages other than Python, but that's beyond the scope of this quick introduction.
```

Several Chapters within this book are Jupyter notebooks that have been converted into a book/website form using [jupyter-book](https://jupyterbook.org/en/stable/intro.html), which I hope demonstrates how useful they can be.