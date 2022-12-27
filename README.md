


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="576" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/029-2-1024x576.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1593" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-2-1024x576.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-2-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-2-768x432.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-2.png 1280w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<p>In this article, we will talk about all known attacks on the blockchain, as well as smart contract vulnerabilities. Blockchain isn’t really as secure as we tend to think. Though security is integrated throughout all blockchain technology, even the strongest blockchains come under attack by modern cybercriminals.</p>



<p>Blockchains can resist traditional cyber attacks quite well, but cybercriminals are coming up with new approaches specifically for hacking blockchain technology. In this article, we describe the main attack vectors against blockchain technology and take a look at the most significant blockchain attacks to date.</p>



<p>Cybercriminals have already managed to misuse blockchains to perform malicious actions.&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/465-ransomware-mechanisms-protection" target="_blank" rel="noreferrer noopener">Ransomware attacks</a>&nbsp;like&nbsp;<a href="https://en.wikipedia.org/wiki/WannaCry_ransomware_attack" target="_blank" rel="noreferrer noopener">WannaCry</a>&nbsp;and&nbsp;<a href="https://en.wikipedia.org/wiki/Petya_(malware)" target="_blank" rel="noreferrer noopener">Petya</a>&nbsp;wouldn’t have been so massive if attackers hadn’t received their rewards in cryptocurrencies. Now, it looks like hackers consider exploiting blockchain security vulnerabilities as their main source of revenue.</p>



<p>In March 2019, white hat hackers&nbsp;<a href="https://thenextweb.com/hardfork/2019/03/14/blockchain-cryptocurrency-vulnerability-bug" target="_blank" rel="noreferrer noopener">found 43 bugs</a>&nbsp;in various blockchain and cryptocurrency platforms in just 30 days. They even found vulnerabilities in such famous platforms as&nbsp;<a href="https://www.coinbase.com/" target="_blank" rel="noreferrer noopener">Coinbase</a>,&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/553-eos-smart-contract-vulnerability" target="_blank" rel="noreferrer noopener">EOS</a>, and&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/602-tezos-blockchain-smart-contract-overview" target="_blank" rel="noreferrer noopener">Tezos</a>.</p>



<p>However, weak spots are often challenging to detect, since they can be hidden in unobvious places. For instance, the&nbsp;<a href="https://cointelegraph.com/news/parity-multisig-wallet-hacked-or-how-come" target="_blank" rel="noreferrer noopener">Parity multisig wallet was hacked</a>&nbsp;by breaking a library that had a withdraw function in it. The attacker managed to initialize the library itself as a wallet and claim owner rights to it. As a result, 573 wallets were affected, $30 million worth of crypto was stolen, and another $180 million rescued by a white hat hacker group was later returned to the rightful owners.</p>


----

* Tutorial: https://youtu.be/7pqVNbcGzls
* Tutorial: https://cryptodeeptech.ru/blockchain-attack-vectors

----


<p>By attacking such huge networks as&nbsp;<a href="https://bitcoin.org/en" target="_blank" rel="noreferrer noopener">Bitcoin</a>&nbsp;and&nbsp;<a href="https://ethereum.org/en" target="_blank" rel="noreferrer noopener">Ethereum</a>, cybercriminals show that they’re clever enough to disprove the myth of blockchain security. Let’s consider the five most common blockchain attack vectors:</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="850" height="774" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-1.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1471" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-1.png 850w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-1-300x273.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-1-768x699.png 768w" sizes="(max-width: 850px) 100vw, 850px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Blockchain_network_attacks.pdf" target="_blank" rel="noreferrer noopener">Blockchain Network Attacks</a></h2>



<p>A blockchain network includes nodes that create and run transactions and provide other services. For instance, the Bitcoin network is formed by nodes that send and receive transactions and miners that add approved transactions to blocks. Cybercriminals look for network vulnerabilities and exploit them with the following types of attacks.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full is-resized"><img decoding="async" loading="lazy" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-42.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1534" width="844" height="1047" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-42.png 520w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-42-242x300.png 242w" sizes="(max-width: 844px) 100vw, 844px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/DISTRIBUTED_DENIAL_OF_SERVICE_(DDOS)_ATTACKS_DETECTION_MECHANISM.pdf" target="_blank" rel="noreferrer noopener">Distributed Denial of Service</a></h3>



<p><a href="https://cryptodeep.ru/doc/DISTRIBUTED_DENIAL_OF_SERVICE_(DDOS)_ATTACKS_DETECTION_MECHANISM.pdf">Distributed denial of service&nbsp;(DDoS) attacks</a> are hard to execute on a blockchain network, but they’re possible.</p>



<p>When attacking a blockchain network using DDoS, hackers intend to bring down a server by consuming all its processing resources with numerous requests. DDoS attackers aim to disconnect a network’s mining pools, e-wallets, crypto exchanges, and other financial services. A blockchain can also be hacked with DDoS at its application layer using DDoS botnets.</p>



<p>In 2017, Bitfinex suffered from a&nbsp;<a href="https://www.infosecurity-magazine.com/news/worlds-largest-bitcoin-exchange" target="_blank" rel="noreferrer noopener">massive DDoS attack</a>. It was especially inconvenient for the IOTA Foundation, which had launched their IOTA token on the platform the day before Bitfinex informed users about the attack. Three years later, in February 2020, Bitfinex&nbsp;<a href="https://thenextweb.com/hardfork/2020/02/28/bitfinex-cryptocurrency-okex-ddos-hacker-denial-of-service-blockchain" target="_blank" rel="noreferrer noopener">experienced another DDoS attack</a>&nbsp;just a day after the OKEx cryptocurrency exchange noticed a similar attack.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="920" height="446" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-41.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1531" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-41.png 920w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-41-300x145.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-41-768x372.png 768w" sizes="(max-width: 920px) 100vw, 920px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Bitcoin_Transaction_Malleability_and_MtGox.pdf" target="_blank" rel="noreferrer noopener">Transaction Malleability Attacks</a></h3>



<p>A transaction malleability attack is intended to trick the victim into paying twice. In the Bitcoin network, every transaction has a hash that’s a transaction ID. If attackers manage to alter a transaction’s ID, they can try to broadcast the transaction with a changed hash to the network and have it confirmed before the original transaction. If this succeeds, the sender will believe the initial transaction has failed, while the funds will still be withdrawn from the sender’s account. And if the sender repeats the transaction, the same amount will be debited twice. This hack is successful once the two transactions are confirmed by miners.</p>



<p><a href="https://www.darkreading.com/attacks-and-breaches/mt-gox-bitcoin-meltdown-what-went-wrong" target="_blank" rel="noreferrer noopener">Mt. Gox</a>, a Bitcoin exchange, went bankrupt as the result of a malleability attack in 2014. However, Bitcoin seems to have&nbsp;<a href="https://medium.com/@herman_10687/malleability-attack-why-it-matters-7b5f59fb99a4" target="_blank" rel="noreferrer noopener">solved this issue</a>&nbsp;by introducing the Segregated Witness (SegWit) process, which separates signature data from Bitcoin transactions and replaces it with a non-malleable hash commitment to each signature.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="672" height="739" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-28-1.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1430" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-28-1.png 672w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-28-1-273x300.png 273w" sizes="(max-width: 672px) 100vw, 672px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Vulnerabilities_and_Security_Breaches_in_Cryptocurrencies.pdf" target="_blank" rel="noreferrer noopener">Timejacking Attack</a></h3>



<p>Timejacking exploits a theoretical vulnerability in Bitcoin timestamp handling. During a timejacking attack, a hacker alters the network time counter of the node and forces the node to accept an alternative blockchain. This can be achieved when a malicious user adds multiple fake peers to the network with inaccurate timestamps. However, a timejacking attack can be prevented by restricting acceptance time ranges or using the node’s system time.</p>



<p>The timejacking attack is also an extension of the Sybil attack. Each node maintains a time counter which is based on the median time of its peers, and if the median time differs from the system time by a certain value, then the node reverts to the system time. An attacker can flood the network with nodes reporting inaccurate timestamps, which can cause the network to slow down or speed up, leading to a desynchronization.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="820" height="560" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-26.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1412" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-26.png 820w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-26-300x205.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-26-768x524.png 768w" sizes="(max-width: 820px) 100vw, 820px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Routing_Attacks_on_Cryptocurrencies.pdf" target="_blank" rel="noreferrer noopener">Routing Attacks on Cryptocurrencies</a></h3>



<p>A routing attack can impact both individual nodes and the whole network. The idea of this hack is to tamper with transactions before pushing them to peers. It’s nearly impossible for other nodes to detect this tampering, as the hacker divides the network into partitions that are unable to communicate with each other. Routing attacks actually consist of two separate attacks:</p>



<ol>
<li>A partition attack, which divides the network nodes into separate groups</li>



<li>A delay attack, which tampers with propagating messages and sends them to the network</li>



<li></li>
</ol>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="895" height="345" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-27.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1426" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-27.png 895w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-27-300x116.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-27-768x296.png 768w" sizes="(max-width: 895px) 100vw, 895px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Sybil_Attacks_in_Cryptocurrency_Mixers.pdf" target="_blank" rel="noreferrer noopener">Sybil Attacks in Cryptocurrency Mixers</a></h3>



<p>A&nbsp;<a href="https://en.wikipedia.org/wiki/Sybil_attack" target="_blank" rel="noreferrer noopener">Sybil attack</a>&nbsp;is arranged by assigning several identifiers to the same node. Blockchain networks have no trusted nodes, and every request is sent to a number of nodes.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="730" height="350" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/figure2-sybil-attack.webp" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1425" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/figure2-sybil-attack.webp 730w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/figure2-sybil-attack-300x144.webp 300w" sizes="(max-width: 730px) 100vw, 730px"></figure></div>


<p class="has-text-align-center"><em>Figure 1. Sybil attack</em></p>



<p>During a Sybil attack, a hacker takes control of multiple nodes in the network. Then the victim is surrounded by fake nodes that close up all their transactions. Finally, the victim becomes open to&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/578-blockchain-attack-vectors#double">double-spending attacks</a>. A Sybil attack is quite difficult to detect and prevent, but the following measures can be effective: increasing the cost of creating a new identity, requiring some type of trust for joining the network, or determining&nbsp;<a href="https://delaat.net/rp/2017-2018/p97/report.pdf" target="_blank" rel="noreferrer noopener">user power based on reputation</a>.</p>



<p>A sybil attack is defined by Wikipedia as “<em>a type of attack on a computer network service in which an attacker subverts the service’s reputation system by creating a large number of pseudonymous identities and uses them to gain a disproportionately large influence.</em>” If the network does not keep the count of the nodes, then the attacker can completely isolate the victim node from the network. The sybil attack on blockchain also works similarly, where an attacker tries to flood the network with their controlled nodes so that the victim only connects to the attacker controlled nodes. This can lead to a wide variety of damages where the attacker can prevent genuine blocks from being added to the chain, the attacker can add their own blocks to the chain, or they can cause confusion among the nodes, hampering the general functioning of the blockchain network.</p>



<p>In the above visual representation, the red nodes are controlled by the attacker, and they flood the network, making the victim connect only to a malicious node.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Sybil_Attacks_on_Identity-Augmented_Proof-of-Stake.pdf" target="_blank" rel="noreferrer noopener">Sybil Attacks on Identity-Augmented Proof-of-Stake</a></h2>



<p>IdAPoS is an identity-based consensus protocol for decentralised Blockchain networks that implements a trustless reputation system by extending Proof-of-Stake to facilitate leader selection in non-economic contexts. Like any protocol operating in a public/permissionless setting, it is vulnerable to Sybil attacks in which byzantine actors interfere with peer sampling by presenting artificially large numbers of identities. This paper demonstrates what influence these attacks have on the stability of member selection of a Blockchain system using the IdAPoS protocol and investigates how attacks can be mitigated. As a novel protocol, its vulnerability to this type of attack has not previously been researched. The research question is approached via an agent-based model of an IdAPoS system in which both honest and malicious actors are represented as agents. Simulations are run on some reasonable configurations of an IdAPoS system that employ different attack mitigation strategies. The results show that a super strategy that combines multiple individual mitigation strategies is more effective for containing Sybil attacks than the unmitigated protocol and any other individual strategies proposed. In the simulation this strategy extended the time until a system was taken over by a malicious entity approximately by a factor of 5. These positive initial results indicate that further research into the practical viability of the protocol is warranted</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="704" height="482" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-43.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1538" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-43.png 704w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-43-300x205.png 300w" sizes="(max-width: 704px) 100vw, 704px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Eclipse_Attacks_on_Bitcoin.pdf" target="_blank" rel="noreferrer noopener">Eclipse Attacks on Bitcoin</a></h3>



<p>An eclipse attack requires a hacker to control a large number of IP addresses or to have a distributed botnet. Then the attacker overwrites the addresses in the “tried” table of the victim node and waits until the victim node is restarted. After restarting, all outgoing connections of the victim node will be redirected to the IP addresses controlled by the attacker. This makes the victim unable to obtain transactions they’re interested in. Researchers from Boston University&nbsp;<a href="https://bitcoinmagazine.com/articles/researchers-explore-eclipse-attacks-ethereum-blockchain" target="_blank" rel="noreferrer noopener">initiated</a>&nbsp;an eclipse attack on the Ethereum network and managed to do it using just one or two machines.</p>



