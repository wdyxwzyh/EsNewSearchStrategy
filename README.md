# EsNewSearchStrategy
一种限制 某个词 出现次数过多对整体ES搜索结果的干扰 的 策略

es搜索对 多个词的输入 可以分配权重 进而达到 抑制 某个词出现频繁对整体排序的影响

但是由于事先不知道 哪个词出现频率过高 故这种方式需要额外的操作来选择权重（jieba关键词排序等）

或者 更改 搜索策略 先查询 两个词 and 存在的数据 如果没有结果 再查询 or(should)


