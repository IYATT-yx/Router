# CQUT router
针对重庆理工大学宽带的路由器固件  

_____________________________________________
2021-4-9  
[固件](固件)  
目前编译了斐讯K2和newifi3的固件  
从2.1g1开始集成了使用创翼所需的脚本和库  
只需要登录管理页面,打开 服务->终端,在里面执行 `sh nk4conf.sh` 即可启用  
方案采用拦截账号,路由器代替创翼拨号

管理页面地址 `192.168.6.1`  
wifi名和密码都是:  iyatt.com  
____________________________________________
2021-4-10

2.14g1 2.15g2 去除adblock
____________________________________________
2021-4-11

2.16g2 去除cshark
____________________________________________
2021-4-11

2.15g1 2.17g2 添加TCP-BBR
____________________________________________
2021-4-11

2.16g1 2.18g2 修改脚本
启用创翼支持命令改为 sh nkconf.sh
____________________________________________