<p><a href="https://cointelegraph.com/explained/what-is-an-eclipse-attack" target="_blank" rel="noreferrer noopener">Eclipse attack</a>&nbsp;arises in the blockchains, where the architecture partitions workloads and assigns tasks among the peers. As an example, if a chain has a node that has only eight outgoing connections and can support at most 128 threads at any given moment, each node has view access to only the nodes that are connected to it. The view of the chain for the victim node can be changed if an attacker attacks a specific node and&nbsp;<a href="https://www.gemini.com/cryptopedia/eclipse-attacks-defense-bitcoin#section-how-are-cryptocurrency-eclipse-attacks-executed" target="_blank" rel="noreferrer noopener">gains control of the eight nodes</a>&nbsp;connected to it. This can lead to a wide variety of damages that include double spending of the coins by tricking a victim that a particular transaction has not occurred, and also the attacks against the second layer protocols. The attacker can make the victim believe that a payment channel is open when it is closed, tricking the victim to initiate a transaction. The following diagram demonstrates a node under Eclipse attack.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="268" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Blockchain-1-1024x268.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1432" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-1-1024x268.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-1-300x78.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-1-768x201.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-1.png 1450w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p class="has-text-align-center" id="caption-attachment-31671"><a href="https://cryptodeep.ru/doc/Eclipse_Attacks_on_Bitcoin.pdf" target="_blank" rel="noreferrer noopener">Figure : Eclipse Attack</a></p>



<p>In the above visual representation, the red nodes are controlled by the attacker, and they can change the copy of the chain of the victim node by making it connect to attacker controlled nodes.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Eclipse_Attacks_on_Ethereum.pdf" target="_blank" rel="noreferrer noopener">Eclipse Attacks on Ethereum</a></h2>



<p>In this technical report, we present three vulnerabilities affecting the Ethereum blockchain network and client. First, we outline an eclipse attack that allows an adversary to partition the peer-to-peer network without monopolizing the connections of the victim. This is attack is possible by exploiting the block propagation design of Ethereum. Second, we present an exploit to force a node to accept a longer chain with lower total difficulty than the main chain. Finally, we outline a bug in Ethereum’s difficulty calculation. We provide countermeasure proposals for each reported vulnerability.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full is-resized"><img decoding="async" loading="lazy" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-44.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1541" width="981" height="1016" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-44.png 696w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-44-290x300.png 290w" sizes="(max-width: 981px) 100vw, 981px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Long-Range_Attacks_in_Proof-of-Stake_Systems.pdf" target="_blank" rel="noreferrer noopener">Long-Range Attacks in Proof-of-Stake Systems</a></h3>



<p>Long range attacks target networks that use the&nbsp;<a href="https://en.wikipedia.org/wiki/Proof_of_stake" target="_blank" rel="noreferrer noopener">proof of stake</a>&nbsp;(PoS) consensus algorithm, in which users can mine or validate block transactions according to how many coins they hold.</p>



<p>These attacks can be categorized into three types:</p>



<ol>
<li><a href="https://blog.positive.com/rewriting-history-a-brief-introduction-to-long-range-attacks-54e473acdba9" target="_blank" rel="noreferrer noopener">Simple</a>&nbsp;— A naive implementation of the proof of stake protocol, when nodes don’t check block timestamps</li>



<li><a href="https://github.com/filecoin-project/consensus/issues/17" target="_blank" rel="noreferrer noopener">Posterior corruption</a>&nbsp;— An attempt to mint more blocks than the main chain in a given time frame</li>



<li><a href="https://eprint.iacr.org/2018/248.pdf" target="_blank" rel="noreferrer noopener">Stake bleeding</a>&nbsp;— Copying a transaction from the honestly maintained blockchain to a private blockchain maintained by the attacker
<ul>
<li></li>
</ul>
</li>
</ol>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="231" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-45-1024x231.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1544" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-45-1024x231.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-45-300x68.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-45-768x173.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-45.png 1262w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>When conducting a long-range attack, a hacker uses a purchased or stolen private key of a sizable token balance that has already been used for validating in the past. Then, the hacker can generate an alternative history of the blockchain and increase rewards based on PoS validation.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="727" height="559" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-25.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1410" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-25.png 727w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-25-300x231.png 300w" sizes="(max-width: 727px) 100vw, 727px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2>2. <a href="https://cryptodeep.ru/doc/User_Wallet_Attacks.pdf" target="_blank" rel="noreferrer noopener">User Wallet Attacks</a></h2>



<p>Actually, blockchains and cybersecurity go together like salt and pepper until people interact with them. It may sound surprising, but blockchain users pose the greatest security threat. People know about the use of&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/462-blockchain-cybersecurity-pros-cons" target="_blank" rel="noreferrer noopener">blockchain in cybersecurity</a>, and tend to overestimate the security of the blockchain and overlook its weaknesses. User wallet credentials are the main target for cybercriminals.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="574" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-46-1024x574.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1545" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-46-1024x574.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-46-300x168.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-46-768x431.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-46.png 1131w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>To obtain wallet credentials, hackers try to use both traditional methods like phishing and dictionary attacks and new sophisticated methods like finding weaknesses in cryptographic algorithms. Here’s an overview of the most common ways of attacking user wallets.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="800" height="400" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Digital-Wallet.jpg" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1435" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Digital-Wallet.jpg 800w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Digital-Wallet-300x150.jpg 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Digital-Wallet-768x384.jpg 768w" sizes="(max-width: 800px) 100vw, 800px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Phishing_Attacks.pdf" target="_blank" rel="noreferrer noopener">Phishing Attacks</a></h3>



<p>In 2018, there was an&nbsp;<a href="https://alex.studer.dev/2018/01/28/iotaseed.html" target="_blank" rel="noreferrer noopener">attack</a>&nbsp;on IOTA wallets initiated with iotaseed.io (now offline), a fake online seed generator. Hackers conducted a phishing campaign with this service and collected logs with secret seeds. As a result, in January 2018, hackers successfully stole more than $4 million worth of IOTA from victims’ wallets.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="858" height="658" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-47.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1548" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-47.png 858w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-47-300x230.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-47-768x589.png 768w" sizes="(max-width: 858px) 100vw, 858px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="889" height="566" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-22.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1403" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-22.png 889w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-22-300x191.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-22-768x489.png 768w" sizes="(max-width: 889px) 100vw, 889px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Dictionary_Attacks.pdf" target="_blank" rel="noreferrer noopener">Dictionary Attacks</a></h3>



<p>During these attacks, a hacker attempts to break a victim’s cryptographic hash and&nbsp;<a href="https://en.wikipedia.org/wiki/Salt_(cryptography)" target="_blank" rel="noreferrer noopener">salt</a>&nbsp;by trying hash values of common passwords like password1. By translating clear text passwords to cryptographic hashes, attackers can find wallet credentials.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="739" height="569" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/how-dictionary-attack-works.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1437" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/how-dictionary-attack-works.png 739w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/how-dictionary-attack-works-300x231.png 300w" sizes="(max-width: 739px) 100vw, 739px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeeptech.ru/lattice-attack/" target="_blank" rel="noreferrer noopener">Vulnerable Signatures</a></h3>



<p>Blockchain networks use various cryptographic algorithms to create user signatures, but they may also have vulnerabilities. For example, Bitcoin uses the&nbsp;<a href="https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm" target="_blank" rel="noreferrer noopener">ECDSA cryptographic algorithm</a>&nbsp;to automatically generate unique private keys. However, it appears that ECDSA has insufficient&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/535-entropy-as-a-service" target="_blank" rel="noreferrer noopener">entropy</a>, which can result in the same random value in more than one signature. IOTA also faced cryptographic problems with its old&nbsp;<a href="https://www.boazbarak.org/cs127/Projects/iota.pdf" target="_blank" rel="noreferrer noopener">Curl hash function</a>.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="455" height="154" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/signECDSA.jpg" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1439" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/signECDSA.jpg 455w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/signECDSA-300x102.jpg 300w" sizes="(max-width: 455px) 100vw, 455px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Security_Threats_Classification_in_Blockchains.pdf">Flawed Key Generation</a></h3>



<p>Exploiting vulnerabilities in key generation, the hacker known as Johoe got access to private keys provided by Blockchain.info in December 2014. The&nbsp;<a href="https://cointelegraph.com/news/ceo-nicholas-cary-around-250-btc-gone-in-blockchaininfo-security-lapse" target="_blank" rel="noreferrer noopener">attack happened</a>&nbsp;as the result of a mistake that appeared during a code update that resulted in poor randomness of inputs for generating public user keys. Though this vulnerability was quickly mitigated, the flaw is still possible with the ECDSA algorithm.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="987" height="458" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-48.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1553" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-48.png 987w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-48-300x139.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-48-768x356.png 768w" sizes="(max-width: 987px) 100vw, 987px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeeptech.ru/lattice-attack/" target="_blank" rel="noreferrer noopener">Lattice Attack</a></h2>



<blockquote class="wp-block-quote">
<p>If&nbsp; the signing&nbsp;<em><u>nonce&nbsp;</u></em><code>NONCES</code>&nbsp;&nbsp;is ever disclosed, the&nbsp;&nbsp;<em>private key</em>&nbsp;can be immediately&nbsp;&nbsp;<em><u>recovered</u></em>&nbsp;, which&nbsp;&nbsp;<strong><u>breaks our entire signature scheme</u></strong>&nbsp;.</p>
</blockquote>



<p>Also, if two nonces ever repeat, no matter what the messages are,&nbsp;&nbsp;<em>an attacker</em>&nbsp;&nbsp;can easily detect this and immediately&nbsp;&nbsp;<strong>recover the secret key</strong>&nbsp;, again breaking our whole scheme.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/lattice-attack/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="657" height="91" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-33.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1492" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-33.png 657w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-33-300x42.png 300w" sizes="(max-width: 657px) 100vw, 657px"></a><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/lattice-attack/" target="_blank" rel="noreferrer noopener"><code>https://cryptodeeptech.ru/lattice-attack/</code></a></figcaption></figure></div>


<h2>In the Bitcoin blockchain, we found a certain transaction:</h2>



<p>transaction:&nbsp;&nbsp;<a href="https://www.blockchain.com/btc/tx/08d917f0fee48b0d765006fa52d62dd3d704563200f2817046973e3bf6d11f1f" target="_blank" rel="noreferrer noopener">08d917f0fee48b0d765006fa52d62dd3d704563200f2817046973e3bf6d11f1f</a></p>



<p>for Bitcoin Addresses:&nbsp;&nbsp;<a href="https://www.blockchain.com/btc/address/15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E" target="_blank" rel="noreferrer noopener">15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E</a></p>



<blockquote class="wp-block-quote">
<p>and we managed to multiply the fake signatures and apply the lattice</p>
</blockquote>



<p>where using the&nbsp;&nbsp;<em>Python script&nbsp;</em>&nbsp;<a href="https://youtu.be/YP4Xj6gUcf4" target="_blank" rel="noreferrer noopener">algorithmLLL.py</a>&nbsp;&nbsp;with the installation of packages in&nbsp;&nbsp;<strong>GOOGLE COLAB</strong></p>



<p><strong>INSTALL &gt;&gt; SAGE + ECDSA + BITCOIN + algorithm LLL</strong></p>



<blockquote class="wp-block-quote">
<p>We managed to get&nbsp;&nbsp;<code>Private Key</code>&nbsp;to&nbsp;&nbsp;<code>Bitcoin Wallet</code>&nbsp;from one weak transaction in&nbsp;&nbsp;<code>ECDSA</code>.</p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/77737e84bb453449fd6956a39c4eb195.png" alt="Installation" title="Installation"><figcaption class="wp-element-caption">Installation</figcaption></figure>



<figure class="wp-block-image"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/ae20b37475bfff1ce38f81cc206a93f3.png" alt="Run Bash script: lattice.sh" title="Run Bash script: lattice.sh"><figcaption class="wp-element-caption">Run Bash script: lattice.sh</figcaption></figure>



<figure class="wp-block-image"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/72289e9dab54d5aa568438a94a4c90a6.png" alt="Result in HEX format Private key found!" title="Result in HEX format Private key found!"><figcaption class="wp-element-caption">Result in HEX format Private key found!</figcaption></figure>



<figure class="wp-block-image"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/46921784bb73f1218ded9e16bc0f8abd.png" alt="File: ONESIGN.txt (ECDSA Signature R, S, Z Value)" title="File: ONESIGN.txt (ECDSA Signature R, S, Z Value)"><figcaption class="wp-element-caption">File: ONESIGN.txt (ECDSA Signature R, S, Z Value)</figcaption></figure>



<figure class="wp-block-image"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/8cbe22f9cd364064a8e005ac8ea4e99e.png" alt="We propagated fake signatures for the Python script algorithmLLL.py" title="We propagated fake signatures for the Python script algorithmLLL.py"><figcaption class="wp-element-caption">We propagated fake signatures for the Python script algorithmLLL.py</figcaption></figure>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/83f750d81ba83309039189495a10680a.png" alt="File: PRIVATEKEY.txt" title="File: PRIVATEKEY.txt"><figcaption class="wp-element-caption">File: PRIVATEKEY.txt</figcaption></figure></div>

<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/2029821051232d8a95744863eaa65049.png" alt="File: ADDRESS.txt" title="File: ADDRESS.txt"><figcaption class="wp-element-caption">File: ADDRESS.txt</figcaption></figure></div>


<p><strong><a href="https://cryptodeep.ru/bitaddress.html" target="_blank" rel="noreferrer noopener">Let’s open bitaddress</a></strong>&nbsp;and&nbsp;check:</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/4ce93fdd168a7acc734929d342c8949c.png" alt="Checking the private key on the bitaddress website" title="Checking the private key on the bitaddress website"><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/lattice-attack/" target="_blank" rel="noreferrer noopener"><code>Checking the private key on the bitaddress website</code></a></figcaption></figure></div>


<p><em><u>Private key found!</u></em></p>



<p><a href="https://www.blockchain.com/btc/address/15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E">https://www.blockchain.com/btc/address/15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E</a></p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/00cbe70723846c402c4da47bcb6d47b3.png" alt="0.001 BTC" title="0.001 BTC"><figcaption class="wp-element-caption">0.001 BTC</figcaption></figure></div>


<pre class="wp-block-code"><code>ADDR: 15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E
WIF:  5JCAmNLXeSwi2SCgNH7wRL5qSQhPa7sZvj8eDwxisY5hJm8Uh92
HEX:  31AFD65CAD430D276E3360B1C762808D1D051154724B6FC15ED978FA9D06B1C1 </code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeeptech.ru/kangaroo/" target="_blank" rel="noreferrer noopener">RangeNonce</a></h2>



