# GateScan - Incognito Investigation Module

## Overview
GateScan is a web-based application designed for the **Signature Event PROCOM** at FAST NUCES. It simulates an access control system for a fictional organization, allowing users to check access logs and details for both public and private cardholders. The system is designed to assist in an incognito investigation scenario, where users can verify access permissions and logs for specific card numbers and dates.

---
## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Other Project](#other-project-for-this-university-event)

---
## Features
- **Public Access Check**: Verify the presence of public cardholders on specific dates.
- **Private Access Check**: Check detailed access logs for private cardholders, including floor access and timestamps.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Loading Animation**: A sleek loading animation enhances the user experience.
- **Mock Data**: Pre-populated with mock data for testing and demonstration purposes.

## How It Works
1. **Public Form**:
   - Enter a public card number and a date to check if the cardholder was present on that day.
   - The system will display whether the cardholder was present or absent.

2. **Private Form**:
   - Enter a private card number and a date to view detailed access logs, including time in, time out, and accessed floors.
   - If the card is blocked (e.g., card number `97452368`), the system will notify the user.

## Technologies Used
- **HTML5**: Structure of the web page.
- **CSS3**: Styling and animations, including responsive design.
- **JavaScript**: Logic for handling form inputs, displaying results, and toggling between public and private forms.
- **GSAP (GreenSock Animation Platform)**: For smooth loading animations.
- **Google Fonts**: Custom fonts (`Orbitron` and `Roboto`) for a modern look.

## Other Project for this University Event
https://sana-munir-alam.github.io/Hangman
