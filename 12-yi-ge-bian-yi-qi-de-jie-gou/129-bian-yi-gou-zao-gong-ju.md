和其他软件开发者一样，写编译器的人可以充分利用现代的软件开发环境。这些华宁包含了诸如语言编辑器、调试器、版本管理程序描述、测试管理等工具。除了这些通用的软件开发工具，人们还床架拿了一些更加专业的工具来实现编译器的不同阶段：

1. 语法分析器的生成器，可以根据一个程序设计语言的语法描述自动生成语法分析器。
2. 扫描器的生成器，可以根据一个语言的语法单元的正则表达式描述生成词法分析器。
3. 代码生成器的生成器，一句一组关于如何把中间语言的每个运算翻译成目标机上的机器语言的规则，生成一个代码生成器。
4. 数据流分析引擎，可以帮助收集数据流信息，即程序中的值如何从程序的一个部分传递到另一个部分。数据流分析是代码优化的一个重要部分。
5. 编译构造工具集，提供可用于构造编译器不同阶段的例程的完整集合。



