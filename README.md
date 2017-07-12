# Article Auto Summarizer

This is a simple machine learning algorithm which scrapes a given URL to get article content, and auto-summarizes it.

#### Brief Descriptions of the algorithm

Currently, it has a function which can scrape a given URL of Washington Post, and return the article content. Then, using the NLTK corpus, it tokenizes all
the words and sentences, by ignoring common stop words. It then uses a frequency summarizer class to keep rack of the n-most frequently occurring words 
or sentences. Then, 3 of the most frequent sentences are printed as summary.

## Special Packages used

NLTK  
BeautifulSoup

## License

Open Sourced under the [MIT License](LICENSE)