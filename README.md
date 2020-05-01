# note-taking-system

### 一个笔记系统——如何把MarginNote3, DEVONThink3, TheBrain11 和 nvALT当一个App使用 
https://www.bilibili.com/video/BV147411A7CP/

### John的阅读工作流的第一步——信息从MarginNote3流入nvALT
https://www.bilibili.com/video/BV1M7411w7bv/

### John的阅读工作流的第二步——概念的诞生
https://www.bilibili.com/video/BV1z7411F7Vf/


# 在边远处种一颗橡树——将MarginNote，nvALT，DEVONThink与TheBrain结合起来使用的原因

When you are famous it is hard to work on small problems. This is what did Shannon in. After information theory, what do you do for an encore? The great scientists often make this error. They fail to continue to plant the little acorns from which the mighty oak trees grow. They try to get the big thing right off. And that isn't the way things go.

——Richard Hamming, You and Your Research



这一套工作流程的目的在于创造知识[[create knowledge]]，特别是创造特殊知识[[create specific knowledge]]，创造[[specific knowledge]]。

这套工作流程有一个基础假设，那就是知识[[knowledge]]并不存储于某一个文档之中，像是一个宝箱中开天辟地的神剑。相反，知识本身不是一个实体，而是关联网络[[network]]。

比如说，记忆，记忆并不是存储于一个单独的神经元细胞之中的，相反，记忆存储于神经元细胞之间所形成的的网络[[network]]。

再比如说，我们的市场中所存在的问题解决方案并不是存储于一个独立的实体公司之中，相反，市场中的解决方案都是存储于广泛的供应商，生产商，消费者之间所形成的的网络[[network]]之中。比如说iphone，没有任何一家公司掌握了制造一台iphone的所有知识，苹果是集成了网络，集成了各种知识做的这个产品。



当然这是一个假设，如果这个假设成立，在设计这套流程时，我思考的就是如果可以通过机器的自动化来实现知识之间关联地迅速取得，是不是可以实现更好地创造知识[[create knowledge]]？

那么接下来的问题就是如何通过现有的app实现知识之间关联的迅速取得，首先，我们需要创造知识之间的关联，我们还要允许机器为我们创造知识之间的关联，然后我们要能够实现我们创造的或者机器创造的关联的迅速取得。



问题1-为什么我考虑的是如何通过现有app来实现，而不是设计一个新的app？

第一当然不是因为我没有那个代码能力（其实是的），而是因为从方法论[[methodology]]的角度来说，我选择相信[[create knowledge]]的解决方案不应该是设计[[design]]出来的，相反，应该是生长出来的。



if you want to make a living flower, you don’t build it physically, with tweezers, cell by cell. You grow it from the seed.

——Christopher Alexander, The Timeless Way of Building



当然也可以说是设计[[design]]的，但是是反复迭代经由设计流程[[iterative design]]设计出来的，经由了一个[[evolution]]的过程。

这个在法哲学领域讨论的非常多，原因是法律工程在人类历史上的事故和灾难太多了。比如说事实上没有人设计了民法。英美法系自不必说，大陆法系的民法起源于罗马法，但是罗马法本身是经由大量的诉讼生长起来之后，被罗马法学家归纳出来逻辑而生成了诸多模块。萨维尼讲“所有的法律⋯ ⋯ 首先通过习俗，然后通过法律科学而产生，总之是通过内在的潜移默化的力量，而不是立法者的强制而产生的。”他反对德国民法典的制定，认为法律的生成应该是一个自下而上地有机生长的过程。哈耶克在论述自生自发秩序时提到，“道德观念、宗教和法律、语言和书写、货币和市场，都被认为是由某人经由刻意思考而建构出来的：至少它们所具有的各种程度的完备形式被认为是经由某人刻意思考而设计出来的。”



Order generated without design can far outstrip plans men consciously contrive. 

——Friedrick Hayek, The Fatal Conceit



问题2-为什么要通过机器的自动化实现知识之间关联地迅速取得？



第一当然不是因为我只会一点自动化技术（其实是的），而是因为对于创造知识[[create knowledge]]而言，真正重要的是发生在信息流从外部流入你，经由你，再流出的过程中发生的事件event。



We know, then, that what matters in a building or a town is not its outward shape, its physical geometry alone, but the events that happen there.

——Christopher Alexander, The Timeless Way of Building



那么在这个信息流入流出的过程中，经常发生的是什么呢？是创建关联。那么决定一个[[create knowledge]]的工作流的特质是什么呢？是取得关联和创建关联的速度，或者可以说是取得关联和创建关联的交易成本[[transaction cost]]。这里的交易成本主要是时间和复杂的操作，那么是不是可以把时间缩短，把复杂的操作降低呢？当然，通过自动化。







A building or a town is given its character, essentially, by those events which keep on happening there most often. 

——Christopher Alexander, The Timeless Way of Building



通过自动化，我们把本来相对复杂的操作，相对漫长的取得时间变的简单而迅速，从而成为整个信息流入流出过程中经常发生的event。

