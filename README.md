[Instagram Following](https://apify.com/patient_discovery/instagram-following?fpr=data)

# **Instagram Following Scraper - No Login Required**

## **What does this scraper do?**

This actor extracts the Instagram following list from any public profile.

Enter a username, run the actor, and receive structured data of accounts that the target profile follows.

No Instagram login, no cookies, no session handling required.

Cookieless architecture ensures stable, risk-free, and scalable automation.

## **Why scrape Instagram following lists?**

Instagram following data reveals audience interests, competitor networks, and influencer ecosystems. This helps marketers, analysts, and sales teams to:

- Analyze competitor following behavior
- Identify high-value audience segments
- Discover influencers and industry communities
- Build social graph and network models
- Generate qualified leads from niche accounts
- Enrich CRM databases with verified profiles
- Develop targeted outreach campaigns

Its cookieless design fits scalable data pipelines without needing Instagram accounts.

## **How much will scraping cost?**

The pricing for this actor is **$2.50 per 1,000 scraped results**. Refer to the pricing page.

Because this actor does not require login or session management, it reduces operational complexity and lowers the risk associated with account-based scraping. This predictable architecture keeps your data pipelines highly stable.

## **How to use the scraper**

Here is a **step-by-step guide**:

**Step 1: Open the actor:** Go to your Apify Console and open the scraper.

**Step 2: Enter your input parameters:** In the input field, enter the Instagram `username`, user ID, or profile URL (e.g., "cristiano").

**Step 3: Configure extraction depth:** Set the maximum number of pages to process.

1 page ≈ 50 following accounts.

**Step 4: Start the run:** Click Start to begin scraping. The actor will automatically fetch the following list from the public profile.

**Step 5: Export or integrate:** Once complete, download the dataset in JSON, CSV, or connect it via API to your analytics or automation system.

## **Input parameters**

Below are the configuration options you can use to control the scraper.

**Input example**

```
{
  "username": "cristiano",
  "maxPages": 2
}
```

| Field | Type | Description |
| --- | --- | --- |
| username | String | Instagram username, user ID, or profile URL |
| maxPages | Number | Maximum number of pages to extract (1 page ≈ 50 accounts) |

## **What data does this scraper extract?**

**Formats**: JSON, CSV, Excel

**Key Fields Extracted**:

- `username` - Instagram handle
- `full_name` - Display name
- `id` - Unique user identifier
- `is_verified` - Verification badge status
- `is_private` - Account privacy setting
- `profile_pic_url` - Profile image URL
- `latest_reel_media` - Timestamp of most recent reel

All data is returned as structured JSON with null-safe fields for reliable downstream processing.

## Sample Output

```
[
  {
    "username": "techfounder",
    "full_name": "Sarah Chen",
    "id": "8472639104",
    "is_verified": true,
    "is_private": false,
    "profile_pic_url": "https://scontent-cdninstagram.com/v/t51.2885-19/profile_pic.jpg",
    "latest_reel_media": 1734187293
  },
  {
    "username": "digitalmarketer",
    "full_name": "Marcus Johnson",
    "id": "5938271046",
    "is_verified": false,
    "is_private": false,
    "profile_pic_url": "https://scontent-cdninstagram.com/v/t51.2885-19/profile_pic.jpg",
    "latest_reel_media": 1733982147
  }
]
```

All data is delivered in structured JSON format suitable for social graph analysis, influencer research, and Instagram lead generation workflows.

## **Key Features:**

- 📈 Extract complete following lists from public profiles
- 📊 Capture verification status and privacy indicators
- ⚡ Structured JSON output ready for analytics and automation
- 📈 Discover influencer ecosystems and niche communities
- 📊 Export-ready formats including JSON, CSV, and Excel
- ⚡ Scalable architecture for processing thousands of accounts
- 🔒 Fully cookieless architecture with no login required

## **FAQs**

**Does this scraper require Instagram login?** No. It is fully cookieless and does not require login credentials.

**Can it scrape private accounts?** No. Only publicly accessible profiles can be scraped.

**Can I extract thousands of following accounts?** Yes. Configure the number of pages to control extraction depth.

**Other Instagram scrapers that you may find useful:**

[Instagram Followers Scraper](https://apify.com/patient_discovery/instagram-followers-scraper---no-login)

[Instagram User Info Scraper](https://apify.com/patient_discovery/instagram-user-info-scraper-cookieless)

[Instagram Comments Scraper](https://apify.com/patient_discovery/instagram-comments-scraper-no-login-required)

[Instagram likes scraper](https://apify.com/patient_discovery/instagram-likes)

[Instagram search hashtags](https://apify.com/patient_discovery/instagram-hashtags-scraper-no-login-required)

[Instagram location posts](https://apify.com/patient_discovery/instagram-location-posts)

[Instagram following](https://apify.com/patient_discovery/instagram-following)

[Instagram user posts](https://apify.com/patient_discovery/instagram-posts)

[Instagram search users](https://apify.com/patient_discovery/instagram-search-users)

[Instagram search reels](https://apify.com/patient_discovery/instagram-search-reels)