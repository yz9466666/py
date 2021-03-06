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
    PyPy：一个追求执行速度的Python解释器。采用JIT技术，对Python代码进行动态编译（注意，不是解释），可以显著提高Python代码的执行速度。绝大部分CPython     代码都可以在PyPy下运行，但还是有一些不同的，这就导致相同的Python代码在两种解释器下执行可能会有不同的结果。
    Jython：运行在Java平台上的Python解释器，可以直接把Python代码编译成Java字节码执行。
    IronPython：和Jython类似，只不过IronPython是运行在微软.Net平台上的Python解释器，可以直接把Python代码编译成.Net的字节码。
2.python初体验
  print 和input
    ![https://github.com/yz9466666/py/blob/master/2.png]
    参考https://www.cnblogs.com/laoliu07/p/10653999.html
3.基础讲解
  python变量特性+命名规则
    变量保存的数据则可以多次发生改变，只要程序对变量重新赋值即可。
    Python 需要使用标识符给变量命名，其实标识符就是用于给程序中变量、类、方法命名的符号（简单来说，标识符就是合法的名字）。
    在使用标识符时，需要注意如下规则：
    a.标识符可以由字母、数字、下画线（_）组成，其中数字不能打头。
    b.标识符不能是 Python 关键字，但可以包含关键字。
    c.标识符不能包含空格。
  注释方法
    方式1：
    单行注释：shift + #（在代码的最前面输入，非选中代码进行注释）
    多行注释：同单行一样在每一行的前面输入shift+#
    方式2：
    单行和多行一样的方式：Ctr+/（前提是选中需要注释的代码）
    方式3：
    输入''' '''或者""" """，将要注释的代码插在中间
  dir()和help()
   dir()用来查询一个类或者对象所有属性
   ![https://github.com/yz9466666/py/blob/master/3.png]
   help()函数帮助我们了解模块、类型、对象、方法、属性的详细信息
   ![https://github.com/yz9466666/py/blob/master/4.png]
4.python数值基本知识
  在Python中，能够直接处理的数据类型有以下几种：整数、浮点数、字符串、布尔值、列表、元组、字典、集合。
    整数
      Python可以处理任意大小的整数，例如：1，100，-80，0，等等。
      计算机由于使用二进制，所以有时候用十六进制表示整数比较方便，十六进制用0x前缀和0-9，a-f表示，例如：0xff00，0x15a7b4，等等。
    浮点数
      浮点数也就是小数，之所以称为浮点数，是因为按照科学记数法表示时，一个浮点数的小数点位置是可变的，比如，1.23x105和12.3x104是完全相等的。浮点数       可以用数学写法，如1.2，3.141，-7.356，等等。对于很大或很小的浮点数，必须用科学计数法表示，把10用e替代，1.23x105就是1.23e5，或者12.3e8，           0.000012可以写成1.2e-5，等等。整数和浮点数在计算机内部存储的方式是不同的，整数运算永远是精确的，而浮点数运算则可能会有四舍五入的误差。
    字符串
      字符串是以单引号'或双引号"括起来的任意文本，比如'abc'，"xyz"等等。字符串'abc'只有a，b，c这3个字符。
      转义字符\可以转义很多字符，比如\n表示换行，\t表示制表符，字符\本身也要转义，所以\表示的字符就是\。
    布尔值
      布尔值和布尔代数的表示完全一致，一个布尔值只有True、False两种值。在Python中，可以直接用True、False表示布尔值（请注意大小写），也可以通过布尔       运算计算出来：
      >>> 3 > 2
      True
      >>> 3 > 5
      False
    空值None
      空值是Python里一个特殊的值，用None表示。None不能理解为0，因为0是有意义的，而None是一个特殊的空值。
    算术运算符
    ![https://github.com/yz9466666/py/blob/master/5.png]
    逻辑运算符
    ![https://github.com/yz9466666/py/blob/master/8.png]
    成员运算符
    ![https://github.com/yz9466666/py/blob/master/9.png]
    Python身份运算符
    身份运算符用于比较两个对象的存储单元。
    ![https://github.com/yz9466666/py/blob/master/11.png]
    运算符优先级
    ![https://github.com/yz9466666/py/blob/master/22.png]
    

