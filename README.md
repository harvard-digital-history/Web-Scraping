# Web-Scraping

This repository contains materials for "Web Scraping", a workshop taught by the [Digital Scholarship Group](https://dsg.fas.harvard.edu) at Harvard University. 

The workshop teaches participants how to automate the extraction of data from websites and other online repositories into a well-formatted, locally stored dataset, for later analysis. Web scraping tools make the process of collecting large amounts of online information more efficient, and help automate an otherwise tedious, time-consuming, and error prone process. 

The workshop includes an introduction to web structures and provides direct, hands-on experience with a series of scraping techniques that run the gamut from simple to complex, including tools for batch file downloading, a full workflow using browser extensions only, and advanced HTML and DOM parsing techniques using Python.

## Workshop Plan

This is a two-day workshop with three hours of instruction on each day. You can find links to all the tools and resources mentioned during the workshop [here](/Documents/Resources.md), and the excersises are listed in [this page](/Documents/Exercises.md).

### Day 1

>[!IMPORTANT]
>You'll need a recent version of [Chrome](https://www.google.com/chrome/) and the [Web Scraper](https://webscraper.io) extension.

#### Introduction
- The structure of a web page
- Using *selectors* to target data
- The legal fine print

#### Scraping on the Browser
- Inspecting websites
- Batch downloading
- Introduction to [Web Scraper](https://webscraper.io)

#### Designing a scraper
- Structure of a scraper
- Basic selectors: 
    - text
    - link
    - image
    - HTML
    - table
- Advanced selectors: 
    - groups
    - generic elements
    - scroll
    - click
    - pagination

### Day 2

>[!IMPORTANT]
>You'll need a working installation of [Python](https://www.python.org) and [Jupyter Notebooks](https://jupyterlab.readthedocs.io/en/latest/user/notebook.html). Setup instructions for both can be found [here](https://github.com/harvard-digital-history/Introduction-to-Python/blob/main/Documents/Getting_started.md). You will also need to install [Selenium](https://www.selenium.dev) (a browser automation tool), following the [instructions here](/Documents/Setup_instructions.md).
>

>[!TIP]
> If you are not familiar with Python, or need a refresher, you may want to go over Unit 1 of [this workshop](https://github.com/harvard-digital-history/Introduction-to-Python).

#### Programmatic approaches
- Shortcuts
- Using APIs

#### HTML Parsing with BeautifulSoup

#### DOM Parsing with Selenium


