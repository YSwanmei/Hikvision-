# Hikvision综合漏洞利用工具

没事写个工具，
程序采用C#开发,
首次使用请安装依赖：
NET8.0
声明：仅用于授权测试，用户滥用造成的一切后果和作者无关
请遵守法律法规！

https://dotnet.microsoft.com/zh-cn/download

海康威视综合漏洞利用工具 收录漏洞如下：

Hikvision 摄像头未授权访问漏洞

Hikvision 远程代码执行漏洞

Hikvision iVMS综合安防系统任意文件上传漏洞

Hikvision综合安防管理平台isecure center文件上传漏洞

Hikvision综合安防管理平台config信息泄露漏洞

Hikvision综合安防管理平台env信息泄漏漏洞

Hikvision综合安防管理平台report任意文件上传漏洞

Hikvision综合安防管理平台api session命令执行漏洞

Hikvision applyCT命令执行漏洞

Hikvision applyAutoLoginTicket命令执行漏洞

Hikvision keepAlive远程代码执行漏洞

# 功能介绍
输入目标地址，默认模块一键扫描所有漏洞
Hikvision applyCT模块检测，需要配置ceye token，http://ceye.io/，考虑到批量识别可能会阻塞网络，没有采取这种方式，提供Hikvision applyCT模块漏洞识别
,选择模块可单独选择模块进行漏洞扫描

![image](https://github.com/MInggongK/Hikvision-/blob/main/202406080819451.png)

批量检测模块：
模块如下：Hikvision 远程代码执行漏洞

Hikvision iVMS综合安防系统任意文件上传漏洞

Hikvision综合安防管理平台isecure center文件上传漏洞

Hikvision综合安防管理平台config信息泄露漏洞

Hikvision综合安防管理平台api session命令执行漏洞

Hikvision综合安防管理平台env信息泄漏漏洞

Hikvision applyAutoLoginTicket命令执行漏洞

webshell利用模块
Hikvision iVMS综合安防系统任意文件上传漏洞

Hikvision综合安防管理平台isecure center文件上传漏洞

Hikvision综合安防管理平台report任意文件上传漏洞

内置Godzilla，Behinder，AntSword，JSPcmdshell，测试文件可直接上传

自定义上传，可选择模块进行上传，输入你要上传的shell代码，输入文件名，点击上传即可

cmshell命令执行模块
Hikvision 远程代码执行漏洞

Hikvision综合安防管理平台api session命令执行漏洞

Hikvision applyAutoLoginTicket命令执行漏洞
验证漏洞是否存在，执行cmdshell命令



