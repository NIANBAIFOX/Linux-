#### Linux常见的7种文件类型 
|属性|文件类型|
|---|---|
|-|常规文件|
|d|目录（direct）文件|
|b|块设备（block device）文件，如硬盘。支持以块为单位进行**随机访问**|
|c|字符设备（character device）文件，如键盘。支持以字符为单位进行**线性访问**|
|l|符号连接（symbolic link）文件，又称软连接文件|
|p|命名管道（pipe）文件|
|s|套接字（socket）,用于实现两个进程间的通信|

例如：输入ls -l /dev （查看设备文件） 
执行效果如图所示：

![查看文件类型图](https://github.com/NIANBAIFOX/Linux-/blob/main/%E7%AC%AC%E4%BA%8C%E7%AB%A0/%E5%9B%BE%E7%89%87/%E6%9F%A5%E7%9C%8B%E6%96%87%E4%BB%B6%E7%B1%BB%E5%9E%8B.png)
最左侧10个字符含义依次如下：  
* 第1个字符：代表文件类型
* 第2~4个字符：代表用户的权限
* 第5~7个字符：代表用户组的权限
* 第8~10个字符：代表其他用户的权限
* 第2~10个字符中，r代表可读，w代表可写，x代表执行

例如：输入file /dev  （查看详细的文件类型）
  
执行效果如图所示：
  
![查看详细的文件类型](https://github.com/NIANBAIFOX/Linux-/blob/main/%E7%AC%AC%E4%BA%8C%E7%AB%A0/%E6%9F%A5%E7%9C%8B%E8%AF%A6%E7%BB%86%E6%96%87%E4%BB%B6%E7%B1%BB%E5%9E%8B.png)
