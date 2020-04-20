更新功能
1.钉钉群报警、邮件报警、微信报警(需要更新脚本请更改脚本即可)
2.使用方法：
    git clone https://github.com/msj905/zabbix-docker.git
	
   cd /zabbix-docker/Dockerfile/zabbix-db-mariadb
   
   docker build -t zabbix-db .
   
  cd /zabbix-docker/Dockerfile/zabbix-xxl
  
  docker build -t zabbix .# zabbix-docker
