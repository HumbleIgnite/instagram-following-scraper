[Instagram Following Scraper](https://apify.com/scrapier/instagram-following-scraper?fpr=data)

A compact, production-grade **Apify Actor** that scrapes Instagram **following** lists for one or more input profiles and saves results **in real time** to the dataset.

## Why Choose This Actor?

- **Matches your required output shape** (same keys as your `output.json`)
- **Bulk input** (URLs or usernames/keywords)
- **Smart proxy fallback**:

- Start with **no proxy** (direct)
- If blocked → fallback to **datacenter proxy**
- If blocked → fallback to **residential proxy**
- If residential fails → **retry 3 times** with residential
- After fallback happens → **stick to residential** for remaining requests
- **Clear progress logs** to keep the user engaged

## Input

Example:

```
{
  "urls": [
    "https://www.instagram.com/mrbeast/",
    "virat.kohli"
  ],
  "maxItems": 300,
  "pageSize": 12,
  "sessionId": "YOUR_SESSIONID_COOKIE_VALUE",
  "proxyConfiguration": {
    "useApifyProxy": false
  }
}
```

## Output

Each dataset item contains these keys:

- `pk`, `pk_id`, `id`, `full_name`, `is_private`, `fbid_v2`, `third_party_downloads_enabled`, `strong_id__`, `profile_pic_id`, `profile_pic_url`, `is_verified`, `username`, `has_anonymous_profile_picture`, `account_badges`, `latest_reel_media`, `is_favorite`, `followed_by`

## Notes / Cautions

- The actor scrapes only **publicly available** data.
- The end user is responsible for compliance with applicable laws and platform rules.

## What are other Instagram scraping tools?

If you want to scrape specific Instagram data, you can use any of the dedicated scrapers below for faster and more targeted results.

| Scraper Name | Scraper Name |
| --- | --- |
| [Instagram B2b Email Scraper](https://apify.com/scrapier/instagram-b2b-email-scraper) | [Instagram Posts Scraper](https://apify.com/scrapier/instagram-posts-scraper) |
| [Instagram B2b Lead Scraper](https://apify.com/scrapier/instagram-b2b-lead-scraper) | [Instagram Profile Email Scraper](https://apify.com/scrapier/instagram-profile-email-scraper) |
| [Instagram B2b Phone Number Scraper](https://apify.com/scrapier/instagram-b2b-phone-number-scraper) | [Instagram Profile Email Scraper By Keyword](https://apify.com/scrapier/instagram-profile-email-scraper-by-keyword) |
| [Instagram Comments Scraper](https://apify.com/scrapier/instagram-comments-scraper) | [Instagram Profile Lead Scraper](https://apify.com/scrapier/instagram-profile-lead-scraper) |
| [Instagram Dm Automation](https://apify.com/scrapier/instagram-dm-automation) | [Instagram Profile Lead Scraper By Keyword](https://apify.com/scrapier/instagram-profile-lead-scraper-by-keyword) |
| [Instagram Email Scraper](https://apify.com/scrapier/instagram-email-scraper) | [Instagram Profile Phone Number Scraper](https://apify.com/scrapier/instagram-profile-phone-number-scraper) |
| [Instagram Followers And Following Scrapper](https://apify.com/scrapier/instagram-followers-and-following-scrapper) | [Instagram Profile Phone Number Scraper By Keyword](https://apify.com/scrapier/instagram-profile-phone-number-scraper-by-keyword) |
| [Instagram Followers Count Scraper](https://apify.com/scrapier/instagram-followers-count-scraper) | [Instagram Profile Post Scraper](https://apify.com/scrapier/instagram-profile-post-scraper) |
| [Instagram Followers Scraper](https://apify.com/scrapier/instagram-followers-scraper) | [Instagram Profile Reels Scraper](https://apify.com/scrapier/instagram-profile-reels-scraper) |
| [Instagram Hashtag Scraper](https://apify.com/scrapier/instagram-hashtag-scraper) | [Instagram Profile Scraper](https://apify.com/scrapier/instagram-profile-scraper) |
| [Instagram Hashtag Username Scraper](https://apify.com/scrapier/instagram-hashtag-username-scraper) | [Instagram Reels Scraper](https://apify.com/scrapier/instagram-reels-scraper) |
| [Instagram Highlights Scraper](https://apify.com/scrapier/instagram-highlights-scraper) | [Instagram Related Hashtag Stats Scraper](https://apify.com/scrapier/instagram-related-hashtag-stats-scraper) |
| [Instagram Lead Scraper](https://apify.com/scrapier/instagram-lead-scraper) | [Instagram Related Person Scraper](https://apify.com/scrapier/instagram-related-person-scraper) |
| [Instagram Likes Scraper](https://apify.com/scrapier/instagram-likes-scraper) | [Instagram Single Reels Scraper](https://apify.com/scrapier/instagram-single-reels-scraper) |
| [Instagram Location Scraper](https://apify.com/scrapier/instagram-location-scraper) | [Instagram Story Details Scraper](https://apify.com/scrapier/instagram-story-details-scraper) |
| [Instagram Mentions Scraper](https://apify.com/scrapier/instagram-mentions-scraper) | [Instagram Tagged Mentions Posts Scraper](https://apify.com/scrapier/instagram-tagged-mentions-posts-scraper) |
| [Instagram Phone Number Scraper](https://apify.com/scrapier/instagram-phone-number-scraper) | [Instagram Tagged Posts Scraper](https://apify.com/scrapier/instagram-tagged-posts-scraper) |
| [Instagram Post Details Scraper](https://apify.com/scrapier/instagram-post-details-scraper) |  |