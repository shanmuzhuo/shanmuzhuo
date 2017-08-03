---
layout: post
title:  "你好 GitHub"
date:   2017-04-09 14:34:25
categories: mediator feature
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---

# 我的markdown学习过程

### TO DO LISt

- [x] 已经完成项目
	- [x] 项目一
	- [x] 项目二
- [ ] 待办事项
- [ ] 待办事项2 

### 代码高亮

```java
public class Demo{
	public static void main(String[] args) {
		System.out.println("hello world");	
	}
}
```

### 引用
> 为了更好的自己，每一天的付出都是值得的。

### 无序列表
- 列表一
	- 列表1.1
	- 列表1.2
- 列表二
- 列表三

### 有序列表
1. 列表1
2. 列表2
	1. 列表2.1
	2. 列表2.2
3. 列表3

### 粗体/斜体
*这段文字是斜体*
**这段文字是粗体**

### 插入链接
[百度官网](http://www.baidu.com)

### 插入图片
![一张网络图片](http://note.youdao.com/favicon.ico)

![一张本地图片](ailee.jpg)

### 分割线
这是第一段内容
***
这是第二段内容
***
这是第三段内容

### 表格
header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2

|Item	 |value	|pwd	|
|:-------|-------|-------|
|computer|888$	 |5		 |
|phone   |999￥  |12     |
|watch   |999￥  |12     |

### 流程图
```graph 
	TD
	A[main] --> B(GO Shopping)
	B --> C{let me think}
	C -->|one |D[laptop]
	C -->|two |E[iphone]
	C -->|three|F[car]
```

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

### 流程图
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
