# Web-Scrapping-RottenTomatoes
This project focusses on scrapping te necessary data from the Rotten-Tomato website and saving in into an excel workbook.
Libraries used
- Beautiful Soup
- Openpyxl
- Requests

`Beautiful Soup` - this library is used to acquire the entire HTML code from the website into the working environment
`Openpyxl` -  to integrate python and excel environment by which the details generated from python code is stored in excel
`Requests`- for the process of sending HTTP requests and handling the corresponding responses

The details such as 
- Title of the movie
- Year of release
- Director of the movie
are obtained from the website.

Using BeautifulSoup, the HTML code is brought from website into jupyter environment from where certain functions such as `find()` is used to locate and extract the text inside the tag.
After obtaining the necessary informations, the collected data is stored into the excel workbook and is saved.
