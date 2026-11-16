# Vultr coupon code: $300, $250 or $200 — which one to use, what the credit won't cover, and the billing rules that set your real cost (full plan table)

Four promo codes are listed on Vultr's own coupon page right now. **FLY300VULTR** is the largest at $300 in credit, followed by **250VULTRFLY** at $250 and **FLYTWOHUNDRED** at $200. **VULTRMATCH** works differently: it matches your first deposit "dollar for dollar, up to $100."

Every one of them carries the same footnote — promotional credit applies to select products only, cannot be combined with any other offers, new customers only. Those three conditions decide whether the number on the coupon page means anything for the server you actually want to run, so most of this page is about them rather than about hunting for a fifth code.

> **Quick pick:** opening a fresh account and want the longest free runway? Enter FLY300VULTR. Already planning to deposit $100? VULTRMATCH doubles it and its bonus is officially good for 12 months, but it drains half from credit and half from your own cash. Just need a small box? The real entry price is $5/month for 1 GB; the $2.50 plan is IPv6-only and sold in two US locations.
> 👉 See which codes Vultr is listing on its coupon page today

## The four official codes, side by side

| Code | What you get | Who qualifies | The catch |
| --- | --- | --- | --- |
| FLY300VULTR | $300 credit | New customers | Select products only, no stacking |
| 250VULTRFLY | $250 credit | New customers | Same conditions |
| FLYTWOHUNDRED | $200 credit | New customers | Same conditions |
| VULTRMATCH | Deposit doubled, up to $100 | New customers | Requires a deposit; credit spent 50/50 alongside cash |

Coupon sites don't fully agree on the $300 tier. HostCodes, which stamps each offer with its own verification date, lists FLYTWOHUNDRED and 250VULTRFLY as verified on 13 November 2026 and files the $300 offer under "Partner Offer" with no verification date and no stated source. Vultr's own page still presents FLY300VULTR as a plain $300 credit for new customers. Trust the page you're buying from, then confirm the amount in your billing dashboard after signup instead of assuming it landed.

### VULTRMATCH isn't $100 of free hosting

Vultr publishes the mechanics on its own match page, and they change what the offer is worth. The bonus credit expires 12 months after issuance, which is far longer than any other promo here. It's applied on a 50/50 basis: if your hourly accrued balance is $10, $5 comes out of promotional credit and $5 out of real funds.

Run that through a realistic case. Deposit $100, receive $100 bonus, hold $200 of balance. Spending down $200 consumes the whole thing, bonus and deposit together, so the match works out to a 50% discount on your first $200 of usage. If you were going to spend $100 on Vultr regardless, that's a fair deal with unusually long validity. If you were hoping to run a $5 server for twenty months on bonus money, the arithmetic doesn't get there.

Duplicate accounts are explicitly ineligible, and Vultr describes the promotion as time-limited, so it can disappear without notice.

👉 Open the deposit match page and read the current terms before you pay

## What the credit won't pay for

"Select products only" is carrying a lot of weight in that footnote, and Vultr doesn't publish the list. Don't assume GPU instances, bare metal or managed databases qualify until you see the credit applied at checkout. Three more things that catch first-time buyers:

- **Usage past the credit bills at normal rates.** The credit is a balance. Nothing stops you when it reaches zero, and there's no automatic shutdown.
- **Payments are final.** Vultr's terms state that it doesn't offer refunds and that credits are non-refundable. Unused credit is forfeited if you close the account.
- **Codes don't stack.** Vultr's wording is "cannot be combined with any other offers." Aggregators repeat a stricter version, one promo code per user, but that's their interpretation rather than Vultr's published rule. Either way, plan on one.

Vultr also doesn't publish a redemption walkthrough, and HostCodes admits it hasn't confirmed where the promo field sits in the checkout flow. Enter the code before you deploy anything, then check the credit balance on the billing page before you spin up a server.

## Plans and prices

These are the entry configurations of each plan family, checked against Vultr's price list in November 2026. Each family has multiple sizes: the public price list runs to 121 plans across 36 regions, so treat this as the starting point for each line rather than the complete catalogue. The price at checkout is the one you pay.

