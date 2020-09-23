# Compiler-based-on-LL-1-grammar
编译原理课程作业——基于python语言实现C的子集
基本功能：
1、可以实现表达式赋值，布尔逻辑运算

2、实现了for,while，if,else语句以及语句嵌套功能

3、定义类型暂时只有int型

4、根据语法规则自动生成LL（1）预测生成表

5、基于全局定义的函数调用功能

lexical为词法文件，实现tokens数据流分析，采用正则表达式实现

syntax为生成LL(1)预测分析表以及FIRST，FOLLOW集，

semantic为递归下降子程序，并嵌入语义分析，生成符号表以及四元式

vm为解释程序，实际上就是对四元式进分析

compilerGUI为一个简单的图形界面

