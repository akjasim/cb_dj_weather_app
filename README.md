# Build a Weather App in Django | Scrape Weather Data from Google | Beautiful Soup | Python Requests
See detailed project tutorial in YouTube:

English : https://youtu.be/-gzUIPyBRJg

Malayalam : https://youtu.be/MB_3eFKyq38

## Request Headers

```python
USER_AGENT = "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/44.0.2403.157 Safari/537.36"
LANGUAGE = "en-US,en;q=0.5"
session = requests.Session()
session.headers['User-Agent'] = USER_AGENT
session.headers['Accept-Language'] = LANGUAGE
session.headers['Content-Language'] = LANGUAGE
```
