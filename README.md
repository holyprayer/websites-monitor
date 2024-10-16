# Websites Monitor
## Project Description

This project aims to continuously monitor various aspects of specified websites. It runs a variety of checks, ranging from performance to security considerations. The GitHub Action is scheduled to run once per day, updating this README with the latest results.

![Static Badge](https://img.shields.io/badge/project_status-alpha-red?style=for-the-badge&logo=github)

## How to Use

1. Fork this repository.
2. Add the websites you want to monitor in the `websites.txt` file, one per line.
3. Enable GitHub Actions if not already enabled.
4. The README will be automatically updated with the latest check results once a day.


## Monitoring Checks
[![Create report](https://github.com/fabriziosalmi/websites-monitor/actions/workflows/create-report.yml/badge.svg)](https://github.com/fabriziosalmi/websites-monitor/actions/workflows/create-report.yml)
| Check Type | rumbascafe.com | njtaxplus.com | ariesinteriordoors.com | ariesblinds.net | arieskitchencabinets.com | qcconstructions.com | costaengineeringcorporation.com | hardwarestoreelizabeth.com | verikas.com | friendlycheckcashingnj.com | verikasphotography.com | seasquiddockside.com | foxfenceenterprisesinc.com | turbofishingboat.com | 3rdstreetlaundromat.net | cuomosons.com | ninjatennisacademy.com | friendlycheckcash.com | casacurazao.com | qcconstructions.verikas.com | ajipanel.ramsayrivero.com | ariesblinds.com | rperdomorefrigeration.com | svinsuranceagency.com | soscmd.com | qualityrehabconsulting.com | piamservices.com | dulceviewbakery.com | elmarautorepaircorp.com |
|------------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Domain breach | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| Domain Expiration | 🟢 (174 days left) | 🟢 (340 days left) | 🟢 (332 days left) | 🟢 (34 days left) | 🟢 (218 days left) | 🟢 (144 days left) | 🟢 (109 days left) | 🟢 (187 days left) | 🟢 (342 days left) | 🟢 (126 days left) | 🟢 (200 days left) | 🟢 (339 days left) | 🟢 (73 days left) | 🟢 (342 days left) | 🟢 (187 days left) | 🟢 (140 days left) | 🟢 (118 days left) | 🟢 (210 days left) | 🟢 (139 days left) | 🟢 (342 days left) | 🟢 (194 days left) | 🟢 (91 days left) | 🟢 (120 days left) | 🔴 (-67 days left) | 🟢 (542 days left) | 🟢 (111 days left) | 🔴 (-67 days left) | 🟢 (232 days left) | 🟢 (189 days left) | 
| SSL Expiration | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (39 days left) | 🟢 (74 days left) | 🟢 (36 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (63 days left) | 🟢 (68 days left) | 🟢 (63 days left) | 🟢 (36 days left) | 🟢 (81 days left) | 🟢 (63 days left) | 🟢 (241 days left) | 🟢 (63 days left) | 🟢 (43 days left) | 🟢 (56 days left) | 🟢 (36 days left) | 🟢 (360 days left) | 🔴 | 🟢 (33 days left) | 🟢 (36 days left) | 🔴 | 🟢 (58 days left) | 🔴 | 
| DNS Blacklists (Spamhaus + Spamcop) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| DNS Blacklist (DomainsBlacklists) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| HSTS | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| XSS Protection | 🟢 | ⚪ | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | ⚪ | 🔴 | ⚪ | 🔴 | ⚪ | 
| Redirect chains | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Pagespeed Performances | 79 | 0 | 74 | 32 | 72 | 64 | 98 | 95 | 74 | 82 | 99 | 0 | 82 | 100 | 48 | 78 | 94 | 72 | 0 | 0 | 100 | 35 | 98 | 0 | 100 | 0 | 0 | 83 | 50 | 
| Website Load Time | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟠 | ⚪ | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Rate limited | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| CDN | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Brotli | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Deprecated libs | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| Client rendering | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Mixed content | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Content-Type headers | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Internationalization | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| FLOC | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| AMP | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Robots.txt | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🟢 | ⚪ | 
| Sitemap | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | 
| Favicon | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Alt Tags | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟢 | 🔴 | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🔴 | 🔴 | 🔴 | 🔴 | 🟠 | ⚪ | ⚪ | 🔴 | 🔴 | ⚪ | 🟠 | ⚪ | 
| Open Graph Protocol | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Semantic Markup | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Ad and tracking | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Privacy-Protected Whois | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Privacy Exposure | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 

---
Last Updated: 2024-10-16 04:43:46
