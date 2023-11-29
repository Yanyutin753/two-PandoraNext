# two-PandoraNext

##### 1.把Pandora文件放在主机根目录

##### 2.填写两个config.json文件里面的license_ip(都是同一个值）

###### 第一个config.json  \pandora\data\config.json

###### 第二个config.json \pandora\pandoraproxy\data\config.json

##### 3.启动指令
```
cd /pandora

docker-compose up -d
```
##### 4.开放8081（tokensTool）、8082(proxy)、8181(web)端口即可访问

##### 5.打开8081，配置刷新token的地址为：http://你的ip:8082
