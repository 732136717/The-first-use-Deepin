我们在Deepin的操作系统下的时候可以按照这个网站来配置C/C++配置环境：
https://blog.csdn.net/qq_34347375/article/details/80851417
但是其实我们自己测试的时候也会发现其实在运行的时候其实事情没有这么简单，会出现
“Unable to start debugging. Launch options string provided by the project system is invalid. 
Unable to determine path to debugger. Please specify the "MIDebuggerPath" option."的错误。这个时候就
需要我们按照：https://blog.csdn.net/qq_40871466/article/details/88079279来处理即可。
最后我们就是debug阶段了，debug阶段的时候在逐步调试最后会出现错误描述：
无法打开"libc-start.c"：无法读取文件(Error:找不到文件(/build/glibc-LK5gWL/glibc-2.23/csu/libc-start.c))
最后我们只需要按照：https://blog.csdn.net/weixin_39758398/article/details/101912759就可以完成最后的操作了。以上就是VScode
中C++的环境配置过程。
以上是我在网上找到自己测试过之后靠谱的一套流程。
具体流程等做系统的时候再专门做出来自己的一套完整的流程叭
