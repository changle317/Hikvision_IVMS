# Hikvision_IVMS_Exp
海康威视IVMS 综合安防管理平台 漏洞利用脚本，包含Fastjson，以及两个文件上传漏洞、

本项目属于是初次学习Golang的练手小项目, 不喜误喷, 如果感觉用着可以不妨来个Start 这是我更新最大的动力
# 使用方法
单个目标
```
./Exploit -u http://x.x.x.x -v Hikvision -w webshell.jsp
```
多个目标
```
./Exploit -f url.txt -v Hikvision -w webshell.jsp

url.txt内容为
http://x.x.x.x
https://x.x.x.x
```
检测某一个漏洞
```
./Exploit -u http://x.x.x.x -v Hikvision_ivms_upload1 -w webshell.jsp
```

# 注 意
本仓库分享的安全工具，仅供安全研究与学习之用，如用于其他用途，由使用者承担全部法律及连带责任，与工具作者无关。
