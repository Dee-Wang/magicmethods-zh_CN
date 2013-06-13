# Python 的神奇方法指南 #

###Rafe Kettler###

Copyright &copy; 2012 Rafe Kettler

Version 1.17

A PDF version of this guide can be obtained from [my site](http://www.rafekettler.com/magicmethods.pdf) or [Github](https://github.com/RafeKettler/magicmethods/raw/master/magicmethods.pdf). The magic methods guide has [a git repository at http://www.github.com/RafeKettler/magicmethods](http://www.github.com/RafeKettler/magicmethods). Any issues can be reported 
there, along with comments, (or even contributions!).

**<a id="table" href="#table">目录</a>**
 
1. [介绍](./magicmethods.markdown#1)
2. [构建和初始化](./magicmethods.markdown#2)
3. [使操作符在自定义类内工作](./magicmethods.markdown#3)
    * [神奇方法——比较](./magicmethods.markdown#31-)
    * [神奇方法——数字](./magicmethods.markdown#32-)
4. [描述你的类](./magicmethods.markdown#4)
5. [属性访问控制](./magicmethods.markdown#5)
6. [制作自定义序列](./magicmethods.markdown#6)
7. [反射](./magicmethods.markdown#7)
8. [可调用对象](./magicmethods.markdown#8)
9. [上下文管理](./magicmethods.markdown#9)
10. [构建描述符对象](./magicmethods.markdown#10)
11. [Pickling 你的对象](./magicmethods.markdown#11pickling-)
12. [总结](./magicmethods.markdown#12)
13. [附录：如何调用神奇方法](./magicmethods.markdown#13)
