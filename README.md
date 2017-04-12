# socks5-netty
基于netty实现的socks代理

##安装

- 下载git代码 ，mvn clean package appassembler:assemble
 

##运行
- linux ： target/assembler/jsw/proxy/bin/SocksServer start
	
- windows ： target/assembler/jsw/proxy/bin/SocksServer.bat start

##配置

- config.properties
	- port=11080   监听端口
	- auth=true    是否鉴权  (未启用)

- password.properties（为启用）
	- user=password 鉴权用户密码，每行一个

- logback

##扩展
- 使用logback生成日志

##git地址
https://github.com/breakawayz/fsocks
