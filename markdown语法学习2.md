# MdrkDown语法part3

## 水平分隔线 demo  
    HTML中的语法<hr> Horizontal Rule代表水平分隔线。  
    在MD语法中同样常用。

```
MD中3种实现方法：3个中隔线，3个星号，3个下划线，均为英文半角符号.  
```  

---
    <hr> Horizontal Rule
***
    <hr> Horizontal Rule
___

## HTML代码 demo  
HTML代码在MarkDown中都可以支持。  

例如：  
- 借助HTML语法使标题居中显示：  
<p align='center'>Hello World</p>  

- HTML的注释功能可在MD中使用：  
<!--这是块注释，不会显示-->  


## 表格 demo    
| 这 | 是 | 表头 |  
|---|:---:|---:|  
| cell1|cell2cell2cell2|cell3cell3cell3|  
|row1| row2|row3|  

注：中间那行，2个冒号夹着内容，则这列为居中；冒号在右边，则这列为靠右。


## GFM demo  
GFM: Github Flvored Markdown，Github实现的具有自身特色的MD功能。  

##### task list任务列表    

- [x] task 1  

- [ ] task 2  

- [ ] task 3  

##### emoji表情符号  
语法：  

    :emoji code:  
      
:smile:  
:+1:  
:pray:    

注：在github平台中可见表情符号