语义制导定义（syntax-directed definition）把每个文法符号和一个属性集合相关联。并且把每个产生式和一组语义规则（semanticrule）相关联，这些规则用于计算与该产生式中符号相关联的属性值。

属性可以按照下面的方式求值。对于一个给定的输入串x，构建x的一个语法分析树。然后按照下面的方法应用语义规则来计算语法分析树中各个节点的属性。

如果某个属性在语法分析树节点N上的值是由N的子节点以及N本山的属性值确定的，那么这个属性就称为综合属性（synthesized attribute）。

