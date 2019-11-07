## 描述
* 基于Pocsuite3框架
* 所有的POC都使用python3从新编写或修改
* 部分POC并未有环境进行测试
* 所有的POC都只写了verify
* POC将会不定期更新
* 主要方便工作中的漏洞验证
* 有任何问题请Issue

## 问题说明
* 部分使用了socket包的POC如果无法验证漏洞是因为python2转python3的编码问题, python3的 socket.send()需要的是byte类型参数

## 使用方法
请查看pocsuite3的官方文档

## 更新日志
* 2019/10/25 提交10个POC
* 2019/10/28 提交php-fpm远程代码执行漏洞POC, 漏洞编号CVE-2019-11043
* 2019/11/04 提交Kibana < 6.6.0 Timelion rce漏洞POC
* 2019/11/05 提交Apache Solr <= 8.2.0 rce 漏洞POC
* 2019/11/05 提交Zookeeper未授权访问漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 API JSON-RPC rce漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 jsrpc 参数profileIdx2 insert注入漏洞POC
* 2019/11/06 提交Zabbix <= 4.4 验证绕过漏洞POC
* 2019/11/06 提交Weblogic SSRF漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 latest SQL注入漏洞POC
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2016-0638
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2016-3510
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2017-3248

## 致谢
* 感谢开放POC的所有大神, 感谢你们的默默奉献, 小弟沾你们的光了
