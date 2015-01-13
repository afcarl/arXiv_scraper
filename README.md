arxiv_scraper
==============

This is a modification of the arXiv here:
http://arxiv.org/help/api/user-manual#python_simple_example

I changed it to query the server to retrive all abstracts (not pdfs!) from articles
of a given category. 

I used it to create the dataset for our machine learning class's Kaggle competition: 
http://inclass.kaggle.com/c/abstract-classification

Command line usage is: arXiv.py category max_results
Example: arXiv.py stat 5000

This is free software.  Feel free to do what you want
with it, but please play nice with the arXiv API!