<p><code>«RangeNonce»</code>&nbsp;is a script to find the range of the secret key</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/kangaroo/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="885" height="143" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-37.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1504" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-37.png 885w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-37-300x48.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-37-768x124.png 768w" sizes="(max-width: 885px) 100vw, 885px"></a><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/kangaroo/" target="_blank" rel="noreferrer noopener"><code>https://cryptodeeptech.ru/kangaroo/</code></a></figcaption></figure></div>


<p>Let’s choose the version for the distribution kit&nbsp;&nbsp;<code>GNU/Linux</code>&nbsp;.&nbsp;<code>Google Colab</code>&nbsp;provides&nbsp;<code>UBUNTU 18.04</code></p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/94dd82af4d7155e548aa7241df9b3206.png" alt="RangeNonce" title="RangeNonce"><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/kangaroo/" target="_blank" rel="noreferrer noopener"><code>RangeNonce</code></a></figcaption></figure></div>


<p>Upload all files to&nbsp;<code>Google Colab</code></p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/75191d9a233987a74ed0fa016aa5e2a1.png" alt="RangeNonce + Google Colab" title="RangeNonce + Google Colab"><figcaption class="wp-element-caption">RangeNonce + Google Colab</figcaption></figure></div>


<p>Let’s allow permissions for the script and run the script&nbsp;<code>«RangeNonce»</code></p>



<p><strong>Teams:</strong></p>



<pre class="wp-block-code"><code>chmod +x RangeNonce
./RangeNonce
cat Result.txt</code></pre>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/8ff5460c3570ebbbb3c7fb0f6a394fd9.png" alt="Pollard&#39;s Kangaroo find solutions to the discrete logarithm secp256k1 PRIVATE KEY + NONCES in a known range"></figure></div>


<h4>Everything will be saved to a file: Result.txt</h4>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/2af471f7eb46f84157b402ed67ea9139.png" alt="result.txt" title="result.txt"><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/kangaroo/" target="_blank" rel="noreferrer noopener">result.txt</a></figcaption></figure></div>


<h2 class="has-text-align-center">This is the partial disclosure of bytes of information the value of “K” (NONCES)</h2>



<p><em>So our&nbsp;&nbsp;<u>secret key</u>&nbsp;&nbsp;is in&nbsp;&nbsp;<u>the range</u>&nbsp;:</em></p>



<pre class="wp-block-code"><code>K = 070239c013e8f40c8c2a0e608ae15a6b00000000000000000000000000000000
K = 070239c013e8f40c8c2a0e608ae15a6bffffffffffffffffffffffffffffffff</code></pre>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/204ef79845ae3d93a9c93d43f81e484b.png" alt="Pollard&#39;s Kangaroo find solutions to the discrete logarithm secp256k1 PRIVATE KEY + NONCES in a known range"></figure></div>


<blockquote class="wp-block-quote">
<p><strong>Pay attention</strong>&nbsp;to the initial&nbsp;&nbsp;<code>32</code>&nbsp;digits and letters&nbsp;&nbsp;<code>HEX</code>&nbsp;of the format, the value of the signature&nbsp;&nbsp;<code>Z</code>&nbsp;matches&nbsp;&nbsp;<em><u>the range of the secret key</u></em>&nbsp;&nbsp;, that is, the value&nbsp;<code>"K" (NONCES)</code></p>
</blockquote>



<h2 class="has-text-align-center">This is a very serious ECDSA signature error</h2>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeeptech.ru/frey-ruck-attack/" target="_blank" rel="noreferrer noopener">Frey-Rück Attack</a></h2>



<p>With a critical vulnerability in the Bitcoin blockchain transaction, we can solve the rather difficult discrete logarithm problem to extract the&nbsp;<code>ECDSA</code>&nbsp;<em>secret key</em><code>"K" (NONCE)</code>&nbsp;from the vulnerable signature in order to ultimately restore the Bitcoin Wallet, since knowing the secret key we can get the private key.</p>



<p>To do this, there are several algorithms from&nbsp;<a href="https://attacksafe.ru/list-of-bitcoin-attacks/" target="_blank" rel="noreferrer noopener"><strong>the list of popular attacks on Bitcoin</strong></a>&nbsp;, one of which is&nbsp;<strong><a href="https://attacksafe.ru/frey-ruck-attack-on-bitcoin/" target="_blank" rel="noreferrer noopener">“Frey-Rück Attack on Bitcoin”</a></strong>&nbsp;.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/frey-ruck-attack/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="925" height="203" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-34.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1499" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-34.png 925w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-34-300x66.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-34-768x169.png 768w" sizes="(max-width: 925px) 100vw, 925px"></a><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/frey-ruck-attack/" target="_blank" rel="noreferrer noopener"><code>https://cryptodeeptech.ru/frey-ruck-attack/</code></a></figcaption></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeeptech.ru/rowhammer-attack/" target="_blank" rel="noreferrer noopener">Rowhammer Attack</a></h2>



<p>The biggest cryptographic strength of the Bitcoin cryptocurrency is a&nbsp;<a href="https://cryptodeep.ru/doc/Computational_Discrete_Mathematics.pdf" target="_blank" rel="noreferrer noopener">computational method in discrete mathematics</a>&nbsp;that takes the problem of factorization of large integers and the problem of hidden numbers&nbsp;<code>(HNP)</code>in the Bitcoin signature transaction as a basis&nbsp;<code>ECDSA</code>.</p>



<p><code>Rowhammer Attack on Bitcoin</code>, allows us to efficiently find all zeros for normalized polynomials modulo a certain value, and we adapt this method to a signature algorithm,&nbsp;<code>ECDSA</code>more precisely, to critically vulnerable transactions in the Bitcoin blockchain.<br>We will apply multiplication by different powers of the same element of the finite field, which, oddly enough, can coincide and give us a certain function over the finite field, which can be specified using&nbsp;<a href="https://en.wikipedia.org/wiki/Lagrange_polynomial" target="_blank" rel="noreferrer noopener">the Lagrange interpolation polynomial</a>&nbsp;.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/rowhammer-attack/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="957" height="198" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-35.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1500" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-35.png 957w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-35-300x62.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-35-768x159.png 768w" sizes="(max-width: 957px) 100vw, 957px"></a><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/rowhammer-attack/" target="_blank" rel="noreferrer noopener"><code>https://cryptodeeptech.ru/rowhammer-attack/</code></a></figcaption></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeeptech.ru/whitebox-attack/" target="_blank" rel="noreferrer noopener">WhiteBox Attack</a></h2>



<p>Differential fault analysis&nbsp;<code>(DFA)</code>was briefly described in the literature in 1996 when&nbsp;<em>an Israeli cryptographer and cryptanalyst</em>&nbsp;<code>Eli Biham</code>&nbsp;and&nbsp;<em>an Israeli scientist</em>&nbsp;<code>Adi Shamir</code>&nbsp;showed that they could use error injection to extract the&nbsp;<em>secret key</em>&nbsp;and recover the&nbsp;<em>private key</em>&nbsp;using various signature and verification algorithms.</p>



<p>We implement the&nbsp;<strong><a href="https://attacksafe.ru/whitebox-attack-on-bitcoin" target="_blank" rel="noreferrer noopener">“WhiteBox Attack on Bitcoin”</a></strong>&nbsp;with the differential bugs described in this research paper.&nbsp;The classic&nbsp;<code>DFA</code>that we described in the previous&nbsp;<a href="https://cryptodeep.ru/rowhammer-attack/" target="_blank" rel="noreferrer noopener">article</a>&nbsp;is called&nbsp;<code>F()</code>.&nbsp;Some of these attacks also require two signature pairs&nbsp;<code>ECDSA</code>.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/whitebox-attack/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="962" height="195" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-36.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1503" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-36.png 962w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-36-300x61.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-36-768x156.png 768w" sizes="(max-width: 962px) 100vw, 962px"></a><figcaption class="wp-element-caption"><a href="https://cryptodeeptech.ru/whitebox-attack/" target="_blank" rel="noreferrer noopener"><code>https://cryptodeeptech.ru/whitebox-attack/</code></a></figcaption></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<p></p>



<p></p>



<p></p>



<p></p>



<h3><a href="https://cryptodeep.ru/doc/Attacking_Threshold_Wallets.pdf">Attacks on Cold Wallets</a></h3>



<p>Hardware wallets, or cold wallets, can also be hacked. For instance,&nbsp;<a href="https://thenextweb.com/hardfork/2018/02/06/cryptocurrency-wallet-ledget-hardware" target="_blank" rel="noreferrer noopener">researchers</a>&nbsp;initiated an Evil Maid attack by exploiting bugs in the Nano S Ledger wallet. As a result of this hack, researchers obtained the private keys as well as the PINs, recovery seeds, and passphrases of victims.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="815" height="374" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-49.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1554" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-49.png 815w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-49-300x138.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-49-768x352.png 768w" sizes="(max-width: 815px) 100vw, 815px"></figure></div>


<p>One of the latest cold wallet attacks happened in 2019, when the&nbsp;<a href="https://www.hackread.com/upbit-cryptocurrency-exchange-hacked-ether-stolen" target="_blank" rel="noreferrer noopener">UPbit</a>&nbsp;cryptocurrency exchange was transfering funds to a cold wallet. This is a common way to freeze crypto when you’re expecting a cyberattack. The hackers managed to steal 342,000 ETH, apparently because they knew the timing of the transaction.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="750" height="375" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-676.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1441" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-676.png 750w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-676-300x150.png 300w" sizes="(max-width: 750px) 100vw, 750px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Enhancing_Cold_Wallet_Security_with_Native_Multi-Signature_schemes_in_Centralized_Exchanges.pdf" target="_blank" rel="noreferrer noopener">Attacks on Hot Wallets</a></h3>



<p>Hot wallets are internet-connected apps for storing private cryptographic keys. Though owners of cryptocurrency exchanges claim they keep their user data in wallets disconnected from the web, a $500 million&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/561-coincheck-hack" target="_blank" rel="noreferrer noopener">attack</a>&nbsp;on Coincheck in 2018 proved this isn’t always true.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full is-resized"><img decoding="async" loading="lazy" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-50.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1556" width="778" height="769" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-50.png 602w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-50-300x297.png 300w" sizes="(max-width: 778px) 100vw, 778px"></figure></div>


<p>In June 2019, an&nbsp;<a href="https://gatehub.net/blog/gatehub-update-investigation-continues" target="_blank" rel="noreferrer noopener">attack on GateHub</a>&nbsp;resulted in unauthorized access to dozens of native&nbsp;<a href="https://en.wikipedia.org/wiki/Ripple_(payment_protocol)" target="_blank" rel="noreferrer noopener">XRP</a>&nbsp;wallets and the theft of crypto assets. Singapore-based&nbsp;<a href="https://cointelegraph.com/news/singaporean-exchange-bitrue-gets-hacked-losing-5-million-in-xrp-cardano" target="_blank" rel="noreferrer noopener">crypto exchange Bitrue</a>&nbsp;also experienced a hot wallet attack at almost the same time due to a system vulnerability. As a result, hackers managed to steal funds worth over $4.5 million in XRP and $237,500 in ADA.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="578" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-23-1024x578.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1406" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-23-1024x578.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-23-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-23-768x434.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-23.png 1188w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Smart_Contract_Vulnerability_Detection_Technique.pdf">Smart Contract Attacks</a></h2>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="977" height="684" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-51.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1560" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-51.png 977w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-51-300x210.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-51-768x538.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-51-700x490.png 700w" sizes="(max-width: 977px) 100vw, 977px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full is-resized"><img decoding="async" loading="lazy" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-52.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1561" width="663" height="262" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-52.png 500w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-52-300x119.png 300w" sizes="(max-width: 663px) 100vw, 663px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1004" height="598" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-53.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1562" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-53.png 1004w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-53-300x179.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-53-768x457.png 768w" sizes="(max-width: 1004px) 100vw, 1004px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="65" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-55-1024x65.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1564" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-55-1024x65.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-55-300x19.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-55-768x49.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-55.png 1027w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full is-resized"><img decoding="async" loading="lazy" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-56.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1565" width="1010" height="733" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-56.png 975w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-56-300x218.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-56-768x558.png 768w" sizes="(max-width: 1010px) 100vw, 1010px"></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="922" height="415" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-57.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1566" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-57.png 922w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-57-300x135.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-57-768x346.png 768w" sizes="(max-width: 922px) 100vw, 922px"></figure></div>


<p>We’ve already accumulated rich experience in analyzing and avoiding vulnerabilities in smart contracts based on the&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/562-suspicious-ethereum-transactions" target="_blank" rel="noreferrer noopener">Ethereum</a>,&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/576-eos-ram-exploit" target="_blank" rel="noreferrer noopener">EOS</a>, and&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/571-neo-nep-5-vulnerabilities" target="_blank" rel="noreferrer noopener">NEO</a>&nbsp;platforms. The main blockchain security issues associated with smart contracts relate to bugs in source code, a network’s virtual machine, the runtime environment for smart contracts, and the blockchain itself. Let’s look at each of these attack vectors.</p>



<p></p>



<p class="has-text-align-center has-medium-font-size"><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/A%20Survey" target="_blank" rel="noreferrer noopener"><strong> </strong></a><strong><a href="https://cryptodeep.ru/doc/Smart_Contract_Vulnerability_Detection_Technique.pdf" target="_blank" rel="noreferrer noopener">PDF:</a></strong><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/A%20Survey" target="_blank" rel="noreferrer noopener"> </a><em><a href="https://cryptodeep.ru/doc/Smart_Contract_Vulnerability_Detection_Technique.pdf" target="_blank" rel="noreferrer noopener">Smart Contract Vulnerability Detection Technique: A Survey</a></em></p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="747" height="722" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-29.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1443" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-29.png 747w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-29-300x290.png 300w" sizes="(max-width: 747px) 100vw, 747px"></figure></div>


