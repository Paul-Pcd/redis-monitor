## redis-monitor ##

一个web可视化的redis监控程序

### Done ###

监控数据包括以下：

 - redis服务器信息，包括redis版本、上线时间、os系统信息等等
 - 实时的消息处理信息，例如处理command数量、连接总数量等
 - 联通时间动态图表
 - ops时间动态图表
 - 内存占用、cpu消耗实时动态图表
 
 
### TODO ###
 
 - 配置redis放到前端存储中（storage），不用到后台配置，这样可以形成一个平台式工具
 - 报警设置和提醒方式
 - 更多的redis信息以及不同redis兼容性测试
 
 
### Why ###

redis监控程序很多，为什么还要自己做？

因为我找了很多网上推荐的程序，存在一些问题，导致我没有用起来，除了自己知识欠缺的问题，主要包括：

1. 配置麻烦，需要修改代码中的配置文件，而且太难找；
2. 版本不兼容，不记得是哪个项目，2.8可以跑起来，但是2.6完全直接启动出错，我也不知道怎么去修改，原谅我的无知；
3. 启动麻烦，需要启动两个东东，我也不知道为什么，可能是为了性能上的东西吧！


### screenshot ###

![shot_1](/doc/shot/shot_1.png)

![shot_2](/doc/shot/shot_2.png)

![shot_3](/doc/shot/shot_3.png)