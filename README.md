# dmit便宜套餐到底多少钱：$36.90/年的 WEE 够干什么？香港节点为什么不一定更快？优惠码对最便宜那档有用吗？（附三机房全套餐价格表）

DMIT 全线最便宜的套餐是洛杉矶的 **LAX.AN4.T1.WEE，$36.90/年**，折合每月约 $3.1，配置 1 核 / 1GB 内存 / 20GB SSD / 每月 1000GB 流量。它走国际线路，没有中国大陆优化，这一点既决定了它为什么便宜，也决定了它不适合哪些人。

下面把三个机房、三条产品线的最低门槛全部列清楚：最便宜那台能干什么，想留中国大陆优化要多花多少钱，以及最容易白花钱的几个地方。

> **选购速览**
> - 只要一台便宜机器跑脚本、做落地、当测试环境 → **LAX.AN4.T1.WEE，$36.90/年**
> - 要中国大陆优化，又不想上 Pro → **LAX.AN4.EB.TINY，$88.88/年**（年付 8 折码验证后约 $71.1/年）
> - 要 20–50ms 的低延迟 → 香港 Pro 从 $39.90/月 起，这已经不是“便宜”选项了
>
> 👉 [以 $36.90/年 查看 WEE 当前库存](https://www.dmit.io/aff.php?aff=9081&pid=71)

## WEE 这台机器，$36.90 买的是什么

1 核 CPU、1GB 内存、20GB SSD、1000GB 月流量，年付 $36.90。KVM 虚拟化，独立内核，可以自己换内核开 BBR，这一点比同价位常见的 OpenVZ 共享内核机器实在。

流量跑完不会停机，自动限速继续跑，月初流量重置后恢复原速。这个设计对挂机、跑同步、做备份中转的人很实用，不用担心某天突然断服。

三个机房的 T1 系列都有同价 WEE：洛杉矶 `pid=71`、香港 `pid=197`、东京 `pid=228`，都是 $36.90/年。香港和东京的 T1 往上还有 MEDIUM、LARGE、GIANT 大档位，洛杉矶的 T1 高配则走 AN5 VOLUME 和 AN4 GENERAL 两个大流量系列，配置和价格见下面的表。

WEE 属于常缺货的档位，补货没有固定时间表。三机房同价，如果 LAX 没货，HKG 或 TYO 的 WEE 可以直接顶上，除非你的业务必须用美国 IP。

## 全套餐价格表

以下价格来自官网套餐页的整理版本，页面自标“2026 年 4 月最新”。现在是 2026 年 11 月，中间隔了大半年，**下单前务必以官网购物车实时显示为准**，库存同理。

### 洛杉矶 LAX — T1 国际线路（入门年付首选）

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| WEE | 1核 / 1GB | 20GB | 1000GB | $36.90/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=71) |
| TINY | 1核 / 1GB | 20GB | 2000GB | $6.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=116) |
| STARTER | 2核 / 2GB | 40GB | 4000GB | $12.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=117) |
| MINI | 2核 / 4GB | 80GB | 8000GB | $21.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=118) |
| MICRO | 4核 / 4GB | 120GB | 16000GB | $32.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=119) |

**LAX.AN5.T1 VOLUME 大流量系列**（AMD EPYC 9005，10Gbps 口）

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| V2C2G | 2核 / 2GB | 40GB | 5000GB | $14.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=169) |
| V2C4G | 2核 / 4GB | 80GB | 10000GB | $23.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=170) |
| V4C4G | 4核 / 4GB | 120GB | 20000GB | $36.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=171) |
| V4C8G | 4核 / 8GB | 160GB | 40000GB | $52.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=180) |
| V8C16G | 8核 / 16GB | 240GB | 80000GB | $119.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=172) |
| V12C24G | 12核 / 24GB | 320GB | 160000GB | $199.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=173) |

