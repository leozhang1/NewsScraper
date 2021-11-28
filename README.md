## Thanks for using my script! This script brings you the current news from 7 different categories all in one excel file!
## The categies are ``` 'business', 'entertainment', 'general', 'health', 'science', 'sports', 'technology' ```

## You may filter certain categories to your own liking but I believe these are the current 7 offered by the news api

## Note that it is generally good practice to run this script in a virtual environment although you don't have to. There are many resources you can find online as to why it is better to do so.

Directions:
**Run this in terminal (assuming you're already in the directory containing NewsScraper.py)**
* ```python -m venv [VirtualEnvironmentName]``` (run this only once if you dont have one in the directory already)
* ```[VirtualEnvironmentName]\Scripts\activate.bat``` (execute this line)
* make sure you have all the dependencies you need in this virtual environment by typing ```pip install -r requirements.txt```
* ```python NewsScraper.py```

## The secrets.py module that I have imported is just my own personal information that I don't want to show to the public!

## What I can show is the boilerplate, so you can add your own (just don't forget to add secrets.py to your gitignore so you don't share information such as your news api key to the public)

secrets.py boilerplate
```
class Credentials:
    newsapiKey = [YourNewsAPIKey] (You can get your own key here https://newsapi.org/)
    outputFilePath = [YourDesiredDirectory] (The directory you want your output excel file to reside in)
```

## Enjoy!