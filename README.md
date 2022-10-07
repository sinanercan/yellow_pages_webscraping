# yellow_pages_webscraping
This project has been developed for web scraping from https://www.yellowpages.ca/ website. In order to use the programme, the chrome driver must be compatible with the related version of selenium package. For this reason, the lines between 3-10 in the script have been added so that the download and installation process can be performed automatically. The code asks the user to enter two different keywords to generate search results on the yellowpages page:

(1) A keyword what you want to search on yellowpages website (variable name: what).  You can browse yellowpages website first to determine what keywords you want to search on. Besides, the code does not sensitive upper and lower cases, and please do not include special characters in search results.
(2) A keyword where you want to search on yellowpages website (variable name: where).This variable helps you to restrict the search results for specific locations (e.g. a state or city). 

Note: In this script, entire searching results are listed and the informations listed below are scrapped from search results.Finally, the results are saved as ".csv" file. 
1- Category
2- Postcode
3- Province
4- City (if any)
5- Street
6- Name
7- Phone
8- Site (if any)
9- Review (if any)