**LAX.AN4.T1 GENERAL 系列**（10Gbps 口）

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| G2C4G | 2核 / 4GB | 80GB | 4000GB | $16.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=234) |
| G4C8G | 4核 / 8GB | 160GB | 8000GB | $36.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=235) |
| G8C16G | 8核 / 16GB | 320GB | 12000GB | $79.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=236) |
| G12C24G | 12核 / 24GB | 480GB | 240000GB | $119.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=174) |
| G16C32G | 16核 / 32GB | 640GB | 320000GB | $199.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=175) |

### 洛杉矶 LAX — Pro 系列（三网 CN2 GIA）

**LAX.AN4.Pro**（AMD EPYC 9004）

| 套餐 | CPU / 内存 | 硬盘 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB | 20GB | 1000GB / 1Gbps | $88.88/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=237) |
| Pocket | 2核 / 2GB | 40GB | 1500GB / 4Gbps | $159.98/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=238) |
| STARTER | 2核 / 2GB | 80GB | 3000GB / 10Gbps | $29.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=239) |
| MINI | 4核 / 4GB | 80GB | 5000GB / 10Gbps | $58.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=240) |
| MICRO | 4核 / 4GB | 160GB | 7000GB / 10Gbps | $74.99/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=241) |
| MEDIUM | 6核 / 8GB | 160GB | 15000GB / 10Gbps | $168.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=242) |
| LARGE | 8核 / 16GB | 320GB | 25000GB / 10Gbps | $338.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=243) |
| GIANT | 12核 / 24GB | 640GB | 50000GB / 10Gbps | $619.99/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=244) |

**LAX.AN5.Pro**（AMD EPYC 9005，单核跑分约 2770）

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB | 20GB | 1000GB | $119.99/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=100) |
| Pocket | 2核 / 2GB | 40GB | 1500GB | $203.90/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=137) |
| STARTER | 2核 / 2GB | 80GB | 3000GB | $38.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=56) |
| MINI | 4核 / 4GB | 80GB | 5000GB | $76.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=58) |
| MICRO | 4核 / 4GB | 160GB | 7000GB | $99.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=81) |
| MEDIUM | 6核 / 8GB | 160GB | 15000GB | $219.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=82) |
| LARGE | 8核 / 16GB | 320GB | 25000GB | $2759.40/半年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=61) |
| GIANT | 12核 / 24GB | 640GB | 50000GB | $839.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=98) |

AN5.Pro 的 LARGE 一档是**半年付**口径，不是月价，两处来源的记录也不完全一致，真要买这档请直接看购物车。

### 洛杉矶 LAX — Eyeball 系列（AS9929 + CMIN2）

**LAX.AN4.EB**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB | 20GB | 1500GB / 2Gbps | $88.88/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=245) |
| Pocket | 2核 / 2GB | 40GB | 3000GB / 4Gbps | $159.98/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=246) |
| STARTER | 2核 / 2GB | 80GB | 5000GB / 10Gbps | $29.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=247) |
| MINI | 4核 / 4GB | 80GB | 10000GB / 10Gbps | $58.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=248) |
| MICRO | 4核 / 4GB | 160GB | 14000GB / 10Gbps | $74.99/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=249) |
| MEDIUM | 6核 / 8GB | 160GB | 30000GB / 10Gbps | $168.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=250) |
| LARGE | 8核 / 16GB | 320GB | 50000GB / 10Gbps | $338.88/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=251) |
| GIANT | 12核 / 24GB | 640GB | 100000GB / 10Gbps | $619.99/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=252) |

**LAX.AN5.EB**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB | 20GB | 1500GB | $119.99/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=189) |
| Pocket | 2核 / 2GB | 40GB | 3000GB | $203.90/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=190) |
| STARTER | 2核 / 2GB | 80GB | 5000GB | $38.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=191) |
| MINI | 4核 / 4GB | 80GB | 10000GB | $76.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=192) |
| MICRO | 4核 / 4GB | 160GB | 14000GB | $99.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=193) |
| MEDIUM | 6核 / 8GB | 160GB | 30000GB | $219.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=194) |
| LARGE | 8核 / 16GB | 320GB | 50000GB | $2759.40/半年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=195) |
| GIANT | 12核 / 24GB | 640GB | 100000GB | $839.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=196) |

