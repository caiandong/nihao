# kuaipai
之前有提到，采用qvertor作为输入数据的容器会有越界错误。这个错误在于在比较过程中没有加上left<上界，right>下界 检验。不知道为什么使用vertor却没有报错。。使用三中值分割的副作用免去了边界的检验。

[windows下可运行](https://github.com/caiandong/mycpp_code/releases)
