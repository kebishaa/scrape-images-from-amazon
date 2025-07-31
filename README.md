# scrape-images-from-amazon

✅ Project Summary
Task:
Scrape images from ~14,200 product URLs and populate them into an Excel sheet with columns:

Image 1

Image 2

Image 3

Image 4

Image 5

Image 6

If a product page was unavailable or invalid, "NA" was inserted under Image 1 to indicate an inactive link.


⚙️ Tech Stack
Python 3

aiohttp + asyncio – for fast asynchronous scraping

BeautifulSoup – for parsing HTML and extracting image tags

pandas – for reading and writing Excel files

openpyxl – Excel backend

requests – for downloading sample image files

🚀 Key Features
⚡ Asynchronous scraping using aiohttp — ~14,000 pages scraped in under 20 minutes

🧠 Automatic filtering for full-sized .jpg images (excluding thumbnails)

📁 Image showcase folder created with a small set of downloaded images

🧾 Structured Excel output with up to 6 images per product

🔁 Graceful handling of broken or inactive URLs

📌 Use Case
This type of scraper is useful for:

eCommerce product cataloging

Competitor analysis

Dropshipping and marketplace listing automation

Dataset creation for ML/computer vision training

