# VPS Black Friday deals 2026: what BandwagonHost actually offers, which plans are worth buying early, and how its recurring discounts really work

Search for VPS Black Friday deals 2026 in September and you'll mostly find two things: coupon sites recycling last year's numbers, and deal roundups promising "up to 80% off" from hosts you've never heard of. Neither is very useful if you're actually about to spend money on a VPS.

This article takes a different angle. Instead of guessing what discounts might appear in late November, it looks at one specific vendor that dominates this search niche — **BandwagonHost** (often shortened to BWH, or 搬瓦工 in the Chinese-speaking community) — and answers the questions that actually matter: what does this host sell right now, what do the plans cost, what did its past Black Friday events look like, and what should you do if you need a server before Black Friday even starts?

Everything below is based on BandwagonHost's current official plan pages and pricing, cross-checked against independent community archives that have tracked the company's promotions for years.

## First, the awkward truth about BandwagonHost and Black Friday

If you're expecting a blowout "80% off everything" event, BandwagonHost is the wrong host to wait for. Its Black Friday history is well documented, and it looks like this:

- **2018** was the classic year: dedicated Black Friday VPS plans, with the CN2 GIA special plan dropping to roughly $33.68/year and the CN2 plan to about $25.88/year — still cited by community archivists as some of the lowest CN2 GIA prices the company has ever offered.
- **2019 through 2021** brought sitewide recurring coupon codes: `BWH2019BF` at around 11% off, followed by `BWH2020BF` and `BWH2021BF` at around 10%. The key detail: these codes applied to renewals too, so the discount stuck with the plan for life.
- **2022, 2023 and 2024** had no dedicated Black Friday promotion at all. The company had shifted upmarket — average plan prices climbed, and it leaned on limited-edition restocks instead of coupons.
- **2025** skipped Black Friday again, but dropped an 11% sitewide recurring code (`ILOVEBANDWAGON`) during the Double 11 shopping period in early November — and then quietly retired its regular standing coupon codes.

There's a pattern here. BandwagonHost's version of a "deal" is either a short-lived recurring code in the 6–11% range, or a limited-edition plan priced far below the regular lineup. Coupon aggregators currently list Black Friday–branded offers of "up to 7% off" for BandwagonHost, but that's the same recurring-discount territory the host has always occupied — not a dramatic one-day sale.

So if your whole plan is "wait until November 27 and grab a half-price VPS," adjust your expectations now.

## What BandwagonHost actually sells in 2026

BandwagonHost runs self-managed KVM VPS on its in-house **KiwiVM** control panel. Every plan includes full root access, free automatic backups, free snapshots, instant rDNS management, and free migration between datacenters (the regular plans, that is — more on that later). All plans carry a 30-day refund policy, and standard plans are advertised with a 99.95% uptime guarantee.

The current lineup falls into a few distinct families, and the differences matter more than any coupon code.

### The regular KVM line — cheap, decent, flexible

This is the entry tier. Intel Xeon CPUs, RAID-10 SSD storage, 1Gbps ports, and a long list of datacenter locations (Los Angeles, New York, Amsterdam, Fremont, and more). It's genuinely cheap — the smallest plan is **$49.99/year** — and you can move between locations at any time without losing data.

If your goal is "a cheap VPS that works," this line is the answer. If your goal is "a VPS that's fast from mainland China," keep reading, because the regular KVM line doesn't use China-optimized routes.

### The CN2 GIA-E line — the reason most people buy BandwagonHost

BandwagonHost's reputation was built on its **CN2 GIA** connectivity: China Telecom's premium low-congestion transit network, which the company uses (alongside CTGNet, China Unicom Premium and China Mobile CMIN2) on its China-optimized plans. On its own network page, BandwagonHost notes that CN2 GIA transit can cost as much as $120 per megabit in some markets — which is why these plans cost more than generic VPS, and why regular 163/AS4134 routing congests badly during China's evening peak hours.

The **CN2 GIA-E (E-Commerce)** line starts at **$49.99/quarter or $169.99/year** for 2 vCPU, 1GB RAM, 20GB SSD and 1TB traffic on a 2.5Gbps port. The big practical perk: these plans can migrate between 12+ locations, including Los Angeles DC6 (CN2 GIA-E), DC9 (CN2 GIA), Osaka (Softbank route) and Amsterdam (Unicom premium route). If a route degrades, you move. That flexibility is a real feature, not marketing filler.

