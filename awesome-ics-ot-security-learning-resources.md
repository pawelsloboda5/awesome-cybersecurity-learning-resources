# Awesome ICS / OT Security Learning Resources

ICS (Industrial Control Systems) and OT (Operational Technology) security covers SCADA, PLCs, HMIs, DCS, historians, safety systems, and the protocols that bind them (Modbus, DNP3, IEC 61850, OPC UA, Profinet, S7). These environments prioritise safety and availability over confidentiality, which inverts many IT security assumptions.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [ICS / OT Tools](#ics--ot-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [Industrial Network Security, 2nd Ed by Eric Knapp, Joel Langill (Syngress)](https://www.elsevier.com/books/industrial-network-security/knapp/978-0-12-420114-9)
2. [Countdown to Zero Day by Kim Zetter](https://www.amazon.com/Countdown-Zero-Day-Stuxnet-Digital/dp/0770436196) - Stuxnet story; required reading.
3. [Hacking Exposed: Industrial Control Systems by Clint Bodungen, Bryan Singer et al.](https://www.mhprofessional.com/hacking-exposed-industrial-control-systems-ics-scada-security-secrets-solutions-9781259589713-usa)
4. [Pentesting Industrial Control Systems by Paul Smith (Packt)](https://www.packtpub.com/product/pentesting-industrial-control-systems/9781800202382)
5. [Practical Industrial Cybersecurity by Charles J. Brooks, Philip A. Craig Jr.](https://www.wiley.com/en-us/Practical+Industrial+Cybersecurity)
6. [NIST SP 800-82 Rev 3 - Guide to OT Security (free)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-82r3.pdf)
7. [ICS Cybersecurity Field Manual Vol 1-3 by Pascal Ackerman (free from Dragos)](https://hub.dragos.com/)
8. [Cybersecurity for Industrial Automation by Pascal Ackerman (Packt)](https://www.packtpub.com/product/industrial-cybersecurity-second-edition/9781800202092)

## Videos
1. [S4 Conference talks](https://www.youtube.com/@S4Events)
2. [Dragos webinars and year-in-review](https://www.youtube.com/@DragosInc)
3. [SANS ICS Summit archives](https://www.sans.org/cyber-security-summit/archives/ics/)
4. [DEF CON ICS Village](https://www.youtube.com/@icsvillage)
5. [Claroty research talks](https://www.youtube.com/@ClarotyLtd)
6. [Langner Communications (Ralph Langner - Stuxnet)](https://www.langner.com/category/videos/)
7. [Robert M. Lee talks on ICS adversaries](https://www.youtube.com/results?search_query=robert+m+lee+ics)

## Free/Paid Courses
### Free
1. [CISA ICS Training (free, ICS-CERT Virtual Learning Portal)](https://www.cisa.gov/ics-training-available-through-cisa)
2. [Dragos Academy free content](https://www.dragos.com/learning/)
3. [ENISA ICS training materials (free)](https://www.enisa.europa.eu/topics/critical-information-infrastructures-and-services/scada)
4. [TryHackMe - ICS / SCADA rooms](https://tryhackme.com/)
5. [OT Cybersecurity Essentials by Nozomi Networks (free webinars)](https://www.nozominetworks.com/)

### Paid
6. [SANS ICS410: ICS/SCADA Security Essentials (GICSP)](https://www.sans.org/cyber-security-courses/ics-scada-security-essentials/)
7. [SANS ICS515: ICS Active Defense and Incident Response (GRID)](https://www.sans.org/cyber-security-courses/ics-active-defense-and-incident-response/)
8. [SANS ICS612: ICS Cybersecurity In-Depth](https://www.sans.org/cyber-security-courses/ics-cybersecurity-in-depth/)
9. [SANS ICS456: Essentials for NERC Critical Infrastructure Protection](https://www.sans.org/cyber-security-courses/essentials-for-nerc-critical-infrastructure-protection/)
10. [ISA/IEC 62443 Cybersecurity training series](https://www.isa.org/certification/certificate-programs/isa-iec-62443-cybersecurity-certificate-program)
11. [Dragos Threat Intelligence & WorldView subscription training](https://www.dragos.com/)
12. [Claroty Academy training](https://academy.claroty.com/)

## Free/Paid Labs
1. [GRFICSv2 - Graphical Realism Framework for Industrial Control Simulation](https://github.com/djformby/GRFICSv2) - Free, full plant simulation.
2. [OpenPLC project](https://openplcproject.com/) - Open-source PLC to build your own lab.
3. [ICSsim / Virtuaplant / PLCSim](https://github.com/thatericsmith/ICSsim)
4. [SANS ICS CyberCity (course labs, paid)](https://www.sans.org/cyber-security-courses/ics-scada-security-essentials/)
5. [Dragos Neighborhood Keeper community data](https://www.dragos.com/neighborhood-keeper/)
6. [Awesome ICS Honeypots (Conpot, GasPot, S7comm-trace)](https://github.com/mushorg/conpot)
7. [CISA Cyber Storm / tabletop exercises](https://www.cisa.gov/cyber-storm-exercises)

## ICS / OT Tools
### Protocol / assessment
1. [Wireshark with ICS dissectors (Modbus, DNP3, IEC 61850, Profinet, S7)](https://www.wireshark.org/)
2. [Scapy + ICS plugins](https://scapy.net/)
3. [Modbus-CLI / modbus-tk / pymodbus](https://github.com/riptideio/pymodbus)
4. [opendnp3 / dnp3-scanner](https://github.com/dnp3/opendnp3)
5. [iec104-python / libiec61850](https://github.com/mz-automation/libiec61850)
6. [PLCScan](https://github.com/meeas/plcscan) / [S7scan](https://github.com/klsecservices/s7scan)
7. [ISF - Industrial Security Framework](https://github.com/w3h/isf)
8. [Industroyer2 / CRASHOVERRIDE research samples (for lab use only)](https://www.welivesecurity.com/)

### Monitoring / passive detection (commercial)
9. [Dragos Platform](https://www.dragos.com/)
10. [Claroty CTD / xDome](https://claroty.com/)
11. [Nozomi Networks Guardian / Vantage](https://www.nozominetworks.com/)
12. [Armis Centrix](https://www.armis.com/)
13. [Tenable OT Security (formerly Indegy)](https://www.tenable.com/products/ot-security)
14. [Cisco Cyber Vision](https://www.cisco.com/c/en/us/products/security/cyber-vision/)

### Honeypots / deception
15. [Conpot (SCADA/ICS honeypot)](https://github.com/mushorg/conpot)
16. [GasPot](https://github.com/sjhilt/GasPot)
17. [T-Pot multi-honeypot distribution](https://github.com/telekom-security/tpotce)

### Mapping / attack
18. [redpoint Nmap scripts for ICS](https://github.com/digitalbond/Redpoint)
19. [Metasploit ICS modules](https://www.metasploit.com/)
20. [ICS-specific exploits archive via exploit-db and ICS-CERT advisories](https://www.exploit-db.com/)

## Certifications
1. [GICSP - Global Industrial Cyber Security Professional (SANS ICS410)](https://www.giac.org/certifications/global-industrial-cyber-security-professional-gicsp/)
2. [GRID - GIAC Response and Industrial Defense (SANS ICS515)](https://www.giac.org/certifications/response-industrial-defense-grid/)
3. [GCIP - GIAC Critical Infrastructure Protection (SANS ICS456)](https://www.giac.org/certifications/critical-infrastructure-protection-gcip/)
4. [ISA/IEC 62443 Cybersecurity Certificate Program (Fundamentals / Risk / Design / Maintenance / Expert)](https://www.isa.org/certification/certificate-programs/isa-iec-62443-cybersecurity-certificate-program)
5. [EC-Council CSA-ICS](https://www.eccouncil.org/) (newer offering)
6. [ISACA CISA / CRISC (adjacent, for audit/risk)](https://www.isaca.org/)

## Blogs/Articles
1. [Dragos blog and annual "Year in Review" report](https://www.dragos.com/blog/)
2. [Claroty Team82 research](https://claroty.com/team82)
3. [Nozomi Labs research](https://www.nozominetworks.com/blog/)
4. [Robert M. Lee's SCADAhacker / Dragos writing](https://www.dragos.com/)
5. [CISA ICS advisories](https://www.cisa.gov/news-events/cybersecurity-advisories/ics-advisories)
6. [MITRE ATT&CK for ICS](https://attack.mitre.org/matrices/ics/)
7. [ICS Kill Chain (Michael Assante, Robert M. Lee)](https://www.sans.org/white-papers/36297/)
8. [NIST SP 800-82 Rev 3 (OT Security, 2023)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-82r3.pdf)
9. [ISA99 / IEC 62443 series overview](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards)
10. [ENISA Good Practices for IoT and OT](https://www.enisa.europa.eu/)
11. [INL / DOE CyberStrike and CESER resources](https://inl.gov/)
12. [Awesome Industrial Control System Security GitHub](https://github.com/hslatman/awesome-industrial-control-system-security)
13. [SCADAhacker resource library](https://scadahacker.com/library/index.html)
14. [Chernovite / Volt Typhoon / Sandworm / Xenotime - APT threat groups of interest (Dragos/Mandiant reporting)](https://www.dragos.com/threat-groups/)
15. [CRASHOVERRIDE / Industroyer, Triton/Trisis, Pipedream/Incontroller technical write-ups](https://www.dragos.com/blog/industry-news/chernovite-pipedream-malware-targeting-industrial-control-systems/)
