# GeoPhish CTF Challenge 2026 🐶

Welcome to the GeoPhish CTF Challenge! This is a static Capture The Flag (CTF) challenge based on the GeoPhish phishing tool.

## Challenge Description

GeoPhish is a tool that creates a fake interface to trick users into enabling location sharing, capturing their IP, device info, and GPS coordinates.

This is a static website CTF challenge. The backend remains the same (PHP scripts for data capture), but the frontend is static with hidden flags.

## Objectives

Find the hidden flags by inspecting the website files:

1. **FLAG{source_code_inspection}** - In the HTML source code comments.
2. **FLAG{css_hidden_flag}** - In the CSS file comments.
3. **FLAG{payload_analysis_complete}** - In the script.js file.

## Setup

1. The website is static, so no server needed for the frontend.
2. The backend PHP scripts are still present for analysis.

## Rules

- Inspect the source code, CSS, and other files.
- Do not run the server unless analyzing the backend.
- This is for educational CTF purposes only.

## Credits

Original GeoPhish tool by 0xBinaryOrbit.
CTF adaptation for educational purposes.
