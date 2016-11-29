###时间:  2012年6月
###地点:  安徽 合肥 安徽农业大学 网络工程系
###关键词:毕业 别离
*	毕业了,可能也结束了这一生的学校生涯,最美的年华全都给了象牙塔,不知道他给了我什么,但我知道,一切都值得,一切都等着去验证.
*	同学收拾行李,空气中分离的悲伤和向往社会的兴奋交织着.
*	火车票上的目的地指向全国各地,而我即将成为一个北漂.
*	北京,那里应该会是我美梦成真的地方.

###时间:  2012年7月
###地点:  北京 赶集网
###关键词:新人 好奇 学习
*	正式入职赶集网技术保障部成为一名SA.
*	学会了搬服务器,做raid,装系统,换硬盘,修内存...各种硬件.
*	看了tcp/ip,udp,http...各种协议.
*	更学会了Nginx,php-fpm,zabbix,lvs,Xen Server...各种服务.
*	也知道了什么是sql什么是nosql.
*	写了第一个公司级服务(shell)-星际之门.

###时间:  2013年3月
###地点:  北京 赶集网
###关键词:MySQL Redis Python
*	从SA到DBA只差两个字母,付出的努力只有自己知道.
*	开始做MySQL运维,也开始改造前任留下的脚本.
*	Python成了首选开发语言,[MySQL监控](https://github.com/kangqiao-lu/mysql_monitor "MySQL监控"),备份,[归档](https://github.com/kangqiao-lu/mysql_archive "归档")统统写了一遍.
*	还是nosql,以前架构真是烂透了,于是有了[redis监控](https://github.com/kangqiao-lu/redis_monitor "redis监控"),redis-sentinal,[tmc_twem_monitor](https://github.com/kangqiao-lu/tmac_twem_monitor "tmc_twem_monitor").
*	到处都是脚本,太难管理了,于是有automan,赶集网有了自己的数据库平台.

###时间:  2015年3月
###地点:  南京 途牛旅游网
###关键词:MySQL Redis Python
	####途牛第一个数据库平台(基于tornado):
	*	监控对象：从物理机到MySQL实例.
	*	监控项阀值：可以针对每个实例的每个监控项设置不同的阀值.
	*	自动发现：对于新部署的实例会被自动发现，防止监控遗漏.
	*	告警：每个MySQL集群可以定义不同告警接收人，实例和系统关联后自动发给各个系统负责人.
	*	监控数据展示：更多监控项数据展示，更快的找到想找的实例.
	*	监控数据异步处理：监控agent获取到监控数据推送到NSQ消息队列，woker端消费并处理监控数据.
	*	周期性的对报警进行统计，统计哪些系统，哪些监控项报警最为频繁，每条报警需要处理多长时间恢复.
*	备份系统：
	*	通过数据平台，统一调度备份.
	*	处理数据的物理备份，更加入了mysqldump的逻辑备份(之前只有xtrabackup).
	*	统一收集备份结果，并邮件周知，第一时间知道备份结果.
	*	重写写备份脚本，解决了备份时连接数打满，机器负载过高，甚至crash的状况.
*	Redis：
	*	从单点到codis再到Twemproxy，找到最适合途牛的缓存集群，缓存更加稳定.
	*	Twemproxy+LVS实现整个集群的高可用.
	*	接入监控平台，研发更方便查看整个集群的状态.
	*	监控数据展示，从集群，后端redis实例数据更加全面.
	*	读写监控，对集群的可用性做到全面监控.

###时间:  2016年10月
###地点:  深圳 腾讯
###关键词:MySQL
*	加入更大的平台,遇见更加优秀的人,keep going DBA...


###Contact me:
*	CellPhone:13381109027
*	QQ:617485059
*	mail:kangqiao43@sina.com
*	微信:kangqiao43
*	![微信二维码](./weixin.png)
