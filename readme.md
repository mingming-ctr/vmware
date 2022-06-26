记录vmware中出现的问题


1. 磁盘损坏修复
查看日志问题，找出需要修复的磁盘。
在日志中搜索 The specified virtual disk needs repair
![image](https://user-images.githubusercontent.com/12455138/175803452-23d03fcc-7496-436f-a826-653f663840b0.png)

用下面的工具修复，相关exe 在wmware.exe所在文件夹
vmware-vdiskmanager -R "<path of the vmdk(virtual disk>"
参考
https://kb.vmware.com/s/article/2019259
https://blog.csdn.net/l1212xiao/article/details/80430414

![image](https://user-images.githubusercontent.com/12455138/175803604-9e6d330e-3173-45b3-bf71-53f2bc82222c.png)
以上图片修复成功，重新启动就好了




