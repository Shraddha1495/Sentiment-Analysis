
# Sentiment Analysis on Yelp.com


## Author

- Shraddha Khadepatil


## About Project

The purpose of this project is to perform the Sentiment Analysis on Yelp.com. The Web Scrapping is carried out using the Python library BeautifulSoup and scraped all the customer reviews from the Yelp.com website. 

## Built with

Jupyter Notebook
## Python Version

Python 3.10.2
## Pre-requisites

To run this project, the following libraries should be installed and imported successfully

pip install numpy

pip install pandas

from transformers import AutoTokenizer, AutoModelForSequenceClassification
import torch
import requests 
from bs4 import BeautifulSoup
import re
