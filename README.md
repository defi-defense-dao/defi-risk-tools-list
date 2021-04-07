# DeFi Risk Tools List
A list of the available tools, projects, and protocols for analyzing and managing risk within DeFI.

Creation of this list was spurred by folks at [ArmorFi](https://armor.fi/) and [ConsenSys](https://consensys.net/) who saw a need for better sharing of tools, standards, and development patterns to encourage the safe and continued growth of the DeFi ecosystem.

Note that these resources are focused on technical, centralization, and liquidity risk of DeFi protocols, **NOT Price risk of tokens.**

## Contributions are welcome!
Feel free to submit a pull request, with anything from small fixes to translations to tools you'd like to add (or remove!). If adding a new tool, **please add a brief description** that you think new developers would understand.
* Projects that do not have a working product can only be added to the *Coming Soon* section.
* Projects that are deprecated or no longer maintained will be removed.
* Projects that are paid/restricted services without open source code or developer reviews will be further vetted.

## The Basics of DeFi Risk
Building on the work of awesome projects like DeFi Score, Nexus Mutual, Aave's Safety Modules, and others, we believe that large technical vulnerabilities are the biggest risk to a thriving DeFi community over the next few years. Smart contracts that contain large amounts of value face the following risks:

Smart Contract Risk - Technical bugs that can expose funds to hackers
Centralization Risk - Centralized admin keys are stolen or used nefariously, or oracles are manipulated to allow an exploit
Financial Risk - Collateral falls below outstanding obligations, likely due to price movement, or low liquidity leads to locked funds

## Risk Ratings
* [DeFi Score](https://defiscore.io/) - A 1-10 grade on the smart contract, centralization, and financial risk of lending protocols
* [Economic Safety Grade from DeFi Pulse & Gauntlet](https://defipulse.com/blog/introducing-the-defi-pulse-economic-safety-grade/) - A 1 to 100 grade to quantify and compare the economic risks of using on-chain protocols
* [DeFi Safety](https://defisafety.com/) - A 1-100 rating of smart contract quality and safety for DeFi apps
* [Certik Security Scores](https://www.certik.org/) - A 1-100 score across on-chain monitoring, social sentiment, governance changes, and market volatility

## Hack Incident Reporting
* [Rekt News](https://www.rekt.news/) - Anonymous platform for whistleblowers and DeFi detectives to present their information to the community
* [Blockchain Threat Intelligence](https://blockthreat.substack.com/) - Newsletter covering the latest security news, tools, events, vulnerabilities, and threats in the cryptocurrency landscape
* [Blockchain Graveyard](https://magoo.github.io/Blockchain-Graveyard/) - A list of all massive security breaches or thefts involving blockchains.

## Risk Management Projects & Protocols
* [Nexus Mutual](https://nexusmutual.io/)
* [ArmorFi](https://armor.fi/)
* [Certik Foundation](https://shield.certik.foundation/)
* [Cover Protocol](https://www.coverprotocol.com/)
* [Unslashed Finance](https://unslashed.finance)
* [Nayms](https://nayms.io/)
* [Risk Harbor](https://www.riskharbor.com/)
* [3F Mutual / Hakka Finance](https://3fmutual.com/)
* [Bridge Mutual](https://www.bridgemutual.io)
* [Atomica](https://atomica.org/)
* [UNION](https://www.unn.finance)
* [NSure](https://nsure.network/#/)
* [Opium Network](https://opium.finance/)

## Coming Soon
* [Cozy.finance](https://cozy.finance/)
* [Tidal Finance](https://tidal.finance/)
* [Protekt Protocol](https://www.protektprotocol.com/)
* [Umbrella Protocol](https://medium.com/yam-finance/introducing-the-umbrella-protocol-by-yam-e89109548c6d)
* [Shield Finance](https://shieldfinance.net/)

## Developer Tools
* Technical Risks
  * [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - A checklist of common findings, and issues to watch out for when auditing a contract for a mainnet launch.
* [MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
* [Mythril](https://github.com/ConsenSys/mythril) - Open-source EVM bytecode security analysis tool
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
* [SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Slither](https://github.com/crytic/slither) - A Solidity static analysis framework
* [Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
* [solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network
* [Piet](https://piet.slock.it) - A visual Solidity architecture analyzer

## Risk and Security Resources
* [Gemini's Cryptopedia](https://www.gemini.com/cryptopedia/explore#security) - Accessible encyclopedia on crypto security topics
* [Paradigm's CFT](https://ctf.paradigm.xyz/) - Challenges to learn common smart contract failures
* [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) - Challenges to understand common DeFi vulnerabilities
* [ImmuneFi](https://immunefi.com/) - Bug bounties on smart contract vulnerabilities

## Further Work (To be discussed)
* Hack Event Registry - The Hack Event Registry is an accessible resource for learning about past DeFi vulnerabilities/exploits and helping prevent them in the future. The goal is to support the DeFi ecosystem by documenting and learning from all past hacks/technical bugs/exploits. With better historical information and learning, risk will be priced more fairly and accurately.
* Bug Bounties on Gitcoin 

