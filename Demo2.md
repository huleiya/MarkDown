# Demo2


## 链接Demo

### 内嵌式链接

- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：[demo1](Demo1.md)
- 内部链接2，链接本文档的其他部分：[代码块 Demo](Demo2.md#代码块-demo)

### 引用式链接

- 外部链接：[百度]
- 外部链接：[百度别名][baidu]
- 内部链接1，链接仓库的其他文件：[demo1]
- 内部链接2，链接本文档的其他部分：[代码块 Demo]


## 图片Demo

- 图片的MarkDown语法  
`![alt](url text)`

- 外部图片Demo	
![百度](https://www.baidu.com/img/bd_logo1.png?where=super "百度网站")

- 仓库内的图片Demo
![](images/bd_logo1.png)

### 图片的引用式链接

- 外部图片Demo	
![][baidu_logo]
- 仓库内的图片
![][baidu_demo]



## 引用Demo

> 窗前明月光，疑是地上霜。举头望明月，低头思故乡。

——出自《静夜思》

### 多重引用
>>> 这是多重引文

## 代码块Demo

- 行内代码

代码中用来声明变量的是`var = 10`， 用来打印变量内容的是`console.log(a)`

- 块式代码

```javascript
var = 10
console.log(a)
```

<!--- 下面是本文档中用到的链接 --->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:Demo1.md
[代码块 Demo]:Demo2.md#代码块-demo

[baidu_logo]:https://www.baidu.com/img/bd_logo1.png?where=super
[baidu_demo]:images/bd_logo1.png