<p>The Smart Contract examples used are issues that have occurred on the Ethereum blockchain. They are applicable to any platform that uses the Ethereum Virtual Machine and the concepts can be applied to any form of smart contracts. The topic will also cover known best practices to mitigate these issues.</p>



<p>The Topology attacks explore possible attack vectors on the Bitcoin network, and subsequently any networks that rely on a controlled amount of peer-peer communication for validation. The issues explored will be on two levels: Vulnerable Smart Contract codes and Topology attacks.</p>



<p>Jorden Seet’s interest in the Cybersecurity world started in 2013 when he competed in his first CTF after a 2-day penetration testing bootcamp. Ever since, he has grown a passion in cybersecurity and explored many facets of it, from Cryptography to Social Engineering.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="1024" height="514" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-39-1024x514.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1519" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-39-1024x514.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-39-300x151.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-39-768x385.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-39.png 1146w" sizes="(max-width: 1024px) 100vw, 1024px"></a><figcaption class="wp-element-caption"><a href="https://youtu.be/LInz2YaDhgQ" target="_blank" rel="noreferrer noopener"><code>https://youtu.be/LInz2YaDhgQ</code></a></figcaption></figure></div>


<p>Currently, he is working on a National Research Foundation – Tel Aviv University (NRF-TAU) granted project on using Network Topology Analytics for Cyber Attack Deterrence in SMU. He was previously with the Cyber Security Agency of Singapore’s Penetration Testing department as an intern and is currently working with BlockConnectors on Smart Contract Audit and Blockchain development.</p>



<p>In his spare time, he works on Smart Contract Hacking as well as explore potential blockchain attack vectors. He firmly believes that decentralization is a paradigm that could have real potential in revolutionizing the security industry, such as in DDoS prevention, Data integrity and IoT security.</p>



<p class="has-text-align-center"><iframe loading="lazy" width="560" height="315" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/LInz2YaDhgQ.html" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeeptech.ru/frey-ruck-attack/" target="_blank" rel="noreferrer noopener">Vulnerabilities in Contract Source Code</a></h3>



<p>If a smart contract has vulnerabilities in its source code, it poses a risk to parties that sign the contract. For instance, bugs discovered in an Ethereum contract&nbsp;<a href="https://www.technologyreview.com/2016/06/17/159556/80-million-hack-shows-the-dangers-of-programmable-money" target="_blank" rel="noreferrer noopener">cost</a>&nbsp;its owners $80 million in 2016. One of the common vulnerabilities in Solidity opens up a possibility to delegate control to untrusted functions from other smart contracts, known as a reentrancy attack. During this attack, contract A calls a function from contract B that has an undefined behavior. In turn, contract B can call a function from contract A and use it for malicious purposes.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="807" height="528" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Classification-of-vulnerabilities-in-Ethereum-smart-contracts.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1445" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Classification-of-vulnerabilities-in-Ethereum-smart-contracts.png 807w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Classification-of-vulnerabilities-in-Ethereum-smart-contracts-300x196.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Classification-of-vulnerabilities-in-Ethereum-smart-contracts-768x502.png 768w" sizes="(max-width: 807px) 100vw, 807px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeeptech.ru/rowhammer-attack/" target="_blank" rel="noreferrer noopener">Vulnerabilities in Virtual Machines</a></h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="678" height="254" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/vulnerabilities-introduced-by-virtual.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1448" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/vulnerabilities-introduced-by-virtual.png 678w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/vulnerabilities-introduced-by-virtual-300x112.png 300w" sizes="(max-width: 678px) 100vw, 678px"><figcaption class="wp-element-caption"><em>Vulnerabilities in virtual machines</em></figcaption></figure></div>


<p>The Ethereum Virtual Machine (EVM) is a distributed stack-based computer where all smart contracts of Ethereum-based blockchains are executed. The most common vulnerabilities of the EVM are the following:</p>



<ul>
<li>Immutable defects&nbsp;— Blockchain blocks are immutable by nature, which means that once a smart contract is created, it can’t be changed. But if a smart contract contains any bugs in its code, they also are impossible to fix. There’s a risk that cybercriminals can discover and exploit code vulnerabilities to steal Ether or create a new fork, as happened with the&nbsp;<a href="https://medium.com/swlh/the-story-of-the-dao-its-history-and-consequences-71e6a8a551ee" target="_blank" rel="noreferrer noopener">DAO attack</a>.</li>



<li>Cryptocurrency lost in transfer&nbsp;— This is possible if Ether is transferred to an orphaned address that doesn’t have any owner or contract.</li>



<li>Bugs in access control&nbsp;— There’s a&nbsp;<a href="https://github.com/crytic/not-so-smart-contracts/tree/master/unprotected_function" target="_blank" rel="noreferrer noopener">missed modifier</a>&nbsp;bug in Ethereum smart contracts that allows a hacker to get access to sensitive functionality in a contract.</li>



<li><a href="https://cryptodeeptech.ru/shortest-ecdsa-signature/" target="_blank" rel="noreferrer noopener">Short address attack</a>&nbsp;— This is possible because the EVM can accept incorrectly padded arguments. Hackers can exploit this vulnerability by sending specifically crafted addresses to potential victims. For instance, during a successful attack on the&nbsp;<a href="https://medium.com/crypt-bytes-tech/ico-hack-coindash-ed-dd336a4f1052" target="_blank" rel="noreferrer noopener">Coindash ICO</a>&nbsp;in 2017, a modification to the Coindash Ethereum address made victims send their Ether to the hacker’s address.</li>



<li></li>
</ul>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="570" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-24-1024x570.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1407" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-24-1024x570.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-24-300x167.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-24-768x427.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-24.png 1026w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Also, hackers can compromise smart contracts by applying other methods that are typical for compromising blockchain technology, including DDoS, eclipse, and various low-level attacks.</p>



<p>However, younger blockchains such as Cardano and Zilliqa use different virtual machines: IELE, KEVM, and others. These new blockchains claim to&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/573-contract-security-cardano-zilliqa" target="_blank" rel="noreferrer noopener">guarantee smart contract security within their protocols</a>.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Transaction_Verification_Mechanism_Attacks.pdf" target="_blank" rel="noreferrer noopener">Transaction Verification Mechanism Attacks</a></h2>



<p>Unlike financial institutions, blockchains confirm transactions only after all nodes in the network are in agreement. Until a block with a transaction is verified, the transaction is classified as unverified. However, verification takes a certain amount of time, which creates a perfect vector for cyberattacks.</p>



<p><a href="https://en.wikipedia.org/wiki/Double-spending" target="_blank" rel="noreferrer noopener">Double-spending</a>&nbsp;is a common blockchain attack exploiting the transaction verification mechanism. All transactions on a blockchain need to be verified by users in order to be recognized as valid, which takes time. Attackers can use this delay to their advantage and trick the system into using the same coins or tokens in more than one transaction.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="591" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Untitled-2-1024x591.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1417" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Untitled-2-1024x591.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Untitled-2-300x173.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Untitled-2-768x443.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Untitled-2.png 1300w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Figure 2. A double-spending attack</p>



<p>Here are the most common types of attacks based on exploiting the intermediate time between a transaction’s initiation and confirmation.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Exploring_the_Attack_Surface_of_Blockchain.pdf" target="_blank" rel="noreferrer noopener">Finney Attacks</a></h3>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1023" height="402" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-17.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1386" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-17.png 1023w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-17-300x118.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-17-768x302.png 768w" sizes="(max-width: 1023px) 100vw, 1023px"><figcaption class="wp-element-caption"><a href="https://cryptodeep.ru/doc/Exploring_the_Attack_Surface_of_Blockchain.pdf" target="_blank" rel="noreferrer noopener">https://cryptodeep.ru/doc/Exploring_the_Attack_Surface_of_Blockchain.pdf</a></figcaption></figure></div>


<p>A <a href="https://cryptodeep.ru/doc/Exploring_the_Attack_Surface_of_Blockchain.pdf" target="_blank" rel="noreferrer noopener">Finney attack</a> is possible when one transaction is premined into a block and an identical transaction is created before that premined block is released to the network, thereby invalidating the second identical transaction.</p>



<p>The Finney attack can be termed as an extension of the selfish mining attack. The attacker mines a block stealthily and sends the unconfirmed transaction to the other node, possibly to a merchant node. If the merchant node accepts the transaction, then the attacker can further add a new block to the chain in a small-time frame, reversing that transaction and inducing a double spending attack. The attack window in the case of a Finney attack is considerably small, but this can cause a lot of damage if the value of the transaction is large enough.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Security_threats_on_Blockchain_and_its_countermeasures.pdf" target="_blank" rel="noreferrer noopener">Race Attacks</a></h3>



<p>A race attack is executed when an attacker creates two conflicting transactions. The first transaction is sent to the victim, who accepts the payment (and sends a product, for instance) without waiting for confirmation of the transaction. At the same time, a conflicting transaction returning the same amount of cryptocurrency to the attacker is broadcast to the network, eventually making the first transaction invalid. </p>



<p>In a race attack, the attacker does not pre-mine the transaction but simply broadcasts two different transactions, one of them to the merchant and one of them to the network. If the attacker is successful in giving the merchant node the illusion that the transaction received by them is the first one, then they accept it, and the attacker can broadcast a completely different transaction to the entire network.</p>



<p>Besides these core blockchain level attacks, there are a number of other attacks that can happen at the application implementation level. One of the most infamous of them was the DAO attack that happened in June 2016, leading to a theft of about $70 million. The attacker contributed to the crowdfunding campaign of a company and requested a withdrawal. However, a recursive function was implemented for the withdrawal that didn’t check the settlement status of the current transaction. To&nbsp;<a href="https://en.wikipedia.org/wiki/Ethereum_Classic#The_DAO_bailout" target="_blank" rel="noreferrer noopener">recover</a>&nbsp;the money, the Ethereum chain went into a hard fork, with the old chain continuing on as Ethereum Classic. This severely damaged the reputation of the chain, and the autonomy of the chain also came into question.</p>



<p><strong>Some general measures to prevent these attacks from happening:</strong></p>



<ul>
<li>It should be ensured that there are no logical inconsistencies in the chain code and consensus algorithm.</li>



<li>The peers should be selected with sufficient complexity and caution, and the transactions should be reviewed regularly.</li>



<li>In case any suspicious activity is detected, the network should be vigilant enough to isolate the bad actor node immediately.</li>



<li>A proper review process should be deployed for the network for each new node when it joins the network.</li>



<li>Rate limiting algorithms should be present at all the relevant processes to limit the damage and prevent attacks as and when they happen.</li>



<li>2FA should be present at all the concerned authentication points, and it should be ensured that all the authentication level bugs should be fixed at the application level itself to the extent possible</li>



<li>Most of the time, the approach of blacklisting and whitelisting does not work due to scalability issues. So, a better approach should be to make the attacks costly enough to be performed and increase the complexity of the system to be resilient enough and make successful exploitation extremely difficult.</li>
</ul>



<p>Multiple other bugs and&nbsp;<a href="https://wesecureapp.com/blog/how-do-cryptocurrencies-affect-cybersecurity/" target="_blank" rel="noreferrer noopener">vulnerabilities</a>&nbsp;exist in different kinds of the blockchain networks, the most common and concerning of them being at the smart contract level, but they are a topic for another time.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="878" height="542" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-30.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1451" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-30.png 878w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-30-300x185.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-30-768x474.png 768w" sizes="(max-width: 878px) 100vw, 878px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Bitcoins_Security_Model_Revisited.pdf" target="_blank" rel="noreferrer noopener">Vector76 Attacks</a></h3>



<p>Vector76 is a combination of two previous attacks. In this&nbsp;<a href="https://www.reddit.com/r/Bitcoin/comments/2e7bfa/vector76_double_spend_attack/cjwya6x" target="_blank" rel="noreferrer noopener">case</a>, a malicious miner creates two nodes, one of which is connected only to the exchange node and the other of which is connected to well-connected peers in the blockchain network. After that, the miner creates two transactions, one high-value and one low-value. Then, the attacker premines and withholds a block with a high-value transaction from an exchange service. After a block announcement, the attacker quickly sends the premined block directly to the exchange service. It along with some miners will consider the premined block as the main chain and confirm this transaction. Thus, this attack exploits the fact that one part of the network sees the transaction the attacker has included into a block while the other part of the network doesn’t see this transaction.</p>



<p>After the exchange service confirms the high-value transaction, the attacker sends a low-value transaction to the main network, which finally rejects the high-value transaction. As a result, the attacker’s account is credited the amount of the high-value transaction. Though there’s a high chance for success with this type of attack, it’s not common because it requires a hosted e-wallet that accepts the payment after one confirmation and a node with an incoming transaction.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="942" height="292" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/vector76-attack.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1453" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/vector76-attack.png 942w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/vector76-attack-300x93.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/vector76-attack-768x238.png 768w" sizes="(max-width: 942px) 100vw, 942px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/Stake-Bleeding_Attacks_on_Proof-of-Stake_Blockchains.pdf" target="_blank" rel="noreferrer noopener">Alternative History Attacks</a></h3>



<p>An alternative history attack — also called a&nbsp;<a href="https://en.bitcoin.it/wiki/Irreversible_Transactions#Alternative_history_attack" target="_blank" rel="noreferrer noopener">blockchain reorganization attack</a>&nbsp;— may happen even in the case of multiple confirmations but requires a huge amount of computing power from the hacker. In this case, a malicious user sends a transaction to a recipient and at the same time mines an alternative fork with another transaction that returns the same coins. Even if the recipient considers the transaction valid after n confirmations and sends a product, for instance, the recipient may lose money if the attacker releases a longer chain and gets the coins back.</p>



