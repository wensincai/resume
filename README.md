### 个人名片
<table>
	<thead>
	<th>姓名</th><th>GitHub</th><th>Blog</th><th>学校</th><th>专业</th><th>学历</th><th>mobile</th><th>email</th>
	</thead>
	<tbody>
	<tr>
	<td>孙焕然</td><td><a href="http://github.com/abbshr">@abbshr</a></td><td><a href="http://digitpie.cf">DigitPie</a></td><td>哈尔滨工业大学</td><td>软件工程</td><td>本科</td><td>18704624517</td><td>abbshrsoufii@gmail.com</td>
	</tr>
   </tbody>
</table>

HIT FoOTOo实验室成员

### 能力概述

擅使JavaScript/Node.js/CoffeeScript, 也会Ruby, C, Lua, Lisp. 喜欢异步编程. 能够熟练运用Web技术、Hack手段以及多种JavaScript奇淫巧技. 遵循ES5规范， ES6的Promise。

完整阅读过RFC 6544 WebSocket Protocol, 实现了一个WebSocket库, 并在实验室和俱乐部做过一期关于RealTime Web的技术分享讲座. 对计算机网络有所研究, 曾实现过Node.js版的GBN协议模型和停等协议, 对WebRTC技术有一定了解.

阅读了Connect框架的源码. 能使用Express, LoopBack, Sinatra, Connect, React, cheerio, libgit2等库和框架构建应用或工具. 数据库常使用LevelDB、MongoDB, 也用过Redis, RethinkDB.

熟悉Linux大部分命令、系统/网络管理技术和Bash脚本编程. 懂得Git底层工作机制, 并能熟练使用Git进行版本控制以及应用开发.

正在学clisp, 了解lambda演算等函数式编程的思想及理论基础.

读过Node.js和libuv部分源码, 清楚其实现机制, 如Node启动, 流机制, 模块加载, 事件循环, 事件触发等等, 修改编译过一个自定义版的Node.js.

除此之外, 完整阅读了比特币创业公司bitpay的开源项目insight-api源码, 并贡献了代码, 做过BitCoin BlockChain的数据可视化与分析.

### 主要实现作品

- 完整web应用 & 后台服务:
	* [Yinle.me](https://github.com/abbshr/Yinle.me-architecture): 私有项目. 一款Node.js编写的面向校园的云打印服务, 曾得过IBM暑期夏令营的创新大赛二等奖. 经历了两次重构，重构使用了LoopBack框架，
		并扩展了扫码打印，打印机群管理，资源共享，在线支付等功能.
	* [ctheyvs](https://github.com/abbshr/ctheyvs): 一个外卖比价器. 综合运用了爬虫, 前端hack, 集群, 动态规划, 字符串模糊匹配算法等技术与理论.
	* [Git-Contacts](https://github.com/abbshr/Git-Contacts): 使用Git特性开发的通讯录共享服务, Ruby开发.
	* [Hugo](https://github.com/abbshr/lbs-app): 一个基于AMap地图的信息分享应用，使用CoffeeScript，RethinkDB，thinky，SemanticUI以及Angular.js构建.
	* [BlogOS](https://github.com/abbshr/BlogOS): 一个基于Node.js + Express + MongoDB的小型论坛系统. 支持后台统计管理.
- 数据可视化:
    * [env.BTC](https://github.com/abbshr/env.BTC): 基于开源项目insight/insight-api开发的比特币区块链数据可视化与分析系统, 部分完工.
- 其他应用:
    * [TeamChat](https://github.com/abbshr/FoOTOoRTCA): Node.js驱动, Sokcet.io + Express构建的RealTime团队通讯Web应用.
- 密码学研究:
	* [encryp2p](https://github.com/abbshr/encryp2p): 参考HTTPS的安全模型, 由Ruby编写的P2P文件加密共享程序, 实现了来源可靠性, 信息加密性以及完整性验证.

### 主要个人开源框架/库:
* JavaScript & Node.js
	- [RocketEngine](https://github.com/abbshr/RocketEngine): 一个完整的超轻量级Node.js WebSocket库, 无第三方模块依赖, 使用简单, 并且提供了Socket.IO尚未支持的流式API和二进制流传输。被用于Yinle.me的重构以及几个外包项目中。
	- [execq](https://github.com/abbshr/execQ): 曾用于RocketEngine库内部,  解决异步工作流次序问题.
	- [event.js](https://github.com/abbshr/event.js): 用于RocketEngine前端库内部, 在浏览器端实现异步操作的Pub/Sub观察者体系.
	- [node-adt](https://github.com/abbshr/node-adt): 将JSON数据转换成Tree ADT，增强对JSON数据操纵能力。
	- [read.i](https://github.com/abbshr/read.i): 解决Node.js中异步标准I/O的麻烦,方便终端输入
	- [colorlogger](https://github.com/abbshr/colorlogger): 实现彩色终端日志的输出与保存
	- [Lotterior](https://github.com/abbshr/Lotterior): Node/Coffee抽奖机，较高的可配置性
* Ruby
    - [gitdb](https://github.com/AustinChou/Git-Contacts/tree/git-repository): 封装了Git的底层操作，是Git-Contacts的源动力.
* CSS & HTML
    - [inkiron](https://github.com/abbshr/inkiron): 暑期实训项目写的类flat UI风格的前端CSS框架.