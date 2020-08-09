# wjq 自检清单

## 本周完成情况

- [x] 每周 1 篇技术博客: [javascript客户端检测](https://blog.csdn.net/qq_40552867/article/details/107893756)
- [x] 10 个面试问题
1.`html`DTD 

DTD是一组机器可读的规则，它们定义 XML 或 HTML 的特定版本中所有允许元 素及它们的属性和层次关系的定义。在解析网页时，浏览器将使用这些规则检查页面的有效性并且采取相应的措施。

DTD 是对 HTML 文档的声明，还会影响浏览器的渲染模式（工作模式）。

2.`html`Label 的作用

label 标签来定义表单控制间的关系，当用户选择该标签时，浏览器会自动将焦点转到和标签相关的表单控件上。

3.`css`选择符有哪些？那些属于可以继承？

id选择器(#myid)

类选择器(.myclassName)

标签选择器(div,h1,p)

子代选择器(ul>li)

后代选择器(li a)

通配符选择器(*)

属性选择器(a[rel="external"])

伪类选择器(a:hover,li:nth-child)

可继承的样式： font-size font-family color

不可继承的样式： border padding margin height width

4.`css`flex(弹性盒布局模型)以及使用场景

一个用于页面布局的全新css3功能，flexbox可以把列表放在同一个方向(从上到下排列，从左到右)，并且列表能延伸到占用可用的空间，较为复杂的布局还可以嵌套一个伸缩容器(flex container)来实现。采用flex布局的元素，成为flex容器。常规布局是基于块和内联流方向，而flex布局是基于flex布局flex-flow流可以很方便的用来做居中，能对不同屏幕大小自适应，在布局上有了比以前更加灵活的空间

5. `css` 水平、垂直居中的写法

水平居中

行内元素: text-align: center

块级元素: margin: 0 auto

position:absolute +left:50%+ transform:translateX(-50%)

display:flex + justify-content: center


垂直居中

设置line-height 等于height

position：absolute +top:50%+ transform:translateY(-50%)

display:flex + align-items: center

display:table+display:table-cell + vertical-align: middle;

6.`javascript` 异步加载的方式

 渲染引擎遇到 标签会停下来，等到执行完脚本，继续向下渲染

defer 是“渲染完再执行”，async 是“下载完就执行”，defer 如果有多个脚本，会按照在页面中出现的顺序加载，多个async 脚本不能保证加载顺序

加载 es6模块的时候设置 type=module，异步加载不会造成阻塞浏览器，页面渲染完再执行，可以同时加上async属性，异步执行脚本（利用顶层的this等于undefined这个语法点，可以侦测当前代码是否在 ES6 模块之中）

7. 解释`JavaScript`中定时器？说明定时器的缺点？

定时器用于在设定的时间执行一段代码，或者在给定的时间间隔内重复该代码。这通过

使用函数setTimeout，setInterval和clearInterval来完成。

setTimeout（function，time）用于启动在所述延迟之后调用特定功能的定时器。

setInterval（function，time）用于在提到的延迟中重复执行给定的功能，只有在取消时才停止。

clearInterval（id）指示定时器停止。

缺点：定时器在一个线程内运行，因此事件可能需要排队等待执行。

8.`javascript`的split() join() 的区别

split()将字符串按照指定的字符分割成一个数组，并返回

join()将数组用指定的字符连接成一个字符串，并返回

9.`javascript`数组方法pop() push() unshift() shift()

栈方法：
push()尾部添加，返回 数组长度
pop()尾部删除，返回 被删除的元素

队列方法：
unshift()头部添加 ，返回 数组长度
shift()头部删除，返回被删除的元素

10.`javascript`事件绑定和普通事件有什么区别

普通事件：给html元素添加一个特定的属性（比如：onclick）

事件绑定：js代码中通过标记(id tag class)获取元素，给元素添加特定的方法(比如onclick)

- [x] 代码时间打卡

![](https://raw.githubusercontent.com/matplot/code/master/%E5%9B%BE%E7%89%87/readme.png)

