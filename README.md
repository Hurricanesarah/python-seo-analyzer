Python SEO Analyzer
===========

A small SEO tool that analyzes the structure of a site, crawls the site, count words in the body of the site and warns of any general SEO related issues.

Requires Python 2.7+, BeautifulSoup4, minidom, nltk, numpy and urllib2.

Installation
------------

### PIP

```
pip install -r requirements.txt
```

### Python Shell

```
>> import nltk
>> nltk.download()
```

Usage
-----

If you run without a sitemap it will start crawling at the homepage

```
./analyze.py http://www.domain.com/
```

Or you can specify the path to a sitmap to seed the urls to scan list.

```
./analyze.py http://www.domain.com/ path/to/sitemap.xml
```