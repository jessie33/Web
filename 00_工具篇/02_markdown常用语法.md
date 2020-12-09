### markdown常用语法

```
参考链接：
markdown基本语法：https://www.jianshu.com/p/191d1e21f7ed/
```



[toc]

#### 零、目录

- 语法：

```
[toc]
```



#### 一、标题

- 语法：

```
# 一级标题
## 二级标题
###### 六级标题，最小标题
```

- 效果：

![](https://github.com/jessie33/Web/raw/master/IMG/markdown标题效果.png)


#### 二、字体

- 语法：

```
加粗：文字左右分别用2个*包起来
斜体：文字左右分别用1个*包起来
斜体加粗：文字左右分别用3个*包起来
删除线：文字左右用2个~包起来
```

- 效果：

**加粗**

*斜体*

***斜体加粗***

~~删除线~~



#### 三、引用

- 语法：文字前加>，不用空格。引用也可以嵌套，如加两个>>三个>>>

  ```
  >这是引用
  >>yinyong2
  ```

- 效果

>这是引用
>
>>yinyong2



#### 四、分割线

- 语法：3个或者3个以上的 - 或者 * 都可以

```
---
***
```

- 效果：

---
***



#### 五、图片

- 语法：

```
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

- 效果：

![wēixin](https://github.com/jessie33/Web/raw/master/IMG/logo_weixin.png)



#### 六、超链接

- 语法：

```
[超链接名](超链接地址 "超链接title")
title可加可不加
```

```
[简书](http://jianshu.com)
[百度](http://baidu.com)
```

- 效果：

[简书](http://jianshu.com)
[百度](http://baidu.com)



#### 七、列表

- 语法：

```
无序列表：- 文字， - + *都可以
有序列表：数字. 文字
列表嵌套：子列表的选项前添加4个空格即可
1. 父哈哈：
    - 子哈哈
    - 子哈哈
```

- 效果：

1. 父哈哈：
    - 子哈哈
    - 子哈哈



#### 八、表格

- 语法：

```
| 表头 | 表头 | 表头 |
| -- | :--: | --: |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```

- 效果：

| 表头 | 表头 | 表头 |
| ---- | :--: | ---: |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |



#### 九、代码

- 语法：

```
单行代码：
`create database hero;`

代码块：
​```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
​```
```

- 效果：

```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```



#### 十、流程图

- 语法：

```
​```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

- 实例：

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```



