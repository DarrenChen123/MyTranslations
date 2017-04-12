昨天有人问我， Swift 初学者应该先学什么。 问题是这样的：
> 我有个问题要问一下你,  花时间学习一下 TDD (测试驱动开发) , 或者利用那些时间学习 Swift 和函数式编程，哪样更值得一些?

当然，我的观点会有一些偏见，因为我写了一本[关于 Swift 中的 TDD 的书](http://swiftandpainless.com/book/)。所以，在看我的回答时，切记这一点。

##### 建议＃1：阅读苹果官方提供的 [Swift Book](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/)。
在我看来，应该先学习Swift。这是一切的基础。如果你连 Swift 中有哪些函数都不懂，何来函数式编程的概念？此外，Swift 还是编写 iOS 和 OS X 应用主要的语言。这意味着大多数时候你需要和面向对象的 API 进行交互（至少在写代码的时候需要）。所以你也需要理解面向对象的 Swift, 以便在写 Swift 时充分利用 Swift 的潜力。
就算你不相信我，Chris Eidhof，Florian Kugler和Wouter Swierstra在[《Functional Swift》](https://www.objc.io/books/functional-swift/)中也这样说过：
> “你应该能很顺利地阅读 Swift 程序，并熟悉常见的编程概念，例如类、方法和变量。如果你只是一名初学者，这本书可能不太适合你。”

##### 建议＃2：阅读大量博客文章。 有很多伟大的Swift 博客。
苹果的官方文档非常好。但是，如果你想了解社区中有创造力的想法，你需要阅读很多博客。

##### 建议＃3：学习并为你的代码编写测试。
在我看来，测试至关重要。每个开发者都需要测试他们的代码。一套好的测试用例会带来很多好处。[Michael Feathers](https://twitter.com/mfeathers) 在 [《Working Effectively with Legacy Code》](http://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code?from_search=true) 一书中这样写道：
> 对我来说，旧代码就是代码，没有测试。

对我来说，测试驱动开发从测试开始比较好，因为要测试什么是次要的。你（某种意义上说）为（几乎）一切编写测试。TDD 的一个规则是，只在测试失败时编写代码。

##### 建议＃4：学习函数式编程。
Swift 还有函数式的一面。你不需要使用它们，但是如果你正好（或者愿意）积极参与社区，你可能很快就会见到函数式的魔法。在我看来，学习函数式编程会让你成为一个更好的开发者。函数式的代码通常看起来就像魔法一样。（只要你能通过测试验证，）它就能工作。

以上是我的观点。我相信许多开发者有不同的意见。去吧，问问别人怎么看。

以及，请购买我的书。  ;)