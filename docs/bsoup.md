# Scraping Static Sites with Beautiful Soup

I'm going to scrape, and restructure the official WCAG 2.1 TR.

``` bash
pip install beautifulsoup4 requests
```

here's code I enter in the Python repl

``` python
from bs4 import BeautifulSoup as BSoup
import requests

wcag21 =  requests.get("")
```