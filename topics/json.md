## 什么是JSON

JSON全称JavaScript Object Notation，翻译成中文是 JavaScript对象表示法。

JSON格式的数据格式非常适合于服务器与 JavaScript 的数据交互，JSON数据格式也成为轻量级数据交换格式。

## JSON格式的特点

1. 最外层有一堆挂括号。
2. 内容都是由一对对key/value组成。

#### 使用JSON的注意点

![](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/json.png)


1. 红色：必须有挂括号。
2. 黄色：双引号必须是半角字符（英文挂括号）
3. 蓝色：key值只能是英文(或符合标准的字符，坚决不能是中文)
4. 绿色：双引号必须是半角字符（英文挂括号）
5. 橙色：值可以是任意字符(包涵中文)。但最外层的双引号必须是半角字符。
6. 紫色：一对key/value必须由半角的逗号隔开。

#### 记住

1. 编程世界中不能用任何中文输入法的字符。
2. 字符串除外

双引号(半角)包住的内容较字符串

```
"jack" //正确。这事一个字符串，这个字符串的长度是4

“jack” //错误。用了中文引号（全角）。

"杰克" //正确。引号(半角)包住的都是字符串的内容。
```


## JSON的举例

```
//错误
{
  name: "jack" // name必须用双引号包住。
}

//正确
{
  "name": "jack"
}
```
```
//错误
{
  "name": jack // jack必须用双引号包住。
}

//正确
{
  "name": "jack"
}
```
```
//错误
{
  "name": "jack"  //两个key/value之间没有用逗号分开
  "sex": "man"
}

//正确
{
  "name": "jack",  
  "sex": "man"
}
```
```
//错误
{
  姓名: "jack"  //key使用了中文
}

//正确
{
  "name": "jack"
}
```
```
//错误
{
  name: “杰克”  //使用了中文的双引号
}

//正确
{
  "name": "杰克"
}
```
```
// 正确
{"name": "jack"}

回车不是必要的，回车的目的只是为了更直观
```
```
//正确
{"name": "jack", "sex": "man"}

回车不是必要的，回车的目的只是为了更直观
```