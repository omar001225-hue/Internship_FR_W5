# Scraper — Stage 0

## Target classification

### Target

**Books to Scrape**
https://books.toscrape.com/

### Why this site?

Books to Scrape is specifically designed as a sandbox/demo website for practising web scraping. The parent site describes it as a safe place for beginners learning web scraping, and the Books to Scrape website itself states that it is a demo website for web scraping purposes.

### Scope

I will scrape **only the first 3 catalogue pages**.

Each catalogue page contains up to 20 books, so the maximum scope is 60 books.

### Data to collect

For each book, I will collect:

* Book title
* Price
* Availability
* Rating
* Book detail URL

### Robots.txt result

I requested:

`https://books.toscrape.com/robots.txt`

Result: **no robots file found** — the request returned **404 Not Found**.

A missing robots.txt file is not treated as permission by itself.

### Why this target is appropriate

This target is appropriate because it is explicitly provided as a web-scraping practice sandbox and is intended for developers and beginners to practise scraping.

I will not reuse this code on another site without checking its rules and terms first.
