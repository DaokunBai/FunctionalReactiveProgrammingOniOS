# 总结

在过去的章节中，我们使用RXCollections后不需要额外的可变变量就可以在列表上进行操作，虽然RXCollections可能隐式地生成了这样的可变变量来完成任务，但是这不是我们要关心的，因为它已经为我们抽象出了这样的方式，通过:mapping\filtering和folding这种方式让我们不必在意实现任务的步骤。(当然，这并不是说，我们不应该熟悉RXCollections的源码，只是告诉你不必按部就班地去完成任务了)

&nbsp;&nbsp;在最后的章节中，我们也看到了，使用链式操作一次可以输出一个更为复杂的逻辑操作的结果。下一章我们将谈论更多的有关链式操作的内容———实际上，它是ReactiveCocoa中的重要语法之一。

&nbsp;&nbsp;下一章，我们将要讨论更多的有关映射、过滤及折叠相关的内容。我们不仅仅局限于将高阶函数运用在列表的操作上，我们也将用她们来操作流(译者注:一切皆文件，文件以流的形式传播，也就是说一切的操作都可以使用高阶函数)，还会介绍其他的高阶函数。
