---
layout: post
title:  "Markdown语法总结!"
subtitle:   "Markdown使用指南"
date:   2016-03-18 14:38:11 +0800
categories: tech edit markdown

author:     "zhongyw"
header-img: "img/home-bg.jpg"
tags:
    - markdown
---


### 目录

- [定义标题](#title)

- [定义粗体、斜体](#bold_italic)

- [分割线](#halvingline)

- [列表](#list)

- [添加超链接、图片](#link)

- [添加表格](#table)

- [添加代码](#code)

- [引用](#quote)

- [小型文本](#small)


# 定义标题 {#title}

```
# 一级标题 {#id}
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
大标题
=
小标题
-
```
预览效果：

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题


大标题
=
小标题
-

# 粗体、斜体 {#bold_italic}

Markdown语法：

```markdown
**粗体**
__粗体__
*斜体*
_斜体_
```
预览效果：

**粗体**
__粗体__
*斜体*
_斜体_

# 分割线 {#halvingline}

Markdown语法：

```markdown
    ---
    ***
    ~~文字删除线~~
```

预览效果：
 
---
***
~~文字删除线~~


# 列表 {#list}

```markdown

- 无序列表项目
- 无序列表项目
- 无序列表项目

* 无序列表项目
* 无序列表项目
* 无序列表项目

1. 有序列表项目
2. 有序列表项目
3. 有序列表项目

- 外层列表项目
 + 内层列表项目
 + 内层列表项目
 + 内层列表项目
- 外层列表项目

```
预览效果：

- 无序列表项目
- 无序列表项目
- 无序列表项目

* 无序列表项目
* 无序列表项目
* 无序列表项目

1. 有序列表项目
2. 有序列表项目
3. 有序列表项目

- 外层列表项目
 + 内层列表项目
 + 内层列表项目
 + 内层列表项目
- 外层列表项目

# 添加超链接、图片 {#link}

### 文本链接

代码：

```markdown
   [网易](http://www.163.com/)
```
结果：[网易](http://www.163.com/)

### 显示图片

代码：

```markdown
 ![网易](/img/in-post/editor/netease.jpg)
```
结果：

![网易](/img/in-post/editor/netease.jpg)


### 替换法

代码：

```markdown
[网易][1]
![网易][2]

[1]:/img/tech/editor/netease.jpg
[2]:/img/tech/editor/netease.jpg
```

结果：

[网易][1]
![网易][2]

[1]:/img/in-post/editor/netease.jpg
[2]:/img/in-post/editor/netease.jpg


# 添加表格 {#table}

    | ABCD | EFGH | IJKL |
    | -----|:----:| ----:|
    | a    | b    | c    |
    | d    | e    |  f   |
    | g    | h    |   i  |
    
    ABCD | EFGH | IGKL
    -----|------|----
    a    | b    | c
    d    | e    | f
    g    | h    | i
    
| ABCD | EFGH | IJKL |
| -----|:----:| ----:|
| a    | b    | c    |
| d    | e    |  f   |
| g    | h    |   i  |

ABCD | EFGH | IGKL
-----|------|----
a    | b    | c
d    | e    | f
g    | h    | i


# 添加代码 {#code}


### 行内代码\`字符\`：

`var a = 1;` 这是一条赋值语句

### `Tab`或四个空格（大段文字添加代码框，每行前添加）：

            var a = 1;

### \`\`\`方式：

```markdown
    ```js
    ...

    ```
```
```js
var a = 1;
function f(){
    console.log("hello world");
}
```


# 引用 {#quote}

    > 引用的文字
    > 引用的文字
    > 引用的文字
    
    > 引用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引
    用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引用
    的文字引用的文字引用的文字
    
    > 引用的文字引用的文字引用的文字引用的文字引用的文字
    
     >> 引言内的引言引言内的引言引言内的引言
    
    > 引用的文字引用的文字引用的文字引用的文字引用的文字
    
> 引用的文字
> 引用的文字
> 引用的文字

---

> 引用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引
用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引用
的文字引用的文字引用的文字

---

> 引用的文字引用的文字引用的文字引用的文字引用的文字

 >> 引言内的引言引言内的引言引言内的引言

> 引用的文字引用的文字引用的文字引用的文字引用的文字


# 小型文本 {#small}

    <small>文本内容</small>

small： <small>文本内容</small>

正常： 文本内容
    