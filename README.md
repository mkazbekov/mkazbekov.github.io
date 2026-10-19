# mkazbekov.github.io
Personal website

## Visitor analytics

Cloudflare Web Analytics collects cookie-free traffic and page performance
statistics for `mkazbekov.github.io`. The site remains hosted on GitHub Pages.

To view the data, sign in to [Cloudflare Web Analytics](https://dash.cloudflare.com/?to=/:account/web-analytics)
and select **mkazbekov.github.io**. The dashboard shows visits, page views,
referring websites, countries, device/browser breakdowns, and page performance.
It does not identify visitors by name or email address.

The installation script is at the end of `index.html`. Its beacon token is a
public site identifier, not an API credential. No GitHub secret is required.
Keep this script when updating the page. To disable collection, remove the
script and deploy the change.

Statistics begin after installation; previous visits cannot be recovered.
Ad blockers and disabled JavaScript can prevent visits from being counted.
Your own visits may appear in the dashboard. Data may take a few minutes to
arrive. See [Cloudflare's setup documentation](https://developers.cloudflare.com/web-analytics/get-started/).
