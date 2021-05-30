##  Introduction

##### 程序运行的两种方式

解释器运行（interpreters）：边解释边执行，不需要生成目标代码，每次执行都需要重新解释，运行速度较编译器慢，但平台通用性更好。以该方式执行的语言包括：python、ruby

<img src="CH1 Introduction.assets/image-20210520223028487.png" alt="image-20210520223028487" style="zoom:50%;" />



编译器翻译后运行（compilers）：编译后生成目标代码后执行，编译后重新执行不需要重新编译，运行速度较快，但平台通用性不佳。以该方式执行的语言包括：C/C++

<img src="CH1 Introduction.assets/image-20210520223450395.png" alt="image-20210520223450395" style="zoom:50%;" />



两种模式混合运行（Hybrid）:程序运行时同时包含解释和编译。如：Java、JavaScript。

<img src="CH1 Introduction.assets/image-20210520223838138.png" alt="image-20210520223838138" style="zoom:50%;" />



##### 编译的步骤（phase）

程序的编译共包含7个步骤：词法分析、语法分析、语义分析、中间代码生成、机器无关代码优化、生成目标代码、机器相关代码优化。