### The SLA line — for when downtime actually costs you money

The **E-Commerce SLA** line runs on AMD EPYC hardware with ECC RAM and NVMe storage in Los Angeles (USCA_5), and is the only line backed by a contractual **99.99% SLA**. It uses the same premium China routing (CN2 GIA/CTGNet, Unicom AS10099, CMIN2), and the facility carries SOC 1/SOC 2, ISO 27001 and PCI DSS certifications. Entry price: **$65.89/quarter or $239.99/year**.

### Hong Kong, Tokyo, Osaka and Singapore — low latency, high price

For minimum latency, BandwagonHost offers CN2 GIA plans physically in Hong Kong, Tokyo, Osaka and Singapore. Hong Kong's entry plan is **$89.99/month or $899.99/year** — excellent routing, but you're paying a steep premium for proximity. Osaka and Singapore start notably lower at **$49.99/month or $499.99/year** for the same 2GB configuration, with slightly higher latency. Tokyo sits between the two.

## The full plan comparison table

Here is the complete current lineup, taken from BandwagonHost's official plan pages (prices in USD, verified against the live checkout catalog). Each link goes through to the plan's order page.

**Regular KVM line (multiple locations, free migration):**

| Plan | CPU | RAM | Storage | Traffic/mo | Port | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM | 2 vCPU | 1 GB | 20 GB | 1 TB | 1 Gbps | $49.99/yr | [ See the 20G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| 40G KVM | 3 vCPU | 2 GB | 40 GB | 2 TB | 1 Gbps | $52.99/semi-yr, $99.99/yr | [ Check the 40G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| 80G KVM | 4 vCPU | 4 GB | 80 GB | 3 TB | 1 Gbps | $19.99/mo – $199.99/yr | [ View the 80G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| 160G KVM | 5 vCPU | 8 GB | 160 GB | 4 TB | 1 Gbps | $39.99/mo – $399.99/yr | [ View the 160G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| 320G KVM | 6 vCPU | 16 GB | 320 GB | 5 TB | 1 Gbps | $79.99/mo – $799.99/yr | [ View the 320G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| 480G KVM | 7 vCPU | 24 GB | 480 GB | 6 TB | 1 Gbps | $119.99/mo – $1,199.99/yr | [ View the 480G KVM plan](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

**CN2 GIA-E (E-Commerce) line — 12+ switchable locations, 2.5Gbps ports:**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| CN2 GIA-E 20G | 2 vCPU | 1 GB | 20 GB | 1 TB | $49.99/qtr, $169.99/yr | [ Check the CN2 GIA-E entry plan](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| CN2 GIA-E 40G | 3 vCPU | 2 GB | 40 GB | 2 TB | $89.99/qtr, $299.99/yr | [ Check the CN2 GIA-E 2GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| CN2 GIA-E 80G | 4 vCPU | 4 GB | 80 GB | 3 TB | $56.99/mo – $549.99/yr | [ View the CN2 GIA-E 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| CN2 GIA-E 160G | 6 vCPU | 8 GB | 160 GB | 5 TB | $86.99/mo – $879.99/yr | [ View the CN2 GIA-E 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| CN2 GIA-E 320G | 8 vCPU | 16 GB | 320 GB | 8 TB | $159.99/mo – $1,599.99/yr | [ View the CN2 GIA-E 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| CN2 GIA-E 640G | 10 vCPU | 32 GB | 640 GB | 10 TB | $289.99/mo – $2,759.99/yr | [ View the CN2 GIA-E 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| CN2 GIA-E 1280G | 12 vCPU | 64 GB | 1.28 TB | 12 TB | $549.99/mo – $5,399.99/yr | [ View the CN2 GIA-E 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |

**E-Commerce SLA line (Los Angeles USCA_5, 99.99% SLA, AMD EPYC + NVMe):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| SLA 20G | 2 vCPU | 1 GB ECC | 20 GB NVMe | 1 TB | $65.89/qtr, $239.99/yr | [ Compare the SLA entry plan](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| SLA 40G | 3 vCPU | 2 GB ECC | 40 GB NVMe | 2 TB | $116.99/qtr, $399.99/yr | [ View the SLA 2GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| SLA 80G | 4 vCPU | 4 GB ECC | 80 GB NVMe | 3 TB | $69.99/mo – $699.99/yr | [ View the SLA 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| SLA 160G | 6 vCPU | 8 GB ECC | 160 GB NVMe | 5 TB | $109.99/mo – $1,099.99/yr | [ View the SLA 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| SLA 320G | 8 vCPU | 16 GB ECC | 320 GB NVMe | 8 TB | $199.99/mo – $1,999.99/yr | [ View the SLA 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| SLA 640G | 10 vCPU | 32 GB ECC | 640 GB NVMe | 10 TB | $369.99/mo – $3,699.99/yr | [ View the SLA 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| SLA 1280G | 12 vCPU | 64 GB ECC | 1.28 TB NVMe | 12 TB | $699.99/mo – $6,999.99/yr | [ View the SLA 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| SLA 1280G+ | 12 vCPU | 64 GB ECC | 1.28 TB NVMe | 15 TB | $879.99/mo – $8,799.99/yr | [ View the SLA 15TB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| SLA 1280G++ | 12 vCPU | 64 GB ECC | 1.28 TB NVMe | 20 TB | $1,159.99/mo – $11,598.99/yr | [ View the SLA 20TB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

**Hong Kong CN2 GIA line (Equinix HK2, tri-network direct routes, no migration):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| HK 40G | 2 vCPU | 2 GB | 40 GB | 500 GB | $89.99/mo, $899.99/yr | [ Check Hong Kong CN2 GIA stock](https://bandwagonhost.com/aff.php?aff=79616&pid=95) |
| HK 80G | 4 vCPU | 4 GB | 80 GB | 1 TB | $155.99/mo – $1,559.99/yr | [ View the HK 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=96) |
| HK 160G | 6 vCPU | 8 GB | 160 GB | 2 TB | $299.99/mo – $2,999.99/yr | [ View the HK 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=97) |
| HK 320G | 8 vCPU | 16 GB | 320 GB | 4 TB | $589.99/mo – $5,899.99/yr | [ View the HK 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=98) |
| HK 640G | 10 vCPU | 32 GB | 640 GB | 6 TB | $989.99/mo – $9,989.99/yr | [ View the HK 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=122) |
| HK 1280G | 12 vCPU | 64 GB | 1.28 TB | 8 TB | $1,889.99/mo – $18,989.99/yr | [ View the HK 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=124) |

**Tokyo CN2 GIA line (Equinix TY8, 1.2Gbps port, no migration):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| Tokyo 40G | 2 vCPU | 2 GB | 40 GB | 500 GB | $89.99/mo, $899.99/yr | [ Check Tokyo CN2 GIA stock](https://bandwagonhost.com/aff.php?aff=79616&pid=108) |
| Tokyo 80G | 4 vCPU | 4 GB | 80 GB | 1 TB | $155.99/mo – $1,559.99/yr | [ View the Tokyo 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=109) |
| Tokyo 160G | 6 vCPU | 8 GB | 160 GB | 2 TB | $299.99/mo – $2,999.99/yr | [ View the Tokyo 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=110) |
| Tokyo 320G | 8 vCPU | 16 GB | 320 GB | 4 TB | $589.99/mo – $5,899.99/yr | [ View the Tokyo 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=111) |
| Tokyo 640G | 10 vCPU | 32 GB | 640 GB | 6 TB | $989.99/mo – $9,989.99/yr | [ View the Tokyo 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=123) |
| Tokyo 1280G | 12 vCPU | 64 GB | 1.28 TB | 8 TB | $1,889.99/mo – $18,989.99/yr | [ View the Tokyo 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=125) |

**Osaka CN2 GIA line (Equinix Osaka, 1.5Gbps port, CN2 GIA return route):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| Osaka 40G | 2 vCPU | 2 GB | 40 GB | 500 GB | $49.99/mo, $499.99/yr | [ Check Osaka CN2 GIA stock](https://bandwagonhost.com/aff.php?aff=79616&pid=134) |
| Osaka 80G | 4 vCPU | 4 GB | 80 GB | 1 TB | $86.99/mo – $869.99/yr | [ View the Osaka 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=135) |
| Osaka 160G | 6 vCPU | 8 GB | 160 GB | 2 TB | $165.99/mo – $1,665.99/yr | [ View the Osaka 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=136) |
| Osaka 320G | 8 vCPU | 16 GB | 320 GB | 4 TB | $329.99/mo – $3,279.99/yr | [ View the Osaka 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=137) |
| Osaka 640G | 10 vCPU | 32 GB | 640 GB | 6 TB | $549.99/mo – $5,549.99/yr | [ View the Osaka 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=138) |
| Osaka 1280G | 12 vCPU | 64 GB | 1.28 TB | 8 TB | $1,059.99/mo – $10,559.99/yr | [ View the Osaka 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=139) |

**Singapore CN2 GIA line (Equinix SG1, up to 5Gbps port):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| SG 40G | 2 vCPU | 2 GB | 40 GB | 500 GB | $49.99/mo, $499.99/yr | [ Check Singapore CN2 GIA stock](https://bandwagonhost.com/aff.php?aff=79616&pid=173) |
| SG 80G | 4 vCPU | 4 GB | 80 GB | 1 TB | $86.99/mo – $869.99/yr | [ View the SG 4GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=174) |
| SG 160G | 6 vCPU | 8 GB | 160 GB | 2 TB | $165.99/mo – $1,665.99/yr | [ View the SG 8GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=175) |
| SG 320G | 8 vCPU | 16 GB | 320 GB | 4 TB | $329.99/mo – $3,199.00/yr | [ View the SG 16GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=176) |
| SG 640G | 10 vCPU | 32 GB | 640 GB | 6 TB | $549.99/mo – $5,549.99/yr | [ View the SG 32GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=177) |
| SG 1280G | 12 vCPU | 64 GB | 1.28 TB | 8 TB | $1,059.99/mo – $10,559.99/yr | [ View the SG 64GB plan](https://bandwagonhost.com/aff.php?aff=79616&pid=178) |

**Dubai E-Commerce line (AEDXB_1 + 12+ switchable locations, 1Gbps port):**

| Plan | CPU | RAM | Storage | Traffic/mo | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- | --- |
| Dubai 20G | 2 vCPU | 1 GB | 20 GB | 500 GB | $19.99/mo, $169.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 40G | 3 vCPU | 2 GB | 40 GB | 1 TB | $32.99/mo – $299.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 80G | 4 vCPU | 4 GB | 80 GB | 2 TB | $56.99/mo – $549.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 160G | 6 vCPU | 8 GB | 160 GB | 3 TB | $86.99/mo – $879.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 320G | 8 vCPU | 16 GB | 320 GB | 4 TB | $159.99/mo – $1,599.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 640G | 10 vCPU | 32 GB | 640 GB | 5 TB | $289.99/mo – $2,759.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |
| Dubai 1280G | 12 vCPU | 64 GB | 1.28 TB | 6 TB | $549.99/mo – $5,399.99/yr | [ Check the full E-Commerce lineup](https://bit.ly/BandwagonHost) |

## Limited-edition plans: where the real "deals" live

Here's the part most Black Friday roundups miss. For BandwagonHost, the closest thing to a genuine discount isn't a coupon — it's the **limited-edition plan** rotation. These are small-batch plans sold at a fraction of the regular price, often tied to one datacenter, and they routinely sell out within hours of a restock. Community trackers that follow the host's inventory describe exactly this pattern: THE PLAN, MINICHICKEN, the Box series and the Tokyo limited plans vanish fastest and return unpredictably.

Plans that have appeared in this rotation recently include:

- **MINICHICKEN** — $19/year for 1 vCPU, 1GB RAM, 20GB SSD, 1TB traffic at 1Gbps, locked to the Fremont datacenter (HE route). No datacenter migration. Cheapest way into BandwagonHost, period.
- **BiggerBox Pro** — $39/year for similar specs on a 2.5Gbps port, hosted in Los Angeles DC1 with tri-network CN2 GIA / CMIN2 / Unicom premium routing. Upgradable to the MEGABOX-PRO tier.
- **MEGABOX PRO** — $49/year (list price before discounts) for 2 AMD cores, 2GB RAM, 40GB SSD, 2TB traffic at 2.5Gbps, also in LA DC1. For the price, the specs are far beyond anything in the regular lineup.
- **Amsterdam limited edition** — $39/year, 1 vCPU, 1GB RAM, 1TB traffic at 2.5Gbps, with tri-network CN2 GIA return routing from Europe. Historically restocked rarely.
- **DC6 Plan** — $53/year, CN2 GIA-E routing out of Los Angeles DC6.
- **THE PLAN / The Tokyo Plan v2** — $99/year for 2 cores, 2GB RAM, 40GB SSD and 1TB traffic. THE PLAN's appeal is location freedom: 18 datacenters to choose from, and it was restocked at that price in 2026. The Tokyo Plan v2 locks you to Tokyo DC39v2 with CMI tri-network direct return routing at 5Gbps.

Compare that to the regular CN2 GIA-E line: THE PLAN costs $99/year while the closest regular equivalent configuration runs $299.99/year. That's the actual discount mechanism — a 60-70% effective saving baked into the plan price, available whether or not it's November.

The catch is availability. [👉 Check which limited plans are currently in stock](https://bit.ly/BandwagonHost) before you plan anything around them, because the answer changes week to week.

## How discounts actually work at BandwagonHost

A few mechanics are worth understanding before you buy, because they change the math:

**Recurring codes beat one-time codes.** BandwagonHost's promotional codes have historically applied to every renewal, not just the first invoice. A 6.77% code (the most recent widely reported one was `NODESEEK2026`, released in early 2026) saves you the same percentage every year for as long as you keep the plan. Whether any given code is still active changes without much notice, so always test it in the cart's "Promotional Code" field at checkout — if it's expired, the cart will tell you immediately.

**Activity codes cluster around November.** Double 11 and Black Friday are when the bigger 10–11% codes have historically appeared. In 2025, `ILOVEBANDWAGON` delivered 11% off sitewide during Double 11. There is no guarantee of a 2026 repeat, but if you're buying an expensive plan (SLA line, Hong Kong, Tokyo), a few weeks of patience around November could be worth 10% off every future renewal — roughly $90/year on a $899.99 Hong Kong plan.

**Annual billing is where the real savings sit.** On most plans, paying annually costs less than half of what twelve monthly payments would. The 80G KVM plan, for example, is $19.99/month or $199.99/year — annual billing effectively gives you two months free before any code even enters the picture.

**The 30-day refund policy lowers the risk.** New customers can request a refund within 30 days, which makes "buy now, see if the network suits you" a reasonable strategy rather than a gamble.

## A realistic buying strategy for Black Friday 2026

Putting all of this together, here's what the evidence actually supports:

1. **If you need a server now, buy now.** The regular KVM and CN2 GIA-E lines are always available, and the 30-day refund covers buyer's remorse. Waiting two months to maybe save 10% on a $49.99/year plan isn't worth the two months.
2. **If you want a limited-edition plan, don't wait for Black Friday — watch for restocks instead.** Restocks happen year-round and sell out in hours. Black Friday week does historically see restock activity, but so does every other month, and betting on one specific week is a good way to end up with nothing.
3. **If you're buying an expensive annual plan, timing around November is rational.** An 11% recurring discount on a $899.99/year Hong Kong plan pays for the wait. Just set a reminder for early November rather than relying on the deal finding you.
4. **Test whatever code you find at checkout.** Coupon sites list codes that expired months ago. The cart is the only source of truth.

The honest summary: BandwagonHost is unlikely to ever be the host that tops a "biggest Black Friday discount" list, because it doesn't play that game. What it offers instead is a plan lineup with unusually strong China-optimized routing, prices that are already competitive on annual billing, and a limited-edition system where the genuine bargains live — if you're quick enough to catch them. If your search for VPS Black Friday deals 2026 is really a search for "the best long-term value on a China-optimized VPS," that combination is worth more than a one-weekend 80% banner.
