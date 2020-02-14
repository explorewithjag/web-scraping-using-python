# Web Scraping Using Python

Web scraping is a term used to describe the use of a program or algorithm to extract and process large amounts of data from the web. Whether you are a data scientist, engineer, or anybody who analyzes large amounts of datasets, the ability to scrape data from the web is a useful skill to have. Let's say you find data from the web, and there is no direct way to download it, web scraping using Python is a skill you can use to extract the data into a useful form that can be imported.

__Steps involved in web scraping:__

<ul>
<li>Send a HTTP request to the URL of the webpage you want to access. The server responds to the request by returning the HTML content of     the webpage. For this task, we will use a third-party HTTP library for python requests.</li>
  <li>Once we have accessed the HTML content, we are left with the task of parsing the data. Since most of the HTML data is nested, we        cannot extract data simply through string processing. One needs a parser which can create a nested/tree structure of the HTML data.</li>
  <li>Now, all we need to do is navigating and searching the parse tree that we created, i.e. tree traversal. For this task, we will be       using another third-party python library, Beautiful Soup. It is a Python library for pulling data out of HTML and XML files.</li>
</ul>


__This series contains a  deep-in understanding of different ways and elements you need to know for web scraping. Hope you will enjoy learning this, if so share this with others and for more such contents you can connect with me on__ 

YouTube: https://www.youtube.com/channel/UCmF8qppe02J1ot4Jfwl_lFg

LinkedIn: https://www.linkedin.com/in/jagwithyou/

Medium: https://medium.com/@jagwithyou
