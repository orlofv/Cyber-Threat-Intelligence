# crtia
An exhaustive collection of resources used in my studies for the CRTIA

## Table of Contents 
- [1. Blog posts & Articles](#1-blog-posts--articles)
- [2. Tools & Collections](#2-tools--collections)
- [3. Standards & Frameworks](#3-standards-and-frameworks)
  -   [3.1 Mitre Standards - CTI management](#31-mitre-standards---cti-management)
- [4. Help Me Understand with ChatGPT :)](#4-help-me-understand-with-chatgpt-)

  
## 1. Blog posts & Articles 
Getting started in cyber threat intelligence: [4 pieces of advice](https://redcanary.com/blog/getting-started-in-cyber-threat-intelligence/)  

A Top 10 [Reading List](https://medium.com/katies-five-cents/a-top-10-reading-list-if-youre-getting-started-in-cyber-threat-intelligence-c11a18fc9798) if You’re Getting Started in Cyber Threat Intelligence 

CTI [Reading List](https://sroberts.medium.com/cti-reading-list-a93ccdd7469c)  

## 2. Tools & Collections
https://github.com/hslatman/awesome-threat-intelligence  

## 3. Standards and Frameworks
[TLP](https://www.cisa.gov/news-events/news/traffic-light-protocol-tlp-definitions-and-usage)  - Traffic Light Protocol 

[MILE](https://datatracker.ietf.org/wg/mile/about/) - Managed Incident Lightweight Exchange workgroup
  - [IODEF](https://datatracker.ietf.org/doc/rfc8274/) - Incident Object Description Exchange
  - [RID](https://datatracker.ietf.org/doc/rfc6545/) - Real time Inter-network Defense

[OpenIOC](https://www.mandiant.com/resources/blog/openioc-basics) - Mandiant  

[VERIS](https://github.com/vz-risk/veris)   - Vocabulary for Event Recording and Incident Sharing (verizon)

### 3.1 Mitre Standards - CTI management  
Mitre has developed three standards that each fill different needs for a CTI
management system.  


[CybOX](https://cybox.mitre.org/about/) - Provides a standard for defining indicator details known as observables  
[STIX](
## 4. Help Me Understand with ChatGPT :) 

Q: What's the difference between CybOX and VERIS   

A: CybOX and VERIS serve similar purposes in the cybersecurity domain by standardizing the way cybersecurity incidents are described, but they focus on different aspects. CybOX details the technical specifications of cyber threats and incidents, aiming for precise descriptions of observables in the cyber environment. VERIS, developed by Verizon, focuses more on categorizing and analyzing security incidents from a business impact perspective, including what happened, how it happened, and the effect on the organization. Essentially, CybOX is more about the technical "signatures," while VERIS is about the incident "story" and its implications.  

---

Q: Which are the most common/popular frameworks and protocols used in CTI today (2024)?

A: In the realm of Cyber Threat Intelligence (CTI), several protocols and frameworks stand out due to their widespread adoption and effectiveness in facilitating the exchange, analysis, and understanding of threat data. The most popular ones, as of my last update, include:

STIX (Structured Threat Information eXpression) and TAXII (Trusted Automated Exchange of Indicator Information):

STIX is a language and serialization format used to convey threat intelligence in a structured manner. It enables organizations to share detailed information about threats, including indicators of compromise (IoCs), tactics, techniques, and procedures (TTPs) of threat actors, and vulnerabilities.
TAXII is a protocol that operates alongside STIX to automate the exchange of information formatted in STIX. TAXII defines services and message exchanges to enable sharing of actionable threat information across organization and product boundaries.
Together, STIX and TAXII provide a comprehensive ecosystem for threat intelligence sharing, supporting various use cases from tactical to strategic levels.
OpenIOC (Open Indicators of Compromise):

Developed by Mandiant, OpenIOC is an open framework for sharing threat intelligence. It focuses on defining and communicating the technical characteristics that describe a malware threat, compromise, or attack operation.
OpenIOC allows for the detailed description of the technical indicators that can be used to detect malicious activities, making it particularly useful for incident response and threat detection.
MISP (Malware Information Sharing Platform & Threat Sharing):

MISP is an open-source software solution for collecting, storing, distributing, and sharing cybersecurity indicators and threats. It's designed to facilitate the exchange of structured information and improve the overall situational awareness of organizations.
MISP supports a wide range of standards for threat intelligence, including STIX, OpenIOC, and others, making it a versatile tool for threat intelligence communities and organizations.
CycloneDX and SWID (Software Identification Tags):

While not exclusively CTI protocols, CycloneDX and SWID tags are increasingly used within the cybersecurity industry for software component analysis and vulnerability tracking.
CycloneDX is a lightweight software bill of materials (SBOM) standard designed for use in application security contexts and supply chain component analysis.
SWID Tags provide a standard means for identifying software products and components. When used in cybersecurity, they help organizations track vulnerabilities and exposures associated with specific software components.
IODEF (Incident Object Description Exchange Format):

As mentioned previously, IODEF is a standard for describing cybersecurity incidents in a common format to improve incident response and cooperation among different entities. It's particularly valued in communities where rapid and clear communication about incidents is critical.
These protocols and frameworks are crucial for cybersecurity operations, enabling better detection, response, and understanding of cyber threats. The choice among them often depends on the specific needs of an organization, such as the type of threat intelligence being shared, the organization's role within the cybersecurity ecosystem, and interoperability requirements with existing tools and platforms.



