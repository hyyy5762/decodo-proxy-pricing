# Decodo pricing: what its residential, datacenter and mobile plans really cost, and how to pay less per GB

Most people searching for Decodo pricing want one number. What they get instead is a homepage plastered with "from $3.75/GB", "from $0.020/IP" and "from $0.95/1K req" — three different units for three different products, none of which is the total you'll be charged at checkout.

The gap between the advertised rate and the invoice comes from a few predictable places: volume tiers, a wallet you have to pre-fund, VAT, and the fact that Decodo sells residential, ISP, datacenter, mobile and scraping-API products as separate meters. Here's the actual ladder from Decodo's own pages, the fine print that moves the number, and an honest look at whether a pay-as-you-go provider at $1/GB makes more sense for your workload.

## Decodo residential proxies: the full price ladder

Decodo (the company formerly known as Smartproxy) sells residential traffic in monthly packages that taper in price as the package grows. As listed on its residential product page:

| Package | Rate per GB | Total per month |
| --- | --- | --- |
| 3 GB | $3.75 | $11.25 |
| 10 GB | $3.50 | $35.00 |
| 25 GB (the tier it flags as most popular) | $3.25 | $81.25 |
| 50 GB | $3.00 | $150.00 |
| 100 GB | $2.75 | $275.00 |
| Pay as you go | $4.00 | billed on what you use |

All of that is plus VAT, and all of it is billed monthly. What you get for the money, per Decodo's product page: 115M+ IPs across 195+ locations, HTTP(S) and SOCKS5, continent/country/state/city/ZIP/ASN targeting at no extra charge, rotating sessions plus sticky sessions of 1, 10, 30 or 60 minutes (custom durations available), a claimed 99.92% success rate and sub-0.5-second average response time.

The targeting is the part worth noticing. Plenty of residential providers gate city or ZIP-level targeting behind an add-on. Decodo doesn't, and third-party testing backs up that the pricing is competitive. PCMag's comparison reviews have Decodo beating both IPRoyal and Bright Data on price and dashboard usability, and AIMultiple's per-GB benchmark put Decodo at the top of its residential value chart from 10 GB through 10 TB.

## The number on the page isn't the number on the card

A rate of $3.50 or $4.00 per gigabyte looks simple until you use pay-as-you-go.

PCMag's reviewer walked through this directly: pay-as-you-go is listed at $3.50/GB, but Decodo's wallet tokens only come in whole-dollar amounts, so the smallest possible top-up on a 1 GB test is $4. Add tax and that single gigabyte came out to **$4.27**. There's a checkbox at checkout confirming you understand how the wallet works, which suggests other customers have hit the same confusion. The residential page currently lists pay-as-you-go at $4.00/GB, so the sticker has drifted between $3.50 and $4.00 across versions — the wallet minimum is the part that stays put.

Two practical notes from that. First, if you're testing, fund the wallet knowing you'll buy more dollars than gigabytes. Second, if your usage is spiky — heavy this week, nothing for a month — monthly subscriptions are a poor fit, because a 25 GB package doesn't care whether you used it.

## Decodo's other products, and what each one costs

Residential is the headline, but Decodo's pricing question gets messier across the product line because each one has a different unit.

**Datacenter proxies.** Decodo's homepage lists these from $0.020 per IP, and its shared-proxy page advertises shared datacenter traffic as low as $0.50 per GB. PCMag's review reports the per-IP ladder at $5.55/month for 3 IPs scaling to $2,300/month for 2,000 IPs. CNET reports datacenter plans starting at $3.50 for 50 GB with 100 shared IPs. The pool covers 16 countries for shared IPs; dedicated datacenter IPs sit in the US, and you can only target whole countries rather than cities.

**Static residential (ISP) proxies.** PCMag lists these at $9.99/month for 3 IPs, up to $4,000/month for 2,000 IPs.

**Mobile proxies.** Reported at $15/month for 2 GB, capping around $550/month for 100 GB. That works out to roughly $5.50–$7.50 per GB at the entry end, so mobile is not the cheap tier.

