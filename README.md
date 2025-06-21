# faculty-email-crawler
e-mail scraper uni. dept.
# 📧 Punjabi University CSE Email Scraper

This is a simple Python script that scrapes email addresses of faculty members from the **Computer Science and Engineering (CSE) Department** page of [Punjabi University](https://www.punjabiuniversity.ac.in).

---

## 🔍 Features

- Extracts email addresses using `BeautifulSoup` and regular expressions.
- Filters and displays **unique** email addresses found on the department page.
- Includes custom headers to simulate a real browser request.

---

## 🛠️ Technologies Used

- Python 3.x
- `requests` – for fetching the web page
- `beautifulsoup4` – for parsing HTML content
- `re` – for matching email patterns

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/punjabiuniv-cse-emails.git
cd punjabiuniv-cse-emails
###2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
