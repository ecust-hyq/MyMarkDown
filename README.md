# MarkDown语法
## 什么是MarkDown
>Markdown是一种轻量级标记语言，创始人为约翰·格鲁伯（英语：John Gruber）。 它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。
由于Markdown的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，许多网站都广泛使用Markdown来撰写帮助文档或是用于论坛上发表消息。 如GitHub、Reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge、简书等，甚至还能被使用来撰写电子书-[百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)
## 为何使用MarkDown
MarkDown使用纯文本格式编写，用户无需过多考虑字体大小，颜色等，有利于沉浸式创作，并且其非常轻量化，广泛地应用于各大网页文本的撰写。
相较于Word图形化使用界面，MarkDown在语法上需要有一定的了解。
## 快速完成一篇MarkDown文稿
### 1. 首先我要有一大标题
> 输入`# 一级标题`
>显式效果：
># 一级标题
>注意：#号后面一定要加一个**空格**  
### 2. 然后我要写一个二级标题
>输入`## 二级标题`
>显式效果：
>## 二级标题
>注意：这里同样要在#号后面加一个**空格**
### 3. 我要开始写正文了
>1. 我的内容需要**有序分点罗列**
>>输入：`1.` + <kbd>space</kbd> +`内容`
>显式效果：*就是此块内容你所见到的效果啦*
>2. 我的内容只需要**无序分点罗列**就好
>>输入：<kbd>-</kbd>+ <kbd>space</kbd>+`内容`
>>显示效果：
>>+ 内容1：<kbd>*</kbd>和<kbd>-</kbd>有同样的效果哦
>>+ 内容2：<kbd>+</kbd>也是同样的效果
>3. 想给文字**加粗**？
>>输入：<kbd> * </kbd><kbd> * </kbd>+`内容`+<kbd> * </kbd><kbd> * </kbd>
>>显示效果：**加粗**
>4. 部分内容变为**斜体**？
>><kbd> * </kbd>+`内容`+<kbd> * </kbd>
>>显示效果：*斜体*
### 4. 插入链接
> 输入：`[链接名称](链接地址)`
> 显示效果：[链接名称](https://github.com/ecust-hyq/MyMarkDown/edit/main/README.md)
### 5. 插入图片
> 输入：`!`+`[链接名称](链接地址)`
> 注意：  
> 
> 1. 保存在计算机本地的图片一般有防盗链机制，网页无法直接使用，故不可直接将本地图片地址直接添加到链接地址
> 2. CSDN可直接点击图片按钮，将图片上传到CSDN库，可以直接生成图片及响应链接
> 3. Github需要用到git，比较复杂。关注我，持续更新，给你最清晰的解答。你的关注与点赞是我写博的最大动力

### 6. 插入代码块
输入：```java
这里可以是JavaScript或Python等语言
显示效果
> ```java
> public class Code(){
> 		public static void main(String[] arg){
> 				System.out.println("HelloWord")
> 		}
> }
>```
>也可以是无风格的内容块，直接按4个<kbd>space</kbd>，或者一个<kbd>Tab</kbd>键生成内容块  
>	如下所示：
>
	public class Code(){
		public static void main(String[] arg){
			System.out.println("HelloWord")
		}
	}
### 7. 你一定已经发现这篇文章出现了很多<kbd>按钮</kbd>符号，`高亮标记`符号
>1. 按钮符号
>> `<kbd>` +`内容`+`</kbd>`
>>显式出效果
>><kbd>内容</kbd>
>>注意： `<kbd>`会将该行后面所有内容以此样式显式，若只想显式后面部分文字内容，需要加上带`/`的`</kbd>`
>>助记：这里**kbd**是**keyboard**的缩写
>2. 高亮标记
>>输入：两个<kbd>`</kbd>将内容包起来  
>>
>>显式效果：
>>`内容`  

到这里我们已经完成了一篇漂亮的文章了，快来试试吧!
有任何问题都可以随时<kbd>submit</kbd>你的`issue`！你的star和fork是我更新的最大动力！谢谢！
>语法表随后更新，敬请期待！
