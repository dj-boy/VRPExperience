主程序为vrptw.cpp。输入文件在input文件夹，里面有两个instance，详细instance以及最优结果参见下面链接。

https://www.sintef.no/projectweb/top/vrptw/solomon-benchmark/100-customers/


为了便于测试，程序经过部分修改，如果需要更换实例，更改代码53行：
```C++
ifstream fin(".\\input\\R102.txt");

```
将R102换成R01即可。

直接放到DevC++编译即可运行。

参考推文：https://mp.weixin.qq.com/s/5AC8OfGKRpRZRIRfCLURXg