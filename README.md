# Awesome Home Networking

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

本文档主要用于整理家庭网络相关知识，目前由 [Blanboom](https://blanboom.org/) 维护。

## 目录

* [Awesome Home Networking](#awesome-home-networking)
  * [目录](#%E7%9B%AE%E5%BD%95)
  * [网站与资源](#%E7%BD%91%E7%AB%99%E4%B8%8E%E8%B5%84%E6%BA%90)
    * [主题网站](#%E4%B8%BB%E9%A2%98%E7%BD%91%E7%AB%99)
    * [讨论区](#%E8%AE%A8%E8%AE%BA%E5%8C%BA)
    * [相关组织](#%E7%9B%B8%E5%85%B3%E7%BB%84%E7%BB%87)
    * [YouTuber、Bilibili UP 主](#youtuberbilibili-up-%E4%B8%BB)
    * [书籍、教程](#%E4%B9%A6%E7%B1%8D%E6%95%99%E7%A8%8B)
  * [硬件设备](#%E7%A1%AC%E4%BB%B6%E8%AE%BE%E5%A4%87)
    * [设备类型](#%E8%AE%BE%E5%A4%87%E7%B1%BB%E5%9E%8B)
      * [无线路由器](#%E6%97%A0%E7%BA%BF%E8%B7%AF%E7%94%B1%E5%99%A8)
      * [无线 mesh 系统/分布式路由](#%E6%97%A0%E7%BA%BF-mesh-%E7%B3%BB%E7%BB%9F%E5%88%86%E5%B8%83%E5%BC%8F%E8%B7%AF%E7%94%B1)
      * [无线 AP](#%E6%97%A0%E7%BA%BF-ap)
      * [交换机](#%E4%BA%A4%E6%8D%A2%E6%9C%BA)
      * [有线路由器](#%E6%9C%89%E7%BA%BF%E8%B7%AF%E7%94%B1%E5%99%A8)
      * [软路由](#%E8%BD%AF%E8%B7%AF%E7%94%B1)
      * [光猫](#%E5%85%89%E7%8C%AB)
      * [开发板](#%E5%BC%80%E5%8F%91%E6%9D%BF)
      * [企业级设备](#%E4%BC%81%E4%B8%9A%E7%BA%A7%E8%AE%BE%E5%A4%87)
      * [其他](#%E5%85%B6%E4%BB%96)
    * [选购指南](#%E9%80%89%E8%B4%AD%E6%8C%87%E5%8D%97)
    * [设备厂商与品牌](#%E8%AE%BE%E5%A4%87%E5%8E%82%E5%95%86%E4%B8%8E%E5%93%81%E7%89%8C)
      * [TP\-LINK / MERCURY / FAST](#tp-link--mercury--fast)
      * [华硕 ASUS](#%E5%8D%8E%E7%A1%95-asus)
      * [网件 NETGEAR](#%E7%BD%91%E4%BB%B6-netgear)
      * [领势 Linksys](#%E9%A2%86%E5%8A%BF-linksys)
      * [斐讯](#%E6%96%90%E8%AE%AF)
      * [新路由 newifi](#%E6%96%B0%E8%B7%AF%E7%94%B1-newifi)
      * [腾达 Tenda](#%E8%85%BE%E8%BE%BE-tenda)
      * [小米](#%E5%B0%8F%E7%B1%B3)
      * [华为、荣耀](#%E5%8D%8E%E4%B8%BA%E8%8D%A3%E8%80%80)
      * [新华三 H3C](#%E6%96%B0%E5%8D%8E%E4%B8%89-h3c)
      * [友讯 D\-Link](#%E5%8F%8B%E8%AE%AF-d-link)
      * [360](#360)
      * [群晖 Synology](#%E7%BE%A4%E6%99%96-synology)
      * [优倍快 Ubiquiti](#%E4%BC%98%E5%80%8D%E5%BF%AB-ubiquiti)
      * [Aruba Networks](#aruba-networks)
      * [Apple AirPort](#apple-airport)
      * [MikroTik](#mikrotik)
      * [竞斗云](#%E7%AB%9E%E6%96%97%E4%BA%91)
      * [爱快 iKuai](#%E7%88%B1%E5%BF%AB-ikuai)
      * [磊科](#%E7%A3%8A%E7%A7%91)
      * [eero](#eero)
      * [Google Nest Wi\-Fi](#google-nest-wi-fi)
      * [诺基亚 Nokia](#%E8%AF%BA%E5%9F%BA%E4%BA%9A-nokia)
      * [烽火 FiberHome](#%E7%83%BD%E7%81%AB-fiberhome)
    * [芯片厂商](#%E8%8A%AF%E7%89%87%E5%8E%82%E5%95%86)
  * [操作系统](#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F)
    * [OpenWrt](#openwrt)
    * [ASUSWRT](#asuswrt)
    * [padavan/rt\-n56u](#padavanrt-n56u)
    * [RouterOS](#routeros)
    * [pfSence/OPNSense](#pfsenceopnsense)
    * [VyOS](#vyos)
    * [EdgeOS](#edgeos)
    * [爱快 iKuaiOS](#%E7%88%B1%E5%BF%AB-ikuaios)
    * [Tomato](#tomato)
    * [DD\-WRT](#dd-wrt)
    * [高恪](#%E9%AB%98%E6%81%AA)
  * [组网相关](#%E7%BB%84%E7%BD%91%E7%9B%B8%E5%85%B3)
    * [mesh 网络、有线回程](#mesh-%E7%BD%91%E7%BB%9C%E6%9C%89%E7%BA%BF%E5%9B%9E%E7%A8%8B)
    * [有线路由器 \+ AC \+ AP](#%E6%9C%89%E7%BA%BF%E8%B7%AF%E7%94%B1%E5%99%A8--ac--ap)
    * [VLAN 划分](#vlan-%E5%88%92%E5%88%86)
    * [单臂路由](#%E5%8D%95%E8%87%82%E8%B7%AF%E7%94%B1)
  * [技术概念](#%E6%8A%80%E6%9C%AF%E6%A6%82%E5%BF%B5)
    * [MU\-MIMO](#mu-mimo)
    * [Wi\-Fi 6、Wi\-Fi 6E、Wi\-Fi 6\+](#wi-fi-6wi-fi-6ewi-fi-6)
    * [160MHz 频宽](#160mhz-%E9%A2%91%E5%AE%BD)
    * [PA/LNA/功放](#palna%E5%8A%9F%E6%94%BE)
  * [软硬件功能](#%E8%BD%AF%E7%A1%AC%E4%BB%B6%E5%8A%9F%E8%83%BD)
    * [UPnP/NAT\-PMP/端口映射](#upnpnat-pmp%E7%AB%AF%E5%8F%A3%E6%98%A0%E5%B0%84)
    * [DDNS](#ddns)
    * [流量整形与 QoS](#%E6%B5%81%E9%87%8F%E6%95%B4%E5%BD%A2%E4%B8%8E-qos)
    * [Captive Portal](#captive-portal)
    * [内网穿透](#%E5%86%85%E7%BD%91%E7%A9%BF%E9%80%8F)
    * [家长控制](#%E5%AE%B6%E9%95%BF%E6%8E%A7%E5%88%B6)
    * [内容过滤](#%E5%86%85%E5%AE%B9%E8%BF%87%E6%BB%A4)
    * [IPS/IDS](#ipsids)
    * [流量统计/DPI](#%E6%B5%81%E9%87%8F%E7%BB%9F%E8%AE%A1dpi)
    * [多 WAN 口、多拨](#%E5%A4%9A-wan-%E5%8F%A3%E5%A4%9A%E6%8B%A8)
    * [带宽提升](#%E5%B8%A6%E5%AE%BD%E6%8F%90%E5%8D%87)
    * [游戏加速](#%E6%B8%B8%E6%88%8F%E5%8A%A0%E9%80%9F)
    * [智能家居整合](#%E6%99%BA%E8%83%BD%E5%AE%B6%E5%B1%85%E6%95%B4%E5%90%88)
    * [运行第三方应用](#%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%94%E7%94%A8)
    * [虚拟化](#%E8%99%9A%E6%8B%9F%E5%8C%96)
    * [手机 App](#%E6%89%8B%E6%9C%BA-app)
    * [SNMP](#snmp)
    * [网络存储、媒体中心](#%E7%BD%91%E7%BB%9C%E5%AD%98%E5%82%A8%E5%AA%92%E4%BD%93%E4%B8%AD%E5%BF%83)
    * [第三方服务整合](#%E7%AC%AC%E4%B8%89%E6%96%B9%E6%9C%8D%E5%8A%A1%E6%95%B4%E5%90%88)
    * [Bonjour/mDNS](#bonjourmdns)
    * [校园网](#%E6%A0%A1%E5%9B%AD%E7%BD%91)
  * [安全性](#%E5%AE%89%E5%85%A8%E6%80%A7)
    * [相关文章](#%E7%9B%B8%E5%85%B3%E6%96%87%E7%AB%A0)
    * [开源固件 vs 闭源固件](#%E5%BC%80%E6%BA%90%E5%9B%BA%E4%BB%B6-vs-%E9%97%AD%E6%BA%90%E5%9B%BA%E4%BB%B6)
    * [官方版固件 vs 修改版固件](#%E5%AE%98%E6%96%B9%E7%89%88%E5%9B%BA%E4%BB%B6-vs-%E4%BF%AE%E6%94%B9%E7%89%88%E5%9B%BA%E4%BB%B6)
    * [软件更新](#%E8%BD%AF%E4%BB%B6%E6%9B%B4%E6%96%B0)
    * [Linux 安全特性的应用](#linux-%E5%AE%89%E5%85%A8%E7%89%B9%E6%80%A7%E7%9A%84%E5%BA%94%E7%94%A8)
    * [KRACK](#krack)
    * [WPA3](#wpa3)
    * [防火墙配置](#%E9%98%B2%E7%81%AB%E5%A2%99%E9%85%8D%E7%BD%AE)
  * [网络质量优化](#%E7%BD%91%E7%BB%9C%E8%B4%A8%E9%87%8F%E4%BC%98%E5%8C%96)
  * [基础设施](#%E5%9F%BA%E7%A1%80%E8%AE%BE%E6%96%BD)
    * [装修与布线](#%E8%A3%85%E4%BF%AE%E4%B8%8E%E5%B8%83%E7%BA%BF)
    * [弱电箱、机柜](#%E5%BC%B1%E7%94%B5%E7%AE%B1%E6%9C%BA%E6%9F%9C)
    * [其他创意](#%E5%85%B6%E4%BB%96%E5%88%9B%E6%84%8F)
  * [网络诊断、调试工具](#%E7%BD%91%E7%BB%9C%E8%AF%8A%E6%96%AD%E8%B0%83%E8%AF%95%E5%B7%A5%E5%85%B7)
  * [ISP 相关](#isp-%E7%9B%B8%E5%85%B3)
    * [运营商选择](#%E8%BF%90%E8%90%A5%E5%95%86%E9%80%89%E6%8B%A9)
    * [公网 IP、IPv6 地址的获取](#%E5%85%AC%E7%BD%91-ipipv6-%E5%9C%B0%E5%9D%80%E7%9A%84%E8%8E%B7%E5%8F%96)
    * [光猫改桥接，使用路由器拨号](#%E5%85%89%E7%8C%AB%E6%94%B9%E6%A1%A5%E6%8E%A5%E4%BD%BF%E7%94%A8%E8%B7%AF%E7%94%B1%E5%99%A8%E6%8B%A8%E5%8F%B7)
    * [IPTV 相关](#iptv-%E7%9B%B8%E5%85%B3)
    * [相关政策、投诉方式](#%E7%9B%B8%E5%85%B3%E6%94%BF%E7%AD%96%E6%8A%95%E8%AF%89%E6%96%B9%E5%BC%8F)
  * [常见误区、Q&amp;A](#%E5%B8%B8%E8%A7%81%E8%AF%AF%E5%8C%BAqa)
    * [终端只支持 2x2 MIMO，没有必要选用 3x3 MIMO 或 4x4 MIMO 的无线路由器？](#%E7%BB%88%E7%AB%AF%E5%8F%AA%E6%94%AF%E6%8C%81-2x2-mimo%E6%B2%A1%E6%9C%89%E5%BF%85%E8%A6%81%E9%80%89%E7%94%A8-3x3-mimo-%E6%88%96-4x4-mimo-%E7%9A%84%E6%97%A0%E7%BA%BF%E8%B7%AF%E7%94%B1%E5%99%A8)
  * [综合案例](#%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B)
  * [欢迎参与](#%E6%AC%A2%E8%BF%8E%E5%8F%82%E4%B8%8E)
  * [许可证](#%E8%AE%B8%E5%8F%AF%E8%AF%81)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## 网站与资源

### 主题网站

* [acwifi.net 路由器交流](https://www.acwifi.net/)
* [少数派：#网络设备](https://sspai.com/tag/%E7%BD%91%E7%BB%9C%E8%AE%BE%E5%A4%87)
* [什么值得买：网络设备](https://post.smzdm.com/fenlei/wangluoshebei/)
* [SmallNetBuilder](https://www.smallnetbuilder.com/)
* [ServeTheHome](https://www.servethehome.com/)
* [WikiDevi](https://web.archive.org/web/20191022065144/https://wikidevi.com/wiki/Main_Page): 一个关于无线芯片、网络设备等硬件的 Wiki，目前网站已关闭
* [fccid.io](https://fccid.io/): 能够找到各种无线设备的说明书、照片、拆机图等
* [INCREASE BROADBAND SPEED Tips and Guides](https://www.increasebroadbandspeed.co.uk/)
* [StopLagging.com](https://www.stoplagging.com/)

### 讨论区

* [KoolShare](http://koolshare.cn/)
* [Anywlan](https://www.anywlan.com/)
* [恩山无线论坛](https://www.right.com.cn/forum/forum.php)
* [数码之家：WiFi/路由器](http://bbs.mydigit.cn/thread.php?fid=147)
* [V2EX: 宽带症候群](https://www.v2ex.com/go/bb)
* [V2EX: 路由器](https://www.v2ex.com/go/router)
* [Chiphell: 电脑讨论 - 网络](https://www.chiphell.com/forum.php?mod=forumdisplay&fid=36&filter=typeid&typeid=736)
* [SmallNetBuilder Forums](https://www.snbforums.com/)
* [Reddit: r/homelab](https://www.reddit.com/r/homelab/)
* [Reddit: r/HomeNetworking](https://www.reddit.com/r/HomeNetworking/)
* 网络设备厂商官网的讨论区

### 相关组织

* [Wi-Fi Alliance](https://www.wi-fi.org/zh-hans)
* [Broadband Forum](https://www.broadband-forum.org/)
* [国家无线电监测中心](http://www.srrc.org.cn/index2018.aspx)


### YouTuber、Bilibili UP 主

* [YouTube: Lawrence Systems](https://www.youtube.com/channel/UCHkYOD-3fZbuGhwsADBd9ZQ)
* [YouTube: Crosstalk Solutions](https://www.youtube.com/channel/UCVS6ejD9NLZvjsvhcbiDzjw)
* [YouTube: Willie Howe](https://www.youtube.com/channel/UCD-QkofF-bFBAcI83U8ZZeg)
* [Bilibili: BIG东东](https://space.bilibili.com/108142407)
* [Bilibili: 司波图](https://space.bilibili.com/28457)
* [Bilibili: NGXHK](https://space.bilibili.com/30496941)
* [Bilibili: Vedio Talk](https://space.bilibili.com/28459251)
* [Bilibili: 悟空的日常](https://space.bilibili.com/250915741)

### 书籍、教程

- [Linux Advanced Routing & Traffic Control HOWTO](https://lartc.org/)
  - [Linux 的高级路由和流量控制 HOWTO 中文版](https://lartc.org/LARTC-zh_CN.GB2312.pdf)

## 硬件设备

### 设备类型

#### 无线路由器

我们平时最常见的无线路由器（SOHO 无线路由器），其实不仅仅包含路由器的功能，而是整合了路由器、防火墙、交换机、无线 AP 等多种功能为一体。操作和设置相对简单，能够满足绝大多数家庭的需求。

* [Wireless router - Wikipedia](https://en.wikipedia.org/wiki/Wireless\_router)

#### 无线 mesh 系统/分布式路由

在单个无线路由器无法满足覆盖面积时，可以通过多台设备组网，扩展无线面积。无线 mesh 系统的多个节点之间可以相互通信，组成网状网络，并在通信时自动选择最佳路径。目前已有大量厂商推出家用的无线 mesh 系统。

* [Wireless mesh network - Wikipedia](https://en.wikipedia.org/wiki/Wireless\_mesh\_network)

#### 无线 AP

无线 AP 一般仅提供 Wi-Fi 接入功能，需要配合交换机和路由器，才能搭建一个完整的无线网络。多个无线 AP 组网的方式，比起家用无线 mesh 系统，在稳定性、速率、覆盖面积上都占有优势。缺点是安装复杂，主要用于企业，家庭使用时一般需要在装修初期考虑。

* [无线接入点 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E7%84%A1%E7%B7%9A%E6%8E%A5%E5%85%A5%E9%BB%9E)

#### 交换机

交换机工作于数据链路层，能够连接同一网络内的多个设备。例如家中有多台电脑、游戏机等设备，而普通无线路由器上的网口数量不足时，就可以使用交换机扩展网口，连接多个设备。

* [网络交换机 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8)

#### 有线路由器

路由器工作于网络层，用于连接两个或多个网络，在多个网络之间转发数据。对于家用场景，路由器一般用于连接运营商网络和家庭网络，负责让家中的设备访问 Internet。

在普通的无线路由器无法满足需求时，可以使用功能更强大的有线路由器，结合交换机和无线 AP，搭建家庭网络。

* [路由器 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E8%B7%AF%E7%94%B1%E5%99%A8)

#### 软路由

软路由一般是使用通用的硬件平台，例如 x86 服务器搭建的路由器。实现报文转发等功能，与普通路由器相比，很少利用专用硬件进行加速，而是通过纯软件的形式处理。

由于软路由使用通用的硬件、拥有较大的内存、大多运行基于 Linux 或 FreeBSD 的操作系统，能够通过软件扩充更多功能，具有更强的灵活性。在性能上，软路由具有更强大的 CPU，但普通的路由器能够通过专门的硬件实现路由转发、QoS、NAT 等功能，无法进行简单的对比。

* [软路由是什么？ - 知乎](https://www.zhihu.com/question/263523980)
* [从听说到上手，人人都能看懂的软路由入门指南 - 少数派](https://sspai.com/post/58628)

#### 光猫

光猫用于将光信号转换为电信号。目前大部分家用光猫也同时具有路由和 Wi-Fi 的功能。

光猫一般由运营商提供，在安装宽带时租用。部分对网络有追求的用户也会选择自行购买，但不同地区对光猫的要求不同，设置方式也不一定相同，购买前需要先了解相关信息。

此外还有 PON Stick 这样的硬件，将光猫集成在 SFP+ 模块中，可以直接搭配支持 SFP+ 接口的路由器或交换机使用，减少体积占用。

* [家用千兆光猫该如何选择？ - 网络设备 - KoolShare - 源于玩家 服务玩家](http://koolshare.cn/thread-127073-1-1.html)
* [抛弃光猫esxi+光卡+gpon stick模块上网 - 网络设备 - KoolShare - 源于玩家 服务玩家](https://koolshare.cn/thread-170674-1-1.html)
* [双模 PON STICK ONU SFP-深圳市南天威视科技有限公司](http://www.natywish.com/product/detail/219.html)

#### 开发板

目前市面上有不少开发板，具有单个或多个网口，运行标准 Linux 或 OpenWrt，部分甚至支持 Wi-Fi，能够实现如下功能：

- 自制无线路由器<br>大部分开发板性能不一定够用，或者只有一个网口，并没有太多人这样做
- 做为 DNS 服务器、代理服务器、HomeBridge/HomeAssistant 服务器等使用<br>部分家用无线路由器也可通过安装软件实现这些功能。不过考虑到性能和稳定性，通过独立的开发板运行相关服务，是一种更好的选择
- 连接传感器、显示屏、继电器等，实现物联网、智能家居相关功能<br>开发板大多拥有丰富的 IO 口资源，可以连接更多模块，来实现物联网相关功能

常见的带网络功能的开发板有如下几种：

- [Raspberry Pi](https://www.raspberrypi.org) 等单板计算机<br>热门的单板电脑，在网上能够找到大量资源
- [wrtnode](http://www.wrtnode.cc/)<br>运行 OpenWrt 的开发板
- [Widora](https://wiki.widora.io/)<br>运行 OpenWrt 的开发板
- [Arduino Yún](https://store.arduino.cc/usa/arduino-yun-rev-2)<br>运行 OpenWrt 的开发板，且内部与一块 AVR 单片机相互连接，扩展 IO 口资源，并同时融合 Arduino 和 OpenWrt 两种生态。更适合用来制作物联网相关的 DIY 作品
- [BPI-R1](http://www.banana-pi.org.cn/r1.html)<br>带有五个网口、SATA、USB 的开发板
- [Marvell ESPRESSObin](http://espressobin.net/#1479827193124-28c92b06-d318)<br>带有三个网口、SATA 接口的开发板，并具有硬件转发芯片
- [NanoPi R2S](http://wiki.friendlyarm.com/wiki/index.php/NanoPi_R2S/zh)<br>带有两个网口的开发板，能够运行 Linux，体积小巧。

#### 企业级设备

对于网络爱好者，也可考虑企业级网络设备，例如 Aruba、Ruckus、CISCO，或者国内华为、H3C、锐捷等厂商的设备。

由于本 List 主要关注家庭网络，不会过多整理企业级设备的相关知识。

#### 其他

除了路由器、交换机等设备，市面上还有不少辅助设备，用于增强家庭网络的功能。

- Wi-Fi 扩展器/信号放大器
- [花生棒](https://hsk.oray.com/device/)等内网穿透工具
- [Fingbox](https://www.fing.com/products/fingbox): 集成了局域网扫描、家长控制、带宽监控等功能的独立硬件
- [Circle](https://meetcircle.com/): 具有家长控制功能的独立硬件

### 选购指南

- [How To Buy A Wireless Router - 2018 Edition](https://www.smallnetbuilder.com/basics/wireless-basics/33177-how-to-buy-a-wireless-router-2018-edition)

- [How To Buy A Wireless Router - 2017 Edition](https://www.smallnetbuilder.com/basics/wireless-basics/33029-how-to-buy-a-wireless-router-2017-edition)

- [2020 生活手册系列：家用网络配置与选购指南 – Yachen's Blog](https://yach.me/2020/10/06/2020-生活手册系列：家用网络配置与选购指南/)

### 设备厂商与品牌

#### TP-LINK / MERCURY / FAST

TP-LINK 是国内最知名的无线路由器品牌。价格相对较低，如果只是想快速搭建一个简单稳定的家庭网络，TP-LINK 是一个不错的选择。当然，TP-LINK 也有不少支持 OpenWrt 的型号。

另外，TP-LINK 在国内和国外，在产品布局、营销策略上也有不少差异，甚至连国内外的 logo 都不相同。在淘宝、闲鱼等平台，能够买到部分国外版本的硬件。

- [TP-LINK 国内官网](https://www.tp-link.com.cn)
- [TP-LINK 国际官网](https://www.tp-link.com/us/)
- [MERCURY 水星网络官网](https://www.mercurycom.com.cn)
- [FAST 迅捷网络官网](https://www.fastcom.com.cn)

#### 华硕 ASUS

华硕无线路由器有着较为丰富的产品线，从入门的百元级别型号，到 4000 元以上的高端型号都有覆盖，同时也有 ROG 玩家国度等特色型号。

AiMesh 是华硕路由器的一个标志性功能，能够在不同型号的设备间进行 mesh 组网，降低成本。

华硕的 ASUSWRT 操作系统功能丰富，另外还可以方便地安装 asuswrt-merlin 修改版系统。关于 ASUSWRT 的详细介绍可参考后面「操作系统」部分的内容。

- [华硕无线路由器官网](https://www.asus.com.cn/Networking/)
- [ASUSWRT](https://www.asus.com.cn/ASUSWRT/)
- [ASUS Router App](https://www.asus.com.cn/asus-router-app/)
- [AiMesh 家用网状 mesh 系统](https://www.asus.com/Microsite/AiMesh/cn/)
- [RT-AX88U](https://www.asus.com.cn/Networking/RT-AX88U/): 经典型号 [RT-AC88U](https://www.asus.com.cn/Networking/RT-AC88U/) 的 Wi-Fi 6 升级版
- [RT-AX89X](https://www.asus.com.cn/Networking/RT-AX89X/): 支持 Wi-Fi 6，带有双万兆网口的高端型号
- [ASUS ROG 游戏路由器](https://www.asus.com/ROG-Republic-Of-Gamers/Wireless-Routers-Products/)
- [ASUS Lyra 家用 mesh 无线路由器](https://www.asus.com.cn/Networking/Lyra/)

#### 网件 NETGEAR

网件是一家网络设备设备生产商，其生产的家用设备也覆盖了低端到高端不同型号，部分型号支持 Plex Media Server 等特色功能。

自带固件在功能和易用性上，与 ASUSWRT 等相比有一些不足之处，不过网件的不少型号都对 OpenWrt 友好，可以方便地刷 OpenWrt 等第三方系统。

其中网件 R6300v2，虽然已经是多年前的产品，但由于性能够用，能刷 asuswrt-merlin，至今受到不少用户的喜爱。

- [网件官网](https://www.netgear.com.cn/)

- [R6300v2](https://www.netgear.com/support/product/R6300v2.aspx)
  - [路由界一代神器：网件R6300v2开箱](https://post.smzdm.com/p/366708/)
- [NETGEAR Orbi](https://www.netgear.com.cn/orbi/): 家用 mesh Wi-Fi 系统
- [Nighthawk X10 R9000](https://www.netgear.com.cn/home/products/networking/wifi-routers/R9000.aspx): 支持 Plex Media Server 的无线路由器

#### 领势 Linksys

Linksys 成立于 1988 年，后来被 CISCO 收购。但在 2013 年 CISCO 又将 Linysys 卖给了 Belkin。

其中 Linksys 的 WRT54G，是历史上较早使用 Linux 的家用无线路由器，所以其固件按照 GPL 协议需要开源。不少爱好者基于 WRT54G 的开源固件进行修改，增加功能。知名的开源路由器操作系统 OpenWrt、DD-Wrt 等，都与 WRT54G 或多或少有一定的渊源。

目前，Linksys 依然有着不少有竞争力的产品，例如 mesho 系统 Velop。

- [Linksys 官网](https://www.linksys.com/cn/)
- [WRT54G](https://en.wikipedia.org/wiki/Linksys_WRT54G_series)
- [Velop](https://www.linksys.com/cn/velop/): 家用 mesh Wi-Fi 系统

#### 斐讯

因为采取「0元购」模式而受到大家的熟知。常见的型号有 K2P、K3C 和 K3。目前能在部分二手交易平台以较低的价格买到。

斐讯路由器整体配置和做工都不错，也有不少人为其适配开源固件。不过购买时需要注意不同版本硬件的区别，比如 K2P 的 A 版和 B 版；K3 等型号可能还需要自己改装一下硬件，才能避免「漏油」等问题。如果喜欢折腾，可以在二手价比较低时购买。

- [斐讯官网](http://www.phicomm.com/cn/)
- [K2P](http://www.phicomm.com/cn/index.php/Products/family_details/cateid/18/id/122.html): AC1200，根据版本的不同，支持 OpenWrt、Padavan 或 asuswrt-merlin 等
  - [K2P A 版和 B 版的区别](https://www.acwifi.net/3761.html)
- [K3](http://www.phicomm.com/cn/index.php/Products/family_details/cateid/18/id/121.html): AC3150，支持 OpenWrt 和 asuswrt-merlin
  - [K3 闪存坏块问题](https://www.right.com.cn/forum/thread-252057-1-1.html)
  - [K3 漏油问题改造](https://www.right.com.cn/forum/thread-326035-1-1.html)
- [K3C](http://www.phicomm.com/cn/index.php/Products/family_details/cateid/18/id/124.html): AC1900，支持 asuswrt-merlin
- [K2T](http://www.phicomm.com/cn/index.php/Products/family_details/cateid/18/id/125.html): AC1200，分体式设计，适合做为 AP 使用

#### 新路由 newifi

来自联想，曾经由于挖矿功能和还不错的性能而受到欢迎，支持刷开源固件。目前已停产，能以非常低的价格在二手交易平台买到。

- [newifi 官网（存档）](https://web.archive.org/web/20171215072313/https://www.newifi.com/)
- [联想新路由3 newifi 3简评，100块的简易矿渣究竟值不值得买？](https://new.qq.com/omn/20191014/20191014A0OL7F00.html)
- [新路由3(Newifi D2)与斐讯K2P对比测试](https://www.acwifi.net/5638.html)

#### 腾达 Tenda

国内的无线路由器品牌，价格较低，部分型号能刷 OpenWrt。

- [腾达官网](https://www.tenda.com.cn/)

#### 小米

小米路由器采用「互联网模式」进行开发。官方固件就提供了丰富的功能（例如和迅雷合作推出远程下载），且 UI 相对更为现代和美观。但同时也存在劫持「404 页面劫持」等问题。

不过，小米路由器的大多数不带硬盘的型号，都能较好地支持 OpenWrt、Padavan 等系统；在工业设计、硬件配置、性价比方面存在一定优势。尤其是最近的 Wi-Fi 6 系列路由器，有着较好的口碑。可考虑购买后使用第三方系统。

- [小米路由器官网](http://www.miwifi.com/)
- [小米路由器劫持用户浏览器事件始末](https://www.infoq.cn/article/2015/06/xiaom-hijack)
- [如何看待小米路由进行 404 网页劫持？](https://www.zhihu.com/question/30358197)

#### 华为、荣耀

华为原有业务主要侧重于运营商网络，较晚推出家用无线路由器。

主要特色包括支持 HiLink 智能家居平台、部分型号采用自研芯片等。但使用自研新品也为支持 OpenWrt 等系统带来了一定的难度。

由于华为和荣耀家用路由器已有较多型号，不同型号间差异较大，具体的功能、性能、稳定性等，建议购买前上网自行搜索了解和判断。

- [华为家用路由器官网](https://consumer.huawei.com/cn/routers/)

- [荣耀家用路由器官网](https://www.honor.cn/products/home-internet-media/)

#### 新华三 H3C

H3C 原有业务主要侧重于企业网络，较晚推出家用无线路由器。

根据官方宣传资料，H3C 家用路由器使用 MINIWARE 操作系统（与 H3C 的部分商用无线 AP 使用的操作系统名称相同），支持 IPS 等安全功能。系统主要关注基本的网络功能，界面较为简单、功能没有互联网厂商的家用路由器那样丰富。但也在理论上保证了一定程度的稳定性。硬件上 Magic B1 等型号工业设计比较独特。

其产品线除了无线路由器、mesh 系统外，还包括家用 AC+AP 套装等。目前暂未发现支持 OpenWrt 等第三方系统。

- [H3C 官网](http://www.h3c.com/cn)
- [H3C Magic B1](http://www.h3c.com/cn/Products___Technology/IntelligentTerminalProducts/Standard-Network/B/H3C_Magic_B1/): 分体式设计，外观较为简洁
- [H3C H5](http://www.h3c.com/cn/Products___Technology/IntelligentTerminalProducts/Intelligence-Home/H/H5/): AC+AP 套装

#### 友讯 D-Link

网络设备品牌，提供路由器、交换机、无线网卡等设备。

- [友讯官网](http://www.dlink.com.cn/)

#### 360

以「互联网模式」开发的家用路由器，以「安全」功能作为卖点。但其「孕妇模式」等营销概念受到了不少人的反感。

- [360 家用路由器官网](https://luyou.360.cn/)

- [如何评价 360 安全路由器 的「孕妇模式」？](https://www.zhihu.com/question/31207364)

#### 群晖 Synology

NAS 厂商，较晚进入无线路由器领域。目前推出 RT1900ac、RT2600ac，以及 mesh 路由器 MR2200ac 三款产品。其特色在于自带的 Synology Router Manager (SRM) 操作系统。

SRM 基于群晖的 NAS 操作系统 [DSM](https://www.synology.com/zh-cn/dsm)，具有友好的用户界面，外接移动硬盘后，具有一定的 NAS 功能。并支持与其 NAS 相同的 [File Station](https://www.synology.com/zh-cn/knowledgebase/DSM/help/FileStation/FileBrowser_desc)、[Download Station](https://www.synology.com/zh-cn/knowledgebase/DSM/help/DownloadStation/DownloadStation_desc)、[Media Server](https://www.synology.com/zh-cn/knowledgebase/DSM/help/MediaServer/application_mediaserver_desc) 三大软件。

SRM 对新技术的应用比较积极，例如 WPA3、DNS over HTTPS 等。SRM 上的家长控制/访问控制功能，以及基于 Suricata 的 IPS 功能，在同类产品中都较为强大。

另外 SRM 一定程度上拥有安装第三方软件的功能。部分 DSM 软件经过修改后，可在 SRM 上运行。同时也可以在 SRM 上安装 optware/entware，通过 `opkg` 命令来安装更多软件。

但群晖做为家用路由器的新厂商，在软件开发与发布流程上经验不足。曾经遇到过同一天发布多个版本才彻底解决一个问题的情况，以及新版本导致原先设置的计划任务失效、需要重新设置的问题（参考[此链接](https://www.synology.com/en-uk/releaseNote/RT2600ac)，版本 1.2.3-8017-4 中的描述）。另外在个人使用过程中，也遇到过网络不稳定，重启路由器才能恢复的问题。

- [Synology 官网](https://www.synology.com/zh-cn)

- [RT2600ac](https://www.synology.com/en-us/products/RT2600ac)

- [MR2200ac](https://www.synology.com/en-us/products/MR2200ac): mesh 路由器

- [Synology Router Manager (SRM) 操作系统](https://www.synology.com/zh-cn/srm)

  - [网络安全/IPS](https://www.synology.com/zh-cn/srm/feature/secure_network_foundation)
    - [Building an intrusion prevention system for small businesses and homes](https://blog.synology.com/building-an-intrusion-prevention-system-for-small-businesses-and-homes/)<br>本文介绍了 Synology 如何优化 Suricata，使其能在家用路由器上流畅运行的
    - [DNS over HTTPS: things to consider when you go “private”](https://blog.synology.com/dns-over-https/)<br>本文介绍了 SRM 对于 DNS over HTTPS 的支持
  - [访问控制/家长控制](https://www.synology.com/zh-cn/srm/feature/device_content_control)
  - 安装第三方软件
    - [RT1900ac 路由器折腾笔记：安装 Homebridge 和 Plex Media Server](https://blanboom.org/2017/plex-on-rt1900ac/)<br>我的一篇博文，涉及如何在 SRM 上安装 entware 和 DSM 套件
    - [nelek's soapbox - A blog about creating packages for Synology DSM](https://synopackages.wordpress.com/)<br>一个个人博客，定期分享自己编译的、适用于 DSM/SRM 的软件（但没有开源，请自行判断是否存在安全风险）


#### 优倍快 Ubiquiti

网络设备厂商，创始人为 Apple AirPort 系列的硬件工程师。其 UniFi 系列提供了价格低廉（相对 CISCO、Aruba、Ruckus 来说）的商用 Wi-Fi 系统，也因为工业设计、易用性等原因，受到了部分个人/家庭用户的喜爱。后续 Ubiquiti Labs 也推出过 AmpliFi 系列的家用产品。

另外，Ubiquiti 的产品，在软件（Web 界面与移动 App）的用户界面和用户体验上比较出色，对于 Dark Mode 等也能在第一时间支持。

- [Ubiquiti 官网](https://www.ui.com.cn/)
- [UniFi 系列](https://unifi-network.ui.com.cn/)：主打商用无线 AP，同时有配套的交换机、路由器、摄像头、NVR 等硬件，可通过 UniFi Controller 统一管理
- [EdgeMax 系列](https://www.ui.com.cn/products/#edgemax)：主打企业级的网络设备，包括路由器和交换机，配置比较丰富，可通过免费的 UNMS 实现部分的管理功能
- [AmpliFi 系列](https://amplifi.com.cn/)：主打家用 mesh 系统，较早提出「家用 mesh 路由器」的概念。工业设计出色
  - [家用 Wi-Fi 的变迁](https://blog.ui.com.cn/post/evolution-home-wi-fi/)

#### Aruba Networks

HPE 在 2015 年 5 月完成了对其的收购因此 Aruba 成为了 HPE 旗下的子公司

由于 Aruba AP 1xx 产品线在 2020 年 8 月 1 日全面结束支持使得二手价格极为便宜，体验 Aruba AP 产品来说是相当划算的

see <https://www.arubanetworks.com/zh-hans/support-services/end-of-life/>

#### Apple AirPort

Apple 的无线路由器，特色功能包括：来自 Apple 的工业设计、与 macOS 和 iOS 的紧密整合、支持 Time Machine 无线备份、支持连接音箱进行 AirPlay 音乐播放、支持无线打印等。

另外 AirPort Extreme 也较早支持多台路由器之间的组网和漫游，虽然 Apple 没有以「mesh」的卖点公开宣传。

目前 AirPort 系列已停产，部分国家和地区的 Apple Online Store 仍有销售，国内可在二手交易网站购买到。

- [AirPort 官方支持页面](https://support.apple.com/zh-cn/airport)
- [AirPort Express（存档）](https://web.archive.org/web/20150613231653/http://www.apple.com/airport-express/): 小巧、支持 AirPlay
- [AirPort Extreme（存档）](https://web.archive.org/web/20150616190421/http://www.apple.com/airport-extreme/): 性能强大
- [AirPort Time Capsule（存档）](https://web.archive.org/web/20150613231648/http://www.apple.com/airport-time-capsule/): 在 AirPort Extreme 的基础上，内置了硬盘，支持 Time Machine 无线备份
- [Wi-Fi 基站：设置和配置漫游网络](https://support.apple.com/zh-cn/HT204616)
  - [简单实惠的无缝漫游家庭网络——AirPort Extreme × 3](https://www.chiphell.com/thread-1772731-4-1.html)

#### MikroTik

MikroTik 为知名软路由操作系统 RouterOS 的开发商，也推出了自有品牌的硬件。其硬件产品官方支持 RouterOS，并附送 RouterOS 软件授权。

- [MikroTik 官网](https://mikrotik.com/)
- [MikroTik SOHO 无线路由器系列](https://mikrotik.com/products/group/wireless-for-home-and-office)
- [MikroTik Audience](https://mikrotik.com/product/audience): 家用 mesh 路由器
- [最强家用路由器: RB4011](https://zhuanlan.zhihu.com/p/58247964)

#### 竞斗云

原先以「区块链路由器」的名义高价销售，目前可以用较低的二手价购买，并安装第三方系统。

- [我爱捡垃圾：100包邮的竞斗云 G-DOCK TTL 刷机教程 X-wrt 很好用！](https://post.smzdm.com/p/amm5355p/)
- [竞斗云2.0 终于找到原始型号和固件了。](https://www.right.com.cn/forum/thread-776593-1-1.html)

#### 爱快 iKuai

爱快为软路由操作系统 iKuai OS 的开发商，也推出了自有品牌的硬件，包括无线路由器、企业级路由器、交换机、无线 AP 等。

- [爱快官网](https://www.ikuai8.com/)

#### 磊科

网络设备厂商，其路由器的 QoS 功能比较有特色。曾和 360、腾讯等厂商合作推出过定制款无线路由器。

- [磊科官网](http://www.netcoretec.com/)

#### eero 

家用无线路由器厂商，目前已被亚马逊收购。外观小巧，主打 mesh 功能，并有付费订阅的 eero Secure 服务。

- [eero 官网](https://eero.com/)
- [eero Secure](https://eero.com/shop/eero-secure)

#### Google Nest Wi-Fi

来自 Google 的无线路由器，主打 mesh 功能。其 mesh 节点上集成了麦克风和音箱，支持 Google Assistant，可同时做为智能音箱使用。

- [Google Store 中的 Nest Wifi](https://store.google.com/product/nest_wifi) 

#### 诺基亚 Nokia

来自诺基亚的 mesh Wi-Fi 系统。

- [Nokia Wi-Fi 官网](https://www.nokia.com/zh_int/node/76546/)

#### 烽火 FiberHome

发源于武汉邮电科学研究院的央企，专于光通信领域，在运营商网络中有大量光猫、机顶盒等设备。

近年开始以 MIFON 品牌投入消费者领域，主打 mesh 功能。

- [烽火通信官网](https://www.fiberhome.com/)
- [MIFON 官网](https://mifon.com/)

### 芯片厂商

大多家用无线路由器中的 SoC，一般来自 MediaTek/Ralink、Broadcom、Qualcomm/Atheros、Realtek、Intel、海思 等几大芯片厂商。

* [Broadcom Inc. | Connecting Everything](https://www.broadcom.cn/)
* [Wireless Technology & Innovation | Mobile Technology | Qualcomm](https://www.qualcomm.com/)
* [联发科技-全球尖端无晶元半导体公司](https://www.mediatek.cn/)
* [首页 - 瑞昱半导体](https://www.realtek.com/zh/)
* [Intel - Smart and Connected Home Products](https://www.intel.com/content/www/us/en/products/devices-systems/home-networking.html)
* [海思- 使能全场景智能终端](https://www.hisilicon.com/cn/)
* [看完它，你就全懂了十大Wifi芯片原厂！\_嵌入式\_whatnamecaniuse的专栏-CSDN博客](https://blog.csdn.net/whatnamecaniuse/article/details/80358415)
* [咦WiFi怎么又断了？选对路由器芯片很关键！\_值客原创\_什么值得买](https://post.smzdm.com/p/746035/)
* [MTK路由器和博通路由器有什么差距呢？博通使用上有提升吗？ - 斐讯无线路由器以及其它斐迅网络设备 - 恩山无线论坛 - Powered by Discuz!](https://www.right.com.cn/forum/thread-219324-1-1.html)
* [无线路由器CPU浅析 MT7621A、 BCM47189 到底谁强？\_嵌入式\_lightrain0的博客-CSDN博客](https://blog.csdn.net/lightrain0/article/details/84979245)
* [无线路由器未来大家是看好博通、高通还是联发科？ - 网络设备 - KoolShare - 源于玩家 服务玩家](https://koolshare.cn/thread-23553-1-1.html)


## 操作系统

本节主要介绍通用（支持在不同品牌设备上运行）的网络操作系统。对于 Synology Router Manager 等私有操作系统，请参考[设备厂商与品牌](#%E8%AE%BE%E5%A4%87%E5%8E%82%E5%95%86%E4%B8%8E%E5%93%81%E7%89%8C)部分。

### OpenWrt

OpenWrt 是最知名的开源无线路由器操作系统，已支持大量厂商和品牌的路由器，也支持在 x86 电脑/服务器上运行。在 2016 年，OpenWrt 派生出 LEDE 项目，但在 2018 年，LEDE 重新合并回 OpenWrt，合并后继续使用 OpenWrt 的名称。

OpenWrt 目前有着广泛的使用范围，不少个人和团队基于 OpenWrt 推出了修改版固件，一些商业公司的无线路由器、无线 AP 等设备，也是基于 OpenWrt 进行开发的。OpenWrt 社区也为开源社区做出了较多贡献，例如拥塞控制算法 CAKE，最早就是在 OpenWrt 上使用，后续进入 Linux 主线的。

OpenWrt 使用 opkg 包管理系统，支持通过安装软件来扩展功能。

- [OpenWrt 官网](https://openwrt.org/start?id=zh/start)
- [选用 OpenWrt 的原因](https://openwrt.org/zh/reasons_to_use_openwrt)
- [OpenWrt 与 LEDE 的关系](https://openwrt.org/start?id=zh/about)
- [OpenWrt 支持的设备列表](https://openwrt.org/toh/start)
- [清华大学 OpenWrt 软件源镜像](https://mirrors.tuna.tsinghua.edu.cn/openwrt/)
- OpenWrt 第三方修改版
  - [OpenWrt Koolshare 修改版](https://koolshare.cn/forum-97-1.html)<br>提供「软件中心」，方便安装来自 Koolshare 和第三方开发者的特色软件。
  - [OpenWrt Lean 修改版](https://github.com/coolsnowwolf/lede)<br>代码开源。在添加适合中国用户的特色功能的基础上，尽量保持精简。
  - [Gargoyle](https://www.gargoyle-router.com/)<br>在国内常被称做「石像鬼固件」，具有强大的 QoS 功能。
  - [Linino](https://www.linino.org/)<br>基于 OpenWrt 的操作系统，内置 `cpu-mcu-bridge`，能够方便的在 OpenWrt 和单片机之间通信，更适合物联网应用。

### ASUSWRT

华硕路由器官方固件。同时存在知名的 asuswrt-merlin 修改版固件。

- [ASUSWRT 官网](https://www.asus.com.cn/ASUSWRT/)
  - [AiProtection](https://www.asus.com.cn/AiProtection/)
  - [AiCloud](https://www.asus.com.cn/AiCloud/)
  - [AiMesh](https://www.asus.com/Microsite/AiMesh/cn/)

- [Asuswrt-Merlin](https://www.asuswrt-merlin.net/)：基于 ASUSWRT 的修改版固件，在国内常被称做「梅林固件」
  - [Koolshare 修改版梅林固件](https://koolshare.cn/forum-96-1.html)：在 Asuswrt-Merlin 的基础上，增加了软件中心等 Koolshare 特色功能

- [Review: ASUSWRT router firmware](https://www.ctrl.blog/entry/review-asuswrt.html)：关于 ASUSWRT 的一篇评测，指出了系统的一些缺点和安全性弱点

### padavan/rt-n56u

基于华硕 RT-N56U 等型号路由器的开源代码二次开发而成的路由器固件，支持基于 MT7620 系列芯片的大量无线路由器。在国内经常被称做 Padavan 或老毛子固件。

- [padavan/rt-n56u 官方 Bitbucket 仓库](https://bitbucket.org/padavan/rt-n56u)
  - [荒野无灯修改版](https://80x86.io/page/padavan)
  - [hiboy 修改版](https://opt.cn2qq.com/padavan/)

- [开源固件的前世今生](https://www.right.com.cn/forum/thread-215106-1-1.html)：关于 ASUSWRT 和 padavan 的一些历史

### RouterOS

来自 MikroTik 的无线路由器操作系统，可在通用 x86 硬件（软路由）、以及 MikroTik 自家硬件上运行。

在 x86 软路由上使用 RouterOS，需要购买软件授权。但大部分 MikroTik 自家的硬件附送了 RouterOS 授权，可免费使用。

RouterOS 功能强大，但入门门槛较高，需要经过专门的学习才能熟练操作。

- [RouterOS 官网](https://mikrotik.com/software)

### pfSence/OPNSense

基于 FreeBSD 的开源网络操作系统，防火墙功能比较强大。内置的软件包管理器可以方便地安装更多软件、扩充功能，例如 Suricata IPS、ntopng 流量统计工具等。

由于 pfSense/OPNSense 基于 FreeBSD，也可以方便地安装 FreeBSD 软件包，例如安装 java 后运行 UniFi Controller。

- [pfSense 官网](https://www.pfsense.org/download/)
- [OPNSense](https://opnsense.org/): 原为 pfSense 的一个分支，因不满 pfSense 开源许可证的变化而创建
  - [pfSense® CE vs OPNsense®: technical comparison](https://www.firewallhardware.it/en/pfsense-vs-opnsense-technical-comparison/)

### VyOS

开源的路由器/防火墙操作系统，基于 Vyatta，功能强大，但仅支持通过 CLI 配置，不支持图形化界面。

- [VyOS 官网](https://www.vyos.io/)
- [Vyatta - VyOS Wiki](https://wiki.vyos.net/wiki/Vyatta)

### EdgeOS

来自 Ubiquiti 的网络操作系统，与 VyOS 同样基于 Vyatta，但拥有图形化界面，支持通过 [UNMS](https://unms.com/) 集中管理。

EdgeOS 仅能运行在 Ubiquiti 自己的 [EdgeRouter](https://www.ui.com.cn/edgemax/edgerouter/) 硬件上。另外 [UniFi Security Gateway](https://www.ui.com.cn/unifi-routing/usg/) 的操作系统也基于旧版的 EdgeOS。

- [EdgeOS User Guide](https://dl.ubnt.com/guides/edgemax/EdgeOS_UG.pdf)


### 爱快 iKuaiOS

免费的软路由操作系统，具有强大的流控功能。

部分旧版本的 iKuaiOS，有不少人反映有流量劫持等问题。

- [iKuaiOS 官网](https://www.ikuai8.com/product/rjcp/routersystem.html)
- [强烈谴责爱快的劫持行为。速来测试](https://www.anywlan.com/thread-393451-1-1.html)

### Tomato

易用的开源路由器操作系统。

* [Tomato Firmware | Polarcloud.com](http://www.polarcloud.com/tomato)
* [Tomato by Shibby » Alternatywne oprogramowamie na routery](https://tomato.groov.pl/)
* [AdvancedTomato :: Open Source Broadcom Firmware](https://advancedtomato.com/)
* [Tomato Koolshare 修改版](https://koolshare.cn/forum-102-1.html)
* [Tomato - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/Tomato)
* [Fresh Tomato](http://freshtomato.org/):  对老机型友好，仍在更新，支持 Multi-WAN、IPv6、QoS 等
### DD-WRT

- [DD-WRT 官网](https://dd-wrt.com/)

### 高恪

适配 K2P、newifi 3 等无线路由器，特色功能包括网管流控、内容协议识别、客户端访问网址查询等

缺点：

1. 如果想要网络类型为 NAT1，需要付费购买授权
2. 目前还不支持 IPv6

- [高恪官网论坛固件发布区](http://www.gocloud.cn/bbs/forum-51-1.html)

## 组网相关

### mesh 网络、有线回程

mesh 网络在多台无线路由器间相互组网，以提高 Wi-Fi 覆盖范围。

- [Mesh无线网络的定义与WiFi的区别](https://www.mr-wu.cn/mesh-wu-xian-wang-luo-de-ding-yi-yu-wifi-de-qu-bie/)
- 不同型号设备间的 mesh<br>部分厂商的不同型号设备间，可以进行 mesh 组网，从而可以充分利用旧设备，节省成本。典型的有华硕的 AiMesh。

  - [AiMesh](https://www.asus.com/Microsite/AiMesh/cn/)
- 不同厂商设备间的 mesh
  - [EasyMesh](https://www.wi-fi.org/zh-hans/discover-wi-fi/wi-fi-easymesh)<br>Wi-Fi联盟制定的标准，旨在使不同厂商设备可互操作，通过Wi-Fi联盟EasyMesh认证的设备即可以共同进行组网。作为一项较新的技术标准，目前支持的设备还不多，国内关注的厂商主要有华为、中兴、烽火、友讯等。
  
- 有线回程<br>大多数厂商的无线 mesh 系统，都支持有线回程功能。即 mesh 节点之间的通信，通过有线的方式进行，进一步增大带宽和稳定性。确定是需要重新复杂的布线工作。

  - [Mesh 路由器有线回程布线方案](https://xoyozo.net/Blog/Details/mesh-wired-backhaul#)
- 三频 mesh<br>部分厂商的高端无线路由器型号，拥有一个独立的 5GHz 频段，用于 mesh 节点之前的通信，不占用无线路由器与终端进行通信的频段。这样做也能一定程度上提高带宽、稳定性，且减少了布线带来的麻烦。
  - [豪宅必备的2200Mbps三频Mesh路由器：Linksys 领势 Velop 3只套装版评测](https://post.smzdm.com/p/akmr7wq4/)

### 有线路由器 + AC + AP

通过有线路由器 + AC + AP 的方式，能够保证最佳的速度和稳定性。不过这样的方案需要更复杂的布线，一般用于企业、酒店、商场等场所。家用时需要在装修前考虑。

大部分厂商的 AC + AP 方案也不是为家用涉及，一般配置比较复杂。不过 TP-LINK、H3C 等厂商目前也推出了家用 AP 套装，并将路由器与 AC 整合在单个设备上，可直接放入弱电箱，节省空间。

另外，Ubiquiti 的无线 AP 方案，由于不需要 AC、配置简单、拥有友好的图形化界面，也受到了一部分家庭用户的喜爱。

无线 AP 除了可以放置在桌面和柜子，也可以选择面板式或吸顶式，从而更好地融入装修风格，并节省空间。

- [Difference Between Access Point and Router](https://www.ligowave.com/difference-between-access-point-and-router)
- [无线AP,胖AP和瘦AP的区别？](https://www.zhihu.com/question/59991119)
- [如何组建一个完善的家庭无线 Wi-Fi 网络？](https://www.zhihu.com/question/35789817)
- [老生常谈，搭建无线AP，到底面板好还是吸顶好](https://www.chiphell.com/thread-1930326-1-1.html)
- [吸顶式AP挂墙、放桌面，哪种效果好？](http://koolshare.cn/thread-123920-1-1.html)

### VLAN 划分

通过划分 VLAN 的方式，可以使用一根网线传输多个网络的流量。例如同一根网线实现 Internet 和 IPTV 流量的复用。

* [IPTV单线复用折腾记--新思路近完美解决0812更新](https://koolshare.cn/thread-120569-1-1.html)

### 单臂路由

对于只有一个网口的设备（例如普通家用电脑、Intel NUC、Raspberry Pi 开发板等），如果想做为路由器使用，可通过单臂路由的方式实现。

单臂路由相当于在一个接口上创建多个子接口，不同子接口对应不同的 VLAN，从而实现将一个接口做为多个接口来使用。

- [【教程】LEDE单臂软路由安装心得](https://nipgeihou.com/router-on-a-stick/)

## 技术概念

### MU-MIMO

MU-MIMO 是 802.11ac Wave 2 中增加的特性，能够让多个设备同时与无线路由器进行通信，提高无线的利用效率和吞吐量。

但 MU-MIMO 需要终端设备的支持，且存在较多限制，目前对网络体验的提升并不明显。

在 Wi-Fi 6 中，MU-MIMO 的到了增强，可能会随着 Wi-Fi 6 的普及而变得更加实用。

- [Multi-user MIMO - Wikipedia](https://en.wikipedia.org/wiki/Multi-user_MIMO)

- [TP-LINK 的 MU-MIMO 介绍页面](https://www.tp-link.com/common/Promo/en/MU-MIMO/MU-MIMO.html)

- [Why You Don't Need MU-MIMO](https://www.smallnetbuilder.com/wireless/wireless-features/33100-why-you-don-t-need-mu-mimo)

### Wi-Fi 6、Wi-Fi 6E、Wi-Fi 6+

Wi-Fi 6 是最新一代的 Wi-Fi 标准，基于 IEEE 802.11ax，通过多项技术提升了多用户接入下的稳定性和吞吐量。2019 年之后上市的不少无线路由器，已经支持 Wi-Fi 6。

- [何为 802.11AX (WI-FI 6)？](https://www.arubanetworks.com/assets/_zh-hans/so/SO_80211ax.pdf)
- [Wi-Fi CERTIFIED 6](https://www.wi-fi.org/discover-wi-fi/wi-fi-certified-6)
- [Wi-Fi 6 对我们的日常生活有哪些帮助 | 科普 - 少数派](https://sspai.com/post/60464)

Wi-Fi 6E 则将 Wi-Fi 6 扩展到了 6GHz 频段。

- [Wi-Fi Alliance® brings Wi-Fi 6 into 6 GHz](https://www.wi-fi.org/news-events/newsroom/wi-fi-alliance-brings-wi-fi-6-into-6-ghz)
- [Wi-Fi 6E: The Basics - SmallNetBuilder](https://www.smallnetbuilder.com/basics/wireless-basics/33227-wi-fi-6e-the-basics)

Wi-Fi 6+ 是华为的 Wi-Fi 6 方案，增加了动态窄频宽等特性，能够自动调整频宽，兼顾吞吐量和覆盖范围。具体技术细节暂时没有太多公开文档。

### 160MHz 频宽

802.11ac 和 Wi-Fi 6 支持 160MHz 频宽，使用 160MHz 频宽能够大幅度提升 Wi-Fi 带宽，但是由于兼容性和干扰等问题，实际效果需要受到多种因素的影响，需要自行测试。

- [160 MHz Wi-Fi Channels: Friend or Foe? - SmallNetBuilder](https://www.smallnetbuilder.com/wireless/wireless-features/33210-160-mhz-wi-fi-channels-friend-or-foe)
- [160 MHz Wi-Fi Channels: Revisited - SmallNetBuilder](https://www.smallnetbuilder.com/wireless/wireless-features/33212-160-mhz-wi-fi-channels-revisited)

### PA/LNA/功放

在阅读路由器的评测、产品介绍页面时，经常会看到 PA、LNA 等概念。其中，PA 为功率放大器，用于增强发射信号的功率，LNA 为低噪声放大器，用于增强接收到的信号。

拥有 PA/LNA 的无线路由器/AP，能够获得更好的信号。

* [什么是PA，与LNA的区别是什么-电子发烧友网](http://m.elecfans.com/article/711953.html)
* [Understanding the Basics of Low-Noise | DigiKey](https://www.digikey.com/en/articles/techzone/2013/oct/understanding-the-basics-of-low-noise-and-power-amplifiers-in-wireless-designs)
* [amplifier - What is a PA/LNA? - Electrical Engineering Stack Exchange](https://electronics.stackexchange.com/questions/237267/what-is-a-pa-lna)

## 软硬件功能

### UPnP/NAT-PMP/端口映射

路由器通过家用宽带接入 Internet 时，运营商会为其分配一个 IP 地址。但家庭中会有电脑、手机等多种设备，多个设备都需要访问 Internet，这时候路由器为各个设备分配一个内网 IP，通过网络地址转换（NAT）来访问 Internet。

但是，通过 NAT 的方式，内网中的设备只能主动发起对外的连接，而不能做为服务器，接收外部的连接。这种情况下，想从外部访问家中的 NAS 等设备、远程控制家中的电脑等，都会变得比较困难。同时 BT、eMule 等 P2P 分享工具的上传下载速度也会受到影响、部分语音/视频通话工具的连接质量也可能受到影响。

针对这种情况，可通过端口映射，将内网设备的端口映射到公网，来实现外部访问。大部分家用路由器都支持手动配置端口映射，也支持通过 UPnP/NAT-PMP 的方式进行自动端口映射。

- [P2P 网络核心技术：UPnP 和 SSDP 协议](https://zhuanlan.zhihu.com/p/40407669)
- [NAT端口映射协议 - 维基百科](https://zh.wikipedia.org/zh-hans/NAT%E7%AB%AF%E5%8F%A3%E6%98%A0%E5%B0%84%E5%8D%8F%E8%AE%AE)
- [RFC6886 - NAT Port Mapping Protocol (NAT-PMP)](https://tools.ietf.org/html/rfc6886)

### DDNS

DDNS 也是大部分家用路由器都会拥有的一个常见功能。由于家庭宽带的公网 IP 是不固定的，每次重启路由器，都可能获取到一个新的 IP 地址。通过 DDNS，能够通过一个固定的域名来从外部访问家庭网络中的设备。

- [动态DNS - 维基百科](https://zh.wikipedia.org/zh-cn/%E5%8B%95%E6%85%8BDNS)
- [DDNS简单教程](https://zhuanlan.zhihu.com/p/46580280)

### 流量整形与 QoS

在家用场景下，部分应用需要比较高的带宽，但对延迟不敏感（例如在线视频、P2P 下载等）；部分应用对带宽要求不高，但对延迟敏感（例如网络游戏、语音/视频通话等）。

在家中，往往会遇到 P2P 下载等占用了较大的带宽，影响了网络游戏、音视频通话等应用的流畅程度，甚至正常的浏览网页也会变慢。通过 QoS 可以解决这一问题。

大部分中高端型号的家用路由器都提供 QoS 功能，能够手动设置不同设备、不同应用的优先级，例如提高某款游戏，或家中某台游戏机的优先级。

另外 fq_codel 和 CAKE 等算法在家用路由器上也逐渐得到了应用，可以做到无需复杂的配置，智能的管理流量。这项功能在 OpenWrt 中被称为 SQM，在其他路由器固件中的「智能 QoS」、「智能队列」等选项，一般也是指的这项功能。

- [服务质量 - 维基百科](https://zh.wikipedia.org/zh-cn/%E6%9C%8D%E5%8A%A1%E8%B4%A8%E9%87%8F)
- [Introduction - Bufferbloat.net](https://www.bufferbloat.net/projects/bloat/wiki/Introduction/)
- [OpenWrt Project: QoS (aka Network Traffic Control)](https://openwrt.org/docs/guide-user/network/traffic-shaping/packet.scheduler)
- [OpenWrt Project: SQM (aka Smart Queue Management)](https://openwrt.org/docs/guide-user/network/traffic-shaping/sqm)
  - [「智能队列」如何改善你的家庭网络质量 - 少数派](https://sspai.com/post/64870)
- [openwrt下各种qos(sqm,石像鬼，qosv4，nft-qos，emong-qos)使用心得 - OPENWRT专版 - 恩山无线论坛 - Powered by Discuz!](https://www.right.com.cn/forum/thread-511173-1-1.html)
- [Traffic Shaper — Configuring Traffic Shaping | pfSense Documentation](https://docs.netgate.com/pfsense/en/latest/trafficshaper/traffic-shaping-guide.html)<br>pfSense 中的流量整形配置指南
	- [How I Maximized the Speed of My Non-Gigabit Internet Connection](https://www.speedtest.net/insights/blog/maximized-speed-non-gigabit-internet-connection/)<br>speedtest.net 工程师的一篇博文，介绍了作者在家中的 pfSense 路由器上，是如何配置 QoS 的

### Captive Portal

Captive Portal 提供了一个网页认证页面，在网页中输入密码，才能访问网络。

在家庭网络中，Captive Portal 常用于访客网络，访客需要在网页中输入密码后连接，避免了 Wi-Fi 密码被类似「Wi-Fi 万能钥匙」等软件泄漏。 同时，也可以在 Portal 页面加入使用须知、免责声明等内容，用户同意后才能连接；如果是在店铺中使用，还可以利用 Portal 页面投放广告。

Captive Portal 功能常见于商用和企业级设备，家用路由器支持此功能的不多。对于 OpenWrt 等开源系统，可使用 WiFiDog 等工具实现 Captive Portal。

- [WiFiDog](http://dev.wifidog.org/)
  - [OpenWrt Project: WiFiDog captive portal](https://openwrt.org/docs/guide-user/services/captive-portal/wireless.hotspot.wifidog)
- [UniFi - Guest Network, Guest Portal, and Hotspot System – Ubiquiti Networks Support and Help Center](https://help.ubnt.com/hc/en-us/articles/115000166827-UniFi-Guest-Network-Guest-Portal-and-Hotspot-System)

### 内网穿透

由于 IPv4 地址资源有限，部分运营商不会给家庭宽带用户分配公网 IPv4 地址。这时候，如果需要访问家庭网络中的服务，就需要内网穿透功能。

常见的内网穿透方式有两种，一种是通过服务器进行中转，不过一般需要自己购买 VPS 服务器并搭建环境。或者购买专门的商业服务。

另一种是通过 NAT 打洞的方式实现。这种方式优点是设备间能够直接通信，避免消耗服务器流量，一定程度上提高速度。缺点是 NAT 打洞一般使用 UDP 协议，流量较大的情况下可能会被部分 ISP 限速。

- 通过服务器中转方式实现的内网穿透工具
  - [SSH 端口转发](https://www.ibm.com/developerworks/cn/linux/l-cn-sshforward/index.html)
  - [ngrok](https://ngrok.com/)

- 同时支持 NAT 打洞和服务器中转的内网穿透工具
  - [ZeroTier](https://www.zerotier.com/): 主打 NAT 打洞，NAT 打洞成功率较高。打洞失败后回退到服务器中转。
  - [frp](https://github.com/fatedier/frp): 支持多种协议的内网穿透工具
  - [nps](https://github.com/ehang-io/nps): 支持多种协议的内网穿透工具
  - [花生壳](https://hsk.oray.com/): 商业服务，包含 DDNS 和内网穿透，操作简单
  - [Tailscale](https://tailscale.com): 与 ZeroTier 类似，基于 WireGuard®

- 其他
  - [Synology QuickConnect](https://www.synology.com/zh-cn/knowledgebase/SRM/help/SRM/RouterApp/internet_quickconnect)：群晖路由器/NAS 中的外部访问服务，通过群晖的服务器进行中转，仅支持访问路由器、NAS 中的部分应用
  - [UniFi Remote Access](https://help.ubnt.com/hc/en-us/articles/115012240067-UniFi-How-to-Enable-Remote-Access-for-Remote-Management): Ubiquiti UniFi Controller 中的外部访问服务，通过 NAT 打洞或通过 Ubiquiti 服务器进行中转，仅支持访问 UniFi Controller

### 家长控制

家长控制功能能够控制特定设备的上网时长，避免子女上网时间过长。

部分路由器的家长控制功能，还可以限制设备访问不良网站，同时强制打开 Google 搜索、YouTube 的安全搜索功能，避免子女接触到不良内容。

而 Synology Safe Access 等提供了更强大的家长控制，除了控制上网时长、限制访问内容，还拥有强大的分析与统计功能，能够根据统计信息来分析家庭中不同人的上网习惯。

* [Synology Safe Access](https://www.synology.com/zh-cn/srm/feature/device_content_control)
* [华硕 AiProtection](https://www.asus.com.cn/AiProtection/)
* [eero Secure](https://eero.com/shop/eero-secure)

### 内容过滤

通过内容过滤功能，可以根据规则，过滤恶意广告、恶意网站、追踪器、成人网站等内容，保护安全与隐私，获取更好的上网体验。同时可以与家长控制结合，限制未成年人访问不适合当前年龄的内容。

* 基于 DNS 的过滤工具
  * [Pi-hole](https://pi-hole.net/)
  * [AdGuard Home](https://adguard.com/zh_cn/adguard-home/overview.html)
  * 大部分路由器的广告过滤功能，也是基于 DNS 实现的
* 基于代理服务器的过滤工具<br>基于代理服务器的过滤工具，拥有更好的过滤效果，但需要通过 HTTPS 中间人攻击的方式，来实现更复杂的过滤规则。在安全性方面，需要自行了解其工作原理并选择是否使用。
  * [KoolProxy](https://koolshare.cn/thread-64086-1-1.html)（已停止维护）
* 广告过滤的法律/道德问题<br>部分人认为，是否选择过滤广告是用户的自由；部分人认为，广告过滤会对互联网生态产生不利影响。关于是否应该进行广告过滤，请参考互联网中的讨论。

### IPS/IDS

IPS/IDS 功能通过分析报文中的内容，来记录和阻止具有安全风险的报文，提高家庭网络的安全性。与其他基于域名/DNS 的方案相比，IPS/IDS 能够识别更多安全威胁，但也消耗了更多 CPU 和内存资源。

常见的开源 IPS/IDS 软件有 Snort 和 Suricata，部分路由器的官方固件也提供有 IPS/IDS 功能。

* [Snort](https://www.snort.org/)
* [Suricata](https://suricata-ids.org/)
	* [Synology Threat Prevention](https://www.synology.com/zh-cn/srm/feature/secure_network_foundation)
	* [UniFi Threat Management](https://help.ubnt.com/hc/en-us/articles/360006893234-UniFi-USG-UDM-Configuring-Internet-Security-Settings)
* [华硕 AiProtection](https://www.asus.com.cn/AiProtection/)
* [Norton Core Router](https://us.norton.com/core)

### 流量统计/DPI

流量统计功能能够分析和统计网络中各个设备流量的使用情况。不过因为需要占用 CPU 和存储资源，部分低端型号的路由器不具备这样的功能。

而一部分路由器拥有基于 DPI 的流量统计，除了能统计各个设备的流量使用情况，还能统计各个应用的流量，从而提供更详细的流量统计数据。

对于开源系统，可使用 ntopng 等工具实现流量统计：

- [ntopng – ntop](https://www.ntop.org/products/traffic-analysis/ntop/)

### 多 WAN 口、多拨

部分路由器拥有多个 WAN 口，可接入多条宽带，实现带宽叠加。并实现一条宽带故障时切换到另一条宽带。

此外还有路由器能通过 USB 接口连接 LTE 网卡，或者使用 Android、iOS 的 USB 网络共享功能，实现在宽带故障时，使用 4G/LTE 链路实现 Internet 的备份。

对于 OpenWrt、RouterOS 等系统，还可以在一个 WAN 口上建立多个 PPPoE 会话，实现「单线多拨」，提高带宽。但部分运营商不支持多拨，具体请参考办理宽带时，与运营商签订的协议。

- [OpenWrt Project: Multiwan](https://openwrt.org/docs/guide-user/network/wan/multiwan/multiwan_package)
  - [LEDE/OpenWrt使用macvlan和mwan3实现单线多拨 | Acris' Blog](https://acris.me/2017/06/25/Load-balancing-multiple-PPPoE-on-LEDE/)
- [VLOG | 你想知道的ROS如何实现单线多拨，多线接入叠加宽带，轻松实现千兆网速。 – Vedio Talk - VLOG、科技、生活、乐分享](https://www.vediotalk.com/archives/3040)
- 通过 4G/LTE 实现 Internet 备份
  - [Synology 的 USB/3G/4G 网络共享](https://www.synology.com/zh-cn/compatibility?search_by=category&category=usb_3g_4g_dongles&p=1)
  - [Ubiquiti | UniFi | Manageable LTE WAN Failover](https://unifi-lte.ui.com/)

### 带宽提升

一些路由器宣称具有「物理带宽提升」的功能，实际上是通过与运营商合作的方式实现的，运营商可以动态地调整带宽限制，付费后自动提高带宽。

「迅雷快鸟」是比较著名的一个网络加速服务，同时有第三方开发者将其移植到路由器，能够在路由器上方便地打开提速服务。

- [迅雷快鸟 Xunlei Network Accelerator For Router](https://github.com/fffonion/Xunlei-Fastdick)
- [迅雷快鸟 - 带宽加速神器插件 - KoolShare](http://koolshare.cn/thread-34888-1-1.html)

### 游戏加速

游戏加速也是不少家用无线路由器的一大卖点。一般通过提高游戏的 QoS 优先级来实现，同时内置「网易 UU 加速器」等服务，通过第三方提供的代理服务器连接到更高质量的网络，实现网游加速。

- [网易UU网游加速器 - 路由器插件](https://uu.163.com/router/direction.html)
- [网易UU网游加速器 - 合作款路由器](https://uu.163.com/router/crossover.html)

- [Recommended Routers & Controllers | NVIDIA GeForce NOW](https://www.nvidia.com/en-us/geforce-now/recommended/)

### 智能家居整合

智能家居属于新兴领域，在路由器中整合智能家居相关功能，不同厂商有着不同的思路。

- Apple: 自动为 HomeKit 设备设置严格的防火墙规则，提高安全性。同时支持 PPSK 认证，避免泄漏主 Wi-Fi 密码
  - [HomeKit 路由器 - Apple 支持](https://support.apple.com/zh-cn/guide/security/seccab60e931/1/web/1)
  - [Apple lists the cameras and routers that will be compatible with the latest HomeKit features - 9to5Mac](https://9to5mac.com/2019/11/27/apple-lists-the-cameras-and-routers-that-will-be-compatible-with-the-latest-homekit-features/)
  - [eero Now Supports Apple HomeKit](https://blog.eero.com/eero-now-supports-apple-homekit/)
- 小米：米家设备连 Wi-Fi 免输密码，提高初次设置设备时的便捷程度；同时为只能设备提供独立的频段，避免过多智能设备拖慢网速
  - [小米AIoT路由器 AX3600](https://www.mi.com/r3600)（参考「智能设备接入」相关描述）
- Google: 整合语音助手 Google Assistant；之前的 OnHub 产品还可以充当 ZigBee 网关，控制 Phillips Hue 智能照明系统
  - [Exclusive: New Google Nest Wifi adds an Assistant speaker - 9to5Google](https://9to5google.com/2019/09/17/exclusive-google-nest-wifi-assistant/)
  - [Google OnHub | Philips Hue](https://www2.meethue.com/en-ca/friends-of-hue/google-onhub)
- 华为：为智能家居设备提升 QoS 优先级，使设备能够快速响应；同时也支持为自动智能家居设备设置防火墙规则
  - [华为路由 A2 - 华为商城](https://www.vmall.com/product/10086534540521.html)（参考页面中关于 IoT 设备的描述）
- HomeBridge、Home Assistant 整合<br>对于开放的路由器操作系统，还可以实现在路由器上运行 HomeBridge，或者将路由器接入 Home Assistant。
  - [RT1900ac 路由器折腾笔记：安装 Homebridge 和 Plex Media Server – Blanboom](https://blanboom.org/2017/plex-on-rt1900ac/)
  - [OpenWRT - Home Assistant](https://www.home-assistant.io/integrations/openwrt/)
  - [misenhower/homebridge-unifi-led-control](https://github.com/misenhower/homebridge-unifi-led-control): 通过 HomeBridge 控制 UniFi 设备上的 LED

### 运行第三方应用

不少路由器操作系统，可以通过一定的方式运行第三方应用，扩展路由器的功能，使路由器更加「智能」。

- 软件包管理系统<br>和不少 Linux/UNIX 发行版一样，一些基于 Linux/UNIX 的路由器操作系统，也有着自己的软件包管理系统。
  - [OpenWrt 的 Opkg Package Manager](https://openwrt.org/docs/guide-user/additional-software/opkg)<br>OpenWrt 完全采用 Opkg 做为其软件包管理系统，整个系统，包括内核模块和驱动，都由 Opkg 管理。
  - [pfSense 的软件包管理系统](https://docs.netgate.com/pfsense/en/latest/packages/package-manager.html)<br>pfSense 基于 FreeBSD，除了安装 pfSense 自己的软件包，也可以方便地安装 FreeBSD 软件包。
- 软件中心<br>不少路由器操作系统拥有带有图形化界面的软件中心，可以方便地以图形化的方式添加软件。不过也有一部分路由器，例如 TP-LINK 的部分型号，其「软件中心」只是一系列内置功能的开关，无法做到安装第三方软件扩充功能。
	- [Koolshare 软件中心](https://koolshare.cn/forum.php?mod=forumdisplay&fid=98&filter=typeid&typeid=103)<br>来自 Koolshare 论坛的软件中心，支持 OpenWrt、ASUSWRT 等多种路由器操作系统，提供了适合国内用户使用的特色软件。
	- [Synology SRM 套件中心](https://www.synology.com/zh-cn/srm/packages)<br>Synology Router Manager (SRM) 操作系统自带的软件中心，目前仅有来自 Synology 的少量软件。但是来自 Synology DSM 的部分软件，经过修改后，也可以在 SRM 软件中心中手动安装。
- Entware/Optware<br>不少路由器操作系统，例如 Asuswrt-Merlin、DD-WRT、Synology Router Manager 等，默认不支持安装第三方软件，或者对第三方软件的支持有限，可通过 Entware/Optware 的方式来安装软件。
  - [Entware/Entware: Ultimate repo for embedded devices](https://github.com/Entware/Entware)
  - [Optware/Optware-ng](https://github.com/Optware/Optware-ng)
  - [Entware · RMerl/asuswrt-merlin Wiki](https://github.com/RMerl/asuswrt-merlin/wiki/Entware)
  - [Installing Entware - DD-WRT Wiki](https://wiki.dd-wrt.com/wiki/index.php/Installing_Entware)
- docker<br>由于部分支持 Docker 的路由器操作系统，还可以通过 Docker 运行容器，来运行第三方软件。
  - [Persistent PiHole via Docker on UDMPro : Ubiquiti](https://www.reddit.com/r/Ubiquiti/comments/dvik8g/persistent_pihole_via_docker_on_udmpro/)

### 虚拟化

部分路由器操作系统具有一定的虚拟化功能，能够在路由器中运行其他的容器或操作系统。

一种常见的应用，利用 RouterOS 的 Metarouter 功能来运行 OpenWrt，实现在一台设备上同时使用 RouterOS 和 OpenWrt 的特色功能。

* [RouterOS KVM](https://wiki.mikrotik.com/wiki/Manual:KVM): 在路由器中运行虚拟机
* [RouterOS Metarouter](https://wiki.mikrotik.com/wiki/Manual:Metarouter): 轻量级的虚拟路由器，能够运行 RouterOS、OpenWrt 等系统

### 手机 App

目前的不少主流的家用路由器，都支持使用手机 App 来控制。但对于一些较为流行的开源的路由器操作系统，会有一些第三方开发者为其开发 App。

这些第三方 App 的质量和安全性不一定有保证，使用前需要先对 App 的功能、作者、开源情况等做一个初步的了解。

- [啪嗒路由器app，适配Padavan老毛子固件的手机端控制app - 恩山无线论坛](https://www.right.com.cn/forum/thread-315066-1-1.html)
- [WinboxMobile](https://septudio.com/winboxmobile)
- [‎DD-WRT on the App Store](https://apps.apple.com/us/app/dd-wrt/id897098616)

### SNMP

少量的家用路由器操作系统（例如 Synology Router Manager），以及绝大多数商用/企业级网络设备，都支持 SNMP。通过 SNMP 协议，可实现对设备的集中管理和集中监控（例如利用 Cacti 采集流量统计数据 ）。

- [UniFi开启snmp功能可供网络流量监测工具抓取UniFi-AP数据 - 深圳捷联讯通科技有限公司](https://wiki.edcwifi.com/index.php?title=UniFi%E5%BC%80%E5%90%AFsnmp%E5%8A%9F%E8%83%BD%E5%8F%AF%E4%BE%9B%E7%BD%91%E7%BB%9C%E6%B5%81%E9%87%8F%E7%9B%91%E6%B5%8B%E5%B7%A5%E5%85%B7%E6%8A%93%E5%8F%96UniFi-AP%E6%95%B0%E6%8D%AE)

### 网络存储、媒体中心

有很多路由器带有 USB 接口，可以连接 USB 移动硬盘，实现网络存储等功能。

此外，也有带有 SATA 接口和带有 M.2 接口的无线路由器，可以直接将硬盘装入路由器内部，外观更加紧凑：

- [小米路由器HD](http://www.mi.com/miwifihd): 内置 SATA 接口的硬盘

- [华硕 BRT-AC828](https://www.asus.com/Business-Networking/BRT-AC828/): 内置 M.2 接口，可以安装 M.2 接口的 SSD

在功能上，连接硬盘后，无线路由器完成如下任务：

- 通过 SMB/AFP/NFS 等协议实现文件共享
  - [OpenWrt Project: Samba](https://openwrt.org/docs/guide-user/services/nas/cifs.server)
- Time Machine（Mac 电脑备份）
  - [OpenWrt Project: AFP Netatalk 分享配置 (又名 Apple Time Machine).](https://openwrt.org/zh/docs/guide-user/services/nas/netatalk_configuration)（本教程使用 AFP 协议实现 Time Machine，但 AFP 协议目前已过时，可参考教程内容，改用 SMB 协议实现）
- WebDAV<br>不少 App 支持使用 WebDAV 协议同步文件（例如 DEVONthink 笔记软件），通过 WebDAV，可使用自己的路由器做为文件同步服务。
  - [OpenWrt 上通过 WebDAV 共享文件 – lookas2001](https://lookas2001.com/openwrt-%E4%B8%8A%E9%80%9A%E8%BF%87-webdav-%E5%85%B1%E4%BA%AB%E6%96%87%E4%BB%B6/)
- OwnCloud / NextCloud<br>OwnCloud 和 NextCloud 是一款多功能的网盘/个人云软件，可用于搭建个人网盘，同时支持安装插件扩展功能。
  - [OpenWrt Project: OwnCloud or NextCloud](https://openwrt.org/docs/guide-user/services/nas/owncloud)
- 远程下载<br>通过远程下载功能，可以将路由器做为下载机使用，无需长期打开电脑下载。
  - [OpenWrt 安装及配置 Aria2 教程 | 米V米](https://www.mivm.cn/openwrt-aria2/)
  - [OpenWrt Project: Transmission configuration](https://openwrt.org/docs/guide-user/services/downloading_and_filesharing/transmission)
  - [在 OpenWRT 上使用 aMule 下載資源](https://butui.me/post/amule-on-openwrt/)
- 媒体中心<br>通过媒体中心，可以将路由器做为媒体服务器使用，在手机、平板、电视、游戏机等设备上直接播放路由器硬盘中的视频。
  - [OpenWrt Project: DLNA Media Server](https://openwrt.org/docs/guide-user/services/media_server/dlna)
  - [RT1900ac 路由器折腾笔记：安装 Homebridge 和 Plex Media Server – Blanboom](https://blanboom.org/2017/plex-on-rt1900ac/)（由于大部分家用路由器性能不足，不推荐安装 Plex Media Server）
  - [Easiest Plex Set-Up Ever: Nighthawk X10 R9000 Router by NETGEAR](https://www.netgear.com/landings/plex/): 官方支持 Plex Media Server 的无线路由器
- 将第三方软件安装在外部存储设备<br>大部分无线路由器的内置存储空间一般较小，可通过外部存储设备扩展空间，将软件安装在外部存储设备上。
  - [OpenWrt安装软件到外置存储（U盘/移动硬盘） - 简书](https://www.jianshu.com/p/5549241429d0)

### 第三方服务整合

部分无线路由器能够整合第三方服务，实现更高级的自动化。

- [IFTTT](https://ifttt.com/)
  - [ASUS Router works better with IFTTT](https://ifttt.com/asusrouter)
  - [TP-Link Router works better with IFTTT](https://ifttt.com/tplink_router)
  - [z-george-ma/openwrt-iot: IoT support for OpenWRT based router](https://github.com/z-george-ma/openwrt-iot)
- [iOS 快捷指令](https://support.apple.com/zh-cn/guide/shortcuts/welcome/ios)
  - [‎DS router on the App Store](https://apps.apple.com/us/app/ds-router/id963699443): Synology Router Manager 的手机 App，支持 iOS 快捷指令
- Alexa
  - [ASUS ROUTER: Alexa Skills](https://www.amazon.com/ASUS-ROUTER/dp/B07285G1RK)
  - [Amazon Alexa Smart Home Connected Routers by NETGEAR](https://www.netgear.com/landings/amazon-alexa/)
  - [What is the TP-Link Router Alexa Skill and how do I use it?](https://www.tp-link.com/us/support/faq/1569/)
  - [Amazon Alexa | D-Link](https://us.dlink.com/en/alexa)
  - [eero now works with Amazon’s Alexa](https://blog.eero.com/announcing-eeros-alexa-skill-available-today/)

### Bonjour/mDNS

通过 Bonjour 功能，能够使 Apple 设备直接通过 `.local` 域名访问路由器，无需记住复杂的 IP 地址。

除了 Apple 设备，目前有不少智能家居设备（例如米家的 Wi-Fi 设备），以及 Chromecast 等，也开始使用 Bonjour 协议。如果家中的网络比较复杂（例如有多个子网/多个 VLAN），可使用 Bonjour 网关的功能，来实现在多个网络之间通过 Bonjour 来发现设备。

- [OpenWrt Project: Zero configuration networking in OpenWrt](https://openwrt.org/docs/guide-user/network/zeroconfig/zeroconf)
- [Need Bonjour across VLANs? Set Up an Avahi Reflector!](http://chrisreinking.com/need-bonjour-across-vlans-set-up-an-avahi-gateway/)
- [UniFi - Best Practices for Managing Chromecast/Google Home on UniFi Network – Ubiquiti Networks Support and Help Center](https://help.ubnt.com/hc/en-us/articles/360001004034-UniFi-Best-Practices-for-Managing-Chromecast-Google-Home-on-UniFi-Network#create)

### 校园网

不同学校的校园网有着不同的认证方式，部分学校还会使用私有协议。对于校园网，建议先在学校论坛等社区了解本校的校园网是否可以在 OpenWrt 等设备上连接和认证。

* [liuqun/njit8021xclient: 南京工程学院802.1X客户端（Linux版兼容H3C/iNode V2.40-F0335）](https://github.com/liuqun/njit8021xclient)：802.1x 认证
* [MentoHUST (简体中文) - ArchWiki](https://wiki.archlinux.org/index.php/MentoHUST_(简体中文))：锐捷认证
* [drcoms/drcom-generic: Dr.COM/DrCOM 现已覆盖 d p x三版。](https://github.com/drcoms/drcom-generic)：Dr.COM 认证
* [路由器认证校园网的一个思路 | Damon Lee 's blog](http://blog.zhenglee.top/2018/08/09/%E8%B7%AF%E7%94%B1%E5%99%A8%E8%AE%A4%E8%AF%81%E6%A0%A1%E5%9B%AD%E7%BD%91%E7%9A%84%E4%B8%80%E4%B8%AA%E6%80%9D%E8%B7%AF/index.html)：Portal 认证

## 安全性

### 相关文章

- [Home Router Security Report 2020](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/HomeRouter/HomeRouterSecurity_2020_Bericht.pdf)

### 开源固件 vs 闭源固件

在有条件的情况下，尽量使用开源固件，或使用声誉良好的闭源固件/原厂固件。

如下为部分商业固件/闭源固件可能会拥有的「特色功能」：

- 劫持 404 页面
  - [如何看待小米路由进行 404 网页劫持？ - 知乎](https://www.zhihu.com/question/30358197)
- 网页中插入广告
  - [网页篡改，满屏广告，你的斐讯路由器被绑架了！ - 知乎](https://zhuanlan.zhihu.com/p/51273981)
- 收集统计信息/遥测数据、甚至直接收集用户的隐私数据
  - [Ubiquiti adds phone-home to the access point firmware | Hacker News](https://news.ycombinator.com/item?id=21430997)
  - [斐讯路由收集用户隐私数据 用户应立刻使用第三方固件|蓝点网](https://www.landiannews.com/archives/21406.html)
- 对于部分安全漏洞，厂商没有动力及时修复
  - [Several Netgear Router Models Are Vulnerable to Hackers | WIRED](https://www.wired.com/2016/12/ton-popular-netgear-routers-exposed-no-easy-fix/)



### 官方版固件 vs 修改版固件

有不少人和不少组织，会基于 OpenWrt、Padavan、Asuswrt-Merlin 等开源系统，或者部分厂商的官方固件进行修改，使其符合更多人的使用习惯。

一般来说，在安全性方面，使用官方发布的固件，或者基于开源代码自行编译，是最为安全的。而修改版固件质量参差不齐，可能会解决官方固件中的一些安全问题，但又有可能引入新的安全风险。在安全性方面，可以从如下几点做一个简单的判断：

- 修改版固件是否开源<br>修改版固件保持开源，有利于用户通过检查源代码等方式，确保相关修改不引入安全漏洞。例如 [coolsnowwolf/lede](coolsnowwolf/lede)，就在 GitHub 上公开了基于 OpenWrt 修改后的源代码。
- 修改版固件的知名度/使用人数<br>用户较多的修改版固件，如有安全漏洞，有利于更快地被发现和暴露。从而有利于及时修复。
- 修改版固件是否通过安全的方式发布<br>如果固件以 HTTPS 方式下载，并提供 HASH 和 GPG 签名校验，有利于保证固件的下载过程不被中间人攻击。而通过 HTTP 下载、通过百度网盘等方式下载的固件，可能会导致下载过程被中间人攻击，导致下载到被替换的固件。
- 修改版固件是否跟随主项目，同步合入主项目最新的安全更新<br>可通过版本日志、Git commit log 等方式，观察修改版固件是否及时跟随主项目，进行安全性相关更新与修改。
- 排查修改版固件的默认设置是否安全
  - 防火墙规则是否默认允许从外部访问路由器中的服务
  - 是否默认使用不安全的协议（HTTP、telnet 等）进行外部访问<br>（例如从[这篇帖子](http://koolshare.cn/thread-10237-1-1.html)的配图可以看到，Koolshare 梅林固件之前的远程 Telnet 功能，是通过 HTTP 协议实现的，可能会存在安全性问题。不过目前 Koolshare 梅林固件已经采取其他方式实现远程登录）
- 系统更新、软件中心等功能，是否使用不安全的协议下载，且不进行签名校验<br>一般来说，系统更新或者软件中心等功能，需要实现 HTTPS 下载或签名校验，以避免中间人攻击。Koolshare 软件中心[旧版就使用过 HTTP 方式](http://koolshare.cn/forum.php?mod=viewthread&tid=60134)进行下载，不过已经及时修复。
- 部分比较小众的功能，建议评估安全风险后使用
  - 例如是否存在功能需要通过 HTTPS 解密，在电脑上安装证书后才能使用
  - 或者是否存在使用 FTP、HTTP WebDAV 等未加密协议的文件共享功能

### 软件更新

厂商和固件开发者可通过软件更新等方式，修复安全漏洞。选择固件时，需要考虑固件是否及时进行安全更新、是否采用安全的方式进行更新。

- 对于商业固件/闭源固件
  - 确认自动更新时是否使用加密方式，或进行签名校验
  - 从更新日志中，观察软件更新是否及时、是否有安全漏洞休息
  - 在 [CVE List](https://cve.mitre.org/cve/search_cve_list.html)、[国家信息安全漏洞共享平台](https://www.cnvd.org.cn/flaw/list.htm?flag=true)等网站进行搜索和调查，观察相关漏洞是否及时修复
- 对于开源固件<br>部分开源固件不包含自动更新功能，需要通过一定的方式关注其软件更新。主要要如下集中方式。
  - 定期关注系统的 Release Notes
  - 订阅开源项目的邮件列表，通过邮件的方式获取安全更新相关信息
  - 在 GitHub 中 watch 对应的开源项目，及时收到项目更新的通知

### Linux 安全特性的应用

不少家用路由器，并没有应用 [ALSR](https://en.wikipedia.org/wiki/Address_space_layout_randomization) 等 Linux 内核已经提供的安全特性。一定成带上上削弱了设备的安全性。

- [Build Safety of Software in 28 Popular Home Routers](https://cyber-itl.org/assets/papers/2018/build_safety_of_software_in_28_popular_home_routers.pdf)<br>本文分析了 28 款最流行的家用路由器对 Linux 相关安全特性的应用，并给出了购买建议。

### KRACK

KRACK 是对 WPA2 协议的一种攻击方式，在购买无线路由器或选择固件时，需要考虑对应的路由器或固件，是否已包含针对 KRACK 的修复。

- [KRACK Attacks: Breaking WPA2](https://www.krackattacks.com/)
- [KRACK - 维基百科，自由的百科全书](https://zh.wikipedia.org/zh-hans/KRACK)
- [WPA2 “KRACK”漏洞简介与重现](https://paper.seebug.org/512/)

### WPA3

WPA3 是新的 Wi-Fi 安全协议，改进了 WPA2 的一些安全性弱点。

同时，WPA3 支持 Wi-Fi Enhanced Open 模式，为开放、无密码的 Wi-Fi 网络提供了加密机制，一定程度上增强了安全性，适合图书馆、商场等公共场所的 Wi-Fi 网络。

目前已有少量无线路由器支持 WPA3。另外，部分无线路由器（例如 Synology RT2600ac）和终端设备（例如 iPhone），已通过软件更新的方式支持了 WPA3。

- [安全性 | Wi-Fi Alliance](https://www.wi-fi.org/zh-hans/discover-wi-fi/security)
- [What Is WPA3, and When Will I Get It On My Wi-Fi?](https://www.howtogeek.com/339765/what-is-wpa3-and-when-will-i-get-it-on-my-wi-fi/)
- [Wi-Fi CERTIFIED Enhanced Open™ delivers data protection in open Wi-Fi® networks](https://www.wi-fi.org/news-events/newsroom/wi-fi-certified-enhanced-open-delivers-data-protection-in-open-wi-fi-networks)

### 防火墙配置

在能够获取到公网 IP 的环境中，合理配置防火墙，避免路由器中的服务被外部访问，有利于提高安全性。

- [适用于家用场景的电信 IPv6 网络和防火墙配置](https://zhuanlan.zhihu.com/p/40836019)
- [请教： IPv6“内网”设备透出到到公网的正确姿势 - V2EX](https://www.v2ex.com/t/530084)

###SSID 隐藏、MAC 地址过滤等功能是否能提高安全性？

隐藏 SSID、MAC 地址过滤等功能，对提高安全性的作用有限，所以不建议打开：

* [Wi-Fi 路由器和接入点的推荐设置 - Apple 支持](https://support.apple.com/zh-cn/HT202068)

## 网络质量优化

* 无线网络相关参数的调整与优化
	* [802.11 无线网络参数解惑](https://beijinglug.club/wiki/doku.php?id=docs:wifi)
* AirTime Fairness
	* [Airtime Fairness On or Off](https://routerguide.net/airtime-fairness-on-or-off/)


## 基础设施

### 装修与布线

- [五类/超五类/六类/超六类/七类等多类网线的比较](https://network.51cto.com/art/201801/563938.htm)
- [装修那点破事 篇三：外番 — 被坑的网线 - 什么值得买](https://post.smzdm.com/p/560761/)
- [万兆光纤布网实战攻略，让光纤铺满你家！](https://www.bilibili.com/video/av59732534/)
- [对于数码控，在装修方面有哪些好的设计？ - 知乎](https://www.zhihu.com/question/21170551)
- [家庭 10Gbps 网络施工指南 – Yachen's Blog](https://yach.me/2020/08/29/家庭-10gbps-网络施工指南/)

### 弱电箱、机柜

- [抢救家庭弱电箱大作战 - 什么值得买](https://post.smzdm.com/p/427001/)
- [风扇多真可以为所欲为之弱电箱整理 - 什么值得买](https://post.smzdm.com/p/alpoe0k0/)
- [开年第一贴:家庭网络机柜及网络拓扑 - Chiphell](https://www.chiphell.com/thread-1209486-1-1.html)

### 其他创意

* [使用乐高积木搭建 UniFi 机架](https://community.ui.com/stories/How-my-Mini-Lego-Unifi-Rack-came-to-be/5eaabfb6-390c-4db0-a323-7ed938a5b651)
* [3D 打印的 UniFi 机架](https://otichi.com/from-asus-to-unifi.html)
* [Ubiquiti Unifi Dream Machine Wall Mount](https://www.d3d.shop/listing/779073493/ubiquiti-unifi-dream-machine-wall-mount)

## 网络诊断、调试工具

* [Speedtest by Ookla](https://www.speedtest.net/) 知名的测速工具
* [DSLReports Speed Test](http://www.dslreports.com/) 网络测速工具，支持 Bufferbloat 测试
* [Fing App](https://www.fing.com/products/fing-app) 局域网扫描、测速工具
* [iPerf](https://iperf.fr/) 命令行测速工具，可以搭建在云端进行 ISP 测速，也可以搭建在本地，测试路由器、交换机、Wi-Fi 的最大吞吐量
* [WiFiman](https://blog.ui.com/2018/12/11/introducing-wifiman/) Wi-Fi 扫描、局域网扫描、测速工具
* [BestTrace](https://www.ipip.net/product/client.html) 图形化的 `traceroute` 工具，能够将 traceroute 结果显示在地图上
* [nali](https://github.com/meteoral/Nali) 为 `ping`, `traceroute`, `nslookup` 等命令增加中文地理位置信息
* [WiFi魔盒](https://wis.ruijie.com.cn/wmg/static/homepager/index.htm) 多功能 Wi-Fi 检测工具，能够在多个 AP、mesh 组网等情况下，进行 Wi-Fi 漫游测试
* [AirPort 实用工具](https://apps.apple.com/cn/app/airport-%E5%AE%9E%E7%94%A8%E5%B7%A5%E5%85%B7/id427276530) Wi-Fi 扫描与信号强度检测工具（由于系统的限制，这是 iOS 上唯一一个能实现相关功能的工具）
* [iStumbler](https://istumbler.net/) macOS 上的 Wi-Fi 扫描工具
* [WiFi Explorer](https://www.adriangranados.com/) macOS 上的 Wi-Fi 扫描工具
* [Hurricane Electric Network Tools](https://networktools.he.net/) 用于 iOS 和 Android 的网络工具箱，包含 DNS 查询、接口信息、iPerf、Bonjour 浏览器等多种工具
* [Rumble Network Discovery](https://www.rumble.run/) 功能强大的局域网扫描工具
* [macOS 自带的无线诊断](https://support.apple.com/zh-cn/guide/mac-help/mchlf4de377f/mac) macOS 自带「无线诊断」工具，具有 Wi-Fi 扫描、查看 Wi-Fi 日志、推荐最佳 Wi-Fi 频段、Wi-Fi 性能监控、抓包等功能
* [TP-LINK 网络百宝箱](https://apps.apple.com/app/id1502063951)
* [Netool.io - Network Engineer Tool](https://netool.io/) 小巧便携的网络诊断工具
* [PingTools](https://pingtools.org/) Android 上便携的网络扫描工具

## ISP 相关

###  运营商选择

按照大部分人的经验，移动宽带访问国外网站速度快，电信宽带国内线路质量较高，联通宽带则比较均衡。不过，不同地区之间存在较大差异，需要实际测试才能知道真实情况。

另外，部分地区运营商还提供「国际精品网」等业务，能够加速国外网站的访问。

- [电信，联通，和移动哪个宽带更好? - 知乎](https://www.zhihu.com/question/30744052)
- [联通和电信宽带区别 - V2EX](https://www.v2ex.com/t/566413)
- [中国电信的国际精品网业务到底有什么用？ - 知乎](https://www.zhihu.com/question/20749587)
- [吐一下中国移动的宽带。DNS 污染的不只是一点点呀... - V2EX](https://www.v2ex.com/t/452546)
- [为什么同是移动网络，移动4G 与 移动宽带 体验怎么差别那么大? - 知乎](https://www.zhihu.com/question/54220923)
- [运营商流量穿透是什么？ - 知乎](https://www.zhihu.com/question/52390237)

### 公网 IP、IPv6 地址的获取

目前国内 IPv6 逐渐普及，越来越多的运营商，开始分配 IPv6 地址，设置路由器后就能分配到。

但 IPv4 地址资源更加紧缺，不少地区已经无法获取到公网 IPv4 地址。

在无法获取到 IPv6 地址，或者没有公网 IPv4 地址的情况下，可以尝试拨打运营商客服电话，申请获取公网 IP 或 IPv6 地址。但由于 IPv4 地址资源有限，即使是拨打客服电话，也有可能申请不到公网 IP。

另外，部分地区可以通过特殊的用户名、或者通过付费购买的方式获取公网 IP。

- [广东电信拨号加pub就是公网ip-远景论坛](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1789805)


### 光猫改桥接，使用路由器拨号

在光猫 NAT 性能不足的情况下，可将光猫修改为桥接模式，使用路由器拨号，提高性能。

大部分地区都可以拨打运营商电话，要求运营商远程将光猫修改为桥接模式。也可以上网根据光猫型号，查找光猫的超级密码或进行破解，并在管理页面中修改为桥接模式。

但部分地区的千兆宽带，光猫改桥接之后，带宽反而会下降。

- [中国电信天翼光猫改桥接模式方法 | Yeboyzq Blog](https://www.yeboyzq.com/luyoujiaohuan/984.html)
- [上海电信千兆改桥接会限速？好像，被我不小心破解了？ - KoolShare](https://koolshare.cn/thread-151416-1-1.html)

### IPTV 相关

- IPTV 单线复用
  - [网络设备 篇一：家庭网络改造-单线复用实践总结_值客原创_什么值得买](https://post.smzdm.com/p/alpzdxpo/)
- 组播转单播，实现在电脑、iPad 等设备上观看电视
	- [udpxy+xupnpd，IPTV+智能电视 完美解决方案 - 简书](https://www.jianshu.com/p/3f9018c6d2bf)

### 相关政策、投诉方式

- 家用宽带不允许对外提供 Web 服务
	- [家庭宽带 私设 web 被检测 魔都电信被停宽带 - V2EX](https://www.v2ex.com/t/608821)
- 工信部投诉
	- [如何更快更好地投诉运营商？ - 知乎](https://zhuanlan.zhihu.com/p/22405071)
	- [中华人民共和国工业和信息化部](http://www.miit.gov.cn/)

## 常见误区、Q&A

### 终端只支持 2x2 MIMO，没有必要选用 3x3 MIMO 或 4x4 MIMO 的无线路由器？

目前大多数移动设备只支持 1x1 MIMO 或者 2x2 MIMO，但不少高端的家用路由器，都已经支持 4x4 MIMO 了。不少人认为选择 4x4 MIMO 的无线路由器并没有必要。

但实际上，路由器和终端的无线电发射功率是固定的，支持 4x4 MIMO 的无线路由器，能够通过多根天线接收和发送相同的数据，来提高吞吐量和 Wi-Fi 覆盖面积。

具体请参考如下链接中的介绍：

- [How To Buy A Wireless Router - 2018 Edition - SmallNetBuilder](https://www.smallnetbuilder.com/basics/wireless-basics/33177-how-to-buy-a-wireless-router-2018-edition)
  - [Diversity gain - Wikipedia](https://en.wikipedia.org/wiki/Diversity_gain)
  - [Spatial multiplexing gain - Wikipedia](https://en.wikipedia.org/wiki/Spatial_multiplexing_gain)

## 综合案例

* [Unifi全家桶高级组网方案](https://bbs.ui.com.cn/t/unifi/48147)
* [Tour of Home Network 2020 - The 8-Bit Guy](https://www.youtube.com/watch?v=Ev0PL892zSE)
* [EP19 - 安装配置pfsense 配置安全可靠的家用网关 - NGXHK](https://www.bilibili.com/video/av15823557/)

## 欢迎参与

欢迎通过[提交 Issue](https://github.com/blanboom/awesome-home-networking-cn/issues/new)，或[提交 Pull request](https://github.com/blanboom/awesome-home-networking-cn/pulls) 的方式，为本文档做出贡献。

本文档遵守[参与者公约](code-of-conduct.md)，此外，在做出贡献时，请注意以下几点：

1. 本文档遵守 CC BY 协议，请确保新增内容与此协议兼容，避免加入有版权的内容
2. 本文档不接受违反中华人民共和国法律法规，或不适合在中国大陆地区公开讨论的内容
3. 本文档主要关注家用网络设备，暂不考虑过于专业的企业级设备


## 许可证

[![CC-BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

本作品采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

