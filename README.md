# ensp_homework
一些简单的ensp配置实验和使用指令，并且每个实验配有wireshark抓包分析。

1 ppp pap与chap认证

2 广播风暴

3 vlan划分与通信

4 IP数据报分片实验

5-RIP环路

6 ipv6无状态自动配置

7 dns搭建与报文分析

[Huawei]un in en


[hxf_1]info-center source ds channel 0 log state off trap state off


            也可以用undo info enable 即un in en


[hxf_1]user-interface console 0

[hxf_1-ui-console0]idle-timeout 0 不会自动退出sys


reset arp dynamic
reset arp all