<p>One of the latest blockchain reorganization attacks happened to&nbsp;<a href="https://www.coindesk.com/ethereum-classic-undergoes-likely-51-attack-with-3693-block-chain-reorganization" target="_blank" rel="noreferrer noopener">Ethereum Classic</a>&nbsp;in August 2020 when a miner used old software and lost access to internet access for a while when mining. A reorganization happened when two versions of the blockchain competed for validity from nodes in the network and resulted in about a&nbsp;<a href="https://hackmd.io/@cUBb4hAvQciAEPoU2yfrzQ/Skd4X6MZw" target="_blank" rel="noreferrer noopener">3000-block insertion</a>.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="850" height="774" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1456" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain.png 850w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-300x273.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Different-types-of-attacks-on-blockchain-alternative-history-attacks-blockchain-768x699.png 768w" sizes="(max-width: 850px) 100vw, 850px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/A_Rational_Protocol_Treatment_of_51%25_Attacks.pdf">51% or Majority Attacks</a></h3>



<p>A <a href="https://cryptodeep.ru/doc/A_Rational_Protocol_Treatment_of_51%25_Attacks.pdf" target="_blank" rel="noreferrer noopener">majority attack</a> is possible when a hacker gets control of 51% of the network hash rate and creates an alternative fork that finally takes precedence over existing forks. This attack was initially the only known blockchain vulnerability and seemed unrealistic in the near past. However, at least five cryptocurrencies —&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/563-verge-mining-hack" target="_blank" rel="noreferrer noopener">Verge</a>, ZenCash, Monacoin, Bitcoin Gold, and Litecoin Cash — have already suffered from 51% attacks. In each of these cases, cybercriminals collected enough hashing power to compromise the network and pocket millions of dollars.</p>



<p>The recent&nbsp;<a href="https://cointelegraph.com/news/51-attack-bleeds-more-than-5m-from-ethereum-classic" target="_blank" rel="noreferrer noopener">51% attack on Ethereum Classic</a>&nbsp;(ETC) that happened in August 2020 resulted in approximately $5.6 million worth of the ETC cryptocurrency being double-spent. Apparently, the hacker had good knowledge of the ETC protocol and managed to mine 4,280 blocks over four days until the platform noticed an attack. Just five days after the incident, ETC suffered from&nbsp;<a href="https://cointelegraph.com/news/is-etc-102-screwed-after-second-51-attack" target="_blank" rel="noreferrer noopener">a second 51% attack</a>, in which a miner conducted a 4,000-block network reorganization.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="730" height="220" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/figure3-51-percents-attack.webp" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1458" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/figure3-51-percents-attack.webp 730w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/figure3-51-percents-attack-300x90.webp 300w" sizes="(max-width: 730px) 100vw, 730px"></figure></div>


<p class="has-text-align-center"><em> <a href="https://cryptodeep.ru/doc/A_Rational_Protocol_Treatment_of_51%25_Attacks.pdf" target="_blank" rel="noreferrer noopener"><code>Majority attack</code></a></em></p>



<p>Unfortunately, all small cryptocurrencies are still at risk of majority attacks. Since these cryptocurrencies attract fewer miners, attackers can just rent computing power to gain a majority share of the network. The developers of&nbsp;<a href="https://www.crypto51.app/about.html" target="_blank" rel="noreferrer noopener">Crypto51</a>&nbsp;have tried to draw attention to the potential risks of hacking smaller cryptocurrencies. Their website shows the expected costs of a 51% attack on various blockchains.</p>



<p>Possible measures for preventing double-spending attacks include monitoring received transactions during a listening period, forwarding double-spending attempts, inserting other nodes to observe transactions, and rejecting direct incoming connections.</p>



<p>Moreover, there’s an innovative technology called the&nbsp;<a href="https://lightning.network/" target="_blank" rel="noreferrer noopener">lightning network</a>&nbsp;that’s designed to solve the problem of exploiting weaknesses in the transaction verification mechanism. This network allows users to instantly verify transactions through a network of bidirectional payment channels without delegating custody of funds. However, it’s still susceptible to DDoS attacks, one of which already&nbsp;<a href="https://www.coindesk.com/researchers-uncover-bitcoin-attack-that-could-slow-or-stop-lightning-payments" target="_blank" rel="noreferrer noopener">happened in March 2018</a>.</p>



<p>51% attack happens when a particular miner or a set of miners gain more than 50% of the processing power of the entire blockchain network, which helps them gain a majority in regard to the consensus algorithm. This attack vector is primarily related to the Proof of Work algorithm, but it can be extended as a test case to other consensus algorithms also, where there is a risk of a single party gaining enough influence in the network to unduly modify the state of the chain. This can lead to multiple damages including rewriting the chain data, adding new blocks, and double spending. The following diagram shows how this attack happens.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="372" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-16-1024x372.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1379" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-16-1024x372.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-16-300x109.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-16-768x279.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-16.png 1186w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>In the above visual representation, the red nodes are controlled by the attacker, and they can change the copy of the chain by adding new blocks post gaining majority consensus.</p>



<p>Some of the major chains that have suffered a 51% attack are the Bitcoin Gold Blockchain (in May 2018, 388,000 BTG worth around $18 million were stolen from multiple exchanges), Bitcoin Satoshi’s Vision (in August 2021, they suffered a 51% attack after which the coin suffered a 5% loss in value) and the Ethereum Classic blockchain.&nbsp;Rented Hash Power&nbsp;can also lead to 51% attacks. In this method, the attackers can rent computing power on servers to calculate hashes faster than other participants and gain consensus. Mining pools are also an interesting party in this, since they too can sometimes exceed the consensus requirements. In July 2014, the mining pool ghash.io gained more than 50% processing power for a brief period, after which it committed to reducing its power voluntarily.</p>



<p>The culprits behind the recent 51% attacks on Ethereum Classic used rented mining hash power to carry off their heists, exploiting a vulnerability common to cryptocurrencies that rely on “<a href="http://forkast.news/proof-of-work-what-is-it-bitcoin-halving/">proof of work</a>” as their underlying technology.&nbsp;</p>



<p>Rented mining hash power is at the center of all three attacks on ETC last month, which resulted in millions of dollars in losses and delivered a significant blow to the reputation of PoW protocols previously believed to be&nbsp;<a href="https://www.technologyreview.com/2019/02/19/239592/once-hailed-as-unhackable-blockchains-are-now-getting-hacked/" rel="noreferrer noopener" target="_blank">immutable and “unhackable</a>.”&nbsp;</p>



<p>“It’s actually a huge vulnerability in the system,” said Terry Culver, CEO of ETC Labs, an incubator of projects on Ethereum Classic, in an<a href="https://forkast.news/ethereum-classic-repeat-hacks-etc-labs-ceo-terry-culver-ben-sauter/">&nbsp;interview with<em>&nbsp;Forkast.News</em></a>.&nbsp;</p>



<p>“Three attacks in one month will tell you that security is an issue on Ethereum Classic. And we believe and know that other blockchains get attacked more regularly, maybe with less visibility,” Culver said. “It’s a universal problem.”</p>



<p>The cryptocurrency space has been trying to weed out criminals and tighten up security, including the implementation of “<a href="https://forkast.news/could-fatf-travel-rule-make-cryptos-mainstream/">know your customer” and anti-money laundering (KYC/AML) procedures</a>,&nbsp;<a href="https://forkast.news/us-regulators-cftc-occ-sec-fatf-cryptocurrency-rules-trend/">increased regulations</a>&nbsp;from governments, and enhanced security systems to stave off hacking.</p>



<p>But despite these efforts, malicious actors continue to exploit a core feature of many blockchain systems — decentralization and the requirement that there must be a 51% consensus of the protocol’s nodes to control the network.&nbsp;</p>



<p>“The [cryptocurrency] system is maturing, but the hash rental market is actually growing,” Culver said. “Think of it like, you turn the light on, and where do the mice go? [Malicious actors have] left the exchanges for the most part, and they’ve moved into the hash rental market.”</p>



<p>Proponents of PoW systems would say that the 51% requirement needed to gain consensus would make it very hard to hack large blockchain protocols like Bitcoin and Ethereum. But there is still a theoretical possibility if someone or a group manages to gain 51% control over those networks. The risks of a 51% attack increases for smaller cryptocurrencies that don’t have as many nodes, as it would be relatively easier to take over the network of a smaller network while still turning a profit.</p>



<p>For example, it would take over&nbsp;<a href="https://www.crypto51.app/" rel="noreferrer noopener" target="_blank">US$513,000 to perform a 51% attack</a>&nbsp;(at the time of this publication) for one hour on Bitcoin, but only about US$3,800 for a similar attack on Ethereum Classic, which is why the smaller network may be much easier and more profitable for malicious actors to attack.</p>



<p>“The hash rental market is like under a rock somewhere, it’s totally anonymous,” Culver said. “They’re basically money laundering operations. So you could take your BTC from ill-gotten gains, rent hash power, and get out freshly-minted tokens with no provenance.”</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="965" height="633" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/hincehash.webp" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1460" title="Rented hash power for 51% attacks is a ‘huge vulnerability’ for proof-of-work blockchains, says ETC Labs CEO 2" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/hincehash.webp 965w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hincehash-300x197.webp 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/hincehash-768x504.webp 768w" sizes="(max-width: 965px) 100vw, 965px"><figcaption class="wp-element-caption"><em>The cost of launching a 51% attack on various top cryptocurrencies through NiceHash. Image:&nbsp;</em><a href="https://www.crypto51.app/" rel="noreferrer noopener" target="_blank"><em>Crypto51</em></a></figcaption></figure></div>


<h4><strong>What does renting hashpower do?</strong></h4>



<p>How did they do it? The malicious actors behind the first two attacks on ETC in August were able to achieve 51% dominance over the network by renting hash power from NiceHash provider&nbsp;<a href="https://www.nicehash.com/algorithm/daggerhashimoto" rel="noreferrer noopener" target="_blank">daggerhashimoto</a>, based on an&nbsp;<a href="https://blog.bitquery.io/attacker-stole-807k-etc-in-ethereum-classic-51-attack" rel="noreferrer noopener" target="_blank">analysis&nbsp;</a>by Bitquery, a data intelligence firm.</p>



<p>Slovenia-based NiceHash is an online platform where customers can rent hashing power from sellers providing the computing power to mine cryptocurrencies.&nbsp;</p>



<p>By using this rented hash power, the attackers behind the&nbsp;<a href="https://forkast.news/bitcoin-hong-kong-china-dcep-testing-ethereum-classic-51-attack-current-forkast-25/">first and second attacks</a>&nbsp;on Ethereum Classic were able to “double spend” over US$7 million by overwriting entries in the blockchain, reversing or even changing the destination of transactions. In other words, the attackers had almost complete control over the network and were able to route money as they pleased.</p>



<p>NiceHash has previously been embroiled in controversy. In 2019, its former chief technology officer and co-founder Matjaz Skorjanec was&nbsp;<a href="https://www.coindesk.com/former-nicehash-cto-arrested-in-germany-over-us-hacking-charges" rel="noreferrer noopener" target="_blank">arrested</a>&nbsp;in Germany over U.S. charges of being involved in a hacking group that organized the theft of millions of dollars.&nbsp;</p>



<p>NiceHash itself was&nbsp;<a href="https://www.coindesk.com/nicehash-ceo-confirms-bitcoin-theft-worth-78-million" rel="noreferrer noopener" target="_blank">hacked&nbsp;</a>in 2017, resulting in the loss of an estimated US$78 million in bitcoin.</p>



<p>The August hacks were not the first time Ethereum Classic suffered from such breaches, as a&nbsp;<a href="https://decrypt.co/4408/cryptocurrencies-protect-51-attacks" rel="noreferrer noopener" target="_blank">similar 51% attack occurred against ETC in January 2019</a>. Hackers have also&nbsp;<a href="https://www.vice.com/en_us/article/a3a38e/what-is-a-51-percent-attack-silicon-valley-bitcoin-gold-verge-monacoin-cryptocurrency" rel="noreferrer noopener" target="_blank">launched successful 51% attacks</a>&nbsp;on a number of other smaller cryptocurrencies, including Bitcoin Gold, Verge and Monacoin in 2018.</p>



<p>“Computers are getting better, it’s going to keep getting easier and easier to get control of the computer power necessary to do these things,” said Benjamin J. A. Sauter, partner at New York-based international law firm Kobre &amp; Kim, which is representing ETC Labs in investigating and suing the hackers.&nbsp;</p>



<p>Moreover, the concentration of hashing power in China has also been shown to be a risk for cryptocurrencies, as&nbsp;<a href="https://forkast.news/yfi-bitcoin-consensys-jpmorgan-quorum-blockchain-omg-network-tether-transfers-current-forkast-27/">recent flooding</a>&nbsp;in the country’s Sichuan province destroyed thousands of crypto miners. Sichuan province, which is known for its cheap hydropower, has been a popular location for cryptocurrency mining farms looking to save money, but the floods and landslides caused a distinct drop of BTC hashrate in Chinese mining pools.</p>



<p>In a&nbsp;<a href="https://www.nicehash.com/blog/post/official-response-regarding-the-latest-51-attack-allegations" rel="noreferrer noopener" target="_blank">statement</a>&nbsp;addressing the recent attacks and allegations from ETC Labs, NiceHash says that it “does not support or enable 51% attacks” but also concedes that its hash power “might be abused by the attacker’s pool.”</p>



<p>NiceHash says it takes steps to prevent or help prevent market disruptions and manipulations, and cooperates with law enforcement conducting investigations on activities which break their terms of service and privacy policy.</p>



<p><em>Forkast.News</em>&nbsp;has reached out to NiceHash for additional comment, but has not received a response as of the time of writing.&nbsp;</p>



<h4><strong>Self regulation vs government intervention?</strong></h4>



<p>Despite the hacks and the numerous monetary losses, the crypto community have largely said they prefer to pursue malicious actors privately instead of bringing in greater government regulation and scrutiny.&nbsp;</p>



