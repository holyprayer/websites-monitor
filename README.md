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
| Domain Expiration | 🟢 (64 days left) | 🟢 (230 days left) | 🟢 (222 days left) | 🟢 (654 days left) | 🟢 (108 days left) | 🟢 (34 days left) | 🔴 (-1 days left) | 🟢 (77 days left) | 🟢 (232 days left) | 🟠 (16 days left) | 🟢 (90 days left) | 🟢 (229 days left) | 🟢 (328 days left) | ⚪ | 🟢 (77 days left) | 🟢 (30 days left) | 🔴 (8 days left) | 🟢 (100 days left) | 🟠 (29 days left) | 🟢 (232 days left) | 🟢 (84 days left) | 🟢 (346 days left) | 🔴 (10 days left) | ⚪ | 🟢 (432 days left) | 🔴 (1 days left) | ⚪ | 🟢 (122 days left) | 🟢 (79 days left) | 
| SSL Expiration | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (51 days left) | 🟠 (7 days left) | 🟢 (48 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (75 days left) | 🟢 (80 days left) | 🔴 | 🟢 (48 days left) | 🟢 (32 days left) | 🟢 (75 days left) | 🟢 (131 days left) | 🟢 (75 days left) | 🟢 (55 days left) | 🟢 (68 days left) | 🟢 (48 days left) | 🟢 (250 days left) | 🔴 | 🟢 (45 days left) | 🟢 (48 days left) | 🔴 | 🟢 (66 days left) | 🔴 | 
| DNS Blacklists (Spamhaus + Spamcop) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| DNS Blacklist (DomainsBlacklists) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| HSTS | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| XSS Protection | 🟢 | ⚪ | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | ⚪ | 🔴 | ⚪ | 🔴 | ⚪ | 
| Redirect chains | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Pagespeed Performances | 83 | 0 | 86 | 34 | 72 | 66 | 51 | 95 | 78 | 82 | 100 | 0 | 82 | 0 | 53 | 90 | 93 | 57 | 0 | 0 | 100 | 41 | 99 | 0 | 100 | 0 | 0 | 83 | 55 | 
| Website Load Time | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Rate limited | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| CDN | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Brotli | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Deprecated libs | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| Client rendering | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Mixed content | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Content-Type headers | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Internationalization | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| FLOC | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| AMP | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Robots.txt | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🟢 | ⚪ | 
| Sitemap | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | 
| Favicon | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Alt Tags | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟢 | 🔴 | 🟠 | ⚪ | 🟠 | 🟠 | 🟠 | 🔴 | 🔴 | 🔴 | 🔴 | 🟠 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🟠 | ⚪ | 
| Open Graph Protocol | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Semantic Markup | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Ad and tracking | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Privacy-Protected Whois | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 
| Privacy Exposure | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 

---
Last Updated: 2025-02-03 04:40:09
