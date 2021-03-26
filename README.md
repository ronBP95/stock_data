# Stock Bot (Script)
We are going to create a script that retrieves, parses, and store stock data into a MongoDB database

Today, we will be making a script that will be analyzing data from [Wallmine](https://www.wallmine.com)

We need to do a couple of things before we start:
- Set up an account on [Wallmine](https://www.wallmine.com) (it's free)
**IMPORTANT**: Be sure to select ***Sign in with a password*** so you can have that for your *credentials*
- Create a repo if you want to display your work on your personal github or *fork* and *clone* this repo if otherwise
- Create a *.gitignore* file and input the following:
```text
.ipynb_checkpoints
__pycache__/    
credentials.py
```
- Create a *credentials.py* file and store your **email** and **password** from your Wallmine account here
```py
email = "your.email@email.com
password = "yourPassword12345"
```
- Create an *app.py* file add the below code snippet
```py
class StockData:
  def __init__(self):
     self.data = []
     self.urls = {}
     self.driver = webdriver.Chrome('/Users/romebell/downloads/chromedriver-4') # use your path to your Chromedriver
  
  def login(self):
    
  def retrieve_data(self): # get back all data
  
  def parse_data(self): # parse data into an array of objects -> returns items parsed
  
  def store_data(self): # -> store data in MongoDB database
  
  def view_stock(self, ticker): # -> 
  
  def compare_price(self, ticker): # -> 
 ```
