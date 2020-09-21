# Scrapy-worldometer-population-scrap

There are several tools available for web scraping, such as lxml, BeautifulSoup, MechanicalSoup, Scrapy, Python Requests and others. Among these, Scrapy and Beautiful Soup are popular among developers.

Scrapy is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages.
## Scraping With Scrapy

*Using pip*
If you just want to install scrapy globally in your system, you can install scrapy library using the python package ‘pip’. Open your terminal or command prompt and type the following command.

> pip install scrapy

*Using Conda*
If you want scrapy to be in your conda environment just type in and execute the following command in your terminal

> conda install -c conda-forge scrapy

create scrapy project diretory:

![setup image](https://raw.githubusercontent.com/Trinkesh/scrapy-worldometer-population-scrap/master/scrapy%20setup.png)

[worldometer](https://www.worldometers.info/world-population/population-by-country/) website used for scarping world population.

## now Inspecting the Web with Chrome's DevTools
You can open the DevTools by going to the menu and selecting View -> Developer -> Developer Tools.

Or better yet, use the keyboard shortcut: ctrl + shift + i
inspecting HTML/CSS elements 
and also have to disable java script of webiste for inspection simply use shortcut ctrl + shift + p an search box will appears search for javascript and disable it.

### now open the project directory in command prompt.
![fatch](https://raw.githubusercontent.com/Trinkesh/scrapy-worldometer-population-scrap/master/scrapy%20shell.png)

some of the websites for performing synatax featch selecting css/xpath-
**jsoup** is an interactive demo for jsoup that allows you to see how it parses HTML into a DOM, and to test CSS selector queries.
[jsoup](https://try.jsoup.org/)

**XPath** stands for XML Path Language. It uses a non-XML syntax to provide a flexible way of addressing (pointing to) different parts of an XML document.
It can also be used to test addressed nodes within a document to determine whether they match a pattern or not. 
[xpath-playground](https://scrapinghub.github.io/xpath-playground/)

use your choice python IDE and give command to scarping file for what kind of data you want to collect. 

as we understand which syntax giving us the right data we can perfrom scraping opration into your project file.

