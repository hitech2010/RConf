# RConf
这是一个通过xml文件描述定义对象配置文件的库和工具，可以定义各种类型的配置文件对象，基本内容包括描述如何修改文件内容，以及在修改之前执行前置/后置命令等。
利用这些行为，可以设计定义各种类型的文件配置修改对象，实现复杂的文件配置，可以执行一键配置部署软件；若通过远程获取xml描述文件，也可以轻松实现远程配置部署软件，
实现强大的功能；
    配置的对象可以设计成拥有各种想象力的功能，如可以比较新配置和当前配置，若配置无项目更新，则不会去重新加载相关的软件，从而避免
不必要的重启；可以实现为灰度重新加载，自动重新加载更新配置受到影响的对应程序；
