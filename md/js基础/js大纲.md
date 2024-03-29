# JS大纲

## 向页面添加JS
* script src
```html
    <script src="./"></script>
```
* script src async
```html
    <script src="./" async></script>
```
    告知浏览器在遇到<script>元素时不要中断后续HTML内容的加载

* script src defer
```html
    <script src="./1.js" defer></script>
    <script src="./2.js" defer></script>
    <script src="./3.js" defer></script>
```
    defer 属性的脚本将按照在页面中出现的顺序加载

## JS注释方式
```js
    //let a = 1;
    /*
        let a = 2;
        let b = 1;
        console.log(a+b);
    */
```

## 类型、值和变量
 ### 数据类型 
 * [数据类型](./类型、值和变量/数据类型.md)
 ### 各种值 
 * [各种值](./类型、值和变量/各种值.md)
 ### 变量
 * [变量](./类型、值和变量/变量.md)

## 表达式和运算符
### 表达式
* [表达式](./表达式和运算符/表达式.md);

### 运算符
* [运算符](./表达式和运算符/运算符.md);

## 语句
 ### 条件语句
* [条件语句](./语句/条件语句.md)
 ### 循环语句
* [循环语句](./语句/循环语句.md)
 ### 跳转
* [跳转](./语句/跳转.md)
 ### 其它语句
* [其它语句](./语句/其它语句.md)

## 函数
 ### 定义函数
 * [定义函数](./函数/定义函数.md)
 ### 调用函数
 * [调用函数](./函数/调用函数.md)
 ### 函数的属性、方法和构造函数
 * [属性、方法、构造函数](./函数/属性、方法和构造函数.md)
 ### 参数
 * [参数](./函数/参数.md)
 ### 作为参数的函数
 * [作为参数的函数](./函数/作为参数的函数.md)
 ### 函数作用域
 * [函数作用域](./函数/函数作用域.md)
 ### 递归
 * [递归](./函数/递归.md)
 ### 闭包
 * [闭包](./函数/闭包.md)
 ### 函数式编程
 * [函数式编程](./函数/函数式编程.md)
 
## 对象
    
    对象是属性的无序集合，每个属性都是一个键值对。属性名是字符串，因此可以把对象看做是字符串到值得映射。
    对象还可以从一个被称为原型的对象继承属性。对象中不能包含两个相同名字的属性。每个属性都有"属性特征"

    可写 表明是否可以设置该属性的值

    可枚举 表明是否可以通过for/in循环返回该属性

    可配置 表明是否可以删除或者修改该属性

    每个对象还拥有"对象特征"

    原型(prototype)指向另一个对象，本对象的属性继承自它的原型对象。

    对象的类(class)是一个标识对象类型的字符串

    对象的扩展标记，指明了是否可以向该对象添加属性

三类对象和两类属性
* 内置对象，例如数组，函数，日期，正则
* 宿主对象 由js解释器嵌入的宿主环境，比如web浏览器
* 自定义对象 由运行中的js代码创建的对象
* 自有属性 是直接在对象中定义的属性
* 继承属性 由原型对象中继承的属性

 ### 创建对象
 * [创建对象](./对象/创建对象.md)


## 数组 
