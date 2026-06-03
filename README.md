# Pedestal — US Market Opportunity

A 24-month snapshot of **organic US demand** across all 11 Pedestal Shopify
storefronts (Jun 2024 – May 2026). Pedestal has no US-localized store and no
US-targeted ad spend, yet US visitor sessions are substantial and growing fast.
Bot & AI-agent traffic is flagged out so the headline reflects **real people**.

## Start here
Open **`index.html`** in any browser — it's the one-page summary with the
animated maps, growth chart, top markets, and method notes.

## The numbers (real customers, bots/AI agents removed)
- **158,762** real US visitor sessions over 24 months
- **+126%** growth from the first 6 months to the last 6 (≈4.3k → ≈9.7k/mo)
- Top states: **California (28.6k) › New York (18.4k) › Texas (13.3k) › Washington › Florida › Illinois**
- Top cities: **Los Angeles › New York › Brooklyn › San Jose › Chicago › Fort Worth › San Antonio › Seattle**
- California + New York + Texas ≈ **38%** of US demand

## What's in the box
```
index.html                     One-page opportunity summary (open this)
maps/
  states-by-month.html/.gif/.mp4   Animated state choropleth, month by month
  cities-by-month.html/.gif/.mp4   Animated city bubble map (top metros)
charts/
  overview.html / overview.png     Real humans vs bots/AI agents; growth + top markets
data/
  real-customers_state-by-month.csv   Real-customer sessions by state × month
  real-customers_city-by-month.csv    Real-customer sessions by city × month
  all-traffic_state-by-month.csv      All sessions incl. bots/AI agents (for reference)
  all-traffic_city-by-month.csv       All sessions incl. bots/AI agents (for reference)
```
GIF/MP4 work offline. The interactive `.html` maps use a charting library from a
CDN, so they need an internet connection.

## Method & the bot/AI caveat
- **Source:** Shopify "Sessions by location" report, all 11 storefronts, United
  States only, monthly. Figures are **website sessions (visits), not orders.**
- **Why filter bots/AI agents:** ~48% of raw "US sessions" originate from cloud
  datacenters — Council Bluffs IA (Google), Ashburn VA (AWS), North Bergen NJ,
  Forest City NC (Meta), Prineville OR. These are search/AI crawlers, on-demand
  AI fetchers (ChatGPT, Perplexity, Google AI) and uptime/monitoring bots. They
  geolocate to the **server**, not a person, so including them would put the
  "market" wherever Amazon/Google/Meta keep their servers (it makes Iowa and New
  Jersey outrank California). They're excluded from the real-customer view and
  preserved in the `all-traffic_*` files.
- **AI-driven *human* visits are still counted.** When a person reads a ChatGPT
  or Google-AI answer that cites Pedestal and clicks through, that's a normal
  session at their real location — already in the real-customer numbers.
- A finer "AI agents vs other bots" breakdown (by traffic source / user-agent)
  is a logical next step if useful.

*Prepared June 2026 · data through May 2026.*
