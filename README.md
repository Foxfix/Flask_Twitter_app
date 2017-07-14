# Twitter app

This app works with Twitter API. There's a few steps in order to log in with Twitter.
The first thing is to create a consumer. The consumer is an object which represents our application.
Next is to create a client. The client get the access token.
If user has not yet been created, this app creates user and save it in the database. (Postgresql)
I use Twitter api to retrieve the latest tweets, what I searching.
After that I adding sentiment analysis with another API and noted tweets in different colors.

**$ git clone https://github.com/Foxfix/Flask_Twitter_app.git**
  
**$ cd Flask_Twitter_app**
  
In your virtualenv install 

**$ pip install -r requirements.txt**
  
Then run the app.py file. 

**$ python app.py**
  
Follow the http://127.0.0.1:4995/


  
  ![search](https://img-host.org.ua/images/1jvj.png)
  
  ![search](https://img-host.org.ua/images/2gkg.png)
