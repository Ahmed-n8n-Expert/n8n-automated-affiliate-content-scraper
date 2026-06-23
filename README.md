# n8n-automated-affiliate-content-scraper
Automated Web Scraper and Content Pipeline built on n8n. Extracts products, images, and text from websites, converts them into affiliate assets, and auto-publishes to social media.
# 🕸️ Automated Affiliate Content Scraper & Social Media Pipeline (n8n)

A powerful, production-ready data scraping and marketing automation workflow built using **n8n**. This system automatically extracts product data, descriptions, and media assets from targeted e-commerce or content websites, processes them into optimized affiliate marketing posts, and publishes them directly to social media channels.

## 🚀 Key Features

- **Automated Web Scraping:** Uses HTTP Request nodes and custom parsing logic to extract clean product titles, pricing, descriptions, and high-quality image URLs from target sites.
- **Dynamic Affiliate Link Generation:** Features a logical processing node that injects custom affiliate tracking IDs or shortens URLs dynamically before publishing.
- **Automated Media Downloading:** Programmatically handles binary data to fetch, store, and re-upload product images and video assets directly to social platforms.
- **Omni-Channel Social Publishing:** Links with social media APIs (or scheduling platforms like Buffer) to auto-post the scraped products as highly engaging promotional content with images and captions.
- **Smart Scheduling & Updates:** Runs on a custom interval/cron trigger to fetch only new or updated items, ensuring your social feeds remain fresh without scraping duplicates.

## 🛠️ Built With

- **n8n** (Data Parsing, Binary Content Handling & Workflow Automation)
- **HTTP Request / HTML Parser Nodes** (For web scraping and DOM extraction)
- **Custom JavaScript** (For text cleaning, regex matching, and affiliate URL formatting)
- **Social Media APIs / Buffer API** (For auto-publishing content pipelines)

## 📦 How to Deploy This Workflow

1. **Import to n8n:** Download the `affiliate-content-scraper.json` file from this repository and upload it into your n8n canvas.
2. **Configure Scraping Targets:** Modify the HTTP Request node with the specific URL you wish to scrape, and adjust the HTML Parser selectors (CSS/Xpath) to match the target site's layout.
3. **Set Affiliate Parameters:** Update the custom JavaScript or Set nodes with your specific affiliate tracking tags and link shortener keys.
4. **Connect Destination Channels:** Authenticate your social media channels or scheduling gateway credentials to enable seamless posting.

---
*Developed by Ahmed Tamer - AI Automation Engineer*
