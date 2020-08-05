# awesome-blockchain
A curated list of awesome blockchain resources. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


### Contents

- [Bitcoin — Prior Art](#prebitcoin)
  - [Computer Science](#cspapers)
    - [Reflections on Trusting Trust](https://news.ycombinator.com/item?id=13569275)
  - [Smart Contracts](https://en.wikipedia.org/wiki/Smart_contract)
    - [Szabo](http://szabo.best.vwh.net/smart.contracts.html)
    - [Miller](http://erights.org/smart-contracts/index.html)
  - [Distributed Systems](https://dl.acm.org/citation.cfm?id=1202502)
    - [Logical Time](https://en.wikipedia.org/wiki/Lamport_timestamps#Lamport.27s_logical_clock_in_distributed_systems)
    - [CAP Theorem](https://en.wikipedia.org/wiki/CAP_theorem)
    - [Byzantine Generals](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance#Byzantine_Generals.27_Problem)
    - [PBFT](http://pmg.csail.mit.edu/papers/osdi99.pdf)    
    - [State Machine Replication](https://en.wikipedia.org/wiki/State_machine_replication)
  - [Game Theory](https://en.wikipedia.org/wiki/Game_theory)
    - [Nash Equilibria](https://en.wikipedia.org/wiki/Nash_equilibrium)
    - [Prisoner's Dilemma](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma)
    - [Schelling](https://en.wikipedia.org/wiki/Focal_point_(game_theory))
  - [Financial Cryptography](https://en.wikipedia.org/wiki/Financial_cryptography)
    - [FC in 7 Layers]( http://iang.org/papers/fc7.html)
  - [Database Technology](#databases)
    - [Immutability](http://www.odbms.org/2015/10/the-rise-of-immutable-data-stores/)
    - [Distributed Databases](https://en.wikipedia.org/wiki/Distributed_database)
  - [Peer-to-Peer Systems](#peer-to-peer)
    - [BitTorrent](#bittorrent)
  - [Electronic Cash](#ecash)
    - [Chaum](#chaum)
    - [NSA Mints](https://groups.csail.mit.edu/mac/classes/6.805/articles/money/nsamint/nsamint.htm)
    - [Dai](https://en.bitcoin.it/wiki/Wei_Dai)
    - [Hashcash](https://en.wikipedia.org/wiki/Hashcash)
    - [Double-Spending](http://www.investopedia.com/terms/d/doublespending.asp)
   - [Miner Games](#consensusgames)
    - [Negotiated Arbitrage](#ml)
- [Bitcoin](#bitcoin)
  - [Paper](#paper)
  - [People](#bitcoin-people)
    - [Satoshi Nakamoto](#satoshi)
    - [Hal Finney](#finney)
  - [Awesome Bitcoin](https://github.com/igorbarinov/awesome-bitcoin)
- [Blockchain: Building Blocks](#blockchain-basics)
  - [Public-Key Cryptography](#public-key-cryptography)
  - [Hashing](#hashing)
  - [Merkle trees](#merkle-trees)
  - [DHTs](#dht)
  - [Consensus Protocols](#consensus-protocols)
    - [Proof of Work](#PoW)
    - [Proof of Stake](#PoS)
    - [Social Consensus](#social-consensus)
    - [BFT](#bft)
- [Debates](#debates)
  - [Scaling](#scaling-debate)
  - [Incentive Engineering](#incentive-engineering)
  - [Trust Assumptions](#trust-assumptions)
  - [Private vs. Public](#private-public)
- [Blockchain: Schools of Thought](#blockchain-schools-of-thought)
  - [Money (De)nationalization](#de-nationalization)
  - [Cypherpunks](#cypherpunks)
  - [Bitcoin Maximalism](#maximalism)
  - [Blockchain Utilitarianism](#utilitarianism)
  - [Cryptoeconomics](#cryptoeconomics)
    - [Mock Fungibility](#tokenship)
      #tokenship
    - [Non-Fungibility](#tokenship)
    - [Full Fungibility](#tokenship)
    - [Partial Fungibility](#tokenship)
  - [Enterprise Perspectives](#enterprises)
  - [Turing-completness](#turing)
  - [Functional Programming](#fp)
  - [Formal Methods](#formal)
- [Philosophy](#philosophy)
  - [Virtual Worlds](#virtual)
  - [MPN negotiations](https://link.springer.com/article/10.1007/BF00999251) and [SPJ-style contracts](https://www.cs.tufts.edu/~nr/cs257/archive/simon-peyton-jones/contracts.pdf)
  - [Multi-Fungibility](#ffff)
- [Sci-Fi](#sci-fi)
- [Non-Bitcoin Blockchains](#current)
  - [Active](#active-systems)
    - [Ethereum](#ethereum)
    - [Zerocash](#zcash)
    - [Awesome IPFS](https://github.com/ipfs/awesome-ipfs)
    - [Others](http://coincap.io/)
  - [Proposed](#proposed)
    - [Algorand](#algorand)
- [Interest Groups](#interest-groups)
  - [Consortia](#consortia)
    - [R3](#r3)
    - [Hyperledger](#hypeledger)
    - [EEA](#eea)
    - [Project Bletchley](#project-bletchley)
  - [Academia](#academia)
    - [IC3](#ic3)
    - [DCI](#dci)
- [Media](#media)
    - [Online Publications](#online-publications)
    - [Podcasts](#podcasts)
    - [Mainstream](#mainstream-media)
      - [Economist](http://www.economist.com/printedition/2015-10-31)
- [Notable Cases](#major-events)
  - [BitLicense](#bitlicense)
  - [The DAO Hack](#dao-hack)
- [Books](#books)
  - [The Age of Cryptocurrency](#ageofcrypto)
- [Conferences](#conferences)
- [Fundamental Challenges](#challenges)
  - [Privacy](#privacy)
  - [Transparency](#transparency)
  - [Scalability](#privacy)
  - [Regulation](#regulation)
  - [Identity](#identity)
    #cryptophiloogy
- [Major Players](#players)
  - [Governments](#gov)
  - [Banks](#banks)
  - [Tech Giants](#corp)
    - [Microsoft](#microsoft)
    - [IBM](#ibm)
  - [Consultancies](#consultancies)
  - [Startups](#startups)
  - [VCs](#vc)
  - [Individuals](#individuals)
- [Convergence](#convergence)
  - [Cloud](#cloud)
  - [IoT](#iot)
  - [AI](#ai)
- [Good Reads](#good-reads)
  - [Semantics](#semantics)
    - [Is Git a Blockchain?](https://www.reddit.com/r/Bitcoin/comments/33s8x0/is_git_a_block_chain_domus_tower_says_yes/)
    - [My Sofa is a Sidechain](http://www.ic.unicamp.br/~stolfi/EXPORT/projects/bitcoin/posts/2015-06-10-my-sofa-is-a-sidechain/main.html)
    - [What is “Blockchain” anyway?](https://coincenter.org/entry/what-is-blockchain-anyway)
  - [Visionary Articles](#visionary)
    - [Programmable Blockchains in Context](https://media.consensys.net/programmable-blockchains-in-context-ethereum-s-future-cd8451eb421e)
- [The Future](#future)
  - [(Fully) Homomorphic Encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)
  - [Secure Multiparty Computation](#smpc)
  - [Physical Unclonable Function](https://en.wikipedia.org/wiki/Physical_unclonable_function)
  - [Zero-Knowledge Proofs](https://en.wikipedia.org/wiki/Zero-knowledge_proof)
  - [ASIC Resistant Blockchains](https://bitcoin.stackexchange.com/questions/29975/what-does-it-mean-for-a-cryptocurrency-to-be-asic-resistant)
  - [Quantum-Resistance](https://www.wired.co.uk/article/quantum-computers-quantum-security-encryption)
  - [On Future-Proof Design](https://www.youtube.com/watch?v=soUG72j7kB0)
----
- [Privacy](#privacy)
  - [Zkopru (zk optimistic rollup) for private transactions](https://ethresear.ch/t/zkopru-zk-optimistic-rollup-for-private-transactions/7717)

- [Crypto-Law](#cryptolaw)
  - [Conceptualizing Cryptolaw](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2914103)
  - [Intro to Kojève](https://www.jstor.org/stable/20131192?newaccount=true&read-now=1&socuuid=c2445e81-7bf0-4fd8-b63b-5cb721530c93&socplat=email#page_scan_tab_contents)

- [Token Engineering](#tokenengineering)
  - [#tokenship](https://gitter.im/or-humanity-token/community#)
  - [TBA](https://ethereum.org/en/)

- [Crypto-Economics](#cryptoeconomics)
  - [Blockchain Governance Bibliography](https://medium.com/cryptolawreview/blockchain-governance-bibliography-360efc52d3f9 )
  - [Kojève at the Bank -ravachol70 gist](https://gist.github.com/ravachol70/a974892e196aa209acad0600340f6e02)

- [Crypto-Philology](#cryptophilology)
  - [Passwords: Philology, Security, Authentication](http://bitfragment.net/files/authentication.pdf)
  - [Ethereum state tree format change using an overlay](https://medium.com/@gballet/ethereum-state-tree-format-change-using-an-overlay-e0862d1bf201)
  - [Blockchains as Kripke Models:an Analysis of Atomic Cross-Chain Swap](https://yoichihirai.com/isola-paper.pdf)
  - [“Foundations” of Philosophical Hermeneutics: Truth and Method](https://iep.utm.edu/gadamer/)

