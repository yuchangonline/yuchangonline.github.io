---
layout:     post
title:      markdown
subtitle:   先得学会markdown
date:       2019-08-12
author:     YC
header-img: img/2019-08-12.png
catalog: true
tags:
    - 学习
---

学习markdown

来源：[https://www.jianshu.com/p/191d1e21f7ed](https://www.jianshu.com/p/191d1e21f7ed)  
      [http://www.markdown.cn/](http://www.markdown.cn/)  
      [https://www.runoob.com/markdown/md-tutorial.html](https://www.runoob.com/markdown/md-tutorial.html)  

***段落的换行是使用两个以上空格加上回车!***  

# 这是一级标题
## 这是二级标题
### 这是三级标题
（标题要加空格）  

# 文字  
**这是加粗文字**  
*这是斜体文字*  
***这是斜体加粗文字***  
~~这是加删除线的文字~~  
下划线可由html的<u>标签实现
>这是引用  


# 以下都是分割线（三个以上的*或-）  
---
----
***
*****


# 图片  
![这里是图片说明](图片地址 "图片title//可不加")  


# 超链接  
[超链接名](超链接地址 "超链接title//可不加")  
*在新标签页打开*  
使用html的a标签：  
<a href="https://" target= "_blank">连接</a>  


# 列表  
## 无序列表：  
- 列表内容（要有空格）  
+ 列表内容  
* 列表内容  
## 有序列表:  
1. 列表内容（要有空格too）  
2. 列表内容  
3. 列表内容  
## 列表嵌套  
上一级和下一级之间敲三个空格即可  


# 表格  
表头|表头|表头  
---|:--:|---:  
内容|内容|内容  
内容|内容|内容  
第二行分割表头和内容。  
- 有一个就行，为了对齐，多加了几个  
文字默认居左(:-)  
-两边加：表示文字居中(:-:)  
-右边加：表示文字居右(-:)  
注：原生的语法两边都要用 | 包起来。此处省略  


# 代码  
## 单行  
`用反引号框起来`  
## 块  
代码之间分别用三个反引号包起来，且两边的反引号单独占一行  
```  
  代码...  
  代码...  
  代码...  
```  


# 流程图  
```flow  
st=>start: 开始  
op=>operation: My Operation  
cond=>condition: Yes or No?  
e=>end  
st->op->cond  
cond(yes)->e  
cond(no)->op  
```  
~~好麻烦的样子我应该不会用吧~~  

# 附：  
[https://www.runoob.com/markdown/md-advance.html](https://www.runoob.com/markdown/md-advance.html)  
