# NEXUS Threat Scanner

NEXUS Threat Scanner is a web-based URL analysis tool that checks a target link for possible phishing and cybersecurity warning signs. It uses an AI prompt to inspect the URL structure, identify suspicious patterns, and return a risk result with clear warnings.

## Features

- Scans URLs for possible phishing indicators
- Shows a risk level: safe, warning, or danger
- Breaks the URL into readable parts such as protocol, domain, path, and suspicious sections
- Displays warning messages explaining possible risks
- Uses a cyber-themed responsive interface
- Runs directly in the browser as a static website

## How It Works

1. The user enters a Google Gemini API token.
2. The app unlocks the scanner screen after the token format is accepted.
3. The user enters a target URL.
4. The app sends the URL to the Gemini API for analysis.
5. The AI response is shown as a risk report with URL anatomy and warnings.

## Technologies Used

- HTML
- CSS
- JavaScript
- Google Gemini API

## Project Structure

```text
NEXUS Threat Scanner/
├── index.html
├── phishing1.css
├── phishing1.js
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Enter your Gemini API key when asked.
4. Paste a URL into the scanner.
5. Click `Initiate Scan`.

## API Key Note

This project asks for an API key in the browser. Do not publish your real API key in the code, screenshots, README, or GitHub commits.

For a production version, the API request should be handled through a secure backend server instead of directly from the browser.

## Example URLs to Test

```text
https://google.com
http://secure-login.paypal.com@192.168.1.1/update
https://example.com/login
```

## Important Disclaimer

This tool is for learning and basic URL analysis only. It should not be treated as a complete cybersecurity solution. Always verify suspicious links with trusted security tools and avoid opening unknown links.

## Author

Created by [jimmmy1234](https://github.com/jimmmy1234).
