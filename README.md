# URL Crawler

Python scripts for sampling a slice of a crawl list (such as Alexa Top 1M), crawling through each site and fetching the internal links for each site.

## Usage instructions

### Preparations

Setup a Python 3 venv with the required modules:

```
./setup-python-venv.sh
```

Activate the Python 3 venv:

```
source venv/bin/activate
```

### Crawl URLs

This will fetch Alexa Top 10k, crawl through each site and gather one depth of internal links. The results will be saved in `./data`. 

```
python gather_internal_links.py
```
