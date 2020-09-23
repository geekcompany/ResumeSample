

<div align="left">
	<table rules=none frame=void>
    <tr>
        <td align = "left" >钱磊 / 男 / 1990</td>
        <td align = "right" style="width:170px;"  rowspan = "7"><img src="https://gitee.com/suqianlei/Pic-Go-Repository/raw/master/img/20200922114203.jpg" align="cneter" /></td>
    </tr>
    <tr>
        <td align = "left">手机：15801030098（同微信号） </td>
    </tr>
    <tr>
        <td align = "left">Email：suqianlei@gmail.com </td>
    </tr>
    <tr>
        <td align = "left">博客：http://suroot.win </td>
    </tr>
    <tr>
        <td align = "left">Github：http://github.com/onlinelei  </td>
    </tr>
    <tr>
        <td align = "left">学历：本科 / 党员 / 河南大学民生学院 / 2015 年毕业 </td>
    </tr>
    <tr>
        <td align = "left">期望职位薪资：Java 中级开发  </td>
    </tr>
	</table>
</div>
## 专业技能
<p>
  Java：<progress value="90" max="100"></progress>
  jvm：<progress value="80" max="100"></progress>
  mysql：<progress value="85" max="100"></progress>
</p>
<p>
  spring：<progress value="60" max="100"></progress>
  redis：<progress value="60" max="100"></progress>
  python：<progress value="50" max="100"></progress>
</p> 

- 语言：Java / Python / C# / HTML / javaScript
- 框架：Spirng / MyBatis / Hibernate
- 数据库相关：MySQL / Oracle / Redis 
- 开发平台和工具：Windows / macOs / linux / IntelliJ IDEA / Eclipse
- 技能点：jvm / Git / GitLab / Gerrit / Svn / Maven / xxlJob / Kafka / RocketMQ /  nginx / docker 

---
## 公司：尚德机构 （ 2016 年 9 月 ~ 至今 ）所在部门：集团研发


### 项目：微信平台项目 
20 年 3 月我参与并主导了微信平台系统的开发。项目主要是通过第三方工具 WeHub 对微信运营数据的收集、分析、以及调用 WeHub 接口实现微信聊天。项目中我们运用了 RocketMq 作为微信消息的处理缓冲，使用有序消息队列做削峰处理，给微信下发消息使用的是 Redis 队列保证下发消息的间隔、有序发送，老师聊天页面使用 weSocket 通讯。这个项目我们遇到了不少技术难点都被一一克服，例如消费能力的提升、群成员消息风暴的消除、webSocket session 共享问题的解决等。项目快速的推进和稳步的迭代，有效减轻 BF 模式中老师的工作量，也收集了大量老师服务数据，对规范教学、以及决策层提供了重大帮助。  
**技术点**：springBoot、redis、mysql、websocket、wehub、SSO、ES

### 项目：天网标准版项目 
19年9月我参与了天网项目标准化的开发，该项目是公司第二个成功外售的 SaaS 系统。项目基于公司天网机会管理系统开发的标准版，引入了高可配置的设计方案，针对不同客户的业务场景，抽象出公共的机会字段，并提供给客户自定义字段的能力。不同客户间的数据做物理隔离，保证快速安全的扩展。项目中我们引入 MySql 5.8 版本的支持，扩展字段用 JSON 格式存储提升了主表的扩展能力。针对机会的查询和导出我们使用了 Es，减轻了查询对数据库造成的压力。项目完成后，童程童美等教育机构先后成功接入。  
**技术点**：springBoot、redis、mysql5.8、SSO、ES

### 项目：客诉工作台项目
18 年 10 月我主导并参与了客诉工作台项目的开发。该项目主要是对旧项目的改造升级，原有项目逻辑过于复杂，代码臃肿，针对客诉工单部分功能分离出新的系统。通过对旧系统进行了大量的代码逻辑梳理，抽离出业务逻辑主干线，对复杂、不需要的逻辑进行优化，或调整基数方案。该项目我们运用了 SpringBoot 作为主要框架、使用 rocketMq 作为和订单、工单的消息推送。在和订单系统交互中为了保证订单状态的一致性使用了 TCC 分布式事务。项目上线后，通过接入部分渠道，逐渐替代旧系统。旧系统产生的数据依旧在旧系统中完成流转，并在3个月内实现了旧系统功能的完全替代。  
**技术点**：springBoot、redis、mysql、SSO、activity、rocketMq、kafka、TCC

### 项目：SSO 单点登录系统

该项目是尚德机构内部的统一登录和权限中心服务，是尚德内部统一登录、权限管理的主要平台。改服务主要提供统一认证登录，包括用户扫码登录、手机验证码登录、账号密码登录、一次登录，各个子系统都不用再次登录的功能；用户角色接口、用户权限列表、统一管理用户的权限、用户角色权限的管理的 web 管理功能。项目基于的 cas 开源软件，cas-server-4.2.7 进行的二次开发，使用 gardle 完成项目的 jar 包管理，数据库使用的 mysql5.6，使用 redis 实现用户 TGT 的 session 共享。整个服务部署 3 个节点，对外使用 nginx 做负载均衡。其他系统使用 SDK + 配置文件的接入的方式，接入极其方便。主要为公司上万的员工进行大概 100 多个系统的统一认证登录以及权限管理。  
**技术点**：SSO、CAS、redis

**其他系统**：班主任工作台、质检工作台、日报系统、分账系统、抽奖活动、微信小程序后台

## 公司：龙源美生医疗投资有限公司 （ 2015 年 5 月 ~ 2016 年 9 月 ）所在部门：技术部-基础平台
龙源美生医疗投资有限公司是一家为医院提供管理服务平台的投资公司，主要业务有：孕期、产检、育儿、 疫苗接种，等全套服务管理平台，
### 项目：无线医疗Web项目
无线医疗项目是为河北省各大医院做的一套办公系统，项目中以AOP方式实现动态切换数据源、日志记录、权限控制。使用jxl实现报表导出excel，以及quartz定时器处理job任务，后期接入亿美短信服务，使用jueryPrint在线打印医疗本等功能的开发，以及条形码扫描实现疫苗入库，等功能的开发。后期报表的开发以及报表查询速度优化、表结构优化。  
**技术点**：Spring、SpringMVC、MyBatis、Oracle

### 项目：妈咪Baby App后台项目
妈咪Baby，是河北省各家医院主推给孕期妈妈的一款APP，在APP中可以看到当前自己的健康档案，以及疫苗接种情况，预约挂号。并根据孩子孕期、年龄推送育儿相关知识。  在后台项目中，我主要负责了App所需功能点的接口梳理与开发。项目中我们使用了Token鉴权，且接口数据传输皆为加密处理，后期开发了爬虫系统，定时爬取河北省相关政府网站新闻、以及其他信息。  
**技术点**：Spring、SpringMVC、MyBatis、Oracle、爬虫

---
## 参加的开源项目

 - [gold-miner](https://github.com/xitu/gold-miner)：掘金翻译计划，英译中技术社区
 - [doPi](http://github.com/yourname/projectname)：控制树莓派GPIO端口的java项目

## 技术文章

- [java 即时编译分享](http://suroot.win/2020/04/29/java-JIT%E5%8D%B3%E6%97%B6%E7%BC%96%E8%AF%91%E5%88%86%E4%BA%AB/) 
- [webSocke t接入问题总结](http://suroot.win/2020/04/28/java-webSocket%E6%8E%A5%E5%85%A5%E7%A2%B0%E5%88%B0%E7%9A%84%E9%97%AE%E9%A2%98/)

## 