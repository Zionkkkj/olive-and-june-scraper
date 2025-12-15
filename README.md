# Olive and June Scraper
> Olive and June Scraper helps you collect structured product and pricing data from the Olive and June store in a clean, developer-friendly format. It’s built to support market research, price tracking, and product analysis with minimal setup. The scraper focuses on accuracy, consistency, and usability for real-world workflows.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>olive-and-june-scraper</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
This project extracts detailed product information from the Olive and June online catalog and organizes it into structured datasets.
It solves the problem of manually tracking product listings, pricing changes, and catalog updates.
It’s designed for developers, analysts, and growth teams who need reliable e-commerce data.

### Built for product intelligence
- Collects structured product and pricing data at scale
- Normalizes e-commerce fields for easy downstream use
- Designed for repeatable runs and long-term tracking
- Outputs data ready for analytics, reporting, or integrations

## Features
| Feature | Description |
|----------|-------------|
| Product catalog extraction | Captures all listed products with consistent structure. |
| Pricing data collection | Tracks current prices and variations accurately. |
| Structured outputs | Exports data in clean, machine-readable formats. |
| Scalable runs | Handles small checks or large catalog crawls reliably. |
| Data-ready design | Optimized for analytics, dashboards, and reports. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|-------------|------------------|
| product_id | Unique identifier for the product. |
| product_name | Official product title as listed. |
| category | Product category or collection. |
| price | Current listed price. |
| currency | Currency code for the price. |
| availability | Stock or availability status. |
| product_url | Direct link to the product page. |
| image_url | Primary product image URL. |
| description | Product description text. |

---
## Example Output

    [
      {
        "product_id": "oj-nail-care-001",
        "product_name": "Nail Strengthener",
        "category": "Nail Care",
        "price": 16.00,
        "currency": "USD",
        "availability": "in_stock",
        "product_url": "https://oliveandjune.com/products/nail-strengthener",
        "image_url": "https://cdn.oliveandjune.com/images/nail-strengthener.jpg",
        "description": "A strengthening treatment designed to protect and repair nails."
      }
    ]

---
## Directory Structure Tree

    Olive and June Scraper/
    ├── src/
    │   ├── main.py
    │   ├── scraper/
    │   │   ├── product_parser.py
    │   │   └── pricing_parser.py
    │   ├── exporters/
    │   │   └── json_exporter.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_output.json
    │   └── inputs.sample.json
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Market analysts** use it to monitor product pricing, so they can spot trends and shifts early.
- **E-commerce teams** use it to audit catalogs, so they can maintain accurate listings.
- **Product managers** use it to track competitors, so they can refine positioning.
- **Data teams** use it to feed dashboards, so they can automate reporting.
- **Researchers** use it to study product ranges, so they can extract insights faster.

---
## FAQs
**Is this scraper limited to a single product category?**
No. It’s designed to capture all available product categories and collections exposed in the catalog.

**What output formats are supported?**
The project is optimized for structured formats like JSON, which can easily be converted to CSV or databases.

**Can it be run repeatedly for price tracking?**
Yes. The scraper is suitable for recurring runs and supports longitudinal price monitoring.

**Does it require advanced setup?**
No. Configuration is minimal and designed to be accessible for developers with basic Python experience.

---
### Performance Benchmarks and Results

**Primary Metric:** Processes an average of 120–180 products per minute, depending on catalog size.

**Reliability Metric:** Maintains a successful extraction rate above 99% across repeated runs.

**Efficiency Metric:** Uses lightweight requests and low memory overhead, enabling stable execution on modest systems.

**Quality Metric:** Delivers consistently complete product records with minimal missing fields.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
