# jquery简单例子

* HTML 元素选取
* HTML 元素操作
* CSS 操作
* HTML 事件函数
* JavaScript 特效和动画
* HTML DOM 遍历和修改
* AJAX
* Utilities
* Jquery插件。

 # 特定内容详解 
## jQuery - 获取内容和属性  
attr 和 prop 的区别介绍：
对于 HTML 元素本身就带有的固有属性，在处理时，使用 prop 方法。
对于 HTML 元素我们自己自定义的 DOM 属性，在处理时，使用 attr 方法。    
实例 1：
```<a href="https://www.runoob.com" target="_self" class="btn">菜鸟教程</a>```    
这个例子里 <a> 元素的 DOM 属性有: href、target 和 class，这些属性就是 <a> 元素本身就带有的属性，也是 W3C 标准里就包含有这几个属性，或者说在 IDE 里能够智能提示出的属性，这些就叫做固有属性。处理这些属性时，建议使用 prop 方法。    
```<a href="#" id="link1" action="delete" rel="nofollow">删除</a>```  
这个例子里 <a> 元素的 DOM 属性有: href、id 和 action，很明显，前两个是固有属性，而后面一个 action 属性是我们自己自定义上去的，<a> 元素本身是没有这个属性的。这种就是自定义的 DOM 属性。处理这些属性时，建议使用 attr 方法。  
  
prop()函数的结果:

  1.如果有相应的属性，返回指定属性值。

  2.如果没有相应的属性，返回值是空字符串。

attr()函数的结果:

      1.如果有相应的属性，返回指定属性值。

      2.如果没有相应的属性，返回值是 undefined。

对于HTML元素本身就带有的固有属性，在处理时，使用prop方法。

对于HTML元素我们自己自定义的DOM属性，在处理时，使用 attr 方法。

具有 true 和 false 两个属性的属性，如 checked, selected 或者 disabled 使用prop()

## jQuery Ajax GET和POST
GET 和 POST 方法的区别：
1、发送的数据数量

在 GET 中，只能发送有限数量的数据，因为数据是在 URL 中发送的。

在 POST 中，可以发送大量的数据，因为数据是在正文主体中发送的。

2、安全性

GET 方法发送的数据不受保护，因为数据在 URL 栏中公开，这增加了漏洞和黑客攻击的风险。

POST 方法发送的数据是安全的，因为数据未在 URL 栏中公开，还可以在其中使用多种编码技术，这使其具有弹性。

3、加入书签中

GET 查询的结果可以加入书签中，因为它以 URL 的形式存在；而 POST 查询的结果无法加入书签中。

4、编码

在表单中使用 GET 方法时，数据类型中只接受 ASCII 字符。

在表单提交时，POST 方法不绑定表单数据类型，并允许二进制和 ASCII 字符。

5、可变大小

GET 方法中的可变大小约为 2000 个字符。

POST 方法最多允许 8 Mb 的可变大小。

6、缓存

GET 方法的数据是可缓存的，而 POST 方法的数据是无法缓存的。

7、主要作用

GET 方法主要用于获取信息。而 POST 方法主要用于更新数据。

# jquery学习网  
菜鸟教程[jquery runboo](https://www.runoob.com/jquery/jquery-intro.html)
