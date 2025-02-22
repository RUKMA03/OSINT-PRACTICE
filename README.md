# OSINT Practice Repository

This repository contains a collection of scripts designed for practicing Open-Source Intelligence (OSINT) techniques. OSINT involves gathering and analyzing publicly available information to produce actionable intelligence. These scripts cover various aspects of OSINT, including web scraping, metadata extraction, email and phone number validation, social media analysis, network scanning, and automation tasks.

## What is Open-Source Intelligence (OSINT)?

Open-Source Intelligence (OSINT) refers to the process of collecting, evaluating, and analyzing information from publicly accessible sources to answer specific intelligence questions. It's important to distinguish between mere information and intelligence; raw data becomes intelligence only after thorough analysis and contextualization. OSINT sources include public records, news media, libraries, social media platforms, websites, and even the dark web. ([sans.org](https://www.sans.org/blog/what-is-open-source-intelligence/))

## Repository Structure

The repository is organized into the following directories:

- **web_scraping**: Scripts for extracting data from websites.
  - `scrape_twitter.py`: Scrapes tweets based on a hashtag.
  - `scrape_linkedin.py`: Extracts public LinkedIn profiles.
  - `scrape_whois.py`: Performs WHOIS lookups.

- **metadata_extraction**: Tools for retrieving metadata from files.
  - `extract_pdf_metadata.py`: Reads metadata from PDF files.
  - `extract_image_metadata.py`: Extracts EXIF data from images.

- **email_phone_lookup**: Utilities for validating emails and finding phone numbers.
  - `validate_email.py`: Checks if an email is valid.
  - `find_phone_number.py`: Extracts phone numbers from text.

- **social_media_analysis**: Scripts for analyzing social media content.
  - `analyze_twitter_sentiment.py`: Performs sentiment analysis on tweets.
  - `analyze_reddit_posts.py`: Extracts popular Reddit posts.

- **network_scanning**: Tools for network reconnaissance.
  - `port_scanner.py`: Scans open ports on a given IP.
  - `ip_geolocation.py`: Retrieves geolocation data for an IP.

- **osint_automation**: Scripts to automate OSINT tasks.
  - `bulk_email_lookup.py`: Automates email lookups.
  - `bulk_whois_check.py`: Automates WHOIS checks.

## Prerequisites

Before running these scripts, ensure you have the necessary Python packages installed. You can install the required packages using:

```bash
pip install -r requirements.txt
```

## Usage

Each script is designed to be executed independently. Navigate to the respective directory and run the desired script using Python:

```bash
python script_name.py
```

Replace `script_name.py` with the actual script you intend to run.

## Disclaimer

These scripts are intended for educational and ethical purposes only. Ensure you have proper authorization before accessing or extracting data from any source. Misuse of these tools may lead to legal consequences.

---

*This repository is inspired by the principles and practices outlined by the SANS Institute on Open-Source Intelligence.* ([sans.org](https://www.sans.org/blog/what-is-open-source-intelligence/))
