GitHub上README.md的简单介绍
===
## 1、编辑README文件

大标题（一级标题）：在文本下面加等于号，那么上方的文字就变成了大标题，等于号的个数无限制，但一定要大于0

大标题
===
大标题<br>
\===


中标题（二级标题）：在文本下面加下划线，那么上方的文本就变成了中标题，下划线个数无限制，中标题比大标题低一级

中标题
---
中标题<br>
\---<br>
 

 1~6级标题：文本大小依次减小，以#号开头，多少个#号就是多少级标题，#号和标题名称要并排写

\# 一级标题<br>
\## 二级标题<br>
\### 三级标题<br>
\#### 四级标题<br>
\##### 五级标题<br>
\###### 六级标题<br>
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
插入圆点符号：编辑的时候使用的是星号 *，星号后面要有一个空格，否则为普通星号

\* 列表一<br>
\* 列表二<br>
\* 列表三<br>
* 列表一
* 列表二
* 列表三
 

二级圆点、三级圆点：多加一个Tab，即第二行一个Tab，第三行两个Tab

\* 列表一<br>
   \* 列表二<br>
       \* 列表三<br>
* 列表一
    * 列表二
        * 列表三
 

缩进：

\>缩进一<br>
\>>缩进二<br>
\>>>缩进三<br>
\>>>>缩进四<br>
\>>>>>缩进五<br>
>缩进一
>>缩进二
>>>缩进三
>>>>缩进四
>>>>>缩进五
 

## 插入链接

\[百度]\(http://baidu.com)<br>
[百度](http://baidu.com)
 

*  插入网络图片：![](网络图片链接地址)，即叹号!+方括号[]+括号()，如果不加叹号!就会变成普通文本，方括号里可以加入一些 标识性的信息

\![baidu]\(http://www.baidu.com/img/bdlogo.gif "百度logo")<br>
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  
 

插入GITHub仓库里的图片：![](图片链接地址)，即叹号!+方括号[]+括号()，URL写法：http://github.com/自己的用户名/项目名/raw/分支名/存放图片的文件夹/文件夹里的图片名字

给图片加上超链接：即点击一个图片进入指定网页，方括号里写自己起的标识名称，上下两行标识要一致。

[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"  
 

插入代码片段：在代码上下行用```标记，注意`符号是tab键上面那个，要实现语法高亮，则在```后面加上编程语言的名称

```Java
public static void main(String[] args){}
```

```javascript
document.getElementById("ts").innerHTML="Hello"
```
换行：使用标签<br>

单行文本：前面使用两个Tab

多行文本:每行行首加两个Tab

部分文字高亮：使用``包围，这个符号不是单引号，而是Tab上方，数字1左边那个按键的符号

文字超链接格式：[要显示的文字](链接的地址"鼠标悬停显示")，在URL之后用双引号括起来一个字符串，即鼠标悬停显示的文本，可不写


## 可参考链接
(http://blog.csdn.net/brian512/article/details/41310269)<br>
(http://www.cnblogs.com/shiy/p/6526868.html)
