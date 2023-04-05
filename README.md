# 1412
cto-Libevent C＋＋高并发网络编程 | 完结
### 微:NoBug1024 


课程介绍：

LIBEVENT：是一款事件驱动的网络开发包，由于采用C语言开发体积小巧，跨平台，速度极快．课程中讲解分析 LIBEVENT原理，跨平台编译事件1O、缓冲1O处理。讲解HTTP服务端开发示例，HTTP客户端请求开发示例，最后基于 LIBEVENTT创建线程池C＋＋框架，并用此框架完成FTP服务器的登录、目录访问、文件上传下载功能

〖课程目录〗:

├──1-1 课程介绍-讲师介绍和目标学员说明.mp4 48.63M
├──1-10 libevent在linux环境编译源码并编写测试程序.mp4 57.41M
├──1-2 课程介绍-学员学习收益和课程资料说明.mp4 84.82M
├──1-3 windows平台编译libevent分析及环境安装和源.mp4 93.87M
├──1-4 用vs2017编译zlib源码并完成编译批处理脚本.mp4 81.13M
├──1-5 用vs2017编译openssl源码并完成编译批处理脚本.mp4 191.59M
├──1-6 libevent源码vs2017编译完成包含openss模块.mp4 95.09M
├──1-7 libevent集成zlib的测试程序配置修改和编译.mp4 218.86M
├──1-8 libevent源码vs2017编译批处理脚本编写.mp4 104.10M
├──1-9 libevent第一个vs2017的测试程序完成.mp4 82.46M
├──2-1 高并发网络模型select_epoll_iocp区别.mp4 38.09M
├──2-2 libevent接口分析.mp4 12.04M
├──2-3 libevent服务端接收连接的代码示例.mp4 64.96M
├──2-4 libevent上下文属性配置和源码分析.mp4 65.95M
├──2-5 获取系统所支持的网络模型例如epoll_select.mp4 35.47M
├──2-6 配置特征_例如边缘触发_并判断是否生效event_con.mp4 82.61M
├──2-7 设置网络模型并显示当前应用的网络模型event_config.mp4 54.76M
├──2-8 windows上使用iocp网络模型并测试.mp4 164.90M
├──3-1 event事件状态流程和API接口分析.mp4 53.33M
├──3-10 event循环函数和退出代码示例event_base.mp4 44.57M
├──3-2 event在linux下信号事件处理evsignal_.mp4 73.71M
├──3-3 event的定时器接口讲解和代码示例.mp4 67.18M
├──3-4 event优化公用超时用双向队列替换二叉堆.mp4 24.92M
├──3-5 使用event的读取用户登录日志文件并监听文件更新.mp4 60.36M
├──3-6 使用event网络服务器的端口绑定和连接事件处理.mp4 81.42M
├──3-7 使用event网络服务器数据接收和响应并处理超时.mp4 42.58M
├──3-8 使用event网络服务器测试epoll的边缘触发ET.mp4 20.96M
├──3-9 event循环函数原理分析event_base_loop.mp4 34.38M
├──4-1 bufferevent基本原理缓冲水位分析.mp4 77.22M
├──4-2 bufferevent代码演示服务器接收和发送数据.mp4 85.56M
├──4-3 bufferevent超时事件处理和资源清理.mp4 47.98M
├──4-4 bufferevent客户端连接服务器.mp4 58.80M
├──4-5 bufferevent客户端发送文件并处理超时和断开事件.mp4 70.60M
├──5-1 bufferevent_filter过滤器接口分析.mp4 29.61M
├──5-2 buffervent输入输出过滤器处理代码讲解.mp4 64.27M
├──5-3 用于zlib示例的evbuffer处理函数分析.mp4 29.58M
├──5-4 zlib压缩和解压缩函数接口分析.mp4 29.91M
├──5-5 bufferevent_filter过滤器示例完成服务端.mp4 73.96M
├──5-6 bufferevent_filter完成过滤器客户端发送.mp4 76.11M
├──5-7 使用bufferevent的filter完成文件的发送.mp4 214.68M
├──5-8 使用bufferevent的filter和zlib完成文件.mp4 108.78M
├──5-9 使用过滤器和zlib完成服务端接收压缩数据并解压存储.mp4 116.66M
├──6-1 http协议分析.mp4 26.78M
├──6-10 完成了http客户端的POST请求.mp4 44.05M
├──6-2 libevent的evhttp接口分析.mp4 35.35M
├──6-3 evhttp服务器代码示例完成http请求消息解析.mp4 90.07M
├──6-4 evhttp读取本地网页响应浏览器请求.mp4 76.74M
├──6-5 完成http服务器支持图片文件下载和并能获取表单POST.mp4 60.63M
├──6-6 http客户端程序完成uri解析端口_服务器_请求地址.mp4 64.95M
├──6-7 完成http客户端的请求.mp4 44.21M
├──6-8 完成http的客户端接收的response并打印获取.mp4 42.87M
├──6-9 http客户端完成图片文件下载.mp4 30.14M
├──7-1 基于libevent的c++线程池原理详解.mp4 85.40M
├──7-2 创建好XThreadPool的单件模式代码.mp4 48.19M
├──7-3 使用c++11的thread完成XThread线程池.mp4 20.08M
├──7-4 完成线程的安装和跨平台管道激活事件处理.mp4 97.57M
├──7-5 完成线程池的线程分发和线程激活.mp4 37.61M
├──7-6 完成线程池的自定义任务和任务的线程分发.mp4 101.01M
├──7-7 完成想线程池线程中添加一个自定义任务并处理客户发送的数据.mp4 75.89M
├──7-8 完成线程池任务资源清理并移植到linux.mp4 140.31M
├──8-1 FTP协议详解和用到指令说明.mp4 177.67M
├──8-10 解析FTP协议中RETR完成文件下载功能.mp4 169.10M
├──8-11 解析FTP协议中STOR完成文件上传功能.mp4 116.28M
├──8-12 完成ftpserver的内存和资源清理.mp4 175.25M
├──8-13 基于libevent线程池的ftp项目完成移植到linu.mp4 163.38M
├──8-14 课程总结.mp4 33.58M
├──8-2 基于libevent的线程池FtpServer设计分析类分析.mp4 99.36M
├──8-3 重构线程池测试代码添加ftp工厂类和ftp任务基类.mp4 166.49M
├──8-4 完成ftp指令注册处理框架搭建并完成用户登录事件.mp4 112.57M
├──8-5 完成ftp服务器的PWD获取当前路径指令处理.mp4 114.39M
├──8-6 解析PORT命令分析出数据通道的IP和端口.mp4 130.01M
├──8-7 完成数据通道架构调整解析LIST发送测试的目录数据.mp4 125.54M
├──8-8 解析LIST指令完成windows中目录列表的发送.mp4 165.44M
├──8-9 完成FTP协议中CWD和CDUP目录切换.mp4 162.02M
└──课件.zip 185.50M
