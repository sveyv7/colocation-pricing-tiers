# data center colocation: How It Works, What It Costs, and Where the Good Deals Are (With Real Per-Month Pricing)

If you've been typing "data center colocation" into a search box, you probably own a server (or ten) and have realized your office closet, garage, or current host isn't cutting it anymore. Maybe the power bill is creeping up, the AC can't keep up in summer, or you want your hardware somewhere with actual redundant network paths instead of a single Comcast line. This guide covers what colocation actually is, what drives the price, how it stacks up against cloud and dedicated servers, and — because pricing is where most guides get vague — real monthly numbers from a provider that publishes them openly: Sharktech, which runs colocation facilities in five cities across the US and Europe.

## What Data Center Colocation Actually Means

Colocation (usually shortened to "colo") is a simple arrangement: you buy and own the server hardware, and a data center company rents you the space, power, cooling, bandwidth, and physical security to run it. Your machine sits in a rack next to other companies' machines. You get a cage, a rack, or as little as a single rack unit (1U — about 1.75 inches of vertical rack space).

The division of labor is the key thing to understand:

- **You handle**: the hardware itself, the OS, your data, applications, and remote management
- **The provider handles**: power feeds, UPS and backup generators, cooling, physical security, network uplinks, and (with some providers) DDoS protection and remote hands support

Why do companies bother? Building your own facility means generators, redundant cooling, multiple carrier contracts, and a badge-access room — that's a capital project measured in hundreds of thousands of dollars minimum. Colocation splits that cost across dozens of tenants. You also get connectivity you can't buy at your office: enterprise data centers sit on multi-hundred-gigabit backbones with connections to Tier 1 and Tier 3 providers, which is why a small game hosting company or a SaaS startup with steady traffic often ends up better off colocating one or two beefy servers than paying month-to-month cloud rates.

The people who typically search for this fall into a few camps: growing hosting providers who've outgrown rented dedicated servers, businesses with compliance or hardware-ownership requirements, and technical folks who've done the math and realized a $4,000 server colocated for $99/month beats renting equivalent hardware for $400/month after about a year.

## What Actually Drives Colocation Pricing

This is where generic guides love to waffle. Let's be specific. Your monthly colo bill is built from four inputs:

**Space.** Measured in rack units (U) for small setups, quarter/half/full racks for medium ones, and private cages for large ones. A 1U server takes less space and costs less to house than a 4U box, even if the specs are identical.

**Power.** Usually the biggest driver after space, and quoted in watts or amps. A 200W server costs far less to colocate than a 1,200W GPU monster, because the provider bills you (directly or indirectly) for both the electricity and the cooling capacity needed to deal with the heat. High-density racks cost real money to support.

**Bandwidth.** Providers quote port speed (10Gbps, 100Gbps) plus included transfer (300TB is a common starting allowance). If you're pushing video or serving files at scale, overage terms matter more than the base price.

**Location.** Same server, same power draw, very different price depending on the city. Premium interconnection hubs like Los Angeles near One Wilshire — one of the world's busiest telecom buildings — cost more than a mid-continent facility in Denver or a cost-effective market like Las Vegas. Real estate, power rates, and network density all vary.

Industry-wide, US colocation runs anywhere from roughly $150 to over $1,000 per month per rack unit depending on those four factors — which is why publishing a fixed price list, as some providers do, is genuinely useful for buyers.

> **The honest framing:** colocation's economics favor people with steady, predictable workloads and a willingness to buy hardware up front. If your compute demand spikes wildly week to week, cloud's elastic billing probably still makes sense. If you'd rather never touch hardware, a dedicated server lease (where the provider owns the box) is the middle ground.

## Colocation vs. Cloud vs. Dedicated Servers

Quick comparison so you know which lane you're actually in:

|  | Colocation | Dedicated Server (rented) | Public Cloud |
| --- | --- | --- | --- |
| Hardware ownership | You own it | Provider owns it | No discrete hardware |
| Up-front cost | High (you buy the server) | None | None |
| Monthly cost | Lowest for steady workloads | Medium | Highest at sustained scale |
| Control | Full — your box, your rules | Full software control, limited hardware say | Constrained by platform |
| Scaling hardware | Buy and ship/install more | Upgrade or migrate plans | Instant, within limits |
| Best for | Long-term, predictable, hardware-specific needs | Mid-term needs, no capex | Variable or short-term workloads |

