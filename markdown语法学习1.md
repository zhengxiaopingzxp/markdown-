# Demo2  
## 链接 demo  
语法：  

    [链接文字](URL)  
注:方括号圆括号都是英文半角括号      
### 内嵌式链接   
- 外部链接:[百度](http://www.baidu.com)  
- 内部链接1：链接仓库的其他文件：[demo1](demo1.md)  

    注：如果demo1和当前文件在同一个目录下面，就不用写绝对路径，直接写相对路径“demo1.md”
- 内部链接2：链接本文档的其他部分：[代码块 demo](demo2.md#代码块-demo)  

    注：链接到本文档内，URL地址为demo2.md + 井号键# + 链接标题（空格用横杠代替）

### 引用式链接  
- 外部链接:[百度] 
- 内部链接1：链接仓库的其他文件：[demo1] 
- 内部链接2：链接本文档的其他部分：[代码块 demo]  

    注： 当一份文档中链接很多且比较长时，引用式链接可以使MD文档内容看起来清晰明了，因为它把所有链接都放到了文档最后，类似于论文引用
 
## 图片 demo  
- 语法：  

        ![alt](url "text")  
        即感叹号+[图片名称](图片地址+空格+"鼠标悬停时的浮动提示文字")   
     
- 外部图片demo：  
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")   
  
- 图片的引用式链接：    
![baidu][baidu_logo]

## 引用 demo  
语法：  
 
     半角大于号“ > ” + 引用的文字  
      
>这是一段引文。  
——出自《出处》  

## 代码块 demo  
- 行内代码  
这个代码中用来表示是标题的是`<title></title>`，表示文档主体部分的是`<body></body>`。  

注：行内代码前后各1个半角的反引号。无法形成语法高亮

- 块式代码  
  
```html  
<head><title>我是标题</title><head>;
<body><h5>我是身体</h5></body>
```

注：上下各3个半角的反引号，形成块式代码。  
且在上一行中写明是什么代码（javascript/html/css），会形成语法高亮




<!-- 下面是本文档中用到的链接 -->  
<!--链接 demo-->  
[百度]: http://www.baidu.com  
[baidu]: http://www.baidu.com  
[demo1]: demo1.md  
[代码块 demo]: demo2.md#代码块-demo  

<!--图片 demo-->  
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png