### 中国香港 HKG

**HKG Pro（三网 CN2 GIA，1Gbps）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB | 20GB | 500GB | $39.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=123) |
| STARTER | 1核 / 2GB | 40GB | 1000GB | $79.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=124) |
| MINI | 2核 / 2GB | 60GB | 1500GB | $119.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=125) |
| MICRO | 4核 / 4GB | 80GB | 2000GB | $159.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=126) |
| MEDIUM | 4核 / 8GB | 160GB | 2500GB | $179.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=127) |
| LARGE | 8核 / 16GB | 320GB | 3000GB | $239.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=128) |
| GIANT | 8核 / 24GB | 640GB | 6000GB | $499.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=129) |

**HKG Eyeball（三网 CMI）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINYv2 | 1核 / 1GB | 20GB | 1000GB / 1Gbps | $29.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=210) |
| STARTERv2 | 1核 / 2GB | 40GB | 2000GB / 2Gbps | $59.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=211) |
| MINIv2 | 2核 / 2GB | 60GB | 3000GB / 2Gbps | $89.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=212) |
| MICROv2 | 4核 / 4GB | 80GB | 4000GB / 4Gbps | $129.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=213) |
| MEDIUMv2 | 4核 / 8GB | 160GB | 6000GB / 4Gbps | $199.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=214) |
| LARGEv2 | 8核 / 16GB | 320GB | 12000GB / 4Gbps | $389.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=215) |
| GIANTv2 | 8核 / 24GB | 640GB | 24000GB / 4Gbps | $789.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=216) |

**HKG T1（无中国大陆优化）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| WEE | 1核 / 1GB | 20GB | 1000GB | $36.90/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=197) |
| TINY | 1核 / 1GB | 20GB | 2000GB | $6.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=198) |
| STARTER | 1核 / 2GB | 40GB | 4000GB | $12.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=199) |
| MINI | 2核 / 2GB | 60GB | 8000GB | $21.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=200) |
| MICRO | 4核 / 4GB | 80GB | 16000GB | $32.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=201) |
| MEDIUM | 4核 / 8GB | 160GB | 32000GB | $49.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=202) |
| LARGE | 8核 / 16GB | 320GB | 64000GB | $99.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=203) |
| GIANT | 8核 / 24GB | 640GB | 128000GB | $199.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=204) |

### 日本东京 TYO

**TYO Pro（三网 CN2 GIA，1Gbps）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB | 20GB | 500GB | $21.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=138) |
| STARTER | 1核 / 2GB | 40GB | 1000GB | $39.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=139) |
| MINI | 2核 / 2GB | 60GB | 2000GB | $79.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=140) |
| MICRO | 4核 / 4GB | 80GB | 4000GB | $159.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=141) |
| MEDIUM | 4核 / 8GB | 160GB | 5000GB | $259.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=142) |
| LARGE | 8核 / 16GB | 320GB | 8000GB | $429.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=143) |
| GIANT | 8核 / 24GB | 640GB | 15000GB | $799.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=144) |

**TYO Eyeball（三网 CMI）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB | 20GB | 1000GB / 1Gbps | $25.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=221) |
| STARTER | 1核 / 2GB | 40GB | 2000GB / 2Gbps | $55.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=222) |
| MINI | 2核 / 2GB | 60GB | 3000GB / 2Gbps | $85.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=223) |
| MICRO | 4核 / 4GB | 80GB | 4000GB / 4Gbps | $119.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=224) |
| MEDIUM | 4核 / 8GB | 160GB | 6000GB / 4Gbps | $179.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=225) |
| LARGE | 8核 / 16GB | 320GB | 12000GB / 4Gbps | $369.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=226) |
| GIANT | 8核 / 24GB | 640GB | 24000GB / 4Gbps | $749.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=227) |

**TYO T1（无中国大陆优化）**

