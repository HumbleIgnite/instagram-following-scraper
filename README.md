[Instagram Following Scraper](https://apify.com/datavoyantlab/instagram-following-scraper?fpr=data)

# Instagram Following Scraper | No‑Login Instagram Follower Data API

**Scrape any Instagram user’s following list in seconds**—no account needed, no rate limits, no hidden fees.

> 💡 **Usage Notice**
> 
> 
> 
> 
> This actor is available for:
> 
> 
> 
> 
> 1. ✅ **Subscribed Apify users** (full access with usage-based billing).
> 2. ✅ **Approved free users** on the allowlist (limited usage).
> 
> 
> 
> 
> If you're a free user and would like to request access, please **email us at [datavoyant @ gmail .com]** with your Apify username.
> Once approved, you will be added to the allowlist and can use the actor within the free tier limits.

## 🔑 Key Features

- **No Login Required**: Zero risk to your Instagram account.
- **Lightning‑Fast**: Extracts followings at incredible speed—thousands processed in moments.
- **Pay‑Per‑Use**: Only pay for successful scrapes—no subscriptions.
- **Unlimited Scale**: From a single influencer to thousands of profiles.
- **Clean Data**: CSV/JSON output ready for marketing, research, or lead gen.

## 👥 Who It’s For

- Growth hackers & marketers
- Competitive intelligence analysts
- Researchers & developers
- Founders & agencies

## Use Cases

- **Influencer mapping** — see who your competitors or favorite creators follow.
- **Lead generation** — build lists for outreach or research.
- **Community analysis** — discover hidden connections and audience clusters.
- **Market research** — spot trends and rising accounts.

## Why Use This?

- **No Instagram login required** — your account stays safe.
- **Bulk results, instantly** — scrape unlimited followings per run.
- **Much cheaper than competitive actors** — save up to 50% or more on large jobs.
- **Rich profile data** — get full metadata for every followed account.
- **Simple pricing** — only pay for what you actually scrape.
- **Built for automation** — plug into your workflow, CRM, or research pipeline.

## 💰 Pricing

| Usage Scenario | This Actor Cost (USD) | Competitor Cost (USD) |
| --- | --- | --- |
| 1,000 followings scraped | **$0.69** | $1.00 |
| 5,000 followings scraped | $3.45 | $5.00 |

For every $1 spent (including 1 run fee), you can fetch approximately *1,376* followings.

Set a max budget per run to stay in control.

## What You Get (Output Example)

Each output item contains:

- **`username`**: Queried account handle.
- **`following_user`**: Metadata for the followed account:

- **`pk`, `pk_id`, `id`**: Internal user ID.
- **`full_name`**: Display name.
- **`is_private`**: Profile privacy status.
- **`fbid_v2`**: Facebook‐linked ID.
- **`third_party_downloads_enabled`**: Media download permission.
- **`strong_id__`**: Same as primary key.
- **`profile_pic_id`**: Profile picture asset ID.
- **`profile_pic_url`**: Profile picture URL.
- **`is_verified`**: Verification badge status.
- **`username`**: Followed account handle.
- **`has_anonymous_profile_picture`**: Default avatar flag.
- **`account_badges`**: Special badges array.
- **`latest_reel_media`**: Last Reel post timestamp.
- **`is_favorite`**: Marked-as-favorite flag.

Example:

```
{
  "username": "natgeo",
  "following_user": {
    "pk": "185546187",
    "pk_id": "185546187",
    "id": "185546187",
    "full_name": "Ed Sheeran",
    "is_private": false,
    "fbid_v2": 17841400305612899,
    "third_party_downloads_enabled": 1,
    "strong_id__": "185546187",
    "profile_pic_id": "3595459408358341063_185546187",
    "profile_pic_url": "https://scontent-iad3-2.cdninstagram.com/v/t51.2885-19/485753879_649341171019201_6702228279932360473_n.jpg?stp=dst-jpg_e0_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-iad3-2.cdninstagram.com&_nc_cat=1&_nc_oc=Q6cZ2QGQGEIWzHv23CpFM18aO_kr_8yB3Os4JlQ6ebSkbR9nmcj7iQ1-pCETw5jZqy4IJ8M&_nc_ohc=nHQ0NHXgsHQQ7kNvwG9K2qb&_nc_gid=isiHZJpRZlb1HmzYA1o1jA&edm=ALB854YBAAAA&ccb=7-5&ig_cache_key=GBcE9BzBLdaFkk4CABkX8lQcGQNdbkULAAAB-ccb7-5&oh=00_AfQzsKYJezJTjeT61rUKQf7NCjT4TGgmcURjx-rIbtu57w&oe=688B0F69&_nc_sid=ce9561",
    "is_verified": true,
    "username": "teddysphotos",
    "has_anonymous_profile_picture": false,
    "account_badges": [],
    "latest_reel_media": 1753551049,
    "is_favorite": false
  }
}
```

## How It Works

1. Enter one or more Instagram usernames (public accounts only).
2. Run the actor.
3. Download your structured data.

## Automation & Integrations

Connect this actor to your favorite tools, APIs, or cloud services for automated workflows, alerts, and CRM enrichment.

## Support & Feedback

Questions or feature requests? Open an issue in the Apify Console or contact support through the platform.

**Get started now and unlock the real following data behind any public Instagram account.**

## Legal and Ethical Considerations

Our Instagram Following Scraper is designed for ethical use and only downloads publicly shared content. However, be aware that:

- Results may contain personal data protected by GDPR and other regulations
- You should not scrape personal data unless you have a legitimate reason to do so
- Consult legal advice if unsure about the legitimacy of your use case

## Integrations

Connect Instagram Following Scraper with various cloud services and web apps through the [Apify platform](https://apify.com/integrations), including:

- Zapier
- Make
- Slack
- Airbyte
- GitHub
- Google Sheets
- Google Drive

Use [webhooks](https://docs.apify.com/integrations/webhooks) to trigger actions based on events, such as receiving notifications when an extraction completes.

## Using Instagram Following Scraper with the Apify API

The Apify API gives you programmatic access to the Apify platform. The API is organized around RESTful HTTP endpoints that enable you to manage, schedule, and run Apify actors. The API also lets you access any datasets, monitor actor performance, fetch results, create and update versions, and more.

To access the API using Node.js, use the apify-client NPM package. To access the API using Python, use the apify-client PyPI package.

Check out the [Apify API reference](https://docs.apify.com/api/v2) docs for full details, or click on the [API tab](https://apify.com/datavoyantlab/instagram-following-scraper/api) for code examples.

## Feedback and Support

We value your input! If you encounter any issues or have suggestions for improvement.

1. Visit the [Issues tab](https://apify.com/datavoyantlab/instagram-following-scraper/issues) in Apify Console
2. Create a new issue describing your feedback or the bug you've found

Your feedback helps us continually enhance the Instagram Following Scraper's performance and functionality.

Meta Description: Extract any public Instagram user’s following list in seconds—no login, no limits, pay‑per‑use. Ideal for marketers, researchers, and developers.