基于 Hierarchical Attention Networks 的文本分类

模型结构：

 - embedding

 - Word Encoder: word level bi-directional GRU to get rich representation of words

 - Word Attention:word level attention to get important information in a sentence

 - Sentence Encoder: sentence level bi-directional GRU to get rich representation of sentences

 - Sentence Attetion: sentence level attention to get important sentence among sentences

 - FC+Softmax

运行方法：
1.下载数据
2.将数据解压到data目录下后
3.运行： python train.py

