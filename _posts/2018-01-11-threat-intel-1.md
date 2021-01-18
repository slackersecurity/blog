---
layout: post
title:  "Threat Intel - Part One: Gathering Data"
date:   2018-01-11 
categories: security
---

Threat Intel is the 'new' hottness in Infosec. Everyone has a threat intel program or is trying to start their threat intel program.
Threat Intelligence can enhance and augment your understanding about what's going on in your environment. However, true threat intelligence is more than just data feeds.
A good threat intelligence program not only has data, but as a firm understanding what the data means, how reliable it is and how it relates to your threat landscape.
Threat Intelligence should also include new attack vectors and new vulnerabilities that affect your environment.
This is going to be a three part series - I'm breaking it down into the following categories:
Gathering Data
Analyze & Normalize
Blocking / Alerting

The 'Gathering Data' phase is the easiest. There is a ton of data out there that is ready to be automated and integrated with your security stack.
Below is by no means an exaustive list, but it's a good starting point. Now, lets get to the data!
Gathering Data
Tools
Intelmq - Great framework for processing data feeds
MISP - Open Source platform to store and share IOCs

Open Threat Exchanges
Alien Vault Open Threat Exchange (OTX)
Facebook Threat Exchange
IBM X-force
Threat Connect

API Integrations
Virus Total - Number one place to see if a file is malicious
Threat Crowd - A search engine for threats
Threat Miner - Data Mining for Threat Intelligence

Feeds / Trackers
Ransomeware Tracker
OpenBL
NoThink
SANS DShield
CI Army
TALOS

Blogs
Malware don't need Coffee
Malware Traffic Analysis
Slacker Threat Intel Dashboard - My dashboard of blog feeds
Automating OSINT - Advanced OSINT collection

US Government Threat Sharing
US CERT
Infragard
DHS
List of ISACS

Threat Reports
APT Notes - White papers and Threat Reports on APT campaigns
APT Notes Feed - Automated feed for APT Notes

Most of these sources can be automated to be pulled into your SIEM or one of the platforms mentioned above.
With that said, some coding/scripting can go a long way to pull all the data together and some sources require manual analysis.
Keep fighting the good fight!
 - @midnightslacker