| 套餐 | CPU / 内存 | 硬盘 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| WEE | 1核 / 1GB | 20GB | 1000GB | $36.90/年 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=228) |
| TINY | 1核 / 1GB | 20GB | 2000GB | $6.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=131) |
| STARTER | 1核 / 2GB | 40GB | 4000GB | $12.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=132) |
| MINI | 2核 / 2GB | 60GB | 8000GB | $21.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=133) |
| MICRO | 4核 / 4GB | 80GB | 16000GB | $32.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=134) |
| MEDIUM | 4核 / 8GB | 160GB | 32000GB | $49.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=135) |
| LARGE | 8核 / 16GB | 320GB | 64000GB | $99.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=136) |
| GIANT | 8核 / 24GB | 640GB | 128000GB | $199.90/月 | [选此方案](https://www.dmit.io/aff.php?aff=9081&pid=229) |

## “便宜”的三层账：年付差价、优惠码、续费

**第一层，年付和月付的价差。** WEE 是 $36.90/年，平均每月约 $3.1；同机房配置最接近的 TINY 是 $6.90/月，一年 $82.80。两者差价 $45.90，TINY 的月流量是 2000GB，WEE 是 1000GB。换句话说，多付 1.24 倍的钱，换来每月多 1TB 流量，单位流量成本其实降下来了。所以：

- 流量吃紧、要长期跑 → TINY 月付或季付更划算
- 只是偶尔用、跑个小脚本 → WEE 的年付单价没人能打

**第二层，优惠码对最便宜这档基本无效。** 这是最容易做无用功的地方。现有资料里，洛杉矶 T1 系列没有任何可用优惠码，$36.90 就是实付价；香港和东京 T1 有 7 折循环码 `202510_HKG_TYO_T1_30OFF_RECURRING`，但适用范围明确写着“不含 WEE”。所以等一个码再买 WEE，等不到。

想把码用上，起点得从 TINY 开始。以香港 T1 TINY 为例，$6.90/月，季付原价 $20.70，7 折后 $14.49/季，一年下来约 $57.96，换来 2000GB/月流量。比 WEE 贵，但流量翻倍。这类码名称里带“2025”“202510”，属于阶段性活动码，**下单前必须在结算页的 Promotion Code 框里点 Validate Code 验证**，不生效就换回原方案，别硬凑。

洛杉矶 EB 系列的 `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` 是另一回事，它作用于 $88.88/年 的 EB TINY，8 折后约 $71.10/年，这是目前能用码拿到的最低大陆优化价格。码名带 RECURRING，字面上是循环折扣，续费同折，但官方条款里没有逐字确认，续费时以账单为准。

**第三层，续费和换机房。** 资料里同款套餐只给了一个标价，没有区分首期价与续费价，也没看到涨价条款，所以这里不编涨幅。唯一确定的是：**机房之间不支持迁移**，买了香港想换洛杉矶，只能重新买一台，数据自己搬。第一次买，先想清楚落在哪个机房。

## T1 能干什么，不能干什么

T1 是国际线路，没有中国大陆方向的专门优化。这意味着：

**能干的**：跑脚本、做定时任务、当开发测试环境、做海外业务的前端或反代、当落地节点、做大流量下载和备份中转。AN5 VOLUME 系列 10Gbps 口、5000GB 起步的流量，$14.90/月，这类活儿它很合适。

**不能干的**：面向中国大陆用户的网站、API、需要实时响应的应用。不是因为慢到不能用，而是你花了钱还得忍受晚高峰的抖动，不如直接上 EB 或 Pro。

这里有个反复有人踩的坑：**香港 T1 对国内用户不一定更快。** 香港 Pro 的 20–50ms 是 CN2 GIA 带来的，T1 走的是国际路由，国内访问这个节点，延迟可能比洛杉矶 Pro 还高。便宜的香港机器和快的香港机器，是两台完全不同的机器。买之前先确认自己买的是哪一档。

## 想要大陆优化，最低门槛是 $88.88/年

洛杉矶 AN4 平台的 Pro TINY 和 EB TINY 同为 **$88.88/年**，配置都是 1核 2GB / 20GB SSD。差别在三个地方：

|  | AN4.Pro TINY | AN4.EB TINY |
| --- | --- | --- |
| 线路 | 三网 CN2 GIA | 联通 AS9929 + 移动 CMIN2 |
| 月流量 | 1000GB | 1500GB |
| 带宽 | 1Gbps | 2Gbps |
| 价格 | $88.88/年 | $88.88/年 |

电信用户优先 Pro，CN2 GIA 的回程质量是这条线的核心价值。联通、移动用户用 EB 更划算，流量多 50%，带宽翻倍，价格一样。加上 8 折码，EB TINY 实际支出约 $71.10/年，比 WEE 贵不到一倍，但拿到的是能正经跑站的线路。

👉 [用 EB 年付方案 + 8 折码开通洛杉矶优化线路](https://www.dmit.io/aff.php?aff=9081&pid=245)

再往上就没必要在“便宜”这个话题里讨论了。香港 Pro 最低 $39.90/月，一年 $478.8，它解决的是延迟问题，不是预算问题。

## 买之前的四条规则

**退款。** 购买 3 天内、流量使用不超过 30GB，可全额退款，扣支付网关手续费；30 天内按剩余价值比例退款。退到账户余额免手续费，原路退回可能扣费。续费订单不退，同系列产品累计退款 3 次不退，IP 被封不退。对第一次买的人来说，3 天窗口足够跑一轮测速、看延迟、验证线路是不是自己想要的。

**换 IP。** IP 被墙每 15 天可免费换一次，2026 年起支持自助操作，不用等工单；超出免费次数每次 $5。

**登录方式。** 默认 SSH 密钥登录，不是用户名密码。第一次用 KVM 的人别在登录环节卡住，官网知识库有教程。

**付款。** 支付宝、微信、PayPal、信用卡、加密货币都支持，有中文客服。国内用户下单没有障碍。

把退款窗口和换 IP 政策放在一起看，$36.90 的试错成本其实很低：三天内不满意就退，IP 出了问题半个月有一次免费换的机会。

👉 [从 WEE 开始试，3 天内可全额退款](https://www.dmit.io/aff.php?aff=9081&pid=71)

## 常见问题

**dmit 便宜套餐里最便宜的是哪个？**
洛杉矶 LAX.AN4.T1.WEE，$36.90/年，1核 1GB / 20GB / 1000GB 月流量。香港和东京的 T1 也有同价 WEE，三选一看库存。

**WEE 能用优惠码吗？**
不能。洛杉矶 T1 系列没有可用码，香港/东京 T1 的 7 折码明确排除 WEE。$36.90 就是最终实付。

**T1 能建站吗？**
能建，但不适合面向中国大陆用户的站。海外用户访问、纯展示页、内部工具没问题；国内用户为主的站点请直接看 EB 或 Pro。

**香港 T1 是不是国内访问更快？**
不是。T1 没有大陆优化，香港节点对国内用户可能比洛杉矶 Pro 还慢。低延迟要买香港 Pro，$39.90/月起。

**想要的套餐缺货怎么办？**
热门档（尤其 Pro 和 EB 的入门款）经常缺货，补货没有固定时间表。同价位的三机房 WEE 可以互为替代；Pro/EB 缺货时，先确认自己是要美国 IP 还是要低延迟，再决定等货还是换机房。

## 怎么选：三条规则

只要一台便宜机器跑脚本、做落地、当测试环境 → **LAX.AN4.T1.WEE，$36.90/年**，三机房任选，别买贵的那档，1核1GB 干这些活够了。

要大陆优化、预算压到最低 → **LAX.AN4.EB.TINY，$88.88/年**，年付时试 8 折码，验证通过约 $71.10/年。

要低延迟、服务国内用户 → 香港 Pro，$39.90/月起。这一档没有便宜方案，别在 T1 里找。

下单前做两件事：一是看购物车里的实时价格和库存，本文价格整理自 2026 年 4 月的官网套餐页，七个多月过去，价格和库存都可能变；二是把优惠码在结算页验证一遍再付款，验证不通过就按原价买，不要为了用码去升级到用不上的配置。

👉 [查看 DMIT 全部套餐与当前库存](https://www.dmit.io/aff.php?aff=9081)
