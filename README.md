# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Threat actors chained and exploited multiple zero-day vulnerabilities affecting Ivanti CSA (Cloud Services Appliance).If successful, this could lead an attacker to gain admin access, obtain credentials, bypass security measures, run arbitrary SQL commands, and execute code remotely. 

 The **Outbreak Response - Ivanti Cloud Services Appliance Zero-Day Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/ivanti-csa-zero-day-attack) contains information about the outbreak alert **Outbreak Response - Ivanti Cloud Services Appliance Zero-Day Attack**. 

## Background: 

In an incident response engagement during September 2024, FortiGuard Incident Response (FGIR) services discovered a campaign targeting Ivanti Cloud Services Appliance (CSA) for initial access and released a detailed Threat Blog. To read more, visit: https://www.fortinet.com/blog/threat-research/burning-zero-days-suspected-nation-state-adversary-targets-ivanti-csa

According to a new report released by CISA on 22 January 2025, in response to exploitation activities relating to Ivanti Cloud Service Appliances (CSA): CVE-2024-8963, an administrative bypass vulnerability; CVE-2024-9379, a SQL injection vulnerability; and CVE-2024-8190 and CVE-2024-9380, remote code execution vulnerabilities. Threat actors chained the listed vulnerabilities to gain initial access, conduct remote code execution (RCE), obtain credentials, and implant webshells on victim networks. 

Ivanti has available updates for Ivanti CSA (Cloud Services Appliance) which addresses these vulnerabilities. FortiGuard recommends users apply the vendor's fixes as mentioned in the advisory and validate your security controls. (See the References section for the link to the patch release)
 

## Announced: 

Please note: Ivanti also recently disclosed two new vulnerabilities affecting, Ivanti Connect Secure, Policy Secure & ZTA Gateways (CVE-2025-0282, CVE-2025-0283)  - To read more, see the relevant FortiGuard Threat Signal posted at https://www.fortiguard.com/threat-signal-report/5612 

## Latest Developments: 

January 22, 2025: The Cybersecurity and Infrastructure Security Agency (CISA) and Federal Bureau of Investigation (FBI) are releasing this joint Cybersecurity Advisory in response to exploitation in September 2024 of vulnerabilities in Ivanti Cloud Service Appliances (CSA)
https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-022a

October 11, 2024: FortiGuard Threat Research team released a Blog on Suspected Nation-State Adversary Targets Ivanti CSA.
https://www.fortinet.com/blog/threat-research/burning-zero-days-suspected-nation-state-adversary-targets-ivanti-csa

October 8, 2024: FortiGuard Labs released a Threat Signal on Ivanti CSA (Cloud Services Appliance) Zero-Day Attack
https://www.fortiguard.com/threat-signal-report/5556/

October 8, 2024: Security Advisory Ivanti CSA (Cloud Services Application) (CVE-2024-9379, CVE-2024-9380, CVE-2024-9381)
https://forums.ivanti.com/s/article/Security-Advisory-Ivanti-CSA-Cloud-Services-Appliance-CVE-2024-9379-CVE-2024-9380-CVE-2024-9381?language=en_US

September 13, 2024: FortiGuard Labs released a Threat Signal on Ivanti Cloud Services Appliance (CSA) OS Command Injection Vulnerability (CVE-2024-8190)
https://fortiguard.fortinet.com/threat-signal-report/5523 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|