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


# jquery学习网  
菜鸟教程[jquery runboo](https://www.runoob.com/jquery/jquery-intro.html)
