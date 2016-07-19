






## Markdown 语法之个人版

### 本文目的
> * 本文持续更新，定期总结，直至熟练使用
> * 最后总结成第一份个人版 Cheatsheet

### 无论怎样，基础的基础在这里
>* [Mastering Markdown · GitHub Guides](https://guides.github.com/features/mastering-markdown/)
>* Markdown [Wikipedia EN](https://en.wikipedia.org/wiki/Markdown)
>* Markdown [Wikipedia 中文](https://zh.wikipedia.org/wiki/Markdown)
>  * 图片
>  * 换行；在文本中输入的换行会从最终生成的结果中删除，浏览器会根据可用空间自动换行。如果想强迫换行，可以在行尾插入至少两个空格。
>  * 强调；强调、加重强调、特别强调
>  * 代码
>  * 标题；#；======，--------
>  * 断行；如果你真的想在Markdown中插入换行标签<br/>，你可以在行尾输入两个或以上的空格，然后回车。这样插入换行十分麻烦，但是“每个换行都转换为<br/>”在 Markdown中并不合适，所以只在你确定你需要时手动添加。
>  * 引用；引用可以嵌套
>  * 链接
>  * 水平分区线
>  * 
>  * [wikipedia][1]
>  * [wikipedia][2]
>  * [wikipedia][1]
>  * 
>  * 
>  * 
>  * 

[1]:https://zh.wikipedia.org/wiki/Markdown
[2]:http://site.uit.no/english/words/intense/



###能与不能
>* \>* 与其后内容之间需要空格
>* >* 之间不需要空格
>* >* 之间两个空格或两个以上空格是再缩进
> * 加粗 ** 不能有空格
> * 标题 # 空格可有可无，且数量不限

### 实例 vs 反例
一般来说，一两个例子基本就能说明清楚问题了。

> * // > * 之间有或者说一般会有一个空格
> * 
>   * // * 前面再加两个空格

* Item 1
* Item 2
  * Item 2a
  * Item 2b

> 标记：Run `brew help` to get started

> Strikethrough 删除线，use `~~` for ~~ksdfghj~~

### 意外发现
要实现意外发现，需要先把 Markdown 语法 Disable 掉。
> * \

### 偶尔在在评论框中有如下发现：
> * # // 后有空格
> * ## // 后有空格
> * \### // 后有空格。备注：加不加一个“\”，显示不同。
> * **** // 加粗，Ctrl+b
> * __ // 斜体，Ctrl+i
> * > // 引用，
> * `` // insert code
> * [](url) // Add a link，Ctrl+k
> * - // Add a bulleted list
> * 1. // Add a numbered list
> * \\- [ ] // Add a task list。备注：加不加一个或两个“\”，显示不同。



### Question
> * 作为文本的链接内文字无法加粗

### Q&A 
> * 缩进之再缩进
>   * 开始加上两个空格
> * disable markdown
>   * \ 或 \ \
> * 

