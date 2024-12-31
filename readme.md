# ReNews
ReNews is a Flask-based web application that fetches and displays news articles from various sources using the News API.

## Features
- Search for news articles by keyword
- Filters out buggy articles from Yahoo and articles with "removed" as a title
- Responsive interface using bootstrap
- Navigation bar sorted by topics

## Prereuisites
- Python 3.x
- Flask
- News API key
  
## Installation
1. Clone the repo
   '''
   git clone https://github.com/yourusername/insta-news.git
    cd insta-news
    '''

2. Create a virtual environment and activate it:
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
   '''
   pip install -r requirements.txt
   '''

4. Set up your News API key in config.py
   '''
   NEWS_API_KEY = "your_api_key_here"
   '''
