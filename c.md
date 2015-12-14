
---


# 联系方式

- 手机：18519119405 
- Email：zhangchunzhong@gmail.com/zczxyz@126.com 
- 微信号：zhangchunzhongbj

---

# 个人信息

 - 张春重/男/1976 
 - 本科/电子科技大学自动化系 
 - 工作年限：10+年
 - Github：http://github.com/jzhang

 - 期望职位：C/C++高级程序员
 - 期望薪资：税前月薪25k，特别喜欢的公司可例外
 - 期望城市：北京

---

# 工作经历

## Symantec/Veritas公司 （ 2009年3月 ~ 今 ）

### 去重存储优化  
我和同组同事分别使用Intel C编译器和Intel ISA-L库优化去重存储的MD5计算部分，因为去重系统需要使用MD5/SHA256定位重复数据块，MD5消耗CPU巨大。我负责Intel C编译器部分，Intel C编译器对于memcpy优化很多，大概在各种场景下提升备份效率10+%。该项目正在进行中。

### 网络重连Proxy项目 
我和另一位同事负责这个项目的设计、开发和测试用例的编写。Netbackup备份系统中有使用卫星链路备份的案例，卫星链路一旦意外断开，整个备份任务失败，必须重新启动新的备份任务，而且卫星链路很贵。我们的设计成客户端和服务端启动proxy服务，缓存部分数据，等到链路意外断开，客户端和服务器端交换丢失部分的数据。整个项目使用ACE Reactor异步模式完成，因为callback处理中有很多中间状态，使用了状态机。此项目已经成功部署到NETBACKUP 7.5及其以上版本。

### Adobe AIR BE2NBU 项目 
公司有两个产品BE是低端，NBU是高端，底层的数据格式不一样。项目第一阶段是迁移备份策略，第二阶段是迁移数据。我们做的是第一个阶段。一个负责“画”H5网页，我负责使用BE的SDK的C API写命令行。因为画网页工作繁忙，所以尝试写javascript代码，在此过程中熟悉了jquery，html5。此项目已经移交成都同事。

## Motorala公司 （ 2006年9月 ~ 2009年3月 ）

### Android手机项目 
集成TI提供的OpenMAX的codec元件到OpenCore系统，该项目没有完成就遭遇裁员。

### iDen手机音频项目 
集成蓝牙服务到音频服务器。根据新的手机音频软件改动硬件接口层。声音的硬件/软件混音策略。

## TechFaith公司 （ 2006年9月 ~ 2009年3月 ）

Windows Mobile RIL层开发	
增强和修改RIL层的数据业务部分（GPRS&CSD）
开发应用到FTA现场测试的跟踪无线层LOG的工具


## 北京鑫博发公司 （ 2001年3月 ~ 2009年2月 ）

### mp4压缩卡驱动移植
移植LINUX MPEG4编码器接口从原先的USB接口到HPI接口，芯片厂商提供usb驱动，但是ARM板上只有HPI接口。
开发MP4多播系统LINUX服务器端和window客户播放端，服务器端使用jrtp库，客户端使用ffmpeg在widnows上解码播放。
摄像头MP4编码控制使用RTSP协议

### H323 IP电话项目
 把OpenH323移植到BSP15并减小系统尺寸。重新改写控制接口（从命令行到串口控制）。


## 天津动力机厂 （ 1998年11月 ~ 2002年11月 ）

### 8051单片机开发

---


# 技能清单
（我一般主张将技能清单写入到工作经历里边去。不过很难完整，所以有这么一段也不错）

以下均为我熟练使用的技能

- 系统开发：C/C++
- 数据库相关：/SQLite
- 版本管理、文档和自动化部署工具：Cvs/Svn/Git
- 单元测试：CPPUnit/Cunit

## 参考技能关键字
- linux(369)
- tcp(96)
- unix(93)
- python(72)
- socket(71)
- shell(47)
- stl(41)
- perl(24)
- html(23)
- javascript(23)
- gdb(21)
- gcc(18)
- udp(17)
- boost(12)
- svn(12)
- sqlite(7)
- ffmpeg(7)
- rtp(6)
- scrum(5)
- arm(5)
- embedded(4)
- module(4)
- usb(4)
- epoll(4)
- ace(4)
- mp4(4)

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
