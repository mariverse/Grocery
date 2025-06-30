B 站压码率这事，是向运营成本的妥协。作为流媒体内容平台，在国内必须要承担的大额成本就是向运营商购买的商业带宽成本。运营商本质是按流量计费的，反哺了对家庭宽带的按时间收费。这就要从骨干网互联说起了。
不同运营商骨干网间互联互通，随之产生了网间流量费用结算。比如 2020年7月1日以前，中国移动须单方面向中国电信和中国联通按照最高 8 万元/Gbps/月支付网间结算费用（流量穿透以规避结算费用），因为电信发家早、水管粗啊。运营商从家庭宽带上赚不到什么钱，单人单设备每月随随便便几十 GB，而家用宽带缴费一年也就百千元。面对这么大缺口，运营商自然向商业用户找补了。[B 站 2023 年财报](https://ir.bilibili.com/media/3xfch12a/annual-and-transition-report-of-foreign-private-issuers-sections-13-or-15-d.pdf)就披露出，其服务器及带宽费用占总收入成本从 21 年的 10.2% 降低到 23 年的 8.7%（怎么肥四呢）。
[[attachments/bilibili_2023_annual_report.png |Bilibili 2023 年度财报]]
那为什么国外的 Youtube、Netflix、Disney+ 这些内容平台，能做到高码率呢？首先因为 Youtube 背靠 Google，Disney+ 背靠 ABC，都是有钱的角儿；其次，Google 凭自己在国外绝对强势，还有个骚操作，就是自个儿向运营商买用户近侧光纤组边缘机房乃至自己埋光纤，只需要支付一次性的铺设费用，后续走自己家线路的成本微乎其微。
这不就是 PCDN 吗？但国内运营商是不允许私建基于 Peer2Peer 的 PCDN 的。
https://www.huxiu.com/article/368600.html
https://www.usenix.org/system/files/atc24-zhang-rui-xiao.pdf