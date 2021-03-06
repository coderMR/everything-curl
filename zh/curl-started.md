## cURL的起源

在1996年，[丹尼尔 斯坦伯格](https://daniel.haxx.se/)正在利用琐碎时间编写一个聊天机器人：一款可以为聊天室提供服务的自动化程序。他突然想到，如果聊天机器人可以为聊天室中的用户提供当前汇率以及兑换外汇的业务，那将非常的有趣。

为了保证汇率的精确性，机器人必须反复的从相关网站上下载最新汇率数据。所以需要一个可以通过HTTP协议来下载相关数据的小工具。很快，丹尼尔发现了一款叫做httpget的小工具(作者是来自巴西的拉斐尔·塞格拉)。httpget只需要稍稍调整就可以胜任这项工作。很快，丹内尔接手了这几百行代码的维护工作。

HttpGet 1.0随后在1997年4月8日发布，并且具有最新的HTTP代理支持。

很快我们实现了“汇率支持”的业务功能，并且还为项目添加了FTP协议下载功能，所以项目也被更名为了urlget2.0，并于1997年8月发布。仅支持HTTP协议的日子成为了历史。

在之后的日子里，项目的功能慢慢完善起来。当上传功能被添加后，项目原有的名称又产生了误导性，所以项目再次被更名为了curl4，并于1998年3月发布（保留了原名称中的版本号）。

我们决定将**1998年3月20日**定为curl项目的生日。
