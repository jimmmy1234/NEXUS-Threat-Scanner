# NEXUS Threat Scanner

NEXUS Threat Scanner is a web-based URL analysis tool that checks a target link for possible phishing and cybersecurity warning signs. It uses local browser-based heuristics to inspect the URL structure, identify suspicious patterns, and return a risk result with clear warnings.

## Features

- Scans URLs for possible phishing indicators
- Shows a risk level: safe, warning, or danger
- Breaks the URL into readable parts such as protocol, domain, path, and suspicious sections
- Displays warning messages explaining possible risks
- Uses a cyber-themed responsive interface
- Runs directly in the browser as a static website
- Does not require login, installation, or an API key

## How It Works

1. The user enters a target URL.
2. The app checks the URL in the browser using local rules.
3. The scanner looks for warning signs such as unsafe protocols, IP-address hosts, suspicious keywords, hidden destinations, link shorteners, and brand impersonation patterns.
4. The result is shown as a risk report with URL anatomy and warnings.

## Technologies Used

- HTML
- CSS
- JavaScript

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
3. Paste a URL into the scanner.
4. Click `Initiate Scan`.

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
