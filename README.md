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
| Domain Expiration | 🟢 (256 days left) | 🟢 (57 days left) | 🟢 (49 days left) | 🟢 (481 days left) | 🟢 (300 days left) | 🟢 (226 days left) | ⚪ | 🟢 (269 days left) | 🟢 (59 days left) | 🟢 (208 days left) | 🟢 (282 days left) | 🟢 (56 days left) | 🟢 (155 days left) | ⚪ | 🟢 (269 days left) | 🟢 (222 days left) | 🟢 (200 days left) | 🔴 (-73 days left) | 🟢 (221 days left) | 🟢 (59 days left) | 🟢 (276 days left) | 🟢 (173 days left) | 🟢 (202 days left) | 🟢 (314 days left) | 🟢 (259 days left) | ⚪ | ⚪ | 🔴 (-51 days left) | 🟢 (271 days left) | 
| SSL Expiration | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (61 days left) | 🔴 | 🟢 (58 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟢 (85 days left) | 🟠 (29 days left) | 🔴 | 🟢 (58 days left) | 🟢 (42 days left) | 🟢 (85 days left) | 🔴 | 🟢 (85 days left) | 🟢 (65 days left) | 🟢 (78 days left) | 🟢 (75 days left) | 🟢 (77 days left) | 🟢 (40 days left) | 🟢 (55 days left) | 🔴 | 🔴 | 🔴 | 🔴 | 
| DNS Blacklists (Spamhaus + Spamcop) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| DNS Blacklist (DomainsBlacklists) | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 
| HSTS | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | 
| XSS Protection | 🟢 | ⚪ | 🟢 | 🔴 | 🟢 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | 🔴 | 🔴 | 🟢 | ⚪ | 🔴 | 🟢 | 🟢 | ⚪ | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | 
| Redirect chains | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
| Pagespeed Performances | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 
| Website Load Time | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | 🟢 | ⚪ | 🟢 | 🟠 | 🟢 | ⚪ | 🟢 | 🟢 | 🟢 | 🟠 | 🟢 | 🟢 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 
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
| Privacy-Protected Whois | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | ⚪ | 🔴 | 🔴 | 
| Privacy Exposure | 🔴 | 🟢 | 🔴 | 🔴 | 🔴 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | 🟢 | 🟢 | 🔴 | ⚪ | 🔴 | 🔴 | 🔴 | ⚪ | 🟢 | 🟢 | 🟢 | 🔴 | 🟢 | 🔴 | 🟢 | ⚪ | ⚪ | ⚪ | ⚪ | 

---
Last Updated: 2025-07-26 04:47:15
