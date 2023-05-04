# plugin_collection
一些用到的插件记录一下

## 查看汇编
jdk1.8.0_191\jre\bin\server 目录添加：hsdis-amd64.dll 
vm options：-XX:+UnlockDiagnosticVMOptions -XX:+PrintAssembly -Xcomp

**注意：**
jdk 不要用 openjdk: 
java -version 如果打印的是 openjdk version ... 那么需要重新安装下 jdk

## 字节码
idea 插件市场搜 bytecode --> 安装下载最多的
