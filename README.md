[Instagram Following Scraper](https://apify.com/instaprism/instagram-following-scraper?fpr=data)

# Instagram Following Scraper - Export Who Any Account Follows 2026

Extract the complete list of accounts that any public Instagram user follows. See who influences your competitors, discover partnership opportunities, and map relationship networks.

## No Login Required

**Your Instagram account stays safe.** This Actor:

- Does NOT require your Instagram login or cookies
- Uses our own infrastructure to fetch data
- Zero risk of account suspension for you
- Works with any public Instagram profile

Unlike browser extensions or tools that use your account, we handle all scraping server-side. Your credentials are never needed.

## Important: Processing Time

**This Actor uses a distributed scraping architecture.** Here's what to expect:

| Data Size | First Results | Complete Results |
| --- | --- | --- |
| 1,000 following | 2-5 min | 5-10 min |
| 5,000 following | 5-10 min | 15-30 min |
| 10,000+ following | 10-20 min | 30-60+ min |

**Why does it take time?**

- Instagram has strict rate limits to prevent spam
- We use multiple proxy servers worldwide to stay undetected
- Large following lists require sequential data fetching

**Don't worry about timeouts!** Our streaming mode saves results every 60 seconds. Even if Apify times out after 24h, you'll have all the data collected up to that point.

## What You Get

- **User ID** - Unique Instagram identifier for each followed account
- **Username** - Instagram handle (without @)
- **Full Name** - Display name from their profile
- **Profile Picture URL** - Direct link to their profile image
- **Verification Status** - Whether the account has a blue checkmark
- **Position** - Order in the following list
- **Timestamp** - When the data was scraped

## Input

| Parameter | Type | Required | Default | Description |
| --- | --- | --- | --- | --- |
| `username` | String | Yes | - | The Instagram username to scrape following from (without the @ symbol) |
| `limit` | Integer | No | 1000 | Maximum number of accounts to extract. Set to 0 for unlimited |
| `extractEmails` | Boolean | No | false | Try to extract contact info from business profiles. Slower but useful for partnership outreach |

### Example Input

```
{
    "username": "garyvee",
    "limit": 2000,
    "extractEmails": false
}
```

## Output

| Field | Type | Example | Description |
| --- | --- | --- | --- |
| `position` | Integer | 1 | Position in the following list |
| `userId` | String | "12345678901" | Unique Instagram user ID |
| `username` | String | "entrepreneur_hub" | Instagram username |
| `fullName` | String | "Entrepreneur Hub" | User's display name |
| `profilePicUrl` | String | "[https://scontent](https://scontent)..." | URL to profile picture |
| `isVerified` | Boolean | true | True if account has blue checkmark |
| `scrapedFrom` | String | "garyvee" | Source account username |
| `scrapedAt` | String | "2026-01-15T10:30:00.000Z" | ISO timestamp of extraction |

### Example Output

```
[
    {
        "position": 1,
        "userId": "12345678901",
        "username": "entrepreneur_hub",
        "fullName": "Entrepreneur Hub",
        "profilePicUrl": "https://scontent-cdg4-1.cdninstagram.com/v/t51.2885-19/...",
        "isVerified": true,
        "scrapedFrom": "garyvee",
        "scrapedAt": "2026-01-15T10:30:00.000Z"
    },
    {
        "position": 2,
        "userId": "98765432109",
        "username": "business_insider",
        "fullName": "Business Insider",
        "profilePicUrl": "https://scontent-cdg4-1.cdninstagram.com/v/t51.2885-19/...",
        "isVerified": true,
        "scrapedFrom": "garyvee",
        "scrapedAt": "2026-01-15T10:30:01.000Z"
    }
]
```

## Use Cases

- **Competitor Intelligence** - Discover who your competitors follow. Find their partners, vendors, and influences.
- **Influencer Research** - Understand who shapes opinions in your industry by analyzing who thought leaders follow.
- **Partnership Discovery** - Find potential partners by seeing who key accounts in your niche follow.
- **Network Mapping** - Build relationship graphs to understand industry connections.
- **Trend Spotting** - See which accounts industry leaders are paying attention to.

## Streaming Mode (Auto-Save)

This Actor uses **streaming mode** to protect your data:

- Results saved to dataset every 60 seconds
- No data loss even on timeout or interruption
- Monitor progress in real-time via logs
- Partial results always available

**Example:** If you're scraping 10,000 following and Apify times out at 7,000, you still get those 7,000 accounts. Just run again to get the rest.

## Integrations

Export your data to:

- **Google Sheets** - Direct integration, auto-sync results
- **Zapier / Make (Integromat)** - Trigger workflows when scrape completes
- **Webhooks** - Get real-time notifications
- **API** - Programmatic access via Apify API
- **Download** - JSON / CSV / Excel files

## FAQ

### Why is my scrape taking so long?

Instagram strictly limits how fast data can be fetched. Our distributed architecture uses multiple proxies worldwide to maximize speed while staying undetected. Accounts following thousands of users naturally take longer because we must fetch data in batches.

### Can I scrape private accounts?

No, this Actor only works with public Instagram profiles. Private accounts require login credentials which we don't support.

### What if the Actor times out?

Your data is safe! Streaming mode saves results every 60 seconds to the Apify dataset. If the run times out, you can download whatever was collected. Then run again to get more.

### What's the difference between followers and following?

**Followers** = people who follow an account. **Following** = accounts that user follows. This scraper extracts the *following* list (who they follow).

### How accurate is the data?

Data is scraped in real-time directly from Instagram. It reflects the current state of the account at scrape time.

### Why would someone want this data?

The accounts someone follows reveal their interests, influences, and network. This is valuable for competitor research, influencer analysis, and partnership prospecting.

### How often can I run this?

As often as you need. Each run is independent. For monitoring changes, set up scheduled runs via Apify.

## Keywords

Instagram following scraper, export Instagram following, Instagram following list, scrape Instagram following, who does account follow, Instagram competitor analysis, Instagram influencer research, Instagram network mapping, Instagram partnership discovery, Instagram data extraction

## Need Custom Solutions?

Looking for **custom scraping**, **higher limits**, or **dedicated infrastructure**?

📩 **Contact us:**

- **Telegram:** [@taskforceorange](https://t.me/taskforceorange)
- **Website:** [social-swarm.com](https://social-swarm.com)

We offer:

- Custom actor development
- Enterprise-grade scraping solutions
- Dedicated proxy infrastructure
- White-label integrations
- Priority support

---

*Built with ❤️ by the InstaPrism team*