这个交互的过程是首先你要告诉机器这个概念，其次就是机器自动帮你取得这个概念的上下文[[context]]。这里的自动化分为两步，第一步是自动化地取得概念，第二步是自动化地取得概念的上下文[[context]]，进而获得知识之间的关联。第一步通过nvALT的自动补全[[AutoComplete]]来完成，第二步是通过DEVONThink和TheBrain的[[AutoSuggest]]来实现。其中，nvALT的[[AutoComplete]]自不必说，DEVONThink是通过see-also功能实现[[AutoSuggest]]的，而TheBrain则是通过视觉提示该概念的上下级概念的相关概念来实现的。



问题3-为什么这样的工作流对于创造知识create knowledge的效率提高有帮助？



以下是我的理解，在城市规划方面的研究指出，与每名劳动者的效率强相关的是每名劳动者在一小时以内可以触及的工作数量的平均数。也就是说，每一个劳动者在一个小时内可以找到的工作越多，创造的关联越多，这个员工的工作效率就越高。那么一个知识集市[[concept market]]的有效能力，或者说一个知识集市[[concept market]]创造一个概念相关的想法的效率强相关的是不是也可以是在一定时间内（比如3s）该概念能关联到的概念的平均数量相关，也就是说，效率在3秒钟内非常高，3秒钟之后仍然增长，但是增长率下降，而直到2分钟，停止增长并扭头下降。如果说你在2分钟内无法获得任何关联网络的提示，念头过去了，什么都不会发生。



Prud’homme and Lee’s paper, titled “Size, Sprawl, Speed and the Efficiency of Cities,” shows that productivity per worker is closely correlated to the average number of jobs per worker that are reachable in less than 60 minutes.....Productivity increases as accessibility does due to the following: when individuals are able to optimize individual labor decisions, firms have the most productive people in jobs, and aggregate output increases. Beyond 20 minutes of travel time, worker productivity still increases, but its rate decays and practically disappears beyond 60 minutes.

——Alain Bertaud, Order without Design_How Markets Shape Cities



为什么每一个劳动者接触到的工作机会多了导致了生产效率的提高？因为当个体有不止一项工作选项的时候，个体本身能够优化自己的劳动决策的可能性会就会出现。当个体能够拥有可选择的工作选项不断增加，个体优化自己的劳动决策的可能性就会不断增长。这也意味着公司有更多的机会找到生产效率高的人，总产出就会进一步提高。

那么，在[[concept market]]，我们尝试让一个concept在极短的时间内能够接触到足够多的相关concept，如何做到呢，就是通过[[AutoSuggest]]提供更多的[[context]]，一个是devonthink的see-also功能，他自动推荐了在内容上有相似性的其他概念，一个是thebrain的layout我们能够看到父级概念的其他子级概念，我们也能够看到平级概念的相关概念，也可以看到子级概念的相关概念。因为nvalt中的[[AutoComplete]]和devonthink，thebrain中接口的存在，我们可以允许在当我们想到一个概念的时候，可以在[[concept market]]中以极低地[[transaction cost]]取得该概念的[[context]]，他可以迅速地与其他有相似性，或者有家族相关性的concept交谈。如果正在思考的我代表的是这个概念，我就可以优化一个决策——在这么丰富的context中，我要与谁构建关联，与此同时，我也代表着被[[AutoSuggest]]的概念，要站在他们的角度考虑是不是要跟这个concept构建起有意义的关联，因此对于既有的context，也能选出更有意义[[meaning]]的关联被构建起来。更多有意义的关联被构建，也就意味着更多知识被创造出来。



问题4：工作流的使用过程中的体验是什么？



三十辐共一轂，当其无，有车之用。埏埴以为器，当其无，有器之用。凿户牖以为室，当其无，有室之用。故有之以为利，无之以为用。

——老子，道德经



之前我接触到的所有知识管理都是一个仓库模型，即我把未来可能会需要的资料存到机器里，当未来我意识到我需要的时候，我可以通过搜索引擎找到这些资料。但是这里有一个问题就是我必须“意识”到我需要，如果我“意识”不到我需要这个资料，但这个资料又恰好是解决这个问题的方案，我就搜索不到，也无法解决这个问题。



我们之所以要通过 automation 来实现 AutoSuggest ，实现 AutoComplete ，本质上就是把知识生产的过程，由强调“有”，迁移至强调“无”。



这里最有趣的就是，你不知道你会遭遇什么概念，而机器 AutoSuggest 给你的所有的概念，机器也不理解是什么，就在这短暂的一刻，有趣的事情发生了，你不知道会遭遇什么，但即将遭遇，机器开始给你建议，但机器也不理解这些建议的概念，也就是说，你不知道，机器也不知道，都处在一个“空”的状态。

像一个空碗，像一个瞬间被构建起来的房间。“空无一物”的状态。

但实际上你并不是完全是空。因为此刻，你肯定在想着些什么，在思考些什么，有些想法，或者你正在阅读些什么，在某种[[context]]之中，不然你不会触发这个程序。你仿佛端着一只锅，然后这个空碗突然出现在你的面前。你仿佛背负着归家的行李，而家的房间突然在此刻出现。