| Plan | Entry configuration | Price/month | Billing | Get it |
| --- | --- | --- | --- | --- |
| Cloud Compute (IPv6 only) | 1 vCPU, 512 MB, 10 GB SSD, 0.5 TB transfer | $2.50 | Hourly, 672-hour cap | [ See this plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud Compute Regular | 1 vCPU, 512 MB | $3.50 | Hourly, 672-hour cap | [ Check the 512 MB price](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud Compute Regular | 1 vCPU, 1 GB, 25 GB SSD, 1 TB transfer | $5.00 | Hourly, 672-hour cap | [ Start on the 1 GB plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance (NVMe) | 1 vCPU, 1 GB, 25 GB NVMe, 1 TB transfer | $6.00 | Hourly, 672-hour cap | [ Compare the NVMe tier](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Frequency | 1 vCPU, 2 GB, 64 GB NVMe, 3 TB transfer | $12.00 | Hourly, 672-hour cap | [ See High Frequency pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized Cloud Compute | 2 vCPU, 4 GB, 80 GB NVMe, 4 TB transfer | $28.00 | Hourly, 672-hour cap | [ View Optimized plans](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 Cloud Compute | 2 vCPU dedicated, 4 GB, NVMe block storage, 4 TB transfer | $43.80 | Actual hours, no monthly cap | [ See VX1 pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Bare Metal | Single-tenant dedicated server, no virtualization layer | $120.00 | Hourly per server | [ Check bare metal availability](https://www.vultr.com/pricing/?ref=9738262-9J) |

Four things about that table that change how you read it:

**The $2.50 plan isn't a general-purpose server.** It's IPv6-only and sold in New Jersey and Atlanta only. If your ISP, monitoring or clients are IPv4-only, that box is unreachable. The $3.50 512 MB tier has IPv4 but is sold in New Jersey alone, which makes **$5/month the realistic floor** for most people.

**High Frequency starts at $6/month** for smaller sizes; the 2 GB / 64 GB NVMe configuration above is $12.

**São Paulo charges roughly 1.5× these prices.** The other regions bill at list.

**Smaller plans are loss-leaders with limited geography.** If you need a specific city, check availability before you plan around the price.

## When does the credit expire?

The match credit is the only one with a published expiry: 12 months from issuance.

For FLY300VULTR, 250VULTRFLY and FLYTWOHUNDRED, Vultr's coupon page states no expiry at all, and neither do the third-party listings. User reports fill the gap. Reddit users on an earlier $200 promotion said the card-entry screen told them the credit expired 30 days after signup; SimplyCodes, a community-verified coupon site, says these credits "typically expire 30-60 days after account creation" based on member feedback.

Both are third-party reports about past promotions, not current terms. The practical read is to assume roughly a month: sign up when you have something to deploy that week, not when you're still choosing a stack.

## Billing rules that decide your real cost

Most Vultr instances bill hourly with a monthly ceiling of 672 hours. Run a test box for six hours and you pay six hours; leave it up for the full month and you pay the listed monthly price and nothing more. That ceiling is what makes the cheap tiers usable for short jobs.

VX1 is the exception. Launched in October 2025 on dedicated AMD EPYC cores rather than shared vCPUs, it bills actual hours used with no 672-hour cap. Workloads that run in bursts or stay below full-time fit it better than the capped tiers, at an entry price of $43.80/month.

Stopping the meter takes more than powering a server off. Hourly billing continues until you destroy the instance, and snapshots, block storage volumes, load balancers and Kubernetes clusters bill separately. Cancelling at Vultr's billing page doesn't clean those up for you, so delete them first. Traffic between two instances in the same data center is free, which matters if you split an app across boxes.

## Codes on other sites that Vultr doesn't list

One aggregator lists 20 "active" Vultr offers as of 12 November 2026, including NGINX20 for $20, SSDVPS for $27, 25OFF for 25% off, OWNCLOUD for $22 and a $300 tier available "by link" with no code at all. None of these appear on Vultr's coupon page, and the site publishes no per-code verification date. They may be legacy affiliate codes, partner codes or simply entries carried forward long after they stopped working. There's no way to confirm from outside.

HostCodes is more conservative: two code-based offers, both matching codes Vultr publishes itself, plus a standing warning that "listing a code does not establish checkout success."

The failure mode that costs you money is trying an unlisted code, watching it get rejected, and concluding the official ones are dead too. Start with the four on Vultr's own page and work backwards from there.

## Other ways to cut the bill

The code is one lever among several, and for small accounts the others matter more.

**Pick the right entry tier.** $5/month for 1 GB covers a blog, a staging environment or a small API. The $3.50 and $2.50 tiers exist mainly to win a price comparison, and their location restrictions make them awkward for real work.

**Use object storage for static assets.** Vultr prices object storage below instance disk, so images and backups sitting on a $12 server are paying instance rates for storage.

**The student credit.** Sign up with a `.edu` address from an accredited US university and Vultr adds $5 to the account. Small, but it's real and it stacks with nothing.

**The referral program.** Vultr pays up to $100 per referred customer who stays active for 30 days or more.

**`vultr.com/50off/`.** One coupon site says new accounts get 50% off their first two monthly invoices, applied automatically. That claim appears only on third-party pages and isn't confirmed on Vultr's site, so verify it in the invoice before you count on it.

**Black Friday and Cyber Monday.** The third-party estimates conflict: one source says up to 50% off cloud hosting, another says up to $250 in free credits, with a secondary promo window in March and April. Both are observations of past years rather than announcements, so treat the specific numbers as unreliable and the timing as roughly correct.

## How Vultr compares (information only)

|  | Vultr | DigitalOcean | Linode (Akamai) |
| --- | --- | --- | --- |
| Entry VPS price | $3.50/mo (512 MB, one location); $5 for 1 GB | $4/mo | $5/mo (Nanode 1 GB) |
| US data centers | 9 | 4 | 9 |
| Billing granularity | Hourly, 672-hour monthly cap; VX1 uncapped | Per-second, 60-second minimum | Hourly, monthly cap |
| Bare metal | Yes, from $120/mo | No | No |
| New-user credit | Up to $300 with a code | $200 for 60 days | $100 |

Vultr's case rests on footprint and hourly flexibility: nine US locations, bare metal with no virtualization layer, GPU instances, and per-hour billing that only charges for what you run. DigitalOcean's $4 entry undercuts Vultr's $5 general-purpose tier and its per-second billing is finer-grained if you constantly create and destroy servers, but four US locations and no bare metal limit it. Linode matches Vultr's nine US locations and $5 floor and adds Akamai's CDN and DDoS backbone, at the cost of bare metal.

If a dedicated single-tenant box or GPU capacity without a hyperscaler contract is the requirement, Vultr is the only one of the three that covers bare metal.

## Which code fits your case

**You're opening a new account and will deploy within a week.** Use FLY300VULTR. It's the largest credit, needs no deposit, and a month is enough time to burn through a meaningful chunk of $300 on a $5 or $12 server. Just don't sign up a week before you're ready.

**You were going to deposit $100 or more anyway and will spread usage over months.** VULTRMATCH. The 12-month validity is the only long-dated credit here, and a 50% drawdown on the first $200 is a fair trade if your plan involves steady usage rather than a burst. Read the 50/50 rule again before you pay, because it changes what "double your deposit" feels like in practice.

**You need one small box for a few days of testing.** Any of the four codes gets you there, and the size of the number stops mattering. Take FLY300VULTR and spend the rest on learning the platform.

**You already have a Vultr account.** None of these apply; all four are new-customer only, and duplicate accounts are explicitly ineligible. The referral program is the remaining lever.

Two things to confirm before you enter card details: which code actually applied at checkout, and what expiry date the payment screen shows for the credit. Vultr doesn't publish that date on the coupon page, and the number you see there is more reliable than anything a coupon site tells you.

Second, look for idle resources. Snapshots, block storage volumes and load balancers keep billing after you stop using them, and no promo credit changes that.

👉 Start a new Vultr account with the $300 code and confirm the credit before you deploy
