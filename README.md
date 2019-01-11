# ThoughtWorks（西安）面试经历

老实说根本没还没有面试就被Pass了，事情经历是这样：电话交谈以后HR发了我三个需要用代码解决的问题，让我选择其中一个问题，编写解决方案并提交。由于时间刚好是周末，所以我使用了两天的周末时间编写了第三个问题的解决方案（就是本仓库中所示代码）。提交代码之后到了第四个工作日，我主动向HR确认并得到的反馈是没有通过，接着我向HR询问审查员认为我的代码没有通过的主要原因有哪些，得到了以下回复。
```
文件结构不太好；
方法 变量 命名不好,
可读性差。
```

我写这篇文章到底是要干嘛？主要是抒发一下自己的心情和对TW这个公司的简短评价。在看到如此回复之后我的心情就像吃了屎一样，我本人内心一直是拒绝任何形式的面试作业的，因为很容易不被认真对待而竹篮打水一场空（两天时间可以读完一本书了兄弟），我方先付出沉没成本总是风险很大的行为。  

那么到底是什么问题呢？第三个问题的解决方案，简单来说就是我实现了一个非常简单的能处理类似自然语言的解释型脚本语言，接受任意输入并输出对应结果。你可以查阅<kbd>./PROBLEM</kbd>了解第三个问题的陈述，<kbd>./js</kbd>目录是包含了第三个问题解决方案的完整实现。如果你觉得自己懒的看问题陈述和分析我的代码，也可以，我提供了一个文件<kbd>./js/guide.test.js</kbd>来通篇简短的解释问题和我的解决方案，我推荐你阅读这个。待你阅读完后也可以对这件事做出一个公允的评价。  

最后我想写一些结论，对于TW公司使用一些冠冕堂皇的理由拒绝我，我只感觉很可笑。这可能是审查官没有认真对待我的作业，也有可能是TW公司的技术天花板就在那。也许某天linus去TW面试并当面把linux重写了一边，估计也会被如此的理由拒绝。我想各位看官现在已对TW公司有所了解，我想说的是，如果你打算求职TW，但凡你对技术还有点热爱，就可以用不考虑这家公司了。如果你还死命要去求职，我只能建议你不要犯我同样犯的错误，不要在你的代码中炫技，压根不要考虑什么宏实现、模板元实现、函数式的实现，你应该怎么做？你就认认真真用最原始最纯正的面向对象，一个一个类建出来，要非常注意（其实我也不知道怎么叫非常注意，可能就是把名字往长了写的意思吧）变量方法命名和类结构。而且重要的是，不要把你的代码搞的太复杂，如果你像我一样写了一个类似的东西，审查官可能因为不懂编译原理而根本看不懂你在干什么，就会找些理由给你打回来。 

还有一些泛泛而谈的内容，简单写几个，详细的就不展开了，以后有机会再写吧。
* 比如用内部的琢磨不定、变幻莫测、没有标准paper的（假）共识命名方法来要求你一个外部的还没入职的人员在写代码的时候要有同样的命名规则。
* 命名如何成为团队政治斗争的工具等。
* 公司是否应对有潜力的应聘者或雇员持有包容、开放、多元化的态度，尽量发挥其闪光点，包容其缺点？
* 公司里没有拥有足够能力的雇员去鉴别更高级能力的雇员怎么办，你的公司如何能招到更强的人？

另外感谢我的推荐人帮我推荐这次机会，他建议我半年以后再次面试TW，说过的可能性很大，我内心的想法是：不存在的。  

## 道德风险

我的推荐人电话打到我这说，他被HR找麻烦，叫我帮忙下线这个仓库，最终沟通结果是我只下线了面试题中的原问题。不久之后HR又打电话过来说我的仓库中不能包含任何ThoughtWorks字眼，并且以法务的形势对我进行了一种威胁，随便来，怕你？还有就是我们也说了一些关于纯技术上的交流事项，我的建议是TW内部技术人员可以直接在这里提Issues讨论，然后我被告知我不下线整个仓库他们是不会讨论的，话说不公开讨论个鬼？   

关于我泄露面试题的道德风险说明：TW公司HR在发于我邮件面试题的链接地址中确实有说明需要公平的对待其他面试者，不能让其他面试者提前搜到相关信息。但我需要强调，我并没有与TW公司签署任何有关面试题不能泄露的保密协议，也并不是先同意保密后才接收的题目，但我依然选择在电话联系后，下线原题目，目前仓库中已经没有任何有关从ThoughtWorks取得的信息了，如果有我愿意跟随和移除。原代码是我花了两天时间认真书写的，我拥有完全的产权，更别说公开了，而且何况我这是个错误的答案。