这些正在存在的想法会非常自然地流入“空”之中，会在[[context]]之中发生些有趣的关联，这种流入会使得 improvise 发生，也就是说，一切都在 uncertainty 的状态下完成，因为 uncertainty ，所以你无法 predict ，因为你无法 predict ，因此你才会感到[[Surprise]]，你才能遇到 coincidence，而其中的meaningful coincidence ，即 synchronicity 导致了我们所说的心流 flow。



我们来看这个工作流的结构，他分为一个基础层[[base layer]]，一个保留层[[retention layer]]。

[[base layer]]解决的问题在于如何让学习者不停下来，也就是要产生instant dopamine loop，为什么学习者不会停下来，因为[[dopamine]]在[[Surprise]]的反复出现下不断地分泌，[[Surprise]]为什么会不断出现，因为在“空无一物”的状态下，学习者所遭遇到的机器的提示都是学习者当下的意识里不存在的概念，都是超出学习意料之外的概念，都是[[coincidence]]。[[retention layer]]解决的问题是如何让学习者知道自己在自己选择的道路上在不断取得进展，也就是[[completion]]，这能让学习者感受到[[internal sense of achievement]]。

这两者的[[motivation]]分别是[[Surprise]]和[[completion]]，并形成了[[motivation chain]]。







The more living patterns there are in a thing-a room, a building, or a town--the more it comes to life as an entirety, the more it glows, the more it has this self-maintaining fire, which is the quality without a name.

——Christopher Alexander, The Timeless Way of Building



[[base layer]]与[[retention layer]]形成了一个[[core loop]]，这个[[core loop]]能够[[self-maintaining]]。也就是说它形成这样一个循环，学习者在[[base layer]]中基于[[retention layer]]中托付给机器去[[AutoSuggest]]的越多，他就越能发现更多的[[Surprise]]，从而让他愿意去创造更多的概念并托付给机器到[[retention layer]]，而被创造出来的更多的概念又会回过头来因为[[AutoSuggest]]创造更多地[[Surprise]]。这就形成了一个[[self-maintaining]]的状态。



And finally the quality without a name appears, not when an isolated pattern lives, but when an entire system of patterns, interdependent at many levels, is all stable and alive. 

——Christopher Alexander, The Timeless Way of Building







————————

后记：

这篇文章是我很长时间以来一直思索和尝试寻找解决方案的一个阶段性总结，这里要感谢很多人，首先就是封面上的人物，艺术家刘勃麟，我第一个老板，他不断地告诉我好的艺术家就是扎根在自己的土壤里，寻找自己真正愿意去表达的问题，也因此有机会接触到当代艺术家隋建国，张大力，沈少民，黄锐。还有文因互联的鲍捷博士，感谢鲍老师的诸多帮助和提点，我清晰地记得在望京第一次见面的时候聊到Tim Berners-Lee和Social Machine那本书，在602大家一起吃午饭的时候他说知识是关联。感谢文因互联，我在那里得到了很多帮助和启发。还有MarginNote的开发者Min大哥，第一次见面是在嘉里中心一风堂拉面，聊到了David P. Ausubel的Assimilation Theory，后来每次去找他聊天几乎都是他请客，我跟他交流了很多作为用户的想法（其实我主要是在那吹牛，他很nice不好意思戳穿）。还有在国关读书时候的老师许可，他是我的日语老师，是清华的法学博士，受他的影响我去读法律，去考清华法学院（当然没考上），因此对民法和法哲学产生了兴趣，有缘知道了法哲学领域的哈耶克，卢曼和他的笔记箱系统，有机会接触到冯象等法哲学家。还有北师大系统科学学院的吴金闪、韩战刚，王大辉老师的讲座，因此有缘知道了概念图，对复杂系统产生了浓厚的兴趣。

我想恰恰是因为北京这座巨大的城市，让我能在这里遇到了一流的当代艺术家，科学家，软件工程师，法学家，出版人，创业者，他们每一个人对我来说都是surprise，都是coincidence，都是我从未曾想到会遇到的，是这座城市里可以触及的无数网络提示着我他们的存在，才触发了这篇文章里的诸多思考。



最后在说一点，为什么我之前的知识管理系统都是仓库模式，我想这里的关键可能不在于技术Technology，而是文化culture，是看不见的东西，正如刘勃麟隐形在其中的这面墙，我们生活在很多日用而不自知的文化之中，我是说pedagogy，现有的一切秩序都是围绕着将学习者定位为信息的接受者，而不是创造者，学习者是不被尊重的，被视为是懒惰而没有目标的，需要接受训练的，是应该被操纵和控制的。学习者应该把自己解放出来，他们不应该允许自己被视作各种解决方案的存储器，不应该允许自己被视作一个被数据训练的神经网络。学习者应该是值得尊重的，创造新的可能性的人。他们不压迫其他人，而是解放其他人。

https://mp.weixin.qq.com/s?__biz=MzI4MTA2MDg5Mw==&mid=2651271080&idx=1&sn=30448f0bd565230d9f03512ee615de0d&chksm=f05d7cdac72af5cc089b1215a59696c326aac52bc0d463f70e990184f7d132536c9b51e33e60&token=1834921829&lang=zh_CN#rd