<p>As a result of the attacks on Ethereum Classic, ETC Labs has&nbsp;<a href="https://medium.com/ethereum-classic-labs/etc-network-security-plan-fed70402b727" rel="noreferrer noopener" target="_blank">announced</a>&nbsp;that they are developing a strategic plan to protect the integrity of the ETC ecosystem. The plan includes cooperating with miners to maintain a consistent hash rate on the network, advanced monitoring to identify anomalies or spikes in the hashrate, and eventually changing the PoW mining algorithm.</p>



<p>“By and large, I think the space doesn’t want the government to become deeply involved in how the exchanges operate and try to remedy wrongs,” Sauter said. “I think the industry as a whole wants to be able to self-regulate and have an environment where the government doesn’t need to be in the weeds. But as long as there’s not an effective private resolution, it’s how problems are going to be solved.”</p>



<blockquote class="wp-block-quote">
<p>This is a thought-provoking observation. 🤔<br><br>By definition, a decentralized cryptocurrency must be susceptible to 51% attacks whether by hashrate, stake, and/or other permissionlessly-acquirable resources.<br><br>If a crypto can’t be 51% attacked, it is permissioned and centralized.&nbsp;<a href="https://t.co/LRCVj5F0O1" rel="noreferrer noopener" target="_blank">https://t.co/LRCVj5F0O1</a>— Charlie Lee [LTC⚡] (@SatoshiLite)&nbsp;<a href="https://twitter.com/SatoshiLite/status/1082491687169998848?ref_src=twsrc%5Etfw" rel="noreferrer noopener" target="_blank">January 8, 2019</a></p>
</blockquote>



<p>The cryptocurrency industry has seen increasing government interest, stricter rules and moves toward regulations in recent times, including the U.S.’ Financial Action Task Force’s&nbsp;<a href="https://forkast.news/could-fatf-travel-rule-make-cryptos-mainstream/">guidelines</a>&nbsp;for virtual asset service providers like exchanges to include the personal information of people transacting over US$1,000.&nbsp;</p>



<p>Another U.S. agency, the Commodity Futures Trading Commission (CFTC) also&nbsp;<a href="https://forkast.news/us-regulators-cftc-occ-sec-fatf-cryptocurrency-rules-trend/">announced a strategic plan</a>&nbsp;to regulate cryptocurrencies by 2024. The U.S. Security and Exchange Commission (SEC) may also be on track to shift its views on how it determines cryptocurrencies to be securities, according to SEC commissioner Hester Peirce.&nbsp;</p>



<p>“Capital markets can transform people’s lives, and so allowing the financial system to reach more people means that we have to really revisit some regulatory features that are in place now,” Peirce said in an&nbsp;<a href="https://forkast.news/us-regulators-cftc-occ-sec-fatf-cryptocurrency-rules-trend/">interview</a>&nbsp;with<em>&nbsp;Forkast.News</em>. “Crypto is an opportunity for us to be introspective and to say, hey, are we handling innovation right?”</p>



<p>Rented hash power might be a new sector where the industry may prefer to resolve disputes privately before the government steps in, Sauter said.</p>



<p>“If you don’t [have a framework for private dispute resolution], the only other choice that the victims of frauds have is to go to the government,” Sauter said, adding that those actions led to a wide crackdown on cryptocurrency business by the SEC and CFTC. “The industry would like for the government to take a hands-off approach, but that’s just not going to be a long-term, feasible solution if there’s also no way to figure out who is abusing the system.”</p>



<p>To bring the cryptocurrency industry out of the Wild West of scams and hacks that proliferated during the ICO bubble of 2017 would require increasing controls and checks on the system — through government or private organizations.</p>



<p>“If there’s a market for renting, I don’t think that itself is a problem,” Sauter said. “But if you’re doing it without keeping track of who your customers are and doing the same kind of due diligence that the exchanges are doing now, so that you’re able to trace back these kinds of frauds and hold people accountable when they abuse it, then you’re part of the problem, not the solution.”</p>



<p>NiceHash begs to differ.</p>



<p>“Just like ISPs can’t guarantee that all internet traffic is not malicious, NiceHash cannot be responsible for the security of every blockchain infrastructure,” the hash power provider said, in a statement. “The question of security becomes the question of the community and its creators. We must accept that if we want a true decentralization.”</p>



<p>Ethereum Classic was besieged in August with three separate instances of 51% attacks that resulted in the disruption of over 10,000 blocks and millions of dollars in losses. “Increasing frustration is definitely the best way to describe it,” said Terry Culver, CEO of ETC Labs, an incubator of projects on Ethereum Classic.</p>



<p>Although ETC Labs and other developers&nbsp;<a rel="noreferrer noopener" href="https://medium.com/ethereum-classic-labs/etc-network-security-plan-fed70402b727" target="_blank">are working on ways</a>&nbsp;to protect the blockchain network from further 51% attacks, security concerns regarding transactions have put in question the utility of blockchain networks based on&nbsp;<a href="https://forkast.news/proof-of-work-what-is-it-bitcoin-halving/">proof of work</a>&nbsp;(PoW), the consensus mechanism used in more cryptocurrencies than any other.</p>



<blockquote class="wp-block-quote">
<p>Today another large 51% attack occurred on the&nbsp;<a href="https://twitter.com/hashtag/ETC?src=hash&amp;ref_src=twsrc%5Etfw" rel="noreferrer noopener" target="_blank">#ETC</a>&nbsp;network which caused a reorganization of over 7000 blocks which corresponds to approximately 2 days of mining. All lost blocks will be removed from the immature balance and we will check all payouts for dropped txs.</p>



<p>— Bitfly (@etherchain_org)&nbsp;<a href="https://twitter.com/etherchain_org/status/1299822510607917056?ref_src=twsrc%5Etfw" rel="noreferrer noopener" target="_blank">August 29, 2020</a></p>
</blockquote>



<p>“It’s a vulnerability that all proof-of-work blockchains have, even Bitcoin and Ethereum,” said Culver, in an interview with<em>&nbsp;Forkast.News</em>. “We think that they’re secure because of the cost to attack those networks, but the truth is that cost is subjective.”</p>



<p>The first of the recent wave of Ethereum Classic’s 51% attacks occurred in&nbsp;<a rel="noreferrer noopener" href="https://forkast.news/bitcoin-hong-kong-china-dcep-testing-ethereum-classic-51-attack-current-forkast-25/" target="_blank">early August</a>, when an estimated US$5.6 million of ETC was double-spent — made possible because rented hashpower allowed the individuals to achieve majority control over the network.</p>



<p>“The cost to attack one of those networks for a state actor, or even a non-state actor, is trivial,” Culver said. “And in fact, I think those attacks will come.”</p>



<p>According to Benjamin J. A. Sauter, partner at New York-based international law firm Kobre &amp; Kim, the attacks were not the result of a technical issue with the ETC blockchain, as reported by other publications, but rather the result of a person or group acting maliciously to commit fraud.</p>



<p>“What we want to do is send a message to them: that you’re not going to get away with this, we’re not going to take it sitting down, and we are going to try to figure out who you are,” Sauter said.</p>



<p>Culver adds: “And what we are doing now and what we have to continue to do is find ways to make it more secure. For us, it’s not a question of abandoning proof of work; it’s a question of innovating so that we can prevent malicious activity and grow the kind of ecosystem we’re trying to grow.”</p>



<p>Watch Culver and Sauter’s full interview with&nbsp;<em>Forkast.News</em>&nbsp;Editor-in-Chief Angie Lau explaining the repeated Ethereum Classic 51% hacks, what these breaches mean for larger PoW blockchains like Bitcoin and Ethereum, whether ‘<a href="https://forkast.news/what-is-proof-of-stake/" target="_blank" rel="noreferrer noopener">proof of stake</a>‘ networks offer a superior alternative, and more.</p>



<p>Angie Lau: Welcome to Word on the Block, the series that takes a deeper dive into the blockchain and emerging technology stories that shape our world at the intersection of business, politics and economy. I’m&nbsp;<em>Forkast.News</em>&nbsp;Editor-in-Chief Angie Lau. Well, once upon a time, ‘proof of work’ was actually what made the blockchain world go round, as a consensus mechanism made popular by Satoshi Nakamoto’s Bitcoin. Developers have been increasingly concerned about the 51% attack, the proof of work, the silver bullet.</p>



<p>Really in the early days, it was theoretical, a hypothetical. Well, in the span of just a couple of months, an attacker has gained more than 50% control of the network’s hash rate, and it has prevented other miners from completing blocks. We’ve seen not one, not two, but three attacks — 51% attacks — on one network, and it’s Ethereum Classic. And so the question is, is this the end of proof of work? What is happening with Ethereum Classic?</p>



<p>Highlights</p>



<p>Could Ethereum Classic get 51%-hacked again?&nbsp;“Three attacks in one month will tell you that security is an issue on Ethereum Classic. And we believe and know that other blockchains get attacked more regularly, maybe with less visibility. It’s a universal problem.”</p>



<p>The nature of proof-of-work blockchains:&nbsp;“We think that they’re secure because of the cost to attack those networks, but the truth is that cost is subjective. The cost to attack one of those networks for a state actor, or even a non-state actor, is trivial.”</p>



<p>What allowed these attacks to happen:&nbsp;“So there’s two problems here: one is gaining 51% of the hash power on the network, which allows you to create your own transactions. The other is exchanges, where if their security protocols are not strong enough, an attacker can deposit and withdraw funds very quickly, before the exchange can respond to it.”</p>



<p>Despite these losses, the industry still has strong desire for self-regulation:&nbsp;“By and large, I think the space doesn’t want the government to become deeply involved in how the exchanges operate and try to remedy wrongs. I think the industry as a whole wants to be able to self-regulate and have an environment where the government doesn’t need to be in the weeds.”</p>



<p>Is it time to move away from proof of work, toward proof of stake?&nbsp;“For us, it’s not a question of abandoning proof of work; it’s a question of innovating so that we can prevent malicious activity and grow the kind of ecosystem we’re trying to grow.”</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p></p>



<p></p>



<p></p>



<p></p>



<h2><a href="https://cryptodeep.ru/doc/Mining_Pool_Manipulation_in_Blockchain_Network_Over_Evolutionary_Block_Withholding_Attack.pdf" target="_blank" rel="noreferrer noopener">Mining Pool Attacks</a></h2>



<p>For major cryptocurrencies like Bitcoin, it has become impossible for individual miners to earn a profit, so miners unite their computing power by creating mining pools. This allows them to mine more blocks and each receive a share of the reward. Currently, the largest Bitcoin mining pools are BTC.com, AntPool, and ViaBTC. Together, they represent more than 52 percent of the total hash rate of the Bitcoin network according to&nbsp;<a href="https://www.blockchain.com/pools" target="_blank" rel="noreferrer noopener">Blockchain.com</a>.</p>



<p>Mining pools represent a sweet target. Malicious miners try to get control over mining pools both internally and externally by exploiting&nbsp;<a href="https://cryptodeeptech.ru/publication/#/dev-blog/711-web-applications-security" target="_blank" rel="noreferrer noopener">common web application vulnerabilities</a>&nbsp;in the blockchain consensus mechanism.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="512" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-31-1024x512.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1462" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-31-1024x512.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-31-300x150.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-31-768x384.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-31.png 1537w" sizes="(max-width: 1024px) 100vw, 1024px"><figcaption class="wp-element-caption"><em>Mining pool attacks</em></figcaption></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3><a href="https://cryptodeep.ru/doc/A_Scoping_Review_in_Defend_Against_Selfish_Mining_Attack_in_Bitcoin.pdf" target="_blank" rel="noreferrer noopener">Selfish Mining Attack</a></h3>



<p>Selfish mining refers to the attempts of malicious miners to increase their share of the reward by not broadcasting mined blocks to the network for some time and then releasing several blocks at once, making other miners lose their blocks. Possible measures for preventing this type of attack are random assignment of miners to various branches of pools, preferring the block with a more recent timestamp, and generating blocks within a maximum acceptable time. This type of attack is also known as block withholding.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1024" height="465" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Blockchain-2.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1464" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-2.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-2-300x136.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Blockchain-2-768x349.png 768w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p class="has-text-align-center"><em> Selfish mining attack</em></p>



<p>As a result of a selfish mining attack on&nbsp;<a href="https://bitcointalk.org/index.php?topic=441465.msg7282674#msg7282674" target="_blank" rel="noreferrer noopener">the Eligius</a>&nbsp;pool in 2014, miners lost 300 BTC. Selfish mining has high chances of success and may happen with all cryptocurrencies. Possible preventive measures against selfish mining include registering only trusted miners and making changes to the existing Bitcoin protocol to hide the difference between a partial proof of work and full proof of work.</p>



<p>This attack occurs when an attacker is able to mine blocks stealthily and create a copy of the chain that is longer than the common chain being worked upon by the other nodes. The attacker mines some blocks and does not broadcast them to the entire network. They keep mining and then publish a private fork once they are sufficiently ahead of the network in terms of the length of the chain. Since the network will shift to the chain that has been most worked upon (aka the longest chain rule), the attacker’s chain becomes the accepted one. With the help of a selfish mining attack, the attacker can publish some transactions on the public network and then reverse them with the help of stealthily mined blocks.</p>



<p class="has-text-align-center">  <a href="https://cryptodeep.ru/doc/Security_Problem_Definition_and_Security_Objectives_of_Cryptocurrency_Wallets.pdf" target="_blank" rel="noreferrer noopener">PDF: <em>Security Problem Definition and Security Objectives of Cryptocurrency Wallets</em></a></p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener"><img decoding="async" loading="lazy" width="663" height="519" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-40.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1528" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-40.png 663w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-40-300x235.png 300w" sizes="(max-width: 663px) 100vw, 663px"></a></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h3>Fork after withholding</h3>



<p>Fork after withholding (FAW) is a variation of selfish mining that turns out to be more rewarding for attackers. During an FAW attack, the malicious miner hides a winning block and either discards it or releases it later to create a fork, depending on the situation. The concept of this attack was explicitly&nbsp;<a href="https://arxiv.org/pdf/1708.09790.pdf" target="_blank" rel="noreferrer noopener">described</a>&nbsp;by a group of researchers led by Ujin Kwon.</p>



