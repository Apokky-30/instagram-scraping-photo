# Instagram Scraping Photo
Simple lines of Python code to scrape Instagram photos and videos.

##### instagram-scraper is a command-line application written in Python that scrapes and downloads an instagram user's photos and videos. Use responsibly.
![demo](https://user-images.githubusercontent.com/92684818/189487230-58263f86-6d74-43ea-bf35-154a77159645.gif)

### Install
To install instagram-scraper:  
```$ pip install instagram-scraper```

To update instagram-scraper:  
```$ pip install instagram-scraper --upgrade```  

Alternatively, you can clone the project and run the following command to install: Make sure you cd into the instagram-scraper-master folder before performing the command below.  
  
```$ python setup.py install```  

### Usage
To scrape a user's media:  
```$ instagram-scraper <username> -u <your username> -p <your password>```  
NOTE: To scrape a private user's media you must be an approved follower.  
  
By default, downloaded media will be placed in ```<current working directory>/<username>```.  
Providing username and password is optional, if not supplied the scraper runs as a guest. Note: In this case all private user's media will be unavailable. All user's stories and high resolution profile pictures will also be unavailable.  
  
To scrape a hashtag for media:  
```$ instagram-scraper <hashtag without #> --tag```  
  
It may be useful to specify the ```--maximum <#>``` argument to limit the total number of items to scrape when scraping by hashtag.  
  
To specify multiple users, pass a delimited list of users:  
```$ instagram-scraper username1,username2,username3```  
  
  
Code By [@apokky_](https://www.instagram.com/apokky_/)
    
