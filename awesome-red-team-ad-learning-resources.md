# Awesome Red Team & Active Directory Attack Learning Resources

Red teaming is goal-oriented, adversary-simulation offensive security: stealthier and longer than a pentest, with tradecraft that mirrors real threat actors. On Windows enterprise networks, this almost always means attacking Active Directory (AD), Entra ID (Azure AD), ADCS, and the surrounding identity infrastructure.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [Red Team / AD Tools](#red-team--ad-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [The Hacker Playbook 3 by Peter Kim](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901759)
2. [Red Team Development and Operations by Joe Vest, James Tubberville](https://www.amazon.com/Red-Team-Development-Operations-Practical/dp/B0845Y1TYL)
3. [Operator Handbook: Red + Blue + OSINT by Joshua Picolet](https://www.amazon.com/Operator-Handbook-Red-OSINT-Reference/dp/B08RRDTNDV)
4. [Adversarial Tradecraft in Cybersecurity by Dan Borges (Packt)](https://www.packtpub.com/product/adversarial-tradecraft-in-cybersecurity/9781801076203)
5. [Hands-On Red Team Tactics by Himanshu Sharma, Harpreet Singh (Packt)](https://www.packtpub.com/product/hands-on-red-team-tactics/9781788995238)
6. [Professional Red Teaming by Jacob G. Oakley](https://link.springer.com/book/10.1007/978-1-4842-4309-1)
7. [Pentesting Active Directory and Windows-based Infrastructure by Denis Isakov (Packt, 2023)](https://www.packtpub.com/product/pentesting-active-directory-and-windows-based-infrastructure/9781804611364)
8. [Windows Internals (7th Ed, Parts 1 & 2) by Pavel Yosifovich, Mark Russinovich et al.](https://www.microsoftpressstore.com/store/windows-internals-part-1-9780735684188)
9. [RTFM: Red Team Field Manual v2](https://www.amazon.com/RTFM-Red-Team-Field-Manual/dp/B0BTH8YK37)

## Videos
1. [SpecterOps webinars and talks](https://www.youtube.com/@SpecterOps)
2. [Black Hat / DEF CON Red Team tracks](https://www.youtube.com/@BlackHatOfficialYT)
3. [Sektor7 videos](https://www.youtube.com/@SEKTOR7net)
4. [Raphael Mudge - original Cobalt Strike / Aggressor talks](https://www.youtube.com/@rsmudge)
5. [ippsec - AD-heavy HackTheBox walkthroughs](https://www.youtube.com/@ippsec)
6. [BC Security channel - Empire / Starkiller](https://www.youtube.com/@bcsecurity1011)
7. [x33fcon talks](https://www.youtube.com/@x33fcon)
8. [OffensiveCon](https://www.youtube.com/@offensivecon)
9. [The Many Hats Club](https://www.youtube.com/@themanyhatsclub)
10. [TrustedSec webinars](https://www.youtube.com/@trustedsec)

## Free/Paid Courses
### Free
1. [HackTheBox Academy - Active Directory Enumeration & Attacks module](https://academy.hackthebox.com/module/details/143)
2. [TryHackMe - Red Teaming, Attacking and Defending AD paths](https://tryhackme.com/paths)
3. [PayloadsAllTheThings - AD section](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Methodology%20and%20Resources)
4. [HackTricks - AD methodology](https://book.hacktricks.xyz/windows-hardening/active-directory-methodology)
5. [Sektor7 free mini-courses](https://institute.sektor7.net/) (many paid, some free intros)
6. [ired.team wiki by Mantvydas Baranauskas](https://www.ired.team/) - Extensive free offensive tradecraft notes.
7. [ADsecurity.org by Sean Metcalf](https://adsecurity.org/) - Foundational AD attack/defense reference.
8. [Offensive Lateral Movement notes (0xcsandker, harmj0y)](https://blog.harmj0y.net/)

### Paid
9. [Zero Point Security - Red Team Ops (CRTO I & II)](https://training.zeropointsecurity.co.uk/) - Widely considered the best modern entry.
10. [Altered Security - CRTP, CRTE, CRTM, CARTP, CARTE, ARTE](https://www.alteredsecurity.com/) - Focused AD/Azure attack courses by Nikhil Mittal.
11. [SpecterOps - Red Team Ops I / II, Adversary Tactics: Identity-Driven Offensive Tradecraft](https://specterops.io/training/)
12. [Sektor7 - Malware Development Essentials, Intermediate & Advanced](https://institute.sektor7.net/)
13. [MalDev Academy](https://maldevacademy.com/) - Modern Windows malware development.
14. [OffSec PEN-300 (OSEP)](https://www.offsec.com/courses/pen-300/) - Evasion-focused.
15. [OffSec PEN-200 (OSCP)](https://www.offsec.com/courses/pen-200/) - Includes significant AD content since 2023.
16. [SANS SEC565: Red Team Operations and Adversary Emulation](https://www.sans.org/cyber-security-courses/red-team-operations-and-adversary-emulation/)
17. [SANS SEC699: Purple Team Tactics & Kill Chain Defenses](https://www.sans.org/cyber-security-courses/purple-team-tactics-kill-chain-defenses-adversary-emulation/)
18. [TCM Security - Practical Ethical Hacking & Windows Privilege Escalation](https://academy.tcm-sec.com/)
19. [Rasta Mouse's Labs](https://rastamouse.me/) - Rastalabs / Offshore / Dante style.

## Free/Paid Labs
1. [HackTheBox - Pro Labs: Dante, Offshore, RastaLabs, Cybernetics, APTLabs, Zephyr](https://www.hackthebox.com/hacker/pro-labs) - Multi-host AD red-team scenarios.
2. [TryHackMe - Attacktive Directory, Holo, Wreath](https://tryhackme.com/)
3. [GOAD (Game of Active Directory) by Mayfly](https://github.com/Orange-Cyberdefense/GOAD) - Free deployable vulnerable AD lab; excellent.
4. [Vulnerable AD (Sagish)](https://github.com/safebuffer/vulnerable-AD) - Scripts to make a lab vulnerable quickly.
5. [BadBlood](https://github.com/davidprowe/BadBlood) - Populate a lab AD with realistic data.
6. [DetectionLab](https://github.com/clong/DetectionLab) (archived but forked) - AD + ELK + Velociraptor.
7. [AD Attack Defense repository (infosecn1nja)](https://github.com/infosecn1nja/AD-Attack-Defense)
8. [HackTheBox Academy AD pathway](https://academy.hackthebox.com/path/preview/active-directory-mastery)
9. [PurpleCloud by Jason Ostrom](https://github.com/iknowjason/PurpleCloud) - Azure AD / hybrid attack lab.
10. [BadZure](https://github.com/mvelazc0/BadZure) - Misconfigured Entra ID tenant generator.

## Red Team / AD Tools
### C2 frameworks
1. [Cobalt Strike (commercial)](https://www.cobaltstrike.com/) - De-facto commercial C2.
2. [Sliver by Bishop Fox (open source)](https://github.com/BishopFox/sliver) - Modern Go C2; very popular.
3. [Mythic](https://github.com/its-a-feature/Mythic) - Multi-agent C2 with rich tradecraft agents.
4. [Havoc](https://github.com/HavocFramework/Havoc)
5. [Empire / Starkiller (BC Security fork)](https://github.com/BC-SECURITY/Empire) - PowerShell-era C2, still maintained.
6. [Metasploit Framework](https://www.metasploit.com/)
7. [PoshC2](https://github.com/nettitude/PoshC2)
8. [Nighthawk by MDSec (commercial, restricted)](https://www.mdsec.co.uk/nighthawk/)
9. [Brute Ratel (commercial, restricted)](https://bruteratel.com/)

### AD enumeration / attack
10. [BloodHound / BloodHound CE by SpecterOps](https://github.com/SpecterOps/BloodHound) - AD attack path visualization; indispensable.
11. [SharpHound](https://github.com/BloodHoundAD/SharpHound) / [AzureHound](https://github.com/BloodHoundAD/AzureHound)
12. [ADExplorer / ADExplorerSnapshot.py](https://github.com/c3c/ADExplorerSnapshot.py) - Silent AD snapshot alternative.
13. [PowerView / PowerSploit](https://github.com/PowerShellMafia/PowerSploit)
14. [Rubeus](https://github.com/GhostPack/Rubeus) - Kerberos abuse (Kerberoast, AS-REP, S4U).
15. [Certify / Certipy](https://github.com/ly4k/Certipy) - AD CS (ADCS) abuse (ESC1-ESC15).
16. [Impacket by Fortra](https://github.com/fortra/impacket) - Core Windows protocol toolkit.
17. [NetExec (maintained fork of CrackMapExec)](https://github.com/Pennyw0rth/NetExec)
18. [Responder / MultiRelay](https://github.com/lgandx/Responder)
19. [ntlmrelayx](https://github.com/fortra/impacket/blob/master/examples/ntlmrelayx.py) - NTLM relaying.
20. [Coercer](https://github.com/p0dalirius/Coercer) - Force authentication coercion (PrinterBug, PetitPotam, DFSCoerce).
21. [Mimikatz by Benjamin Delpy](https://github.com/gentilkiwi/mimikatz) - The legendary credential tool.
22. [Nanodump / pypykatz / DonPAPI](https://github.com/login-securite/DonPAPI) - LSASS and DPAPI tooling.
23. [ADRecon](https://github.com/adrecon/ADRecon) - Reporting-style enumeration.
24. [ADModule / ActiveDirectoryRights / PurpleKnight by Semperis (free)](https://www.semperis.com/purple-knight/)

### Entra ID / Azure
25. [ROADtools by Dirk-jan Mollema](https://github.com/dirkjanm/ROADtools)
26. [AADInternals](https://aadinternals.com/) - The Entra ID research toolkit by Dr. Nestori Syynimaa.
27. [MicroBurst by NetSPI](https://github.com/NetSPI/MicroBurst)
28. [TeamFiltration](https://github.com/Flangvik/TeamFiltration) - Enumerate/spray/backdoor Entra ID.
29. [GraphRunner](https://github.com/dafthack/GraphRunner) by Beau Bullock.
30. [Stormspotter (archived)](https://github.com/Azure/Stormspotter)

### Evasion / payload / recon
31. [ScareCrow](https://github.com/optiv/ScareCrow) - Loader generator.
32. [Donut](https://github.com/TheWover/donut) - Shellcode generator from PE/DLL/.NET.
33. [Freeze.rs](https://github.com/optiv/Freeze.rs), [Inceptor](https://github.com/klezVirus/inceptor)
34. [Havoc / Mythic profiles](https://github.com/MythicAgents) - Agent ecosystem.
35. [Sysinternals Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) - Useful to understand defender telemetry.
36. [SharpCollection](https://github.com/Flangvik/SharpCollection) - Compiled .NET offensive tools.
37. [Seatbelt](https://github.com/GhostPack/Seatbelt) - Situational awareness.
38. [SharpWMI / SharpUp / Watson / Winpeas / Linpeas](https://github.com/peass-ng/PEASS-ng)

### Adversary emulation / purple team
39. [Atomic Red Team by Red Canary](https://github.com/redcanaryco/atomic-red-team)
40. [MITRE Caldera](https://github.com/mitre/caldera)
41. [VECTR by SRA](https://vectr.io/) - Campaign tracking and purple metrics.
42. [APTSimulator by Nextron](https://github.com/NextronSystems/APTSimulator)
43. [SCYTHE (commercial)](https://www.scythe.io/)

## Certifications
1. [OSCP / OSEP / OSCE3 (OSEP + OSWE + OSED) by OffSec](https://www.offsec.com/)
2. [CRTO I & II by Zero Point Security](https://training.zeropointsecurity.co.uk/)
3. [CRTP, CRTE, CRTM, CARTP, CARTE by Altered Security](https://www.alteredsecurity.com/) - Premier AD/Azure offensive certs.
4. [HTB CRTP (Red Team Professional), CRTL (Red Team Lead)](https://academy.hackthebox.com/) - Via HTB Pro Labs.
5. [GXPN - GIAC Exploit Researcher & Advanced Penetration Tester (SANS SEC660)](https://www.giac.org/certifications/exploit-researcher-advanced-penetration-tester-gxpn/)
6. [GRTP / GPEN by SANS GIAC](https://www.giac.org/)
7. [CREST CCSAS / CCSAM / CRT](https://www.crest-approved.org/)
8. [TCM Security PNPT - Practical Network Penetration Tester](https://certifications.tcm-sec.com/pnpt/)

## Blogs/Articles
1. [SpecterOps blog](https://posts.specterops.io/) - Gold-standard AD / Entra ID attack research.
2. [harmj0y blog (Will Schroeder)](https://blog.harmj0y.net/)
3. [dirkjanm.io (Dirk-jan Mollema) - Azure AD / ADCS research](https://dirkjanm.io/)
4. [ired.team wiki](https://www.ired.team/)
5. [HackTricks Windows / AD sections](https://book.hacktricks.xyz/)
6. [ADsecurity by Sean Metcalf](https://adsecurity.org/)
7. [MDSec research](https://www.mdsec.co.uk/research/)
8. [TrustedSec blog](https://www.trustedsec.com/blog/)
9. [NetSPI blog](https://www.netspi.com/blog/)
10. [Outflank research](https://www.outflank.nl/blog/)
11. [Cymulate / SafeBreach / Scythe adversary emulation blogs](https://www.scythe.io/library)
12. [Red Team Notes by ired.team](https://www.ired.team/offensive-security/red-team-infrastructure)
13. [Certified Pre-Owned (ADCS research paper by Will Schroeder, Lee Christensen)](https://posts.specterops.io/certified-pre-owned-d95910965cd2)
14. [Awesome Red Team GitHub](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming)
15. [Awesome Active Directory Attacks](https://github.com/infosecn1nja/AD-Attack-Defense)
16. [MITRE ATT&CK - Enterprise tactics](https://attack.mitre.org/matrices/enterprise/)
17. [Raphael Mudge's "Advanced Threat Tactics" course (free VOD)](https://www.youtube.com/playlist?list=PL9HO6M_MU2nesxSmhJjEvwLhUoHPHmXvz)
