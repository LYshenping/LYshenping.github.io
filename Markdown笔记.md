# Markdown  学习笔记  (精简版)

## 一、标题与段落

# 一级标题
## 二级标题
### 三级标题

段落之间空一行。行尾加两个空格换行  
或使用`<br>`换行。

---

## 二、文字格式

**加粗** *斜体* ***加粗斜体*** ~~删除线~~ 

转义字符用`\`:  
\- 这不是列表

---

## 三、列表

### 无序列表

- 项目1
- 项目2
    - 子项目（缩进2-4空格或tab）

### 有序列表

1. 第一项
2. 第二项
2. 第三项
    1. 子项

数字自动排序

### 任务列表

- [ ] 未完成
- [x] 已完成

---

## 四、链接与图片

### 链接

[普通链接](https://example.com)  
[带title的链接](https://example.com "Just an example url")  
<https://example.com>  <!-- 即直接使用<url> -->  
[引用链接][1]

[1]: https://www.markdown.com '引用链接title'

### 图片

![图片名称](https://picsum.photos/400/200 '图片title')
[![图片名称](https://picsum.photos/400/200 '图片title')](https://www.baidu.com 'title') <!-- 图片超链接 -->

URL中若出现空格，使用%20代替：`/my%20page`

---

## 五、引用与代码

> 单层引用
>> 嵌套引用

`行内代码`
```python
# 代码块（```指定语言）
print('Hello world!')
```

---

## 六、表格

|左对齐|居中|右对齐|
|:---|:---:|---:|
|内容|内容|内容|

---

## 七、提示框（github风格）

> [!NOTE]
> 提示信息

> [!WARNING]
> 警告信息

> [!TIP]
> 小技巧

---

## 八、其他

### 脚注

需要注释的文字[^1]

[^1]: 脚注注释内容。

### 定义列表

术语
: 定义内容

### 分割线

--- 或 *** 或 ___

### 空格

|字符|含义|常见宽度|
|:---:|:---:|:---:|
|键盘` `|普通窄空格|约1/4全角|
|`&nbsp;`|不换行窄空格|约1/4全角|
|`&ensp;`|半方空格|半角|
|`&emsp;`|全方空格|全角|

### 内嵌HTML

<span style="color:red;">红色文字</span>
<kbd>Ctrl</kbd>+<kbd>C</kbd>

<span style='color:pink;'>粉</span>
<span style='color:red;'>红</span>
<span style='color:orange;'>橙</span>
<span style='color:yellow;'>黄</span>
<span style='color:green;'>绿</span>
<span style='color:blue;'>蓝</span>
<span style='color:purple;'>紫</span>

### 小众语法

文本下方加`===`实现一级标题`---`实现二级标题

### 注释

html风格`<!-- 注释内容 -->`

<!-- 注释内容 -->

markdown风格`[//]: # (注释内容)`

[//]: # (也可以把()换成'')
