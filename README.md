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
| Domain Expiration | 🟢 (139 days left) | 🟢 (305 days left) | 🟢 (297 days left) | 🔴 (-1 days left) | 🟢 (183 days left) | 🟢 (109 days left) | 🟢 (74 days left) | 🟢 (152 days left) | 🟢 (307 days left) | 🟢 (91 days left) | 🟢 (165 days left) | 🟢 (304 days left) | 🟢 (38 days left) | 🔴 (-58 days left) | 🟢 (152 days left) | 🟢 (105 days left) | 🟢 (83 days left) | 🟢 (175 days left) | 🟢 (104 days left) | 🟢 (307 days left) | 🟢 (159 days left) | 🟢 (56 days left) | 🟢 (85 days left) | ⚪ | 🟢 (507 days left) | 🟢 (76 days left) | ⚪ | 🟢 (197 days left) | 🟢 (154 days left) | 
| SSL Expiration | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (65 days left) | 🟢 (39 days left) | 🟢 (62 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (89 days left) | 🟢 (33 days left) | 🔴 | 🟢 (62 days left) | 🟢 (46 days left) | 🟢 (89 days left) | 🟢 (205 days left) | 🟢 (89 days left) | 🟢 (69 days left) | 🟢 (82 days left) | 🟢 (62 days left) | 🟢 (325 days left) | 🔴 | 🟢 (59 days left) | 🟢 (62 days left) | 🔴 | 🟢 (82 days left) | 🔴 | 
| DNS Blacklists (Spamhaus + Spamcop) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| DNS Blacklist (DomainsBlacklists) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| HSTS | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| XSS Protection | 🟢 | ⚪ | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | ⚪ | 🔴 | ⚪ | 🔴 | ⚪ | 
| Redirect chains | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Pagespeed Performances | 79 | 0 | 72 | 43 | 71 | 72 | 98 | 95 | 78 | 77 | 100 | 0 | 81 | 0 | 47 | 90 | 92 | 77 | 0 | 0 | 100 | 34 | 99 | 0 | 100 | 0 | 0 | 79 | 40 | 
| Website Load Time | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Rate limited | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| CDN | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Brotli | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Deprecated libs | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| Client rendering | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Mixed content | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Content-Type headers | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Internationalization | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| FLOC | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | ⚪ | 
| AMP | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Robots.txt | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🟢 | ⚪ | 
| Sitemap | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | 🔴 | 🟢 | 🔴 | 
| Favicon | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | ⚪ | 🔴 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Alt Tags | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟠 | 🔴 | 🟠 | 🟠 | 🟠 | 🟢 | 🔴 | 🟠 | ⚪ | 🟠 | 🟠 | 🟠 | 🔴 | 🔴 | 🔴 | 🔴 | 🟠 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🟠 | ⚪ | 
| Open Graph Protocol | 🟢 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 
| Semantic Markup | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 
| Ad and tracking | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🟢 | ⚪ | 
| Privacy-Protected Whois | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 
| Privacy Exposure | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | ⚪ | 🟢 | 🟢 | ⚪ | 🔴 | ⚪ | 

---
Last Updated: 2024-11-20 04:44:48
