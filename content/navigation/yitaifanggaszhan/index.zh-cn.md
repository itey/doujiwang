﻿---
weight: 
title: "以太坊gas站"
description: "以太坊gas站旨在提高以太坊网络的gas价格，交易确认时间和矿工政策的透明度"
date: 2022-07-12T21:57:40+08:00
lastmod: 2022-07-12T16:45:40+08:00
draft: false
authors: ["yangsi"]
featuredImage: "yitaifanggaszhan.png"
link: "https://etherchain.org/tools/gasnow    https://www.jianshu.com/p/eacbb32d2991"
tags: ["数据分析","以太坊gas站"]
categories: ["navigation"]
navigation: ["数据分析"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---
以太坊gas站旨在提高以太坊网络的gas价格，交易确认时间和矿工政策的透明度。

以太坊的 Gas 费是以太坊网络的动力，就像汽油是汽车的动力一样。我们普通用户参与到区块链中，无论是交易 Token，还是使用区块链上的去中心化应用程序（编写成智能合约），Gas 费都是一道绕不过去的坎。

Gas 是指在以太坊网络上执行特定操作所需的计算工作量。

由于每笔以太坊交易都需要计算资源才能执行，每笔交易都需要付费。 在这个方面上，Gas 是指在以太坊成功进行交易所需的费用。

 ![Gas fee = Gas Price * Gas Used（Gas 费 = Gas 价格 * Gas 使用量）](https://math.jianshu.com/math?formula=Gas%20fee%20%3D%20Gas%20Price%20*%20Gas%20Used%EF%BC%88Gas%20%E8%B4%B9%20%3D%20Gas%20%E4%BB%B7%E6%A0%BC%20*%20Gas%20%E4%BD%BF%E7%94%A8%E9%87%8F%EF%BC%89)

 Gas 费用是以太坊的货币 ETH 支付的，单位是 Gwei，1 Gwei = 0.000000001 ETH = 10 的 -9 次方 ETH

Gas Price: 用户愿意为每个 Gas 支付的价格，是由用户自己竞价。

Gas Used: 是用户执行操作消耗的 Gas 总量，是固定数额，ETH 转账为 21000，其他 ERC20 代币因为是智能合约，一般比 21000 贵，具体由智能合约代码复杂度决定。

正如你开汽车需要汽油，运行应用程序（交易 ETH、部署合约）需要 Gas。

消耗 Gas 的量是固定，但是 Gas 的单价是波动的。比如说汽车要跑 20KM 需要 1 升汽油，但是加油站汽油多的时候，1 升汽油的价格是 10 美金，但是加油站汽油不足的时候，1 升汽油的价格可能是 100美金。对应到以太坊网络，网络不拥堵的时候，Gas fee 会比较低；网络拥堵的时候，Gas fee 可能会非常的高。

**为什么要有 Gas**

以太坊就像手机的安卓系统，你在上面给别人发信息（转账）、拍照存储照片（存储）、安装软件（部署智能合约），都需要花费一定的费用（Gas 费）。

我们都知道，免费容易导致泛滥和不规范，收费的社区和不收费的社区，质量和服务是完全不一样的。Gas 的存在，可以保护以太坊网络的安全，假如说没有 Gas 费，大家都可以去上面交易和执行计算，就会产生垃圾信息和浪费资源。有 Gas 费，作恶的成本就会上升，理性的情况下，没有人愿意花钱干一件对自己没有任何意义的事情。

以太坊是去中心化的网络，需要保证网络的安全和运行，还要保证有人去记录交易，那大家为什么愿意去干这个事情呢？这就是矿工做的事情，矿工挖矿得到记账权，会得到系统自动发的 ETH 的奖励，同时每笔交易都有一个手续费（Gas 费）。有记账权矿工的收益 = 挖矿得到的 ETH + 记账手续费（Gas 费）。

BTC 的总量是固定的，为 2100 万枚。但是 ETH 没有固定上限，那怎么保证它的数量不会太多而发生贬值呢？这也是 Gas 的一个功能，Gas 是使用 ETH 来付费的，手续费中的 Base 部分，会被销毁（所谓的销毁，就是把币转到一个黑洞地址，谁都没有私钥，这部分币会永远退出流动性，不能进行交易）。这样就保证了流通中的 ETH 不会只增无减。

稍微总结一下：Gas 费能够激励人们去维护以太坊网络的安全，防止产生过多的垃圾信息；同时交易有 Gas 费，大家都争着去记账；Gas 费中的大部分会被销毁，以维持流通中 ETH 的数量不会过高。

