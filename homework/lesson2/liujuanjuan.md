## 听新生大学CTO讲JavaScript编程入门-2

by刘娟娟 2017-08-18

这堂课，老师依然用类比的方式，教我们认识编程世界的一个重要概念。

名字 = 变量

**命名**，是个哲学话题。现实世界中，为什么人、物、万事均有名字？没有一个名字，我们该如何指代ta呢？我们说到一个苹果，如果只能把那个苹果拿到眼前，那当我们吃掉它，或者在另外一个地方在谈论它时，又该如何指代它？

**等同吗？**名字能代表一个人吗？不能。名字用来指代一个人，但不能代表这个人。能代表这个人的，是他的一堆属性。比如身高、体重、性格、DNA、社交关系等等。_属性，除了属性的名字，还有属性的值。没有值的一个名，是没意义的。_

**以此类比**，在代码的世界里，我们用各种各样的**变量**名，来指代那些我们要用代码操控处理的对象。

我们需要命名，并把名字关联到具体的那个对象。变量需要先申明、再定义。

var myName;

myName = '刘娟娟';

这2行语句可以简写为：

var myName = '刘娟娟';

但，我需要记住的教训是：**只有变量名而无赋值的变量，是没意义的。**

在代码的世界里，变量有很多类型。有数字、字符串、数组、对象等等。为什么要有这么多的变量类型呢？因为变量本身就有那么多类型吖！_这个解释真是令人崩溃吖，老师此刻哭晕在办公室。_

**编程中为什么会有丰富化的数据格式？**

**不同的变量类型，是为了实现存储、传输、计算的效率最大化。**

存储占用硬盘空间，传输占用带宽流量，计算占用内存空间等等。不同变量类型所需要提供的字节大小是有差异的，既满足需求，又要实现效率最大化，于是发展出多种数据类型。

好消息是，**JavaScript中，变量的申明和定义，只需要一个var即可，它会自动处理变量的类型。**

## 本课知识点：

1、如何定义变量？ _直接用var+空格+变量名称;即可。_

2、JS如何处理变量类型？ _自动识别处理，无需编写代码的人操心。_

3、变量命名有哪些技巧或规范？ _英文，各种各样的形式，个人比较喜欢的是小写单词+后续单词首字母大写的驼峰模式。_

4、怎么掌握变量技巧和规范？ _不要背，看看老师和教程的sample，自己试着用用，用多了就融入骨子里。_

## 编写代码，本身如同讲话、写作，就是一种表达。

第2节课有一个令人印象深刻的演进过程，即从一段正常描述的文本，逐步拆解成程序的语言。让我等小白讶然：原来编写代码这么简单！

因为在写这篇小结时，我已经听了第3、4节课程，我越发觉得：把事情想复杂了，反而难以为继；简单点，恢复它的本原就好。
