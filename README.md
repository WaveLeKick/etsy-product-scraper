[Etsy Product Scraper](https://apify.com/getdataforme/Etsy-product-scraper?fpr=data)

---

# Land Broker Scraper

Extract Broker Information from Land.com Effortlessly

The **Land Broker Scraper** is an Apify actor designed to extract detailed broker information from [Land.com](https://land.com). It enables you to gather essential data, such as broker names, contact information, company details, and listing history, in a structured format.

**Note**: Please activate Proxy to avoid restrictions or blockages during scraping. Running the scraper without a proxy may result in incomplete or failed extractions.

---

## How This Land Broker Scraper Works

1. **Input Parameters**

- Provide the target location and the maximum number of brokers to scrape using the simple JSON input format:

```
{
    "location": "Bear-DE",
    "maxItems": 20
}
```
- **Location**: Enter the location in the `"location"` field (e.g., `"Bear-DE"`).
- **Max Items**: Set the maximum number of broker profiles to fetch in the `"maxItems"` field (e.g., `20`).
2. **Run the Scraper**

- Once the input is set, start the scraper. The data will be fetched and returned in JSON format.
3. **Retrieve Results**

- Get detailed broker information, including their name, contact details, company, and historical listing performance.

---

## Input Parameters

**1. Location**

- *Type*: String
- *Description*: Specify the target location for scraping brokers.
- *Example*: `"Bear-DE"`

**2. Max Items**

- *Type*: Integer
- *Description*: Set the maximum number of broker profiles to retrieve.
- *Example*: `20`

---

## Output

When the scraper runs successfully, you will receive the following data for each broker:

```
{
    "url": "https://www.land.com/member/octavia-samuels/1319572/listings/",
    "Account ID": 1319572,
    "Name": "Octavia Samuels",
    "Email": "OctaviaSamuels@c21gk.com",
    "Phone (Office)": "",
    "Company": "CENTURY 21 Gold Key Realty",
    "Address": "600 Peoples Plaza, Newark, DE 19702",
    "Active": "Yes",
    "Listings in Last 5 Years": 40,
    "Price Range in Last 5 Years": "$68000 - $749900"
}
```

### Output Fields Explained

- **url**: URL to the broker's listing page on Land.com.
- **Account ID**: Unique identifier for the broker.
- **Name**: Full name of the broker.
- **Email**: Broker's email address.
- **Phone (Office)**: Broker’s office phone number (if available).
- **Company**: Name of the broker's affiliated company.
- **Address**: The broker's company address.
- **Active**: Indicates whether the broker is currently active.
- **Listings in Last 5 Years**: Number of property listings posted by the broker in the past 5 years.
- **Price Range in Last 5 Years**: Range of property prices for the broker's listings over the past 5 years.

---

## Example Usage

1. **Input**:

```
{
    "location": "Bear-DE",
    "maxItems": 20
}
```
2. **Output**:

```
{
    "url": "https://www.land.com/member/octavia-samuels/1319572/listings/",
    "Account ID": 1319572,
    "Name": "Octavia Samuels",
    "Email": "OctaviaSamuels@c21gk.com",
    "Phone (Office)": "",
    "Company": "CENTURY 21 Gold Key Realty",
    "Address": "600 Peoples Plaza, Newark, DE 19702",
    "Active": "Yes",
    "Listings in Last 5 Years": 40,
    "Price Range in Last 5 Years": "$68000 - $749900"
}
```

---

## Proxy Configuration

To avoid rate-limiting or blocking issues, enable proxy settings when running the scraper. Apify’s proxy configuration ensures uninterrupted data extraction.

---

## Support

For any queries, bug reports, or custom requirements, please reach out to us:

- **Email**: [support@getdataforme.com](mailto:support@getdataforme.com)
- **Contact Form**: [Get Data For Me Contact](https://getdataforme.com/contact/)

When contacting support, include "Custom Support" in the subject for faster assistance.

---

Start extracting valuable broker data from **Land.com** with the **Land Broker Scraper** today!

---

Let me know if you’d like to tweak or enhance anything further! 😊