A concrete example of the math: if you need a machine with 128GB RAM and fast NVMe storage, renting that as a dedicated server might run $250–400/month. Buying it costs maybe $6,000–8,000. Colocate it for under $100/month and the owned hardware breaks even in roughly two years, then keeps costing $99 while the rental price follows the provider's price list, not yours. The trade-off is that if the power supply dies at 3 AM, it's *your* power supply — though a good provider's 24/7 on-site engineers can do remote hands work like swapping a drive or power cable if you ship the part.

## Sharktech's Colocation Pricing: The Actual Numbers

Most colocation providers make you fill out a "request a quote" form and then a salesperson calls you. That's fine for enterprise deals but annoying when you just want to know if 2U in Las Vegas costs $80 or $800. Sharktech — a hosting company headquartered in Las Vegas with over a decade in the colocation and DDoS protection business — publishes its pricing directly, which makes it a useful reference point for the whole market.

Their colocation lineup is structured as two size tiers at each of their five data centers:

**Partial rack (1–6U):**
- Network: 10Gbps to 100Gbps, starting at 300TB of transfer
- Power: 200–1200W
- Price: **starting at $65/month** (Las Vegas, Denver, Chicago) or **$99/month** (Los Angeles, Amsterdam)

**Full rack (10–42U):**
- Network: 10Gbps to 100Gbps, starting at 300TB of transfer
- Power: 1600–5500W
- Price: **starting at $520/month** (Las Vegas, Denver, Chicago) or **$792/month** (Los Angeles, Amsterdam)

Here's the full picture:

