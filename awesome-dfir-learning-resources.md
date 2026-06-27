# Awesome DFIR (Digital Forensics & Incident Response) Learning Resources

DFIR combines digital forensics (host, memory, network, cloud, mobile) with incident response (triage, scoping, containment, eradication, recovery, lessons-learned). Skills in this domain translate across SOC, consulting, and law-enforcement roles.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [DFIR Tools](#dfir-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [The Art of Memory Forensics by Michael Hale Ligh et al.](https://www.wiley.com/en-us/The+Art+of+Memory+Forensics) - Companion to Volatility; gold standard.
2. [File System Forensic Analysis by Brian Carrier](https://www.informit.com/store/file-system-forensic-analysis-9780321268174) - Deep FS internals (NTFS, ext, FAT).
3. [Practical Forensic Imaging by Bruce Nikkel (No Starch)](https://nostarch.com/pfi)
4. [Incident Response & Computer Forensics, 3rd Ed by Jason Luttgens, Matthew Pepe, Kevin Mandia](https://www.amazon.com/Incident-Response-Computer-Forensics-Third/dp/0071798684)
5. [Windows Forensic Analysis Toolkit by Harlan Carvey (4th Ed)](https://www.elsevier.com/books/windows-forensic-analysis-toolkit/carvey/978-0-12-417157-2)
6. [Digital Forensics and Incident Response, 3rd Ed by Gerard Johansen (Packt, 2022)](https://www.packtpub.com/product/digital-forensics-and-incident-response-third-edition/9781803238678)
7. [Intelligence-Driven Incident Response, 2nd Ed by Scott Roberts, Rebekah Brown (O'Reilly, 2023)](https://www.oreilly.com/library/view/intelligence-driven-incident-response/9781098120672/)
8. [Learning Malware Analysis by Monnappa K A (Packt)](https://www.packtpub.com/product/learning-malware-analysis/9781788392501) - Strong IR + malware crossover.
9. [Blue Team Handbook: Incident Response Edition by Don Murdoch](https://www.amazon.com/Blue-Team-Handbook-condensed-Responder/dp/1500734756)
10. [NIST SP 800-61 Rev 3 - Incident Response Recommendations for Cybersecurity Risk Management: A CSF 2.0 Community Profile (free, Apr 2025)](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r3.pdf) - First update since 2012; restructured to align with CSF 2.0.
11. [NIST SP 800-86 - Guide to Integrating Forensic Techniques (free)](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-86.pdf)

## Videos
1. [13Cubed by Richard Davis](https://www.youtube.com/@13Cubed) - The DFIR YouTube channel.
2. [DFIR Science](https://www.youtube.com/@DFIRScience)
3. [SANS DFIR Summit archives](https://www.youtube.com/@SANSInstitute/search?query=DFIR%20Summit)
4. [13Cubed mini-courses on Windows forensics](https://www.13cubed.com/trainings)
5. [Andrew Rathbun - DFIR walkthroughs](https://www.youtube.com/@AndrewRathbun)
6. [The DFIR Report on YouTube](https://www.youtube.com/@TheDFIRReport)
7. [Osquery and Velociraptor channels](https://www.youtube.com/@velociraptor1369)

## Free/Paid Courses
### Free / low-cost
1. [SANS DFIR free resources hub](https://www.sans.org/cyber-security-resources/dfir/)
2. [13Cubed - Investigating Windows Endpoints (paid but widely considered best value)](https://www.13cubed.com/trainings)
3. [Ali Hadi (DFIR.Science) - free DFIR walkthroughs and datasets](https://dfir.science/)
4. [AceResponder free incident response tutorials](https://aceresponder.com/)
5. [TryHackMe - SOC Level 1/2 & DFIR rooms](https://tryhackme.com/)
6. [Blue Team Labs Online](https://blueteamlabs.online/)
7. [Open Source DFIR Workshop by Google](https://github.com/google/IRM)
8. [CISA Incident Response Playbooks (free)](https://www.cisa.gov/resources-tools/services/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)

### Paid / SANS
9. [SANS FOR500: Windows Forensic Analysis (GCFE)](https://www.sans.org/cyber-security-courses/windows-forensic-analysis/)
10. [SANS FOR508: Advanced Incident Response, Threat Hunting, and Digital Forensics (GCFA)](https://www.sans.org/cyber-security-courses/advanced-incident-response-threat-hunting-training/)
11. [SANS FOR572: Advanced Network Forensics (GNFA)](https://www.sans.org/cyber-security-courses/advanced-network-forensics-threat-hunting-incident-response/)
12. [SANS FOR578: Cyber Threat Intelligence (GCTI)](https://www.sans.org/cyber-security-courses/cyber-threat-intelligence/)
13. [SANS FOR585: Smartphone Forensic Analysis In-Depth (GASF)](https://www.sans.org/cyber-security-courses/smartphone-forensic-analysis-in-depth/)
14. [SANS FOR509: Enterprise Cloud Forensics and Incident Response](https://www.sans.org/cyber-security-courses/enterprise-cloud-forensics-incident-response/)
15. [SANS FOR608: Enterprise-Class Incident Response & Threat Hunting](https://www.sans.org/cyber-security-courses/enterprise-class-incident-response-threat-hunting/)
16. [Magnet Forensics AXIOM training](https://www.magnetforensics.com/training/)
17. [13Cubed Investigating Windows Memory / Endpoints](https://www.13cubed.com/trainings)

## Free/Paid Labs
1. [CyberDefenders - blue-team & DFIR challenges](https://cyberdefenders.org/)
2. [DFIR.training - free evidence/CTF links collection](https://dfir.training/)
3. [Magnet Weekly CTF / Magnet Virtual Summit CTF](https://www.magnetforensics.com/blog/tag/magnet-weekly-ctf-challenge/)
4. [Ali Hadi Challenges (Precision Widgets / HoneyNet / CyberSec)](https://github.com/ashemery/dfir-challenges)
5. [Belkasoft CTFs](https://belkasoft.com/ctf)
6. [DFIR Madness - scenario-based practice](https://dfirmadness.com/)
7. [DigitalCorpora - forensic datasets](https://digitalcorpora.org/)
8. [Honeynet Project challenges](https://www.honeynet.org/challenges/)
9. [BootCamp-style Defender tabletop scenarios (CISA)](https://www.cisa.gov/resources-tools/services/cyber-tabletop-exercises)
10. [Unit 42 "Incident of the Week" style walkthroughs](https://unit42.paloaltonetworks.com/)

## DFIR Tools
### Triage / live collection
1. [KAPE by Eric Zimmerman (Kroll)](https://www.kroll.com/en/services/cyber-risk/investigate-and-respond/kroll-artifact-parser-extractor-kape) - Live artifact collection at speed.
2. [Velociraptor](https://docs.velociraptor.app/) - Open-source hunting/IR platform; rapidly replacing GRR.
3. [GRR Rapid Response](https://github.com/google/grr) - Google's remote forensics (less active).
4. [osquery](https://osquery.io/)
5. [Fleet / Kolide](https://fleetdm.com/) - osquery at enterprise scale.
6. [CyLR](https://github.com/orlikoski/CyLR) - Fast live-response collector.
7. [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector)

### Disk / image forensics
8. [Autopsy / The Sleuth Kit](https://www.autopsy.com/)
9. [FTK / FTK Imager by Exterro](https://www.exterro.com/ftk-imager)
10. [EnCase Forensic (OpenText)](https://www.opentext.com/products/encase-forensic)
11. [X-Ways Forensics](https://www.x-ways.net/) - Beloved by many practitioners.
12. [Magnet AXIOM](https://www.magnetforensics.com/products/magnet-axiom/)
13. [Plaso / log2timeline](https://plaso.readthedocs.io/) - Super-timeline creation.
14. [Timesketch](https://timesketch.org/) - Collaborative timeline analysis (Google).
15. [Eric Zimmerman's Tools](https://ericzimmerman.github.io/) - MFTECmd, RECmd, EvtxECmd, PECmd, JLECmd, SBECmd; free and indispensable for Windows.

### Memory forensics
16. [Volatility 3](https://www.volatilityfoundation.org/)
17. [Rekall (archived)](https://github.com/google/rekall)
18. [MemProcFS](https://github.com/ufrisk/MemProcFS)
19. [WinPmem / DumpIt / Magnet RAM Capture](https://github.com/Velocidex/WinPmem)

### Network / PCAP
20. [Wireshark / tshark](https://www.wireshark.org/)
21. [NetworkMiner](https://www.netresec.com/?page=NetworkMiner)
22. [Arkime](https://arkime.com/) - Full PCAP indexing.
23. [Zeek](https://zeek.org/) for metadata-based analysis.
24. [Brim / Zui](https://www.brimdata.io/) - Desktop log / PCAP explorer.

### Malware-adjacent DFIR
25. [YARA](https://virustotal.github.io/yara/) - Rule engine.
26. [Loki / THOR Lite by Nextron](https://github.com/Neo23x0/Loki) - IOC scanner.
27. [Chainsaw by WithSecure](https://github.com/WithSecureLabs/chainsaw) - Fast EVTX hunting with Sigma rules.
28. [Hayabusa by Yamato Security](https://github.com/Yamato-Security/hayabusa) - EVTX timeline generation.
29. [EVTXtract](https://github.com/williballenthin/EVTXtract)

### Cloud / SaaS / email forensics
30. [AWS IR tooling: aws_ir, Prowler, CloudTrail Lake, Amazon Detective](https://github.com/ThreatResponse/aws_ir)
31. [Azure: Invictus-IR cloud IR toolkit, Microsoft Incident Response Toolkit](https://github.com/invictus-ir/Microsoft-Extractor-Suite)
32. [GCP IR guide / Chronicle](https://cloud.google.com/architecture/framework/security/incident-response)
33. [SOF-ELK](https://github.com/philhagen/sof-elk) - SANS ELK VM preloaded with parsers.

### Timeline / analysis
34. [Aurora Incident Response workflow](https://github.com/cyb3rfox/Aurora-Incident-Response)
35. [TheHive + Cortex](https://strangebee.com/)
36. [DFIR-IRIS](https://dfir-iris.github.io/)

## Certifications
1. [GCFE - GIAC Certified Forensic Examiner (SANS FOR500)](https://www.giac.org/certifications/certified-forensic-examiner-gcfe/)
2. [GCFA - GIAC Certified Forensic Analyst (SANS FOR508)](https://www.giac.org/certifications/certified-forensic-analyst-gcfa/)
3. [GNFA - GIAC Network Forensic Analyst](https://www.giac.org/certifications/network-forensic-analyst-gnfa/)
4. [GCIH - GIAC Certified Incident Handler](https://www.giac.org/certifications/certified-incident-handler-gcih/)
5. [GCTI - GIAC Cyber Threat Intelligence](https://www.giac.org/certifications/cyber-threat-intelligence-gcti/)
6. [GREM - GIAC Reverse Engineering Malware](https://www.giac.org/certifications/reverse-engineering-malware-grem/) - Overlap with malware RE.
7. [EnCE - EnCase Certified Examiner](https://www.opentext.com/products/encase-certified-examiner)
8. [CCE - Certified Computer Examiner (ISFCE)](https://www.isfce.com/)
9. [CHFI by EC-Council](https://www.eccouncil.org/programs/computer-hacking-forensic-investigator-chfi/)
10. [CCFE / CMFE by IACIS](https://www.iacis.com/)
11. [Magnet Certified Forensic Examiner (MCFE)](https://www.magnetforensics.com/training/certifications/)

## Blogs/Articles
1. [The DFIR Report](https://thedfirreport.com/) - Public intrusion reports with IOCs, Sigma, timelines.
2. [SANS DFIR blog](https://www.sans.org/blog/?focus-area=digital-forensics)
3. [Didier Stevens blog](https://blog.didierstevens.com/) - Toolsmith for malicious PDFs/Office/scripts.
4. [Hexacorn](http://www.hexacorn.com/blog/) - Windows internals and persistence research.
5. [Harlan Carvey - Windows IR](https://windowsir.blogspot.com/)
6. [Mary Ellen Kennel - DFIR](https://www.whatsthishere.com/)
7. [Invictus Incident Response blog - cloud IR](https://www.invictus-ir.com/news)
8. [Brett Shavers - DFIR.training](https://dfir.training/)
9. [13Cubed blog](https://www.13cubed.com/blog)
10. [Microsoft Incident Response blog](https://www.microsoft.com/en-us/security/blog/topic/incident-response/)
11. [CrowdStrike IR blog](https://www.crowdstrike.com/blog/category/from-the-front-lines/)
12. [Mandiant / Google Cloud Threat Intelligence](https://www.mandiant.com/resources/blog)
13. [Unit 42 (Palo Alto Networks)](https://unit42.paloaltonetworks.com/)
14. [CISA Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
15. [Awesome-Incident-Response GitHub](https://github.com/meirwah/awesome-incident-response)
16. [Awesome Forensics GitHub](https://github.com/cugu/awesome-forensics)
17. [IR Playbooks by CISA, Microsoft, AWS, Google](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)
18. [NIST SP 800-61r3 (Apr 2025)](https://csrc.nist.gov/pubs/sp/800/61/r3/final) - Updated IR guide aligned to CSF 2.0; supersedes r2 (2012).
