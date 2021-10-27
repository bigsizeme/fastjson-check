# fastjson-check

在@pmiaowu插件上做的修改，原作者用dnslog.cn进行出网检查，但在大型攻防演练（HW）过程中由于前期打点，测试的站点较多dnslog.cn会对IP进行封禁操作
导致插件无法正常检测


1、增加burp内置BurpCollaborator进行出网探测，

2、针对不出网payload总结支持一键生成回显payload(15种)


#release中提供下载

config界面
![Alt text](https://github.com/bigsizeme/fastjson-check/blob/main/1.png)
reapter右键
![Alt text](https://github.com/bigsizeme/fastjson-check/blob/main/2.png)

