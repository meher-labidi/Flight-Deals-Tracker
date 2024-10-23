# Flight Deals Tracker

This project is a Python application that tracks flight deals and sends notifications when prices drop below a specified threshold. It integrates with Sheety for managing data, uses the Tequila API for flight searches, and sends notifications via email and SMS using SMTP and Twilio.

## Features
- Track flight deals from various destinations.
- Send email notifications when a flight deal is found.
- Send SMS notifications for flight deals.
- Integrate with Sheety for data management.

## Requirements
- Python 3.x
- `requests` library
- `pprint` library
- `twilio` library
- `smtplib` (included in Python standard library)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/flight-deals-tracker.git
    ```
2. Navigate to the project directory:
    ```sh
    cd flight-deals-tracker
    ```
3. Install the required libraries:
    ```sh
    pip install requests twilio
    ```

## Configuration
1. Update the environment variables for Sheety and Twilio in the `.env` file:
    - `API_Bearer_Sheety_Repl.it`
    - `API_Username_Sheety`
    - `TWILIO_SID`
    - `TWILIO_AUTH_TOKEN`
    - `TWILIO_VIRTUAL_NUMBER`
    - `TWILIO_VERIFIED_NUMBER`
    - `TEQUILA_API_KEY`

2. Ensure you have the necessary API keys and tokens.

## Usage
1. Run the main script:
    ```sh
    python main.py
    ```

2. Follow the prompts to enter your information and receive flight deal notifications.
