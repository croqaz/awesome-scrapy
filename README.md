
# Scrapy Awesomeness ![Awesome list](https://badgen.net/badge/icon/awesome?icon=awesome&color=purple&label)

[Scrapy](https://scrapy.org) is a free application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing, or historical archival.

The Scrapy documentation can be found at [scrapy.readthedocs.io](https://scrapy.readthedocs.io).

To understand what these things mean, take a look at the [Scrapy Architecture Overview](https://scrapy.readthedocs.io/en/latest/topics/architecture.html).


## Spiders

* https://github.com/llonchj/scrapy-sentry - A python library that glues Sentry with Scrapy. Any spider errors will get pushed to Sentry.
* https://github.com/zachgoldstein/scrapy-statsd - Statsd integration middleware for Scrapy. All statistics get sent to Statsd.
* https://github.com/scrapy-plugins/scrapy-deltafetch - Middleware to ignore requests to pages containing items seen in previous crawls of the same spider. The database is BsdDb3.
* https://github.com/TeamHG-Memex/scrapy-crawl-once - Middleware to avoid re-crawling pages which were already downloaded in previous crawls. The database is Sqlite3.
* https://github.com/scrapy-plugins/scrapy-querycleaner - Middleware to clean up query parameters in request URLs.
* https://github.com/andrewbaxter/scrapy-errbackdupefilter - Middleware that causes dropping duplicate requests trigger the errback.


## Item pipelines

* https://github.com/orangain/scrapy-s3pipeline - Pipeline that stores items into S3 bucket in JSONLines format. Uploads items to S3 by chunk while crawler is running. Supports GZip compression.
* https://github.com/sebdah/scrapy-mongodb - MongoDB item pipeline inserts the items to MongoDB as soon as the spider finds data to extract.
* https://github.com/TeamHG-Memex/scrapy-kafka-export - Writes crawled items to to a Kafka topic.
* https://github.com/scrapy-plugins/scrapy-jsonschema - Schema validation pipeline and Item builder using JSON Schema.


## Schedulers

* https://github.com/rmax/scrapy-redis - Redis-based requests queue scheduler.
* https://github.com/scrapinghub/scrapy-frontera - Flexible and featured Frontera scheduler.


## Downloader middlewares

* https://github.com/scrapinghub/scrapy-autoextract - Integrates ScrapingHub's AI Enabled Automatic Data Extraction into a Scrapy spider using a downloader middleware. The middleware adds the result of [AutoExtract](https://scrapinghub.com/autoextract) to response.meta['autoextract'] for consumption by the spider.
* https://github.com/scrapy-plugins/scrapy-crawlera - Crawlera middleware for Scrapy.
* https://github.com/scrapy-plugins/scrapy-splash - Scrapy & JavaScript integration through Splash.
* https://github.com/TeamHG-Memex/scrapy-rotating-proxies - Use rotating proxies, check that they are alive and adjust crawling speed.
* https://github.com/aivarsk/scrapy-proxies - Processes requests using a random proxy from list to avoid IP bans.
* https://github.com/clemfromspace/scrapy-selenium - Handles javascript pages using selenium.
* https://github.com/alecxe/scrapy-fake-useragent - Random User-Agent middleware based on fake-useragent.
* https://github.com/croqaz/scrapy-count-filter - Stops requests after a number of pages, or items are scraped.
* https://github.com/croqaz/scrapy-link-filter - Filter requests with "allow", or "deny" regex rules.
* https://github.com/ArturGaspar/scrapy-delayed-requests - Downloader middleware that delays a request by a number of seconds.
* https://github.com/povilasb/scrapy-html-storage - Scrapy downloader middleware that stores response HTMLs to disk.


## Extensions

* https://github.com/scrapinghub/spidermon - Tools for data validation, stats monitoring and notification messages.
* https://github.com/andrewbaxter/scrapy-settingsdumper - Scrapy extension that logs effective settings at both the crawler and spider level.
* https://github.com/andrewbaxter/scrapy-httplogging - Scrapy extension that logs all HTTP requests and responses.
* https://github.com/ejulio/spider-feeder - Scrapy extension to help loading input files for Scrapy spiders.


## Helpful libraries

* https://github.com/scrapinghub/dateparser - Parse localized dates in almost any string format and convert them to DateTime objects.
* https://github.com/scrapinghub/price-parser Extract price amount and currency symbol from a raw text string.
* https://github.com/scrapinghub/extruct - Extract embedded metadata from HTML markup. Supports HTML Microdata, Microformats, JSON-LD and Facebook's Open Graph.
* https://github.com/TeamHG-Memex/html-text - Deep extract text from HTML.
* https://github.com/scrapinghub/js2xml - Converts Javascript code to an XML document. This makes it easy to extract data embedded in JavaScript code using XPath.
* https://github.com/BurnzZ/scrapy-loader-upkeep - An alternative to the built-in ItemLoader of Scrapy which focuses on maintainability of fallback parsers.


## Frameworks

<!-- TwoFold.js sort lines -->
<sortLines>

* [AutoExtract](https://scrapinghub.com/autoextract) - AI Enabled Automatic Data Extraction. E-commerce and Article extraction at scale.
* [Portia](https://github.com/scrapinghub/portia) - Visually scrape websites without any programming knowledge required. Annotate a web page to identify the data you wish to extract, Portia will understand based on these annotations how to scrape data from similar pages.
* [Scrapely](https://github.com/scrapy/scrapely) - Library for extracting structured data from HTML pages. Given some example web pages and the data to be extracted, Scrapely constructs a parser for all similar pages.

</sortLines>


## Related Lists

* [github.com/scrapy/scrapy/wiki](https://github.com/scrapy/scrapy/wiki)
* [github.com/michael-yin/awesome-scrapy](https://github.com/michael-yin/awesome-scrapy)
* https://awesome-python.com/#web-crawling-web-scraping


## Scrapy examples

<!-- TwoFold.js sort lines -->
<sortLines>

* https://doc.scrapy.org/en/latest/intro/examples.html
* https://github.com/eloyz/reddit
* https://github.com/geekan/scrapy-examples
* https://github.com/mjhea0/Scrapy-Samples
* https://github.com/croqaz/scrapy-quotes

</sortLines>

-----

## License

Unlicensed aka Public Domain. See [UNLICENSE](/LICENSE) for details.
