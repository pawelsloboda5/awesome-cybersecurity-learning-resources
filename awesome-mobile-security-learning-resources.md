# Awesome Mobile Security Learning Resources
![](images/awesome-mobile-security-learning-resources.png)

Mobile security is an intersection of AppSec, reverse engineering, platform-specific knowledge (Android/iOS) and network/transport security. The current authoritative standards are the OWASP MASVS (Mobile Application Security Verification Standard) and the OWASP MASTG (Mobile Application Security Testing Guide), which replaced the older MSTG in 2023.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [Security Tools](#security-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [OWASP MASTG - Mobile Application Security Testing Guide (free)](https://mas.owasp.org/MASTG/) - The de-facto reference, replaces MSTG.
2. [OWASP MASVS - Mobile AppSec Verification Standard (free)](https://mas.owasp.org/MASVS/) - Requirement standard paired with MASTG.
3. [The Mobile Application Hacker's Handbook by Dominic Chell et al.](https://www.wiley.com/en-us/The+Mobile+Application+Hacker%27s+Handbook-p-9781118958506) - Classic, slightly dated but concepts are evergreen.
4. [Android Security Internals by Nikolay Elenkov (No Starch)](https://nostarch.com/androidsecurity) - Deep internals, still highly regarded.
5. [iOS Application Security by David Thiel (No Starch)](https://nostarch.com/iossecurity) - Focused on iOS AppSec.
6. [Android Hacker's Handbook by Joshua J. Drake et al.](https://www.wiley.com/en-us/Android+Hacker%27s+Handbook-p-9781118608647) - Lower-level Android exploitation.
7. [Hacking iOS Applications by Corellium / contributors](https://www.corellium.com/) - Vendor-led but good technical content.

## Videos
1. [OWASP MAS Project videos](https://www.youtube.com/@owasp/search?query=mobile)
2. [Android App Reverse Engineering 101 by Maddie Stone](https://maddiestone.github.io/AndroidAppRE/)
3. [iOS pentesting with Frida - playlist](https://www.youtube.com/results?search_query=frida+ios+pentesting)
4. [Mobile Hacking - Hextree.io by LiveOverflow / Fabian Faessler](https://hextree.io/) - Excellent modern Android RE content.
5. [DEF CON / Black Hat mobile security archives](https://www.youtube.com/results?search_query=defcon+android+ios+security)
6. [OffensiveCon - Android & iOS internals](https://www.youtube.com/@offensivecon)

## Free/Paid Courses
1. [OWASP MAS training materials (free)](https://mas.owasp.org/)
2. [Android App Reverse Engineering 101 (free) by Maddie Stone](https://maddiestone.github.io/AndroidAppRE/)
3. [Hextree.io - Android Hacking courses](https://hextree.io/courses) - High-quality, recently refreshed.
4. [8ksec - Mobile Security Bootcamps](https://academy.8ksec.io/) - Paid, practical Android/iOS.
5. [SANS SEC575: iOS and Android Application Security](https://www.sans.org/cyber-security-courses/ios-android-application-security-analysis-penetration-testing/) - Paid, industry standard.
6. [INE - Mobile Application Security and Penetration Testing](https://ine.com/learning/paths/mobile-application-security-and-penetration-testing)
7. [TCM Security - Mobile Application Penetration Testing](https://academy.tcm-sec.com/p/mobile-application-penetration-testing)
8. [Practical DevSecOps - Certified Mobile Security Expert](https://www.practical-devsecops.com/) - (if available in their catalog).

## Free/Paid Labs
1. [OWASP MASTG Crackmes / UnCrackable apps](https://mas.owasp.org/crackmes/) - Free Android/iOS crackmes aligned to MASTG.
2. [InsecureShop (vulnerable Android app)](https://github.com/hax0rgb/InsecureShop)
3. [DIVA (Damn Insecure and Vulnerable App)](https://github.com/payatu/diva-android) - Classic Android training app.
4. [InjuredAndroid by B3nac](https://github.com/B3nac/InjuredAndroid)
5. [Allsafe by t0thkr1s](https://github.com/t0thkr1s/allsafe) - Modern intentionally vulnerable Android app.
6. [DVIA-v2 (Damn Vulnerable iOS App)](https://github.com/prateek147/DVIA-v2) - Primary iOS training target.
7. [iGoat-Swift](https://github.com/OWASP/iGoat-Swift) - OWASP iOS goat project.
8. [HackTheBox - Mobile challenges](https://www.hackthebox.com/)
9. [Root-Me - Mobile challenges](https://www.root-me.org/?page=recherche&lang=en&recherche=mobile)
10. [pwnable.kr / pwnable.xyz - Android/ARM challenges](https://pwnable.kr/)

## Security Tools
### Static analysis
1. [MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - The all-in-one OSS analyzer for APK/IPA.
2. [jadx](https://github.com/skylot/jadx) - Decompile DEX to Java source.
3. [apktool](https://github.com/iBotPeaches/Apktool) - Decode/rebuild APK resources.
4. [Ghidra](https://ghidra-sre.org/) - SRE for native libraries (NDK, dylib).
5. [radare2 / Cutter](https://rada.re/) - Reverse engineering framework.
6. [Hopper / IDA Pro](https://www.hopperapp.com/) - Commercial RE tools.
7. [Semgrep mobile rule packs](https://semgrep.dev/) - SAST for Android/iOS source.
8. [QARK by LinkedIn](https://github.com/linkedin/qark) - Quick Android Review Kit (note: slower development).

### Dynamic / instrumentation
9. [Frida](https://frida.re/) - Dynamic instrumentation for Android/iOS/macOS/Linux/Windows. Essential.
10. [Objection](https://github.com/sensepost/objection) - Runtime mobile exploration built on Frida.
11. [Drozer by WithSecure](https://github.com/WithSecureLabs/drozer) - Android attack surface analysis.
12. [Medusa](https://github.com/Ch0pin/medusa) - Framework of modular Frida scripts.
13. [RMS - Runtime Mobile Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security)

### Network interception
14. [Burp Suite / mitmproxy / Charles Proxy](https://portswigger.net/burp)
15. [HTTP Toolkit](https://httptoolkit.com/) - Easy mobile HTTPS interception.
16. [Proxyman](https://proxyman.io/)

### Device / emulation
17. [Android Studio AVD + rooted emulator](https://developer.android.com/studio)
18. [Genymotion](https://www.genymotion.com/)
19. [Corellium](https://www.corellium.com/) - Virtual iOS / Android devices (paid).
20. [checkra1n / palera1n](https://palera.in/) - iOS jailbreaks for testing.
21. [Magisk](https://github.com/topjohnwu/Magisk) - Android rooting & module system.

### SSL pinning / security controls bypass
22. [Frida scripts: codeshare.frida.re](https://codeshare.frida.re/)
23. [Objection `android sslpinning disable` / `ios sslpinning disable`](https://github.com/sensepost/objection)

## Certifications
1. [SANS GMOB - GIAC Mobile Device Security Analyst](https://www.giac.org/certifications/mobile-device-security-analyst-gmob/) - Industry standard.
2. [eMAPT by INE/eLearnSecurity](https://ine.com/learning/certifications/internal/elearnsecurity-mobile-application-penetration-tester-emapt) - Practical, affordable.
3. [OSMR by Offensive Security](https://www.offsec.com/courses/exp-312/) - Advanced macOS/iOS exploitation (not pure mobile but relevant).
4. [OSDA / Offensive Mobile certifications (various)](https://www.offsec.com/)
5. [8kSec's Certified Mobile Security Testing Professional](https://academy.8ksec.io/)

## Blogs/Articles
1. [OWASP MAS project home](https://mas.owasp.org/)
2. [OWASP Mobile Top 10 (2024)](https://owasp.org/www-project-mobile-top-10/)
3. [Google Project Zero research (Android, iOS)](https://googleprojectzero.blogspot.com/)
4. [Maddie Stone - in-the-wild 0-days tracker](https://googleprojectzero.github.io/0days-in-the-wild/rca.html)
5. [NCC Group research - mobile](https://research.nccgroup.com/category/mobile/)
6. [8kSec blog](https://8ksec.io/blog/)
7. [Frida CodeShare](https://codeshare.frida.re/) - Shared Frida scripts.
8. [HackTricks - Android/iOS pentesting](https://book.hacktricks.xyz/mobile-pentesting)
9. [Dana Wang / HexRays blog - iOS internals](https://blog.hexrays.com/)
10. [Android Security Bulletins](https://source.android.com/docs/security/bulletin)
11. [Apple Security Releases](https://support.apple.com/en-us/HT201222)
12. [NVISO labs blog - mobile RE](https://blog.nviso.eu/)
13. [r2frida](https://github.com/nowsecure/r2frida) - radare2 + Frida integration.
14. [NowSecure research](https://www.nowsecure.com/blog/)
