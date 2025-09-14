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
| Domain Expiration | 🟢 (206 days left) | 🔴 (7 days left) | 🔴 (-1 days left) | 🟢 (431 days left) | 🟢 (250 days left) | 🟢 (176 days left) | ⚪ | 🟢 (219 days left) | 🔴 (9 days left) | 🟢 (158 days left) | 🟢 (232 days left) | 🔴 (6 days left) | 🟢 (105 days left) | ⚪ | 🟢 (219 days left) | 🟢 (172 days left) | 🟢 (150 days left) | ⚪ | 🟢 (171 days left) | 🔴 (9 days left) | 🟢 (226 days left) | 🟢 (123 days left) | 🟢 (152 days left) | 🟢 (264 days left) | 🟢 (209 days left) | ⚪ | ⚪ | ⚪ | 🟢 (221 days left) | 
| SSL Expiration | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (72 days left) | 🔴 | 🟢 (69 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (35 days left) | 🟢 (40 days left) | 🔴 | 🟢 (69 days left) | 🟢 (53 days left) | 🟢 (35 days left) | 🔴 | 🟢 (35 days left) | 🟢 (76 days left) | 🟠 (28 days left) | 🟢 (86 days left) | 🟠 (27 days left) | 🟢 (49 days left) | 🟢 (66 days left) | 🔴 | 🔴 | 🔴 | 🔴 | 
| DNS Blacklists (Spamhaus + Spamcop) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| DNS Blacklist (DomainsBlacklists) | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| HSTS | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| XSS Protection | 🟢 | ⚪ | 🟢 | 🔴 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| Redirect chains | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Pagespeed Performances | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 
| Website Load Time | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | ⚪ | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟠 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Rate limited | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| CDN | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Brotli | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Deprecated libs | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| Client rendering | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Mixed content | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Content-Type headers | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Internationalization | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| FLOC | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| AMP | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Robots.txt | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Sitemap | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Favicon | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Alt Tags | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟠 | ⚪ | 🟠 | 🟠 | 🟠 | 🟢 | 🔴 | 🟠 | ⚪ | 🟠 | 🟠 | 🟠 | ⚪ | 🔴 | 🔴 | 🔴 | 🟠 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Open Graph Protocol | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Semantic Markup | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Ad and tracking | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Privacy-Protected Whois | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | 🔴 | 
| Privacy Exposure | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 

---
Last Updated: 2025-09-14 04:33:17
