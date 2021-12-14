# Log4j
Log4j漏洞自查工具

# Log4j2_detect工具使用说明
1、本工具用于自查本地服务器是否使用了与log4j相关的漏洞组件
2、支持windows(64位)、linux平台使用，windows支持命令行和界面版
3、检测原理：
判断检测目录的所有jar包里是否包含了log4j组件特征，并读取log4j版本号研判是否为存在漏洞版本，支持递归逐级检测并打印检测路由
4、漏洞版本：
log4j2.x && <2.16.0，其中2.15.0-rc2属于疑似漏洞版本，建议更新
5、修复建议：
更新存在漏洞的jar包，更新地址：
https://github.com/apache/logging-log4j2/tags

# 程序截图

![图片](https://raw.githubusercontent.com/webraybtl/Log4j/main/imgs/1.png)


![图片](https://raw.githubusercontent.com/webraybtl/Log4j/main/imgs/2.png)


![图片](https://raw.githubusercontent.com/webraybtl/Log4j/main/imgs/3.png)
