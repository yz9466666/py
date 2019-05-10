1.环境搭建
anaconda环境配置
  参考https://blog.csdn.net/z2858539804/article/details/81407456  
  配置后效果如图：
  ![https://github.com/yz9466666/py/blob/master/1.png]
解释器
  Python解释器种类
  Python有好几种版本的解释器：
  CPython：官方版本的解释器。这个解释器是用C语言开发的，所以叫CPython。CPython是使用最广的Python解释器。我们通常说的、下载的、讨论的、使用的都是这     个解释器。
  Ipython：基于CPython之上的一个交互式解释器，在交互方式上有所增强，执行Python代码的功能和CPython是完全一样的。CPython用>>>作为提示符，而IPython用     In [序号]:作为提示符。
  PyPy：一个追求执行速度的Python解释器。采用JIT技术，对Python代码进行动态编译（注意，不是解释），可以显著提高Python代码的执行速度。绝大部分CPython代   码都可以在PyPy下运行，但还是有一些不同的，这就导致相同的Python代码在两种解释器下执行可能会有不同的结果。
  Jython：运行在Java平台上的Python解释器，可以直接把Python代码编译成Java字节码执行。
  IronPython：和Jython类似，只不过IronPython是运行在微软.Net平台上的Python解释器，可以直接把Python代码编译成.Net的字节码。
2.python初体验
  print
  
  https://www.cnblogs.com/laoliu07/p/10653999.html
