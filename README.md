# dedicated IP VPS: How to choose a fixed public IPv4 without paying for the wrong VPS

A **dedicated IP VPS** is easy to misunderstand because “dedicated IP” and “VPS” describe two different things.

A VPS is the server environment: virtual CPU, RAM, storage, operating system, and usually administrative access. A dedicated IP is the network identity attached to that environment. You can have a VPS with a dedicated public IP, but the dedicated IP itself does not give you more CPU, RAM, storage, or guaranteed performance. It also does not turn a VPS into a physical dedicated server.

That distinction matters when you are shopping for one. Someone who needs a stable address for SSH, an API allowlist, a VPN endpoint, remote access, or a service that must always point to the same public IPv4 may need a dedicated IP but very little compute. Someone running a database, game server, proxy workload, automation stack, or several applications may need substantially more VPS resources.

LisaHost is relevant to this search because its current catalog contains a large number of VPS and VDS families with **one public IPv4 listed on the plan**, including US, Hong Kong, Singapore, Taiwan, Japan, UK, Korea, Germany, and residential-IP offerings. Its affiliate URL also resolves to LisaHost's main site.

The important part is choosing the right network and billing model rather than simply buying the biggest VPS on the page.

## What a dedicated IP VPS actually gives you

Think of the two components separately.

The **VPS** supplies the computing environment. LisaHost's current plans vary from small 1-core/512MB or 1GB configurations to 8-core/8GB offerings, with NVMe storage, bandwidth limits, traffic allowances, and different network locations.

The **dedicated public IPv4** gives that server a fixed Internet-facing address. That can be useful when another system needs to recognize your server by IP rather than by a changing address.

Typical reasons include:

* SSH or remote administration from a known endpoint
* IP allowlisting for APIs, databases, dashboards, and corporate systems
* A VPN server with a fixed public address
* Applications that need stable DNS records
* Certain mail-server setups where a consistent address is part of the configuration
* Hosting a service that other systems must reach directly

A dedicated IP is not, by itself, a speed upgrade or a security product. Liquid Web makes the same distinction: the IP is an addressing feature, while the VPS supplies the isolated server resources.

It is also worth separating **dedicated IP** from **dedicated server**. A dedicated server means the physical machine is assigned to you. A dedicated IP VPS still runs as a virtual machine on shared physical infrastructure.

## When the dedicated IP matters more than extra VPS power

For many users searching specifically for a dedicated IP VPS, the biggest mistake is overbuying compute.

Suppose the main requirement is a fixed public IPv4 for an allowlist. Moving from 1 CPU and 1GB of RAM to 4 CPU and 4GB of RAM does not make the IP itself more “dedicated.” The extra resources only help if the application needs them.

That is why LisaHost's small plans are worth examining before the expensive tiers. For example, its current US 9929 residential-IP lineup starts at ¥68/month for 1 CPU, 1GB RAM, 10GB NVMe, 50Mbps, 1,000GB traffic, and one IPv4. The same family goes up through 4 CPU/4GB and 8,000GB traffic, plus unlimited-traffic variants.

For a lightweight fixed-endpoint workload, the smaller tier may be enough. For sustained traffic, multiple services, or heavier applications, the additional resources start to matter.

There is another question that often matters more than CPU: **what kind of IP are you actually buying?**

LisaHost separates ordinary VPS, native-IP products, dual-ISP residential/home-broadband products, and residential VDS products into different families. Those labels indicate different network positioning and should not be treated as interchangeable.

## The network label matters

LisaHost's catalog is organized around network families rather than one universal “dedicated IP VPS” product.

You will see terms such as:

* US 9929
* US 4837
* CERA CN2
* New York and Chicago
* Hong Kong CMI/CU2/CN2
* Singapore native IP
* Taiwan native IP
* Japan native IP
* UK dual-ISP residential
* Korea dual-ISP residential
* Germany residential VDS
* US residential VDS

These are not simply different CPU tiers. They represent different locations, routing arrangements, or IP classifications.

For example, LisaHost's US 9929 page describes a KVM VPS using a US native residential IP and explicitly lists one IPv4 on each displayed plan. Its US 4837 family likewise lists one IPv4 per plan but uses a different network family and traffic/bandwidth configuration.

