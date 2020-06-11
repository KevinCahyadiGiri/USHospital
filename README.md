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
> pip install tqdm

Scraping takes a lot of time. In order to know whether our code is running or our computer has crashed, we will use TQDM. TQDM will show progress bar for a loop in our code, so we will know how far the loop has run.
- ##### BeautifulSoup
> pip install beautifulsoup4

There are some tools in Python to help the user when scraping webiste. In this project, we will use Beautifulsoup because it is user friendly and easy to understand.
- ##### Urllib
> pip install urllib3

We will use urllib library to grab the HTML of webistes.
- ##### Time
In this project, we will grab HTML from many websites. In order to not crashing the server, we will put our program to sleep in each loop using Sleep() from Time library. Time library is standard library in Python so it is already installed along with Python.
- ##### JSON
Scraped data will be stored in JSON format. To dump the data into json, we will use JSON library. JSON is also standard library in Python so it is already insalled along with Python.
- ##### Threading
Scraping takes a lot of time. In order to reduce the time taken in scraping, we can implement multithreading in our code. To implement multithreading, we need Threading library. Threading is also standard library in Python so it is already installed along with Python.
- ##### Jupyter Notebook
> pip install notebook

The codes are in .ipynb. We can use Jupyter Notebook to open and run this code.

---

## How to Use

Before we get started, make sure you have a stable internet connection to prevent error when running the code. <br/> <br/>

1. Clone this repository to your local directory. 
> git clone https://github.com/KevinCahyadiGiri/USHospital.git
2. Open Jupyter Notebook and open Hospital.ipynb
Open Jupyter Notebook by open your terminal in your local directory and type: `jupyter notebook`
3. Run the code on Jupyter Notebok

---

## JSON Structure

The scraped data will be saved in JSON. The JSON structure is :

---

## Screenshot

![normalization](/screenshot/normalization.png)
![saving-to-json](/screenshot/saving-to-json.png)
![scrapping-tqdm](/screenshot/scrapping-tqdm.png)

