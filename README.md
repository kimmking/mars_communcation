mars_communcation
========
   该TCP通讯组件（作为服务调用框架---mars的底层通讯）主要是参考了ActiveMQ的通讯层实现的，虽然现在netty、mina等nio框架已经足够普及，但在短短2千行作用的代码里实现了
包括失败重连、心跳处理、异步消息发送在内的等等通讯需要关注的功能，还是值得大家一看。尤其是可以从中学习一下ActiveMQ在通讯层实现中的设计，应该会有所收获的。
   
========
<b>更新记录</b><br>
<b>2013-02-04</b> 提交第一个版本。<br>
