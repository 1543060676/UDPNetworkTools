# UDPNetworkTools
面向UDPNetwork的一款Unity的編譯工具

編譯工具用法：
1.啓動下圖exe

![1701052286041](https://github.com/zinxDev/UDPNetworkTools/assets/37795777/bd81c890-ad32-412b-88d5-c82b32710c01)

2.將Build.dll放入Plugins/Editor目錄

3.將BuildConfig.cs放到Editor目錄

4.Unity添加編譯命令：USE_BUILD_TOOLS

5.編譯

各个插件功能：

ToolsBase.dll：提供二进制的写入和读取功能；

PublicTools.dll：通用的一些工具，例如单例、工厂、缓存池等；

Anticrack.dll：提供加密的工具；

Build.dll：必须放到Editor下使用，提供编译时去除ToolsBase.dll、PublicTools.dll、Anticrack.dll、UDPNetwork.dll等访问到Unity编辑器的代码部分。
