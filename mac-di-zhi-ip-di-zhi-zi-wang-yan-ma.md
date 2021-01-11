# MAC地址\_IP地址\_子网掩码

##  MAC 地址

### 定义

* 每个网卡都有一个6字节（48bit）的MAC地址
  * 1字节为8bit，如40 -&gt; 0101 0101
* 全球唯一，固话在网卡的ROM中，由IEEE802标准制定
  * 前3字节：OUI：组织唯一标识符，由IEEE的注册管理机构分配给厂商
  * 后3字节：网络接口标识符，由厂商自行分配

![](.gitbook/assets/image%20%2849%29.png)

网卡查询：[http://standards-oui.ieee.org/oui.txt](http://standards-oui.ieee.org/oui.txt)     [https://mac.bmcx.com/](https://mac.bmcx.com/)

### 表示格式

![](.gitbook/assets/image%20%2848%29.png)

###  MAC地址操作

![](.gitbook/assets/image%20%2846%29.png)

###  MAC地址获取

![](.gitbook/assets/image%20%2842%29.png)

##  IP 地址

![](.gitbook/assets/image%20%2852%29.png)

###  IP地址的组成与计算

![](.gitbook/assets/image%20%2850%29.png)



#### 例子1

![](.gitbook/assets/image%20%2855%29.png)

按位与出来的 192.168.1.0，其中192.168.1是网络ID，0是主机ID，能有`256 - 2`个主机

#### 例子2

 IP地址：130.168.1.10

 子网掩码：255.255.0.0

 按位与**得网段：**130.168.0.0

* 其中，130.168是网络ID
* 0.0 是主机ID（主机位全0为网段，全1代表广播地址）
  * 所有，能有`256*256 - 2`个主机

![](.gitbook/assets/image%20%2854%29.png)

##  IP地址分类

![&#x8BE6;&#x7EC6;&#x7684;&#x5206;&#x7C7B;&#xFF0C;&#x767E;&#x5EA6;&#x5373;&#x53EF;](.gitbook/assets/image%20%2853%29.png)

