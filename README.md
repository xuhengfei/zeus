##宙斯(zeus)是什么
宙斯是一个完整的Hadoop的作业平台  
从Hadoop任务的调试运行到生产任务的周期调度
宙斯支持任务的整个生命周期

从功能上来说，支持：  
Hadoop MapReduce任务的调试运行  
Hive任务的调试运行  
Shell任务的运行    
Hive元数据的可视化查询与数据预览  
Hadoop任务的自动调度  
完整的文档管理  

完整的学习文档请进入：
* [文档首页](https://github.com/alibaba/zeus/wiki)
* [安装指导文档](https://github.com/alibaba/zeus/wiki/安装指导文档)
* [用户入门手册](https://github.com/alibaba/zeus/wiki/用户入门手册)
* [用户进阶手册](https://github.com/alibaba/zeus/wiki/用户进阶手册)
* [管理员配置手册](https://github.com/alibaba/zeus/wiki/管理员配置手册)
 
###宙斯开源，不仅仅是开源技术，更是开源产品  
开发中心，一个文档管理，开发调试的环境，在任务上线前的主要工作区域  
<a href="http://xuhengfei.github.io/assets/images/articles/zeus/snapshot-dev.png" target="_blank"><img src="http://xuhengfei.github.io/assets/images/articles/zeus/snapshot-dev.png" /></a>
调度中心，生产任务的调度环境，当任务调试通过后，在此处配置调度信息进行生产调度  
<a href="http://xuhengfei.github.io/assets/images/articles/zeus/snapshot-schedule.png" target="_blank"><img src="http://xuhengfei.github.io/assets/images/articles/zeus/snapshot-schedule.png" /></a>  

##宙斯运行原理
<a href="http://yun.duiba.com.cn/xuhengfei/graph-network.png" target="_blank"><img src="http://yun.duiba.com.cn/xuhengfei/graph-network.png" /></a>  

<a href="http://yun.duiba.com.cn/xuhengfei/graph-struct.png" target="_blank"><img src="http://yun.duiba.com.cn/xuhengfei/graph-struct.png" /></a>  

<a href="http://yun.duiba.com.cn/xuhengfei/graph-workflow.png" target="_blank"><img src="http://yun.duiba.com.cn/xuhengfei/graph-workflow.png" /></a>  

<a href="http://yun.duiba.com.cn/xuhengfei/graph-schedule.png" target="_blank"><img src="http://yun.duiba.com.cn/xuhengfei/graph-schedule.png" /></a>   



更多文档，请进入<a href="http://github.com/alibaba/zeus/wiki" target="_blank">文档首页</a> 



关于浏览器兼容性  
默认只支持webkit内核的浏览器，建议使用chrome  
可以扩大浏览器范围，方法：/web/src/main/java/com/taobao/zeus/web/platform/Platform.gwt.xml 中注释掉 user.agent 这一行  
当然这样会大致打包时间加长(gwt为了兼容不同的浏览器会编译更多的代码，导致打包变慢)  
即便如此，我们也不保证IE等浏览器能够正常使用！  


