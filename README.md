# Awesome Threat Intelligence [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome threat intelligence resources, tools, feeds, and platforms.
>
> **Last updated:** 2026-10-21
> **Total entries:** 68

## About This List

This list is organized by a clean, non-overlapping taxonomy. Each entry includes structured metadata
enabling filtering by license, region, deployment model, data type, and more.

### Badge Legend

- ![Open Source](https://img.shields.io/badge/License-Open%20Source-green) = Free and open-source software
- ![Commercial](https://img.shields.io/badge/License-Commercial-orange) = Commercial/paid software
- ![Freemium](https://img.shields.io/badge/License-Freemium-blue) = Free tier with paid upgrades
- ![EU](https://img.shields.io/badge/Region-EU-blueviolet) = Vendor headquartered in the European Union
- ![API](https://img.shields.io/badge/API-Yes-brightgreen) = REST/GraphQL API available
- ![STIX/TAXII](https://img.shields.io/badge/STIX%2FTAXII-Yes-brightgreen) = STIX/TAXII protocol support

### Quick Filter Guide

- **Looking for open-source TIPs?** See [Threat Intelligence Platforms](#threat-intelligence-platforms) and filter by `Open Source` license
- **Looking for free threat feeds?** See [Intelligence Feeds & Data Providers](#intelligence-feeds--data-providers) and filter by `Free` access
- **Looking for EU-based vendors?** Look for the ![EU](https://img.shields.io/badge/Region-EU-blueviolet) badge

### Taxonomy

| Category | Description |
|----------|-------------|
| [Threat Intelligence Platforms](#threat-intelligence-platforms) | Systems that ingest, enrich, correlate, and manage threat intelligence. If it aggregates and operationalizes intelligence, it belongs here. |
| [Intelligence Feeds & Data Providers](#intelligence-feeds-data-providers) | Sources that provide raw or processed intelligence data (IOCs, TTPs, reports, reputation data). If it primarily provides data, it belongs here. |
| [OSINT & Collection Tools](#osint-collection-tools) | Tools used to collect intelligence from public or semi-public sources. If it gathers data but does not provide curated intel, it belongs here. |
| [Frameworks & Standards](#frameworks-standards) | Models and protocols used to structure or exchange intelligence (MITRE ATT&CK, STIX, TAXII, etc.). |

---

## Threat Intelligence Platforms

*Systems that ingest, enrich, correlate, and manage threat intelligence. If it aggregates and operationalizes intelligence, it belongs here.*

| Name | Description | License | Region | Access |
|------|-------------|---------|--------|--------|
| [AIL Framework](https://www.ail-project.org/) | Modular intelligence and leak-analysis platform for collecting, crawling, and analyzing unstructured data from web, Tor, and chat sources. | Open Source | EU | Free |
| [Anomali ThreatStream](https://www.anomali.com/) | Commercial threat intelligence platform aggregating 140+ open-source feeds with contextual enrichment and prioritization. | Commercial | US | Paid |
| [CrowdStrike Falcon Adversary Intelligence](https://www.crowdstrike.com/en-us/platform/threat-intelligence/) | Threat intelligence and hunting platform tracking 280+ adversaries with AI-powered analysis and dark web monitoring. | Commercial | US | Paid |
| [Cyware](https://cyware.com/) | Threat intelligence platform with automated IOC correlation, threat sharing hubs, and SOAR integration for CTI teams. | Commercial | US | Paid |
| [DeCYFIR](https://www.decyfir.ai/) | Commercial threat intelligence and threat hunting platform focused on adversary attribution and infrastructure mapping. | Commercial | North America | Paid |
| [FlowIntel](https://flowintel.org/) | Open-source case and task management platform for security analysts with MISP integration and export modules. | Open Source | EU | Free |
| [Intel 471](https://www.intel471.com/) | Commercial threat intelligence provider specializing in cybercrime ecosystem monitoring and adversary tracking. | Commercial | US | Paid |
| [IntelOwl](https://github.com/intelowlproject/IntelOwl) | Open-source threat intelligence management solution that integrates analyzers, enrichment tools, and malware analysis capabilities. | Open Source | EU | Free |
| [Kaspersky Threat Intelligence Portal](https://www.kaspersky.com/enterprise-security/services/threat-intelligence) | Commercial threat intelligence platform providing access to 25+ years of threat data, MITRE ATT&CK mapping, and sandbox reports. | Commercial | Europe/Asia | Paid |
| [MISP](https://www.misp-project.org/) | Open-source threat intelligence and sharing platform for collecting, storing, and distributing structured security indicators. | Open Source | EU | Free |
| [ODYSAFE-CTI](https://github.com/Odysafe/ODYSAFE-CTI) | Lightweight open-source CTI platform with STIX 2.1 graph visualization, 50+ IOC types, and offline-first operation. | Open Source | EU | Free |
| [OpenCTI](https://github.com/opencti-platform/opencti) | Open-source cyber threat intelligence platform for managing, structuring, and visualizing threat knowledge using STIX 2. | Open Source | EU | Free |
| [Rapid7](https://www.rapid7.com/) | Unified cybersecurity platform offering exposure management, SIEM, MDR, and threat intelligence. | Commercial | US | Paid |
| [Recorded Future](https://recordedfuture.com/) | Commercial threat intelligence platform aggregating data from over one million sources across open, dark, and technical web. | Commercial | US | Paid |
| [SOCRadar](https://socradar.io/) | Extended threat intelligence platform covering dark web monitoring, brand protection, and vulnerability management. | Commercial | Middle East | Paid |
| [TheHive](https://thehive-project.org/) | Security incident response and case management platform designed for SOC, CSIRT, and DFIR teams. | Open Source | EU | Free |
| [Threat Landscape](https://threatlandscape.io/) | Automated threat intelligence platform extracting, structuring, and correlating global OSINT and darknet signals into STIX-native graphs with MITRE ATT&CK mapping. | Commercial | EU | Paid |
| [ThreatConnect](https://www.threatconnect.com/) | Commercial threat intelligence and security risk management platform combining TI, threat operations, and vulnerability management. | Commercial | US | Paid |
| [Yeti](https://github.com/yeti-platform/yeti) | Open-source platform for organizing, storing, and enriching threat intelligence observables, IOCs, and TTPs. | Open Source | EU | Free |

---

## Intelligence Feeds & Data Providers

*Sources that provide raw or processed intelligence data (IOCs, TTPs, reports, reputation data). If it primarily provides data, it belongs here.*

| Name | Description | License | Region | Access |
|------|-------------|---------|--------|--------|
| [AbuseIPDB](https://www.abuseipdb.com/) | IP address abuse reporting and reputation database for identifying malicious IPs used in brute-force, spam, and DDoS attacks. | Freemium | EU | Free |
| [AlienVault OTX](https://otx.alienvault.com/) | Open Threat Exchange with community-driven IOC sharing processing millions of indicators daily across multiple formats. | Freemium | US | Free |
| [Blocklist.de](https://www.blocklist.de/) | IP blocklist of addresses associated with brute-force attacks on SSH, mail, FTP, and web services updated every 12 hours. | Open Source | EU | Free |
| [CERT-Bund](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Cyber-Sicherheitslage/Reaktion/CERT-Bund/) | German national CERT providing threat intelligence, incident response, and security advisories for federal agencies and citizens. | Open Source | EU | Free |
| [CERT-FR (ANSSI)](https://www.cert.ssi.gouv.fr/) | French national CERT providing threat intelligence reports, APT analysis, and CTI indicators via its public portal. | Open Source | EU | Free |
| [CISA AIS](https://www.cisa.gov/ais) | DHS Automated Indicator Sharing program distributing IOCs via STIX/TAXII to federal, state, and local government partners. | Open Source | US | Free |
| [CISA Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories) | Joint FBI/CISA/MS-ISAC advisories with STIX JSON/XML IOCs including the #StopRansomware series covering major ransomware groups. | Open Source | US | Free |
| [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) | Known Exploited Vulnerabilities catalog from CISA tracking CVEs actively exploited in the wild. | Open Source | US | Free |
| [CISA Stop Ransomware](https://www.cisa.gov/stopransomware) | Joint multi-agency campaign covering major ransomware groups including Medusa, Play, and LockBit with STIX IOC packages. | Open Source | US | Free |
| [Cisco Talos IOCs](https://github.com/Cisco-Talos/IOCs) | GitHub repository with IOCs from Cisco Talos research updated weekly, covering malware campaigns, exploits, and threat actors. | Open Source | US | Free |
| [DShield / SANS ISC](https://isc.sans.edu/) | Top attacking IP feed from the SANS Internet Storm Center global sensor network with daily summaries. | Open Source | US | Free |
| [Emerging Threats Open](https://rules.emergingthreats.net/) | Open-source IDS rules and IP blocklists from Proofpoint for network-based threat detection. | Open Source | US | Free |
| [FBI IC3](https://www.ic3.gov/) | Internet Crime Complaint Center tracking cybercrime trends with annual reports and public complaint submission for threat reporting. | Open Source | US | Free |
| [Feodo Tracker](https://feodotracker.abuse.ch/) | abuse.ch botnet C2 server tracking project monitoring Emotet, Dridex, QakBot, and other banking trojans. | Open Source | EU | Free |
| [GreyNoise](https://www.greynoise.io/) | IP noise classification service distinguishing targeted attacks from benign internet scanners and mass exploitation. | Freemium | US | Free |
| [HIPPOCampe](https://github.com/TheHive-Project/HIPPOCampe) | Open-source threat feed aggregator with REST API and native integration with TheHive and Cortex for SOC workflows. | Open Source | EU | Free |
| [Hunt.io C2 Feed](https://hunt.io/) | High-confidence malicious infrastructure feed providing C2 server IPs identified through continuous scanning. | Commercial | US | Free |
| [ICHI Internet Cyber Health Index](https://ichi.global/) | Free, source-transparent daily barometer of internet-wide cyber health. Aggregates 28+ live feeds (CISA KEV, EPSS, ransomware, C2 infra, DShield) into an hourly composite score with RSS alerts. | Open Source | US | Free |
| [JPCERT/CC](https://www.jpcert.or.jp/english/) | Japanese CERT providing quarterly TSUBAME threat monitoring reports, APT analysis, and vulnerability coordination. | Open Source | APAC | Free |
| [Malware Patrol](https://www.malwarepatrol.net/) | Commercial threat intelligence feed provider specializing in malware URLs, IPs, C2s, and DGAs since 2005. | Commercial | US | Paid |
| [MalwareBazaar](https://bazaar.abuse.ch/) | abuse.ch malware sample hash repository for sharing and discovering malicious file samples with family classification. | Open Source | EU | Free |
| [OpenPhish](https://openphish.com/) | ML-detected phishing URL feed with free community feed and premium real-time updates for phishing detection. | Freemium | EU | Free |
| [PhishTank](https://www.phishtank.com/) | Community-verified phishing URL database operated by Cisco Talos for tracking active phishing sites. | Open Source | US | Free |
| [Pulsedive](https://pulsedive.com/) | Free community threat intelligence database that compiles open-source feeds, enriches IOCs, and provides risk scoring. | Freemium | US | Free |
| [SingCERT](https://www.csa.gov.sg/resources/singcert) | Singapore national CERT providing security bulletins, CVE summaries, advisories, and incident response coordination. | Open Source | APAC | Free |
| [Spamhaus DROP](https://www.spamhaus.org/drop/) | Don't Route Or Peer blocklist of IP/CIDR ranges known for spam, phishing, and malware distribution infrastructure. | Open Source | EU | Free |
| [SSL Blacklist](https://sslbl.abuse.ch/) | abuse.ch project maintaining a blocklist of malicious SSL certificate fingerprints and JA3 hashes. | Open Source | EU | Free |
| [Threat Landscape API](https://threatlandscape.io/products/api) | REST and TAXII 2.1 APIs delivering STIX 2.1-native threat intelligence with two endpoints: contextual intelligence and lean IOC ingestion. | Commercial | EU | API |
| [ThreatFox](https://threatfox.abuse.ch/) | abuse.ch project for community IOC sharing linked to specific malware families and campaigns. | Open Source | EU | Free |
| [URLhaus](https://urlhaus.abuse.ch/) | Abuse.ch project tracking malware distribution URLs with community-submitted indicators for rapid blocking. | Open Source | EU | Free |
| [Viriback C2 Tracker](https://tracker.viriback.com/) | Community-driven C2 infrastructure tracker using Shodan-based queries to collect IPs linked to malware and botnet panels. | Open Source | Other | Free |
| [VirusTotal](https://www.virustotal.com/) | Multi-engine malware analysis and URL/domain reputation service aggregating results from 70+ antivirus scanners. | Freemium | US | Free |

---

## OSINT & Collection Tools

*Tools used to collect intelligence from public or semi-public sources. If it gathers data but does not provide curated intel, it belongs here.*

| Name | Description | License | Region | Access |
|------|-------------|---------|--------|--------|
| [Censys](https://censys.com/) | Internet scanning platform providing continuous discovery and monitoring of internet-connected hosts and certificates. | Freemium | US | Free |
| [Flowsint](https://www.flowsint.io/) | A modern platform for visual, flexible, and extensible graph-based investigations. For cybersecurity analysts and investigators. | Open Source | Unknown | Free |
| [Intelligence X](https://intelx.io/) | Search engine and data archive for Tor, I2P, pastebins, document leaks, and darknet sources with API access. | Freemium | EU | Free |
| [Maltego](https://www.maltego.com/) | Visual link analysis and OSINT investigation tool for discovering relationships between people, infrastructure, and organizations. | Freemium | EU | Free |
| [SecurityTrails](https://securitytrails.com/) | Domain and IP intelligence platform providing historical DNS, WHOIS, and attack surface data for threat research. | Freemium | US | Free |
| [Shodan](https://www.shodan.io/) | Search engine for internet-connected devices providing visibility into exposed services, ports, and vulnerable infrastructure. | Freemium | US | Free |
| [SpiderFoot](https://www.spiderfoot.net/) | Open-source OSINT automation tool for gathering intelligence on IP addresses, domains, email addresses, and usernames. | Open Source | APAC | Free |
| [STIX Visualizer](https://stix-viewer.threatlandscape.io/) | Free interactive STIX 2.1 object visualizer. Paste any STIX bundle and instantly explore the relationship graph between threat actors, malware, campaigns, indicators, and more. | Open Source | EU | Free |
| [TweetFeed](https://tweetfeed.live/) | IOC collection tool that harvests indicators shared by the infosec community on Twitter/X in near real-time. | Open Source | EU | Free |
| [URLScan.io](https://urlscan.io/) | Website scanning and analysis service providing screenshots, DOM snapshots, and security assessment of URLs. | Open Source | EU | Free |

---

## Frameworks & Standards

*Models and protocols used to structure or exchange intelligence (MITRE ATT&CK, STIX, TAXII, etc.).*

### Framework

| Name | Description | License | Region | Access |
|------|-------------|---------|--------|--------|
| [ENISA Cybersecurity Threat Landscape Methodology](https://www.enisa.europa.eu/publications/enisa-cybersecurity-threat-landscape-methodology) | Formal methodology for producing horizontal, thematic, and sectorial threat landscapes used across EU member states. | Open Source | EU | Free |
| [MISP Galaxy](https://github.com/MISP/misp-galaxy) | Collection of threat intelligence reference data including threat actors, malware, RATs, and ransomware clusters for MISP tagging. | Open Source | EU | Free |
| [MITRE ATT&CK](https://attack.mitre.org/) | Globally-accessible knowledge base of adversary tactics and techniques based on real-world observations. | Open Source | US | Free |

### Standard

| Name | Description | License | Region | Access |
|------|-------------|---------|--------|--------|
| [OASIS CTI Technical Committee](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cti) | Technical committee of 190+ members maintaining and evolving the STIX and TAXII standards for threat intelligence exchange. | Open Source | US | Free |
| [STIX](https://oasis-open.github.io/cti-documentation/) | Structured Threat Information Expression standard for representing and sharing cyber threat intelligence in machine-readable format. | Open Source | US | Free |
| [TAXII](https://oasis-open.github.io/cti-documentation/) | Trusted Automated Exchange of Intelligence Information protocol for transporting STIX data between services over HTTPS. | Open Source | US | Free |
| [TLP](https://www.first.org/tlp/) | Traffic Light Protocol for indicating how far intelligence can be shared across organizational boundaries. | Open Source | US | Free |

---

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.