**Scraping API.** This is where the per-1,000-request math lives: a free tier at the bottom, then $19, $49 and $99 monthly steps, with per-1K rates sliding from $1.50 down to $0.14 depending on whether you route through regular, JS-rendered or premium proxies. Rate limits step up alongside price, from 10 requests/second on the free tier to 50 on the $99 tier. Decodo also lists a Web Scraping API from $0.09 per 1K requests, a Video Downloader from $0.08/GB and a free AI Parser, though those are separate products with separate meters rather than part of the proxy plans.

One warning that matters more than any single figure above: third-party reviews quote numbers that don't always match the live site. CNET's residential table, for instance, shows a different ladder than Decodo's current page, because tiers get restructured and articles don't get rewritten. Treat any published proxy price, including the ones on this page, as a snapshot and confirm at checkout.

## Free trial, refunds, and the conditions attached

Decodo offers a 3-day free trial with 100 MB of residential traffic — enough to confirm your endpoints work, not enough to benchmark a real scraping job. There's also a 14-day money-back guarantee on eligible subscriptions, but the conditions matter:

- You must have bought through self-service
- You can't have paid with cryptocurrency
- The refund request has to come within 14 days of your first purchase
- Free-trial usage doesn't qualify
- Only first purchases on a given service type count — renewals don't
- You can't have used more than 20% of the plan quota, or 1 GB, whichever comes first
- Enterprise plans are excluded

So the "14-day money-back" headline is real, but it's a narrow window around low usage. If you buy 100 GB and burn 30 GB proving a point, that refund is gone.

## Pay-as-you-go at $1/GB: the DataImpulse alternative

If your actual problem is "I need 10 GB this month to test a scraper and I don't want a subscription," Decodo's monthly ladder is the wrong shape. That's the gap DataImpulse was built for: 90M+ IPs across 195 countries, no subscription, traffic that never expires, entry at $1/GB.

Here's the full plan structure across all four of its proxy products:

| Product | Rate | Entry purchase | Volume pricing | Billing model |
| --- | --- | --- | --- | --- |
| Residential | $1.00/GB | $5 for 5 GB | $0.80/GB at 1 TB, $0.70/GB at 5 TB | Pay-as-you-go, no subscription, traffic never expires |
| Datacenter | $0.50/GB | $5 for 10 GB | $0.45/GB at 1 TB; custom from $2,250 at 5 TB+ | Pay-as-you-go, never expires |
| Mobile (3G/4G/5G/LTE) | $2.00/GB | $5 for 2.5 GB | $1.60/GB at 1 TB; custom from $8,000 at 5 TB+ | Pay-as-you-go, never expires |
| Premium residential | $5.00/GB | $5 for 1 GB | custom from $20,000 at 5 TB+ | Pay-as-you-go; includes dedicated account manager and all targeting |

