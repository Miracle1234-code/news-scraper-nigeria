# Nigerian News Scraper

This is a beginner-friendly web scraping project using Python and Google Colab that fetches news headlines from top Nigerian news websites, filters them by specific keywords (e.g., Nigeria, Lagos, Tinubu, etc.), and saves the results to a CSV file.

---

# Tools Used

- Google Colab
- Python
- `requests` and `BeautifulSoup` for scraping
- `pandas` for handling the data
- `csv` for saving output

---

# News Source

We are scraping from:  
**[Punch Newspaper - Latest News](https://punchng.com/topics/news/)**

---

# Project Logic

1. Get the HTML from the Punch newspaper's "News" section
2. Use BeautifulSoup to parse and extract the headlines
3. Filter the headlines based on keywords like:
   - `"Nigeria", "Lagos", "Tinubu", "Election", "Naira", "Fuel"`
4. Save filtered headlines to a `.csv` file

---

# How to Run

You can open the code in **Google Colab** and run step-by-step:

# Step-by-step Instructions:

1. Install and import libraries  
2. Fetch HTML from the website  
3. Extract news headlines  
4. Filter headlines using keywords  
5. Save the filtered headlines to CSV  
6. (Optional) Display the filtered results in table format

---

#  Sample Output
| Headline |
|----------|
| NDLEA arrests wanted drug kingpin, recovers drugs in Lagos hotel |
| Tinubu visits Ogun ahead of prayer event |
| Smuggling: Indian police seize $4m drugs from Nigerian woman |
| Behind the metal: Dark side of Nigeria’s scrap industry |
| How lunatics, hoodlums attack Lagos ambulance workers on duty — Perm Sec |
| Nigerians will appreciate Buhari more now in death – Ex-SSA Bashir |

---

# Output Files
- `filtered_headlines.csv`: Contains the saved filtered headlines

---

# Author
- Miracle (@Miracle1234-code)
