# markdown-note
markdown学习笔记

## 2018-10-10

## 一、markdown 基本语法

### 1. 标题

只需要在文本前面加上 # ，还可以增加二级标题、三级标题、四级标题、五级标题和六级标题，总共六级，只需要增加 # 即可，标题字号相应降低

>1. \#   一级标题
>2. \##  二级标题
>3. \### 三级标题

# 一级标题
## 二级标题
### 三级标题

...

以此类推，最多六级，其中一级标题文字最大

### 2. 列表

需要在文字前面加上 - 或 1. 两个标识符

>- 列表 -- 1
>- 列表 -- 2
>- 列表 -- 3

(无须列表)

- 列表 -- 1
- 列表 -- 2
- 列表 -- 3

>1. 列表 -- 1
>2. 列表 -- 2
>3. 列表 -- 3

(有序列表)

1. 列表 -- 1
2. 列表 -- 2
3. 列表 -- 3

**注**：*-、1.* 之间需要有一个空格

### 3. 链接和图片

- **链接:**
需要使用 **\[显示文本](链接地址)** 这样的语法

>\[链接解释](链接)

[滴滴出行](https://www.didiglobal.com/)

- **图片:**
需要使用 **\!\[](图片链接地址)** 这样的语法

>\!\[图片解释文案](图片链接)

![图片解释文案](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 4. 引用

需要在你希望引用的文字前面加上 > 就好了

>\>引用文案

效果如下
>引用文案

### 5. 粗体和斜体

用 ** 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法

- **粗体**
>\**粗体文案**

**粗体文案**

- **斜体**
>\*斜体文案*

*斜体文案*

### 6. 代码引用

1. 如果引用的语句只有一段，不分行，可以用 \` 将语句包起来。

2. 如果引用的语句为多行，可以将 \`\`\` 置于这段代码的首行和末行。

>\`console.log('hello world')\`
>
>\`\`\`
>function sayHello () {
>  console.log('hello world')
>}
>\`\`\`

- 单行代码块
`console.log('hello world')`

- 多行代码
```javascript
function sayHello () {
    console.log('hello world')
}
```

### 7. 表格

代码展示
```
| Name       | Sex        | Age        |
| ---------- |:----------:| ----------:|
| Lemons     | man        | 22         |
| Diavd      | man        | 26         |
```
效果展示

| Name       | Sex        | Age        |
| ---------- |:----------:| ----------:|
| Lemons     | man        | 22         |
| Diavd      | man        | 26         |

>1. :--...--: 居中
>2. --...-- 左对齐
>3. --...--: 右对齐

## 2018-10-18 笔记
1. 图片居中展示

<div align=center>

![图片解释文案](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

</div>

>\<div align=center>
>
>\!\[图片解释文案](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
>
>\</div>
