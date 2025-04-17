# 🍏 Web Scraper (A first)

A simple Node.js web scraper that fetches headlines from [Apple's homepage](https://www.apple.com) using:

- 🧩 Axios for HTTP requests
- 🔍 Cheerio for HTML parsing
- 🚀 Express for setting up a basic server

## 📦 Requirements

Install dependencies:

```bash
npm install express axios cheerio
```

🚀 Run the Scraper

node index.js
You should see the extracted headlines printed in the terminal.

📁 How It Works

Sends a GET request to https://www.apple.com.
Parses the returned HTML using Cheerio.
Searches for all elements with the class .headline.
Extracts and logs the text content of each headline.
📌 Sample Output

[
  { "title": "iPhone 15 Pro" },
  { "title": "MacBook Air is supercharged by M3" },
  { "title": "Watch Series 9" }
]
🔧 Note: Headlines are subject to change depending on Apple's homepage structure.
🔧 Optional Improvements

Include the link URLs (href) by uncommenting the relevant lines in the code.
Add an endpoint like /headlines that returns the scraped data as JSON.
Schedule the scraper to run periodically using node-cron.
Maybe use it as an extension on chrome !!

📚 Tech Stack

Node.js
Express
Axios
Cheerio

Made with ❤️ and JavaScript

