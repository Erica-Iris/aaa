### 关于Markdown

Markdown是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。

**优点**

> * 简单标记符完成排版，所写即所见，让你专注于文字而不是排版

* 纯文本，所以兼容性极强，可以用所有文本编辑器打开
* 格式转换方便，Markdown文本可以轻松转换为 html、pdf等
* Markdown 的标记语法有极好的可读性

### Markdown简单语法示例

---

主要分为区块元素和区段元素。

#### 区块元素

---

###### 1.段落和换行

一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行。

###### 2.标题

用#标识符表示，例如：

![](//upload-images.jianshu.io/upload_images/1122690-2f32f3c1bcb2e9db.png?imageMogr2/auto-orient/strip|imageView2/2/w/722/format/webp)

Paste_Image.png

###### 3.区块引用

* 在段落的第一行最前面加">"

  ![img](//upload-images.jianshu.io/upload_images/1122690-359173376a9922ab.png?imageMogr2/auto-orient/strip|imageView2/2/w/763/format/webp)
* 区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：

  ![img](//upload-images.jianshu.io/upload_images/1122690-21c2852e9513503f.png?imageMogr2/auto-orient/strip|imageView2/2/w/750/format/webp)
* 区块内也可以套用其他的 Markdown 语法，包括加粗、列表、代码区块等：

  ![img](//upload-images.jianshu.io/upload_images/1122690-b3f5c77bd6f57871.png?imageMogr2/auto-orient/strip|imageView2/2/w/780/format/webp)

###### 4.列表

Markdown 支持有序列表和无序列表。

* 无序列表使用星号、加号或是减号作为列表标记，效果一样：

  ![](//upload-images.jianshu.io/upload_images/1122690-45da3e39d762f194.png?imageMogr2/auto-orient/strip|imageView2/2/w/688/format/webp)

  Paste_Image.png
* 有序列表则使用数字接着一个英文句点：

  ![](//upload-images.jianshu.io/upload_images/1122690-5651ae146d6e722b.png?imageMogr2/auto-orient/strip|imageView2/2/w/729/format/webp)

  Paste_Image.png

###### 5.代码区块

要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，例如，下面的输入：

![img](//upload-images.jianshu.io/upload_images/1122690-efd3b1828205a622.png?imageMogr2/auto-orient/strip|imageView2/2/w/756/format/webp)

###### 6.分隔线

你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

```undefined
   ***
   ---
   * * *
```

#### 区段元素

###### 1.链接

方块括号后面紧接着圆括号并插入网址链接即可，例如：

![](//upload-images.jianshu.io/upload_images/1122690-d2e91c881357d457.png?imageMogr2/auto-orient/strip|imageView2/2/w/765/format/webp)

,

###### 2.强调

Markdown 使用星号（*）和底线（_）作为标记强调字词的符号

* *斜体*

![](//upload-images.jianshu.io/upload_images/1122690-1cd38ae8ec1de2d7.png?imageMogr2/auto-orient/strip|imageView2/2/w/744/format/webp)

* 粗体

![](//upload-images.jianshu.io/upload_images/1122690-0ad7593fdd7c5eab.png?imageMogr2/auto-orient/strip|imageView2/2/w/756/format/webp)

* 删除线

![](//upload-images.jianshu.io/upload_images/1122690-22d935ee712de1e7.png?imageMogr2/auto-orient/strip|imageView2/2/w/710/format/webp)

* 空格

Markdown语法会忽略首行开头的空格，如果要体现出首行开头空两个的效果，可以使用 全角符号下的空格 ，windows下使用 shift+空格 切换。

![](//upload-images.jianshu.io/upload_images/1122690-0d50cae630b3bc65.png?imageMogr2/auto-orient/strip|imageView2/2/w/736/format/webp)

###### 3.行内标记

行内标记用反引号把它包起来' '，例如：

![](//upload-images.jianshu.io/upload_images/1122690-51fa7d2797238325.png?imageMogr2/auto-orient/strip|imageView2/2/w/729/format/webp)

###### 4.插入图片

我用过的简书在线编辑器和马克飞象都支持直接导入本地图片和从粘贴板粘贴，就像酱紫：

![](//upload-images.jianshu.io/upload_images/1122690-5e3bfd076fdd5bd9.png?imageMogr2/auto-orient/strip|imageView2/2/w/746/format/webp)

Paste_Image.png

#### 其他

###### 1.反斜杠

Markdown可以利用反斜杠来插入一些在语法中有其它意义的符号，例如：如果你想要用星号加在文字旁边的方式来做出强调效果，你可以在星号的前面加上反斜杠：

![](//upload-images.jianshu.io/upload_images/1122690-24c7e805c0a10b1b.png?imageMogr2/auto-orient/strip|imageView2/2/w/704/format/webp)

###### 2.自动邮箱链接

Markdown支持以比较简短的自动链接形式来处理电子邮件信箱

![](//upload-images.jianshu.io/upload_images/1122690-2023636d03742800.png?imageMogr2/auto-orient/strip|imageView2/2/w/736/format/webp)

###### 3.表格
