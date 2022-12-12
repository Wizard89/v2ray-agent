# 网络差异比较大，买之前建议执行以下两个步骤
- 测试一下testIP的丢包，traceroute一下testIP的路由，是否商家宣传的一样
- 以下商家仅作为推荐，实际效果需自测
- 便宜机器都可能会出现Google人机验证问题（因为滥用），可以套warp解决（脚本中有此功能）
- 谨记一分钱一分货

<!-- more -->

# 1.CN2 GIA
## 1.推荐理由
- 可用作主力机
- 电信国际精品网络，CN2线路中的顶级产品，回程基本全部走59.43高速节点
- 线路一般比较稳定，延迟一般180ms以下，晚高峰基本上不丢包

## 2.推荐商家
### 1.[搬瓦工](https://bandwagonhost.com/aff.php?aff=60548)
- 老牌商家在vps圈声望比较高，非常稳定，补货后基本很快会被抢空
- 6.58%折扣码：BWH3HYATVBJW
- 12%优惠码：BWHNY2022


套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
CN2 GIA 限量版|1G|1核|20G|500G|1Gbps|89.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=105)
CN2 GIA|1G|2核|20G|1T|2.5Gbps|169.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=87)
HONG KONG CN2 GIA|2G|2核|40G|500G|1Gbps|$899.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=95)


### 2.Dmit
- 去程路由：电信联通走CN2 GIA，移动CMI
- 回程路由：三网CN2 GIA

套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
LosAngles PVM.LAX.Pro.TINY|1G|1核|10G|650G|500Mbps|28.88 USD/季|[购买链接](https://www.dmit.io/aff.php?aff=4996&a=add&pid=100)


# 2.联通 AS4837（普通民用网）
## 1.推荐理由
- 价格便宜，当备用机很香，晚高峰视本地网络环境不同，可能略炸
- 比如适合联通，电信尚可，一般都可以YouTube流畅1080p
- 相对其他线路比较便宜，适合对网络要求不是特别高，预算有限的用户


## 2.推荐商家

### 1.racknerd
- 流量双向计费，比如3T实际可用1.5T
- 洛杉矶动态路由，有时候会很拉垮
- sanjose大概率会跳Google人机验证，可通过warp或者任意门解锁解决此问题

套餐名称|内存|CPU| 硬盘(SSD) |流量|带宽|价格|购买链接
---|-------|---|---|---|---|---|---
512 MB KVM VPS (New Year 2022)|768M|1核| 10 GB SSD|1T|1Gbps|$9.89 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=620)
768 MB KVM VPS Special|768MB|1核| 10 GB NVMe SSD Storage           |2T|1Gbps|$11.88 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=679)
1 GB KVM VPS (New Year 2022)|1G|1核| 20 GB Pure SSD                   |2T|1Gbps|$13.98 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=621)
1 GB KVM VPS Special |1G|1核| 20 GB SSD Cached RAID-10 Storage |3T|1Gbps|$14.98 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=680)
2 GB KVM VPS Special |2G|2核| 25 GB Pure SSD                   |4T|1Gbps|$29.98 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=681)
3 GB KVM VPS (New Year 2022)|3G|1核| 50 GB Pure SSD                   |6T|1Gbps|$31.98 USD|[购买链接](https://my.racknerd.com/aff.php?aff=6384&pid=623)


### 2.dmit
- 位置：sanjose
- 流量双向计费
- 联通4837，10Gbps超大带宽
- 数据中心目前处于OpenBeta，不保证SLA
- 新购享受年付7折优惠、半年付8折优惠
- 年付七折优惠码：Lite-Annually-Recur-30OFF
- 半年付八折优惠码：Lite-Semi-Annually-Recur-20OFF

#### 非使用优惠介绍
- 如果再不使用优惠码的情况下订购年付产品可享受【买一赠一】
- 赠品第一年免费（仅限首年，这意味着赠品也要求为年付）
- 赠品可以拆分为多个订单（要求不高于原订单价格）
- 赠品可以请求创建在其他账户（工单内备注）
- 通过工单请求赠品，每个订单只允许请求一次，10月26日 23：59（UTC）之前提交工单，不支持TINY系列

套餐名称| 内存    |CPU|硬盘(SSD)|流量|带宽|价格|购买链接
---|-------|---|---|---|---|---|---
PVM.SJC.TINY| 768MB |1vCPU|10G|2T|10Gbps|$6.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=145)
PVM.SJC.STARTER| 1.5G  |1vCPU|20G|4T|10Gbps|$12.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=146)
PVM.SJC.MINI| 2G    |2vCPU|40G|6T|10Gbps|$21.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=147)
PVM.SJC.MICRO| 4G    |2vCPU|80G|8T|10Gbps|$32.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=148)
PVM.SJC.MEDIUM| 4G    |4vCPU|120G|12T|10Gbps|$49.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=149)
PVM.SJC.LARGE| 8G    |4vCPU|200G|22T|10Gbps|$99.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=150)
PVM.SJC.GIANT| 16G   |8vCPU|400G|44T|10Gbps|$199.9 USD/月|[点击购买](https://www.dmit.io/aff.php?aff=4996&a=add&pid=151)


# 4.联通 日本软银

## 1.推荐理由
- 可用作主力机
- 线路一般比较稳定，延迟一般80ms以下，晚高峰基本上不丢包

## 2.推荐商家
### 1.[搬瓦工](https://bandwagonhost.com/cart.php?aff=60548)
- 老牌商家在vps圈声望比较高，非常稳定，补货后基本很快会被抢空
- 不接受退款
- 6.58%折扣码：BWH3HYATVBJW
- location是【JP-Equinix Osaka Softbank】

套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|--|---|---|---|---
软银/CN2 GIA 限量版|1G|1核|20G|500G|1Gbps|89.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=105)
软银/CN2 GIA|1G|2核|20G|1T|2.5Gbps|169.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=87)
软银/CN2 GIA|1G|3核|40G|2T|2.5Gbps|299.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=60548&pid=88)


# 5.CMI
## 1.推荐理由
- 回程三网CMI
- 可用作主力机
- 移动国际精品网络
- 线路大多数情况下比较稳定，偶尔会被打

### 1.DMIT HongKong Lite
- [TOS](https://t.me/DMIT_INC_CN/544)
- 流量双向计费
- 去程有可能更换
- 线路实测为主
- [speedtest](http://dmit-hkg-lite.gubo.org/speedtest/)
- 测试ip：103.135.248.22

#### 去程

- 联通、电信 绕日NTT（4837->日本NTT->HK PCCW【2022-5-9】
- 移动CMI

#### 回程
- 三网CMI

#### 折扣码【仅适用于 STARTER 及以上规格的 Lite 产品，TINY 不包含在内】
- 年付七折：Lite-Annually-Recur-30OFF
- 半年付八折：Lite-Semi-Annually-Recur-20OFF



套餐名称| 内存 |CPU|硬盘(SSD)|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
PVM.HKG.Lite.TINY| 0.75G |1 vCPU|10 GB SSD|2T|1Gbps|$6.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=4996&a=add&pid=109)
PVM.HKG.Lite.STARTER| 1.5G |1 vCPU|20 GB SSD|4T|1Gbps|$12.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=4996&a=add&pid=110)
PVM.HKG.Lite.MINI| 2G |2 vCPU|40 GB SSD|6T|2Gbps|$21.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=4996&a=add&pid=111)
PVM.HKG.Lite.MICRO| 4G |2 vCPU|60 GB SSD|8T|2Gbps|$32.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=4996&a=add&pid=111)