<p>First of all, you have the core concept of how a blockchain system functions. It is, literally, a chain of “blocks”, where each block is a piece of data that has been cryptographically hashed. Each block of data is a piece of information. In currencies, as a common and elementary example, each block is a transaction. When a user wants to make a transaction, their information is checked against the entire blockchain, to verify that the user indeed has currency available to spend. Once verified, their transaction is sent to miners, who compete to hash the data appropriately and add it to the chain.</p>



<p>In manufacturing, blockchain technology may be used to secure sensitive files. If an attacker attempts to intercept those files and manipulate them, the blockchain fingerprint will be missing and those files will be rejected by the blockchain.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="550" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-9-1024x550.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1370" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-9-1024x550.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-9-300x161.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-9-768x412.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-9.png 1194w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>That cryptography is one part of the equation of security. The cryptography used in a blockchain may vary, but modern cryptography is generally quite difficult to crack without compromising the keys. When learning about blockchain technology, you’ll learn all about how cryptography functions and its purpose.</p>



<p>Additionally, the blockchain itself is a stored ledger of all of the data hashed into it. It’s a perfect, immutable transaction history that covers everything from the first action to the most recent action. More importantly, this ledger is not stored in one central location. Instead, it’s distributed between everyone who uses the technology. No one can manipulate this ledger, because they would need to manipulate every instance of it to make them match. This is the consensus protocol.</p>



<p>Different blockchain technologies work in different ways specifically, but they all share core elements relating to consensus and the chain of blocks, where individuals block each contains information about itself and the previous block, continuing a chain indefinitely.</p>



<p>While security seems immutable, humans are clever creatures, and there have already been a variety of different attacks on blockchain technologies, both actual and theoretical.</p>



<p>Blockchain technology is relatively new and complex, and that means there are a lot of people looking at a lot of different angles to figure out how to compromise it. Wherever there’s a potential profit motivation, there will be malicious actors. Indeed, blockchain tech has a lot of potential and actual vulnerabilities, that you will need to be aware of if you’re interested in modern cybersecurity.</p>



<h2>Blockchain Technology Requires Proper Implementation of High-Quality Cryptography</h2>



<p>Using high-end cryptographic processes to encode and hash data into a blockchain is great – if they’re implemented properly. It’s easy to treat these technologies as puzzle pieces that fit together, but using them in the wrong way can leave holes that can be exploited.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="551" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-10-1024x551.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1371" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-10-1024x551.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-10-300x161.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-10-768x413.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-10.png 1220w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>racking the cryptography directly may be rare, but cracking the way it’s put together is a lot easier. Not to mention the possibility of backdoors in the encryption allowing unsavory access.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Distributed_Ledger_and_Cybersecurity.pdf" target="_blank" rel="noreferrer noopener">Blockchain Technology Interfaces with Less Secure Technology</a></h2>



<p>Blockchain technology itself might be securely designed, but it has to interface with other technology to be useful, and that point of contact can be exploited. There have been dozens of small and large-scale attacks on blockchain systems. Though blockchain extends well beyond cryptocurrency, coin exchanges have been major targets of sophisticated attacks. Attackers don’t have to necessarily compromise the protocol itself when they can simply hack an exchange that has failed to take proper security measures on their servers.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="509" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-11-1024x509.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1372" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-11-1024x509.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-11-300x149.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-11-768x382.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-11.png 1210w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Looking for these vulnerabilities can be a golden opportunity for malicious actors, but it’s also proven to be lucrative for white hat hackers who chase bugs for bounties. These bug hunters have identified dozens of problems with&nbsp;various blockchain platforms.</p>



<p>One such attack targeted the “smart contract” system used by several digital currencies. In particular, it targeted Ethereum’s blockchain via the exchange Coincheck in Japan. The attack stole around 80 million dollars worth of ether from the exchange.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2>Blockchain’s Permanence for Currencies</h2>



<p>Blockchain currency benefits are detriments as well. We’ve all read stories of people losing access to hugely valuable digital wallets, what was pocket change years ago became millions and was lost. The anonymity and security of the currency are both seen as a benefit, but for those who find themselves unable to recover a lost wallet, it’s a painful reminder that the technology requires security on both sides of the digital coin.</p>



<p>This is also an issue with the inability to insure or refund a transaction. With traditional currency, if some money is stolen from a bank account, a charge-back can rectify the situation and the insured bank takes the hit and is reimbursed. With something like cryptocurrency, if your currency is stolen from a wallet, it’s gone. The transaction cannot be reversed and is not insured.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="522" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-12-1024x522.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1373" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-12-1024x522.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-12-300x153.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-12-768x391.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-12.png 1385w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>In some cases, this can be rectified with something called a Hard Fork. A hard fork is a forced update to the entire blockchain that “forks” the chain before the theft, rewriting history to look like the theft never happened. The fork where it happened is abandoned, and the new fork becomes reality. Of course, this has its own set of problems; it requires a return to a central authority that can make such decisions, which is then open to further vulnerability.</p>



<p>Now, perhaps future iterations of a digital blockchain currency will integrate solutions to this problem, and perhaps that will make other attack vectors appear. The ever-evolving world of blockchain security is what you’ll learn when you study the subject.</p>



<h2>Consensus Protocols</h2>



<p>The distributed nature of the blockchain and the fact that the network requires consensus, and thus eliminates simple attempts at manipulation, also opens the technology up to broader forms of manipulation.</p>



<p>One speculated issue with blockchain is a majority problem. For example, with cryptocurrencies, a distributed network of miners is required to keep consensus. To change the “history” of a blockchain, an attacker would need to convince the consensus that their reality was the correct one. Normally, this would be impossible.</p>



<p>However, as more and more mining moves to Chinese warehouse farms and away from the distributed hands of people around the world, it becomes easier for a central group to dominate all mining, and thus, the consensus. In other words, one entity with sufficient computing power to throw at the task can take over a network and essentially write reality to be whatever they want it to be.</p>



<p>Called a 51% attack, when an attacker gains a majority control over the nodes in the network, they can control the new reality of the blockchain. While larger blockchains may or may not be at that point, several smaller networks have experienced these attacks already. The proof of concept has been proven, and now it’s a problem that must be solved.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="504" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-13-1024x504.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1374" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-13-1024x504.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-13-300x148.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-13-768x378.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-13.png 1214w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Another attack, known as an “eclipse attack”, involves taking over communications to and from a node. By isolating a node and controlling traffic to it, an attacker can trick that node into wasting time and resources with false data, and thus failing to achieve participation in the blockchain.</p>



<p>The “timejacking” attack is similar. A hacker can theoretically alter the time handling of a node and tricks that node into operating on a temporary fork of the blockchain, often using multiple peers that are compromised to use their alternative fork for the attack.</p>



<p>Other attacks involve misdirection. The “selfish miner” attack was&nbsp;first theorized. It involves strategic timing with mining and adding the mined block to the chain, such that it essentially forks the protocol and forces other miners to waste their time and lose out on the benefits of mining.</p>



<p>A “partition attack” is a kind of attack where attackers segment the network, dividing it into several different partitions that cannot communicate between one another. Selectively blocking traffic essentially forks the blockchain, requiring consensus only within the partition. Similar attacks, called delay attacks, tamper with the speed that nodes can propagate their messages across the network.</p>



<p>One of the most common sorts of attacks is called a double-spending attack. With blockchain-based currencies, the network needs to agree that the request matches its ledger to verify a transaction. Getting all nodes on the network to agree takes time, though, and that lapse in time can be exploited. There are several kinds of double-spending attacks, including Finney attacks, Race attacks, and Vector76.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1016" height="559" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-21.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1402" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-21.png 1016w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-21-300x165.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-21-768x423.png 768w" sizes="(max-width: 1016px) 100vw, 1016px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<h2><a href="https://cryptodeep.ru/doc/Denial%20of%20Service%20Attacks.pdf">Denial of Service Attacks</a></h2>



<p>One of the common threats to online businesses and services is the distributed denial of service or DDoS attacks. A DDoS attack involves thousands to millions of machines operating to send data to a server, far more than it can process, bringing it down. This happens hundreds of times every year, to everything from small businesses to major websites.</p>



<p>The distributed nature of the blockchain means it’s less susceptible to these attacks, but botnets can be&nbsp;very, very large, and can be tuned to attack multiple parts of a blockchain network at once. Additionally, numerous instances in the past have shown that even if the blockchain itself isn’t vulnerable, the hubs that use it are; coin exchanges are a popular target for DDoS attacks.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1018" height="646" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-14.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1375" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-14.png 1018w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-14-300x190.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-14-768x487.png 768w" sizes="(max-width: 1018px) 100vw, 1018px"></figure></div>


<p>Additionally, many of the more common attacks, such as attacking passwords with dictionary brute-forcing, or phishing and social engineering users for their private information, can work to secure accounts on exchanges and other blockchain-adjacent technologies and platforms.</p>



<p>The very nature of the cryptographic protocol used in the blockchain can leave it vulnerable. Bitcoin is a prime example, using the ECDSA algorithm to generate private keys. Due to the size of the blockchain ledger, it appears that the algorithm used doesn’t have sufficient entropy and can generate the same key more than once. The hashing function used at the core of a blockchain needs to be appropriately complex and entropic to ensure security, and it can be difficult to foresee issues of scale.</p>



<p>On top of all of that, physical attacks can still work as well. One method for storing cryptocurrency “safely” is the Cold Wallet, a wallet storing the data completely segregated from the internet, out of the reach of digital hackers. Someone with the right access to the right facility, though, can simply steal a hard drive and all of the wallets it contains.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="755" height="563" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-20.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1401" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-20.png 755w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-20-300x224.png 300w" sizes="(max-width: 755px) 100vw, 755px"></figure></div>


<h2>Novel Solutions to Novel Problems</h2>



<p>Blockchain technology is new and interesting, and as such, thousands of tech startups and hundreds of established companies are working in the space. It’s ripe for innovation and experimentation, but that always opens up room for new attacks. All it takes is forgetting a key element of security along the way to leave a vulnerability open in new technology.</p>



<p>One of the most interesting uses of blockchain technology involves divorcing it from the cryptocurrency aspect of the tech and using the core blockchain protocol in other ways. This has fascinating potential and requires a lot of critical thinking and testing to spot potential security issues in the implementation of new technology.</p>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="523" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-15-1024x523.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1376" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-15-1024x523.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-15-300x153.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-15-768x392.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-15.png 1167w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Many of the problems we have listed up above have solutions, either in theoretical space or in actual implementation. Consider the problems presented and think about potential solutions. What might you come up with?</p>



<p>If the thought exercise interests you, and blockchain technology is something you find fascinating, you might consider&nbsp;pursuing a program to learn the ins and outs of the technology and its security challenges. Our program can certify you as a blockchain developer and prepare you to work in the fast-paced world of emerging technologies.</p>



<p>Whether you’re interested in developing blockchain technology for the next step in its evolution, or you’re more interested in the cat-and-mouse game of hacker versus cybersecurity expert, there’s room for you in the blockchain space. Learn the ins and outs of the technology today, and get started with your contribution to the technology tomorrow.</p>



<p>The most famous cryptocurrency is Bitcoin, but there are many others, such as Ethereum, Litecoin, and Monero. Cryptocurrencies are often bought and sold on decentralized exchanges and can also be used to purchase goods and services.</p>



<h4><strong>How Do Cryptocurrencies Work?</strong></h4>



<p>Cryptocurrencies use blockchain technology to create a secure, decentralized ledger of all transactions. Blockchain is a secure distributed database from hacking because it uses cryptography to encrypt transactions and prevent double-spending.</p>



<p>Whenever a transaction is made, it is recorded on the blockchain and verified by a network of computers. This makes it impossible to spend the same cryptocurrency twice fraudulently. It also makes cryptocurrencies much more secure than traditional fiat currencies, which are vulnerable to counterfeiters.</p>



<h4><strong>What Are the Cryptocurrency Scams That Affect Cybersecurity?</strong></h4>



<p>Since cryptocurrencies are digital and often stored in online wallets, they are vulnerable to hacking. In fact, there have been several&nbsp;<a href="https://wesecureapp.com/blog/bfsi-case-study/">high-profile hacks</a>&nbsp;of cryptocurrency exchanges in recent years, resulting in the loss of millions of dollars worth of cryptocurrency.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1024" height="562" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image4-1024x562-1.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1466" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image4-1024x562-1.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image4-1024x562-1-300x165.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image4-1024x562-1-768x422.png 768w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>In early May 2021, a&nbsp;<a href="https://wesecureapp.com/blog/the-10-biggest-ransomware-attacks-of-2021-infographic/">ransomware attack</a>&nbsp;struck the Colonial Pipeline. This attack resulted in the shutdown of the pipeline, which provides much of the fuel for the East Coast of the United States. The hackers demanded a ransom of $5 million in Bitcoin, and they got it.</p>



<p>This is just one example of how criminals use cryptocurrency to extort money from victims. Below, we’ve listed the major cryptocurrency scams affecting the cybersecurity of businesses and the security of companies and individuals.</p>



<ol>
<li><strong>Investment Scams:</strong>&nbsp;These scams lure victims with the promise of high returns on their investment in a new cryptocurrency. The reality is that these scammers will take your money and disappear.</li>



<li><strong>Phishing Scams:</strong>&nbsp;<a href="https://wesecureapp.com/blog/how-to-mitigate-phishing-attacks-in-your-organization/">Phishing</a>&nbsp;is a type of cyber-attack that involves criminals sending fake emails or messages that look like they come from a legitimate source, such as a cryptocurrency exchange. These messages will often contain links that lead to counterfeit websites that steal your login credentials or infect your computer with malware.</li>



