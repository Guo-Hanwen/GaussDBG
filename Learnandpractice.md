This is a markdown course!
====
-----
####Let's begin with grammar.

##1.标题
标题可以用=、-、#标记，=标记最高阶标题，-标记第二阶标题，#根据数量的多少，分别用来标记1到6阶标题。注意要使用-插入分割线时，需要与前面的文字间隔一行。

##2.字体
Markdown使用星号（\*）和底线（\_）作为标记强调字词的符号，但是在字符的前后两端要使用一样的符号。推荐使用星号（\*）因为不区分全角半角，不需要切换输入法。在文字前后直接插入星号时可以使用反斜线\

单个星号为倾斜\*这是倾斜\*：*这是倾斜*

双星号为加粗\*\*这是加粗\*\*:**这是加粗**

三星号为加粗倾斜\*\*\*这是加粗倾斜\*\*\*:***加粗倾斜***

此外还有加删除线~~加删除线~~。

##3.分割线
可以在一行中用三个以上的星号、减号或底线来创建一个分割线，行内不能有空格之外的其他字符。
* * *
- - -
_____

##4.引用
在引用的文字前加>即可。同时可以根据层次加上不同数量的>来进行嵌套引用。
>这是一行引用
>>这是一行嵌套引用
>>>我还可以继续嵌套

我还能偷个懒，只在段首加一个>就能一次性引用一整段：
>什么人站在革命人民方面，他就是革命派，什么人站在帝国主义封建主义官僚资本主义方面，他就是反革命派。什么人只是口头上站在革命人民方面而在行动上则另是一样，他就是一个口头革命派，如果不但在口头上而且在行动上也站在革命人民方面，他就是一个完全的革命派。

##5.列表
Markdown支持有序列表和无序列表。

无序列表使用星号，加号或是减号作为列表标记。*，+，-与列表内容之间要有一个空格。

- 列表内容
+ 列表内容
* 列表内容

有序列表使用数字加一个英文句点作为标记。还是需要有一个空格，且输入的数字与输出结果没有关系，结果只会从第一个数字开始排序。

3. 列表内容
2. 列表内容
6. 列表内容

列表是可以嵌套的，只需要在上一级和下一级之间敲三个空格即可。

- 一级列表内容
   - 二级列表内容
      - 三级列表内容

列表项目可以包含多个段落，每个项目下的段落都必须缩进4个空格或是1个制表符：

1. 我们共产党人从来不隐瞒自己的政治主张。我们的将来纲领或最高纲领，是要将	中国推进到社会主义社会和共产主义社会去的，这是确定的和毫无疑义的。我	们的党的名称和我们的马克思主义的宇宙观，明确地指明了这个将来的、无限	光明的、无限美妙的最高理想。
	——《论联合政府》（一九四五年四月二十四日），《毛泽东选集》第三卷第一零五九页

##6.表格
| 人民 | 力量 |
| --- | ---|
| 不可 | 阻挡 |

##7.代码
Markdown中加入代码块有两种方式。
第一种，缩进4格或一个制表符即可：

	#include<摸鱼.jpg>
	using giveupspace std;
	int main()
	{
		bu xiang gan;
	}

第二种，单行代码：代码之间分别用一个反引号(键盘左上角)包起来即可：
`return 一个ding`
`error：10086`
代码块可以用三个反引号包起来，三个反引号分别占一行

```
cout<<"假如生活欺骗了你"<<endl;
cout<<"那么它就欺骗了你"<<endl;
```

##8.段落和换行
通过在结尾添加HTML的\<br>标签来换行。<br>
我<br>要<br>换<br>行

通过使用空白行或者HTML的\<p>进行段落分割:

对于人民的缺点是需要批评的，……但必须是真正站在人民的立场上，用保护人民、教育人民的满腔热情来说话。如果把同志当作敌人来对待，就是使自己站在敌人的立场上去了。<p>———《在延安文艺座谈会上的讲话》（一九四二年五月），《毛泽东选集》第三卷第八七四页

##9.超链接
链接文本放在中括号内，链接地址放在后面的括号中，链接的Title是可选的：<br> 
[毛主席语录](https://www.thpx.cn/content-70-391-1.html "学习经典")

也可以用两个尖括号把URL或者email地址变成可点击的链接：
<https://www.xuexi.cn/>

链接还可以是带格式的，表强调：    
让我们一起读：***[毛泽东语录](https://www.thpx.cn/content-70-391-1.html "学习经典")***

##10.图片
要添加图像可以用感叹号 (!), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本：    

![茁壮生长](/strong.jpg "向着希望")    

还可以再给图片加链接：<br>
[![TW大解放](/TWS.jpg "走进未来")](https://www.163.com/dy/article/GHPTFTDB0550HKO5.html)


#THE END!





