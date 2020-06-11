## US Hospital

![images here](images url)

---

### Table of Contents

This README.md contains the following:

- [Description](#description)
- [Specification](#specification)
- [How to use](#how-to-use)
- [JSON Structure](#json-structure)
- [Screenshot](#screenshot)
- [Reference](#reference)
- [Author](#author)

---

## Description

In US, hospitals have their grade every 6 months. The grade determined by scores in 5 aspects: Infections, Problem with Surgery, Practices to Prevent Error, Safety Problems, and Doctor, Nurse & Hospital Staff. This is a project to scrap grade information from US Hospital published in www.hospitalsafetygrade.org using Pyhton 3.   

---

## Specification

We will need the following library to run the code in this project:

- ##### TQDM
Scraping takes a lot of time. In order to know whether our code is running or our computer has crashed, we will use TQDM. TQDM will show progress bar for a loop in our code, so we will know how far the loop has run.
> pip install tqdm
- ##### BeautifulSoup
There are some tools in Python to help the user when scraping webiste. In this project, we will use Beautifulsoup because it is user friendly and easy to understand.
- ##### Urllib
We will use urllib library to grab the HTML of webistes.
- ##### Time
In this project, we will grab HTML from many websites. In order to not crashing the server, we will put our program to sleep in each loop using Sleep() from Time library
- ##### JSON
Scraped data will be stored in JSON format. To dump the data into json, we will use JSON library.
- ##### Threading
Scraping takes a lot of time. In order to reduce the time taken in scraping, we can implement multithreading in our code. To implement multithreading, we need Threading library
- ##### Jupyter Notebook
The codes are in .ipynb. We can use Jupyter Notebook to open and run this code.
