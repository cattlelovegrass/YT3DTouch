# YT3DTouch
3DTouch
这次写的静态类型3D Touch，主要参照苹果的文档来写的，总结如下:</br> 
1 新建一个UIApplicationShortcutItems,NSArray类型，几个快速入口都在这里.</br>
2 新建多个item,代表几个快速选项，目前貌似不超过4个，item类型为NSDictionary.</br>
3 每个item下面，建立title，type,iconFile选项，然后填入相关的参数就OK,</br>
4 在AppDelegate里面的launchOptions里面，取出item,然后根据每个item.type，点击相关的item会进入那个界面，简单的就是这样。。。</br>
![](https://github.com/cattlelovegrass/YT3DTouch/blob/master/IMG_1989.PNG)