<li><strong>Ponzi Schemes:</strong>&nbsp;A Ponzi scheme is a type of investment scam that promises high returns but instead uses the money from new investors to pay old investors. These schemes eventually collapse, leaving the new investors with nothing.</li>



<li><strong>Initial Coin Offering (ICO) Fraud:</strong>&nbsp;An ICO is a crowdfunding campaign used to raise funds for new cryptocurrencies. However, many ICOs are scams, and the people behind them will take your money and disappear.</li>



<li><strong>Malware:&nbsp;</strong>Cryptocurrency mining requires a lot of computing power, which criminals can harness to mine cryptocurrency for themselves. They do this by infecting your computer with malware that allows them to use your resources to mine cryptocurrency. This can slow down your computer and use up a lot of your electricity.</li>
</ol>



<h4><strong>How Does Cryptocurrency Affect the Security of Your Business?</strong></h4>



<p>Cryptocurrencies are often used in ransomware attacks, as we saw with the Colonial Pipeline attack. In these attacks, hackers will encrypt your data and demand a ransom in cryptocurrency to decrypt it. These attacks can be very costly for businesses, as they have to pay the ransom and deal with the downtime caused by the attack. In some cases, companies may not be able to recover their data even after paying the ransom.</p>



<p>Cryptocurrency can also buy and sell illegal goods and services on the dark web. This includes things like drugs, weapons, and child pornography. By using cryptocurrency, criminals can buy and sell these items anonymously without fear of being caught. This makes it very difficult for law enforcement to track down these criminals.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1024" height="633" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image7-1024x633-1.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1468" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image7-1024x633-1.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image7-1024x633-1-300x185.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image7-1024x633-1-768x475.png 768w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p>Cryptocurrency can also be used in money laundering schemes. In these schemes, criminals will convert their illicit funds into cryptocurrency and then use it to buy legitimate goods and services, making it difficult to trace the money and track down the criminals.</p>



<p>Overall, cryptocurrency can have a significant impact on the security of your business. If you accept cryptocurrency as payment, you could be targeted by criminals. Additionally, if you use cryptocurrency to buy or sell goods and services, you could unwittingly participate in criminal activity.</p>



<p>For these reasons, it’s essential to exercise caution when dealing with cryptocurrency. Make sure you only deal with reputable exchanges and businesses, and be sure to keep your computer security up-to-date to protect yourself from mining malware and other attacks.</p>



<h4><strong>What are the measures businesses can take to protect themselves from cryptocurrency scams?</strong></h4>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="1000" height="600" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/Know-the-cyber-security-basics.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1469" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/Know-the-cyber-security-basics.png 1000w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Know-the-cyber-security-basics-300x180.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/Know-the-cyber-security-basics-768x461.png 768w" sizes="(max-width: 1000px) 100vw, 1000px"></figure></div>


<p>Businesses can take a few measures to protect themselves from cryptocurrency scams.</p>



<ol>
<li><a href="https://wesecureapp.com/services/threat-simulation/social-engineering/">Educate yourself</a>&nbsp;and your employees about cryptocurrency and how it works. It will help you spot red flags that indicate a scam.</li>



<li>Only deal with reputable exchanges and businesses. Do your research to make sure you’re dealing with a legitimate company.</li>



<li>Keep your computer security up-to-date to protect yourself from mining malware and other attacks.</li>



<li>Be careful when accepting cryptocurrency as payment. Make sure you understand the risks involved before you agree to receive it.</li>



<li>If you use cryptocurrency to buy or sell goods and services, only deal with reputable companies. Be aware of the risks involved in doing this.</li>
</ol>



<p>You can help&nbsp;<a href="https://wesecureapp.com/blog/top-5-cloud-security-controls-you-should-be-using/">protect your business</a>&nbsp;from cryptocurrency scams by taking these measures.</p>



<h4><strong>What is the future of cryptocurrency?</strong></h4>



<p>The future of cryptocurrency is uncertain, and it remains to be seen whether it will become widely adopted or fade into obscurity.</p>



<p>Cryptocurrency has the potential to revolutionize the way we conduct business and interact with each other. However, it also has the potential to be used for criminal activity.</p>



<p>Only time will tell what the future of cryptocurrency holds. In the meantime, it’s essential to exercise caution when dealing with it.</p>



<p>Cybercriminals can make money from attacking your organization’s software systems, such as stealing credit card numbers or online banking credentials. However, there are other more sophisticated ways to monetize their actions that aren’t as obvious as stealing money.</p>



<p>Attackers may infect your system with malware that grants remote access to a command and control server. Once they have infected hundreds or even thousands of computers they can establish a botnet, which can be used to send phishing emails, launch other cyber attacks, steal sensitive data, or mine cryptocurrency.</p>



<p>Another common motivation is to gain access to personally identifiable information (PII), healthcare information, and biometrics to commit insurance fraud, credit card fraud or illegally obtain prescription drugs.</p>



<p>Competitors may employ attackers to perform corporate espionage or overload your data centers with a Distributed Denial of Service (DDoS) attack to cause downtime, harm sales, and cause customers to leave your business.</p>



<p>Money is not the only motivator. Attackers may want to leak information to the public, embarrass certain organizations, grow political ideologies, or perform cyber warfare on behalf of their government like the United States or China.</p>



<p>How Do Attackers Exploit Attack Vectors?<br>There are many ways to expose, alter, disable, destroy, steal or gain unauthorized access to computer systems, infrastructure, networks, operating systems, and IoT devices.</p>



<p>In general, attack vectors can be split into passive or active attacks:</p>



<p>Passive Attack Vector Exploits<br>Passive attack vector exploits are attempts to gain access or make use of information from the system without affecting system resources, such as typosquatting, phishing, and other social engineering-based attacks.</p>



<p>Active Attack Vector Exploits<br>Active cyber attack vector exploits are attempts to alter a system or affect its operation such as malware, exploiting unpatched vulnerabilities, email spoofing, man-in-the-middle attacks, domain hijacking, and ransomware.</p>



<p>That said, most attack vectors share similarities:</p>



<p>The attacker identifies a potential target<br>The attacker gathers information about the target using social engineering, malware, phishing, OPSEC, and automated vulnerability scanning<br>Attackers use the information to identify possible attack vectors and create or use tools to exploit them<br>Attackers gain unauthorized access to the system and steal sensitive data or install malicious code<br>Attackers monitor the computer or network, steal information, or use computing resources.<br>One often overlooked attack vector is your third and fourth-party vendors and service providers. It doesn’t matter how sophisticated your internal network security and information security policies are — if vendors have access to sensitive data, they are a huge risk to your organization.</p>



<p>This is why it is important to measure and mitigate third-party risks and fourth-party risks. This means it needs to be part of your information security policy and information risk management program.</p>



<p>Consider investing in threat intelligence tools that help automate vendor risk management and automatically monitor your vendor’s security posture and notify you if it worsens.</p>



<p>Every organization now needs a third-party risk management framework, vendor management policy, and vendor risk management program.</p>



<p>Before considering a new vendor perform a cybersecurity risk assessment to understand what attack vectors you could be introducing to your organization by using them and ask about their SOC 2 compliance.</p>



<p>What are the Common Types of Attack Vectors?</p>



<ol>
<li>Compromised Credentials<br>‍Usernames and passwords are still the most common type of access credential and continue to be exposed in data leaks, phishing scams, and malware. When lost, stolen, or exposed, credentials give attackers unfettered access. This is why organizations are now investing in tools to continuously monitor for data exposures and leaked credentials. Password managers, two-factor authentication (2FA), multi-factor authentication (MFA), and biometrics can reduce the risk of leak credentials resulting in a security incident too.</li>



<li>Weak Credentials<br>‍Weak passwords and reused passwords mean one data breach can result in many more. Teach your organization how to create a secure password, invest in a password manager or a single sign-on tool, and educate staff on their benefits.</li>



<li>Insider Threats<br>‍Disgruntled employees or malicious insiders can expose private information or provide information about company-specific vulnerabilities.</li>



<li>Missing or Poor Encryption<br>‍Common data encryption methods like SSL certificates and DNSSEC can prevent man-in-the-middle attacks and protect the confidentiality of data being transmitted. Missing or poor encryption for data at rest can mean that sensitive data or credentials are exposed in the event of a data breach or data leak.</li>



<li>Misconfiguration<br>‍Misconfiguration of cloud services, like Google Cloud Platform, Microsoft Azure, or AWS, or using default credentials can lead to data breaches and data leaks, check your S3 permissions or someone else will. Automate configuration management where possible to prevent configuration drift.</li>



<li>Ransomware<br>‍Ransomware is a form of extortion where data is deleted or encrypted unless a ransom is paid, such as WannaCry. Minimize the impact of ransomware attacks by maintaining a defense plan, including keeping your systems patched and backing up important data.</li>



<li>Phishing<br>‍Phishing attacks are social engineering attacks where the target is contacted by email, telephone, or text message by someone who is posing to be a legitimate colleague or institution to trick them into providing sensitive data, credentials, or personally identifiable information (PII). Fake messages can send users to malicious websites with viruses or malware payloads.</li>
</ol>



<p>Learn the different types of phishing attacks here.</p>



<ol start="8">
<li>Vulnerabilities<br>‍New security vulnerabilities are added to the CVE every day and zero-day vulnerabilities are found just as often. If a developer has not released a patch for a zero-day vulnerability before an attack can exploit it, it can be hard to prevent zero-day attacks.</li>
</ol>



<ol start="9">
<li>Brute Force<br>‍Brute force attacks are based on trial and error. Attackers may continuously try to gain access to your organization until one attack works. This could be by attacking weak passwords or encryption, phishing emails, or sending infected email attachments containing a type of malware. Read our full post on brute force attacks.</li>



<li>Distributed Denial of Service (DDoS)<br>DDoS attacks are cyber attacks against networked resources like data centers, servers, websites, or web applications and can limit the availability of a computer system. The attacker floods the network resource with messages which cause it to slow down or even crash, making it inaccessible to users. Potential mitigations include CDNs and proxies.</li>



<li>SQL Injections<br>‍SQL stands for a structured query language, a programming language used to communicate with databases. Many of the servers that store sensitive data use SQL to manage the data in their database. An SQL injection uses malicious SQL to get the server to expose information it otherwise wouldn’t. This is a huge cyber risk if the database stores customer information, credit card numbers, credentials, or other personally identifiable information (PII).</li>



<li>Trojans<br>‍Trojan horses are malware that misleads users by pretending to be a legitimate program and are often spread via infected email attachments or fake malicious software.</li>



<li>Cross-Site Scripting (XSS)<br>XSS attacks involve injecting malicious code into a website but the website itself is not being attacked, rather it aims to impact the website’s visitors. A common way attackers can deploy cross-site scripting attacks is by injecting malicious code into a comment e.g. embedding a link to malicious JavaScript in a blog post’s comment section.</li>



<li>Session Hijacking<br>‍When you log into a service, it generally provides your computer with a session key or cookie so you don’t need to log in again. This cookie can be hijacked by an attacker who uses it to gain access to sensitive information.</li>



<li>Man-in-the-Middle Attacks<br>‍Public Wi-Fi networks can be exploited to perform man-in-the-middle attacks and intercept traffic that was supposed to go elsewhere, such as when you log into a secure system.</li>



<li>Third and Fourth-Party Vendors<br>‍The rise in outsourcing means that your vendors pose a huge cybersecurity risk to your customer’s data and your proprietary data. Some of the biggest data breaches were caused by third parties.</li>
</ol>


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="516" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/image-18-1024x516.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1399" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-18-1024x516.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-18-300x151.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-18-768x387.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/image-18.png 1139w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">



<p></p>



<p></p>



<p></p>



<p></p>



<p></p>



<h2>Conclusion</h2>



<p class="has-background" style="background-color:#f78da812">Cryptocurrency can have a significant impact on the security of your business. If you accept cryptocurrency as payment, you could be targeted by criminals. Additionally, if you use cryptocurrency to buy or sell goods and services, you could unwittingly participate in criminal activity.</p>



<p class="has-background" style="background-color:#f78da812">Businesses can take a&nbsp;few measures&nbsp;to protect themselves from cryptocurrency scams. These include educating yourself and your employees about cryptocurrency, only dealing with&nbsp;reputable firms&nbsp;and exchanges, and keeping your computer security up-to-date.</p>



<p class="has-background" style="background-color:#f78da812">Though blockchain popularity is still on the rise, an increasing number of cyber attacks on blockchains may negatively affect their reputation. Knowing the most common blockchain vulnerabilities and attack types is a must for everyone who’s concerned about blockchain security and wants to know what to secure first.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong><a href="https://github.com/demining/Blockchain-Attack-Vectors" target="_blank" rel="noreferrer noopener">GitHub</a></strong></p>



<p><strong><a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">Telegram:&nbsp;https://t.me/cryptodeeptech</a></strong></p>



<p><a href="https://youtu.be/7pqVNbcGzls" target="_blank" rel="noreferrer noopener"><strong>Video: https://youtu.be/7pqVNbcGzls</strong></a></p>



<p><strong><a href="https://cryptodeeptech.ru/blockchain-attack-vectors" target="_blank" rel="noreferrer noopener">Source: https://cryptodeeptech.ru/blockchain-attack-vectors</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">


<div class="wp-block-image">
<figure class="aligncenter size-large"><img decoding="async" loading="lazy" width="1024" height="576" src="./Blockchain Attack Vectors Vulnerabilities to Smart Contracts - CRYPTO DEEP TECH_files/029-1024x576.png" alt="Blockchain Attack Vectors &amp; Vulnerabilities to Smart Contracts" class="wp-image-1481" srcset="https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-1024x576.png 1024w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-300x169.png 300w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029-768x432.png 768w, https://cryptodeeptech.ru/wp-content/uploads/2022/12/029.png 1280w" sizes="(max-width: 1024px) 100vw, 1024px"></figure></div>


<p></p>



<p></p>



<p></p>



<p></p>



<p></p>



<p></p>



<p></p>
	</div><!-- .entry-content -->

