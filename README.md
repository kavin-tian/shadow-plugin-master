# shadow-plugin-master
shadow插件化框架演示
参考博客地址：https://blog.csdn.net/fzkf9225/article/details/132107432


报错:
```
D:\LLM\html\shadow-plugin-master\plugin-loader\build\outputs\apk\debug\plugin-loader-debug.apk , loader file not exist...
```
解决方法:
在Android Studio中，点击菜单栏的Build -> Clean Project，然后再点击Build -> Rebuild Project。这样可以清理和重建项目，解决一些构建过程中出现的问题。
如果问题依然存在，可以尝试以下步骤：
1. 关闭Android Studio。打开任务管理器，确保没有任何与Android Studio相关的进程在运行。重新启动Android Studio，打开你的项目，然后尝试重新构建项目。这有时可以解决由于缓存或临时文件引起的问题。
2. clean项目：点击菜单栏的Build -> Clean Project。
3. Rebuild Project ：点击菜单栏的Build -> Rebuild Project。(\build\outputs\apk\debug\plugin-loader-debug.apk 就会生成)
