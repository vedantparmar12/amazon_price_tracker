# Amazon Price Tracker

This Python script tracks the price of a specific product on Amazon and sends an email notification when the price drops below a specified threshold.

## Prerequisites

Before running the script, ensure that you have the following:

- Python 3.x installed
- Required Python libraries installed (`requests`, `beautifulsoup4`, `lxml`)
- A Gmail account with an app password (see instructions below)

## Installation

1. Clone the repository: git clone https://github.com/vedantparmar12/amazon-price-tracker.git
2. Navigate to the project directory: cd amazon-price-tracker
3. Install the required Python libraries: pip install requests beautifulsoup4 lxml

## Setup

1. Open the `price_tracker.py` file and replace the following placeholders with your Gmail account credentials and the desired product URL:

SENDER_EMAIL = 'your-gmail-account@gmail.com'
SENDER_PASSWORD = 'your-app-password'
PRODUCT_URL = 'https://www.amazon.in/boAt-Rockerz-255-Pro-Earphones/dp/B08TTXNZ4Y/ref=sr_1_1_sspa?sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1'
TARGET_PRICE = 1599  # Set your desired price threshold

2. To create an app password for your Gmail account, follow these steps:

1. Log into your Gmail account
2. Click on the "Security" tab on the left
3. Find the "How you sign in to Google" area
4. Click on "2-Step Verification" (set it up if you haven't already)
5.Once you've entered your password and set up 2-Step Verification, scroll to the bottom of the page
6. You'll see the "App passwords" section
7. Click on the little arrow/chevron ('>') to be taken to the app passwords page
8. In the "Select app" drop-down box, select "Mail"
9. In the "Select device" drop-down box, select your computer type (Mac, Windows, etc.)
10. Click "Generate"
11. Copy the generated password immediately (you'll only see it once)
12. Paste the password into the SENDER_PASSWORD variable in the price_tracker.py file

Usage

Run the script:

Copy codepython price_tracker.py
The script will check the price of the specified product on Amazon and send an email notification to your Gmail account if the price drops below the set threshold.
Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
License
This project is licensed under the MIT License.

This README.md file provides an overview of the project, lists the prerequisites, explains how to install and set up the script, and includes sections for usage, contributing, and licensing. You can further customize the content based on your project's specific requirements.
