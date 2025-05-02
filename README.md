# Email to WhatsApp Notifier

This project reads incoming emails, summarizes them, and forwards specific messages to a WhatsApp number using an API.

## Features

- Access Gmail inbox using Google API
- Extract relevant email content
- Send messages to WhatsApp using a chosen API (e.g., Twilio)

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/email-to-whatsapp.git
cd email-to-whatsapp
```

### 2. Set Up Virtual Environment (Optional)

```bash
python -m venv venv
# On Unix or MacOS
source venv/bin/activate
# On Windows
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Google API Credentials

- Go to the Google Cloud Console
- Enable the Gmail API
- Download your `client_secret.json`
- Place it in the root of this project (this file is excluded from Git)
- You can use the `example_client_secret.json` file as a reference for the structure

### 5. Configure WhatsApp API

- Register for an account (e.g., Twilio or other)
- Set your credentials in environment variables or in a config file
- Ensure your device or sandbox is set up for testing

### 6. Run the Script

```bash
python app.py
```
