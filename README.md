# Essay
记录一些临时想法

## 常用网址

云影ss https://get.cloudss.biz/

CNTK https://www.microsoft.com/en-us/cognitive-toolkit/

tensorflow https://www.tensorflow.org/

kaldi http://kaldi-asr.org/

linux命令大全 http://man.linuxde.net/

## C语言-stm32

&&与运算

||或运算

- 地址运算符&和取值运算符（间接运算符）*

在函数定义时若使用int a(* pti) 

则在调用函数时需对应使用a（&x）

如此在使用pti时对应的是一个x的地址&x，* pti则是指向这个地址的值

- 指针与数组

数组short dates[SIZE];

short * pti;

pti = dates;

或者pti = &dates[0];

**即数组 dates == &dates[0]**

dates + 2 == &dates[2]

*(dates + 2) == date[2]

*dates + 2 == date[0] + 2

## python-tensorflow

- 绝对路径与相对路径

Python2.x 缺省为相对路径导入，Python3.x 缺省为绝对路径导入

若Python2.x 要默认使用绝对路径导入，需要输入

from __future__ import absolute_import

from __future__ import division

from __future__ import print_function

## shell-kaldi

 \>\> 如果文件不存在，将创建新的文件，并将数据送至此文件；如果文件存在，则将数据添加在文件后面

 \> 如果文件不存在，同上，如果文件存在，先将文件清空，然后将数据填入此文

## matlab
