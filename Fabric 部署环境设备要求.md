# Fabric 部署环境设备要求
1、因阿里云机器以及公司网络运营商宽带限制，无法做出合理的fabric并发测试。
2、测试增加节点、又得重新购买阿里节点，目前测试都是以最小需求设备测试、无法满足动态增加节点测试要求。
## orderer设备（至少4核8G内存）
1、至少3台服务器
2、对CPU要求高
3、对存储要求至少500GB 建议1T
4、系统要求linux
## kafka
1、可以与orderer机器一块部署、每个orderer机器运行一个kafka进程
2、对存储要求至少500GB 建议1T
3、系统要求linux
## zookeeper
1、可以与orderer机器一块部署、每个orderer机器运行一个zookeeper进程
2、对存储要求至少500GB 建议1T
3、系统要求linux
## peer （至少4核8G内存）
1、至少4台服务器
2、对CPU要求较高
3、对存储要求至少500GB 建议1T
4、系统要求linux
## ca （至少4核8G内存）
1、至少2台服务器
2、对CPU要求高
3、对存储要求至少500GB 建议1T
4、系统要求linux


参照：
https://www.asus.com.cn/Commercial-Servers-Workstations/RS100-E9-PI2/HelpDesk_CPU/

华硕服务器产品：
http://www.asus.com.cn/Commercial-Servers-Workstations/

E9代产品：
https://www.asus.com.cn/Commercial-Servers-Workstations/RS300-E9-RS4/specifications/
