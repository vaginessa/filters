## About

This Repo is scheduled to automatically update (and it's lists) at least every 24 hours.

Lists are to be used with an adblocker solution which supports the appropriate format. This may be such as but not limited to the formats of, adblock (AdGuard), hosts, domains.

Info about formats using [Pi-Hole](https://pi-hole.net/blog/2023/03/22/pi-hole-ftl-v5-22-web-v5-19-and-core-v5-16-1-released#page-content) and [AdGuard](https://adguard.com/kb/general/ad-filtering/create-own-filters/)


### Repo Status

[![Workflow](https://github.com/SystemJargon/filters/actions/workflows/main.yml/badge.svg)](https://github.com/SystemJargon/filters/actions/workflows/main.yml) 
[![HitCount](https://hits.dwyl.com/systemjargon/filters.svg?style=flat&show=unique)](http://hits.dwyl.com/systemjargon/filters) 
[![GitHub stars](https://img.shields.io/github/stars/systemjargon/filters)](https://github.com/systemjargon/filters/stargazers) [![GitHub forks](https://img.shields.io/github/forks/systemjargon/filters)](https://github.com/systemjargon/filters/network/members) [![Issues](https://img.shields.io/github/issues/systemjargon/filters)](https://github.com/SystemJargon/filters/issues) 
[![last commit](https://img.shields.io/github/last-commit/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master) [![commit activity](https://img.shields.io/github/commit-activity/y/SystemJargon/filters.svg)](https://github.com/SystemJargon/filters/commits/master) ![GitHub repo size](https://img.shields.io/github/repo-size/systemjargon/filters)

----


Use the RAW files [linked](#the-lists) below this [README](https://github.com/SystemJargon/filters/blob/main/README.md) file in your AdGuard/Adblock solution. 

Notes:

* Some lists are defined as a blocklist or some an allowlist. Each list has a description or purpose for what it does, i.e allow, block telemetry.

* All lists (so the lines within) will have syntax validated and be de-duplicated. Some may have comments stripped. This is mostly to ensure file sizes (plus download/update times) are managable and future scalable. I may create releases to make this point mentioned, easier.

* You can check my aggregation of sources used in this repo [here](https://github.com/SystemJargon/filters/tree/main/source). Each txt list has a corresponding named JSON file.

* The aggregation of some lists are from my [blocklists](https://github.com/systemjargon/blocklists) or [allowlists](https://github.com/systemjargon/allowlists) repositories. 

* If you want my big Social Media Blocklist, see [here](https://github.com/SystemJargon/blocklists/blob/main/lists/categories/social-media/SystemJargon_Block_SocialMedia_AG.txt) or look in my blocklists repo under the Category of Social Media [here](https://github.com/SystemJargon/blocklists/blob/main/lists/categories/social-media)

* Feel free to 🌟/star the repo.

* Raise any issues or requests [here](https://github.com/SystemJargon/filters/issues/new/choose) 

----

## The Lists

| List Type | File | Raw Link | Description |
|--------|------|----------|-------------|
| ✅ | [Allowlist](allowlist.txt) | [Raw Link](https://raw.githubusercontent.com/SystemJargon/filters/main/allowlist.txt) | Allow list for common services and sites |
| 🚫 | [Core list](core.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/core.txt) | Blocklist core aggregated lists of StevenBlackHosts, Adguard DNS Filter, OISD, Firebog ticklists |
| 🚫 | [Porn list](porn.txt) | [Raw Link](https://raw.githubusercontent.com//systemjargon/filters/main/porn.txt) | Blocklist well beyond 1 million entries across several lists for porn |
| 🚫 | [Security list](security.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/security.txt) | Blocklist aggregated from other well-curated lists which do not appear in phishing.txt nor firebog-ticklist.txt as of the time of commit |
| 🚫 | [Phishing list](phishing.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/phishing.txt) | Blocklist aggregated from other well-curated lists exclusively for phishing |
| 🚫 | [Threats list](threats.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/threats.txt) | Blocklist aggregated from my own multiple blocklists, anti-phishing/scam/coinminer/malware/bad reputation categories |
| 🚫 | [Telemetry list](telemetry.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/telemetry.txt) | Big custom blocklist for Telemetry via SmartTV, Amazon, Windows, Android, iOS, and additional Firebog telemetry lists |
| 🚫 | [Advertising list](ads.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/ads.txt) | Blocklist which is some of my own and aggregated popular adlists across Github and other places |
| 🚫 | [FireBog Ticklist](firebog-ticklist.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/firebog-ticklist.txt) | The blocklists which feature on the [Firebog ticklist here](https://v.firebog.net/hosts/lists.php?type=tick) |
| 🚫 | [Restrict-ByPass list](restrict-bypass.txt) | [Raw Link](https://raw.githubusercontent.com/systemjargon/filters/main/restrict-bypass.txt) | My own curated list with supplement lists aggregated. The Blocklist is to prevent using other DNS or bypass methods like Tor, proxy, Apple Relay, etc. |

----


