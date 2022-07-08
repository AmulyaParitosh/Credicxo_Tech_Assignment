# Credicxo_Tech_Assignment

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AmulyaParitosh/Credicxo_Tech_Assignment/blob/master/main.ipynb)


## Hello evaluators, following are the points explaining my approach towards solving the assignment.
### **Main Assignment** :
- Downloaded the csv files containing Asin and country
- Wrote script to generate URLs form the data
- Visited some urls and inspected the elements
- Made a basic script for extracting :-
	- Title
	- Image url
	- Price
	- Details
- Encountered errors
- Analysed errors and found different classes, ids, etc are required for different types of sites
- Edited script with try-except blocks to handle different requirements for different sites
- Once working properly, refine the output string by removing unwanted spaces and characters from them.
- Made functions for each data
- Ran the script and found that amazon was blocking me for excessive calls
- Tackled this problem by changing part of header after every 100th url

**For Bonus 1:**
- Once the data was being saved in JSON file properly, added function to store same data in Mysql database table

**For Bonus 2:**
- Added open in colab button on very top of the Jupytr notebook and also in Readme

### **Bonus Task:**
- Opened and analysed the given Amazon url to bypass
- Searched ways to extract captcha code from captcha image
- Found a API amazoncaptcha 
- Used selenium to download the image
- Then extracted the captcha from it
- Used selenium to find captcha fill box and filled the extracted captcha in it and submitted to bypass the Amazon Captcha Page. 

### **Time taken for each 100 URLs :-**
- 82 sec
- 82 sec
- 70 sec
- 66 sec
- 72 sec
- 63 sec
- 73 sec
- 56 sec
- 64 sec
- 53 sec