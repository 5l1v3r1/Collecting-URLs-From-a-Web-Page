# Collecting URLs From a Web Page
In this script, we want to find and collect URLs from a target web page. Many web pages not only include full URLs but also they include tags also. So, while scrapt the URLs it doesn't be ignored this details.

In this script, we both collect full URLs and tags from the target web page. Then, start to find and collect new URLs from web pages which we reach from target web pages. Namely, we continue to collect URLs in a loop. Also we note down if a web page doesn't include any URL and continue the other URL.

While this study. we prefer to save the URLs in a dataframe instead of list or something else. And finally we save the result in a CSV file.

We use;
- pandas
- urllib
- BeautifulSoup
