# ESE5023_Assignments_12631515


Comments on HW2 from Yali （98/100）

1.1 ["Deaths"]分组不对，应考虑按["Total Deaths"]分组 （-1p)


1.3: "Ms", "Mw", "Mag", "Mb", "Ml", "Mfa" 几类都表示震级；
Ms在巨震时饱和，所以应该使用 Mw/Mag。同时你没有考虑震级缺失该如何处理
采用Ms震级漏掉了Japan最大地震应该是 2011 本州（Mw 9.1）（-2p）

2. 数据质控合理，趋势分析十分清晰。（+1p)

3.3 这里`BASIN` 的取值里有`NA` （North Atlantic），你设置`dropna=False`, 非常好。（+1p)
3.5 添加了实际地图，非常好！（+1p)

4 你没有说明数据来源，筛选条件，原始字段说明。同时数据在考虑了污染事件（许多极大值）再计算线性变化趋势没有意义。（-2p）