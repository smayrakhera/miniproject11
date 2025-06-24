# 🕷️ Web Crawler - Email Scraper

A simple Python project to crawl a website and extract email addresses from all internal pages.

## 🚀 Features
- Crawls a website recursively
- Extracts email addresses using regex
- Saves emails to `emails_found.txt`

#### 💻 How to Use

1. **Install Dependencies**  
   Make sure Python is installed. Then run:
   ```bash
   pip install -r requirements.txt
Run the Script

bash
Copy
Edit
python email_scraper.py
Enter the Website URL
You'll be prompted to enter a starting URL. The program will begin crawling from there.

Output
All unique email addresses found are saved in emails_found.txt.

📚 How It Works (Theory)
The script sends HTTP requests to fetch HTML content of web pages.

It uses BeautifulSoup to parse the HTML and extract links.

A regular expression pattern is used to find strings that match the structure of an email address.

All internal links (same domain) are crawled recursively.

A set is used to avoid duplicates and repeated crawling.

📁 Project Files
email_scraper.py – Python script

requirements.txt – Required libraries

emails_found.txt – Output file (auto-generated)

⚠️ Disclaimer
This tool is for educational purposes only. Do not use it on websites without permission or in violation of terms of service.

yaml
Copy
Edit
# miniproject11
