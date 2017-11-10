# GFW翻墙小结

![](http://i.v2ex.co/Ur503skA.jpeg)

## 前言

政府无限的权力，都是大部分人自己放弃的。假货坑爹，让政府审核。孩子管不好，让政府关网吧。有人在微博骂我，让政府去删。房价太高，让政府去限购。我们的文化实在太独特，创造出了家长式威权政府，GFW 正是在这种背景下产生的，一个社会矛盾的终极调和器，最终生活不能自理的你每天做的每一件事情都要给政府审查一遍，以免伤害到其他同样生活不能自理的人。这是一个零和游戏，越和这样的用户打交道，越对未来持悲观态度，觉得 GFW 可能永远也不会消失，而墙内的这个局域网看起来还似乎生机勃勃的自成一体，真是让人绝望。

Via [@clowwindy](https://twitter.com/clowwindy) - https://www.v2ex.com/t/166417#reply121

---

## 更新记录

2017年11月11日 - copy from internet

2017年08月01日 - 更新中国App Store下架翻墙软件的临时解决方案，增加国外访问国内加速器快帆

2017年07月31日 - 更新梅林固件软件中心内翻墙软件shadowsocks下架的临时解决方案，增加丝滑云

2017年06月21日 - 移除百度浏览器/赛风，增加开源方案MEOW，增加路由器固件KoolShare，增加付费方案VPNso

2017年04月14日 - 增加iOS免费方案Shadowsocks Wingy

2017年02月09日 - 更新shadowsocks.com为shadowsocks.com.hk

2017年01月24日 - 移除土行孙，更新shadowsocksr-csharp/shadowsocks-windows/ShadowsocksX-NG/shadowsocks-android

2016年08月23日 - 恢复土行孙，增加COW，分离Shadowsocks/ShadowsocksR/ShadowsocksX-R

2016年04月29日 - 移除土行孙，增加V2Ray，影梭，Shadowrocket，佛跳墙

2016年02月23日 - 增加Surge，感谢@刘亚晨

2016年01月08日 - 增加首选免费方案XX-Net，更新付费方案土行孙

2015年12月23日 - 尊重@东哥的要求，移除XXX

2015年11月28日 - 更新XXX和土行孙付费方案

2015年10月11日 - 移除fqrouter和红杏，增加shadowsocks-android和GreenVPN

2015年08月31日 - Thanks @clowwindy & @breakwa11, and all of the contributor of the shadowsocks.

2015年08月11日 - 移除GoAgentX，感谢@ohdarling

2015年08月06日 - 移除曲径，感谢两位前盛大创新院朋友做出的贡献，尊重你们的决定

2015年05月22日 - 移除所有Goagent项目，增加赛风/红杏/Shadowsocks免费账号

2015年03月08日 - fqrouter复活，新增免费方案百度浏览器

2015年02月07日 - 修改细节描述，避免误导大家

2015年02月03日 - 更换网址为f(翻)q(墙)，感谢fqrouter作者做出的贡献

2014年11月30日 - 完善内容，标注自用首选免费和付费翻墙方案

2014年08月24日 - 新增免费方案GoAgent+，付费方案商业版Shadowsocks

2014年06月15日 - 新增Buckyball浏览器，父亲节快乐

2014年06月13日 - 补充Mac/iOS方案

2014年06月12日 - 撰写初稿

阅读原文 - https://wsgzao.github.io/post/fq/

**扩展阅读**

- Contributors - http://shadowsocks.org/en/about/contributors.html

- 科学上网利器 Shadowsocks 使用方法 - http://ttt.tt/150/

---

## 简单验证是否被墙

> 如果你不能访问以下网址，那恭喜你生活在墙的有效保护区内，关键字智能屏蔽效果如下

http://wsgzao.github.io/post/gfw-break/

----

## 免费方案

> 各个平台的解决方案都不唯一，请认真阅读原文中的说明部分

### XX-Net

> 接力GoAgent翻墙工具----Anti-censor tools

- 【首选】GAE proxy, 稳定、易用、快速
- 用过GoAgent的朋友应该还有印象吧

https://github.com/XX-net/XX-Net

### V2Ray

> V2Ray作者关于V2Ray的话"我是只是一名普通的开发人员，已肉翻，本已不依赖这些翻墙工具，但 ShadowSock 和 GoAgent 被迫删除代码的事件实在太恶心，不得不做点什么了。"

https://www.v2ray.com/

### Shadowsocks

> shadowsocks各版本的GitHub源码和发布地址

https://github.com/shadowsocks/shadowsocks-windows/releases

https://github.com/shadowsocks/ShadowsocksX-NG/releases

https://github.com/shadowsocks/shadowsocks-android/releases

### ShadowsocksR

> @breakwa11的私人项目，目前已删除也许从此停止更新

https://github.com/shadowsocksr

https://github.com/shadowsocksr/shadowsocksr-csharp/releases

https://github.com/shadowsocksr/ShadowsocksX-NG/releases

https://github.com/shadowsocksr/shadowsocksr-android/releases

### COW

> HTTP proxy written in Go. COW can automatically identify blocked sites and use parent proxies to access.

- COW 是一个简化穿墙的 HTTP 代理服务器。它能自动检测被墙网站，仅对这些网站使用二级代理。

https://github.com/cyfdecyf/cow

### MEOW

> MEOW is a fork of COW that uses whitelist mode.

- MEOW 是 [COW](https://github.com/cyfdecyf/cow) 的一个派生版本，MEOW 与 COW 最大的不同之处在于COW 采用黑名单模式， 而 MEOW 采用白名单模式,国内网站直接连接，其他的网站使用代理连接

https://github.com/renzhn/MEOW

### Shadowsocks 免费账号

> 感谢ishadowsocks团队分享

http://ss.ishadowx.com/

### iOS Surge/Shadowrocket/Shadowsocks Wingy

>Shadowsocks client for iPhone/iPad.

- 【首选】iOS翻墙方案
- iOS 9以上版本Surge/Shadowrocket或许是你的最佳选择之一
- 错过Surge的就别再错过Shadowrocket和免费的Wingy
- 请切换除中国区以外的账号登录，比如美国的App Store

http://yach.me/

https://itunes.apple.com/app/shadowrocket/id932747118

https://itunes.apple.com/app/wingy-mian-fei-banvpn-ke-hu/id1148026741

---

## 路由器翻墙

### KoolShare

> 路由器固件有很多比如OpenWRT/DD-WRT/Merlin/Tomato等，我这里推荐使用koolshare编译的版本

http://firmware.koolshare.cn/

https://github.com/koolshare/koolshare.github.io/tree/acelan_softcenter_ui/shadowsocks

``` bash
# 通过ssh连接路由器手动执行命令安装
cd /tmp
wget --no-check-certificate --timeout=15 https://raw.githubusercontent.com/koolshare/koolshare.github.io/acelan_softcenter_ui/shadowsocks/shadowsocks.tar.gz
tar -zxvf /tmp/shadowsocks.tar.gz
chmod +x /tmp/shadowsocks/install.sh
sh /tmp/shadowsocks/install.sh
```

## 国外访问国内

### 快帆

> 最好的免费海外访问国内加速器

http://www.speedin.cc/

---

## 付费方案

>请根据自身实际需求，睁大眼睛认真阅读各类网站说明后做出合理的选择

### Shadowsocks商业版

>轻量级科学上网姿势，改变您的生活体验

- 【首选】由[@Showfom](http://ttt.tt/about/)运营
- 我已经在第一时间入坑高级版至2018年
- 信任.Trust，以下是我的推荐链接

https://portal.shadowsocks.com.au/aff.php?aff=43

### VPNso

> 免费稳定的科学上网方式越来越少，最后推荐vpnso的ShadowSocks版本自用保底，请珍惜每一个提供稳定服务的商家

https://vpnso.com/buyss/24793

### SIHuaCloud

> 原佛跳墙，引用GreenVPN的一句话，期待与您有缘相见

http://ftq.link/?r=wsgzao
