# socks5-netty
基于netty实现的socks5代理

##安装

- 下载git代码 ，mvn install
 
- 或者直接下载bin/proxy

##运行
- linux ： target/assembler/jsw/proxy/bin/proxy start
	
- windows ： target/assembler/jsw/proxy/bin/proxy.bat start

##配置

- config.properties
	- port=11080   监听端口
	- auth=true    是否鉴权

- password.properties
	- user=password 鉴权用户密码，每行一个

- logback

##扩展
- 使用logback生成日志
