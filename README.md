# Project Description
A collection of CTI resources. It's a work in progress, expect regular updates!

## Table of Contents 
- [1. Blog posts & Articles](#1-blog-posts--articles)
- [2. Tools & Collections](#2-tools--collections)
- [3. Standards & Frameworks](#3-standards-and-frameworks)
  -   [3.1 Mitre Standards](#31-mitre-standards---cti-management) - CTI management
  -   [3.2 Threat Modeling](#32-Threat-Modeling) - STRIDE/PASTA/DREAD
- [4. Definitions](#4-definitions)  
- [5. Help Me Understand with ChatGPT :)](https://github.com/slashparity/CTI-Resources/tree/main/Help%20me%20understand%20with%20ChatGPT#description)


  
## 1. Blog posts, Articles & Guides
- Getting started in cyber threat intelligence: [4 pieces of advice](https://redcanary.com/blog/getting-started-in-cyber-threat-intelligence/)  
- A Top 10 [Reading List](https://medium.com/katies-five-cents/a-top-10-reading-list-if-youre-getting-started-in-cyber-threat-intelligence-c11a18fc9798) if You’re Getting Started in Cyber Threat Intelligence 
- CTI [Reading List](https://sroberts.medium.com/cti-reading-list-a93ccdd7469c)
- ISAC [list](https://learningsomecti.medium.com/list-of-information-sharing-and-analysis-center-united-states-f4d5743f85d2) US
- [JA3](https://securitytrails.com/blog/ja3-fingerprinting) Fingerprtinting
- How Does [Analysis of Competing Hypotheses](https://pherson.org/wp-content/uploads/2013/06/06.-How-Does-ACH-Improve-Analysis_FINAL.pdf) Improve Intelligence Analysis?



## 2. Tools & Collections
- [Awesome Threat Intel](https://github.com/hslatman/awesome-threat-intelligence) collection repository
- [Yara](https://github.com/virustotal/yara) - Identify and classify malware samples.
    - [YaraCI](https://yara-ci.cloud.virustotal.com/) - Automated scanning of yara rule
- [allien vault OTX](https://otx.alienvault.com/) - Open Threat Exchange is the neighborhood watch of the global intelligence community.  
- [urlscan](https://urlscan.io/)
- [Cuckoo Sandbox](https://github.com/cuckoosandbox) - Open source dynamic malware analysis system
- [VirusTotal](https://www.virustotal.com/gui/home/search) - Online service that analyzes suspicious files and URLs to detect types of malware and malicious content using antivirus engines and website scanners.  
- [PhisTool](https://www.phishtool.com/) - Seeks to elevate the perception of phishing as a severe form of attack and provide a responsive means of email security.
- [OpenCTI](https://github.com/OpenCTI-Platform/opencti) - Threat Intelligence Platform (open source)
- [abuse.ch](https://abuse.ch/) - Identify and track cyber threats
  - [Malware Bazaar](https://bazaar.abuse.ch/) - A resource for sharing malware samples.  
  - [Feodo Tracker](https://feodotracker.abuse.ch/) - A resource used to track botnet command and control (C2) infrastructure linked with Emotet, Dridex and TrickBot.  
  - [SSL Blacklist](https://sslbl.abuse.ch/) - A resource for collecting and providing a blocklist for malicious SSL certificates and JA3/JA3s fingerprints.  
  - [URL Haus](https://urlhaus.abuse.ch/) - A resource for sharing malware distribution sites.  
  - [Threat Fox](https://threatfox.abuse.ch/) - A resource for sharing indicators of compromise (IOCs).  

## 3. Standards and Frameworks
[TLP](https://www.cisa.gov/news-events/news/traffic-light-protocol-tlp-definitions-and-usage)  - Traffic Light Protocol 

[TIBER-EU](https://www.ecb.europa.eu/pub/pdf/other/ecb.tiber_eu_framework.en.pdf) - Applying CTI to Red Team exercises  

[Diamon Model](https://www.threatintel.academy/wp-content/uploads/2020/07/diamond_summary.pdf) - The Diamond Model of Intrusion Analysis 

[MILE](https://datatracker.ietf.org/wg/mile/about/) - Managed Incident Lightweight Exchange workgroup
  - [IODEF](https://datatracker.ietf.org/doc/rfc8274/) - Incident Object Description Exchange
  - [RID](https://datatracker.ietf.org/doc/rfc6545/) - Real time Inter-network Defense

[OpenIOC](https://www.mandiant.com/resources/blog/openioc-basics) - Mandiant  

[VERIS](https://github.com/vz-risk/veris) - Vocabulary for Event Recording and Incident Sharing (verizon)  

CFI [1](https://csirtgadgets.com/collective-intelligence-framework) [2](https://github.com/csirtgadgets/cif-v5#getting-started) - The Collective Intelligence Framework

### 3.1 MITRE Standards - CTI management  
Mitre has developed three standards that each fill different needs for a CTI
management system.  


- [CybOX](https://cybox.mitre.org/about/) - Provides a standard for defining indicator details known as observables
  
- [STIX](https://oasis-open.github.io/cti-documentation/stix/intro.html) - A language and serialization format used to exchange cyber threat intelligence (json format)  
  - [SDO & SRO Examples](https://oasis-open.github.io/cti-documentation/stix/walkthrough) - Stix Domain Object & Stix Relationship Object

- [TAXII](https://oasis-open.github.io/cti-documentation/taxii/intro.html) - Trusted Automated Exchange of Intelligence Information

### 3.2 Threat Modeling
A process by which potential threats, such as structural vulnerabilities, can be identified, enumerated, and prioritized – all from a hypothetical attacker’s point of view.  
- [Threat Models Comparison](https://www.softwaresecured.com/post/comparison-of-stride-dread-pasta) - STRIDE/PASTA/DREAD
- [Octave threat model](https://www.iriusrisk.com/resources-blog/octave-threat-modeling-methodologies) 

## 4. Definitions 
- [Types of CTI](https://www.bluevoyant.com/knowledge-center/cyber-threat-intelligence-cti-definition-types-process) - Strategic, Tactical, Operational, Technical
- [Threat Intelligence Lifecycle](https://socradar.io/5-stages-of-the-threat-intelligence-lifecycle/) - The 5 stages of TI (planning, collection, processing, production&analysis, dissemination)
- [Analysis of competing hypotheses](https://en.wikipedia.org/wiki/Analysis_of_competing_hypotheses)
- [ISAC](https://en.wikipedia.org/wiki/Information_Sharing_and_Analysis_Center) - Information Sharing and Analysis Center
- [MTTR, MTTD, MTTF, and MTBF?](https://www.logicmonitor.com/blog/whats-the-difference-between-mttr-mttd-mttf-and-mtbf#:~:text=What%20is%20MTTI%3F,system%20to%20identify%20an%20issue.) - What’s the difference between the various mean times 

## 5. Help Me Understand with ChatGPT :)
[CTI related questions that I asked ChatGPT](https://github.com/slashparity/CTI-Resources/tree/main/Help%20me%20understand%20with%20ChatGPT#description) 



