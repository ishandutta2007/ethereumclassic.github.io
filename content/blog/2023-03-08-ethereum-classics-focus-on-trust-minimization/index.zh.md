---
title: "以太坊经典对信任最小化的关注"
date: 2023-03-08
author: Donald McIntyre
contributors: ["DonaldMcIntyre"]
tags: ["Philosophy"]
linkImage: ./1.png
---

---
**欢迎由此收听或观看本期内容:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/I9t3xHtAA48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## 什么是信任最小化？

区块链行业的一个常见误解是，这些系统是“不可信的”，但这不是正确的术语或定义。

事实是，像以太坊经典(ETC)这样的区块链是“信任最小化”的，因为仍然有一些对第三方的依赖，这正是为什么我们的关注是应该保持这种方式。

我们所谈论的这种依赖性可以通过以下6个例子来说明:

**1.对矿工的依赖:** 矿工从网络接收交易，使用大量的计算能力和电力进行哈希，然后将区块发送到网络的其他部分，将它们包含在区块链中。这意味着网络依赖于矿工基础来保证其安全性。

**2.对于验证节点的依赖:** 当矿工将区块发送到网络的其他部分时，验证节点将获得新的区块并验证它们。一旦验证，区块就会包含在区块链中，奖励就会存入矿工的账户中。这建立了常规用户和矿工对验证者的依赖，以保持数据的完整性，不包含虚假信息或交易，并在矿工的情况下获得报酬。

**3.复制数据库的存储:** 区块链本身就是一个巨大的数据库。验证节点不仅验证区块链，而且还存储区块链，以保存历史，以供日常使用、保障安全以及子孙后代使用。这是世界对节点操作符的巨大依赖，因为在网络中所有机器中完全复制的数据库是其安全性的关键之一，这是最大限度地增加数据冗余。

**4.交易和区块分配:** 为了实现数据库的完全复制，必须在全球所有节点之间有一个事务和块的分布过程。这是通过让所有参与的机器接收所有交易和所有区块，然后将它们重新发送到所有其他节点来实现的。这是参与者和外部用户的依赖关系，因为如果没有所有节点的协作努力，就不可能实现此功能。

**5.引导节点:** 为了能够第一次加入网络或在脱机后再次连接，每个网络软件客户端都有一个引导节点列表，这些节点在那里接收新的进入者，并向它们发送数据库的所有块，以便它们可以同步并成为其中的一部分。这是一个依赖于其他人能够加入，并重新进入，并能够同步区块链的历史。

**6.核心开发人员:** 核心开发人员是计算机科学家和工程师，他们为升级和修复系统可能不时出现的错误进行研究和开发。他们还在紧急情况下立即采取行动，以防出现网络分裂或必须防止的攻击。这种情况很少发生，但即使在最好和最大的区块链上也发生过。这是对开发人员执行这些任务的依赖。

那么，如果这些依赖关系存在，那么为什么区块链被认为是信任最小化和安全的呢?

![信任最小化的关键是对风险的分配](./1.png)

最小化信任的关键是将这些依赖分布到许多第三方之间，这些第三方可以模糊地、可互换地执行这些依赖。

从矿工到节点运营商，再到开发人员，以太坊经典的设计方式是，这些组成部分都不是单独不可缺少或不可替代的。

世界上任何一个矿工都可以随时加入和离开网络，任何一个节点操作员都可以这样做，核心开发人员是来自不同地区的几个专业人员，世界上任何人都可以检查和学习ETC的代码并在上面工作，因为它是一个开源项目。

在操作网络层，在许多矿工和验证节点之间实现这种级别的全球分布的方法是使用基于工作量证明的共识机制，因为它是唯一提供无许可的入口和出口点的系统，这是每个区块中的加密印章。

## 中本聪对信任最小化的关注

中本聪在[比特币白皮书](https://bitcoin.org/bitcoin.pdf)中14次直接或间接地提到了信任最小化，这是一个例子，说明信任最小化是多么重要，以及它是如何成为密码朋克在构建系统时的中心目标。

**在摘要中提到信任最小化:**

*- 纯点对点版的电子现金将允许在线支付从一方直接发送到另一方，而无需通过金融机构。数字签名提供了部分解决方案，但如果仍然需要可信的第三方来防止重复支出，则主要的好处就失去了.*

**在开篇导语中:**

*- 互联网上的商业几乎完全依赖金融机构作为可信赖的第三方来处理电子支付。*

*- 尽管该系统在大多数交易中运行良好，但它仍然存在基于信任的模型固有的弱点。*

*- 随着形势逆转的可能性，对信任的需求扩大。*

*- 这些成本和支付的不确定性可以通过使用实物货币来避免，但是没有机制可以在没有可信方的情况下通过通信渠道进行支付。*

*- 我们需要的是一个基于加密证明而不是信任的电子支付系统，允许任何两个愿意进行交易的双方直接进行交易，而不需要可信的第三方。*

**在交易部分:**

*- 一个常见的解决方案是引入一个可信的中央机构，或mint，检查每笔交易是否重复支出。*

*- 每笔交易结束后，硬币必须返回造币厂发行新硬币，只有直接从造币厂发行的硬币才被信任不会重复使用。*

*- 要在没有可信方的情况下完成这一点，交易必须公开宣布，并且我们需要一个系统，让参与者就接收它们的顺序的单一历史记录达成一致。*

**在隐私部分:**

*- 传统的银行模式通过限制相关方和受信任的第三方访问信息来实现一定程度的隐私。*

**在隐私部分的图中:**

![图中提到的可信第三方](./2.png)

图的顶部显示了一个受信任的第三方，以说明传统的银行系统。底部部分没有显示可信第三方，这表明模型更安全。

**结论部分**

*- 我们提出了一个不依赖信任的电子交易系统。*

**在参考资料部分:**

*- [2] H. Massias, X.S. Avila, and J.-J. Quisquater, “Design of a secure timestamping service with minimal trust requirements,” In 20th Symposium on Information Theory in the Benelux, May 1999.*

## 为什么ETC应该关注信任最小化?

以太坊经典应该持续关注信任最小化有两个原因。

首先，一旦我们了解到这些系统是信任最小化的，而不是不信任的，那么我们就会意识到，我们仍然存在一些边际风险，即我们仍然存在于受信任的第三方中。如果不关注信任最小化，这种风险可能会增加，因为任何新的更改或升级都可能增加这种风险。

第二个原因是，我们将进入一个全球化和中心化的世界，如果我们不使用以太坊经典系统，受信任的第三方将控制我们生活的方方面面。ETC是受信任的、对第三方无情武断行为的避难所，是世界自由的灯塔。而且ETC将必须保持这种状态。

---

**感谢您阅读本期文章!**

想要了解更多关于ETC的信息，请访问: https://ethereumclassic.org