
---
title: VIM必备快捷键
tags: [Linux,vim]
categories: Linux
date: 2016-09-19

---

<kbd>ta</kbd> 跳到下一个a 前面，配合d，dt) 一直删除到这行的) 
<kbd>fa</kbd> 跳到下一个a 
<kbd>CTRL-F</kbd> 向前一页 <kbd>CTRL-B</kbd> 向后一页 
<kbd>CTRL-D</kbd> 向下半页 <kbd>CTRL-U</kbd> 向上半页
<kbd>ctrl+i</kbd> 跳转到函数、变量和#define
<kbd>ctrl+i</kbd> 向前跳到前几次光标位置
<kbd>ctrl+o</kbd> 向后跳到后几次光标位置

<kbd>vi{</kbd> 选中{}中间的内容,不包括{}， 可以([{'"<
<kbd>va{</kbd> 选中{}中间内容，包括{}

<kbd>:e!</kbd>重新读进上次保存的此文件内容
<kbd>:ab myname william_djj</kbd>
以后再编辑时键入myname，然后空格或回车myname串就会被william_djj代替
<kbd>:r !command</kbd> 在当前位置插入command结果
<kbd>:r filename</kbd> 当前位置插入文件内容
不退出vim，直接执行命令，例如在perl文件中，直接执行不退出，<kbd>:!perl %</kbd> 。 如果前面已经执行过了，则重复前面的命令时，只需要<kbd>:!!</kbd>
插入模式下<kbd>ctrl +r</kbd>，=算式，回车插入结果
<kbd>% </kbd>跳转到相配对的括号，或流控
<kbd>D</kbd> 表示删除从当前光标到光标所在行尾的内容.
删除某行后面的换行符号：在命令状态下，在某一行上按"J"键将Join下一行，呵呵
<kbd>u</kbd> 撤销上次的操作，<kbd>ctrl+r</kbd>恢复上次的撤销。 

<kbd>:n,$s/vivian/sky/g</kbd> 替换第 n 行开始到最后一行中每一行所有 vivian 为 sky
n 为数字，若 n 为 .，表示从当前行开始到最后一行
可以使用 # 作为分隔符，此时中间出现的 / 不会作为分隔符
<kbd>:s#vivian/#sky/#</kbd> 替换当前行第一个 vivian/ 为 sky/


<kbd>:f</kbd>查看当前文件
<kbd>v</kbd>选择模式  ，<kbd>ctrl+v</kbd>块选择模式，<kbd>V</kbd>行选择模式


<kbd>^</kbd> 行首 
<kbd>$</kbd>行尾
<kbd>0</kbd> 第一个字符

<kbd>y</kbd> 复制
<kbd>d</kbd> 删除
<kbd>x</kbd> 剪切
<kbd>p</kbd> 粘贴
