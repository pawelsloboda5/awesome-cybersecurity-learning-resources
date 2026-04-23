# Awesome Cryptography Learning Resources

Cryptography as a standalone domain: symmetric/asymmetric primitives, hashing, MACs, AEAD, digital signatures, key exchange, TLS/PKI, elliptic curves, and the 2024 NIST-standardized post-quantum algorithms (ML-KEM / ML-DSA / SLH-DSA). Focus is practical: learn enough to choose the right primitive for the job and spot dangerous misuse.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [Cryptography Tools & Libraries](#cryptography-tools--libraries)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [Serious Cryptography, 2nd Ed by Jean-Philippe Aumasson (No Starch, 2024)](https://nostarch.com/serious-cryptography-2nd-edition) - Best modern introduction.
2. [Real-World Cryptography by David Wong (Manning, 2021)](https://www.manning.com/books/real-world-cryptography) - Practitioner-focused; pairs well with Serious Cryptography.
3. [Cryptography Engineering by Niels Ferguson, Bruce Schneier, Tadayoshi Kohno](https://www.wiley.com/en-us/Cryptography+Engineering) - Design-oriented.
4. [Introduction to Modern Cryptography by Jonathan Katz, Yehuda Lindell (3rd Ed)](https://www.cs.umd.edu/~jkatz/imc.html) - Rigorous textbook.
5. [Handbook of Applied Cryptography by Menezes, van Oorschot, Vanstone (free)](https://cacr.uwaterloo.ca/hac/) - Classic reference; download full chapters free.
6. [Applied Cryptography by Bruce Schneier](https://www.schneier.com/books/applied-cryptography/) - Older but still widely cited.
7. [Crypto 101 by Laurens Van Houtven (free online)](https://www.crypto101.io/)
8. [The Joy of Cryptography by Mike Rosulek (free draft textbook)](https://joyofcryptography.com/)
9. [A Graduate Course in Applied Cryptography by Dan Boneh, Victor Shoup (free draft)](https://toc.cryptobook.us/)
10. [Post-Quantum Cryptography (multiple books; also see NIST PQC pages)](https://csrc.nist.gov/Projects/post-quantum-cryptography)

## Videos
1. [Dan Boneh - Cryptography I (Stanford on Coursera, free audit)](https://www.coursera.org/learn/crypto)
2. [Dan Boneh - Cryptography II (Coursera, free audit)](https://www.coursera.org/learn/crypto2)
3. [Computerphile Cryptography playlist](https://www.youtube.com/@Computerphile)
4. [Christof Paar - Introduction to Cryptography (24-lecture YouTube series)](https://www.youtube.com/playlist?list=PL2LPNS7VT3ZQeOgvFdHtXxH_2JRZlNB7Z)
5. [Real World Crypto symposium archives](https://rwc.iacr.org/)
6. [Cryptography research talks at USENIX / CRYPTO / CHES](https://www.iacr.org/)
7. [JP Aumasson talks](https://www.youtube.com/results?search_query=jp+aumasson)

## Free/Paid Courses
### Free
1. [Cryptopals Crypto Challenges (free, gold-standard)](https://cryptopals.com/) - If you only do one thing: do these.
2. [Dan Boneh - Cryptography I (Coursera, free audit)](https://www.coursera.org/learn/crypto)
3. [Crypto 101 online textbook + exercises](https://www.crypto101.io/)
4. [MIT 6.875 - Foundations of Cryptography (OCW materials)](https://ocw.mit.edu/)
5. [Paul Rosler / TU Berlin - Applied Cryptography lectures (YouTube)](https://www.youtube.com/)
6. [CryptoHack (free gamified challenges)](https://cryptohack.org/) - Highly recommended after Cryptopals.
7. [Cryptozombies (blockchain-flavored Solidity crypto learning, free)](https://cryptozombies.io/)

### Paid
8. [Stanford Cryptography I & II on Coursera (certificate path)](https://www.coursera.org/learn/crypto)
9. [SANS SEC401 (Cryptography module)](https://www.sans.org/cyber-security-courses/security-essentials-network-endpoint-cloud/)
10. [(ISC)2 SSCP / CISSP cryptography domain review courses](https://www.isc2.org/)

## Free/Paid Labs
1. [Cryptopals](https://cryptopals.com/) - 66+ challenges, free.
2. [CryptoHack](https://cryptohack.org/) - Modern CTF-style crypto; active community.
3. [MysteryTwister C3 (MTC3)](https://www.mysterytwisterc3.org/) - Historical to modern crypto challenges.
4. [id0-rsa](https://id0-rsa.pub/) - Classic RSA / number theory puzzles.
5. [CryptoPals Set 8 (unofficial extension - elliptic curves)](https://toadstyle.org/cryptopals/)
6. [PicoCTF crypto challenges](https://picoctf.org/)
7. [CTFtime crypto categories](https://ctftime.org/)
8. [Hack The Box - Crypto challenges](https://www.hackthebox.com/)

## Cryptography Tools & Libraries
### Libraries (use these, don't roll your own)
1. [libsodium](https://doc.libsodium.org/) - Modern, safe-by-default. Preferred in most cases.
2. [Python cryptography (pyca/cryptography)](https://cryptography.io/) - Replaces deprecated PyCrypto.
3. [PyNaCl](https://pynacl.readthedocs.io/) - libsodium bindings.
4. [Tink by Google](https://developers.google.com/tink) - Multi-language, misuse-resistant.
5. [Monocypher](https://monocypher.org/) - Small, embeddable.
6. [BoringSSL](https://boringssl.googlesource.com/boringssl/), [OpenSSL 3.x](https://www.openssl.org/), [WolfSSL](https://www.wolfssl.com/) - TLS/crypto stacks.
7. [Ring (Rust)](https://github.com/briansmith/ring) / [RustCrypto](https://github.com/RustCrypto)
8. [Bouncy Castle (Java / .NET)](https://www.bouncycastle.org/)
9. [liboqs - Open Quantum Safe (PQC)](https://github.com/open-quantum-safe/liboqs)

### Analysis / testing
10. [CyberChef](https://gchq.github.io/CyberChef/) - "The cyber swiss-army knife" for encoding/crypto.
11. [testssl.sh](https://testssl.sh/) - TLS configuration scanner.
12. [sslyze](https://github.com/nabla-c0d3/sslyze)
13. [Qualys SSL Labs server test](https://www.ssllabs.com/ssltest/)
14. [tlsfuzzer](https://github.com/tlsfuzzer/tlsfuzzer)
15. [hashcat](https://hashcat.net/) / [John the Ripper](https://www.openwall.com/john/) - Hash cracking.
16. [RsaCtfTool](https://github.com/RsaCtfTool/RsaCtfTool) - RSA attacks.
17. [SageMath](https://www.sagemath.org/) - Computer algebra system (essential for CTF crypto).
18. [Z3 SMT solver](https://github.com/Z3Prover/z3) - Symbolic reasoning for crypto puzzles.

### Key / PKI / TLS
19. [step-ca / mkcert / Smallstep](https://smallstep.com/docs/step-ca)
20. [HashiCorp Vault PKI](https://developer.hashicorp.com/vault/docs/secrets/pki)
21. [Let's Encrypt / ACME clients (certbot, acme.sh)](https://letsencrypt.org/)
22. [HSM / PKCS#11 (SoftHSMv2 for labs)](https://www.opendnssec.org/softhsm/)

## Certifications
Cryptography doesn't have a single dominant cert, but these are the most recognized:
1. [EC-Council Certified Encryption Specialist (ECES)](https://www.eccouncil.org/programs/certified-encryption-specialist-eces/)
2. [(ISC)2 SSCP / CISSP / CCSP (cryptography domains are significant)](https://www.isc2.org/)
3. [SANS GIAC GCPN / GCWN (cryptography-adjacent)](https://www.giac.org/)
4. [CompTIA Security+ / CASP+ (cover fundamentals)](https://www.comptia.org/)
5. Academic cryptography tracks (MSc/PhD) are the main path for research-level crypto careers.

## Blogs/Articles
1. [A Few Thoughts on Cryptographic Engineering - Matthew Green](https://blog.cryptographyengineering.com/) - Essential reading.
2. [Schneier on Security](https://www.schneier.com/)
3. [Cryptography Stack Exchange](https://crypto.stackexchange.com/)
4. [Filippo Valsorda's blog](https://blog.filippo.io/) - Practical crypto and Go/Age.
5. [Trail of Bits cryptography research](https://blog.trailofbits.com/category/cryptography/)
6. [NCC Group Cryptography Services](https://research.nccgroup.com/category/cryptography/)
7. [IETF CFRG drafts and RFCs](https://datatracker.ietf.org/rg/cfrg/)
8. [NIST SP 800-57 Key Management, SP 800-131A Transitioning Algorithms](https://csrc.nist.gov/publications)
9. [NIST Post-Quantum Cryptography project and FIPS 203/204/205](https://csrc.nist.gov/projects/post-quantum-cryptography)
10. [Cloudflare Research blog](https://blog.cloudflare.com/tag/research/)
11. [Latacora's "Cryptographic Right Answers"](https://www.latacora.com/blog/2018/04/03/cryptographic-right-answers/) - Short, opinionated, widely shared.
12. [RFC 8446 (TLS 1.3)](https://datatracker.ietf.org/doc/html/rfc8446), [RFC 9147 (DTLS 1.3)](https://datatracker.ietf.org/doc/html/rfc9147), [RFC 8032 (EdDSA)](https://datatracker.ietf.org/doc/html/rfc8032), [RFC 8439 (ChaCha20-Poly1305)](https://datatracker.ietf.org/doc/html/rfc8439)
13. [OWASP Cryptographic Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html)
14. [OWASP Key Management Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Key_Management_Cheat_Sheet.html)
15. [Awesome Cryptography GitHub](https://github.com/sobolevn/awesome-cryptography)
16. [Awesome Crypto Papers GitHub](https://github.com/pFarb/awesome-crypto-papers)
17. [Post-Quantum crypto summary by Cloudflare / Google migration blog posts](https://blog.cloudflare.com/post-quantum-for-all/)
