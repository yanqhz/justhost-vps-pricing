# VPS price: what $1.99, $7 and $23 a month actually buy, where the extra charges hide, and which JustHost plan fits (full plan table)

JustHost's cheapest fully specified VPS is **$1.99 a month** for 1 core, 512 MB of RAM, a 5 GB NVMe disk and a 10 Mbps fair-share port. One tier up, **$7.08** buys 2 cores, 2 GB of RAM and a 20 GB disk. For scale: Liquid Web's Cloud VPS table starts at $11 a month, OVHcloud's VPS-4 lists from $23.37, and Hostinger's KVM 1 bills $6.49 a month on a 24-month prepay and renews at $11.99.

The gap between $2 and $23 rarely comes down to core count. It comes from what's bundled, what the port speed is, and what the second invoice looks like. So the JustHost line comes first, then the arithmetic that turns a headline price into a yearly bill, then the clauses that make a cheap tier a bad fit for certain workloads.

> **Quick pick**
> - **A small site, a tunnel endpoint, a bot:** Sirius, 1 core / 1 GB / 20 GB NVMe at 300 Mbps, $4.85/month list or $3.88/month when you prepay 12 months.
> - **A few containers, n8n, a small database:** Double Star, 2 cores / 2 GB / 20 GB, $7.08/month list or $5.67/month on 12 months ($68.04 up front).
> - **A control panel, a game server, or anything that needs more than 4 GB of RAM:** Vega, 2 cores / 4 GB / 80 GB at 500 Mbps, $13.44/month list or $10.75/month on 12 months.
>
> 👉 [Compare every JustHost VPS tier and its 12-month rate](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## JustHost VPS price list

Every plan below is KVM virtualisation with root access, an IPv4 and an IPv6 address, and a port the page describes as unmetered but fair-share. Prices are the dollar figures printed on the plan list.

| Plan | vCPU / RAM / NVMe | Port (fair-share) | List price | Prepay 12 months | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 / 512 MB / 5 GB | 10 Mbps (≈4+ TB/mo) | $1.99/mo | not shown | [See the Promo plan](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 / 1 GB / 10 GB | 100 Mbps (≈31+ TB/mo) | $3.81/mo | $3.05/mo | [See New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 / 1 GB / 20 GB | 300 Mbps (≈93+ TB/mo) | $4.85/mo | $3.88/mo | [See Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 / 2 GB / 30 GB | 300 Mbps (≈93+ TB/mo) | $6.92/mo | $5.53/mo | [See Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 / 2 GB / 20 GB | 200 Mbps (≈62+ TB/mo) | $7.08/mo | $5.67/mo | [See Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 / 2 GB / 40 GB | 400 Mbps (≈124+ TB/mo) | $8.99/mo | $7.19/mo | [See Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 / 4 GB / 30 GB | 300 Mbps (≈93+ TB/mo) | $9.80/mo | $7.84/mo | [See Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 / 4 GB / 80 GB | 500 Mbps (≈155+ TB/mo) | $13.44/mo | $10.75/mo | [See Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 / 4 GB / 120 GB | 750 Mbps (≈232+ TB/mo) | $18.30/mo | $14.64/mo | [See Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

Three notes on how to read that table:

- The prepay column is the same plan at 20% off, quoted as an effective monthly rate. Paying it means handing over twelve months at once, so Vega on 12 months is $129.00 in one go rather than $10.75 a month on a card.
- New Star, Double Star and Bright Star carry a note that the plan is available when you order 3 months or more. The Promo plan's 12-month rate wasn't rendered on the page, so don't assume the 20% applies to it.
- The tariffs page continues above Capella with larger tiers, and the VPS landing page runs a separate **special-offer line** at lower prices for the same size classes: Sirius Special $2.81/mo (from $2.25 on 12 months), Arcturus Special $4.01 (from $3.21), Vega Special $7.79 (from $6.23), Yildun 4 cores / 8 GB / 200 GB at $16.20 (from $12.96), Betelgeuse 6 cores / 12 GB / 400 GB at $26.40 (from $21.12), Altair 8 cores / 24 GB / 600 GB at $47.40 (from $37.92). There's also a constructor that sells the same size classes on HDD, SSD or NVMe, with IPv4+IPv6 starting at $2.60/mo on 12 months and IPv6-only starting at $1.60/mo.

That last point matters more than it looks. Yildun gives 8 GB of RAM for $16.20 while Capella charges $18.30 for 4 GB, because they sit on two different listings. Check the special-offer set before you buy from the standard tariff table.

The two JustHost pages also advertise different entry points: the VPS landing page headlines $1.16, the tariffs page headlines $1.99. The cheapest plan with a published spec is VPS Promo at $1.99.

## What the monthly price includes, and what it leaves out

Included on every plan: KVM virtualisation, root access, a dedicated IPv4 and IPv6 address, protection against the main DDoS attack types, and an unmetered port. The port is fair-share, which means the Mbps figure is a share of a shared uplink rather than a guaranteed slice. On the Promo plan that share is 10 Mbps, and the page equates it to roughly 4 TB a month at full tilt.

Not stated on the plan pages: a backup service, a refund window, the list of installable operating systems, or data centre locations. Those four items are the ones to ask support about before paying, because none of them can be inferred from the spec sheet, and a backup policy you assumed is the most expensive kind of missing feature.

## First-term price, renewal price, and the two-year total

Hostinger's KVM 1 shows why the biggest number on a pricing page is a weak comparison. The page lists $19.49 struck through, $6.49 a month, and "today you pay $155.76 for 24 months", with renewal at $11.99 a month for the same term. Over a second 24-month term at the renewal rate that's $287.76, or $132 more than the first term. The $6.49 and the $11.99 describe the same server two years apart.

JustHost prices its discount as a prepay term instead: each plan shows a list rate and a rate "when you pay for 12 months" that is exactly 20% lower. So the decision on the page is monthly billing versus a 12-month prepay, not a teaser versus a renewal. Vega at $13.44 billed monthly is $161.28 over a year; the 12-month prepay is $129.00. That's $32.28 saved for paying up front, and it's the whole of the difference.

What the pages don't say is what happens after those 12 months. Renewal terms for justhost.asia plans aren't published in the plan list, so treat the list rate as the number you'd pay if you don't prepay, and confirm the post-term rate with support before committing a year.

Other providers put the extra money in places that don't appear in a "from $X" line:

- **Contabo** advertises Cloud VPS from €4.40 a month, and the footnote is the important part: that figure is the effective monthly rate on a **24-month subscription, including applicable taxes**, in euros. A shorter term costs more, and a one-off setup fee applies to new Cloud VPS 4 instances on monthly contracts.
- **IONOS** sells VPS S+ at $2/month against a $6 list price, and charges **$5 per month for each additional IPv4 address**. Domains start at $1 a year and are not included.
- **OVHcloud** lists VPS-4 from $23.37 a month with 8 vCores, 24 GB RAM and 200 GB NVMe, and the VPS does not include a domain or mailboxes.

Add a $5 monthly IP and a $1 domain to a $2 plan and the "cheapest" option has quietly become a $8 plan.

👉 [Check Vega's current list price and 12-month rate side by side](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392)

## The clauses in cheap tiers that change the deal

Low prices come with conditions, and the conditions are usually written in a footnote rather than a headline.

**A 10 Mbps port is a real ceiling.** JustHost's Promo plan equates its port to about 4 TB a month, which is generous for a text site and tight for anything serving images or video to a crowd. If your page weight is 2 MB and you get 50,000 visits, you're already near the limit.

**Unmetered is not dedicated.** JustHost, Contabo and most budget providers describe traffic as unlimited or unmetered and then apply a fair-share or fair-usage rule. Contabo states it plainly: outgoing traffic is unlimited subject to fair usage, and servers with exceptionally high or disruptive patterns can be throttled. Contabo's port speeds also range from 200 Mbit/s to 1 Gbit/s depending on the tier, so the top spec isn't universal across the range.

**Backups can be an add-on.** Contabo's Auto Backup is a paid extra rather than part of the base price. Nothing in JustHost's plan list mentions a backup service either, so plan on taking your own snapshots until support tells you otherwise.

**Downgrades cost more than upgrades.** OVHcloud lets you move up a tier in one click from the control panel, but only within the same data centre. Moving down means ordering the smaller plan, migrating the data yourself and cancelling the old service. If you overshoot on RAM, correcting it is a project rather than a click.

**Some cheap tiers exclude the software you need.** OVHcloud's Local Zone VPS runs Linux only, with no Windows, Plesk, cPanel or Docker support, and no Additional IPs or Load Balancer. If your plan involves a control panel, that tier isn't a cheaper version of the same thing.

👉 [See exactly what the $1.99 VPS Promo includes before you commit](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)

## Pick by bottleneck, not by core count

Liquid Web's price table is a clean demonstration. At $56 a month you can have a Memory-optimised 4 vCPU / 12 GB / 240 GB machine, or a CPU-optimised 6 vCPU / 8 GB / 180 GB machine. Same money, different shape. Picking the one with more cores is only right if CPU is what's limiting you.

Applied to JustHost's line:

- **Static site, a WireGuard endpoint, a monitoring box:** 512 MB is enough for nginx serving flat files. The Promo plan at $1.99 works, and the 10 Mbps port is the constraint, not the CPU.
- **WordPress with a control panel:** 2 GB of RAM is the practical floor. Arcturus (1 core / 2 GB / 30 GB, $6.92) or Double Star (2 cores / 2 GB / 20 GB, $7.08) both clear it; take Double Star if PHP workers are the bottleneck.
- **cPanel or Plesk:** budget 4 GB and up. Bright Star (4 cores / 4 GB / 30 GB, $9.80) is the cheapest plan in the list that fits.
- **n8n, self-hosted apps, small databases:** RAM and disk first, cores second. Vega (2 cores / 4 GB / 80 GB, $13.44) has three times the disk of Bright Star for $3.64 more, which matters if you're storing run history and attachments.
- **A Minecraft server for a handful of players:** 2 to 4 GB of RAM and decent single-core speed. Bright Star's 4 cores at $9.80 handle a small world; the 30 GB disk is the limit once you add plugins and backups.
- **A local model through Ollama:** an 8B model at 4-bit quantisation wants most of 8 GB before the OS takes its share. That's Yildun on the special-offer list (4 cores / 8 GB / 200 GB, $16.20 list), not anything in the standard table below $18.
- **A production database or API:** memory and NVMe matter more than cores, and you need a backup plan of your own. Vega or Capella, plus off-server backups.

## Which JustHost you're reading about

Search for reviews and most of what comes back describes **JustHost.com**, a US shared-hosting brand sold alongside Bluehost: shared plans around $3.95 to $6.95 a month on three-year terms, VPS plans at $19.99 to $59.99 a month, a 30-day money-back guarantee, and complaints from users who describe being passed between support queues.

None of that applies to justhost.asia. The plan names don't overlap (Sirius, Vega, Capella, Yildun), the price list doesn't overlap, and the products are built differently. Two consequences: don't carry the $19.99 VPS figure or the 30-day guarantee across, and don't let a review of the .com brand talk you out of a $2 plan you were about to test. Equally, the absence of independent reviews for justhost.asia means you're buying on the spec sheet and the terms, so read them.

## Who should not buy the cheapest plan

- **A static brochure site.** Shared hosting at a few dollars a month comes with a panel, mail and support. A $1.99 VPS gives you a root prompt and a 10 Mbps port, and you become the administrator.
- **Anyone who won't touch a command line.** Every plan in this table is self-managed. A managed VPS costs more, and that premium buys the thing you actually need.
- **Windows or licensed software.** JustHost's plan list doesn't state which operating systems you can install. If Windows Server is a requirement, confirm it before ordering rather than after.
- **A busy storefront.** 512 MB and 10 Mbps is not a commerce configuration. Vega or Capella is the entry point, and even then you own the uptime.
- **Anyone who needs a guaranteed bandwidth slice.** Fair-share ports are shared by design. If sustained throughput is contractual, this isn't the product category.

Decision rules to finish with: a single small site or a private endpoint → Sirius at $3.88/month on 12 months. Two to four containers with a real database → Double Star at $5.67 or Vega at $10.75. A panel, a game server, or a model that needs 8 GB → Bright Star, or Yildun from the special-offer list.

Before you pay, confirm three things: the term you're committing to (the 20% lives in the 12-month prepay), whether your RAM floor and port speed match the workload, and who takes the backups. Then check the special-offer line against the standard table, because the same money regularly buys one tier more.

👉 [Open the Double Star plan page and check the term options before ordering](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392)
