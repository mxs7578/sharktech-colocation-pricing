# data centre colocation: what Sharktech charges in each city, what the price actually includes, and how to choose between a 1U slot and a full rack

Colocation means you keep your own servers and rent the space around them: rack units, power, cooling, physical security and network connectivity inside someone else's data centre. If you've been searching for "data centre colocation", you're probably weighing two questions: what does a rack slot realistically cost, and which provider won't sting you with hidden fees. This piece answers both using Sharktech's published colocation pricing — a provider that runs five data centres across the US and Europe and includes DDoS-protected networking on every plan.

> **Quick verdict:** for most self-hosters and small businesses with their own hardware, the sensible entry point is Sharktech's **Chicago 1–6U plan at $35/month** — it includes 200–1200W of power, 10–100Gbps connectivity with transfer starting at 300TB, and 24/7 on-site support. Running several servers? The Chicago full rack (10–42U, up to 5500W) starts at **$280/month**. 👉 Check Sharktech's current colocation pricing

## What data centre colocation actually is

Colocation ("colo") is a rental model where a data centre provides space, power, cooling and physical security for hardware you own. You buy and configure the servers; the facility runs everything around them. The term gets shortened to "colo" in the industry, and larger facilities that host equipment from many companies are sometimes called carrier hotels.

The practical difference from renting cloud servers is control. You pick the hardware, you own it outright, you can physically touch it (or have the facility's staff do it), and you're not paying a cloud provider's margin on compute every month. The trade-off is that you're responsible for the machines themselves — capacity planning, replacements, hardware failures.

Sharktech runs colocation out of five locations: Los Angeles, Las Vegas, Denver, Chicago and Amsterdam. Rather than owning the buildings, it operates within enterprise-grade facilities run by Equinix, CoreSite, H5 Data Centers and CrownCastle, and guarantees 99.99% uptime. The company itself started out in 2003 as a DDoS-mitigation provider, which is why protected networking shows up across its entire product line rather than as an upsell.

## Sharktech colocation pricing: every published plan, location by location

Sharktech prices colocation in two tiers per city — a 1–6U slot tier and a 10–42U full rack tier — with identical network capacity across all locations. Here's the full published table:

| Location | Space | Power | Network & transfer | Price/month | Order |
| --- | --- | --- | --- | --- | --- |
| Chicago | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | **$35** | [Order Chicago 1–6U](https://bit.ly/SharKtech) |
| Chicago | 10–42U full rack | 1600–5500W | 10–100Gbps, 300TB+ | **$280** | [Order Chicago full rack](https://bit.ly/SharKtech) |
| Las Vegas | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | $65 | [Order Las Vegas 1–6U](https://bit.ly/SharKtech) |
| Las Vegas | 10–42U full rack | 1600–5500W | 10–100Gbps, 300TB+ | $520 | [Order Las Vegas full rack](https://bit.ly/SharKtech) |
| Denver | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | $65 | [Order Denver 1–6U](https://bit.ly/SharKtech) |
| Denver | 10–42U full rack | 1600–5500W | 10–100Gbps, 300TB+ | $520 | [Order Denver full rack](https://bit.ly/SharKtech) |
| Los Angeles | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | $99 | [Order Los Angeles 1–6U](https://bit.ly/SharKtech) |
| Los Angeles | 10–42U full rack | 1600–5500W | 10–100Gbps, 300TB+ | $792 | [Order Los Angeles full rack](https://bit.ly/SharKtech) |
| Amsterdam | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | $99 | [Order Amsterdam 1–6U](https://bit.ly/SharKtech) |
| Amsterdam | 10–42U full rack | 1600–5500W | 10–100Gbps, 300TB+ | $792 | [Order Amsterdam full rack](https://bit.ly/SharKtech) |

A note on the headline numbers: Sharktech's main colocation page quotes general starting points of $79/month for 1–6U and $449/month for a full rack. The per-location figures above, which are consistent across multiple independent write-ups of the company's published pricing, show that Chicago sits well below those quoted entry points. Prices are monthly, billed in USD, and non-standard requirements (partial cabinets, higher power density, private cages, multiple racks) are quoted individually by the sales team.

### Why the same rack costs 65% more in Los Angeles than in Chicago

The price differences between cities have nothing to do with features. Every location gets the same network (up to 100Gbps), the same transfer allowance (from 300TB) and the same DDoS-protected backbone. What you're paying for is the power envelope and the cost of the location itself — and the published pricing breakdown traces Chicago's unusually low rates to Sharktech's power costs there.

That spread is substantial. The identical 1–6U slot runs $35 in Chicago and $99 in Los Angeles or Amsterdam — roughly 65% more. For a full rack it's $280 versus $792. If your users are spread out or your latency requirements are loose, putting hardware in Chicago is the cheapest way into any of Sharktech's facilities by a wide margin. Amsterdam and Los Angeles make sense when proximity to a specific market or peering hub genuinely matters, or when you want US and EU deployments under one provider for failover.

## What the price includes — and what it doesn't

Every plan bundles the same core set: rack space within the stated power envelope, redundant power and backup generators, cooling, 10–100Gbps connectivity with transfer starting at 300TB, DDoS-protected networking, physical access controls, and 24/7 on-site technical staff. Independent summaries of Sharktech's plans put the included DDoS mitigation at around 40 Gbps, with the company claiming its nodes can absorb attack traffic of 300 Gbps and above. For context, standalone DDoS mitigation from other providers is typically billed at $50 to several hundred dollars per month, so having it included at the $35 tier is the single biggest value differentiator here. 👉 See Sharktech's full colocation plan details

What's *not* automatically covered is where colocation newbies get surprised. Sharktech's own colocation page tells you to review power, connectivity and any installation or remote-hands charges before ordering — meaning installation fees and per-task remote hands work (a reboot, a drive swap) may be quoted separately. Recent market analyses of colocation pricing also flag the usual suspects across the industry: power overages beyond your included envelope, premium bandwidth tiers, cross-connects, and IP addresses beyond your initial allocation. None of these are Sharktech-specific, but the official deployment guidance is explicit that you should get an itemized quote for anything custom before shipping hardware.

One more billing detail worth knowing from customer feedback: cancelling service means terminating your own PayPal subscription — several older Trustpilot reviews mention it. Set a calendar reminder if you ever wind down a deployment.

## How Sharktech's pricing stacks up against the market

Against published market rates, Sharktech's table reads aggressive. Recent colocation pricing analyses put retail 1U slots in tier-1 US markets at roughly $85–150/month with limited power and bandwidth, and full 42U cabinets at $1,000–2,000+/month once you factor in around 5kW of power and meaningful transfer. Per-kW pricing in the hottest markets — Chicago and Northern Virginia — hit $200–230 per kW per month in early 2026, while secondary markets like Las Vegas, Denver and Amsterdam typically run 30–50% below primary-market rates.

Set Sharktech's numbers next to that: a Chicago full rack with up to 5500W and 300TB+ of transfer on a 10–100Gbps backbone for $280/month lands well below comparable retail colocation in the same city. Even the $792 Los Angeles and Amsterdam cabinets sit in the lower-middle of their typical market ranges — and the hardware lives in carrier-grade Equinix and CoreSite facilities. Market-wide, the same analyses note the average US rate is around $98/kW/month and has climbed roughly 17% over the past five years, which makes a locked-in low monthly rate worth something on its own.

There's also a macro argument for colocation over building your own server room. Uptime Institute's often-cited figure is that colocation runs 19–64% more cost-effectively than operating an in-house Tier 2-style facility, once you count power, cooling and physical security that you'd otherwise fund yourself.

## Who colocation is right for — and who should rent a server instead

Colocation only makes sense if you already own (or plan to buy) your hardware. It fits a few profiles well:

- **Self-hosters and homelab graduates** with one or two enterprise servers who've outgrown a garage in terms of power, uptime or a residential IP that keeps getting DDoS'd.
- **Game server hosts and community operators.** Sharktech's official testimonials include a game server provider, Dingdian Network, which reports its servers absorb 3–8 Gbit DDoS attacks regularly without interruption.
- **Businesses with US + EU footprints** — five locations under one contract, with failover between them.

If you don't have hardware, colocation is the wrong product. Sharktech rents dedicated servers too, and its promotional pricing page has listed an E3-1270v5 with 16GB RAM in Chicago or Los Angeles at $99/month, down from a listed $159 — worth comparing before buying a machine to rack. For a single low-traffic server, even that may be more than you need.

Honest caveat on reputation: Sharktech scores 3.4 out of 5 on Trustpilot, but from only 13 reviews — a sample too small to treat as a verdict. Recent reviews lean positive, praising stability (one user reports close to a year without downtime) and support responsiveness; the recurring complaint in older reviews is that billing cancellation, as noted above, requires manual PayPal work.

## Ordering: what actually happens, step by step

Sharktech's official deployment process has three stages:

1. **Choose a location** based on where your users and network needs are — this is also the biggest price lever, per the table above.
2. **Submit your equipment details**: rack units, power draw, port requirements and expected growth. The company is explicit that colocation has "physical details that a form cannot know," so sharing an accurate power draw matters more than picking a plan name.
3. **Coordinate shipping and installation** with Sharktech before the hardware leaves your hands.

There's also a promotional note for new deployments: independent write-ups of Sharktech's pricing mention 10% off the first six months on new colocation contracts, which would bring the Chicago 1–6U plan to roughly $31.50/month. It reportedly applies to qualifying new contracts without needing a coupon code — confirm the current terms with sales when you order. 👉 Start a Sharktech colocation order

## FAQ

**Is DDoS protection really included in a $35/month colocation plan?**
Yes — DDoS-protected networking is part of every Sharktech plan rather than a paid add-on, and independent plan summaries put the included mitigation at around 40 Gbps. The company's own background is in DDoS mitigation going back to 2003, and its game-server customers report surviving multi-gigabit attacks on it.

**What's the difference between the 1–6U and 10–42U tiers besides size?**
Power. The small tier covers 200–1200W total, which fits one to a few servers; a full rack gets 1600–5500W for denser deployments. Network capacity, transfer allowance and DDoS protection are identical between the tiers.

**Do I need to be near the data centre?**
No, but it helps for emergencies. Official选址 guidance for colocation generally suggests balancing disaster-risk geography (flood, earthquake) against travel convenience for the rare times you need to visit — Sharktech's 24/7 on-site staff cover routine hands-on work remotely.

## Before you place the order

Match the deployment to the actual need: one or two servers you want out of your office → Chicago 1–6U at $35/month, no reason to pay more unless latency to LA or Europe is a hard requirement; five-plus servers or a growing fleet → the $280 Chicago full rack leaves the most headroom per dollar; EU presence or West Coast latency → the $792 tiers. Whatever you pick, get the itemized quote first — power envelope, installation and remote-hands charges are the three line items that move a colocation bill after the fact. 👉 View Sharktech's colocation plans and current pricing
