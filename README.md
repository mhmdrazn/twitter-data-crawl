# Twitter Scraper using Playwright
This repository contains a script to scrape tweets from Twitter search results based on keywords, date range, and geolocation using Playwright.

## Features
- Scrape tweets based on specific keywords.
- Filter tweets by date range.
- Specify geolocation for more targeted results.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Node.js installed on your machine.
- Playwright installed. You can install it using the following command:
  `npm install playwright`

## Usage
To run the scraper, use the following command:
`node scraper.js --keywords="your,keywords" --startDate="YYYY-MM-DD" --endDate="YYYY-MM-DD" --geo="latitude,longitude,radius"`

## Arguments
- `filename` - The filename of csv typefile to store the output.
- `search_keywords` - A comma-separated list of keywords to search for.
- `LATEST` - the time filtering to find the latest tweets.
- `limit` - The limit of the tweets will be crawled.
- `twitter_auth_token` - Your personal Twitter auth token.

## Credits
This project was inspired by and based on the work of [Helmi Satria](https://github.com/helmisatria).
