# BA-sentiment-scraper
Scrapes customer comments about British Airways to identify pain points and highlight strengths. The data supports sentiment analysis and service improvement efforts.
This project collects and processes user comments about British Airways from online sources. The goal is to identify customer pain points, highlight areas where the airline performs well, and support data-driven service improvements.

🧾 Features
Web scraping of customer reviews

Data cleaning and preprocessing

Jupyter notebook for analysis and exploration

Prepares data for sentiment analysis

🔗 Data Source
All reviews were scraped from Skytrax Airline Reviews – British Airways.

🛠️ Tools Used
BeautifulSoup (bs4)

pandas

Jupyter Notebook

📁 Project Structure
bash
Copy
Edit
british-airways-comment-scraper/
├── data/               # Raw and cleaned data files
├── notebooks/          # Jupyter notebooks for scraping and analysis
├── README.md
└── requirements.txt    # Python dependencies
🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/british-airways-comment-scraper.git
cd british-airways-comment-scraper
(Optional) Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook
✅ Goals
Understand customer satisfaction

Identify recurring complaints

Provide actionable insights using scraped review data

📌 Disclaimer
This project is for educational and analytical purposes only. Please ensure compliance with AirlineQuality.com's terms of service and robots.txt when using or modifying this scraper.
