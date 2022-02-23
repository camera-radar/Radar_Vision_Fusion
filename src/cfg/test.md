<!--
 * @Description: 
 * @Author: xielock
 * @Date: 2022-01-04 19:14:39
 * @LastEditors: xie
 * @LastEditTime: 2022-01-04 21:07:09
-->

# 一级标题 Xielock
## 二级标题 hello world
### 三级标题(可以到6级标题)  hello world

#### 1.1、段落控制
1. 换行：2个以上空格加一个回车  
2. 换行：或者当前行后加一个空行
#### 1.2、字体
1. 斜体 *xie*  _xie_
2. 粗体 **xie** __xie__
3. 粗斜体 ***xie*** ___xie___  
#### 1.3、分隔线
1. 多种方式 三个以上***/---/___/中间可以加空格
***
* * *
----
#### 1.4、删除线
1. 文字的两端加上~~波浪线即可  
2. ~~hello world~~
#### 1.5、下划线
1. 通过 < u > 来实现
2. <u>hello world</u>
#### 1.6、脚注
通过 [^xielock]。注意下 这里的变量声明都不要放到区块或者列表中

 [^xielock]:菜鸟

#### 2.1、列表
* 第一项
* 第二项
+ 标记后要有空格
- 还是
1. 第一项:  
    +  第一个元素
    + 嵌套  

#### 3.1、区块
1. 区块使用> 来进行控制 > 最外层 >>内层 类推
>外层
>>二层
>>>三层
#### 3.1、区块内使用表
> 1. noe  
> 2. noe  
>+ 写 
#### 3.2、表内使用区块
1. >第一项  
2. >第二项  
3. >第三项1  
    >第三项2
#### 4.1、markdown代码
1. 段落中的代码使用`printf()`包起来
2. 代码区块使用四个空格或者一个Tab来实现   
3. 或者使用```来包含 并注明语言, 也可不指定
``` C++
#include<iostream>
#include<vector>

using namespace std;
int main()
{
    return 0;
}
```
        cout<<endl;
#### 5.1、markdown链接
1. [链接名称] ( 链接地址 ) 注意去掉空格或者直接使用 <链接地址> 加http前缀
2. 这是一个链接 [xielock's website](http://xielock.com)
3. 这是一个链接 <http://xielock.com>
#### 5.2、高级链接
1. 通过变量来设置一个链接，变量的赋值在文档的末尾进行
> 这个链接使用1作为网址变量 [google][1]  
>这个链接使用2作为网址的变量 [Github][2]  
>注意下这里的声明不要放到列表里 即1. 之后 /或者>里面等等
>[百度][baidu_url]

[1]:http://google.com  
[2]:http://github.com/  
[baidu_url]: http://www.baidu.com

#### 6.1、图片
1. 图片的语法为：开头感叹号！  接着方括号，里面描述性文字  最后一个普通括号，里面是图片的地址
 ![xielock's wallpaper](/home/xielock/图片/Wallpapers/3.jpg)
2. 同样可以类似网址那样使用

#### 7.1 表格
1. 使用| 分隔不同单元格，使用-分割表头和其他行  
   | 水果        | 价格    |  数量  |
    | --------   | -----  | ---- |
    |    橡胶           | 2       | 3     |
2. 自己试一下  
   | 工作 | 薪酬 | 年限|  
   |:---- | ----:|  :-----: |
   |左对齐| 右对齐|  居中对齐|
   


