
这里我们简单介绍一下数据转化是怎么工作的

#1 首先我们记录下在整个数据集中有多少个独立的数据
#2 接着对每个独立的数据进行编号(如，data1: 17)
#3 同样，我们把反对应也同样记录下来(如，17: data1)
#4 用着个对应编号来转化数据

作用:
    可以把稀疏的数据转化为稠密的数据，方便后面向量化(one-hot)处理
