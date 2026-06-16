[Etsy Product Scraper](https://apify.com/yesintelligent/etsy-product-scraper?fpr=data)

# Etsy Product Scraper - Extract Etsy Product Data with Images & Reviews

Effortlessly scrape detailed product information from Etsy including prices, images, reviews, and seller details. Our powerful Etsy scraper bypasses anti-bot measures to extract accurate, structured data for market research, price monitoring, and competitor analysis.

## Key Features

- **Comprehensive Data Extraction**: Get product titles, descriptions, prices, images, reviews, seller info, and more
- **Anti-Detection Technology**: Overcomes Etsy's bot protection systems
- **Rich Media Collection**: Extract all product images and customer reviews
- **Flexible Configuration**: Adjustable concurrency, timeouts, and data selection
- **Structured Output**: Clean JSON data ready for analysis or integration
- **Proxy Support**: Built-in residential proxy rotation for reliable scraping
- **Easy Integration**: Works via Apify Platform or API

## Use Cases

- **Market Research**: Analyze product trends, pricing strategies, and seller performance
- **Price Monitoring**: Track competitor pricing and automate repricing strategies
- **Catalog Building**: Create comprehensive product databases for affiliate marketing
- **Sentiment Analysis**: Study customer reviews to understand product reception
- **Inventory Tracking**: Monitor product availability and seller inventory changes
- **Competitor Analysis**: Compare product offerings, features, and customer feedback

## How to Scrape Etsy Products

1. **Prepare Product URLs**: Collect the Etsy product URLs you want to scrape
2. **Configure Options**: Set parameters like concurrency, proxy settings, and data fields
3. **Run the Scraper**: Execute via Apify Platform or API
4. **Get Structured Data**: Receive clean JSON data ready for analysis

## Input Parameters

### Required

- **productUrls**: List of Etsy product URLs (one per line)

### Optional

- **proxyConfiguration**: Proxy settings for IP rotation
- **maxConcurrency**: Concurrent browser instances (1-10, default: 3)
- **requestTimeout**: Request timeout in seconds (30-300, default: 45)
- **maxRetries**: Failed request retries (0-10, default: 2)
- **includeReviews**: Extract customer reviews (default: true)
- **includeImages**: Extract product images (default: true)
- **maxReviews**: Max reviews per product (0-200, default: 5)

## Output Data Format

```
{
  "title": "Handmade Ceramic Mug",
  "sellerName": "Artisan Pottery Shop",
  "price": "24.99",
  "currency": "USD",
  "description": "Beautiful handmade ceramic mug...",
  "images": ["https://image1.jpg", "https://image2.jpg"],
  "reviews": [
    {
      "rating": 5,
      "reviewer": "Happy Customer",
      "comment": "Love this mug!"
    }
  ],
  "averageRating": 4.8,
  "reviewCount": 127
}
```

## Getting Started

### Via Apify Platform

1. Visit [Apify Store](https://apify.com/store)
2. Search for "Etsy Product Scraper"
3. Click "Try for free" or "Run"
4. Enter your Etsy product URLs
5. Configure settings and run

### Via API

```
curl -X POST https://api.apify.com/v2/acts/YOUR_USERNAME~ETSY-SCRAPER/runs \
  -H "Authorization: Bearer YOUR_API_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"productUrls": "https://www.etsy.com/listing/123456789/product"}'
```

## Why Choose Our Etsy Scraper?

- **Reliable Data Extraction**: Handles Etsy's anti-scraping measures
- **Fast Processing**: Optimized for quick data retrieval
- **Detailed Information**: Captures all relevant product details
- **Regular Updates**: Maintained to work with Etsy's latest changes
- **Technical Support**: Assistance from Apify experts

## Pricing

- Pay-per-use with transparent Apify platform pricing
- Free tier available for testing
- Volume discounts for enterprise users

Start scraping Etsy product data today and gain valuable insights for your business!