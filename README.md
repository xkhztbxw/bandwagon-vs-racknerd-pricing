# 搬瓦工 vs RackNerd：价格差近10倍，差价到底买什么？附两家全套餐价格表与选购建议

搜“搬瓦工 vs RackNerd”的人，多半卡在同一个问题里：RackNerd 特价款年付 $21.99 起，搬瓦工最便宜的套餐也要 $49.99/年，主力 CN2 GIA-E 更是 $169.99/年起步。差的这几倍价钱，到底差在哪，值不值。

先把结论放在前面：这不是“同类产品谁更划算”的比较。RackNerd 卖的是常规国际线路加同价位里更大的内存和硬盘；搬瓦工（BandwagonHost）卖的是针对中国大陆优化的 CN2 GIA 线路，外加一套功能相当完整的自研面板。两家都支持支付宝，但产品定位几乎不重叠。多数人的纠结，本质是“要不要为中国方向的网络质量多花钱”。

## 差价买的是什么：线路，不是配置

搬瓦工官网在 CN2 GIA 介绍页里把成本问题说得很直白：中国大陆三大运营商的普通转接线路（比如电信 AS4134/163 骨干网）便宜，但晚高峰拥堵，丢包率可以到 30% 以上；而 CN2 GIA 是电信最贵的一条通道，按兆计费最高能到 $120/Mbps，1Gbps 满配一个月的线路账单理论上接近 10 万美元。官方贴出这组数字，就是为了解释这条线路为什么不可能卖出白菜价。

RackNerd 的特价 VPS 走的是美国普通 BGP 国际线路，没有对中国大陆做专门优化。主机测评网在同价位性能对比里的总结比较到位：搬瓦工的溢价在网络线路，RackNerd 的优势在基础配置性价比，同价位下硬件性能没有绝对优劣。

所以比较这两家，其实是在比较两个问题：你的用户访问服务器走什么网络，以及你愿不愿意为晚高峰的稳定性付费。下面把两家当前在售的套餐全部列出来，数字对完，选择通常就清楚了。

## RackNerd 在售特价 VPS：配置与价格