[👉 Start with the $5 / 5 GB residential plan](https://bit.ly/dataimPulse)

The mechanics, since they decide whether the rate is real for you:

- **Country targeting is included.** State, city, ZIP and ASN targeting on standard residential is billed at 2× the base rate — so a $1/GB plan becomes $2/GB on those routes. Datacenter proxies list state/city/ZIP/ASN as included, though it's worth confirming that with support before you budget on it.
- **Rotating sessions** run on port 823 for HTTP/HTTPS and 824 for SOCKS5. **Sticky sessions** use ports 10000–20000 and hold an IP for 1 to 120 minutes, defaulting to 30.
- **No free trial.** The entry point is a $5 purchase, refundable within 7 days on card payments if you've used less than 80% of the traffic. Crypto purchases aren't refundable.
- **The £/GB comparison at equal volume.** 50 GB on Decodo's residential ladder is $150/month plus VAT. At DataImpulse's $1/GB that's $50 once, and unused gigabytes are still there next quarter. 100 GB is $275 versus $100. 10 GB is $35/month versus $10.

[👉 Compare the four DataImpulse proxy plans](https://bit.ly/dataimPulse)

## What you give up at $1/GB

Cheaper isn't automatically better, and DataImpulse is fairly direct about where it doesn't fit. Its own documentation says the service isn't the right tool if you need static ISP proxies, a fully managed scraping API, or access to banking and government sites. It sells rotating residential, mobile and datacenter proxies for public-data collection — that's the scope.

So if you specifically need a stable ISP IP for a long-lived account, or you want a maintained scraper that handles the parsing for you, Decodo sells both of those and DataImpulse doesn't. Decodo also publishes a 99.92% residential success rate and 99.99% uptime, plus ISO/IEC 27001:2022 certification; DataImpulse publishes a 99.51% success rate, 4.8/5 on G2, ISO certification and GDPR compliance, and claims 500,000+ customers. Both companies source IPs from consenting users, which matters more than price if your pipeline has to survive a procurement review.

Independent reviews are also not uniformly kind to either side. AIMultiple found Decodo's residential pricing to be the value leader in its benchmark, but noted that pay-as-you-go costs far more per GB than subscriptions and that Decodo is weaker than top providers on Facebook and Instagram scraping. CNET gave Decodo a middling value score, tied for the cheapest pay-as-you-go plan but with expensive bulk packages. DataImpulse's documented weak spots are the ones above: no static ISP product, no managed API, and volume discounts that only really kick in at the 1 TB mark on mobile and premium residential.

## Which one fits your invoice

- **You need a few gigabytes to test, once.** DataImpulse. $5 buys 5 GB that never expires, versus a Decodo package where unused gigabytes roll into the next billing cycle's expectation.
- **You run steady, high-volume residential scraping every month.** Decodo's tiered ladder gets to $2.75/GB at 100 GB, and AIMultiple's benchmark puts it at the top of per-GB value at volume. DataImpulse undercuts it at $1/GB, but Decodo's targeting is included rather than surcharged.
- **You need city or ZIP-level targeting at scale.** Decodo includes it free on residential. DataImpulse charges 2× on those routes, which narrows the gap to $2/GB.
- **You need static ISP IPs for account work.** Decodo, at $9.99/month for 3 IPs and up.
- **You need a managed scraping API rather than raw proxies.** Decodo's API tiers start free and run $19/$49/$99 monthly. DataImpulse is proxy-only by design.
- **Your usage is unpredictable.** Pay-as-you-go with non-expiring traffic, either way — but read the wallet quirks above before funding a Decodo wallet.

[👉 Check current DataImpulse pricing and the $5 starter](https://bit.ly/dataimPulse)

## Decodo pricing FAQ

**Is there a free trial for Decodo proxies?**
Yes — 3 days and 100 MB of residential traffic. The 14-day money-back guarantee doesn't apply to purchases made after using the free trial, so you can't stack both.

**Does Decodo's traffic expire?**
Subscription packages are billed monthly, so the practical question is whether unused gigabytes carry over. If that matters to your budget, ask support before buying a large tier. DataImpulse states plainly that purchased traffic never expires.

**What's the cheapest Decodo residential plan?**
$11.25/month for 3 GB at $3.75/GB, plus VAT. Pay-as-you-go is the cheapest way to test a single gigabyte, though the whole-dollar wallet means you'll likely load $4 rather than $3.50.

**Does DataImpulse offer a free trial?**
No. Its entry point is a $5 purchase — 5 GB of residential, 10 GB of datacenter, 2.5 GB of mobile, or 1 GB of premium residential. Card-funded intro purchases carry a 7-day money-back window if less than 80% of the traffic is used.

**Can I pay with cryptocurrency?**
Decodo accepts crypto. On DataImpulse, crypto purchases on intro plans are explicitly non-refundable, so card is the safer route if you might want your money back.

**Which is cheaper for 20 GB of residential traffic?**
Decodo's ladder puts 25 GB at $81.25/month plus VAT. DataImpulse prices 20 GB at $20, one-time, and it stays on your balance until you spend it.

The short version: Decodo's pricing is competitive when you buy residential volume on a monthly rhythm and use its included targeting. It gets expensive and awkward when you buy small, test intermittently, or pay as you go. If that's your pattern, $1/GB with non-expiring traffic is the simpler invoice — and a $5 entry point is a low-stakes way to find out whether the IP pool holds up on your targets.

[👉 Test DataImpulse on your own targets for $5](https://bit.ly/dataimPulse)
