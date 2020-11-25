---
title: blockchain
weight: 1
---

# bitcoin_0_2_10

## bitoin 0.2.10版本，做了一些修改

* mac下make -f makefile.osx可运行，其他环境未尝试
* 修改初始的nBits，大概一百万次找到一个nNonce
* 注释irc
* 修改增加-port，可以本地组成网络
* 增加一些日志查看
* 修改wxdgets的一些页面，便于查看
* tx详情展示完整信息
* TODO:增加本地钱包的秘钥查看

# 比特币0.2.10代码解析

## [前言](./start)
## [项目运行](./running)
## [项目框架](./arc)
## [比特币的一些疑惑](./questions)
***
* [x]  [节点管理](./nodes)
* [x]  [数据同步](./data_sync)
* [x]  [挖矿过程](./miner)
* [ ]  [存储](./db)
* [x]  [余额](./balance)
* [x]  [交易流程](./transaction)
* [ ]  [默克尔树](./merkle)

