---
layout: post
title: "StackOverflow-Charp常见问题1"
modified:
categories: 
description:
tags: []
image:
  feature:
  credit:
  creditlink:
comments:
share:
date: 2015-06-07T23:25:44+08:00
---
## String 和 string 有什么不同？
如：
{% highlight csharp %}
string s="Hello,World";
String S="Hello,World";
{% endhighlight %}
在C#中```string```是```System.String```的别名，所以在技术上来说没有什么区别，就像```int```和```System.Int32```一样。不过在使用过程中我们一般使用```string```来指向一个字符串对象，
{% highlight csharp %}
string str="hello";
{% endhighlight %}
然而，在使用字符串对象的方法时我们一般使用```String```
{% highlight csharp %}
string greet=String.Format("Hello {0}",place)
{% endhighlight %}
微软的例子中经常这样用
 [原问题地址](http://stackoverflow.com/questions/7074/whats-the-difference-between-string-and-String/7077#7077) 
测试CRLF 测试CRLF