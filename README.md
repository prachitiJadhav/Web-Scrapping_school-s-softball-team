# Web-Scrapping_school-s-softball-team
This project aims to collect the information of players and coaches in a school's softball team using web scraping techniques. The starting point is the roster page of the team website, which is then processed with the BeautifulSoup library to extract relevant information and store it in a structured format. The final output is a list of dictionaries, where each dictionary summarizes the information of a single player or coach. The information includes their names, positions, heights, classes, high school, hometown, and for coaches, their title, email, and phone number. The result of the project can be presented in different forms, such as a data frame or a .csv file. The goal of this project is to demonstrate the use of web scraping to retrieve data from websites and present it in a usable form.
Steps to collect player information from the website:

    1. Import the necessary libraries (in this case, bs4 and requests).
    2. Define the URL of the website to scrape.
    3. Send a GET request to the URL and store the response in a variable (in this case, text_1).
    4. Create a BeautifulSoup object with the response content and specify the parser to use (in this case, html5lib).
    5. Use the prettify method to view the HTML structure of the page in a readable format.
    6. Extract all the URLs in the page using a list comprehension and store it in a variable (in this case, all_urls_1).
    7. Iterate through the URLs and check if the URL is relevant to the player information.
    8. Extract the player information from the relevant URL and store it in a dictionary.
    9. Store all the player information in a list of dictionaries.
    10. (Optional) Write the player information to a .csv file for easy access.
