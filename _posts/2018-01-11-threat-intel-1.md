---
layout: post
title:  "Threat Intel - Part One: Gathering Data"
date:   2018-01-11 
categories: security
---
Lets define threat intelligence as information about threats and threat actors that helps mitigate attacks against your enterprise network. 
Threat Intelligence can also enhance and augment your understanding about what's going on in your environment. True threat intelligence is more than just data feeds.
A good threat intelligence program not only has data, but as a firm understanding what the data means, how reliable it is and how it relates to your threat landscape.
Threat Intelligence should also include new attack vectors and new vulnerabilities that affect your environment.

This is going to be a three part series - I'm breaking it down into the following categories:
1. Gathering Data
2. Analyze & Normalize
3. Blocking / Alerting

The 'Gathering Data' phase is the easiest. There is a ton of data out there that is ready to be automated and integrated with your security stack.
Below is by no means an exaustive list, but it's a good starting point. Now, lets get to the data!

## Gathering Data
### Tools
- [Intelmq](https://github.com/certtools/intelmq) - Great framework for processing data feeds
- [MISP](http://www.misp-project.org/) - Open Source platform to store and share IOCs

### Open Threat Exchanges
- [Alien Vault Open Threat Exchange (OTX)](https://otx.alienvault.com/)
- [Facebook Threat Exchange](https://developers.facebook.com/products/threat-exchange)
- [IBM X-force](https://exchange.xforce.ibmcloud.com/)
- [Threat Connect](https://app.threatconnect.com/auth/index.xhtml)

### API Integrations
- [Virus Total](https://www.virustotal.com/en/documentation/public-api/) - Number one place to see if a file is malicious
- [Threat Crowd](https://threatcrowd.blogspot.co.uk/2016/02/crowdsourced-feeds-from-threatcrowd.html) - A search engine for threats
- [Threat Miner](https://www.threatminer.org/) - Data Mining for Threat Intelligence

### Feeds / Trackers
- [Abuse.ch](https://abuse.ch/)
- [NoThink](http://www.nothink.org/)
- [SANS DShield](https://isc.sans.edu/api/)
- [CI Army](http://cinsscore.com/list/ci-badguys.txt)
- [APT Notes](https://github.com/aptnotes/data)

### Blogs
- [Malware don't need Coffee](https://malware.dontneedcoffee.com/blog/)
- [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/index.html)
- [Slacker Threat Intel Dashboard - My dashboard of blog feeds](https://www.netvibes.com/midnightslacker#Threat_Intel)
- [Automating OSINT - Advanced OSINT collection](http://www.automatingosint.com/blog/)

### US Government Threat Sharing
- [US CERT](https://www.us-cert.gov/ncas)
- [Infragard](https://www.infragard.org/)
- [DHS](https://www.dhs.gov/ciscp)
- [List of ISACS](https://en.wikipedia.org/wiki/Information_Sharing_and_Analysis_Center)

Most of these sources can be automated to be pulled into your SIEM or one of the platforms mentioned above.
With that said, some coding/scripting can go a long way to pull all the data together and some sources require manual analysis.
Keep fighting the good fight!
 - @midnightslacker
