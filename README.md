# Flask-News-App
A web application which uses Flask framework and python to fetch the daily news from news websites.
Using BeautifulSoup for scraping the data and metadata such as 'title', 'description', 'published time', etc from the [xml](https://www.cnet.com/rss/all/) file of news website.
Used Semantic UI in place of CSS to make website more attractive. Added semantic segment, container, button, etc in Html file. 


### To run website on localhost:
1. Run app.py 
2. copy and paste url http://127.0.0.1:5000/ in any browser.


## Output Images:
![ss](https://user-images.githubusercontent.com/61473947/100522987-d9172d00-31d2-11eb-912f-36bd15ce85c6.jpg)
![ss2](https://user-images.githubusercontent.com/61473947/100522991-e7fddf80-31d2-11eb-8b14-351bdb8286f4.jpg)



### websites used for scraping data:
1. Original website: https://www.cnet.com/news/
2. xml data of website: https://www.cnet.com/rss/all/


### Technology used:
1. Python
2. Flask framework
3. Web scraping using BeautifulSoup
4. Html 
5. Semantic UI 


### Features that can be added to this project are:
1. We can deploy our web app on multiple cloud platform like aws, azure, heroku,etc for everyone.
2. We can sql database for storing the data.


### Tip: Make your own server.
For serving this website to all local users, use your IP address and change
   
   **app.run()** to  **app.run(host='190.154.XXX.X',port ='8000')** in __**app.py**__ file.

