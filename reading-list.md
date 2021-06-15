| [Home](index.md) | [Reading List](reading-list.md) | [Posts on Zhihu](https://www.zhihu.com/people/QinlinChen/posts) |

# Reading List

从我学计算机开始，啃了好多书，也慢慢有点心得。所以我在此整理了一些我读过的值得推荐的书（或者课程），并附上简评，作为读者的参考。

## 数学

数学是一切之基础。

- 离散数学
  - [离散数学及其应用](https://book.douban.com/subject/34866266/)
    - 计算机相关的重要数学知识打包在一起就可以称为“离散数学”了。
    - 其实这本书我没看过——因为我学的离散数学被拆开成了下面那几本书。不过考虑到读者也没必要这样学，所以我在此列一本多合一套餐。
- 图论
  - [A First Course in Graph Theory](https://book.douban.com/subject/6934545/)
    - 图论在计算机中的重要性毋庸置疑。不过看上面那本《离散数学及其应用》应该也够了。
    - 这本是我上课用的教材，姑且相信老师的品味列在这。
- 抽象代数
  - [Abstract Algebra: Theory and Applications](http://abstract.ups.edu/)
    - 抽象代数中群和格的概念在计算机中应该是最重要的。当我在之后学习分布式理论和PL相关的理论时，才深切感受到这里面概念的美丽与深刻。所以，如果读者在初读这样抽象的书时感到迷迷糊糊也不要灰心，留个印象就好了。等以后要运用这些概念的时候再来看，便能恍然感受到认知的螺旋式上升。
    - 这本是我上课用的教材，姑且相信老师的品味列在这。
    - 另外，这是一本开源的书，免费。
- 数理逻辑
  - [Logic in Computer Science: Modelling and Reasoning about Systems](https://book.douban.com/subject/1764668/)
    - 数理逻辑在计算机中的地位是绝对重要的。
    - 一般看数学书最痛苦的就是不知道这个抽象的概念是干啥用的，而这本书妙就妙在，书如其名，讲了数理逻辑在计算机建模与推理的应用（如Model Checking和程序证明）。
    - 所以，用这本书学数理逻辑比《离散数学及其应用》更好。
- 组合数学
  - [组合数学 (EtoneWiki)](http://tcs.nju.edu.cn/wiki/index.php/%E7%BB%84%E5%90%88%E6%95%B0%E5%AD%A6_(Fall_2019))
    - 组合数学对广大程序猿修炼内功的效果可能就不如前面几门数学明显了。不过也还是值得一学的。
    - 这是南京大学尹一通老师组合数学课程，制作精良的ppt和讲义值得一看。如果能再配上尹一通老师的授课，那体验就是极佳了。

## 计算机理论

计算机的基础。

- 算法
  - [算法 (by Sedgewick)](https://book.douban.com/subject/19952400/)
    - 这是一本入门级算法书。讲得通俗易懂。
    - 作者开发了红黑树，所以他在这本书里讲红黑树也是信手拈来。
  - [算法导论](https://book.douban.com/subject/20432061/)
    - 想要算法的进阶，就要学习算法正确性的证明和复杂度的分析。算法导论要教你的正是这一点。
  - [Algorithms for Hard Problems](https://book.douban.com/subject/1917565/)
    - 学习算法再推进一步，就是用算法解决所谓的“难问题”。解决难问题的方法有随机算法、近似算法、启发式算法等等。
    - 这本是我上课用的教材，姑且相信老师的品味列在这。至少知识点都覆盖全了。
    - 也可以学习南京大学尹一通老师的[高级算法](http://tcs.nju.edu.cn/wiki/index.php/%E9%AB%98%E7%BA%A7%E7%AE%97%E6%B3%95_(Fall_2020))。里面也有相关参考书。
- 计算理论
  - [Introduction to Automata Theory, Languages, and Computation](https://book.douban.com/subject/3171389/)
    - 学了计算理论后会觉得思维得到了升华。
    - 计算理论讲了三件事：计算模型是什么？在这个模型下某个“东西”能不能计算？如果能计算的话，计算复杂度是多少（到这里才是算法的地盘）？

## 体系结构

计算机体系的最底层。

- 数字电路
  - [数字设计：原理与实践](https://book.douban.com/subject/2068856/)
    - 计算机最底层要从数字电路学起。（模拟电路：那我走？）
    - 回过头来看，这本书也太厚了吧——感觉精髓概念也就那么点，剩下的都忘了也没事儿。
- 体系结构
  - [深入理解计算机系统 (CSAPP)](https://book.douban.com/subject/26912767/)
    - 经典名著了。衔接底层硬件与上层操作系统。
  - [Computer Architecture: A Quantitative Approach (CAAQA)](https://book.douban.com/subject/7006537/)
    - 又一本经典。接过CSAPP，带你更深入理解底层硬件。
  - [A Primer on Memory Consistency and Cache Coherence](https://book.douban.com/subject/6829746/)
    - 在学习并发的时候，会慢慢接触到内存的一致性模型。这本书能帮你解答很大一部分疑惑。CAAQA在这方面反而讲得很粗糙。
    - 其实内存的一致性模型真的很麻烦。后面可以看到，分布式的一致性模型还算是有形式化描述的，但内存的一致性模型早期都没有，因为那时是先有硬件实现后有模型描述，而不是先有模型描述，再有硬件实现。这导致很难用一个简洁的模型统一各种不同的硬件的实现。

## 系统

在体系结构之上构建的各种关键系统。

- 操作系统
  - [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
    - 免费好用的操作系统教材。
    - 但学习操作系统最好的方法，是自己写点代码！配合MIT 6.828食用更佳。
  - [鸟哥的linux私房菜](http://linux.vbird.org/linux_basic/)
    - 教你使用Linux系统的工具书。
    - 建议阅读方法：第一遍找自己感兴趣的细读，其它部分略读。之后有需求了再查阅、细读对应章节。
  - [Linux From Scratch](http://www.linuxfromscratch.org/)
    - 真正的Geek应该自己动手编译一个自己的Linux发布版！
    - 破除认知障。从此再也不会对各类Linux发布版感到迷惑、敬畏。
  - [Linux Kernel Development](https://book.douban.com/subject/6097773/)
    - 带你速览Linux内核实现的引导书。所以比较薄。
    - 玩多了Linux，也该看看Linux本身的奥秘了。
- 数据库
  - [Database System Concepts](https://book.douban.com/subject/10548379/)
    - 学习数据库的最好方法也是写点代码。配合[CMU 15445](https://15445.courses.cs.cmu.edu/fall2019/)食用更佳。
- 分布式系统
  - [Distributed Systems for Fun and Profit](http://book.mixu.net/distsys/index.html)
    - 薄薄的小书，带你快速一窥分布式系统面貌。
  - [Distributed Systems: An Algorithmic Approach](https://www.amazon.com/Distributed-Systems-Algorithmic-Approach-Information/dp/1466552972)
    - 分布式算法是分布式系统的内功，所以想要入门分布式，可以从算法学起。
    - 这本书我没看过，是别人推荐的。不过我看了目录，内容还是挺不错的。
  - [MIT 6.824](https://pdos.csail.mit.edu/6.824/schedule.html)
    - 学完分布式算法后，分布式系统的难点就在“系统”二字了。
    - 这门课带你看各种分布式系统的论文，并让你自己实现分布式系统！
  - [Designing Data-Intensive Applications](https://book.douban.com/subject/30329536/)
    - 联系理论和实践的书，适合在学完前面（偏理论的）东西，并有一定大数据实践经验后再看。
    - 帮你梳理分布式系统的知识框架。
  - [Principles of Eventual Consistency](https://www.microsoft.com/en-us/research/publication/principles-of-eventual-consistency/)
    - 如果前面几本书把分布式一致性讲得让你迷迷糊糊，那么一份形式化的描述应该会很有帮助。
    - 这本书提出vis-ar框架对分布式一致性模型建模。
    - [Consistency in Non-Transactional Distributed Storage Systems](https://dl.acm.org/doi/abs/10.1145/2926965)基于这篇论文的vis-ar框架，为更多一致性模型建模，非常震撼。建议搭配阅读。
- 网络
  - [计算机网络：自顶向下方法](https://book.douban.com/subject/30280001/)
    - 经典教材。
    - 我对网络懂得不多，不多说。

## 软件工程
- 并发
  - [The Art of Multiprocessor Programming](https://book.douban.com/subject/3901836/)
    - 入门并发理论的经典。我也只看了一半，但受益匪浅。
  - [Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://mirrors.edge.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)
    - 上一本偏并发理论，这一本偏并发实践。
    - 最让我受益的概念是“Ownership”。
- 重构
  - [重构：改善既有代码的设计](https://book.douban.com/subject/4262627/)
    - 也是挺有名的书了。核心就是：重构要有测试样例支持，要小步小步地来。

## 程序设计语言
- 编译原理
  - [编译原理 (龙书)](https://book.douban.com/subject/3296317/)
    - 经典教材。或许会有更现代的选择？
- 程序设计语言理论
  - [Software Foundations (Volume 2)](https://softwarefoundations.cis.upenn.edu/)
    - 讲程序语言理论的好书！要先看第一卷（列在了下面）。

## 人工智能
- 机器学习
  - [机器学习 (西瓜书)](https://book.douban.com/subject/26708119/)
    - 其实不是很推荐自学。
  - [机器学习理论导引](https://book.douban.com/subject/35074844/)
    - 看理论也就图一乐。
  - [深度学习 (花书)](https://book.douban.com/subject/27087503/)
    - 先学过深度学习再看这本书升华一下应该更好。
  - [Stanford CS224W 图机器学习](http://web.stanford.edu/class/cs224w/)
    - 入门图机器学习的好课！
- 数据挖掘
  - [数据挖掘：概念与技术](https://book.douban.com/subject/11542972/)
    - 结合实践或许更重要。
- 数据科学
  - [Scipy Lecture Notes](http://scipy-lectures.org/)
    - 既然前面说结合实践更重要，就列一下数据科学库（numpy, scipy）的入门讲义。
    - 至于机器学习库，scikit-learn、pytorch的官方文档写得足够好了，直接看就行。

## 编程实践
前面主要是教你“造车”的书。这里是教你“开车”的书。

- C
  - [C Primer Plus](https://book.douban.com/subject/26792521/)
    - 我入门C语言的书。很不错。
- C++
  - [C++ Primer](https://book.douban.com/subject/25708312/)
    - 我入门C++的书。头铁。
  - [Effective C++](https://book.douban.com/subject/5387403/)
  - [深度探索C++对象模型](https://book.douban.com/subject/10427315/)
  - [STL源码剖析](https://book.douban.com/subject/1110934/)
    - 以上三本，帮你深入理解C++的好书三件套。
- Java
  - [Thinking in Java](https://book.douban.com/subject/2130190/)
    - 学了C++看的这书学Java。真是嫌厚。
  - [深入理解java虚拟机](https://book.douban.com/subject/34907497/)
    - 深入理解Java还得看JVM。
- Python
  - [廖雪峰Python教程](https://www.liaoxuefeng.com/wiki/1016959663602400)
- HTML，CSS，JavaScript
  - [w3school](https://www.w3school.com.cn/index.html)
  - [JavaScript DOM编程艺术](https://book.douban.com/subject/6038371/)
- Coq
  - [Software Foundations Volume 1](https://softwarefoundations.cis.upenn.edu/)
- Haskell
  - [Learn You a Haskell for Great Good](http://learnyouahaskell.com/chapters)
    - 为一个语言而惊叹
- SQL
  - [SQL必知必会](https://book.douban.com/subject/35167240/)
- Unix
  - [UNIX环境高级编程](https://book.douban.com/subject/25900403/)
    - 学习UNIX环境编程的经典，除了太厚了。
  - [UNIX网络编程 第1卷](https://book.douban.com/subject/1500149/)
    - 也是经典。我都惊叹以前的我能看完那么厚的书。
- Qt
  - [C++ GUI Qt 4编程](https://book.douban.com/subject/3173123/)
    - 有人教比看官方文档舒服多了。不过不知道有没有过时了。
- Android
  - [第一行代码 Android](https://book.douban.com/subject/26915433/)
- Python后端
  - [Flask Web开发：基于Python的Web应用开发实战](https://book.douban.com/subject/26274202/)
- Java后端 (Servlet, JSP, Spring, Mybatis, etc.)
  - [how2j](https://how2j.cn/)

