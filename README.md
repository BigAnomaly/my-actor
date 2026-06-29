[My Actor](https://apify.com/lunvixor/my-actor?fpr=data)

## Instagram Business Lead Extractor – Actor README

This Actor extracts public business information from Instagram based on a list of usernames, profile URLs, hashtags, or keywords.
It returns structured data (CSV/JSON) containing:

-Username

-Profile URL

-Full name

-Bio

-Website

-Email & phone found in bio

-Follower & following count

-Profile picture

-Category (if available)

Built by Lunvixor
We build Web Apps, Mobile Apps, AI Automation, Web Scrapers, Custom Bots & Dashboards.
Need a custom scraper, API integration, or automation for your business?
Contact: [lunvixor@gmail.com](mailto:lunvixor@gmail.com)

## Included features

Apify SDK – Tools for building scalable scraping and automation Actors

Input schema – Validated user inputs for keywords, usernames, and limits

Dataset storage – Results saved as structured JSON/CSV/Excel

HTTP Client (Axios) – For fast & stable data fetching

Cheerio – Parse HTML and extract public Instagram data

Proxy support – Handles requests safely to avoid blocking

## How it works

1.The actor reads input fields (keywords, usernames, maxResults, etc.) via Actor.getInput().

2.For each username/URL/keyword, it fetches the public profile page.

3.Cheerio loads and parses the HTML.

4.The scraper extracts:

bio
contact info
website
stats
category

5.Each profile is saved using Actor.pushData() into the dataset.

6.You can export results as JSON, CSV, or Excel.

## Resources

-Apify SDK (JS): [https://docs.apify.com/sdk/js](https://docs.apify.com/sdk/js)

-Building Actors: [https://docs.apify.com/platform/actors/development](https://docs.apify.com/platform/actors/development)

-Cheerio scrapers: [https://blog.apify.com/web-scraping-with-cheerio/](https://blog.apify.com/web-scraping-with-cheerio/)

-Video: Building a scraper with CheerioCrawler

-Integrations (Zapier/Make/Sheets): [https://apify.com/integrations](https://apify.com/integrations)

## Getting started

1.Create your Actor
2.Paste the code
3.Define the input schema
4.Run the Actor
5.Publish to the Apify Store