# Java-Backend-Tech-Road
> Java 后端技术进阶之路





### JVM

[JAVA虚拟机关闭钩子(Shutdown Hook)](https://mp.weixin.qq.com/s?__biz=MzIxMTE0ODU5NQ==&mid=2650237386&idx=1&sn=817622b2d70a54d66c8f22d4756af848&chksm=8f5a0396b82d8a801df124fdbdb898cf2bb59b436a4159fec19789603e8879b8984b66866e6e&mpshare=1&scene=1&srcid=0903d74V5ST2oHEjqlusEUvT#rd)

* 来源：公众号

* 摘要：

  ```
  -Java程序的Hook，也叫钩子方法，可以通过 Java.Runtime.addShutdownHook(Thread hook) 来实现
  -Java程序触发Hook的场景:
      1、程序正常退出
      2、使用 System.exit()
      3、终端使用 Ctrl+C 触发的中断
      4、系统关闭
      5、OutOfMemory 宕机
      6、使用 Kill pid 命令干掉进程，但是 kill -9 pid不会
  ```

  

