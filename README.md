# UoB.CS.Notes 计算机科学の硬核笔记

[![Badge](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg?style=flat-square)](https://996.icu/#/en_US)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)


## Networks 
### Lower Layers - 关于网络底层
* [TokenRing & Bus - 令牌环网](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/Networks/04.%20Lower%20Layers%20-%20%E5%85%B3%E4%BA%8E%E5%BA%95%E5%B1%82%E7%9A%84%E4%B8%80%E4%BA%9B%E7%A2%8E%E7%A2%8E%E5%BF%B5/09.%20TokenRing%20%26%20Bus%20-%20%E4%BB%A4%E7%89%8C%E7%8E%AF%E7%BD%91.md)

* [ATM - 异步传输: 固话公司的回马枪(笑](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/Networks/04.%20Lower%20Layers%20-%20%E5%85%B3%E4%BA%8E%E5%BA%95%E5%B1%82%E7%9A%84%E4%B8%80%E4%BA%9B%E7%A2%8E%E7%A2%8E%E5%BF%B5/10.%20ATM%20-%20%E5%BC%82%E6%AD%A5%E4%BC%A0%E8%BE%93.md)

* [WDM - 波分复用：辨色传信](https://github.com/YiLiuNat/LH-Networks.Notes/blob/master/Networks/04.%20Lower%20Layers%20-%20%E5%85%B3%E4%BA%8E%E5%BA%95%E5%B1%82%E7%9A%84%E4%B8%80%E4%BA%9B%E7%A2%8E%E7%A2%8E%E5%BF%B5/11.%20WDM%20-%20%E6%B3%A2%E5%88%86%E5%A4%8D%E7%94%A8%20%E4%B9%8B%E8%BE%A8%E8%89%B2%E4%BC%A0%E4%BF%A1.md)

* [总结 - 以太网即正义!](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/Networks/04.%20Lower%20Layers%20-%20%E5%85%B3%E4%BA%8E%E5%BA%95%E5%B1%82%E7%9A%84%E4%B8%80%E4%BA%9B%E7%A2%8E%E7%A2%8E%E5%BF%B5/12.%20%E6%80%BB%E7%BB%93%20-%20%E4%BB%A5%E5%A4%AA%E7%BD%91%E5%8D%B3%E6%AD%A3%E4%B9%89!.md)

<br/>

### Transport Layers - 传输层的奥妙

* [IP - 头文件的厉害](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/01.%20IP%EF%BC%8C%E5%A6%99%E4%B8%8D%E5%8F%AF%E8%A8%80.md)

* [IP中的分段 (Flags & Fragments)](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/02.%20IP%E4%B8%AD%E7%9A%84%E5%88%86%E6%AE%B5Flags%26Fragments.md)

* [(往期考题) Path MTU Discovery - 路径MTU发现：寻找两台主机之间最小MTU](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/03.%20PathMTU.md)

* [(重要考点) IPv4中的32位地址，以及地址分类那些破事](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/04.%20IPv432.md)

	* [Sub-Netting & Netmasks - 子网与掩码: 拆分我富裕的地址](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/05.%20sub-net.md)
	* [CIDR & Slash Notation - 无类域间路由(去掉类) & 斜线标注符](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/06.%20CIDR.md)
	
* [IPv6 - 大量的地址](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/07.%20IPv6.md)
	* [IPv6本质上是64位](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/08.%20IPv664.md)

* [以太网中的IP以及如何中转等杂事](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/09.%20IPEthernet.md)

* [Address Allocation - 地址分配](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/10.%20AddressAllo.md)

	* [IPv6的地址分配 - SLAAC](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/11.%20SLAAC.md)

* [TCP之后所有的](./Networks/05.%20Transport%20Layers%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82%E7%9A%84%E5%A5%A5%E5%A6%99/12.%20TCP.md)

<br/>

## Intelligent Data Analysis 智能数据分析(IDA)
### Page Rank 网页排名算法(佩琦算法)

这一章只整理了最后几页的:

* [Simplified Page Rank 之马尔可夫模型对它的诠释](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/01.%20Simplified%20Page%20Rank.md)

* [Damping Factor - 阻尼因子：给新生页面的权重补偿](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/02.%20Damping%20Factor.md)

* [Dangling Pages - 晃来晃去的网页 (致那些没有任何文献的页面)](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/03.%20Dangling%20Pages.md)

* [总结 - 概率学上对Page Rank的阐述](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/04.%20summary.md)

<br/>

### Gaussian Mixture Models 高斯混合模型

一些前提条件(概率密度函数):

* [Discrete Random Variables - 离散随机变量](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/05.%20Discrete%20Random%20Variables.md)

* [Gaussian/Continuous Random Variables - 连续(or 高斯)随机变量: 正态分布](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/06.%20Gaussian%20Random%20Variables.md)

* [Gaussian PDF (1D) - 高斯概率密度函数 (两分钟教会你画图!)](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/07.%20PDF.md)

* [Gaussian PDF (2D+) - 带你进入高维世界](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/08.%20PDF2D.md)

* [Visualising Multivariate Gaussian PDF - 多方差PDF的可视化](https://github.com/YiLiuNat/UoB.CS.Notes/blob/master/IDA/08.%20visualising.md)

* [Fitting a Gaussian PDF to Data - 将高斯PDF与数据组合(估算参数)](./IDA/09.%20fitData.md)

进入正题(高斯混合模型)：

* [Multi-modal Distributions & Gaussian Mixture Model - 多态分布&高斯混合模型](./IDA/10.%20MultiModal.md)

* [Estimating the Parameters of a GMM - 估算GMM的参数](./IDA/11.%20EstimatingGMMpar.md)
	* [E-M Algorithm 分割数据的妙招](./IDA/12.%20E-M%20Algorithm.md)

<br/>



## HCI Case Studies 案例
需求收集：
* [Tourist Information Centre Studies - 旅游问询中心案例 (脏又快的收集需求大法)](./HCI/01.%20Tourist.md)  

Information Probes 信息勘查：
* [Design with Unconventional Users - 与非传统用户一起设计](./HCI/02.%20information.md)  

Autoethnography 模仿用户行为:
* [Understand Mobile Medical Technology Use - 了解移动医疗设备的使用](./HCI/03.%20Autoethnography.md)  
