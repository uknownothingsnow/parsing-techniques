# 5.11 总结

正则语法的特点是没有嵌套。从一个语法规则或网络转换切换到另一个是无内存变化的。因此生成过程是有语法的单个位置决定，而识别过程由语法中的有限位置决定。

正则语法对应于正则表达式，反之亦然，尽管转换算法往往会带来意想之外的复杂结果。

在一个正则集合中字符串可以被识别为自底向上，通过“子集算法”产生的有限状态机，或者被识别为自顶向下，通过正则表达式产生的递归进程。第一个的优点在于非常高效；第二个的优点在于允许轻松添加语义操作和识别限制。

从数据挖掘的目录和网络检索到病毒扫描，有限状态自动机在各种文本搜索中都非常重要。