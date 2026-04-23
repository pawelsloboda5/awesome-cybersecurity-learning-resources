# Awesome SOC / Blue Team Learning Resources

Security Operations Center (SOC) and blue-team work covers monitoring, triage, detection engineering, log analysis, threat hunting, alert tuning, and incident handoff. It sits at the intersection of SIEM/XDR tooling, detection content (Sigma, KQL, SPL, Elastic DSL), and analyst methodology (pyramid of pain, Kill Chain, ATT&CK).

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [SOC / Blue Team Tools](#soc--blue-team-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [The Practice of Network Security Monitoring by Richard Bejtlich (No Starch)](https://nostarch.com/nsm) - Foundational NSM book; still essential.
2. [Blue Team Handbook: Incident Response Edition by Don Murdoch](https://www.amazon.com/Blue-Team-Handbook-condensed-Responder/dp/1500734756)
3. [Blue Team Handbook: SOC, SIEM, and Threat Hunting Use Cases by Don Murdoch](https://www.amazon.com/Blue-Team-Handbook-Condensed-Operations/dp/1091493898)
4. [Crafting the InfoSec Playbook by Jeff Bollinger et al. (O'Reilly)](https://www.oreilly.com/library/view/crafting-the-infosec/9781491949399/)
5. [Applied Network Security Monitoring by Chris Sanders, Jason Smith](https://www.amazon.com/Applied-Network-Security-Monitoring-Collection/dp/0124172083)
6. [Intelligence-Driven Incident Response by Scott J. Roberts, Rebekah Brown (O'Reilly, 2nd ed 2023)](https://www.oreilly.com/library/view/intelligence-driven-incident-response/9781098120672/)
7. [The Tao of Network Security Monitoring by Richard Bejtlich](https://www.amazon.com/Tao-Network-Security-Monitoring-Intrusion/dp/0321246772) - Older but classic.
8. [Practical Threat Intelligence and Data-Driven Threat Hunting by Valentina Costa-Gazcon (Packt)](https://www.packtpub.com/product/practical-threat-intelligence-and-data-driven-threat-hunting/9781838556372)
9. [The Threat Hunter's Handbook by Anton Chuvakin et al. (free, Chronicle / Google)](https://services.google.com/fh/files/misc/the_threat_hunters_handbook.pdf)

## Videos
1. [13Cubed - DFIR & Windows internals](https://www.youtube.com/@13Cubed) - High-quality, long-running channel.
2. [The Taggart Institute](https://www.youtube.com/@TaggartInstitute) - SOC/blue-team fundamentals.
3. [SANS Blue Team Summit archives](https://www.youtube.com/@SANSInstitute/search?query=blue%20team%20summit)
4. [BSides / DEF CON Blue Team Village](https://www.youtube.com/@BlueTeamVillage)
5. [Microsoft Security community channel](https://www.youtube.com/@MicrosoftSecurity)
6. [Black Hills Information Security webcasts (free)](https://www.youtube.com/@BlackHillsInformationSecurity)
7. [John Hubbard - SOC / blue-team content](https://www.youtube.com/results?search_query=john+hubbard+soc)
8. [MITRE ATT&CKcon archives](https://www.mitre.org/news-insights/events/attackcon)

## Free/Paid Courses
### Free / low-cost
1. [Blue Team Labs Online - BTL1 free content](https://www.securityblue.team/)
2. [LetsDefend - free tier](https://www.letsdefend.io/)
3. [TryHackMe - SOC Level 1 & 2 paths](https://tryhackme.com/paths)
4. [HackTheBox Academy - SOC Analyst path](https://academy.hackthebox.com/path/preview/soc-analyst)
5. [Splunk Fundamentals 1 (free)](https://www.splunk.com/en_us/training/free-courses/overview.html)
6. [Microsoft Learn - SC-200 Security Operations Analyst (free)](https://learn.microsoft.com/en-us/training/courses/sc-200t00)
7. [Elastic Security - free training on elastic.co](https://www.elastic.co/training/free)
8. [AttackIQ Academy - Detection Engineering (free)](https://www.academy.attackiq.com/)
9. [Active Countermeasures - free courses by Chris Brenton](https://www.activecountermeasures.com/free-tools/)

### Paid
10. [SANS SEC450: Blue Team Fundamentals](https://www.sans.org/cyber-security-courses/blue-team-fundamentals-security-operations-analysis/) by John Hubbard - the canonical SOC course.
11. [SANS SEC555: SIEM with Tactical Analytics](https://www.sans.org/cyber-security-courses/siem-with-tactical-analytics/)
12. [SANS SEC511: Continuous Monitoring and Security Operations](https://www.sans.org/cyber-security-courses/continuous-monitoring-security-operations/)
13. [BTL1 / BTL2 by Security Blue Team](https://www.securityblue.team/certifications) - Very practical certs.
14. [Zero Point Security - Sentinel / DFIR Fundamentals](https://training.zeropointsecurity.co.uk/)
15. [CyberDefenders Bootcamp](https://cyberdefenders.org/bootcamp/)

## Free/Paid Labs
1. [CyberDefenders - Blue Team CTFs](https://cyberdefenders.org/) - Dozens of free DFIR / SOC challenges.
2. [LetsDefend - guided SOC incidents](https://www.letsdefend.io/)
3. [TryHackMe SOC paths / Red-vs-Blue rooms](https://tryhackme.com/)
4. [Blue Team Labs Online](https://blueteamlabs.online/)
5. [RangeForce](https://www.rangeforce.com/) - Enterprise-grade blue-team labs.
6. [DetectionLab by Chris Long](https://github.com/clong/DetectionLab) - Full AD + ELK + Velociraptor lab stack (note: archived 2023; see forks).
7. [SOC Simulator by SecurityBlueTeam](https://www.securityblue.team/)
8. [HELK - Hunting ELK by Cyb3rWard0g](https://github.com/Cyb3rWard0g/HELK)
9. [Security Datasets project (Mordor)](https://github.com/OTRF/Security-Datasets) - Pre-recorded attack logs for practice.
10. [Splunk BOTS (Boss of the SOC) v1-v3 datasets](https://github.com/splunk/botsv3)
11. [APT Simulator](https://github.com/NextronSystems/APTSimulator) - Quick IoC generation for detection testing.

## SOC / Blue Team Tools
### SIEM / log platforms
1. [Splunk Enterprise Security](https://www.splunk.com/en_us/products/enterprise-security.html) / Splunk Free
2. [Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel) - Cloud-native SIEM with KQL.
3. [Elastic Security (ELK / Elastic Stack)](https://www.elastic.co/security)
4. [Wazuh](https://wazuh.com/) - Open-source SIEM/XDR.
5. [Graylog](https://graylog.org/)
6. [Google SecOps (Chronicle)](https://cloud.google.com/security/products/security-operations)
7. [IBM QRadar](https://www.ibm.com/products/qradar-siem)
8. [Sumo Logic](https://www.sumologic.com/)
9. [CrowdStrike Falcon Next-Gen SIEM](https://www.crowdstrike.com/platform/next-gen-siem/)

### EDR / XDR
10. [CrowdStrike Falcon](https://www.crowdstrike.com/)
11. [Microsoft Defender for Endpoint](https://www.microsoft.com/en-us/security/business/endpoint-security/microsoft-defender-endpoint)
12. [SentinelOne](https://www.sentinelone.com/)
13. [Sysmon (open-source endpoint telemetry)](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) - Use with [SwiftOnSecurity's Sysmon config](https://github.com/SwiftOnSecurity/sysmon-config) or [Olaf Hartong's config](https://github.com/olafhartong/sysmon-modular).
14. [OSSEC](https://www.ossec.net/) / [Wazuh agent](https://wazuh.com/)
15. [osquery](https://osquery.io/) - SQL-based endpoint telemetry.

### Detection content / rules
16. [Sigma](https://github.com/SigmaHQ/sigma) - Vendor-neutral detection rule format.
17. [Elastic detection rules](https://github.com/elastic/detection-rules)
18. [Splunk Security Content](https://github.com/splunk/security_content)
19. [Azure Sentinel Community rules](https://github.com/Azure/Azure-Sentinel)
20. [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) - Adversary test library; essential for detection validation.
21. [Red Canary Mac Monitor / Canary Tokens](https://canarytokens.org/)

### Network defense
22. [Zeek](https://zeek.org/), [Suricata](https://suricata.io/), [Snort 3](https://www.snort.org/)
23. [Security Onion](https://securityonionsolutions.com/) - Turnkey SOC distro.
24. [Arkime (formerly Moloch)](https://arkime.com/) - Full PCAP indexing.
25. [RITA by Active Countermeasures](https://github.com/activecm/rita) - Beacon / C2 analysis.

### SOAR / automation
26. [Shuffle](https://shuffler.io/) - Open-source SOAR.
27. [TheHive + Cortex](https://strangebee.com/thehive/) - Case management + response.
28. [Tines](https://www.tines.com/) / [Torq](https://torq.io/) - Commercial SOAR.
29. [Splunk SOAR (formerly Phantom)](https://www.splunk.com/en_us/products/splunk-security-orchestration-and-automation.html)

### Threat hunting
30. [Jupyter notebooks + MSTICPy by Microsoft](https://github.com/microsoft/msticpy)
31. [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK)
32. [Velociraptor](https://docs.velociraptor.app/) - Endpoint hunting & DFIR.
33. [KAPE by Eric Zimmerman](https://www.kroll.com/en/services/cyber-risk/investigate-and-respond/kroll-artifact-parser-extractor-kape)

## Certifications
1. [BTL1 / BTL2 by Security Blue Team](https://www.securityblue.team/certifications) - Very respected practical certs.
2. [GCIA - GIAC Certified Intrusion Analyst (SANS)](https://www.giac.org/certifications/certified-intrusion-analyst-gcia/)
3. [GCIH - GIAC Certified Incident Handler](https://www.giac.org/certifications/certified-incident-handler-gcih/)
4. [GMON - GIAC Continuous Monitoring Certification](https://www.giac.org/certifications/continuous-monitoring-gmon/)
5. [GCDA - GIAC Certified Detection Analyst](https://www.giac.org/certifications/certified-detection-analyst-gcda/)
6. [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst)
7. [Microsoft SC-200 Security Operations Analyst](https://learn.microsoft.com/en-us/certifications/security-operations-analyst/)
8. [Cisco CyberOps Associate / Professional](https://learningnetwork.cisco.com/s/cyberops-associate)
9. [Splunk Core / Splunk Enterprise Security certifications](https://www.splunk.com/en_us/training/certification-track/splunk-core-certified-user.html)
10. [EC-Council CSA / CTIA](https://www.eccouncil.org/programs/certified-soc-analyst-csa/)
11. [HTB CDSA - Certified Defensive Security Analyst](https://academy.hackthebox.com/preview/certifications/htb-certified-defensive-security-analyst)
12. [TCM Security PSAA - Practical SOC Analyst Associate](https://certifications.tcm-sec.com/psaa/)

## Blogs/Articles
1. [MITRE ATT&CK](https://attack.mitre.org/) - Technique reference every analyst should bookmark.
2. [MITRE D3FEND](https://d3fend.mitre.org/) - Defensive techniques companion.
3. [The DFIR Report](https://thedfirreport.com/) - Intrusion walk-throughs with IOCs and Sigma rules.
4. [Red Canary Threat Detection Report (annual)](https://redcanary.com/threat-detection-report/)
5. [Microsoft Defender XDR / Sentinel blog](https://techcommunity.microsoft.com/category/microsoft-security)
6. [SANS Internet Storm Center diary](https://isc.sans.edu/diary.html)
7. [Pyramid of Pain - David Bianco](http://detect-respond.blogspot.com/2013/03/the-pyramid-of-pain.html)
8. [Palantir Alerting and Detection Strategy framework](https://github.com/palantir/alerting-detection-strategy-framework)
9. [Detection Engineering Cookbook](https://github.com/infosecB/awesome-detection-engineering)
10. [Awesome SOC GitHub list](https://github.com/cyb3rxp/awesome-soc)
11. [Detection Engineering Weekly newsletter by Zack "techstackr" Allen](https://www.detectionengineering.net/)
12. [Chris Sanders' blog (NSM, investigation theory)](https://chrissanders.org/)
13. [Anton Chuvakin's blog - SOC/SIEM research](https://medium.com/anton-on-security)
14. [Florian Roth (Nextron) - detection research and YARA/Sigma rules](https://cyb3rops.medium.com/)
15. [OSSEM - Open Source Security Events Metadata](https://github.com/OTRF/OSSEM)
