[Instagram Following](https://apify.com/data-slayer/instagram-following?fpr=data)

Extract Instagram following lists without authentication or cookies. This scraper enables social media strategists to build comprehensive audience insights and develop targeted marketing campaigns using a completely cookieless architecture.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/ehnJAemUP1w?enablejsapi=1&rel=0)

---

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| username | String | Instagram username, user ID, or profile URL (e.g., `cristiano`) |

## Outputs

**Available Formats**: JSON, CSV, Excel

**Extracted Fields**:

- `username` - Instagram handle
- `full_name` - Display name
- `id` - Unique user identifier
- `is_verified` - Verification badge status
- `is_private` - Account privacy setting
- `profile_pic_url` - Profile image URL
- `latest_reel_media` - Timestamp of most recent reel

## How to Use

**Step 1**: Enter the target Instagram `username` (e.g., `cristiano`), user ID, or full profile URL in the input field.

**Step 2**: Configure extraction depth by setting the maximum number of pages to process (**1 page ≈ 50 following accounts**).

**Step 3**: Run the scraper and download your data in JSON, CSV, or Excel format once extraction completes.

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

---

## Key Features

🔒 **Cookieless / No Login Required** - Extract following data without Instagram credentials, eliminating account suspension risks and authentication complexity.

📈 **Scalable Architecture** - Process multiple profiles and extract thousands of following relationships with enterprise-grade reliability.

✅ **Rich Profile Data** - Capture username, full name, user ID, verification status, privacy settings, profile pictures, and latest reel activity timestamps.

⚡ **Fast & Reliable** - Optimized extraction engine delivers consistent results with minimal latency and maximum uptime.

📊 **Export-Ready Formats** - Download data instantly in JSON, CSV, or Excel formats for seamless integration with your analytics stack.

## Use Cases

**Social Media Marketers**: Analyze competitor following patterns to identify high-value audience segments and craft personalized outreach campaigns that resonate with target demographics.

**Data Analysts**: Build comprehensive social graphs and network analysis models by mapping following relationships across multiple profiles to uncover influencer ecosystems and community structures.

**Sales & Business Development Teams**: Generate qualified leads by extracting following lists from industry leaders and competitors, then enriching prospect databases with verified Instagram profiles for multi-channel engagement.

## Important Considerations

This scraper works exclusively with public Instagram profiles. Private accounts cannot be accessed, and following lists will only be extracted from profiles with public visibility settings.

## 🧩 Other Instagram Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Instagram Followers Scraper | Extract follower lists from any account | [Try it](https://apify.com/data-slayer/instagram-followers-scraper---no-login) |
| Instagram Comments Scraper | Extract comments from any post | [Try it](https://apify.com/data-slayer/instagram-comments-scraper-no-login-required) |
| Instagram Posts Scraper | Extract posts from any profile | [Try it](https://apify.com/data-slayer/instagram-posts) |
| Instagram Likes Scraper | Extract users who liked any post | [Try it](https://apify.com/data-slayer/instagram-likes) |
| Instagram Reels Scraper | Search and extract Instagram Reels | [Try it](https://apify.com/data-slayer/instagram-search-reels) |
| Instagram Profile Scraper | Get full profile data with contact info | [Try it](https://apify.com/data-slayer/instagram-user-info-scraper-cookieless) |
| Instagram User Search | Search Instagram users by keyword | [Try it](https://apify.com/data-slayer/instagram-search-users) |
| Instagram Hashtag Scraper | Discover hashtags and media counts | [Try it](https://apify.com/data-slayer/instagram-hashtags-scraper-no-login-required) |
| Instagram Location Posts | Extract posts from any location | [Try it](https://apify.com/data-slayer/instagram-location-posts) |

**Need verified emails?** Our [LinkedIn Post Engagers Email Finder](https://apify.com/data-slayer/linkedin-post-to-verified-leads) and [LinkedIn Audience Email Finder](https://apify.com/data-slayer/linkedin-influencer-audience-to-verified-leads) extract verified work emails from LinkedIn engagement data.

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too

We typically respond within 24 hours.

---

---