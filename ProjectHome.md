  * Advanced C library(ACL) for UNIX-like OS and WIN32 OS, including sync/async iostream for net/file, thread pool, process pool, database pool, server framework, event, smart string, configure parser,array/hash/ring/list, http protocol lib, C unit test...
  * ACL工程是一组由标准C完成的库，可以运行在WIN32、LINUX平台上。该库既包含一些常用的函数库，又包含一组服务器框架。函数库主要包含以下内容：
    1. 常用的数据结构(如哈希、堆栈、队列、双向链表、动态数组、二叉树、二分块查找等)及一些哈希算法(如CRC32、CRC64)
    1. 网络/文件数据缓冲流操作(包含同步网络通信及非阻塞式网络通信)
    1. 事件调度(封装了 select, epoll, /dev/poll等)及定时器
    1. 多线程消息(包含IO消息及线程消息队列消息)
    1. 数据库操作组件(包含MYSQL数据库连接池、TCP连接池、内存数据库)
    1. 半驻留式线程池库
    1. 单元测试组件库
    1. 从POSTFIX中提炼并加工的半驻留式服务器框架--master(包含进程池、线程池、非阻塞式、触发器等服务器调度模板)--目前该框架仅可运行在UNIX平台下
    1. 内存池分配器(借鉴于SQUID)，可以大大提高内存分配效率
    1. 配置文件库
    1. 文件目录操作库
    1. 一些方便实用的字符串操作，尤其是来源于POSTFIX的 VSTRING 库，其操作易用性几乎可以与MFC的CString相媲美
    1. 网络通信库(包含网络监听、网络连接、DNS查询、DNS协议查询)
    1. 此外，还包含一个基于ACL库的HTTP协议实现，以及一些简单易懂的SAMPLES
    1. 所有代码都在GCC3.4.6，VC2003，CBuilder6上编译通过
