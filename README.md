# 🎬 IMDb Top 100 Movies Scraper Project
This IMDb Top 100 Movies Scraper project is perfect for you! In this project, we scrape IMDb’s list of the top 100 movies, extracting key details like movie titles, release years, ratings, and more. We’ll load this data into a Pandas DataFrame, analyze it, and export it as a beautifully structured CSV file.

Using Python’s requests library and BeautifulSoup, we will fetch IMDb's HTML content, extract meaningful movie attributes, and organize them into a clean and structured format for easy data manipulation and further analysis. 🚀

## 🚀 Project Breakdown:
Fetch IMDb Data: Start by calling the IMDb Top 100 Movies page using the requests library.
### 1. Extract Key Movie Attributes:
Parse the HTML using BeautifulSoup and extract essential details like:
1. 🎥 Movie Name
2. 📅 Release Year
3. ⏳ Runtime
4. ⭐ Ratings
5. 🏅 Metascore
6. 🗳 Number of Votes
7. 💰 Gross Budget
### 2. Organize Data: 
Structure all movie information in Python lists and create a Pandas DataFrame.
### 3. Data Cleaning: 
Use Pandas to clean and format the data, ensuring it's ready for analysis.
### 4. Export to CSV: 
Save the cleaned data as a CSV file (top_100_movies.csv) for future use.
## 🌟 Features:
1. Extracts titles, ratings, and more from IMDb’s Top 100 Movies.
2. Uses BeautifulSoup for web scraping and Pandas for data organization.
3. Data is cleaned, structured, and saved in a well-organized CSV file.
4. Script can be customized to scrape different IMDb movie categories or lists.
## 🛠️ Tech Stack:
1. **Python:** For coding the entire project.
2. **BeautifulSoup:** To parse and scrape IMDb’s web page.
3. **Requests:** To fetch HTML content from IMDb.
4. **Pandas:** For organizing and cleaning the data in a DataFrame.
5. **CSV:** To store the final movie data.
