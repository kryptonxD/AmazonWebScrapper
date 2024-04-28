# Amazon WebScrapper

This project is a Python script designed to track the price of a specific product on Amazon and notify the user via email when the price drops to a certain threshold. The script utilizes web scraping techniques to extract product information from the Amazon website and sends email notifications using the smtplib library.

## Features

- **Price Tracking**: Automatically retrieves the current price of a specified product on Amazon.
- **Email Notification**: Sends an email notification to the user when the price of the product drops to a predefined threshold.
- **Automated Execution**: Runs the price tracking script at regular intervals to ensure up-to-date price information.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/amazon-price-tracker.git
```

2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Set up your email credentials and specify the product URL in the `amazon_price_tracker.py` script.

4. Run the script:

```bash
python amazon_price_tracker.py
```

## Configuration

Before running the script, make sure to configure the following parameters in the `amazon_price_tracker.py` file:

- **Product URL**: Replace the `URL` variable with the URL of the product you want to track on Amazon.
- **Email Credentials**: Provide your email address and password for sending notification emails.
- **Threshold Price**: Set the desired price threshold at which you want to receive notifications.

## Usage

Once configured, the script will run continuously, periodically checking the price of the specified product on Amazon. If the price drops below the threshold, it will send an email notification to the specified email address.
