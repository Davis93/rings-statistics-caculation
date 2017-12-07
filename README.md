# rings-statistics-caculation
分子动力学计算的数据处理，我用的是VASP，得到的是XDATCAR。之后用rings 软件进行计算
rings软件的官方网址：http://rings-code.sourceforge.net/ ， 感兴趣可以去看看。软件是利用fortran语言写的，作为一个编程小白学习起来还是相当吃力，软件比较小众，我们课题组没有人会用，摸索的过程是一个痛苦的过程，小木虫里都没有相关教程，官网有一些介绍和实例，但是没有数据，无法运行，很尴尬。
rings计算用所用到文件包含，data/XDATCAR ,my-input(名字可以随意取，你喜欢就好，知道是输入文件就好)，options(就是这个名字，不能改，就是控制你需要算什么)
下面给出一个简单的例子。介绍rings 软件的使用，和一些注意的地方。主要是XDATCAR和my-input的格式，自己摸索，修改起来真的很痛苦，尼玛。

XDATCAR格式也要注意一下，具体看文件
