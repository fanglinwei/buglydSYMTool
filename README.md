# buglydSYMTool
用于bugly快速上传dSYM文件的脚本



> 开发中，为了更好的用户体验或者为了bug跟踪，可能会需要使用腾讯的bugly分析工具.但是要使用bugly分析报错需要从dYSM中取出符号表配置上传.

##### 符号表说明: [Bugly iOS 符号表配置](https://bugly.qq.com/docs/user-guide/symbol-configuration-ios/?v=20180709165613)



#### 使用: 

### 1. 按照bugly官网配置java环境

### 2. 准备dSYM文件 

dSYM文件是指具有调试信息的目标文件，文件名通常为：xxx.app.dSYM

[Bugly iOS 符号表配置](https://bugly.qq.com/docs/user-guide/symbol-configuration-ios/?v=20180709165613)有说明通过xcode获取或者通过iTunes Connect获取


### 3. 下载`buglySymboliOS.jar`
下载最新版Bugly [iOS符号表工具](https://bugly.qq.com/v2/sdk?id=37f16cf0-2020-4e30-9e8d-0f7de59cfe94).里面有一个`buglySymboliOS.jar`文件,然后把该文件和之前下载的`dYSM`文件放在同一个文件夹里

### 4. 准备脚本
终端命令执行
```
$ bash buglydSYMTool.sh
```

>  只是一个小工具,不喜勿喷.欢迎star
