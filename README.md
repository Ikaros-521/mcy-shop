<p align="center">
  <a href="https://wiki.mcy.im">
    <img src="favicon.ico" width="120" height="120" style="border-radius: 20px;" alt="异次元店铺系统">
  </a>
</p>
<br>
<p align="center">
<span>
<img src="https://wiki.mcy.im/icon/php.svg" alt="php8.1">
</span>
<span>
<img src="https://wiki.mcy.im/icon/mysql-version.svg" alt="mysql5.6+">
</span>
<span><img src="https://wiki.mcy.im/icon/license.svg" alt="license"></span>
</p>

## 法律声明
> 本商城程序基于 MIT 协议开源，并且完全免费。该程序的初衷是为开发者提供学习和研究的机会。未取得合法资质，严禁将本程序用于任何商业用途，尤其是禁止利用本程序搭建平台进行商品销售。
>
> 用户在使用或学习本程序时，必须严格遵守法律法规。我们提倡依法行事，尊重法律，坚守法律，避免对社会产生不良影响。
>
> 使用本程序即表示您已充分理解并同意本法律声明的所有内容。

## 安装文档
- 官方文档：[https://wiki.mcy.im](https://wiki.mcy.im)

将安装包，上传到你的服务器，并且解压出来，比如解压到：/www/wwwroot/mcy-shop目录
进入解压出来的目录，执行SSH命令：cd /www/wwwroot/mcy-shop
给主程序777权限，执行SSH命令：chmod 777 bin console.sh，注意，这里必须是777权限，不要擅自修改权限
准备开始安装，执行SSH命令：./bin index.php，准备安装，**值得注意的是，SSH命令窗口是不能关闭的，如果你执行完这个命令后就关掉SSH窗口，那么你就等于关闭了安装程序 **
根据SSH命令窗口中的提示，使用浏览器访问http://IP地址:端口，进行安装，注意：如果访问不了，请检查防火墙是否放行对应端口
根据安装完成后的网页提示（SSH命令窗口也会提示），拿到反向代理地址 ，然后开始配置Nginx反向代理，根据下方教程配置完成后，访问：http://你的域名/admin，即可进入后台

## 快速体验
- 后台演示地址：http://42.51.0.159:4399/admin
  - 超级管理员演示账号：demo@qq.com 密码：abc123456
- 前台演示地址：http://42.51.0.159:4399/
  - 分站/客户演示账号：test  密码：abc123456

## 功能简介

萌次元商城系统基于`异次元店铺系统3.0`
全新重构，历时两年精心打磨，初心不改。我们采用纯原生PHP打造了一款极具潜力的个人创业型商城系统。数据库底层经过对`hyperf/database`
的深度优化，感谢`hyperf`开发团队提供的强大ORM组件。模版渲染引擎采用世界著名`symfony`团队开发的`twig`
，安全且高性能。以下为系统主要功能介绍，更多细节等待您亲自下载体验。

- **自主研发底层框架，支持多种部署环境**：兼容`FPM`和`CLI`双架构，构建从零到一的纯原生底层框架，适用于虚拟主机、虚拟VPS和高性能云服务器，支持超大型负载均衡部署，能够处理百万级并发。
- **全新内容安全过滤系统**：确保用户输入内容到数据库的安全性，不再强制过滤用户输入的`HTML`
  代码（如分站公告、商品介绍等需要`HTML`展示的内容），保证100%安全过滤用户提交的内容。
- **全站API二进制加密通讯**：使用AES加密，对所有API接口数据进行二进制加密传输，大幅提升数据传输的安全性和私密性。
- **插件系统**
  ：支持多种插件开发模式，包括控制器（API/VIEW）、管理菜单（后台/用户）、控制台命令（命令式插件开发）、进程（定时/后台任务等插件开发）、WebSocket（即时通讯类插件开发）、支付（支付插件开发）、货源（发货插件开发）、HOOK（页面/API钩子类插件开发）。
- **模板系统**：提供高扩展性的模板HOOK，支持控制器（API/VIEW）开发，方便开发者快速构建高性能、功能强大的插件及模板。
- **国际化支持**：完全支持i18n国际化，支持自定义显示国家货币及翻译内容。
- **丰富的用户角色设计**：适用于构建小型个人创业商城、及中大型货源平台及第三方经销商网站，包含平台（主站）、供货商、商家（分站/经销商）、顾客（会员）等多种角色。
- **分站独立插件/模板**：分站即主站，商家开通分站后，几乎拥有与主站相同的功能，可自主安装插件和模板，包括自定义支付接口，无需依赖主站的支付接口。
- **多样化的发货方式**：通过安装不同的发货插件，如虚拟卡密、游戏账号、实体商品实时物流、游戏充值业务、账号充值业务等，满足各种业务需求。

## 更多

- QQ群：941616478 - 广告：🈲
- [Telegram](https://t.me/acgshop) - 广告：🈲
- [Discord](https://discord.gg/MAduAfBvCK) - 广告：🉑
