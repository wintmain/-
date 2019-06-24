# -w
输入一行C语言程序，识别出其中的函数调用，输出调用的函数名和实参名。 输入的C语言程序符合下列要求： 
1、该行程序是函数体内的一条可执行语句，符合C语言语法要求；
2、实参只是简单的变量，不会是常量、表达式、数组元素、结构变量的成员等； 
3、该行程序有可能是控制语句，可能的控制结构只有if、for、while三种情况；
4、该行程序中有可能有空格等空白符。假设该行程序字符数不超过100。
