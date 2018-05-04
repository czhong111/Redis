# Redis
setup Redis Master-Slave + Keepalived + VIP
这是很经典的db架构，也可以用与mysql的主从切换。基本原理是：Keepalive通过脚本检测master的存活，然后通过漂移VIP（Virtual IP）完成主从切换。

