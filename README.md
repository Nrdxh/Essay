# Essay
记录一些临时想法

## C语言-stm32

**地址运算符&和取值运算符（间接运算符）***

在函数定义时若使用int a(* pti) 

则在调用函数时需对应使用a（&x）

如此在使用pti时对应的是一个x的地址&x，* pti则是指向这个地址的值

**指针与数组**

数组short dates[SIZE];

short * pti;

pti = dates;

或者pti = &dates[0];

**即数组 dates == &dates[0]

dates + 2 == &dates[2]

* (dates + 2) == date[2]

* dates + 2 == date[0] + 2

## python-tensorflow

## shell-kaldi

## matlab
