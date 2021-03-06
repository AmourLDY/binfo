---
title: 加密经济学
---

从比特币出现之前很多年开始，人们就都试图在网络上用去中心化的手段实现很多事情。很多人期待一个，没有中央节点，不能形成权力怪兽，依托密码学实现的经济体系。有人把这个体系叫开放经济，也有人叫做加密经济。加密经济学就是对加密经济的实现方法的研究。

## 提出“加密经济学”这个概念的意义

以前 BT 下载的年代，大家认为去中心化的架构其实能做的事情是非常有限的。直到比特币出现后，人们才发现想要做的事情终于有了突破。但是话说回来了，大家究竟想要用去中心化思路做的这个事情是什么呢？不同的人其实有着不太相同的答案。

以太坊之父 V 神的提出了“加密经济学”这个概念，英文是 Cryptoeconomics 。MIT 加密经济实验室 https://ce.mit.edu/ 认为，加密经济学是计算机科学和经济学的融合。V 神在 Youtube 上有一个名为《 The Cryptoeconomic Way 》的演讲 https://www.youtube.com/watch?v=ZH9nMKIHfAE 可以作为参考。本文内容，揉入了 Peter 自己的理解，跟 V 神的观点有差异。

先来给出加密经济学的定义：加密经济学就是用密码学和经济激励来实现去中心化系统的科学。

下面来仔细解释一下这句话。

加密经济学这里，不但使用了密码学，还同时用到了经济激励。密码学最擅长的是证实目前已有的信息的一些属性。例如，可以用数字签名来保证一段信息在某个时间点之前就存在了，而且是出于某个人之手。但是，密码学不能达成的是，让信息在未来依然能处在一个有效管理的系统内，而这就是我们为何要引入经济激励了。比特币的特点就是用经济激励的方式，让矿工有持续的动力去维护系统。而对于电子现金这样的系统，当某人已经花费了他的钱之后，系统要在未来始终保证他不能再次化这些钱了，所以也就需要有矿工去持续不断的维持一个系统，记录每个人的每时每刻的状态，如果不希望让一个老大维护系统的话，经济激励是离不了的。

总结一下，密码学可以用来保证信息的安全，而经济激励可以保证信息不依赖于权威的持续安全。加密经济学是用密码学和经济激励来达成信息安全的科学。提出加密经济学这个概念是非常有意义的，可以统一大家的愿景，共同向着一个方向努力。

## 加密经济学的目标

下面聊一下加密经济学要达成的具体目标。

第一个目标，高效的共识机制。比特币的数据安全就是基于全球的共识，因为很多人都备份了比特币账本，而且大家对正确的账目能够形成共识，才有了比特币。如果能让更多的场景在大家共同见证的前提下自动化的执行，实现没有人能够干预的自动执行的合约，这就是智能合约了。智能合约的安全基础，也是大家的共识。为了实现这个目标，大家去研究了各种共识机制，例如 POW POS POA 等等，这些都是区块链技术本身的范畴。

第二个目标，公平的市场。通过搭建各种去中心化系统，保证没有任何人有特权去作恶。实现基于代码自动化的无摩擦的市场。代码就是法律，而且是可以自动化执行的法律。实现这个目标，就不仅仅是区块链自己能够完成的了，而是要基于区块链，去升级整个互联网，让公平市场运行在下一代互联网之上。相关的研究领域包括，去中心的 ID ，去中心化的 DNS ，去中心化的数字证书等等。

总结一下这两个目标，总的思路就是基于代码去实现不受人干预的公平规则。

## 社会扩展性

最后要特别强调一个词，就是社会扩展性。加密经济学系统，例如区块链，总体的运算效率可能比一个中央服务器还要低，但是换来的最有价值的东西就是社会扩展性 Social Scalability 了。下面来详细聊聊社会扩展性。

什么是社会扩展性，我们从一个实际的创业项目来聊，例如我想要构建的是一个金融服务系统。如果用户范围很小，其实很容易做到的，大家商量一下，弄个服务器就搞定了，用不到区块链，也用不到加密经济学。但是如果我要构建的是一个跨国的大公司呢？一种可行的方案是我会跟各个国家的大机构合作，例如美联储，例如谷歌。但是问题就出来了，如果我们是谷歌员工，可能会比较相信谷歌，否则，很多人就会选择不相信谷歌，如果你身在美国，可能会对美联储有更多的信任，而其他国家的人就可能选择不信任美联储，于是创业就进行不下去了。或者说这样基于对某个个人或者组织的信任的思路，社会扩展性是很差的。

而加密经济学可以降低启动一个事业的社会成本，也就是说可以让说服其他人相信这个事业变得容易。有了加密经济学，我们构建的是一个全球化的任何人都可以自由加入的系统。而一切都只需要大家相信两点，第一，密码学是管用的。第二，人的本性是爱钱的。好，现在的情况是，密码学算法不管是不是在美国，都会安全运行。同时也不管是不是谷歌员工，是美国人还是哪里的人，大部分人都爱钱。既然这两点具有普世的可信性，也就意味着加密经济学是可以工作的。加密经济中的协议是由一种去中心化的机制，而非参与者以外的第三方来保证实施的协议，我们把它称为自我保障协议。基于加密经济学，创业的时候只需要说服大家相信密码学和人性即可，协议能够自己保障执行的，无需建立对人的信任，所以信任达成的社会成本就会很低。换句话说，就是社会扩展性良好。

所以说，加密经济学拥有良好的社会扩展性。

## 总结

关于加密经济学，总结一下，有这么几点：首先，加密经济学就是用密码学和经济激励来达成信息安全的科学。第二，加密经济学要达成的目标是，实现不受人干预的公平游戏规则。最后，加密经济学最明显的优势就是有良好的社会扩展性。

参考：

- https://zhuanlan.zhihu.com/p/44921371
- https://www.youtube.com/watch?v=ZH9nMKIHfAE
