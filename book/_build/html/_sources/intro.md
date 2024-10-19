# SLB Data and Analytics

## An Introduction to Data Scraping and Analysis with Super League Basketball

Most sports have undergone a data and analytics revolution. Whether it's the story of the Oakland A's baseball
team's trail-blazing approach conveyed in Moneyball (either the book or movie), or eXpected Goals stats popping up
on screen when you're watching football/soccer, it feels like it is everywhere. In this book I aim to show how
basketball data can be obtained from websites ("scraped"), and how that data can be subsequently used to analyse
the performance of teams and players. As a basketball fan based in the United Kingdom, the focus will be on
[Super League Basketball](https://www.superleaguebasketballm.co.uk).

The main tool I'll be using throughout is the Python programming language, with code examples embedded within the
pages. When it comes to scraping data, it's also handy to know a little [HTML](https://en.wikipedia.org/wiki/HTML), which is the markup language used in building websites.

Writing this book is very much a hobby project for me. I am not a professional basketball analyst, nor am I
a professional coder. There are almost certainly better ways of doing the same things that I will attempt to show,
although I will aim to make code as readable as possible for someone who is in the process of learning Python.
Right now, I consider this a "living book" and I will add new content to it as and when I find the time. If 
you have any suggestions for topics, or how I could improve what is already here, please get in touch.

Most of all, I hope you have fun discovering trends and insights into your favourite teams and players.

## What is Scraping?

Scraping is extracting/harvesting data, usually from a website. While some sports/leagues (such as the NBA) make their data easily accessible via an API, in other cases you may need to extract it from the data displayed on a website. While you could do this by copy/pasting data into a spreadsheet, this is likely to be far too tedious for all but they most patient of us. Depending on how the data is structured on a website, and how complex the website is, this can take a deal of *trial and error*. Effectively, we are trying to automate that copy/pasting of the information into a spreadsheet.

In this book, we will explore how to scrape SLB data using Python, and then focus on analysing that data. In principle, this data could be analysed with spreadsheet software or other tools, but we will also use Python.

## Running the Code

While it is possible to learn something about data scraping and analysis simply by reading the pages in this book,
it is recommended that you run some of the code to learn about the concepts and make modifications to suit your
own interests. My recommended way to do this would be to install/use Python with the required packages. These
can usually be obtained through [Anaconda](https://anaconda.org). See the [Python Chapter](python.md) for a few more details.

Please remember that the code provided in this book is for fun/educational purposes only. There may be errors in
code, or the websites that host the data may change. I don't provide any guarantees that any of the code will work.
It is up to you to evaluate the code, and this is especially the case if you make any changes to it.

## Table of Contents

```{tableofcontents}
```

## Recent Changes

- Initial version of the site, mostly me learning how to use jupyter-book to make a website/book.

## Want to Work Together on this Book?

If you'd like to contribute to this book, please get in touch. I'm happy to have others contribute.

## Planned Future Updates

- Scraping team efficiency data from BritHoops and analysing it via plots.
