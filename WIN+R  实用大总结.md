---
typora-root-url: WIN+R 命令实用大总结
typora-copy-images-to: WIN+R 命令实用大总结
---
---
title: WIN+R实用大总结😊
date: 2022-07-25 22:10:00
author: highgerms
categories: 
    - 效率提升技巧
tags:
    - 效率提升技巧
---
Windows的各种快捷键用好会提高很高的效率，命令行一下子输入完了，别人都还在傻傻找入口，是不是很快乐。
<!--more-->

# WIN+R  实用大总结 😊

[TOC]

%windir% 是 **Windows** 的安装文件夹

### cmd 与管理员cmd

cmd.exe的路径是C:\Windows\system32\cmd

ps：如果是非管理员身份运行cmd，会有很多操作出现问题  【比如cscript test.vbs 等】

winR  输入 cmd                                            --------->  cmd命令行 

winR  输入 cmd，然后Ctrl+shift+enter   --------->   管理员下的cmd命令行

![image-20220720105427401](/image-20220720105427401.png)

方法2：打开管理员下的cmd命令行【winR  输入**runas /user:administrator Cmd** 】，但是这种方法需要administrator设置密码

方法3：设置快捷方式，区分cmd和管理员cmd，一劳永逸，具体操作如下链接

[通过 Win + R 默认以管理员身份打开 cmd](https://blog.csdn.net/qq_42765363/article/details/115214222)





### 打开网络共享中心 ：ncpa.cpl

<img src="/image-20220720112637622.png" alt="image-20220720112637622" style="zoom: 67%;" />









### 打开画画：mspaint

<img src="/image-20220720112759110.png" alt="image-20220720112759110" style="zoom:67%;" />











### 打开系统配置：msconfig

<img src="/image-20220720112848089.png" alt="image-20220720112848089" style="zoom:67%;" />



### 打开设备管理器：devmgmt.msc

<img src="/image-20220720112934428.png" alt="image-20220720112934428" style="zoom:67%;" />





### 打开远程桌面连接：mstsc

<img src="/image-20220720113044035.png" alt="image-20220720113044035" style="zoom:67%;" />



### 任务管理器：taskmgr

<img src="/image-20220720113140895.png" alt="image-20220720113140895" style="zoom:67%;" />





### 系统属性：sysdm.cpl   【查看计算机名字、重命名计算机名字、查看设备管理信息、创建系统还原点、远程协助设置】

**CPL文件，又叫控制面板项（Control Panel  Item），多保存于系统安装目录的system32文件夹下，它们分别对应着控制面板中的项目，普通用户的访问受到限制。它可由shell32.dll、control.exe打开。此外，你也可以直接在资源管理器中双击调用Open命令打开（实质上调用了shell32.dll）。**

计算机名字可以看【计算机名，cmd下hostname也行】

环境变量可以在这里看【高级】

创建系统还原点和进行系统还原都可以在【系统保护中查看】

<img src="/image-20220720113328931.png" alt="image-20220720113328931" style="zoom:67%;" />



### 注册表：regedit

<img src="/image-20220720144437552.png" alt="image-20220720144437552" style="zoom:67%;" />



### 组件服务：dcomcnfg

<img src="/image-20220720144507062.png" alt="image-20220720144507062" style="zoom:67%;" />

### 本地计算机策略：gpedit.msc

![image-20220720144605490](/image-20220720144605490.png)









### 关机/重启 shutdown -s/-r -t 0 -c ""

-s 关机

-r 重启

-t 时间

-c 提示内容

![image-20220720154237589](/image-20220720154237589.png)



### 系统自带计算器 calc

<img src="/image-20220720154451071.png" alt="image-20220720154451071" style="zoom:67%;" />





### 资源管理器 explorer

<img src="/image-20220720154622769.png" alt="image-20220720154622769" style="zoom:67%;" />





### 管理控制台 mmc

<img src="/image-20220720154657176.png" alt="image-20220720154657176" style="zoom:67%;" />





### 打开我的文档  英文句号(.)

<img src="/image-20220720154750384.png" alt="image-20220720154750384" style="zoom:67%;" />





### 声音管理器 mmsys.cpl

![image-20220721092901030](/image-20220721092901030.png)





### 计算机管理 compmgmt.msc

![1](/image-20220721093653072.png)



#### 性能监视器 perfmon

![image-20220721093228370](/image-20220721093228370.png)



#### 事件查看器 eventvwr

![image-20220721093147966](/image-20220721093147966.png)





#### 本地服务  services.msc

![image-20220721093522492](/image-20220721093522492.png)



#### 磁盘管理  diskmgmt.msc

![image-20220721093843442](/image-20220721093843442.png)





#### 设备管理器  devmgmt.msc

![image-20220721093950104](/image-20220721093950104.png)

#### 本地用户和组 lusrmgr.msc

![image-20220721094034608](/image-20220721094034608.png)





### 组策略 gpedit.msc 

![image-20220721094249722](/image-20220721094249722.png)



### 任务管理器  taskmgr

![image-20220721094338743](/image-20220721094338743.png)







### 证书管理  certmgr.msc

![image-20220721094501244](/image-20220721094501244.png)







### 本地安全策略 secpol.msc

![image-20220721094533266](/image-20220721094533266.png)













### 系统信息 msinfo32

<img src="/image-20220721151826192.png" alt="image-20220721151826192" style="zoom:67%;" />



参考资料：

[快速入门Win+R命令（附图）](https://blog.csdn.net/qq_40287093/article/details/82807075)