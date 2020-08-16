# wjq 自检清单

## 本周完成情况

- [x] 每周 1 篇技术博客: [浏览器内存泄漏](https://blog.csdn.net/qq_40552867/article/details/108038365)
- [x] 10 个面试问题
1.`HTML5`为什么只需要写  `<!DOCTYPE HTML>` ，而不需要引入 DTD

HTML5 不基于 SGML，因此不需要对 DTD 进行引用，但是需要 DOCTYPE 来规范浏览器的行为（让浏览器按照它们应该的方式来运行）。

而 HTML4.01 基于 SGML ，所以需要对 DTD 进行引用，才能告知浏览器文档所使用的文档类型。

2.`html`你是如何理解语义化的？

语义化，顾名思义，就是你写的HTML结构，是用相对应的有一定语义的英文字母（标签）表示的，标记的，因为HTML本身就是标记语言。不仅对自己来说，容易阅读，书写。别人看你的代码和结构也容易理解，甚至对一
些不是做网页开发的人来说，也容易阅读。那么，我们以后再开发的过程中，一定要注意了，尽量使用官方的有语义的标签，不要再使用一堆无意义的标签去堆你的结构。

 语义化，也无非就是自己在使用标签的时候多使用有英文语义的标签，比如h标签，在HTML中就是就是用来定义标题，还有p标签，英文是paragraph段落，table表格标签,等等。

3.`css` box-sizing属性

用来控制元素的盒子模型的解析模式，默认为content-box

context-box：W3C的标准盒子模型，设置元素的 height/width 属性指的是content部分的高/宽

border-box：IE传统盒子模型。设置元素的height/width属性指的是border + padding + content部分的高/宽

4.`css`优先级算法如何计算？

元素选择符： 1

class选择符： 10

id选择符：100

元素标签：1000

5. `css` CSS3新增伪类有那些?

p:first-of-type 选择属于其父元素的首个元素

p:last-of-type 选择属于其父元素的最后元素

p:only-of-type 选择属于其父元素唯一的元素

p:only-child 选择属于其父元素的唯一子元素

p:nth-child(2) 选择属于其父元素的第二个子元素

:enabled :disabled 表单控件的禁用状态。

:checked 单选框或复选框被选中。

6.`javascript` typeof 返回哪些数据类型？

 基础类型包括：Number、String、Boolean、Null、Undefined、Symbol（该类型位 ES2015 中新增类型）
 
 引用类型包括：Object typeof 运算符把类型信息以字符串形式返回，需要注意的是 typeof 返回的类型和 JavaScript 定义的类型有细微的差异。 typeof 返回七种可能的值：“number”、“string”、“boolean”、“object”、"symbol"、“function”和“undefined”。

7. 例举至少 3 种强制类型转换和 2 种隐式类型转换

强制类型转换： 明确调用内置函数，强制把一种类型的值转换为另一种类型。强制类型转换主要有：Boolean、Number、String、parseInt、parseFloat

隐式类型转换： 在使用算术运算符时，运算符两边的数据类型可以是任意的，比如，一个字符串可以和数字相加。之所以不同的数据类型之间可以做运算，是因为 JavaScript 引擎在运算之前会悄悄的把他们进行了隐式类型转换。隐式类型转换主要有：+、–、==、!

8.`javascript`事件流模型都有什么？

事件流描述的是从页面中接收事件的顺序。 DOM 结构是树形结构，当页面中的某一个元素触发了某个一个事件，事件会从最顶层的 window 对象开始，向下传播到目标元素，途径的祖先节点都会触发对应的事件，如果当前节点的该事件绑定了事件处理函数的话，则会执行该函数当事件达到目标元素并执行绑定函数（如果有绑定的话）后，事件又会向上传播到 window 元素，途径的祖先节点都会触发对应的事件

9.`javascript`BOM 对象有哪些，列举 window 对象？

window 对象，是 JS 的最顶层对象，其他的 BOM 对象都是 window 对象的属性；

document 对象，文档对象；

location 对象，浏览器当前URL信息；

navigator 对象，浏览器本身信息；

screen 对象，客户端屏幕信息；

history 对象，浏览器访问历史信息；


10.`javascript`请简述 AJAX 及基本步骤？

AJAX即异步 JavaScript 和 XML，是指一种创建交互式网页应用的网页开发技术。通过在后台与服务器进行少量数据交换，AJAX 可以使网页实现异步更新。这意味着可以在不重新加载整个网页的情况下，对网页的某部分进行更新。

AJAX 基本步骤：

初始化ajax对象

连接地址，准备数据

发送请求

接收数据（正在接收，尚未完成）

接收数据完成

- [x] 代码时间打卡

![](https://raw.githubusercontent.com/matplot/code/master/%E5%9B%BE%E7%89%87/readme1.png)


