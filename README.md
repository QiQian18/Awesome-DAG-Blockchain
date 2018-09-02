# Awesome DAG Blockchain

[![](https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667)](https://github.com/sindresorhus/awesome)
[![](https://camo.githubusercontent.com/cb8cb80af654f3dae14a4aa62e44bf62f16953d6/68747470733a2f2f6a617977636a6c6f76652e6769746875622e696f2f73622f6c616e672f6368696e6573652e737667)](README.md)
[![](https://camo.githubusercontent.com/15a53d5ec5d896319068168a27da0203156bbdb9/68747470733a2f2f6a617977636a6c6f76652e6769746875622e696f2f73622f6c616e672f656e676c6973682e737667)](README-en.md)

这个仓库主要是用来搜集与基于DAG技术的区块链相关的资源，请随意Star或者Fork。如果有任何建议和评论，[请提交到这里](https://github.com/guantau/Awesome-DAG-Blockchain/issues)。欢迎提交各种PR :)，格式参考 [awesome](https://github.com/sindresorhus/awesome) 的清单。

> 喜欢DAG技术的小伙伴有根据地啦，欢迎来我们的DAG技术研究室（ https://daglabs.io/ ）交流及投稿并关注我们的公众号
> ![](http://oc7urqs4c.bkt.clouddn.com/2018-05-20-daglabs_qrcode.jpg)


[中文](README.md) | [English](README-en.md)

## 目录

+ [科普介绍](#科普介绍)
+ [DAG基础](#DAG基础)
+ [主要论文](#主要论文)
+ [典型项目](#典型项目)
+ [技术评测](#技术评测)
+ [相关视频](#相关视频)
+ [相关人物](#相关人物)

## 科普介绍

+ [Future of digital currency may not involve blockchains](https://cointelegraph.com/news/future-of-digital-currency-may-not-involve-blockchains)
+ [Will Other Distributed Ledgers Replace Blockchain?](https://coincentral.com/dag-replace-blockchain/)
+ [Scaling cryptocurrencies: DAGs](https://codeburst.io/scaling-crypto-dags-82363451e753)
+ [警报！一大波DAG公链正在接近！](http://mp.weixin.qq.com/s/YypTjeuWd4RCAJbDvAmucA)
+ [Blockchain and the Challengers](https://blog.goodaudience.com/blockchain-and-the-challengers-74e22cf0cf4e)
+ [区块链共识机制分析——论PoW，PoS，DPos和DAG的优缺点](http://www.8btc.com/blockchain-concensus-mech)
+ [A Beginner’s Ultimate Guide To DAGs](https://hackernoon.com/a-beginners-ultimate-guide-to-dags-7fc0dd7f39a2)
+ [An Introduction to the BlockDAG Paradigm](https://blog.daglabs.com/an-introduction-to-the-blockdag-paradigm-50027f44facb)
+ [DAG vs Blockchain](https://medium.com/crypto-mails/cryptography-dag-vs-blockchain-f4bb4d4590c2)
+ [Ledgers over the years - from ancient Egypt to blockchain, DAG and beyond](https://medium.com/@COTInetwork/ledgers-over-the-years-from-ancient-egypt-to-blockchain-dag-and-beyond-47924175cb97)
+ [Scaling cryptocurrencies: DAGs](https://codeburst.io/scaling-crypto-dags-82363451e753)
+ [Scaling crypto (idea): DAG + “clockchain”](https://medium.com/@thedavidmeister/scaling-crypto-idea-dag-clockchain-7809532c76bc)

## DAG基础

+ [DAG - Wikipedia](https://en.wikipedia.org/wiki/Directed_acyclic_graph)
+ [DAG在分布式版本控制Git上的应用](http://ericsink.com/vcbe/html/directed_acyclic_graphs.html)


## 主要论文

+ [NXT论坛DAG帖](https://nxtforum.org/proof-of-stake-algorithm/dag-a-generalized-blockchain/) - 2014年帖子，需登录查看
+ [DAGCoin](https://bitslog.files.wordpress.com/2015/09/dagcoin-v41.pdf) - 2015年由Sergio Demian Lerner提出，但并没有代码实现
+ [Accelerating Bitcoin’s Transaction Processing. Fast Money Grows on Trees, Not Chains.](https://eprint.iacr.org/2013/881.pdf) - 2013年由提出修改Bitcoin协议，从而加快确认速度
+ [Secure High-Rate Transaction Processing in Bitcoin](http://www.avivz.net/pubs/15/btc_ghost.pdf) - 提出了GHOST（Greedy Heaviest-Observed Sub-Tree），Ethereum的共识就是基于GHOST
+ [Inclusive Block Chain Protocols](http://www.cs.huji.ac.il/~avivz/pubs/15/inclusive_btc.pdf) - 2015年提出DAG模型
+ [SPECTRE:Serialization of Proof-of-work Events: Confirming Transactions via Recursive Elections.](https://eprint.iacr.org/2016/1159.pdf) - 基于DAG的分布式账本
+ [PHANTOM: A Scalable BlockDAG protocol](https://eprint.iacr.org/2018/104.pdf)  - 解决了blockDAG全序的问题
    + [中文翻译](https://github.com/DAGfans/TranStudy/blob/master/Papers/PHANTOM%20-%20A%20Scalable%20BlockDAG%20protocol.md)
+ [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV) - 新型的DAG协议Avalanche
+ [Scaling Nakamoto Consensus to Thousands of Transactions per Second](https://arxiv.org/pdf/1805.03870.pdf) - 新型的DAG协议Conflux


## 典型项目

### IOTA

+ 简介：面向物联网应用
+ [官网](https://iota.org/)
+ [白皮书](https://iota.org/IOTA_Whitepaper.pdf)
+ [代码库](https://github.com/iotaledger)
+ 相关文章：
  + [解不开的缠结和IOTA的泪](http://mp.weixin.qq.com/s/BXf3BTMDGVbMheRQjZXQPw)
  + [10分钟看懂曾飙涨千倍却暗藏风险的IOTA和它的DAG](http://mp.weixin.qq.com/s/RV9Buz_J2s-ZeufPV7afTg)
  + [Cryptographic vulnerabilities in IOTA](https://medium.com/@neha/cryptographic-vulnerabilities-in-iota-9a6a9ddc4367)
  + [创始人come-from-beyond解释IOTA的经济学考虑](https://medium.com/@comefrombeyond/economic-clustering-and-iota-d3a77388900)
  + [IOTA可视化展示](https://public-rdsdavdrpd.now.sh/)
  + [IOTA is centralized](https://medium.com/@ercwl/iota-is-centralized-6289246e7b4d)

### Byteball

+ 简介：面向日常支付使用，具有简单的智能合约
+ [官网](http://byteball.org/)
+ [白皮书](https://byteball.org/Byteball.pdf)
+ [代码库](https://github.com/byteball)
+ 相关文章：
  + [byteball介绍1](https://medium.com/@Suirelav/introduction-to-byteball-part-1-why-ab3ff6a7a8f2) - byteball的产生原因
  + [byteball介绍2](https://medium.com/@Suirelav/introduction-to-byteball-part-2-the-dag-ce84ca4c4e01) - DAG技术
  + [byteball介绍3](https://medium.com/@Suirelav/introduction-to-byteball-part-3-smart-contracts-81efa010a0b3) - 智能合约
  + [byteball介绍4](https://medium.com/@Suirelav/introduction-to-byteball-part-4-adoption-ff37d87615c9) - byteball的各种应用
  + [byteball原理解析1](http://blog.guantau.com/2017/12/14/byteball1/) - DAG数学基础及byteball区块链结构
  + [byteball原理解析2](http://blog.guantau.com/2017/12/19/byteball2/) - byteball的共识算法
  + [byteball原理解析3](http://blog.guantau.com/2018/01/19/byteball3/) - byteball的地址、脚本及合约
  + [byteball原理解析4](http://blog.guantau.com/2018/01/26/byteball4/) - byteball的网络结构
  + [byteball原理解析5](http://blog.guantau.com/2018/01/30/byteball5/) - byteball的应用
  + [byteball主网压力测试](https://blog.goodaudience.com/byteball-main-net-under-stress-test-c131ba85b72b) - 测试给出了三点结论：（1）交易处理速度仅能达到15TPS左右，不同于传统区块链交易处理速度受限于区块大小，DAG网络的交易处理速度与代码执行速度、网络传输时延、硬件处理能力等都可能有关系；（2）网络容易遭受DOS攻击，大量突发式的恶意交易会阻塞网络，降低网络的交易处理速度；（3）随着交易数量增加，交易确认时间可以保持平稳。
  + [Byteball这个项目太让人兴奋了！](https://mp.weixin.qq.com/s/vDo-mSxtSWxaJdyfNzhRMA)
  + [Byteball-NG 新一代DAG区块链](https://medium.com/@iamliqiang/byteball-ng-%E6%96%B0%E4%B8%80%E4%BB%A3dag%E5%8C%BA%E5%9D%97%E9%93%BE-dd353cede558)
  + [Byteball +2 mutations brute force attack](https://blog.goodaudience.com/byteball-2-mutations-brute-force-attack-29fc1f49c654)
  + [Byteball move proposal](https://blog.goodaudience.com/byteball-move-proposal-831187509ed0)

### NANO

+ 简介：早期称为RaiBlocks，最早在2014年发布beta测试
+ [官网](https://nano.org/)
+ [白皮书](https://nano.org/zh/whitepaper)
+ [代码库](https://github.com/nanocurrency)
+ 相关文章：
  + [RaiBlocks网络压力测试1](https://hackernoon.com/stress-testing-the-raiblocks-network-568be62fdf6d)
  + [RaiBlocks网络压力测试2](https://medium.com/@bnp117/stress-testing-the-raiblocks-network-part-ii-def83653b21f)

### HashGraph

+ 简介：一种新型的DAG技术
+ [官网](https://hashgraph.com/)
+ [白皮书](https://www.swirlds.com/downloads/SWIRLDS-TR-2016-01.pdf)
+ 代码库：
  + [Python实现](https://github.com/Lapin0t/py-swirld)
  + [NodeJS实现](https://github.com/TheCallSign/hashgraph)
  + [Go实现](https://github.com/babbleio/babble)
+ 相关文章：
  + [区块链败局已定，Hashgraph 才是未来？](http://mp.weixin.qq.com/s/9KlHqfGHLf9cELL4x98UCw)
  + [Hashgraph —— 或许是目前最为优秀的共识协议](http://mp.weixin.qq.com/s/eo8QiCNwphKJ4m-j43fhEA)
  + [神级项目Hashgraph真的能成为区块链终结者吗？](http://mp.weixin.qq.com/s/BXf3BTMDGVbMheRQjZXQPw)
  + [未来的分布式账本技术:不是区块链，是哈希图?](https://zhuanlan.zhihu.com/p/33558463?group_id=948705960718454784)
  + [Zillqa CTO谈Hashgraph](http://mp.weixin.qq.com/s/22sKqQerMPav5XltTydUoQ)
  + [Hashgraph: Will It Make Blockchain Obsolete?](https://coinsutra.com/hedera-hashgraph/) - 基础原理分析
  + [Building with HashGraph Part 1: Introduction](https://medium.com/hackers-at-cambridge/building-with-hashgraph-part-1-introduction-3232f9ea89ef) - HashGraph开发指南（一）
  + [Building with HashGraph Part 2: Technical Workthrough](https://medium.com/hackers-at-cambridge/building-with-hashgraph-part-2-technical-workthrough-af63eefa53f2) - HashGraph开发指南（二）
  + [Why Hashgraph will never replace Blockchain](https://medium.com/@Lansana/i-was-wrong-hashgraph-is-actually-very-bad-bf7d9b2e8d99)
  + [Inside the Distributed Ledger World; Is the Hashgraph Better Than the Blockchain?](https://medium.com/@nucfootball/inside-the-distributed-ledger-world-is-the-hashgraph-better-than-the-blockchain-6be1f76f7cd5)
  + [Blockchain Just Became Obsolete. The Future is Hashgraph](https://medium.com/@justindanneman/blockchain-just-became-obsolete-the-future-is-hashgraph-de4948609cbf)
  + [HASHGRAPH Python Implementation.](https://medium.com/@vaibhavsaini_67863/hashgraph-python-implementation-501c5ad47531)
  + [Demystifying Hashgraph: Benefits and Challenges](https://hackernoon.com/demystifying-hashgraph-benefits-and-challenges-d605e5c0cee5)
  + [Is The Future Of Blockchains DAGs ?— 5 Takeaways From The Hashgraph Event In NYC on March 13th](https://medium.com/crypto-oracle/is-the-future-of-blockchains-dags-5-lessons-from-the-hashgraph-event-in-nyc-on-march-13th-ff0f7e0fa510)
  + [Hedera Hashgraph and a few thoughts on the future of distributed ledgers](https://medium.com/@eburgwedel/hedera-hashgraph-and-a-few-thoughts-on-the-future-of-distributed-ledgers-648e9eefb901)

### COTI

+ 简介：基于DAG的新型数字支付，提出Trust Chain共识
+ [官网](https://www.coti.io)
+ [白皮书](https://www.coti.io/en/files/COTI-overview-document.pdf?v=a059736e358)
+ 相关文章：
  + [技术白皮书](https://www.coti.io/en/files/COTI-technical-whitepaper.pdf?v=a059736e358)
  + [The Trustchain Consensus](https://medium.com/cotinetwork/the-trustchain-consensus-44a0c807c71d) - 共识算法介绍
  + [2018 could be the year of non-leader-based consensus mechanisms](https://medium.com/cotinetwork/2018-could-be-the-year-of-non-leader-based-consensus-mechanisms-c1d072c71ff9)

### CyberVein

+ 简介：为DAG引入了一种新型资源节约共识机制，重塑了去中心化数据库，以及人们保护信息并实现信息资产化的方式
+ [官网](https://www.cybervein.org/)
+ [白皮书](https://www.cybervein.org/whitepaper)

### Perlin

+ 简介：实现了Avalanche协议，分为共识层和计算层
+ [官网](https://www.perlin.net/)
+ [白皮书](https://ipfs.io/ipfs/QmXNJXNtxFDg5vwBiXuDSUGpfatakock1qJzQkNujzrP37)
+ [代码库](https://github.com/perlin-network)

### DAGX

+ 简介：基于DAG的价值互联与交换网络
+ [官网](https://dagx.io/)
+ [白皮书](https://dagx.io/dagx.pdf)
+ [代码库](https://github.com/dagxio)

### DAGCoin

+ 简介：基于Byteball代码进行修改
+ [官网](https://dagcoin.org/)
+ [白皮书](https://dagcoin.org/whitepaper.pdf)
+ [代码库](https://github.com/dagcoin/)

### TrustNote

- 简介：基于Byteball代码进行修改
- [官网](https://trustnote.org/)
- [白皮书](https://trustnote.org/TrustNote-WhitePaper.pdf)
- [代码库](https://github.com/trustnote)
- [创世贴](https://bitcointalk.org/index.php?topic=3116483.0)

### Nerthus

- 简介：基于DAG通用的智能合约编程平台与区块链操作系统
- [官网](http://nerthus.io/)
- [白皮书](http://nerthus.io/static/downfile/NerthusWhitePageV0.0.2.pdf)

### IOT Chain

- 简介：使用PBFT+DAG
- [官网](https://iotchain.io/)
- [白皮书](https://iotchain.io/whitepaper/ITCWHITEPAPER.pdf)
- [代码库](https://github.com/IoTChainCode)

### XDAG

- 简介：首个可以挖矿的DAG
- [创世贴](https://bitcointalk.org/index.php?topic=2552368.0)
- [官网](http://xdag.io/)
- [白皮书](https://docs.google.com/document/d/1ruNpTVghy0Xsb8gOa-8sYG58GHU_ibeGnwJi2h0TTnA/edit)

### MOL

+ 简介：即时免交易费的DAG公有链
+ [官网](https://www.mol.one/)
+ [白皮书](https://www.mol.one/static/assets/Whitepaper.pdf)
+ [钱包](https://www.mol.one/wallet.html)


### AskCoin（未完成）

- 简介：基于DAG的知识付费
- [白皮书](https://blog.askcoin.org/askcoin-in-one-page-f284bb3d9b42)


### 其它

+ [daglabs](https://www.daglabs.com/) - 主要实现SPECTRE和PHANTOM两种DAG上的共识算法
+ [Get Rid of Blocks](http://slides.com/davidvorick/braids)


## 技术评测

+ [IOTA vs RaiBlocks](https://hackernoon.com/iota-vs-raiblocks-413679bb4c3e)
+ [DAG coin comparison (Byteball, IOTA, RaiBlocks, etc)](https://web.archive.org/web/20171211100146/https://www.reddit.com/r/CryptoCurrency/comments/7iv20r/dag_coin_comparison_byteball_iota_raiblocks_etc/)
+ [ByteBall vs IOTA - battle of two DAG cryptocurrencies](https://steemit.com/cryptocurrency/@jimmco/byteball-vs-iota-battle-of-two-dag-cryptocurrencies)
+ [Blockchain vs DAG (Byteball's concencus algorithm).](https://bitcointalk.org/index.php?topic=1799665.0)
+ [Blockchain vs DAG (Directed Acyclic Graphs) vs Byteball](https://medium.com/coinmonks/blockchain-vs-dag-directed-acyclic-graphs-vs-byteball-c10250702521)
+ [Confirmation Times in SPECTRE](https://blog.daglabs.com/confirmation-times-in-spectre-7f68fec0d997)
+ [IOTA and SPECTRE](https://medium.com/@johndom/iota-and-spectre-64ee12d9b1a8)
+ [Scaling a Blockchain vs Scaling a Tangle - Pointing out possible weaknesses in the DAG scalability](https://medium.com/coinmonks/scaling-a-blockchain-vs-scaling-a-tangle-8b7182eda980)

## 相关视频



## 相关人物

+ Sergio Demian Lerner
+ Yonatan Sompolinsky
+ Yoad Lewenberg
+ Aviv Zohar
+ Serguei Popov
+ Sergey Ivancheglo
+ Anton Churyumov
+ Leemon Baird


