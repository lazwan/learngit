# Cube-Wang's

## My first Makedown code

### markdowm.md
# 一、
> This is a blockquote.
>
> This is the second paragraph in the blockquote.
>
> ## Welcome to my home!
>> Case1:
>>
>> Case2:
>> 
>> Case3:
>>
--------------------------------------------------
# 二、插入链接
>> [baidu](https://www.baidu.com)
>>
>> [Google](https://www.google.com)
--------------------------------------------------
# 三、列表
>> * Number1
>> 
>> * Number2
>> 
>> * Number3
>> 
>>>> 1.C
>>>>
>>>> 2.c++
>>>>
>>>> 3.Java
>>>> 
>>>> 4.Python
>>>> 
--------------------------------------------------
# 四、斜体、粗体
>> *这里是斜体*
>>
>> **这里是加粗**
>>
--------------------------------------------------
# 五、表格
>> 课程|星期一|星期二|星期三|星期四|星期五|星期六|星期日
>> :---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
>> 一|C语言|高等数学|离散数学|近代史纲要|Python| | 

# Next

## HDU_OJ 1089

### Problem:A+B for Input-Output Practice (I)

#### Problem Description
Your task is to Calculate a + b.
Too easy?! Of course! I specially designed the problem for acm beginners. 
You must have found that some problems have the same titles with this one, yes, all these problems were designed for the same aim.

#### Input
The input will consist of a series of pairs of integers a and b, separated by a space, one pair of integers per line.

#### Output
For each pair of input integers a and b you should output the sum of a and b in one line, and with one line of output for each line in input.

#### Sample Input
1 5
10 20

#### Sample Output
6
30
#### Coed
(''')
#include<stdio.h>
int main()
{
   int a,b,s;
   while(scanf("%d%d",&a,&b)!=EOF)
       printf("%d\n",a+b);
   return 0;
}
(''')










