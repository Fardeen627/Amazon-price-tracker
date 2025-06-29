# Price Tracker & Email Alert

A Python script that monitors product prices and sends email alerts when prices drop.

## Features
- Web scraping with BeautifulSoup and requests
- Email notifications via smtplib
- Environment variable support (.env)

## Setup
1. Clone this repository:
   bash
   git clone https://github.com/your-username/price-tracker.git
   
2. Install dependencies:
   bash
   pip install -r requirements.txt
   
3. Create a .env file (use .env.example as a template).

## Usage
Run the script:
bash
python main.py


## Configuration
Edit main.py to:
- Update the target URL
- Adjust the price threshold
- Modify email settings