| Data Center | Space | Power | Network | Transfer | Starting Price | Purchase Link |
| --- | --- | --- | --- | --- | --- | --- |
| **Las Vegas** | 1–6U | 200–1200W | 10–100Gbps | 300TB+ | $65/month | [Get Las Vegas colocation](https://bit.ly/SharKTech) |
| **Las Vegas** | 10–42U | 1600–5500W | 10–100Gbps | 300TB+ | $520/month | [Get a Las Vegas rack](https://bit.ly/SharKTech) |
| **Denver** | 1–6U | 200–1200W | 10–100Gbps | 300TB+ | $65/month | [Get Denver colocation](https://bit.ly/SharKTech) |
| **Denver** | 10–42U | 1600–5500W | 10–100Gbps | 300TB+ | $520/month | [Get a Denver rack](https://bit.ly/SharKTech) |
| **Chicago** | 1–6U | 200–1200W | 10–100Gbps | 300TB+ | $65/month | [Get Chicago colocation](https://bit.ly/SharKTech) |
| **Chicago** | 10–42U | 1600–5500W | 10–100Gbps | 300TB+ | $520/month | [Get a Chicago rack](https://bit.ly/SharKTech) |
| **Los Angeles** | 1–6U | 200–1200W | 10–100Gbps | 300TB+ | $99/month | [Get Los Angeles colocation](https://bit.ly/SharKTech) |
| **Los Angeles** | 10–42U | 1600–5500W | 10–100Gbps | 300TB+ | $792/month | [Get an LA rack](https://bit.ly/SharKTech) |
| **Amsterdam** | 1–6U | 200–1200W | 10–100Gbps | 300TB+ | $99/month | [Get Amsterdam colocation](https://bit.ly/SharKTech) |
| **Amsterdam** | 10–42U | 1600–5500W | 10–100Gbps | 300TB+ | $792/month | [Get an Amsterdam rack](https://bit.ly/SharKTech) |

All pricing is monthly. If your needs don't fit these tiers — bigger cages, unusual power density, specific cross-connects — they'll build a custom quote, which is standard practice in this industry; the listed tiers just establish the floor.

A few things worth noting in these numbers:

- **$65/month for 1–6U is genuinely low** for the US market, especially in a facility like Las Vegas (hosted at the Flexential data center) or Denver (on the H5 Data Center Campus, an enterprise-grade facility). Most quotes you'll get from other providers for comparable power allowances will land higher.
- **The $99 Los Angeles rate reflects the location premium** — their LA facility sits near One Wilshire, the major telecom interchange point for US–Asia traffic. If your audience or peering relationships are Asia-facing, that extra $34/month is doing real work.
- **Amsterdam at $99 gives you a European presence** without European pricing headaches — useful for EU latency or GDPR-adjacent data residency strategies.
- **DDoS protection is included** across their locations, which matters a lot for anyone running game servers or anything attack-prone. One long-term Sharktech customer, a China-based game hosting company, has stated their game servers under 3–8Gbps DDoS attacks "never skip a beat" at Sharktech facilities.
- **300TB of transfer on the base tier** is generous; many budget colo quotes include far less before overages kick in.

## How to Pick a Data Center Location

Since the same $65–$99 decision point applies across Sharktech's five sites, here's the quick logic for choosing:

- **Los Angeles** — best for US–Asia traffic routes, content delivery to the Pacific, and companies needing One Wilshire interconnection. Added in 2012; the facility advertises a strong uptime record.
- **Las Vegas** — the cost-effective pick. Low natural disaster risk (no hurricanes, no major earthquake zone, minimal flooding), and it's Sharktech's home base.
- **Denver** — mid-continent, which means balanced latency to both US coasts. Denver also has strong fiber infrastructure and geo-stability, making it a favorite for disaster-recovery footprints.
- **Chicago** — central US network hub, good for reaching East Coast and Midwest users evenly.
- **Amsterdam** — the European gateway. Excellent international connectivity and a stable climate for natural cooling; the standard choice for EU coverage.

A general rule from the industry: colocation buyers should check for sufficient power backup (generators, not just UPS), verify carrier diversity on the network side, and think about physical access distance — if you'll need to swap hardware yourself, a 4-hour drive beats a flight. All five of these sites are staffed 24/7 with on-site engineers, which reduces how often you'd need physical access at all.

## How to Get Started With Colocation

The process is roughly the same industry-wide, and Sharktech's version follows the standard playbook:

1. **Pick your size and location.** Count your rack units, add up your power draw (check your server's PSU rating and be honest about it — power is what bites people on quotes), and choose a city based on where your users are.
2. **Order or request a consultation.** Sharktech offers a free consultation if you want help speccing, or you can order directly through their portal for the standard tiers. If you want to see current availability or talk through a custom cage, 👉 [start with their colocation page here](https://bit.ly/SharKTech).
3. **Ship or deliver your hardware.** You can colocate your own purchased servers, or — a somewhat unusual but convenient option at Sharktech — colocate servers you've purchased from them, so you don't have to buy hardware elsewhere first.
4. **They rack it and power it.** Their on-site engineers handle installation, and their network team gets you connected with your bandwidth allocation.
5. **Manage remotely.** From there it's your box on their infrastructure — remote reboots, IPMI/BMC access, and 24/7 support if something physical needs attention.

One decision worth flagging: colocation contracts usually run on monthly or longer terms, and providers often discount annual commitments. If you're confident about the workload's lifespan, asking about term pricing is a reasonable move during the consultation.

## What to Watch Out For

Colocation has a few recurring gotchas, none of which are deal-breakers if you know about them beforehand:

- **Power math surprises.** If your server draws more than your allocation, you'll pay overage or get throttled. Budget power based on realistic load, not nameplate.
- **Bandwidth overage terms.** Check what happens after 300TB — per-TB overage pricing varies wildly between providers.
- **Remote hands limits.** Most providers include basic remote hands (reboots, cable checks) but bill for complex work. Ask what's included.
- **Hardware lifecycle is yours.** When your colocated server ages out of usefulness, you're the one buying the replacement. The flip side: you can sell the old box, which you can never do with a rented dedicated server.
- **Contract lock-in.** Moving out of a colo facility means physically retrieving hardware, which is more friction than cancelling a cloud account. Test the waters with a month-to-month arrangement if you're unsure.

## Is Colocation Right for You?

The short version: colocation makes sense when your workloads are steady, your hardware needs are specific, and your time horizon is measured in years. At $65–99/month for 1–6U with 300TB of transfer and DDoS protection included, the entry cost is low enough that a single high-spec server often pays for the colo fee in dedicated-server-rental savings within the first month of the comparison. If your traffic pattern looks like a sawtooth and you need 50 servers on Monday and 3 on Friday, stay in the cloud — colo's predictability advantage works against you when capacity sits idle.

If you want to run real numbers for your own setup, 👉 [check Sharktech's colocation plans and current availability here](https://bit.ly/SharKTech) — the pricing is published, so you can sanity-check your budget before ever talking to a salesperson.
