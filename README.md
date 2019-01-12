# Markdown Practice
markdown的食用方法，now start. 

## 1.标题的食用
markdown食用标题时，跟html不同的是，用#号的个数+上空格来实现。  
一级标题就一个#号，以此类推，官方的文档介绍有六级标题吧，下面来操作一下吧。  
# 我是一级标题
## 我是二级标题
### 我是三级标题
#### 我是四级标题呀
##### 我是五级小老弟
###### 我是666

## 2.段落的食用
  一个页面，或者说一篇作文，开头第一行总是写作文的题目，然后开始写作文的内容，但是不可能一直写下去，不起新段落吧？这样是被语文老师骂惨的。所以有了段落，  
  阅读性才好一些啊。不然密密麻麻的，密集恐惧症患者打死你哦。markdown的段落，是前后都要空一行才实现的，如果我要换行呢，则是两个空格+回车实现。  
  反正效果嘛，我已经实现了。#滑稽  

## 3.区块引用的食用
  这个环节，没啥想说的，也不知道该怎么说。首先一个段落，然后要引用啥的，首行或者每行使用符号>就行了。  
  >我是区块块块块
  >>我是嵌套的区块鸭

## 4.代码区块的食用
  在markdown里编写代码示例时，该行要四个空格哦，或一个制表符（制表符好像是%t？？？懵逼，不知道gitgub里面写markdown语法tab健能有四个空格吗）  
  代码如下：  
  
    void main() {  
        println("冲鸭！");  
    }  
  
  #一开始实现不了，在做列表时，想到F12检验，然后就回来操作，代码块前后要空一行才行呢(- _ -)  
  
## 5.强调的食用
  强调嘛，其实就是加租哦(･ิω･ิ)，变歪，加租就内容左右连个 * 或者 _ ,斜体就一个。  
  **我很粗壮哦#滑稽**，*槽糕射歪了（寒冰大招射歪而已，想什么哦）*
  
## 6.列表的食用
  哦呼，撑不住了，就快点操作一下吧，不BB了。  使用·、+、或-标记无序列表，如：  
  注意：标记后面最少有一个_空格_或_制表符_。若不在引用区块中，必须和前方段落之间存在空行。  
  * 一列  
  * 二列  
  * 三列  
  
  有序序列：（F12来判断是否成功）  
  1. first  
  2. second  
  3. third  
  
## 7.分割线的食用
  分割线，可以用三个或以上的 * ，或 - 或 _  
  ***  

## 8.链接的食用
  链接可以由两种形式生成：行内式和参考式。  
  ### 行内式
  [hy的Markdown库](https://github.com/hy529283176/markdownpractice)。
  
  ### 参考式：
  [hy的Markdown库1][1]  
  [hy的puppy库2][2]  
  [1]:https://github.com/hy529283176/markdownpractice "Markdown"  
  [2]:https://github.com/hy529283176/puppy "puppy"  

## 9.
