# Codechef-Scraper

Given a CSV file having records with fields - **Name, Username (Handle), Rating** , the script reads the user names from the file, scrapes the web for the codechef rating of the corresponding user and writes the results back to the same CSV file. The results are sorted in descending order based on the rating of users and  preserving the same order of the fields.


## Introduction

Codechef is a competitive coding platform which tests the ability of a programmer to write efficient code for the given problems. It was created as a platform to help programmers make it big in the world of data structures, algorithms, computer programming and programming contests. CodeChef revives the geek in you through the medium of competitive programming. They conduct monthly programming contests and have been working constantly to better the programming scenario in India. Today the CodeChef community has grown to over 1,000,000+ programmers from different parts of the globe. They also help organisations connect with developers, brand their products in the developer community and recruit. 

## Packages Required

 - selenium
 - bs4
 - csv
 - socket
 - requests
 >**Note**: You need to install ChromeDriver - Web Driver for Chrome before you run the script. This repository uses ChromeDriver for Linux, so download the appropriate one for your OS. Latest version can be found [here](https://chromedriver.chromium.org/downloads).

## Usage

Download this repo and make sure you have the CSV file in the same directory as the **main.py** file and has been named as **Codechef-Ratings.csv**.

### Running the script
	python3 main.py

## References

 - [Selenium](https://selenium-python.readthedocs.io/)
 - [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
 - [socket](https://docs.python.org/3/library/socket.html)
 - [requests](https://requests.readthedocs.io/en/master/)

## License
![ ](https://img.shields.io/github/license/Akshaykoushik06/Codechef-Scraper)