If your application depends on where the IP is located, then the city or network family can be more important than an extra 1GB of RAM.

The same applies to routes. Some LisaHost product pages explicitly say that the network is not optimized for mainland-China access and discuss using transit through Hong Kong or Japan. That does not mean the network is unsuitable; it means the geographic route is part of the product's characteristics and should be matched to the workload.

## Full current VPS/VDS pricing snapshot

LisaHost's live cart is a multi-family catalog rather than a single four-tier pricing table. The following table consolidates the plan variants and current prices that were explicitly visible on the live product pages reviewed in September 2026. Prices are shown in **CNY/RMB (¥)**, and some products are marked as special or limited offers on the live site.

| Product family / plan | CPU / RAM | Storage | Network / traffic | Current price | Billing | Purchase |
| --- | --- | --- | --- | ---: | --- | --- |
| US 9929 Residential IP — 精简版 | 1C / 1GB | 10GB NVMe | 50Mbps / 1TB / 1 IPv4 | ¥68 | Monthly | [ Buy this LisaHost plan](https://lisahost.com/cart.php?aff=1572&pid=65) |
| US 9929 Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 60Mbps / 2TB / 1 IPv4 | ¥88 | Monthly | [ Buy the US 9929 base plan](https://lisahost.com/cart.php?aff=1572&pid=58) |
| US 9929 Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 80Mbps / 4TB / 1 IPv4 | ¥158 | Monthly | [ Buy the US 9929 advanced plan](https://lisahost.com/cart.php?aff=1572&pid=59) |
| US 9929 Residential IP — 豪华版 | 4C / 4GB | 80GB NVMe | 100Mbps / 8TB / 1 IPv4 | ¥899 | Monthly | [ Buy the US 9929 deluxe plan](https://lisahost.com/cart.php?aff=1572&pid=60) |
| US 9929 Residential IP — 无限流量 Lite | 2C / 2GB | 40GB NVMe | 20Mbps / unlimited / 1 IPv4 | ¥498 | Monthly | [ View the US 9929 Lite unlimited plan](https://lisahost.com/cart.php?aff=1572&pid=62) |
| US 9929 Residential IP — 无限流量 Pro | 4C / 4GB | 80GB NVMe | 50Mbps / unlimited / 1 IPv4 | ¥1,288 | Monthly | [ View the US 9929 Pro unlimited plan](https://lisahost.com/cart.php?aff=1572&pid=63) |
| US 9929 — 特价年付版 | 1C / 1GB | 10GB NVMe | 50Mbps / 600GB / 1 IPv4 | ¥499 | Annual | [ View the US 9929 annual offer](https://lisahost.com/cart.php?aff=1572&pid=168) |
| US 4837 Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 300Mbps / 3TB / 1 IPv4 | ¥68 | Monthly | [ Buy the US 4837 base plan](https://lisahost.com/cart.php?aff=1572&pid=48) |
| US 4837 Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 500Mbps / 8TB / 1 IPv4 | ¥100 | Monthly | [ Buy the US 4837 advanced plan](https://lisahost.com/cart.php?aff=1572&pid=47) |
| US 4837 Residential IP — 豪华版 | 4C / 4GB | 80GB NVMe | 1Gbps / 20TB / 1 IPv4 | ¥699 | Monthly | [ Buy the US 4837 deluxe plan](https://lisahost.com/cart.php?aff=1572&pid=49) |
| US 4837 Residential IP — 无限流量 Lite | 2C / 2GB | 20GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥398 | Monthly | [ View the US 4837 Lite unlimited plan](https://lisahost.com/cart.php?aff=1572&pid=50) |
| US 4837 Residential IP — 无限流量 Pro | 8C / 8GB | 80GB NVMe | 500Mbps / unlimited / 1 IPv4 | ¥998 | Monthly | [ View the US 4837 Pro unlimited plan](https://lisahost.com/cart.php?aff=1572&pid=51) |
| US 4837 — 特价年付版 | 1C / 1GB | 10GB NVMe | 100Mbps / 600GB / 1 IPv4 | ¥399 | Annual | [ View the US 4837 annual offer](https://lisahost.com/cart.php?aff=1572&pid=169) |
| US CERA CN2 — 试用 | 1C / 1GB | 10GB SSD | 10Mbps / 1GB / 1 IPv4 | ¥2 | 1 day | [ Try the CERA CN2 VPS](https://lisahost.com/cart.php?aff=1572&pid=33) |
| US CERA CN2 — 精简版 | 1C / 512MB | 10GB SSD | 10Mbps / 100GB / 1 IPv4 | ¥40 | Monthly | [ Buy the CERA CN2 entry plan](https://lisahost.com/cart.php?aff=1572&pid=36) |
| US CERA CN2 — 基础版 | 1C / 1GB | 20GB SSD | 15Mbps / 500GB / 1 IPv4 | ¥50 | Monthly | [ Buy the CERA CN2 base plan](https://lisahost.com/cart.php?aff=1572&pid=32) |
| US CERA CN2 — 进阶版 | 2C / 2GB | 20GB SSD | See live configuration | ¥256 | Quarterly | [ View the CERA CN2 advanced plan](https://lisahost.com/cart.php?aff=1572&pid=34) |
| New York Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 300Mbps / 3TB / 1 IPv4 | ¥68 | Monthly | [ Buy the New York base plan](https://lisahost.com/cart.php?aff=1572&pid=149) |
| New York Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 500Mbps / 8TB / 1 IPv4 | ¥100 | Monthly | [ View New York VPS plans](https://bit.ly/LIsahost) |
| New York Residential IP — 豪华版 | 4C / 4GB | 80GB NVMe | 1Gbps / 20TB / 1 IPv4 | ¥300 | Monthly | [ View the New York deluxe option](https://bit.ly/LIsahost) |
| New York Residential IP — 无限流量 Lite | 2C / 2GB | 40GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥198 | Monthly | [ View New York unlimited Lite](https://bit.ly/LIsahost) |
| New York Residential IP — 无限流量 Pro | 8C / 8GB | 120GB NVMe | 500Mbps / unlimited / 1 IPv4 | ¥498 | Monthly | [ View New York unlimited Pro](https://bit.ly/LIsahost) |
| New York Residential IP — 特价年付版 | 1C / 1GB | 10GB NVMe | 100Mbps / 600GB / 1 IPv4 | ¥399 | Annual | [ View the New York annual offer](https://bit.ly/LIsahost) |
| Chicago Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 300Mbps / 3TB / 1 IPv4 | ¥68 | Monthly | [ Buy the Chicago base plan](https://lisahost.com/cart.php?aff=1572&pid=156) |
| Chicago Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 500Mbps / 8TB / 1 IPv4 | ¥100 | Monthly | [ View Chicago advanced](https://bit.ly/LIsahost) |
| Chicago Residential IP — 豪华版 | 4C / 4GB | 80GB NVMe | 1Gbps / 20TB / 1 IPv4 | ¥300 | Monthly | [ View Chicago deluxe](https://bit.ly/LIsahost) |
| Chicago Residential IP — 无限流量 Lite | 2C / 2GB | 40GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥198 | Monthly | [ View Chicago unlimited Lite](https://bit.ly/LIsahost) |
| Chicago Residential IP — 无限流量 Pro | 8C / 8GB | 120GB NVMe | 500Mbps / unlimited / 1 IPv4 | ¥498 | Monthly | [ View Chicago unlimited Pro](https://bit.ly/LIsahost) |
| Chicago Residential IP — 特价年付版 | 1C / 1GB | 10GB NVMe | 100Mbps / 600GB / 1 IPv4 | ¥399 | Annual | [ View the Chicago annual offer](https://bit.ly/LIsahost) |
| Hong Kong CMI/CU2/CN2 — 基础版 | 1C / 1GB | 20GB NVMe | 30Mbps / 1TB / 1 IPv4 | ¥88 | Monthly | [ Buy the Hong Kong optimized base plan](https://lisahost.com/cart.php?aff=1572&pid=90) |
| Hong Kong CMI/CU2/CN2 — 进阶版 | 2C / 2GB | 40GB NVMe | 50Mbps / 2TB / 1 IPv4 | ¥188 | Monthly | [ View the Hong Kong advanced plan](https://bit.ly/LIsahost) |
| Hong Kong CMI/CU2/CN2 — 无限流量 Lite | 2C / 2GB | 40GB NVMe | 30Mbps / unlimited / 1 IPv4 | ¥998 | Monthly | [ View the Hong Kong unlimited Lite](https://bit.ly/LIsahost) |
| Hong Kong CMI/CU2/CN2 — 无限流量 Pro | 4C / 4GB | 80GB NVMe | 50Mbps / unlimited / 1 IPv4 | ¥1,988 | Monthly | [ View the Hong Kong unlimited Pro](https://bit.ly/LIsahost) |
| Hong Kong iCable Residential IP — 精简版 | 1C / 1GB | 10GB NVMe | 100Mbps / 2TB / 1 IPv4 | ¥88 | Monthly | [ Buy the iCable entry plan](https://lisahost.com/cart.php?aff=1572&pid=182) |
| Hong Kong iCable Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 150Mbps / 4TB / 1 IPv4 | ¥129 | Monthly | [ View iCable base](https://bit.ly/LIsahost) |
| Hong Kong iCable Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 200Mbps / 6TB / 1 IPv4 | ¥299 | Monthly | [ View iCable advanced](https://bit.ly/LIsahost) |
| Hong Kong iCable Residential IP — 豪华版 | 4C / 4GB | 80GB NVMe | 300Mbps / 10TB / 1 IPv4 | ¥599 | Monthly | [ View iCable deluxe](https://bit.ly/LIsahost) |
| Hong Kong HGC Residential IP — 精简版 | 1C / 1GB | 10GB NVMe | 50Mbps / 1TB / 1 IPv4 | ¥99 | Monthly | [ Buy the HGC entry plan](https://lisahost.com/cart.php?aff=1572&pid=124) |
| Hong Kong HGC Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 60Mbps / 3TB / 1 IPv4 | ¥129 | Monthly | [ View HGC base](https://bit.ly/LIsahost) |
| Hong Kong HGC Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 100Mbps / 5TB / 1 IPv4 | ¥299 | Monthly | [ View HGC advanced](https://bit.ly/LIsahost) |
| Singapore Native IP — 基础版 | 1C / 1GB | 10GB NVMe | 300Mbps / 6TB / 1 IPv4 | ¥68 | Monthly | [ Buy the Singapore base plan](https://lisahost.com/cart.php?aff=1572&pid=70) |
| Singapore Native IP — 进阶版 | 2C / 2GB | 20GB NVMe | 500Mbps / 10TB / 1 IPv4 | ¥88 | Monthly | [ Buy the Singapore advanced plan](https://lisahost.com/cart.php?aff=1572&pid=71) |
| Singapore Native IP — 豪华版 | 4C / 4GB | 40GB NVMe | 1Gbps / 20TB / 1 IPv4 | ¥388 | Monthly | [ Buy the Singapore deluxe plan](https://lisahost.com/cart.php?aff=1572&pid=72) |
| Singapore Native IP — 无限流量 Lite | 2C / 2GB | 40GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥398 | Monthly | [ View Singapore unlimited Lite](https://lisahost.com/cart.php?aff=1572&pid=73) |
| Taiwan Hinet Residential VDS — 200Mbps | 1C / 1GB | 20GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥399 | Monthly | [ View the Taiwan Hinet 200Mbps VDS](https://lisahost.com/cart.php?aff=1572&pid=111) |
| Taiwan Hinet Residential VDS — 300Mbps | 2C / 2GB | 40GB NVMe | 300Mbps / unlimited / 1 IPv4 | ¥599 | Monthly | [ View the Taiwan Hinet 300Mbps VDS](https://bit.ly/LIsahost) |
| Taiwan Native IP VPS — 进阶版 | 2C / 2GB | 20GB NVMe | 200Mbps / 5TB / 1 IPv4 | ¥99 | Monthly | [ Buy the Taiwan native-IP VPS](https://bit.ly/LIsahost) |
| Taiwan Native IP VPS — 豪华版 | 4C / 4GB | 40GB NVMe | 500Mbps / 20TB / 1 IPv4 | ¥388 | Monthly | [ View the Taiwan native-IP deluxe plan](https://bit.ly/LIsahost) |
| Taiwan Native IP VDS — 100Mbps unlimited | 1C / 1GB | 20GB NVMe | 100Mbps / unlimited / 1 IPv4 | ¥299 | Monthly | [ View Taiwan unlimited VDS](https://bit.ly/LIsahost) |
| Japan Native IP VPS — 基础版 | 1C / 1GB | 10GB NVMe | 300Mbps / 3TB / 1 IPv4 | ¥88 | Monthly | [ View the Japan native-IP VPS](https://bit.ly/LIsahost) |
| Japan Native IP VPS — 进阶版 | 2C / 2GB | 20GB NVMe | 500Mbps / 8TB / 1 IPv4 | ¥158 | Monthly | [ View the Japan advanced plan](https://bit.ly/LIsahost) |
| UK Dual-ISP Residential IP — 基础版 | 1C / 1GB | 10GB NVMe | 300Mbps / 6TB / 1 IPv4 | ¥68 | Monthly | [ View the UK residential VPS](https://bit.ly/LIsahost) |
| UK Dual-ISP Residential IP — 进阶版 | 2C / 2GB | 20GB NVMe | 500Mbps / 8TB / 1 IPv4 | ¥100 | Monthly | [ View the UK advanced plan](https://bit.ly/LIsahost) |
| UK Dual-ISP Residential IP — 豪华版 | 4C / 4GB | 40GB NVMe | 1Gbps / 20TB / 1 IPv4 | ¥300 | Monthly | [ View the UK deluxe plan](https://bit.ly/LIsahost) |
| Korea Dual-ISP Residential IP — 基础版 | 1C / 1GB | 20GB NVMe | 100Mbps / 3TB / 1 IPv4 | ¥99 | Monthly | [ View the Korea base plan](https://bit.ly/LIsahost) |
| Korea Dual-ISP Residential IP — 进阶版 | 2C / 2GB | 40GB NVMe | 150Mbps / 5TB / 1 IPv4 | ¥188 | Monthly | [ View the Korea advanced plan](https://bit.ly/LIsahost) |
| Germany Dual-ISP Residential VDS — 100Mbps | 1C / 1GB | 20GB NVMe | 100Mbps / 3TB / 1 IPv4 | ¥169 | Monthly | [ View the Germany residential VDS](https://bit.ly/LIsahost) |
| Germany Dual-ISP Residential VDS — 200Mbps | 2C / 2GB | 40GB NVMe | 200Mbps / 8TB / 1 IPv4 | ¥399 | Monthly | [ View the Germany 200Mbps VDS](https://bit.ly/LIsahost) |
| US Seattle Residential VDS — 基础版 | 1C / 1GB | 20GB NVMe | 100Mbps / 3TB / 1 IPv4 | ¥169 | Monthly | [ View the Seattle residential VDS](https://bit.ly/LIsahost) |
| US Seattle Residential VDS — 进阶版 | 2C / 2GB | 40GB NVMe | 200Mbps / 6TB / 1 IPv4 | ¥299 | Monthly | [ View Seattle advanced VDS](https://bit.ly/LIsahost) |
| US Seattle Residential VDS — 200Mbps unlimited | 4C / 4GB | 80GB NVMe | 200Mbps / unlimited / 1 IPv4 | ¥599 | Monthly | [ View Seattle unlimited VDS](https://bit.ly/LIsahost) |
| US Los Angeles Astound Residential VDS — 基础版 | 1C / 1GB | 20GB NVMe | 100Mbps / 3TB / 1 IPv4 | ¥169 | Monthly | [ View the Los Angeles residential VDS](https://bit.ly/LIsahost) |

The live cart also exposes additional product families, including other Japan ISP/residential VDS, Vietnam residential-IP VPS, a Germany dual-stack/dual-native-IP 9929-optimized family, and additional annual-sale products. Those catalogs use separate product pages and billing presentations, so they should be checked on the live cart rather than silently treating an unverified configuration as identical to one of the plans above.

## Which LisaHost family fits which dedicated-IP use case?

### For a normal fixed US IPv4

The US 9929 and US 4837 families are the most straightforward place to start when you specifically want a US IP attached to a VPS.

The configurations make the trade-off quite obvious.

US 9929 starts at **¥68/month** and offers 1,000GB traffic on the smallest tier. US 4837 also starts at **¥68/month**, but the base plan lists 300Mbps bandwidth and 3,000GB traffic. The more expensive tiers scale CPU, RAM, storage, bandwidth, and traffic together.

That makes the choice less about “which one has a dedicated IP?” and more about the network family and the workload.

[👉 Compare LisaHost's current US VPS choices](https://bit.ly/LIsahost)

### For a fixed IP with DDoS-focused infrastructure

The CERA CN2 family is different. LisaHost's current page lists a default **50G DDoS protection** configuration and says upgrades to 100G are available. The smallest standard plans are much cheaper than the larger network products, while the trial is a ¥2 one-day product and is explicitly shown as a trial rather than a normal refundable VPS subscription.

That can make more sense when the application requirement includes attack mitigation rather than simply “I need one fixed IPv4.”

The important caveat is the network limit itself. The 512MB entry plan is only 10Mbps and 100GB traffic, so buying it because it has the right IP type does not make it a substitute for a higher-resource server.

### For home-broadband or residential-IP requirements

LisaHost has several product families it labels as residential, home broadband, native residential, or dual-ISP residential.

This is where the distinction between **a dedicated IP** and **the characteristics of the IP** becomes especially important.

A fixed data-center IPv4 and a fixed residential/home-broadband-labelled IPv4 can both be dedicated IPs, but the second category is being sold for a different network identity. LisaHost explicitly uses different product pages and names for those offerings.

Third-party testing adds a useful qualification. A June 2026 test of a LisaHost US 4837 VPS reported a 1-core/1GB configuration, roughly 19GB of usable disk, an IPv4 address associated with Cogent, and testing across multiple locations. Another 2026 test of the US 9929 product reported a native-IP configuration matching the published entry-level pricing and resources. These are individual test nodes, however, and do not prove that every IP allocated under a product family will have identical routing or reputation.

There is also contrary discussion worth knowing about: a 2026 forum thread questioned whether some products marketed with residential terminology should automatically be treated as equivalent to conventional household broadband lines, noting that IP classification databases and ASN information can tell a different story.

So, if the exact IP classification matters to your application, test the **actual assigned IP**, not just the product title.

## Dedicated IP does not mean “clean IP”

This is one of the most important points for anyone buying a dedicated IP VPS.

A dedicated address is unique to your server, but it is not automatically guaranteed to have a perfect reputation. Previous use, blocklists, mail reputation, abuse history, and the behavior of the service using it can all matter.

That is particularly relevant for email. A dedicated IP may be useful for a mail-server setup, but the dedicated-IP purchase itself does not guarantee inbox placement. Liquid Web explicitly separates the concept of a dedicated address from its reputation and security characteristics.

The same logic applies to security. A dedicated IP does not remove the need for firewalls, updates, access controls, monitoring, and application-level security.

Before deploying a production service, check the actual IP through the relevant reputation and blocklist tools rather than assuming the product label settles the question.

## Check IPv4, IPv6, rDNS, and ports before you buy

A dedicated IP VPS can still be the wrong purchase when one small networking requirement has not been checked.

### Public IPv4

Confirm that the plan actually includes a public IPv4. Most of the LisaHost plans above explicitly show **1 IPv4** in the current configuration.

That is more useful than vague wording such as “dedicated network,” which does not necessarily tell you how many addresses are assigned.

### IPv6

IPv6 support can be useful, but it is not a universal substitute for IPv4. Some LisaHost pages advertise IPv6 allocations separately; for example, the Singapore product page lists five free IPv6 addresses.

That is a bonus only if your application and users actually support IPv6.

### Reverse DNS

If you need mail, a network service, or anything that depends on DNS consistency, check whether reverse DNS/PTR can be configured and under what conditions.

This is one of those boring details that becomes very important after the server is already deployed.

### Port restrictions

Some applications need specific inbound or outbound ports. Mail is a classic example because outbound TCP/25 policies vary between providers.

Do not assume that having a dedicated IPv4 means every port is open.

### IP persistence

Ask what happens to the IP if you reinstall the OS, migrate the VPS, change plans, or encounter a hardware issue.

A fixed address is useful only if you understand how the provider handles it during lifecycle events.

## What LisaHost's refund rules actually mean

The refund policy is not identical across every product type.

LisaHost's general site prominently advertises a **48-hour unconditional refund** for many ordinary products.

But several special-product pages use different terms. The residential VDS pages for products such as the US Seattle residential VDS, Taiwan residential VDS, Germany residential VDS, and Japan residential VDS are shown as special products whose refunds are handled as website balance rather than the same cash-refund treatment used on ordinary VPS plans. The CERA trial is also a separate product with its own trial terms.

So “48-hour refund” should not be read as a universal rule across the entire catalog.

When buying a dedicated IP VPS, read the refund line on the **specific product page**, especially for residential VDS or special promotional products.

## There is a current 2026 coupon, but verify the checkout total

A current 2026 deal listing reports the coupon code **`TS-CBP205DQJE`** and describes it as a recurring 10% discount. The same source reports additional cycle discounts, including 10% off quarterly billing, 20% off annual billing, and 30% off two-year billing, with the coupon listed through **December 31, 2026**.

Because this information comes from a current deal publisher rather than LisaHost's public pricing table itself, the sensible way to use it is simple: enter the code during checkout and **confirm that the discount is actually reflected in the final order total before paying**.

That matters because LisaHost also displays products that are already marked as special prices, so the effective discount can depend on the specific product and billing cycle.

[👉 Check the live LisaHost pricing and coupon eligibility](https://bit.ly/LIsahost)

## Monthly versus annual pricing

Some of LisaHost's most aggressive entry prices are annual offers rather than ordinary month-to-month rates.

The clearest examples in the current catalog are the US 4837 annual plan at **¥399/year** and the US 9929 annual plan at **¥499/year**. Their advertised monthly-equivalent prices are roughly ¥33 and ¥41 respectively, but those figures are only meaningful when you are comfortable paying for the full annual term upfront.

That changes the comparison substantially.

A ¥68 monthly plan costs ¥816 over 12 months before any other discount. An annual ¥399 plan is a completely different commitment and configuration, with only 1 CPU, 1GB RAM, 10GB storage, and a 600GB traffic allowance on the US 4837 annual product.

So do not compare “¥33/month” with “¥68/month” as though they were identical subscriptions. They are not.

The same warning applies to annual-sale products throughout the catalog.

## How much VPS resource do you actually need?

For a dedicated IP VPS, start with the application rather than the network label.

A small server can make sense for:

* a VPN endpoint
* SSH administration
* a lightweight reverse proxy
* a simple webhook receiver
* a small personal API
* DNS-related tools
* one lightweight web application

You may need more CPU and RAM for:

* several Docker containers
* databases with meaningful workloads
* build servers
* browser automation at scale
* media processing
* multiple simultaneous services
* high-concurrency applications

Traffic and bandwidth are separate from compute.

LisaHost's US 4837 plans illustrate this nicely: its base plan has 1 CPU and 1GB RAM but lists **300Mbps and 3,000GB traffic**, while the 4-core deluxe plan reaches 1Gbps and 20,000GB.

That means a customer can become network-limited, CPU-limited, RAM-limited, or traffic-limited for completely different reasons.

Buying a larger VPS to solve the wrong limit is just an expensive way to keep the original problem.

## Residential VDS has stricter acceptable-use considerations

The US residential VDS page is unusually explicit about prohibited activities.

LisaHost states that its residential VDS products must not be used for spam, bulk email, scanning, phishing, abuse, or similar activities, and says service may be suspended without refund after a complaint.

That matters because a residential-IP product can look attractive for automation or email-related projects, but the provider's acceptable-use policy still controls what you can actually do with it.

The presence of a dedicated IP is never a license to run whatever traffic you want.

## A simple buying checklist

Before paying for a dedicated IP VPS, check these items against the exact plan:

1. **IPv4:** Is one public dedicated IPv4 explicitly included?
2. **Location:** Is the city/country suitable for the service you are hosting?
3. **Network:** Is it standard data-center, native IP, dual-ISP residential, home broadband, or VDS?
4. **Resources:** CPU, RAM, storage, bandwidth, and monthly traffic.
5. **Operating system:** Is your required OS available?
6. **IPv6:** Is it included, optional, or unavailable?
7. **rDNS/PTR:** Can you configure reverse DNS if needed?
8. **Ports:** Are the ports required by your workload allowed?
9. **IP reputation:** Can you inspect the actual assigned IP before putting it into production?
10. **Refund:** Does the exact product have the normal 48-hour refund, a trial rule, or a website-balance-only policy?
11. **Billing:** Is the attractive price monthly, quarterly, annual, or a limited promotion?
12. **Renewal:** What does the product cost on the next billing cycle?

That last point is easy to miss when a product is displayed as a special price.

## Dedicated IP VPS FAQ

### Is a dedicated IP the same thing as a VPS?

No. A dedicated IP is a network address assigned to your service. A VPS is the virtual server environment running your operating system and applications. A VPS can use a dedicated IP, and having a dedicated IP does not mean you have a physical dedicated server.

### Does a dedicated IP improve VPS speed?

Not by itself. Speed depends on the server's CPU, RAM, storage, network capacity, routing, congestion, and the application workload. The IP being dedicated does not automatically add performance resources.

### Does a dedicated IP improve SEO?

A dedicated IP should not be treated as a general SEO performance upgrade. Its main value is network identity and address stability. The VPS still needs normal security, performance, uptime, and application configuration.

### Is one IPv4 enough?

For many single-server applications, yes. Whether it is enough depends on the application architecture. If you need separate services, multiple endpoints, special allowlists, or several IP identities, check the provider's additional-IP policy rather than assuming more addresses are included.

### Can I run a VPN on a dedicated IP VPS?

Technically, a VPS with a public dedicated IPv4 can be used as a VPN endpoint, subject to the provider's terms, ports, and network restrictions. The practical advantage is having a stable endpoint rather than a changing address.

### Are LisaHost residential IP VPS products the same as ordinary VPS products?

No. LisaHost separates them into different product families and uses different network descriptions. Third-party testing also shows that IP classification can vary by actual address, so “residential” should be treated as a product/network characteristic to verify, not as a guarantee about every allocated IP.

### Which LisaHost plan should I start with?

Start with the smallest plan that satisfies the application's actual CPU, RAM, storage, bandwidth, traffic, and location requirements. For a lightweight fixed-IP workload, the entry-level 1-core/1GB plans are worth checking before moving to a much larger tier. If the network type is the main requirement, choose the appropriate family first and then size the VPS within that family.

### Is the LisaHost coupon still worth trying?

The code `TS-CBP205DQJE` is currently reported by 2026 deal pages as a 10% recurring discount through December 31, 2026. Treat that as a current offer to test at checkout, and use the checkout total as the final authority on whether the discount applies to your exact product and billing cycle.

## The practical takeaway

A **dedicated IP VPS** is really a combination of two buying decisions: how much server you need, and what kind of public IP/network you need.

For a lightweight fixed endpoint, paying for an 8-core server just because the IP is important usually addresses the wrong constraint. For a location-sensitive application, the opposite mistake is more common: choosing a cheap VPS with the wrong network or IP classification and discovering later that the server resources were never the problem.

LisaHost's current catalog gives you a wide range of choices, from ordinary US VPS tiers around **¥68/month** to residential VDS products at **¥169/month and up**, plus higher-resource and unlimited-traffic options. Its current site also advertises a general 48-hour refund policy for many products, while special VDS and trial products can carry different refund terms.

The most sensible comparison is therefore not “which dedicated IP VPS is biggest?” It is:

**Which IP type, location, traffic allowance, and server resources match the application I actually need to run?**

[👉 View LisaHost's current VPS and dedicated-IP options](https://bit.ly/LIsahost)
