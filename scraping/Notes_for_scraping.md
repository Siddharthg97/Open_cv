***Note :Refer bookmarks links***  <br />
***Approaches*** <br />
1)Selenium,ulib,request for extracting html file and beautifulsoup for data extraction <br />
2)Langchain based approach Asynchromium_document with beatufulsoup for data extraction <br />

## Libraries and their usecases for web scrapping <br />
1) Request to get access to a url link and returns the response object.( https://www.w3schools.com/python/ref_requests_get.asp ) <br />
2) 
## 1) Language detection <br />
   i)detect :libraries to detect language fast-langdetect,langdetect,textblob,lingua. <br />
     1. fast-langdetect or fasttext-langdetect - https://github.com/LlmKira/fast-langdetect  https://pypi.org/project/fasttext-langdetect/ <br />
     2. https://www.geeksforgeeks.org/detect-an-unknown-language-using-python/ <br />
     3. https://medium.com/@monigrancharov/text-language-detection-with-python-beb49d9667b3 <br />
   ii)There are language detection and there probability predicted for it. <br />
   iii)If text contains multiple languages, then use split_lang. Refer link - https://github.com/DoodleBears/split-lang/blob/main/split-lang-demo.ipynb
   
## 2)library newspaper can be used for extraction of data. <br />
   i) refer link :https://newspaper.readthedocs.io/en/latest/ <br />
   Newspaper can be used to extract data from url, html/text.


## 3) Pdf from url link extraction followed by u<br />
    https://www.geeksforgeeks.org/downloading-pdfs-with-python-using-requests-and-beautifulsoup/

## 4) Pdf to image and image to content


***Steps to perform scraping :*** <br />
1.Runing the request library to get response  <br />
2.Now based on response status code i.e. 200 use newspaper library to perform scraping.  <br />
--- For content is html/text is content  <br />
3.Parallely also soup the response html from resquest library.  <br />
4.Now using try except to filter out document from soup output using 3 ways -   <br />
  i. using id, class and other tags 
  refer following link - https://www.geeksforgeeks.org/how-to-scrape-websites-with-beautifulsoup-and-python/
  ii.
  iii.
---- For content is image/web <br />


---- For content is pdf <br />


***Scraping links***
basics knowledge - https://github.com/rajat4665/web-scraping-with-python/blob/master/Web%20Scraping%20with%20BeautifulSoup.ipynb