RackNerd 的低价主力是长期挂在官网 Specials 页面的特价 KVM VPS，年付计费，无需优惠码，下单页显示多少就是多少。以下是当前官网在售的全部五档特价套餐：

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格（年付） | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1GB KVM | 1 核 | 1 GB | 20 GB | 3 TB | 1 Gbps | $21.99/年 | [ 查看 RackNerd 当前特价 VPS](https://bandwagonhost.com/aff.php?aff=79616&pid=202) |
| 2GB KVM | 2 核 | 2 GB | 35 GB | 5 TB | 1 Gbps | $35.99/年 | [ 购买 RackNerd 2GB 特价款](https://bandwagonhost.com/aff.php?aff=79616&pid=202) |
| 4GB KVM | 3 核 | 4 GB | 60 GB | 7 TB | 1 Gbps | $59.99/年 | [ 购买 RackNerd 4GB 特价款](https://bandwagonhost.com/aff.php?aff=79616&pid=202) |
| 6GB KVM | 6 核 | 6 GB | 100 GB | 12 TB | 1 Gbps | $89.99/年 | [ 购买 RackNerd 6GB 特价款](https://bandwagonhost.com/aff.php?aff=79616&pid=202) |
| 8GB KVM | 7 核 | 8 GB | 150 GB | 20 TB | 1 Gbps | $119.99/年 | [ 购买 RackNerd 8GB 特价款](https://bandwagonhost.com/aff.php?aff=79616&pid=202) |

所有特价款均为 KVM 虚拟化、RAID-10 SSD、1 个独立 IPv4，面板是 SolusVM。下单时从机房列表里选一个，当前可选洛杉矶 DC03、纽约、西雅图、圣何塞、芝加哥、达拉斯等地。

几个购买前值得知道的点：

- **特价款波动很频繁。** 此前年付 $10.60、$11.29 的更低促销档长期缺货，RackNerd 非官方中文站提到，最新补货的特价款起步价已经上调到 $21.99。也就是说上面这张表反映的是当前状态，过几个月再看可能不一样。
- **续费同价是它最大的优点之一。** 多个第三方测评都确认，RackNerd 促销价买下后按原价续费，不玩“首年低价、续费翻倍”那一套。官方博客也说明系统会在到期前 14 天生成续费账单，后台可以手动生成续费发票提前续。
- **机房开通后固定，不能在线切换。** 开通时选了哪个机房就是哪个机房，换 IP 需要提交工单；新分发的 IP 24 小时内不能用的话可以免费工单换。这一点和搬瓦工的机房自由迁移差别很大。
- **第三方普遍提醒它不支持退款。** 没有 30 天无理由退款的兜底，下单前想清楚。
- **需要 Windows 的话有单独的产品线。** RackNerd 另有 Ryzen 加 NVMe 的 Windows VPS 系列，2GB 内存款月付 $27.59 起，和上表的 Linux 特价款是两条产品线。

如果你就是想要一台便宜的测试机、爬虫机或者面向海外用户的小服务，可以直接[👉 查看 RackNerd 全部在售特价套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=202)，五档配置都在同一个页面上。

## 搬瓦工全套餐价格表（当前官网在售）

搬瓦工的产品线比 RackNerd 复杂，按线路和定位分成几个系列。以下价格取自官方购物车当前展示，全部为美元计费：

### KVM 常规套餐：入门和纯海外业务

普通国际线路，没有针对大陆优化，适合练手、学习 Linux 和面向海外用户的项目。

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM | 2 核 | 1 GB | 20 GB | 1 TB | 1 Gbps | $49.99/年 | [ 购买 20G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| 40G KVM | 3 核 | 2 GB | 40 GB | 2 TB | 1 Gbps | $52.99/半年，$99.99/年 | [ 购买 40G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| 80G KVM | 4 核 | 4 GB | 80 GB | 3 TB | 1 Gbps | $19.99/月，$199.99/年 | [ 购买 80G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| 160G KVM | 5 核 | 8 GB | 160 GB | 4 TB | 1 Gbps | $39.99/月，$399.99/年 | [ 购买 160G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| 320G KVM | 6 核 | 16 GB | 320 GB | 5 TB | 1 Gbps | $79.99/月，$799.99/年 | [ 购买 320G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| 480G KVM | 7 核 | 24 GB | 480 GB | 6 TB | 1 Gbps | $119.99/月，$1199.99/年 | [ 购买 480G KVM 常规款](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

这个系列可以在洛杉矶 DC2/DC8 等多个机房间迁移。老用户嘴里的“限量版”“传家宝”是指官方偶尔放出的低价特殊规格，缺货是常态，蹲到补货就值，但不建议把购买决策建立在蹲补货上。

### CN2 GIA-E 套餐：搬瓦工的主力产品

绝大多数人选搬瓦工，买的就是这个系列。三网 CN2 GIA 方向优化，官方购物车标注 10 多个电商级机房可自由切换，包括洛杉矶 DC6/DC9 和大阪软银 JPOS_1 等位置，切换不掉数据。

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G CN2 GIA-E | 2 核 | 1 GB | 20 GB | 1 TB | 2.5 Gbps | $49.99/季，$169.99/年 | [ 购买 20G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| 40G CN2 GIA-E | 3 核 | 2 GB | 40 GB | 2 TB | 2.5 Gbps | $89.99/季，$299.99/年 | [ 购买 40G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| 80G CN2 GIA-E | 4 核 | 4 GB | 80 GB | 3 TB | 2.5 Gbps | $56.99/月，$549.99/年 | [ 购买 80G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| 160G CN2 GIA-E | 6 核 | 8 GB | 160 GB | 5 TB | 5 Gbps | $86.99/月，$879.99/年 | [ 购买 160G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| 320G CN2 GIA-E | 8 核 | 16 GB | 320 GB | 8 TB | 5 Gbps | $159.99/月 | [ 购买 320G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| 640G CN2 GIA-E | 10 核 | 32 GB | 640 GB | 10 TB | 10 Gbps | $289.99/月 | [ 购买 640G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| 1280G CN2 GIA-E | 12 核 | 64 GB | 1280 GB | 12 TB | 10 Gbps | $549.99/月 | [ 购买 1280G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |
| 1280G HICPU | 24 核 | 64 GB | 1280 GB | 12 TB | 10 Gbps | $749.99/月 | [ 购买 1280G HICPU 高CPU款](https://bandwagonhost.com/aff.php?aff=79616&pid=148) |

入门款 $49.99/季折算全年约 $169.99。拿它和 RackNerd 1GB 特价款一比，价差是 7 倍多；如果拿 RackNerd 更早的 $10.60 促销款来比，倍数还能翻上去，这就是网上“价格差 10 倍”说法的来源。多出来的钱买的不是内存和硬盘，是晚高峰依然稳定的回国路由。

### ECOMMERCE SLA 套餐：洛杉矶 DC5，带赔付协议

CN2 GIA-E 的强化版，独享 AMD 核心、ECC 内存、NVMe 硬盘，官方承诺 99.99% SLA 在线率，达不到按协议赔付，并且每两周可以免费更换一次 IP。

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G SLA | 2 核独享 | 1 GB | 20 GB | 1 TB | 2.5 Gbps | $65.89/季，$239.99/年 | [ 购买 20G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| 40G SLA | 3 核独享 | 2 GB | 40 GB | 2 TB | 2.5 Gbps | $116.99/季，$399.99/年 | [ 购买 40G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| 80G SLA | 4 核独享 | 4 GB | 80 GB | 3 TB | 2.5 Gbps | $69.99/月，$699.99/年 | [ 购买 80G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| 160G SLA | 6 核独享 | 8 GB | 160 GB | 5 TB | 5 Gbps | $109.99/月 | [ 购买 160G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| 320G SLA | 8 核独享 | 16 GB | 320 GB | 8 TB | 5 Gbps | $199.99/月 | [ 购买 320G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| 640G SLA | 10 核独享 | 32 GB | 640 GB | 10 TB | 10 Gbps | $369.99/月 | [ 购买 640G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| 1280G SLA | 12 核独享 | 64 GB | 1280 GB | 12 TB | 10 Gbps | $699.99/月 | [ 购买 1280G ECOMMERCE SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| 1280G SLA 15TB | 12 核独享 | 64 GB | 1280 GB | 15 TB | 10 Gbps | $879.99/月 | [ 购买 1280G SLA 15TB](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| 1280G SLA 20TB | 12 核独享 | 64 GB | 1280 GB | 20 TB | 10 Gbps | $1159.99/月 | [ 购买 1280G SLA 20TB](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

这个系列面向跨境电商这类掉线就等于掉钱的业务，普通用户用不到，看看就好。

### 亚太 CN2 GIA：大阪、东京、香港、新加坡

都是 CN2 GIA 高端线路，价格按月计，年付有折扣。适合对延迟极度敏感的场景。

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 大阪 CN2 GIA 40G | 2 核 | 2 GB | 40 GB | 500 GB | 1.5 Gbps | $49.99/月，$499.99/年 | [ 购买大阪 CN2 GIA 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=134) |
| 大阪 CN2 GIA 80G | 4 核 | 4 GB | 80 GB | 1 TB | 1.5 Gbps | $86.99/月，$869.99/年 | [ 购买大阪 CN2 GIA 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=135) |
| 大阪 CN2 GIA 160G | 6 核 | 8 GB | 160 GB | 2 TB | 1.5 Gbps | $165.99/月 | [ 购买大阪 CN2 GIA 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=136) |
| 大阪 CN2 GIA 320G | 8 核 | 16 GB | 320 GB | 4 TB | 1.5 Gbps | $329.99/月 | [ 购买大阪 CN2 GIA 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=137) |
| 大阪 CN2 GIA 640G | 10 核 | 32 GB | 640 GB | 6 TB | 1.5 Gbps | $549.99/月 | [ 购买大阪 CN2 GIA 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=138) |
| 大阪 CN2 GIA 1280G | 12 核 | 64 GB | 1280 GB | 8 TB | 1.5 Gbps | $1059.99/月 | [ 购买大阪 CN2 GIA 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=139) |
| 东京 CN2 GIA 40G | 2 核 | 2 GB | 40 GB | 500 GB | 1.2 Gbps | $89.99/月，$899.99/年 | [ 购买东京 CN2 GIA 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=108) |
| 东京 CN2 GIA 80G | 4 核 | 4 GB | 80 GB | 1 TB | 1.2 Gbps | $155.99/月，$1559.99/年 | [ 购买东京 CN2 GIA 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=109) |
| 东京 CN2 GIA 160G | 6 核 | 8 GB | 160 GB | 2 TB | 1.2 Gbps | $299.99/月 | [ 购买东京 CN2 GIA 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=110) |
| 东京 CN2 GIA 320G | 8 核 | 16 GB | 320 GB | 4 TB | 1.2 Gbps | $589.99/月 | [ 购买东京 CN2 GIA 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=111) |
| 东京 CN2 GIA 640G | 10 核 | 32 GB | 640 GB | 6 TB | 1.2 Gbps | $989.99/月 | [ 购买东京 CN2 GIA 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=123) |
| 东京 CN2 GIA 1280G | 12 核 | 64 GB | 1280 GB | 8 TB | 1.2 Gbps | $1889.99/月 | [ 购买东京 CN2 GIA 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=125) |
| 香港 CN2 GIA 40G | 2 核 | 2 GB | 40 GB | 500 GB | 1 Gbps | $89.99/月，$899.99/年 | [ 购买香港 CN2 GIA 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=95) |
| 香港 CN2 GIA 80G | 4 核 | 4 GB | 80 GB | 1 TB | 1 Gbps | $155.99/月，$1559.99/年 | [ 购买香港 CN2 GIA 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=96) |
| 香港 CN2 GIA 160G | 6 核 | 8 GB | 160 GB | 2 TB | 1 Gbps | $299.99/月 | [ 购买香港 CN2 GIA 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=97) |
| 香港 CN2 GIA 320G | 8 核 | 16 GB | 320 GB | 4 TB | 1 Gbps | $589.99/月 | [ 购买香港 CN2 GIA 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=98) |
| 香港 CN2 GIA 640G | 10 核 | 32 GB | 640 GB | 6 TB | 1 Gbps | $989.99/月 | [ 购买香港 CN2 GIA 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=122) |
| 香港 CN2 GIA 1280G | 12 核 | 64 GB | 1280 GB | 8 TB | 1 Gbps | $1889.99/月 | [ 购买香港 CN2 GIA 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=124) |
| 新加坡 CN2 GIA 40G | 2 核 | 2 GB | 40 GB | 500 GB | 1.5 Gbps | $49.99/月，$499.99/年 | [ 购买新加坡 CN2 GIA 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=173) |
| 新加坡 CN2 GIA 80G | 4 核 | 4 GB | 80 GB | 1 TB | 1.5 Gbps | $86.99/月，$869.99/年 | [ 购买新加坡 CN2 GIA 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=174) |
| 新加坡 CN2 GIA 160G | 6 核 | 8 GB | 160 GB | 2 TB | 2.5 Gbps | $165.99/月 | [ 购买新加坡 CN2 GIA 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=175) |
| 新加坡 CN2 GIA 320G | 8 核 | 16 GB | 320 GB | 4 TB | 2.5 Gbps | $329.99/月 | [ 购买新加坡 CN2 GIA 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=176) |
| 新加坡 CN2 GIA 640G | 10 核 | 32 GB | 640 GB | 6 TB | 5 Gbps | $549.99/月 | [ 购买新加坡 CN2 GIA 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=177) |
| 新加坡 CN2 GIA 1280G | 12 核 | 64 GB | 1280 GB | 8 TB | 5 Gbps | $1059.99/月 | [ 购买新加坡 CN2 GIA 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=178) |

大阪和新加坡的 40G 款年付 $499.99，折合每月约 $41.7，比东京和香港便宜四成多，是“想要亚太低延迟但预算到不了 900 刀”的位置。另外，CN2 GIA-E 套餐本身就能切到大阪软银 JPOS_1 机房，联通用户常被推荐这么用，不必单独买亚太款。

### 迪拜套餐：特殊区域，顺手一提

| 套餐 | CPU | 内存 | SSD | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DUBAI 20G | 2 核 | 1 GB | 20 GB | 500 GB | 1 Gbps | $19.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 40G | 3 核 | 2 GB | 40 GB | 1 TB | 1 Gbps | $32.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 80G | 4 核 | 4 GB | 80 GB | 2 TB | 1 Gbps | $56.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 160G | 6 核 | 8 GB | 160 GB | 3 TB | 1 Gbps | $86.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 320G | 8 核 | 16 GB | 320 GB | 4 TB | 1 Gbps | $159.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 640G | 10 核 | 32 GB | 640 GB | 5 TB | 1 Gbps | $289.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |
| DUBAI 1280G | 12 核 | 64 GB | 1280 GB | 6 TB | 1 Gbps | $549.99/月 | [ 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost) |

业务真在中东再考虑它，其他场景基本用不上。这套表格没有可核验的独立套餐编号，所以统一指向套餐总页。想自己翻完整列表，可以[👉 前往搬瓦工官网查看全部在售套餐](https://bit.ly/BandwagonHost)。

## 面板和日常功能：KiwiVM 对 SolusVM

两家面板的差距比价格差距更具体。搬瓦工的 KiwiVM 是自研面板，官方购物车页面明确列了每款套餐自带的功能：免费自动备份、免费快照、机房之间免费自动迁移、面板内一键设置 rDNS、API 接口，还支持手动挂 ISO 安装系统。备份和快照意味着你把网站搬走或重装时有一条退路。

RackNerd 用的是行业里常见的 SolusVM，开关机、重装系统、看流量都够用，rDNS 也能设置，但没有自动备份和快照。老梁的学习笔记在对比里专门点过这一条：RackNerd 功能少，没有自动备份和镜像，系统支持范围也窄一些。数据安全完全靠自己，用惯了搬瓦工的人切过去会有明显落差。

## 退款、续费和优惠码现状

这是两家差异最大、竞品文章经常讲含糊的部分，直接列清楚：

| 政策 | 搬瓦工 | RackNerd |
| --- | --- | --- |
| 退款 | 30 天内可申请，条件是账户下 VPS 少于 3 台、总支付额低于 100 美元；退款会清空账户下所有服务 | 特价款无退款政策，第三方教程普遍提醒当一次性决策对待 |
| 续费 | 按套餐当期售价续费，第三方记录的 CN2 GIA-E 续费口径为 $169.99/年 | 促销价续费同价，不涨价，可提前生成账单续费 |
| 付款方式 | 支付宝、微信、PayPal、信用卡 | 支付宝、PayPal、信用卡 |

搬瓦工的 30 天退款是老用户公认的试错空间，但注意它不退“其中一台”，申请后账号下所有 VPS 一起清掉，动手前先备份。RackNerd 虽然不退款，好在最低一档只有二十来美元，试错成本本身不高。

搬瓦工的优惠码目前没有官方长期码，第三方优惠信息站的口径不一：有站点称暂时无可用码、原价下单即可，也有中文站流传 6.58% 至 6.77% 的循环折扣码。这类码的可用性随官方活动波动，结账时输一下能折就折，不能折也别为它等。

## 按场景选：直接给答案

- **建站给国内用户访问，晚高峰要稳**：搬瓦工 CN2 GIA-E 入门款，$169.99/年，这条线就是为这个场景存在的。
- **测试机、爬虫、挂脚本、纯海外业务**：RackNerd 1GB 或 2GB 特价款，一年二三十美元，配置比同价位的搬瓦工 KVM 大一截。
- **业务掉线就亏钱**：搬瓦工 ECOMMERCE SLA 系列，99.99% 在线率写进协议，每两周还能免费换 IP。
- **数据重要、不想折腾备份**：搬瓦工，KiwiVM 的自动备份和快照是 RackNerd 没有的。
- **需要 Windows**：RackNerd 的 Windows VPS 产品线（Ryzen 加 NVMe，$27.59/月起）；搬瓦工不支持直接装 Windows。
- **预算紧到极限**：RackNerd 的历史促销款年付 $10 出头，缺货时蹲补货也比勉强买贵的好。

## 常见问题

**RackNerd 为什么能卖这么便宜？** 从产品结构就能看出来：机房是常规 BGP 线路，没有 CN2 GIA 这种昂贵的中国方向传输成本，再靠大流量促销走量。省下的线路钱反映在了价格上。

**RackNerd 适合建站吗？** 面向海外访客没问题，KVM 架构加独立 IPv4 都是标准配置。面向国内访客就要掂量：没有大陆优化线路，晚高峰的延迟和丢包全看当时路由，这一点多个第三方测评结论一致。

**搬瓦工为什么贵这么多？** 因为 CN2 GIA 线路本身贵。官方给出的采购价是最高 $120/Mbps，这是一条面向企业级的通道，个人用户以 $169.99/年 分摊，在同类优化线路产品里其实不算离谱。

**买了能退吗？** 搬瓦工 30 天内、满足账户条件可以全额退；RackNerd 没有退款政策，买前想清楚。

**续费会不会涨价？** RackNerd 促销价续费同价，这是它的招牌；搬瓦工按当期套餐价续费，如果官方调价，续费价跟着走。

**两家都支持支付宝吗？** 都支持。搬瓦工还多微信和信用卡，RackNerd 支持支付宝和 PayPal。

## 最后小结

搬瓦工 vs RackNerd 的比较，本质是“线路质量”和“硬件性价比”二选一。RackNerd 用最少的钱给你够用的配置，代价是普通线路、不能换机房、没有备份；搬瓦工用高出一大截的价格给你 CN2 GIA 线路、KiwiVM 面板和 30 天退款。想清楚你的服务器为谁服务，答案自然就出来了。如果两边的套餐都想再核对一遍，可以[👉 选购搬瓦工在售全部套餐](https://bit.ly/BandwagonHost)，或者[👉 查看 RackNerd 当前全部特价 VPS](https://bandwagonhost.com/aff.php?aff=79616&pid=202)，下单前把页面价格和库存再确认一次。
