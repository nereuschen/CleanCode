#目录
* 1.什么是整洁的代码？
* 2.有意义的命名
	* 2.1 名副其实
	* 2.2
* 3.分支条件语句
	* 3.1 
	* 3.2
	* 3.3 
* 4.方法/函数
	* 4.1
	* 4.2
* 5.类
	* 5.1
	* 5.2
	* 5.3
* 6.注释
	* 6.1
	* 6.2
	* 6.3
* 7.错误处理
	* 7.1 C语言风格
	* 7.2 Golang风格
	* 7.3 基于java异常体系
	* 7.4 数据库事务处理原则
* 8.面向对象六大设计原则:OCP
	* 8.1 合成复用原则
	* 8.2 责任单一原则
	* 8.3 李氏替代原则
	* 8.4 迪米罗法则
	* 8.5 依赖倒置原则
	* 8.6 接口隔离原则

##什么是整洁的代码?
<b> Bjarne Stroustrup，C++之父：</b>
 
* 我喜欢优雅、高效的代码 
* 逻辑应该是清晰的，bug难以隐藏；
* 依赖最少，易于维护；
* 错误处理完全根据一个明确的策略；
* 性能接近最佳化，避免代码混乱和无原则的优化；
* 整洁的代码只做一件事。

<b> Grady Booch，《面向对象分析与设计》作者：</b> 

* 整洁的代码是简单、直接的；
* 整洁的代码，读起来像是一篇写得很好的散文；
* 整洁的代码永远不会掩盖设计者的意图，而是具有少量的抽象和清晰的控制行。

<b> Dave Thomas，OTI公司创始人，Eclipse战略教父：</b> 

* 整洁的代码可以被除了原作者之外的其他开发者阅读和改善；
* 具备单元测试和验收测试；
* 有一个有意义的名字；
* 使用一种方式来做一件事情；
* 最少的依赖，并明确定义；
* 提供了一个清晰的、最小的API；
* 应该根据语言特性，在代码中单独显示必要的信息，而不是所有的信息。

<b> Michael Feathers，《修改代码的艺术》作者：</b> 

* 整洁的代码看起来总是像很在乎代码质量的人写的；
* 没有明显的需要改善的地方；
* 代码的作者似乎考虑到了所有的事情。

<b>Ward Cunningham，Wiki和Fit创始人，极限编程联合创始人，Smalltalk和面向对象的思想领袖：</b> 

* 当你读代码时，你发现每个程序都如你期待的那样
* 你可以称之为漂亮的代码
* 代码完美展现了该编程语言的设计目的

<b><font color=red>
总之，整洁的代码的特点： 

* 容易与其他人协作（简单、意图明确、良好的抽象、不出意料、合适的名称）
* 针对现实世界，比如，有一个清晰的错误处理策略
* 代码作者显然很关心软件和其他开发者（针对双方的可读性和可维护性）
* 最小化（做一件事，最小的依赖）
* 以最合适的方式解决问题

</b>
</font>


##从变量命名谈起

* 方便的`导入导出`功能
    *  直接把一个markdown的文本文件拖放到当前这个页面就可以了
    *  导出为一个html格式的文件，样式一点也不会丢失
* 编辑和预览`同步滚动`，所见即所得（右上角设置）


##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(dev.hubo#gmail.com, 把#换成@)
* QQ: 287759234


##捐助开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一

##感激
感谢以下的项目,排名不分先后

* [mou](http://mouapp.com/) 
* [ace](http://ace.ajax.org/)
* [jquery](http://jquery.com)

##关于作者

```javascript
  var ihubo = {
    nickName  : "草依山",
    site : "http://jser.me"
  }
```

```java
for (int i = 0; i < 10; i++) {
    System.out.println("ten times");
}

```
