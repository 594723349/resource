# 资源整合包

### CentOS7安装yum 出处https://www.jianshu.com/p/7a2a91109835 ###

1、查询原有yum  
rpm -qa |grep yum 

2、删除原有的yum  
rpm -aq|grep yum|xargs rpm -e –nodeps 
rpm -qa |grep yum
