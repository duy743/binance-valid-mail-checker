# Binance Email Validator

This Python script checks if an email is registered with a Binance account. It performs API requests to simulate a login attempt, checking for response codes that can indicate if the email is recognized by Binance. The script includes retry logic, randomized delays to prevent rate limiting, and detailed output for easier debugging.

**Note**: This tool does not attempt to log in or access any account directly. It simply checks if an email address is registered by interpreting Binance’s responses. This is meant for educational purposes only and should be used responsibly.

## Features

- **Retry Logic**: The script retries requests if they fail, up to a specified maximum.
- **Rate Limiting**: Includes random delays to mimic human-like behavior and avoid being rate-limited.
- **Error Handling**: Handles common errors such as network issues, rate limiting, and forbidden access responses.
- **Detailed Output**: Provides clear output on the status of each email validation attempt.

## Requirements

- Python 3.x
- `requests` library

## Setup

1. **Install required libraries**

   Install the necessary Python libraries by running:
   ```bash
   pip install requests
   ```

   ```bash
   python checker.py
   ```
print('axkyavjohi')