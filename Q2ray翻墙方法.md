##  0. 参考链接  
https://qv2ray.net/getting-started/step2.html#%E4%B8%8B%E8%BD%BD-v2ray-%E6%A0%B8%E5%BF%83%E6%96%87%E4%BB%B6
该链接较为全面，提供了软件的不同设备下的下载方法

https://mahongfei.com/1776.html

## 1. 我的具体操作
- 1.1 下载文件
    -   ### 下载界面客户端 
            前往https://github.com/Qv2ray/Qv2ray/releases/tag/v2.6.3 网站中下载 linux-x64.AppImage文件 （可能因为之后版本继续更新无v2.6.3，那么网址到releasse 为止，进入tag寻找合适的版本）
    ![客户端文件](https://img-blog.csdnimg.cn/20210221172737865.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODIxNjU3Mw==,size_16,color_FFFFFF,t_70) 
    - ### 下载核心文件
            前往https://github.com/v2fly/v2ray-core/releases 下载核心文件 v2ray-linux-64.zip,并进行解压。
        ![核心文件](https://img-blog.csdnimg.cn/20210221174049720.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODIxNjU3Mw==,size_16,color_FFFFFF,t_70)
        ### 相关文件内容
        ![核心文件内容](https://img-blog.csdnimg.cn/20210221175517143.png)

-   1.2 配置核心文件
    进入界面客户端AppImage的下载目录，打开终端
    ```cpp
    sudo chmod +x   ./Qv2ray.v2.6.3.linux-x64.AppImage
    ./Qv2ray.v2.6.3.linux-x64.AppImage
//此时出现网络连接界面
    ```
    开始在界面中配置内核文件
    进入-首选项-内核配置
    ![配置界面](https://img-blog.csdnimg.cn/20210221175116362.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODIxNjU3Mw==,size_16,color_FFFFFF,t_70)
    设置核心可执行文件路径和资源目录，如上图。
    核心可执行文件路径将此设置为您的 V2Ray 可执行文件所在的位置。
     资源目录，将其设置为 geoip.dat 和 geosite.dat 所在的位置。


- 1.3 向Qvray2中添加节点（通过订阅地址导入，也可以通过其他方式导入见链接1）
复制G-Helper中的通用链接
我的为https://ghelper.me/rss/965d1fcbddfbd743c8051505c36b6027 
![导入订阅节点](https://img-blog.csdnimg.cn/20210221180325479.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODIxNjU3Mw==,size_16,color_FFFFFF,t_70)
选择一个网络进行链接
![](https://img-blog.csdnimg.cn/20210221180422786.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODIxNjU3Mw==,size_16,color_FFFFFF,t_70)

然后就可以google了,需要访问外网的时候都不要关掉终端，不然就连不上了

