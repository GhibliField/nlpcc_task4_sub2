我切割数据集的时候存在一些问题

1：存在一些slot-dictionaries:song中不存在的词 如 什话

2：存在一些不存在的slot-dictionaries类别(扫了一眼挺多的) 如 destination

3：英文单词(歌手名等等一些专有名词中存在空格，我觉得会影响分词，我全部替换成的#，如 m c替换成m#c)

4: slot-dictionaries:中的词要怎么处理合适。

5: test_data.txt 没按slot-dictionaries的值去切，直接按数据集去切了


阅读代码遇到的问题。

求助中。。。
https://github.com/applenob/RNN-for-Joint-NLU/issues/6

记录一个bug
#还没有做
1 k折部分的代码 没做好 以及实现 抽取这块

2 <s>embedding 的替换</s>
 
3 词向量的优化
  
4 <s>tensorboard 可视化 模型</s>
 
5 模型参数的选择，以及训练的策略

6 模型保存

7 batch_szie 初代码存在bug 。小于64的不会被放进去 这个要特别注意。

8 代码中的 的字典 存在bug  要导出。


