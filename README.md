# Phishing & Scam Detection Tool

## Problem Statement
Students and internet users frequently fall victim to phishing and scam websites that steal personal data and financial information. Most users cannot easily identify whether a link is safe or malicious.

This project aims to help users quickly check whether a URL is safe, suspicious, or dangerous using rule-based detection and security APIs.

## Features (v1)
- URL risk analysis
- Rule-based phishing detection
- API-based verification (VirusTotal)
- Simple and easy-to-use interface

## Tech Stack
- Python (Flask)
- HTML/CSS
- VirusTotal API
- Git & GitHub

## How It Works
1. User enters a URL
2. System checks it using basic security rules
3. The URL is verified using an external security API
4. A final risk level is shown to the user

## Security Considerations
- Input validation to prevent injection attacks
- No storage of user-submitted URLs
- Rate limiting to avoid abuse

## Future Scope
- Email and message phishing detection
- Browser extension
- ML-based detection
- Multi-language support
