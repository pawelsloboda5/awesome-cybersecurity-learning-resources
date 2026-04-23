# Awesome Blockchain / Smart Contract Security Learning Resources

Blockchain security covers Web3 / smart-contract auditing (mostly Ethereum EVM and Solidity, plus Vyper, Move, Cairo, Solana Rust), protocol-level attacks (consensus, MEV, bridges), wallet and key-management security, and cryptographic primitives (zero-knowledge, threshold signatures). Smart-contract auditing is one of the highest-paying specializations in security as of 2024-2026.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs & CTFs](#freepaid-labs--ctfs)
5. [Blockchain Security Tools](#blockchain-security-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [Mastering Ethereum by Andreas M. Antonopoulos, Gavin Wood (free on GitHub)](https://github.com/ethereumbook/ethereumbook)
2. [Mastering Bitcoin by Andreas M. Antonopoulos (3rd Ed, free)](https://github.com/bitcoinbook/bitcoinbook)
3. [Hands-On Smart Contract Development with Solidity and Ethereum by Kevin Solorio et al. (O'Reilly)](https://www.oreilly.com/library/view/hands-on-smart-contract/9781492045250/)
4. [Solidity Documentation (free, always-current)](https://docs.soliditylang.org/)
5. [Ethereum Smart Contract Security Best Practices by ConsenSys (free)](https://consensys.github.io/smart-contract-best-practices/)
6. [The Blockchain Developer by Elad Elrom (Apress)](https://link.springer.com/book/10.1007/978-1-4842-4847-8)
7. [Foundation Handbook of ZK by ZK Hack community (free)](https://zkhack.dev/)

## Videos
1. [Smart Contract Programmer](https://www.youtube.com/@smartcontractprogrammer)
2. [Patrick Collins - Full Foundry / Solidity course (free, 30+ hours)](https://www.youtube.com/@PatrickAlphaC)
3. [Owen (officer_cia) / Web3 security streams](https://www.youtube.com/results?search_query=owen+web3+security)
4. [Secureum Bootcamp videos](https://www.youtube.com/@TheSecureum)
5. [DeFi Security Summit talks](https://defisecuritysummit.org/)
6. [ETH Security Community calls](https://www.youtube.com/@ETHSecurityCommunity)
7. [Trail of Bits YouTube](https://www.youtube.com/@trailofbits)
8. [Immunefi Whitehat Interviews](https://www.youtube.com/@Immunefi)

## Free/Paid Courses
### Free
1. [Cyfrin Updraft (free, Solidity + security, by Patrick Collins)](https://updraft.cyfrin.io/) - Highly recommended starter.
2. [Secureum Bootcamp (RACE / A-MAZE-X) archives](https://www.secureum.xyz/)
3. [SpeedRunEthereum](https://speedrunethereum.com/) - Solidity-focused hands-on.
4. [Solidity by Example](https://solidity-by-example.org/)
5. [ConsenSys Academy free content](https://consensys.io/academy)
6. [CryptoZombies](https://cryptozombies.io/) - Solidity basics, gamified.
7. [Chainshot / Alchemy University](https://university.alchemy.com/)
8. [Rareskills GitHub learning materials](https://github.com/rareskills)
9. [Foundry Book (free, by Paradigm)](https://book.getfoundry.sh/)

### Paid
10. [Cyfrin Updraft Security & Auditing track (paid certificates)](https://updraft.cyfrin.io/)
11. [Extropy - Blockchain Security Training](https://extropy.io/)
12. [Rareskills bootcamps](https://www.rareskills.io/)
13. [ZK Hack courses and workshops](https://zkhack.dev/)
14. [Solana Cookbook / Solana Foundation training](https://solanacookbook.com/)
15. [Web3 certifications by ConsenSys / INE (emerging)](https://consensys.io/academy)

## Free/Paid Labs & CTFs
1. [Ethernaut by OpenZeppelin](https://ethernaut.openzeppelin.com/) - Classic Solidity CTF.
2. [Damn Vulnerable DeFi (Foundry edition)](https://www.damnvulnerabledefi.xyz/) - Industry-standard DeFi challenges.
3. [Capture The Ether (archived but still available)](https://capturetheether.com/)
4. [Paradigm CTF archives](https://github.com/paradigmxyz/paradigm-ctf-2023)
5. [Secureum RACE and A-MAZE-X archives](https://github.com/secureum)
6. [QuillCTF by QuillAudits](https://www.quillctf.com/)
7. [Cipher School / Cipher Shastra](https://ciphershastra.com/)
8. [Node Guardians](https://nodeguardians.io/)
9. [Solana CTF by Neodyme](https://github.com/neodyme-labs/solana-poc-framework)
10. [ZK CTFs (ZK Hack Puzzles, 0xPARC)](https://zkhack.dev/puzzles/)
11. [More Damn Vulnerable Protocols (Bridges, AMMs) - search by community](https://github.com/topics/solidity-ctf)

## Blockchain Security Tools
### Static / dynamic analysis (Solidity / EVM)
1. [Slither by Trail of Bits](https://github.com/crytic/slither) - The de-facto Solidity static analyzer.
2. [Mythril by ConsenSys](https://github.com/ConsenSys/mythril) - Symbolic execution for EVM.
3. [Echidna by Trail of Bits](https://github.com/crytic/echidna) - Property-based fuzzer.
4. [Medusa by Trail of Bits](https://github.com/crytic/medusa) - Go-based smart-contract fuzzer.
5. [Manticore by Trail of Bits](https://github.com/trailofbits/manticore) - Binary / smart-contract symbolic execution.
6. [Foundry (forge test + invariant testing)](https://book.getfoundry.sh/forge/invariant-testing)
7. [Hardhat + smock + hardhat-chai-matchers](https://hardhat.org/)
8. [Scribble by ConsenSys](https://github.com/ConsenSys/scribble) - Spec annotation + runtime checks.
9. [solhint / solium](https://github.com/protofire/solhint) - Linting.
10. [Halmos by a16z](https://github.com/a16z/halmos) - Symbolic testing for Foundry.

### Formal verification
11. [Certora Prover](https://www.certora.com/)
12. [K framework / KEVM](https://github.com/runtimeverification/evm-semantics)
13. [Runtime Verification](https://runtimeverification.com/)
14. [SMTChecker (built into Solidity compiler)](https://docs.soliditylang.org/en/latest/smtchecker.html)

### Monitoring / defense
15. [OpenZeppelin Defender](https://www.openzeppelin.com/defender) - Secure operations platform.
16. [Forta Network](https://forta.org/) - Decentralized monitoring and detection bots.
17. [Tenderly](https://tenderly.co/) - Transaction simulation + monitoring.
18. [Blockaid / GoPlus Security](https://www.blockaid.io/) - Wallet-layer threat detection.
19. [Hexagate / Hypernative](https://www.hypernative.io/) - Real-time risk detection.
20. [Chainalysis](https://www.chainalysis.com/) / [TRM Labs](https://www.trmlabs.com/) - On-chain investigations and compliance.

### Wallet / key security
21. [Safe (Gnosis Safe)](https://safe.global/) - Multi-sig standard.
22. [Fireblocks](https://www.fireblocks.com/) / [Qredo](https://www.qredo.com/) - MPC wallets.
23. [Ledger / Trezor hardware wallets](https://www.ledger.com/)
24. [Web3-signer, Frame, Rabby](https://rabby.io/)

### Dev / testing frameworks
25. [Foundry (Forge, Cast, Anvil, Chisel)](https://book.getfoundry.sh/)
26. [Hardhat](https://hardhat.org/)
27. [Brownie (Python, now Ape)](https://apeworx.io/)
28. [Remix IDE](https://remix.ethereum.org/)

### Non-EVM chains
29. [Cargo-audit, Sealevel / Solana security tools by Neodyme, OtterSec](https://github.com/otter-sec)
30. [Move Prover (Aptos/Sui)](https://aptos.dev/move/prover/move-prover)

## Certifications
1. [Blockchain Council - Certified Smart Contract Auditor (CSCA)](https://www.blockchain-council.org/certifications/certified-smart-contract-auditor/)
2. [Cyfrin Updraft - Security Researcher badge](https://updraft.cyfrin.io/)
3. [Secureum Bootcamp - top-ranked RACE finishers gain recognition instead of formal certs](https://www.secureum.xyz/)
4. [EC-Council Certified Blockchain Professional (CBP)](https://www.eccouncil.org/programs/certified-blockchain-professional-cbp/)
5. [ConsenSys Academy Developer / Auditor tracks](https://consensys.io/academy)
6. [(ISC)2 / ISACA are piloting emerging Web3 modules; check availability](https://www.isc2.org/)

Note: The industry largely values bug-bounty track record, published audit reports, and CTF rankings (Code4rena, Sherlock, Secureum) far more than certifications.

## Blogs/Articles
1. [Ethereum Foundation security blog](https://blog.ethereum.org/category/security)
2. [Trail of Bits blog (blockchain category)](https://blog.trailofbits.com/category/blockchain/)
3. [OpenZeppelin blog](https://blog.openzeppelin.com/)
4. [ConsenSys Diligence blog + best practices](https://consensys.github.io/smart-contract-best-practices/)
5. [Rekt.news](https://rekt.news/) - DeFi exploit post-mortems.
6. [DeFiLlama - Hacks page](https://defillama.com/hacks)
7. [samczsun blog](https://samczsun.com/)
8. [paradigm.xyz research](https://www.paradigm.xyz/writing)
9. [a16z crypto research](https://a16zcrypto.com/posts/)
10. [Immunefi Medium / whitehat reports](https://medium.com/immunefi)
11. [Code4rena reports and findings](https://code4rena.com/reports)
12. [Sherlock audits / protocols](https://www.sherlock.xyz/)
13. [Spearbit portfolio reports](https://spearbit.com/)
14. [OtterSec (Solana audits)](https://osec.io/)
15. [ZK Hack and 0xPARC research](https://0xparc.org/)
16. [Awesome Ethereum Security GitHub](https://github.com/crytic/awesome-ethereum-security)
17. [SWC Registry - Smart Contract Weakness Classification](https://swcregistry.io/) (archived but still referenced)
18. [DASP Top 10 - Decentralized Application Security Project](https://dasp.co/)
19. [OWASP Smart Contract Top 10](https://owasp.org/www-project-smart-contract-top-10/)
