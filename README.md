# Self_Attention
基于Keras的self-attention复现

其输入：上一层的输出张量。

输出：一个三维张量，维度为（samples，maxlen，attention）,第一个维度含义代表句子数目，maxlen维度代表每一个句子长度，attention维度代表每个句子中每个分词构成的attention编码值个数。

运行截图如下（1000条情感分类数据应用下）：

![图1 code](https://github.com/yanhan19940405/Self_Attention/blob/master/image/11.png)

![图2 code](https://github.com/yanhan19940405/Self_Attention/blob/master/image/12.png)
