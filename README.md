# smartproxy pricing: Real Decodo Rates, the Fine Print That Changes Your Bill, and a Per-Request Alternative Worth Comparing

Search **smartproxy pricing** today and you'll land on a company called Decodo. Same company, same network, new name — Smartproxy rebranded in 2025, and the old price pages now redirect. The short answer most people want: residential proxies start at **$3.75/GB** on the cheapest self-serve plan, Pay As You Go runs **$4/GB**, and the "$2/GB" figure in the ads only applies to Enterprise volume. Below is the full rate card, the billing rules that quietly change your total, and — since per-GB is only one way to pay for scraping — a side-by-side look at ScraperAPI, which bills per request instead and starts cheaper than you'd expect.

> **Quick buy guide:** If you already know you want Smartproxy/Decodo, the residential table below is your answer — 3 GB at $11.25/month is the entry point. If you're still deciding how to pay for scraping, ScraperAPI charges per request, includes a free plan with 1,000 credits every month and a 7-day trial with 5,000 credits, no credit card required. 👉 [check ScraperAPI's full plan list and current prices](https://www.scraperapi.com/pricing/?fp_ref=coupons)

## Smartproxy pricing now: the full Decodo rate card

Smartproxy pricing is now published under the Decodo name, and the headline number is smaller than the number you'll actually pay. The residential proxies page advertises "starting at just $2/GB," but that rate sits on the Enterprise tab for roughly 1 TB of monthly traffic. The cheapest plan an ordinary buyer can click is **$3.75/GB**.

Here's the residential lineup, quoted before VAT:

| Plan | Monthly price | Per GB |
| --- | --- | --- |
| Pay As You Go | No commitment | $4.00 |
| 3 GB | $11.25 | $3.75 |
| 10 GB | $35.00 | $3.50 |
| 25 GB | $81.25 | $3.25 |
| 50 GB | $150.00 | $3.00 |
| 100 GB | $275.00 | $2.75 |
| Enterprise 250 GB | $625.00 | $2.50 |
| Enterprise 500 GB | $1,125.00 | $2.25 |
| Enterprise 1 TB | $2,000.00 | $2.00 |

All tiers include the full 115M+ IP pool, targeting down to city, ZIP and ASN level at no extra charge, sticky sessions up to 30 minutes, and both HTTP(S) and SOCKS5 support.

The other product lines sit on cheaper meters:

- **Datacenter**: from $0.02/IP, or roughly $0.45/GB on shared plans
- **ISP (static residential)**: advertised from $0.27/IP — but that's the traffic-billed version; the dedicated IPs most people actually need run closer to $2.70–$3.33/IP/month
- **Mobile**: from about $2.25/GB at enterprise volume, with periodic promotions closer to residential pricing
- **Web Scraping API**: from $0.09 per 1,000 requests
- **Site Unblocker**: $0.95 per 1,000 requests
- **Fast Search API**: $0.40 per 1,000 requests

One thing worth noticing in that table: the residential price curve is unusually flat. Going from 3 GB to 100 GB means 33 times the traffic for only 27% less per GB. Big-volume buyers don't get the dramatic discounts that some enterprise-oriented competitors hand out — which is exactly why it pays to compare billing models before committing.

## The Smartproxy pricing fine print that changes your total

The listed rates are only half the picture. Three rules buried in Decodo's billing terms materially affect what you'll spend.

**Pay As You Go and subscriptions are mutually exclusive.** PAYG works through a wallet: you top up, buy traffic in 1 GB chunks at $4/GB, and unused traffic stays valid for 12 months. But you cannot run a PAYG wallet alongside a monthly residential or mobile subscription on the same account. The math matters here: 25 GB on PAYG costs $100 versus $81.25 on the monthly plan, and at 100 GB it's $400 versus $275. If your usage is predictable within about 20% month to month, the subscription wins; if it swings wildly, PAYG's flexibility may justify the premium.

**The 3-day free trial cancels your 14-day money-back guarantee.** This is the single most important line in Decodo's refund policy: taking the 3-day trial (100 MB of traffic) voids the 14-day money-back guarantee, and Decodo states this in its own policy. The trial also requires a payment method and auto-activates your chosen plan when it ends unless you cancel. If you want to test against your real target sites — not just check that the connection works — the safer route is skipping the trial and buying the 3 GB plan, then relying on the refund window.

> Decodo's refund has its own conditions: first purchase only, requested within 14 calendar days, and residential traffic usage below 20% (10% for Enterprise plans). Miss any one of them and there's no refund.

**Residential traffic is billed both ways.** Decodo counts uploaded and downloaded bytes against your GB. Full HTML pages with images, fonts and third-party scripts burn through a gigabyte faster than the page weight suggests, so estimate based on total transfer, not page count.

## ScraperAPI: pricing per request instead of per GB

ScraperAPI takes a different approach to the same problem. Instead of selling proxy traffic, it sells **API credits** — you send a request to its endpoint, and the service handles proxy rotation, CAPTCHA solving, JavaScript rendering and JSON parsing behind the scenes. A standard page costs 1 credit regardless of how many bytes it returns, which makes budgeting a matter of counting pages rather than estimating bandwidth.

The current plan lineup:

| Plan | Price (monthly / billed annually) | API credits | Threads | Geotargeting | Get started |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | 1,000 / month | 5 | — | [ create a free account](https://www.scraperapi.com/?fp_ref=coupons) |
| Hobby | $49 / $44.10 | 100,000 | 20 | US & EU only | [ start with Hobby](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Startup | $149 / $134.10 | 1,000,000 | 50 | US & EU only | [ start with Startup](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Business | $299 / $269.10 | 3,000,000 | 100 | Country-level | [ start with Business](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Scaling | $475 / $427.50 | 5,000,000 | 200 | Country-level | [ start with Scaling](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Professional | $975 / $877.50 | 10,500,000 | 300 | Country-level | [ start with Professional](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Advanced | $1,975 / $1,777.50 | 21,500,000 | 500 | Country-level | [ start with Advanced](https://www.scraperapi.com/pricing/?fp_ref=coupons) |
| Enterprise | Custom quote | 22,000,000+ | 500+ | Country-level | [ talk to sales](https://www.scraperapi.com/pricing/?fp_ref=coupons) |

Annual billing takes 10% off across the board with no coupon needed. Every paid plan carries the same feature set — JavaScript rendering, premium residential and mobile IPs, automatic CAPTCHA handling, JSON auto-parsing, custom sessions, unlimited bandwidth and a 99.9% uptime guarantee — so the only real differences are credits, concurrency and geotargeting range. The free plan's 1,000 monthly credits plus the 7-day trial with 5,000 credits give you roughly a week of real testing before any payment decision, which is a meaningfully longer leash than a 100 MB proxy trial.

## Credit multipliers: ScraperAPI's version of the fine print

Per-request billing has its own catch: a credit doesn't always mean one page. ScraperAPI prices harder targets automatically, and you can't opt out of the domain-based pricing:

- Standard pages (blogs, news, most sites): **1 credit**
- Amazon, Walmart, eBay: **5 credits**
- Google and Bing, including subdomains: **25 credits**
- LinkedIn: **30 credits**
- Bypassing Cloudflare, Datadome or PerimeterX protection: **+10 credits per request**
- JavaScript rendering multiplies the request cost by **10**; premium proxies cost **25 credits** on their own

Run the numbers on the $49 Hobby plan and the spread becomes obvious: 100,000 credits is 100,000 simple pages, 20,000 Amazon product pages, or 4,000 Google SERP pages. Heavy targets on the cheapest plan get expensive fast.

Two official tools keep this under control. The Domain Cost Estimator in the dashboard tells you the exact credit cost for any URL before you scrape it, and the `max_cost` parameter caps what a single request can consume. If your targets are mostly standard pages with occasional Amazon work, the multipliers rarely bite; if your whole project is SERP scraping, do that math before picking a plan.

Two operational limits are worth knowing too. Exceeding your concurrent thread limit returns a 429 error — requests are rejected rather than queued, though you're not charged. And when credits run out, scraping pauses by default until renewal; auto-upgrade to the next tier is opt-in on plans from Hobby through Professional, while pay-as-you-go overage is only available on **Scaling and above**. 👉 [compare the plan limits and annual pricing side by side](https://www.scraperapi.com/pricing/?fp_ref=coupons)

## Which meter fits your job: Smartproxy or ScraperAPI

Both companies are legitimate, and the right choice depends on what you're scraping and how you prefer to pay.

Decodo (Smartproxy) fits when you already have your own scraper and want raw proxy access. Billing by GB makes sense when your targets are lightweight, your volume is stable, and you need features like SOCKS5, 30-minute sticky sessions or 195+ location targeting — all included without surcharges. The 3 GB plan at $11.25 is also the cheapest paid entry point between the two.

ScraperAPI fits when you'd rather ship one API call than maintain proxy logic yourself, or when your pages are mostly "standard" 1-credit targets. It's also the pragmatic pick for low-volume users: the permanent free plan has no Decodo equivalent, and unused Decodo trial access conflicts with the refund guarantee. If your project lives on Google or LinkedIn, though, factor the 25–30 credit multiplier in — at that point a per-GB proxy provider deserves a hard look.

|  | Decodo (Smartproxy) | ScraperAPI |
| --- | --- | --- |
| Billing unit | GB of traffic (both directions) | API credits per request |
| Cheapest paid entry | 3 GB, $11.25/month | Hobby, $49/month |
| Free option | 3-day trial, 100 MB (voids refund) | 1,000 credits/month forever + 7-day trial |
| Geotargeting | Country/city/ZIP/ASN, no surcharge | US & EU on entry plans, country-level from Business |
| Best for | Existing scrapers, stable volume, SOCKS5/sticky sessions | Hands-off scraping, standard pages, low-volume testing |

## Frequently asked questions

**Does the "$2/GB" Smartproxy price apply to regular customers?** No. That rate is the Enterprise 1 TB tier and lives on a separate tab from the standard pricing page. The cheapest self-serve residential rate is $3.75/GB, and Pay As You Go is $4/GB. Budget from the plan you can actually buy.

**Can I use Smartproxy Pay As You Go together with a monthly plan?** No. Decodo's billing system doesn't allow a PAYG wallet and a residential or mobile subscription on the same account simultaneously. Pick one model per billing period.

**Is ScraperAPI cheaper than Smartproxy?** Depends entirely on your targets. For simple pages at 1 credit each, ScraperAPI's Hobby plan works out to less than half a cent per page with rendering and CAPTCHA handling included. For Google (25 credits) or LinkedIn (30 credits) at scale, per-GB proxy pricing usually wins. Check your specific URLs with the Domain Cost Estimator before deciding.

**What happens if I go over my plan's limits?** On ScraperAPI, excess concurrency gets a 429 rejection at no charge, and exhausted credits pause scraping until renewal unless you've enabled auto-upgrade or — on Scaling and above — pay-as-you-go overage. Decodo's residential plans simply stop at your GB cap; you'd top up the wallet or wait for renewal.

## Before you commit

Match the plan to the job, in order of how specific your situation is: scraping Google or LinkedIn heavily → per-GB residential proxy pricing makes more sense than 25–30 credits per page; mostly standard pages or Amazon work, or you want rendering and CAPTCHA solving handled for you → ScraperAPI's Hobby plan at $49 (or $44.10 on annual billing) is the natural starting point, and the free plan means you can verify your target sites cost 1–5 credits before paying anything. If you go the Decodo route, skip the 3-day trial if there's any chance you'll want your money back inside 14 days.

One last check either way: run two or three of your real target URLs through the cost tools before checkout — Decodo's dashboard and 👉 [ScraperAPI's free trial with 5,000 credits](https://www.scraperapi.com/?fp_ref=coupons) will both tell you the true per-page cost in about five minutes, and that number beats every advertised rate on this page.
