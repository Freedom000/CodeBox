CodeBox android
=======

an open source project demo Demonstration

![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/device-2014-12-02-152750.png)  
![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/device-2014-12-02-152805.png)  
![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/device-2014-12-02-152814.png)  
![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/device-2014-12-02-152827.png)  

关于
------- 
CodeBox是一个搜集优秀android开源代码并提供演示的安卓客户端，其演示功能是将开源项目作为插件加载到客户端中。插件的实现得益于
dynamic-load-apk-Apk动态加载框架https://github.com/singwhatiwanna/dynamic-load-apk   。
目前已经完成的插件非常少，还需要大量的编译插件的工作。
希望能有更多的朋友参与进来。

插件
-------
如果你对该项目感兴趣，可以加入到我们的插件开发中，将你根据dl框架开发的插件放入项目的plugins目录下即可，我会将该插件上传到服务器。插件的命名以你所编译的项目名一致。


用到的开源库
------- 
下拉刷新
######
下拉刷新改写自xListView
图片的异步加载
######
异步加载改写自LazyList https://github.com/thest1/LazyList

以上两个库都集成到了项目中，不必再添加依赖。

目前该项目的功能还很单一，后续会增加更多的功能。