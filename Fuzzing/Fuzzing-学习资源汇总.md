**本文主要是收集和整理与fuzzing相关的资料，包括学习资料，论文、工具等，旨在能更方便的学习fuzzing，为后续做相关研究做铺垫。**

# **fuzzing书籍**

> [《模糊测试-强制性安全漏洞发掘》](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119)作者： Michael Sutton, Adam Greene, Pedram Amini。
>
> [《软件安全测试Fuzzing和质量保证](https://www.amazon.com/Fuzzing-Software-Security-Assurance-Information/dp/1596932147)[》](https://www.amazon.com/Fuzzing-Software-Security-Assurance-Information/dp/1596932147)作者：Ari Takanen, Charles Miller, and Jared D Demott。
>
> [《开源Fuzzing工具》](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950)作者： Gadi Evron and Noam Rathaus。
>
> [《Python灰帽子》](https://www.amazon.com/Gray-Hat-Python-Programming-Engineers/dp/1593271921)作者：Justin Seitz。

**注意：**以下书籍中的相关章节专注于Fuzzing。

> [《Shellcoder手册：发现和利用安全漏洞》（第15章节）](https://www.amazon.com/Shellcoders-Handbook-Discovering-Exploiting-Security/dp/047008023X)作者：Chris Anley, Dave Aitel, David Litchfield等。
>
> [《iOS黑客手册 – 第1章》](https://www.amazon.com/iOS-Hackers-Handbook-Charlie-Miller/dp/1118204123)作者：Charles Miller, Dino DaiZovi, Dion Blazakis, Ralf-Philip Weinmann, Stefan Esser。
>
> [《IDA Pro – IDA Pro Book：全球最受欢迎的反编译器非官方指南》](https://www.amazon.com/IDA-Pro-Book-2nd-ebook/dp/B005EI84TM)

# fuzzing 学习视频

> [纽约大学Poly（查看更多视频）](https://vimeo.com/5236104) – 由Dan Guido免费提供。
>
> [Samclass.info（检查项目部分和第17章）](https://samsclass.info/127/127_F15.shtml) – 由Sam提供。
>
> [现代二进制开发（RPISEC） – 第15章](https://github.com/RPISEC/MBE) – 由RPISEC提供。
>
> [攻击性计算机安全 – 第6周](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) – 由W. Owen Redwood和Xiuwen Liu教授提供。
> [Fuzzing – Coursera软件安全课程](https://www.coursera.org/learn/software-security/lecture/VgyOn/fuzzing) – 由马里兰大学提供
>
> [Youtube上各种有关fuzzing的探讨](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD)[和演示文稿播放列表](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD) – 这些视频中有很多不错的内容
>
> [浏览器bug狩猎 – 最后一个人的回忆录](https://vimeo.com/109380793) – Atte Kettunen
>
> [DerbyCon 2016：Fuzzing基础知识……或如何破解软件](http://www.securitytube.net/video/16939)

# 教程和博客

文章和博客解释了fuzzing的方法，技术和最佳实践。

> [有效的文件格式Fuzzing](http://j00ru.vexillium.org/slides/2016/blackhat.pdf) – Mateusz“j00ru”Jurczyk @Black Hat 2016欧洲，伦敦
>
> [过去一年的Windows内核字体fuzzing第一部分成果 ](https://googleprojectzero.blogspot.in/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html)- 谷歌的Project Zero的一篇惊人的文章，描述了如何进行fuzzing和创建fuzzers。
>
> [过去一年的Windows内核字体fuzzing第二部分技术 ](https://googleprojectzero.blogspot.in/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html)- 谷歌的Project Zero的一篇惊人的文章，描述了fuzzing和创建fuzzers需要什么。
>
> [fuzzing项目中有趣的bug和资源](https://blog.fuzzing-project.org/) – 来自fuzzing-project.org。
>
> [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) – @BrandonPrry。
>
> [用AFL和libFuzzer轻松介绍C++代码fuzzing ](http://jefftrull.github.io/c++/clang/llvm/fuzzing/sanitizer/2015/11/27/fuzzing-with-sanitizers.html)- Jeff Trull。
>
> [15分钟fuzzing介绍 ](https://www.mwrinfosecurity.com/our-thinking/15-minute-guide-to-fuzzing/)- MWR安全。
>
> [我是如何走进黑客世界的？-MyselfExplorer博客](https://1337explorer.blogspot.com/2019/03/learn-to-hacker-for-hour.html)、[中文版介绍](<https://www.freebuf.com/articles/neopoints/190895.html>)
>
> [Fuzzing Papers](https://fuzzing.info/papers/) - fuzzing.info(14年以前的一些论文)

> [Fuzzing中出现崩溃的根本原因分析](https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - Corelan团队。[Root cause analysis of integer flow](https://www.corelan.be/index.php/2013/07/02/root-cause-analysis-integer-overflows/) -Corelan团队。
>
> [Creating custom peach fuzzer publishers](http://blog.opensecurityresearch.com/2014/01/creating-custom-peach-fuzzer-publishers.html) - Open Security Research。
>
> [在](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/)[Fuzzing](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/)[大型开源项目之前需要考虑的七件事](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/) – Emily Ratliff。
>
> [Bright Hub](<https://www.brighthub.com/>)
>
> [INFOSEC](<https://resources.infosecinstitute.com/>)
>
> [gynvael.coldwind](<https://gynvael.coldwind.pl/>)
>
> 

---

# Fuzzer工具

1. 采用到的技术与时间的表格（待整理）

有助于fuzzing应用的工具

## Cloud Fuzzers

在云环境中帮助fuzzing测试的Fuzzers。

### REST-ler-2019

> 云服务最近探索了亚马逊网络服务和Microsoft Azure。如今，大多数云服务都是通过REST API访问的，而Swagger是REST API最流行的语言界面。 Swagger规范描述了如何通过其REST API访问云服务（例如，服务可以处理的请求以及可能期望的响应）。
> 本文介绍了REST-I，这是第一个智能自动REST API安全测试工具。 REST-ler分析Swagger和REST API。每个测试都被定义为一系列请求和响应。 REST-ler将军通过以下方式进行智能测试：（1）推断Swagger规范中声明的请求类型之间的依赖关系（例如，推断出“请求”）由返回）和由（2），以产生新的测试，从观察到的在现有测试执行响应判断动态反馈（例如，当得知“请求℃后-一个请求序列，B是由服务拒绝”，因此避免这种组合在未来）。我们表明这两种技术对于大规模的服务是必要的。我们还讨论了REST-I的应用，以测试GitLab，一种流行的开源自托管Git服务，以及发现的新bug。
>
> **相关资料:** 
>
> 1. [论文:《REST-ler: Automatic Intelligent REST API Fuzzing》(ICSE’19)](<https://www.microsoft.com/en-us/research/uploads/prod/2018/04/restler.pdf>)
> 2. [源代码](<https://github.com/Luracast/Restler>)

### Cloudfuzzer-2017

> 云fuzzing框架，可以轻松在云环境中运行自动化模糊测试。
>
> **相关资料:** 
>
> 1. [源代码](https://github.com/ouspg/cloudfuzzer)
> 2. [视频](<https://vimeo.com/80960932>)

---

## **文件系统 Fuzzers**

可帮助fuzzing文件格式的Fuzzers，如PDF，MP3，SWF等

### REDQUEEN-2019

> 在本文中，我们介绍了一种轻量级但非常有效的污点跟踪和符号执行替代方案，以促进和优化最先进的反馈模糊测试，可轻松扩展到大型二进制应用程序和未知环境。我们观察到，在执行给定程序期间，部分输入通常在程序状态中直接（即几乎未修改）结束。可以利用这种输入到状态的对应来创建稳健的方法，以高效且有效的方式克服常见的模糊障碍。
> 我们的原型实现称为REDQUEEN，能够自动为给定的二进制可执行文件解决魔术字节和（嵌套）校验和测试。此外，我们展示了我们的技术在不同特权级别（内核空间和用户空间）上的各种目标上优于各种最先进的工具，而没有特定于平台的代码。 REDQUEEN是第一种在所有目标中找到LAVA-M中100％以上的漏洞的方法。此外，我们能够在多个程序和操作系统内核驱动程序中发现65个新错误并获得16个CVE。最后，我们的评估表明REDQUEEN快速，广泛适用，并且优于并发方法高达三个数量级。
>
> 论文中提到源码公开，但github链接失效，论文作者github链接为：https://github.com/RUB-SysSec
>
> **相关资料:** 
>
> 1. [论文《REDQUEEN: Fuzzing with Input-to-State Correspondence》-NDSS19](https://www.ei.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)

### ProFuzzer-2019

> 摘要 - 现有的基于突变的模糊器倾向于随机改变程序的输入，而不理解其底层语法和语义。在本文中，我们提出了一种新颖的即时探测技术（称为ProFuzzer），它可以自动恢复和理解在模糊测试过程中对漏洞发现至关重要的输入字段，并智能地调整变异策略以增加达到零日目标的机会。由于这种探测是透明地搭载到常规模糊测试，因此不需要输入规范的先验知识。在模糊测试期间，首先突变单个字节，并自动分析它们的模糊测试结果以链接那些相关的字节并识别连接它们的字段的类型;这些字节按照特定于类型的策略进一步突变，这些策略基本上修剪了搜索空间。
> 我们通常在所有应用程序中定义探测器类型，从而使我们的技术应用程序不可知。我们在标准基准测试和实际应用方面的实验表明，ProFuzzer大大优于AFL及其优化版本AFLFast，以及其他最先进的模糊器，包括VUzzer，Driller和QSYM。
>
> **未找到相应源码**
>
> **相关资料:** 
>
> 1. [论文《ProFuzzer: On-the-fly Input Type Probing for Better Zero-day Vulnerability Discovery》-SP19](<https://www.cs.purdue.edu/homes/ma229/papers/SP19.pdf>)



### UnTracer-AFL-2019

>
>为了消除由覆盖引导的模糊器进行的不必要的跟踪，我们引入了覆盖引导跟踪的概念。覆盖范围的跟踪利用了两个观察结果：（1）只有一小部分生成的测试用例增加了覆盖范围，因此需要跟踪; （2）随着时间的推移，增加覆盖率的测试用例变得越来越少。覆盖引导跟踪对目标二进制中的当前覆盖边界进行编码，以便在测试用例产生新覆盖时自动报告 - 无需跟踪。这可以作为跟踪的过滤器;将跟踪费用限制为仅覆盖范围增加的测试用例。因此，覆盖引导的跟踪交易增加了处理覆盖范围的时间 - 增加了测试用例，以减少处理非覆盖增加测试用例的时间。
>为了展示覆盖引导跟踪的潜力，我们创建了一个基于静态二进制工具器Dyninst的实现，称为UnTracer。我们使用模糊测试社区常用的八个真实世界二进制文件来评估UnTracer。实验表明，经过一个小时的模糊测试，UnTracer的平均开销低于1％，经过24小时的模糊测试，UnTracer接近0％的开销，同时用流行的白盒和黑盒二元示踪器追踪每个测试用例AFL- Clang，AFLQEMU和AFL-Dyninst分别产生36％，612％和518％的管理费用。我们进一步将UnTracer与最先进的混合模糊器QSYM相结合，并表明在24小时的模糊测试中，QSYM-UnTracer分别比QSYM-Clang和QSYM-QEMU多执行79％和616％的测试用例。
>
>1. [论文:《Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing》(arxiv’19)](<https://arxiv.org/pdf/1812.11875.pdf>)
>2. [源码地址](<https://github.com/FoRTE-Research/UnTracer-AFL>)

### Superion-2019

> 近年来，基于覆盖的greybox模糊测试已被证明是在实践中发现安全漏洞的最有效技术之一。特别是，美国模糊Lop（简称AFL）被认为在模糊相对简单的测试输入方面取得了巨大成功。不幸的是，当它遇到XML和JavaScript等结构化测试输入时，AFL中的那些语法盲区修剪和变异策略会影响效率和效率。为此，我们提出了一种基于语法感知覆盖的灰盒模糊方法，用于处理结构化输入的模糊程序。鉴于测试输入的语法（通常是公开可用的），我们引入了语法感知修剪策略，使用解析的测试输入的抽象语法树（AST）修剪树级别的测试输入。此外，我们引入了两种语法感知突变策略（即，增强的基于字典的突变和基于树的突变）。具体而言，基于树的变异通过使用解析的测试输入的AST替换子树来工作。我们的方法具有语法意识，可以进行宽度和深度的模糊探索。我们实施了我们的方法作为AFL的扩展，名为Superion;并评估了Superion对现实生活中的大型程序（XML引擎libplist和三个JavaScript引擎WebKit，Jerryscript和ChakraCore）的有效性。我们的结果表明，Superion可以改善代码覆盖率（即线路和功能覆盖率分别为16.7％和8.8％）和漏洞发现能力（即30个新漏洞，其中我们发现21个新漏洞，分配了16个CVE，3.2通过AFL和jsfunfuzz获得K USD bug赏金奖励。
>
> 1. [论文:《Superion: Grammar-Aware Greybox Fuzzing》(ICSE’19)](<https://arxiv.org/pdf/1812.01197.pdf>)
> 2. [源码地址](<https://github.com/zhunki/Superion>)

### SLF-2019

> 在本文中，我们提出了一种新颖的模糊测量技术，它具有生成有效种子输入的能力。它背负AFL以识别输入有效性检查以及对此类检查有影响的输入字段。它根据它们与输入的关系进一步对这些检查进行分类。这些类包括算术关系，对象偏移，数据结构长度等。开发了一种多目标搜索算法来应用类特定的突变，以便一起完成相互依赖的检查。我们对从其他模糊测试项目和Google模糊测试套件中收集的20个流行基准程序评估我们的技术，并将其与现有的模糊AFL和AFLFast，符号执行引擎KLEE和S2E以及将模糊测试与符号执行相结合的混合工具Driller进行比较。结果表明，我们的技术非常有效和高效，优于其他工具。
>
> 1. [论文:《SLF: Fuzzing without Valid Seed Inputs》(ICSE’19)](<https://www.cs.purdue.edu/homes/ma229/papers/ICSE19.pdf>)

### Eclipser-2019

> 我们提出了灰盒子的concolic测试，这是一种新颖的基于路径的测试用例生成方法，它结合了白盒和灰盒模糊测试的优点。从很高的层面来说，我们的技术系统地探索了被测程序的执行路径，如白盒模糊测试，也就是精简测试，同时不放弃灰盒模糊测试的简单性：它只使用轻量级仪器，而不是依靠SMT求解器。我们在一个名为Eclipser的系统中实现了我们的技术，并将其与最先进的灰盒模糊器（包括AFLFast，LAF-intel，Steelix和VUzzer）以及符号执行器（KLEE）进行了比较。在我们的实验中，我们实现了更高的代码覆盖率，并发现了比其他工具更多的错误。
>
> 1. [论文:《Grey-box Concolic Testing on Binary Code》(ICSE’19)](<https://2019.icse-conferences.org/event/icse-2019-technical-papers-grey-box-concolic-testing-on-binary-code>)
> 2. [源代码](<https://github.com/SoftSec-KAIST/Eclipser>)



### Hawkeye-2018

> 灰盒模糊测试是一种测试真实世界节目的实用方法。然而，大多数现有的灰盒模糊器缺乏定向性，即在程序中向用户指定的目标站点执行的能力。为了强调定向模糊测试中存在的挑战，我们建议Hawkeye具有定向灰盒模糊器的四种所需特性。由于对被测程序和目标站点进行了新颖的静态分析，Hawkeye精确地收集了诸如调用图，函数和到目标的基本块级距离等信息。在模糊测试期间，Hawkeye根据静态信息和执行跟踪评估运行的种子，以生成动态度量，然后将其用于种子优先级排序，功率调度和自适应变异。这些策略有助于Hawkeye实现更好的指导性并吸引目标站点。我们将Hawkeye实现为模糊测试框架，并在不同场景下对各种实际程序进行评估。实验结果表明，Hawkeye可以到达目标位置，并且比AFL和AFLGo等最先进的灰盒模糊器更快地重现崩溃。特别是，Hawkeye可以将某些漏洞的暴露时间从大约3.5小时减少到0.5小时。到目前为止，Hawkeye已经在Oniguruma，MJS等项目中发现了超过41起以前未知的崩溃事件，目标站点由漏洞预测工具提供;所有这些崩溃都得到确认，其中15个已被分配了CVE ID。
>
> **未找到相应源码**
>
> **相关资料:** 
>
> 1. [论文《Hawkeye: Towards a Desired Directed Grey-box Fuzzer》-CCS’18](<https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf>)
> 2. [视频](<https://www.youtube.com/watch?v=BSPj7GAQt5U>)

### CollAFL-2018

> 在本文中，我们提出了一种覆盖敏感的模糊解决方案CollAFL。它通过提供更准确的覆盖信息来缓解路径冲突，同时仍然保留较低的仪器开销。它还利用覆盖信息应用三种新的模糊测试策略，提高了发现新路径和漏洞的速度。我们基于流行的模糊AFL实现了CollAFL的原型，并在24种流行的应用程序上进行了评估。结果表明，路径碰撞是常见的，即在一些应用中高达75％的边缘可能与其他边缘碰撞，并且CollAFL可以将边缘碰撞比降低到接近零。此外，凭借三种模糊测试策略，CollAFL在代码覆盖率和漏洞发现方面均优于AFL。
>
> **未找到相应源码**
>
> **相关资料:** 
>
> 1. [论文《CollAFL: Path Sensitive Fuzzing》-SP’18](<http://chao.100871.net/papers/oakland18.pdf>)

### PerfFuzz-2018

> 当程序被提供具有病理行为的输入时，软件中的性能问题可能意外地出现。但是我们怎样才能首先找到这些输入？PerfFuzz可以自动生成这样的输入：给定一个程序和至少一个种子输入，PerfFuzz自动生成输入，在没有任何领域知识的情况下，跨程序位置运行病理行为。PerfFuzz使用多维性能反馈，独立地最大化所有程序位置的执行计数。这使PerfFuzz能够找到各种输入，在程序中运行不同的热点。
>
> **相关资料：**
>
> 1. [论文(ISSTA’18)](<http://www.carolemieux.com/perffuzz-issta2018.pdf>)
> 2. [源码地址](<https://github.com/carolemieux/perffuzz>)

### T-Fuzz-2018

> 我们的新方法从不同的角度处理覆盖：通过删除目标程序中的健全性检查。 T-Fuzz利用覆盖引导模糊器生成输入。每当模糊器不再能够触发新的代码路径时，基于轻量级动态跟踪的技术会检测输入检查模糊生成的输入是否失败。然后从目标程序中删除这些检查。然后继续对变换后的程序进行模糊测试，允许触发被删除的检查保护的代码并发现潜在的错误。
> 模糊转换程序发现错误带来两个挑战：（1）删除检查会导致过度逼近和误报，（2）即使对于真正的错误，转换程序上的崩溃输入也可能不会触发原始程序中的错误。作为辅助后处理步骤，T-Fuzz利用基于符号执行的方法来过滤掉误报并在原始程序中重现真正的错误。
> 通过转换程序以及改变输入，TFuzz可以覆盖更多代码并找到比任何现有技术更多的真正错误。我们在DARPA Cyber Grand Challenge数据集，LAVA-M数据集和4个真实世界程序（pngfix，tiffinfo，magick和pdftohtml）上评估了T-Fuzz。对于CGC数据集，T-Fuzz发现166个二进制文件中的错误，121个中的Driller和105中的AFL。此外，在之前的模糊程序和库中发现了3个新错误。
>
> **相关资料：**
>
> 1. [论文:《T-Fuzz: fuzzing by program transformation》(SP’18)](<https://nebelwelt.net/publications/files/18Oakland.pdf>)
> 2. [PPT](<https://pdfs.semanticscholar.org/4210/68894abd37faf44c16983949f90043ad0a84.pdf>)
> 3. [视频](<https://www.youtube.com/watch?v=wjvjST0FLhg>)
> 4. [源码地址](<https://github.com/HexHive/T-Fuzz>)

### FairFuzz-2018

> AFL扩展，通过定位稀有分支来增加代码覆盖率。FairFuzz在具有高度嵌套结构的程序（数据包分析器，xmllint，使用laf-inte编译的程序等）上具有特殊优势。
>
> **相关资料：**
>
> 1. [论文ASE ’18](<http://www.carolemieux.com/fairfuzz-ase18.pdf>)
> 2. [源码地址](<https://github.com/Ljiee/fairfuzz>)

### Angora-2018

> 我们提出了一种新的基于突变的模糊器Angora，它的性能远远超过了最先进的模糊器。Angora的主要目标是通过解决路径约束来增加分支覆盖率而无需符号执行。**为了有效地解决路径约束，我们引入了几个关键技术：可扩展的字节级污点跟踪，上下文敏感的分支计数，基于梯度下降的搜索和输入长度探索**。在LAVA-M数据集上，Angora发现了几乎所有注入的错误，发现了比我们比较的任何其他模糊器更多的错误，并且发现错误是程序中第二好的模糊器的8倍。Angora还发现了LAVA作者注射但却无法触发的103个错误。我们还在八个流行的，成熟的开源程序上测试了Angora。
>
> 1. [论文:《Angora: Efficient Fuzzing by Principled Search》(SP’18)](<<http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf>)
> 2. [源码地址](<https://github.com/AngoraFuzzer/Angora>)

### QSYM-2018

> 我们设计了一个快速的concoic执行引擎，称为QSYM，以支持混合模糊测试。关键思想是使用动态二进制转换将符号仿真与本机执行紧密集成，从而可以实现更细粒度，更快速的指令级符号仿真。此外，QSYM放松了传统concolic执行器的严格健全性要求以获得更好的性能，同时利用更快速的模糊器进行验证，为性能优化提供了前所未有的机会，例如，乐观地解决约束并修剪不感兴趣的基本块。
>
> 1. [论文:《QSYM: A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing》(CCS’18)](<https://www.usenix.org/node/217566>)
> 2. [源码地址](<https://github.com/sslab-gatech/qsym>)

### Grammarinator-2018

> 基于ANTLR v4语法的文件格式模糊测试工具（ANTLR项目中已有多种语法可用）。在本文中，我们介绍了Grammarinator，一种通用的测试生成器工具，它能够利用现有的解析器语法作为模型。由于该模型既可以作为解析器也可以作为生成器，该工具可以提供基于生成和基于突变的模糊器的功能。所提供的工具主动用于测试各种JavaScript引擎，并发现了100多个独特的问题。
>
> **相关资料：**
>
> 1. [论文《Grammarinator: a grammar-based open source fuzzer》-A-TEST ’18](<https://dl.acm.org/citation.cfm?id=3278193>)
> 2. [源代码](https://github.com/renatahodovan/grammarinator)

### Vuzzer-2017

> 该工具提出了一种应用程序感知的进化模糊测试策略，它不需要任何有关应用程序或输入格式的先验知识。为了最大化覆盖范围并探索更深入的路径，该工具利用基于静态和动态分析的控制和数据流特征来推断应用程序的基本属性。与应用程序无关的方法相比，这可以更快地生成有趣的输入。我们在VUzzer中实现我们的模糊测试策略并在三个不同的数据集上进行评估：DARPA Grand Challenge二进制文件（CGC），一组实际应用程序（二进制输入解析器）和最近发布的LAVA数据集。
>
> **相关资料：**
>
> 1. [论文NDSS ’17](<http://www.cs.vu.nl//~giuffrida/papers/vuzzer-ndss-2017.pdf>)
> 2. [源码地址](https://github.com/vusec/vuzzer)
> 3. [工具所用污点分析数据存储结构：EWAHBoolArray](https：//github.com/lemire/EWAHBoolArray)
> 4. [APLPIN](https://github.com/mothran/aflpin)
> 5. [DECREE](https://github.com/CyberGrandChallenge/cgc-releasedocumentation/blob/master/walk-throughs/pin-for-decree.md)
> 6. [AFLFAST](https://github.com/mboehme/aflfast)

### QuickFuzz-2017

> QuickFuzz是一个用Haskell编写的工具，用于测试第三方软件上常见文件格式的意外输入，利用现成的，众所周知的模糊器。与其他世代模糊器不同，QuickFuzz不需要为相关文件格式编写规范，因为它依赖于Haskell代码库中可用的现有文件格式处理库。QuickFuzz是开源的（GPL3），它可以使用其他错误检测工具，如[zzuf](http://caca.zoy.org/wiki/zzuf)，[radamsa](https://github.com/aoh/radamsa)，[honggfuzz](http://google.github.io/honggfuzz/)和[valgrind](http://valgrind.org/)。
>
> **相关资料：**
>
> 1. [主页介绍](http://quickfuzz.cifasis-conicet.gov.ar/) 
> 2. [论文:《QuickFuzz testing for fun and profit》](https://dl.acm.org/citation.cfm?id=3163968)
> 3. [另外一篇相同名称论文：《QuickFuzz: An Automatic Random
>    Fuzzer for Common File Formats》](https://people.seas.harvard.edu/~pbuiras/publications/QFHaskell2016.pdf)
> 4. [源码地址](https://github.com/CIFASIS/QuickFuzz)

### AFLGo-2017

> 在本文中，我们介绍了定向灰盒模糊测试（DGF），它生成输入，目的是有效地到达给定的一组目标程序位置。我们开发并评估基于模拟退火的功率计划，该计划逐渐为更接近目标位置的种子分配更多能量，同时减少远离种子的能量。我们实现AFLGo的实验表明，DGF优于基于定向符号执行的白盒模糊测试和无向灰盒模糊测试。我们展示了DGF在补丁测试和崩溃复制方面的应用，并讨论了AFLGo与Google持续模糊测试平台OSS-Fuzz的集成。由于其定向性，AFLGo可以在LibXML2等几个模糊的安全关键项目中发现39个漏洞。分配了17个CVE。
>
> **相关资料：**
>
> 1.[论文:《Directed Greybox Fuzzing》-CCS’17](<https://acmccs.github.io/papers/p2329-bohmeAemb.pdf>)
>
> 2.[源代码](<https://github.com/aflgo/aflgo>)

### Skyfire-2017

> 该论文提出了一种数据驱动的种子生成方法，叫做Skyfire。Skyfire通过从大量的已知样本中学习而生成覆盖良好的种子作为Fuzzing的输入对处理高度结构化输入的程序进行测试。Skyfire接收输入样本集合和文法，通过自动化学习PCSG（Probabilistic context-sensitive grammar，一种带概率的上下文有关文法，包含语义规则和语法特征），并利用其生成种子文件。
>
> 本文利用收集的样本和Skyfire生成的种子作为AFL的seed对开源的XSLT、XML等引擎进行测试，证明skyfire生成的种子文件分布（提高了20%行覆 盖率和15的函数覆盖率）和发现漏洞能力。同时也对闭源的IE11的JavaScript引擎测试。其发现了19个新的内存破坏型bug（其中16个新的漏洞）和32个拒绝服务bug。
>
> **相关资料：**
>
> 1. [论文:《Skyfire: Data-Driven Seed Generation for Fuzzing》-SP’17](<https://www.ieee-security.org/TC/SP2017/papers/42.pdf>)
>
> 2. [论文中文讲解](<https://www.inforsec.org/wp/?p=2678>)
>
> 3. [源代码](<https://github.com/zhunki/skyfire>)

### Hodor-2016

> 它可以配置为使用已知良好的输入和分隔符来fuzz特定的位置。在一个完全愚蠢的模糊器和一些更聪明的东西之间，与实现一个合适的智能模糊器相比，它的努力要少得多。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/nccgroup/Hodor)

###  Win AFL-2016

>  Linux下的智能模糊测试神器afl-fuzz的Windows版本
>
>  **相关资料：**
>
>  1.[源代码](https://github.com/ivanfratric/winafl)

### AFLFast-2016

> 基于抽象覆盖的Greybox模糊测试（CGF）是一种随机测试方法，无需程序分析。通过稍微改变种子输入生成新测试。如果测试运行一条新的有趣的路径，它将被添加到种子集中;否则，它被丢弃。我们观察到大多数测试都使用相同的“高频”路径，并制定策略，通过倾向于低频路径，以相同数量的测试探索更多路径。我们使用马尔可夫链模型解释了CGF的挑战和机遇，马尔可夫链模型指定了运动路径 i 的种子的模糊化生成运行路径 j 的输入的概率。每个状态（即种子）具有指定从该种子生成的输入的数量的能量。我们表明，如果能量与静态分布的密度成反比并且每次选择种子时单调增加，则CGF的效率要高得多。能量由功率计划控制。我们通过扩展AFL实施了几个时间表。在24小时内，AFLFast暴露了3个未被AFL曝光的未报告的CVE，并且暴露了6个先前未报告的CVE，比AFL快7倍。 AFLFast比AFL产生至少一个数量级的独特崩溃。我们将AFLFast与符号执行者Klee进行了比较。在漏洞检测方面，AFLFast在原始Klee论文中讨论的相同主题程序上比Klee显着更有效。在代码覆盖方面，仅限AFLFast
>
> **相关资料：**
>
> 1. [论文：《Coverage-based Greybox Fuzzing as Markov Chain》-CCS’16](<https://mboehme.github.io/paper/TSE18.pdf>)
>
> 2. [源代码](<https://github.com/mboehme/aflfast>)

###  Shellphish Fuzzer-2016

> AFL的Python接口，允许注入测试用例和其他功能。
>
> **相关资料：**
>
> 1.[源代码](https://github.com/shellphish/fuzzer)

### sanitizers-2016（google）

> Google项目，包括AddressSanitizer(检测可寻地址问题), MemorySanitizer(检测未初始化内存的使用), ThreadSanitizer（检测数据争用和死锁问题）, LeakSanitizer（检测内存泄露问题）。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/Google/sanitizers)

### Hodor Fuzzer-2016

> 另一种通用型fuzzer。它可以配置为使用已知良好的输入和分隔符来模糊特定的位置。如果我们对文件/协议/ etc规范有所了解，可以使用它来轻松做一些更智能的模糊测试。
>
> NCC group开源项目
>
> **相关资料：**
>
> 1. [源代码](https://github.com/nccgroup/hodor)

### Driller-2016

> 我们提出了一个混合漏洞挖掘工具Driller，它以互补的方式利用模糊和选择性的执行，以发现更深层次的错误。廉价的模糊测试用于锻炼应用程序的隔间，而花哨的执行用于生成满足分隔隔间的复杂检查的输入。通过结合这两种技术的优势，我们减轻了它们的弱点，避免了复杂分析中固有的路径爆炸和模糊测试的不完整性。 Driller使用选择性的concolic执行来仅探索模糊器所认为有趣的路径，并为模糊器无法满足的条件生成输入。我们评估了Driller在DARPA网络大挑战赛资格赛中发布的126个应用程序，并通过识别相同数量的漏洞同时显示其效力，同时作为排位赛事的得分最高的球队。
>
> **相关资料：**
>
> 1. [论文：《Driller: Augmenting Fuzzing Through Selective Symbolic Execution》-NDSS’16](<https://www.cs.ucsb.edu/~vigna/publications/2016_NDSS_Driller.pdf>)
> 2. [源代码](<https://github.com/shellphish/driller>)

### MoWF-2016

>在本文中，我们建议利用有关现有有效文件的文件格式和数据块的信息，以便在解析器代码之外快速进行探索。我们将我们的方法称为基于模型的白盒模糊测试（MoWF），因为黑盒模糊器的文件格式输入模型可以被利用作为对大量输入空间的约束，以在符号执行中的路径探索期间排除大多数无效输入。我们评估了8个具有6种不同文件格式的大型程序二进制文件中的13个漏洞，发现MoWF暴露了所有漏洞，而传统的whitebox模糊测试和基于模型的blackbox模糊测试分别只暴露了不到一半。我们的实验还表明，MoWF在没有任何种子输入的情况下暴露了70％的漏洞。
>
>**相关资料：**
>
>1. [论文：《Model-Based Whitebox Fuzzing for Program Binaries》-AES’16](<https://www.comp.nus.edu.sg/~abhik/pdf/ASE16.pdf>)

###  MozPeach-2015

> 由Mozilla Security提供的peach 2.7。
>
> **相关资料：**
>
> 1.[源代码](https://github.com/MozillaSecurity/peach)

### AFL-2015

> Afl-fuzz是一种基于面向安全的模糊测试工具，它采用了一种新型的方式（编译时检测和遗传算法），来自动发掘干净的、有趣的测试案例，即在目标二进制中触发新的内部状态。这基本上改善了模糊代码的功能覆盖。该工具生成的简洁的合成语料库也可以用来传播其它更多的劳动型或资源密集型测试方案。与其他仪器化的模糊工具相比，afl-fuzz是以实用性而被设计的：它具有适度的性能开销，采用了多种高效的模糊战略，和努力最小化的技巧，基本上不需要配置，并且能够无缝处理复杂的、真实世界案例，以及常见的图像分析或文件压缩等。
>
> **相关教程：**
>
> 1. [源代码](http://lcamtuf.coredump.cx/afl/)
> 2. [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) – @BrandonPrry。
> 3. [使用afl的persistent模式给capstone做模糊测试](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html) – @toasted_flakes。
> 4. [RAM磁盘以及从AFL Fuzzing中保存你的SSD](http://cipherdyne.org/blog/2014/12/ram-disks-and-saving-your-ssd-from-afl-fuzzing.html)
> 5. [使用American Fuzzy Lop狩猎Bug](https://josephg.com/blog/bug-hunting-with-american-fuzzy-lop/)
> 6. [American Fuzzy Lop在真实案例中的高级使用](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)
> 7. [使用afl-fuzz隔离Python](https://tomforb.es/segfaulting-python-with-afl-fuzz)
> 8. [Fuzzing Perl： American Fuzzy Lops的故事](http://www.geeknik.net/71nvhf1fp)
> 9. [使用AFL-Fuzz Fuzzing，一个练习示例（AFL vs Binutils）](https://www.evilsocket.net/2015/04/30/fuzzing-with-afl-fuzz-a-practical-example-afl-vs-binutils/)
> 10. [Fuzzing的重要性？](https://mgba.io/2016/09/13/fuzzing-emulators/)
> 11. [Heartbleed是如何被找到的](https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html)
> 12. [使用American Fuzzy lop Fuzzing文件系统](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)
> 13. [使用AFL Fuzzing Perl/XS模块](https://medium.com/@dgryski/fuzzing-perl-xs-modules-with-afl-4bfc2335dd90)
> 14. [AFL研讨会Fuzzing – 真正的漏洞带来的一系列挑战](https://github.com/ThalesIgnite/afl-training)
> 15. [AFL内部实现细节小记](http://rk700.github.io/2017/12/28/afl-internals/)
> 16. [afl-fuzz技术白皮书](https://blog.csdn.net/gengzhikui1992/article/details/50844857)
> 17. [如何使用AFL进行一次完整的fuzz过程](https://blog.csdn.net/abcdyzhang/article/details/53487683)
> 18. [AFL(American Fuzzy Lop)实现细节与文件变异](https://paper.seebug.org/496/)
> 19. [fuzz实战之libfuzzer](https://www.secpulse.com/archives/71898.html)

###  honggfuzz-2015(google)

> 一个易于使用的fuzzer以及有趣的分析选项。支持基于代码覆盖的feedback-driven fuzzing。同时支持GNU/Linux，FreeBSD，Mac OSX和Android系统。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/google/honggfuzz)
> 2. [riusksk分析](https://bbs.pediy.com/thread-247954.htm)

### SymFuzz-2015

> 提出了一个算法的设计，以最大化数量的bug为黑盒子突变性的模糊给定一个程序和种子的输入。主要的直观性的是利用给定程序 - 种子对的执行轨迹上的白盒符号进行分析，来检测输入的BIT位置之间的依赖性，然后使用这种依赖关系来为该程序种子对计算概率上最佳的突变比率。
>
> **相关资料：**
>
> 1. [论文：《Program-Adaptive Mutational Fuzzing》-SP’15](https://ieeexplore.ieee.org/document/7163057?arnumber=7163057) 
> 2. [源代码](https://github.com/maurer/symfuzz)

### Choronzon-2015

> Choronzon是一个进化型的模糊工具。它试图模仿进化过程，以保持产生更好的结果。 为了实现这一点，它具有评估系统的能力，用以分类哪些模糊文件是有趣的，哪些应该被丢弃。
> 此外，Choronzon是一个基于知识的模糊器。 它使用用户定义的信息来读取和写入目标文件格式的文件。要熟悉Choronzon的术语，您应该考虑每个文件由染色体表示。用户应该描述所考虑的文件格式的基本结构， 优选文件格式的高级概述，而不是描述它的每个细节和方面。那些用户定义的基本结构中的每一个都被认为是基因， 每个染色体包含一个基因树，并且它能够从中构建相应的文件。
>
> **相关资料：**
>
> 1. [演讲视频](https://www.youtube.com/watch?v=WafsYOCl8hQ) 
> 2. [演讲PPT](https://census-labs.com/media/choronzon-zeronights-2015.pdf)
> 3. [源代码](https://github.com/CENSUS/choronzon)

### ansvif-2015

> 用于查找C/C++代码中的漏洞的高级跨平台模糊测试框架。
>
>  **相关资料：**
>
> 1. [源代码](https://oxagast.github.io/ansvif/)

### binspector-2014

> 该语言允许个人创建二进制格式的形式化描述。这些描述被称为BFFTs。从那里可以针对BFFT测试任何给定的二进制文件，以便：
>
> - 验证二进制文件是否满足二进制格式的要求
>   - 例如，“my_photo.jpg是一个结构良好的jpeg吗？”
> - 分析二进制文件的内容并解释其中的原始数据
>   - 例如，“my_photo.jpg中包含哪些Exif元数据，以及在哪里？”
> - 使用适当的上下文和解释检查文件中的特定二进制值
>   - 例如，“my_photo.jpg中Exif标签37377的价值是多少？”
> - 智能地在文件导入代码中可能存在的潜在“弱点”模糊二进制文件，并自动生成包含这些攻击向量的文件。
>   - 例如，“我需要损坏的示例文件来强化我的Exif导入代码。”
>
> **相关资料：**
>
> 1. [源代码](https://github.com/binspector/binspector)

### CERT Basic Fuzzing Framework (BFF) For Linux-2014

> CERT Basic Fuzzing Framework（BFF）是一种软件测试工具，可以在Linux，Mac OS X和Windows上运行的应用程序中发现缺陷。BFF对消耗文件输入的软件执行突变模糊测试。它们会自动收集导致软件以独特方式崩溃的测试用例，以及调试与崩溃相关的信息。BFF的目标是最大限度地减少软件供应商和安全研究人员有效发现和分析通过模糊测试发现的安全漏洞所需的工作量。基于zzuf框架实现
>
> **相关资料：**
>
> 1. [源代码](https://github.com/CERTCC/certfuzz)

### CERT Failure Observation Engine (FOE)For windows-2014

> The cert Failure Observation Engine (FOE) 是一个软件测试工具，它被用于在Windows平台上运行的应用程序中发现漏洞。FOE在消耗文件输入的软件上执行突变模糊测试。（突变性模糊测试是采取形式良好的输入数据并以各种方式破坏它的行为，寻找导致崩溃的情况。）FOE自动收集导致了软件以独特方式使测试用例崩溃，以及利用崩溃来调试信息。FOE的目标是最大限度地减少软件供应商和安全研究人员有效发现和分析通过模糊测试发现的安全漏洞所需的工作量。
>
> **相关资料：**
>
> 1. [源代码](https://vuls.cert.org/confluence/display/tools/Home)
> 2. [使用FOE Fuzzing](https://samsclass.info/127/proj/p16-fuzz.htm) – Samclass.info

### Pathgrind-2013

> Pathgrind使用基于路径的动态符号执行分析来fuzz linux / unix二进制。 它是基于valgrind被写在python内的。
>
> **相关资料：**
>
> 1. [相关PPT](https://pdfs.semanticscholar.org/e48e/fb9187655ab1393f497f9330e8340b09e643.pdf) 
> 2. [源代码](<https://github.com/jrmuizel/kemufuzzer>)

### rmadair-2012

> 基于文件突变的fuzz测试工具，使用PyDBG来监测感兴趣的信号。
>
> **相关资料：**
>
> 1.[源代码](<https://github.com/rmadair/fuzzer>)

### radamsa-2012

> 它通常用于测试程序如何能够承受格式错误和潜在的恶意输入。它的工作原理是读取有效数据的样本文件，并从中生成有意义的不同输出。radamsa的主要卖点是它已经在程序中找到了大量的错误，这些错误实际上很重要，它易于编写脚本，并且易于启动和运行。
>
> **相关资料：**
>
> 1. [源代码](https://gitlab.com/akihe/radamsa)
> 2. [相应PPT](http://www.cs.tut.fi/tapahtumat/testaus12/kalvot/Wieser_20120606radamsa-coverage.pdf)

### KEMUfuzzer-2010

> 虚拟机提供了分区物理系统资源和创建隔离执行环境的能力。虚拟机的开发是一项非常具有挑战性的任务。对于系统虚拟机来说尤其如此，因为它们运行操作系统并且必须在每个细节上复制它所需的极其复杂的环境。如今，系统虚拟机是许多关键架构的关键组成部分。但是，只有很少的努力来测试它们提供的环境是否在语义上等同于真实机器上的环境。在本文中，我们提出了一种特定于测试系统虚拟机的方法。该方法基于协议特定的模糊测试和差分分析，并且包括强制虚拟机和相应的物理机器执行用户和系统模式代码的特制片段以及比较它们的行为。我们开发了一个代号为的原型**KEmuFuzzer**，它实现了我们的英特尔x86架构方法，并用它来测试四个最先进的虚拟机：BOCHS，QEMU，VirtualBox和VMware。我们发现了所有这些缺陷。
>
> **相关资料：**
>
> 1. [论文：《Testing system virtual machines》-ISSTA’10](<https://dl.acm.org/citation.cfm?id=1831730>)
> 2. [相关PPT](https://pdfs.semanticscholar.org/e48e/fb9187655ab1393f497f9330e8340b09e643.pdf) 
> 3. [源代码](<https://github.com/jrmuizel/kemufuzzer>)

###  zzuf-2007

> zzuf是一个透明的应用程序输入模糊器。其目的是通过破坏用户提供的数据来查找应用程序中的错误（这些数据通常来自Internet上不受信任的来源）。它的工作原理是拦截文件和网络操作，并改变程序输入中的随机位。zzuf的行为是确定性的，可以更容易地重现错误。其主要使用领域是：
>
> - **质量保证**：使用zzuf测试现有软件，或将其集成到您自己软件的测试套件中
> - **安全性**：通常，分段错误或内存损坏问题意味着潜在的安全漏洞，zzuf有助于暴露其中一些漏洞
> - **代码覆盖率分析**：使用zzuf最大化代码覆盖率
>
> zzuf的主要目标是媒体播放器，图像浏览器和Web浏览器，因为它们处理的数据本质上是不安全的，但它也成功地用于查找系统实用程序（如objdump）中的错误。
>
> **相关资料：**
>
> 1. [使用手册](http://caca.zoy.org/wiki/zzuf)
> 2. [源代码](https://github.com/samhocevar/zzuf)

### Peach Fuzzer-2004

> 一款智能模糊测试工具, 广泛用于发现软件中的漏洞和缺陷,它有两种主要模式,基于生长的模糊测试和基于变异的模糊测试。
>
> **相关资料：**
>
> 1. [源代码](https://sourceforge.net/projects/peachfuzz/)
> 2. [开始使用Peach](http://community.peachfuzzer.com/v2/PeachQuickstart.html)
> 3. [Peach Fuzzing第一部分](http://www.flinkd.org/fuzzing-with-peach-part-1/) – corelan团队Jason Kratzer
> 4. [Peach Fuzzing第二部分 ](http://www.flinkd.org/fuzzing-with-peach-part-2-fixups-2/)- corelan团队Jason Kratzer
> 5. [自动生成Peach pit文件/fuzzers ](http://doc.netzob.org/en/latest/tutorials/peach.html)- FrédéricGuihéry，Georges Bossert
> 6. **peach使用介绍：**[1、peach语法介绍](<https://www.kanxue.com/chm.htm?id=12592&pid=node1001008>)、[2、peach语法实战](<https://www.kanxue.com/chm.htm?id=12593&pid=node1001008>)、[3、Peach 实战之 gif 文件格式](<https://www.kanxue.com/chm.htm?id=12594&pid=node1001008>)、[4、Peach Pit 模版调试技巧](<https://www.kanxue.com/chm.htm?id=12595&pid=node1001008>)

---

## **机器学习 Fuzzers**

### V-Fuzz-2019

> 在本文中，我们设计并实现了一个名为V-Fuzz的面向漏洞的进化模糊测试原型，旨在在有限的时间内高效，快速地发现错误。V-Fuzz由两个主要组件组成：基于神经网络的漏洞预测模型和面向漏洞的进化模糊器。给定V-Fuzz的二进制程序，漏洞预测模型将初步估计软件的哪些部分更容易受到攻击。然后，模糊器利用进化算法生成输入，这些输入往往会在漏洞预测结果的指导下到达易受攻击的位置。
>
> **未找到源码**
>
> **相关资料:** 
>
> 1. [论文《V-Fuzz: Vulnerability-Oriented Evolutionary Fuzzing》-SP’18](<https://arxiv.org/pdf/1901.01142.pdf>)

### NEUZZ-2019

> 摘要 - 模糊测试已经成为发现软件漏洞的事实标准技术。然而，即使是最先进的模糊器也不能很有效地找到难以触发的软件错误。最流行的模糊器使用进化指导来生成可以触发不同错误的输入。这种进化算法虽然快速且易于实现，但常常陷入无效的序列或随机突变中。
> 梯度引导优化是进化指导的有前途的替代方案。梯度引导技术已经被证明通过有效利用基础函数的梯度或高阶导数来解决机器学习等领域中的高维结构优化问题，从而显着优于进化算法。
> 然而，梯度引导方法不能直接应用于模糊测试，因为真实世界的程序行为包含许多不连续性，平台和脊，其中基于梯度的方法经常被卡住。我们观察到这个问题可以通过创建一个近似目标程序离散分支行为的平滑代理函数来解决。
> 在本文中，我们提出了一种新的程序平滑技术，使用替代神经网络模型，可以逐步学习平滑近似或复杂的，真实的程序分支行为。我们进一步证明，这种神经网络模型可以与梯度引导输入生成方案一起使用，以显着提高模糊测试过程的效率。
> 我们的广泛评估表明，NEUZZ在发现新漏洞和实现更高边缘覆盖率方面，在10个流行的真实世界节目中明显优于10个最先进的灰盒模糊器。 NEUZZ发现31个先前未知的错误（包括两个CVE），其他模糊测试器在10个真实世界的程序中找不到，并且比24小时运行的所有测试的灰盒模糊器实现了3倍的边缘覆盖。此外，NEUZZ在LAVA-M和DARPA CGC bug数据集上也优于现有的模糊器。
>
> 1. [论文:《NEUZZ: Efficient Fuzzing with Neural Program Smoothing》(SP’19)](<https://arxiv.org/pdf/1807.05620.pdf>)
> 2. [源码地址](<https://github.com/Dongdongshe/neuzz>)

### DeepHunter-2018

> 随着过去十年数据爆炸，基于深度神经网络（DNN）的软件经历了前所未有的飞跃，并且正在成为许多新型工业应用的关键驱动力，包括许多安全关键场景，如自动驾驶。尽管在各种人类智能任务中取得了巨大成功，但与传统软件类似，DNN也可能表现出由隐藏缺陷导致严重事故和损失的错误行为。在本文中，我们提出了DeepHunter，一种用于捕获通用DNN潜在缺陷的自动化模糊测试框架。 DeepHunter执行变形突变以生成新的语义保留测试，并利用多个可插入覆盖标准作为反馈，从不同角度指导测试生成。为了可扩展到实用大小的DNN，DeepHunter批量维护多个测试，并根据主动反馈确定测试选择的优先级。 DeepHunter的有效性在3个流行的数据集（MNIST，CIFAR-10，ImageNet）和7个具有不同复杂性的DNN上进行了广泛的研究，在大量的6个覆盖标准下作为反馈。大规模实验表明，DeepHunter可以（1）在指导下显着提高覆盖率; （2）生成有用的测试以检测错误行为并促进DNN模型质量评估; （3）在平台迁移的DNN量化过程中准确捕获潜在缺陷。
>
> 1. [论文:《DeepHunter: Hunting Deep Neural Network Defects via
>    Coverage-Guided Fuzzing》(arXiv’18)](<https://arxiv.org/pdf/1809.01266.pdf>)
> 2. [源码地址](<https://github.com/sslab-gatech/qsym>)

### Tensorfuzz-2018

>众所周知，机器学习模型难以解释和调试。神经网络尤其如此。在这项工作中，我们引入了神经网络的自动化软件测试技术，这些技术非常适合发现仅针对稀有输入发生的错误。具体来说，我们开发了用于神经网络的覆盖引导模糊（CGF）方法。在CGF中，神经网络输入的随机突变由覆盖度量指导，以达到满足用户指定约束的目标。我们描述了近似最近邻算法如何快速提供此覆盖度量。然后，我们讨论了CGF在以下目标中的应用：在训练好的神经网络中发现数值误差，在神经网络和这些网络的量化版本之间产生分歧，并在角色级语言模型中表现出不良行为。
>最后，我们发布了一个名为TensorFuzz的开源库，它实现了所描述的技术。
>
>**相关资料:** 
>
>1. [论文《TensorFuzz: Debugging Neural Networks with Coverage-Guided Fuzzing](<https://arxiv.org/pdf/1807.10875.pdf>)
>2. [源码地址](<https://github.com/brain-research/tensorfuzz>)

### RamFuzz-2017

> RamFuzz是单元测试中各个方法参数的模糊器。单元测试可以使用RamFuzz为被测方法生成随机参数值。记录这些值，并且可以重播日志以重复完全相同的测试方案。但随机参数值不仅限于基本类型：RamFuzz还可以从用户代码中自动生成任何类的随机对象。这允许用户模糊接受类参数的方法。例如，如果一个方法采用a `int`，a `struct S`和a `class C`作为参数，RamFuzz可以随机生成它们！测试作者不必担心创建`S`和`C`对象的技术性; RamFuzz会自动完成。
>
> 为此，RamFuzz包含一个代码生成器，它读取C ++源代码并从中生成一些测试代码。此测试代码通过随机选择的构造函数创建类实例，然后继续使用随机生成的参数调用实例方法的随机序列。结果是一个随机类对象，可以将该类作为参数提供给任何方法。
>
> 当然，这会产生表面上非常有用的表面测试 - 大多数方法不会采用完全随机的参数，而是以某种方式约束它们。目的是可以从许多RamFuzz测试运行的日志中自动推断出这些约束。由于测试是随机的，因此每次运行都是一种不同的方案，可以增加测试代码的覆盖范围。如果随机性质良好，则长时间反复运行测试将涵盖各种可能的参数值，可能包括一些完全有效的测试。然后可以使用这些日志来训练AI以识别哪些参数值有效。或者，可以使用模糊测试策略来引导参数值生成向有效测试的演变。
>
> RamFuzz提供了一些Python工具，可以轻松地在其生成的日志上训练AI - 请参阅[`ai`](https://github.com/dekimir/RamFuzz/blob/master/ai)目录和[概述文件](https://github.com/dekimir/RamFuzz/blob/master/sci/ramfuzz.md)。例如，可以训练神经网络以基于其RamFuzz日志准确地预测测试运行的结果。这是可能的，因为RamFuzz设法提供足够多的测试运行，以便识别成功和不成功的内容。
>
> 但请注意，RamFuzz不会自动生成方法调用结果的测试断言。将创建其他项目以自动完成，但RamFuzz将通过方便地处理参数模糊测试和日志记录来实现。
>
> RamFuzz是在Apache 2.0许可下提供的。它目前仅支持输入C ++（请参阅下面的“已知限制”），它需要C ++ 11支持来编译其输出代码和运行时
>
> **相关资料:** 
>
> 1. [论文：《RamFuzz: A Framework for C++ Test Generation via Deep Learning》](https://github.com/dekimir/RamFuzz/blob/master/sci/ramfuzz.md#ramfuzz-a-framework-for-c-test-generation-via-deep-learning) 
> 2. [源码地址](https://github.com/dekimir/RamFuzz)

### Neural Fuzzer-2016

> Neural-Fuzzer是一款实验性模糊器，旨在使用最先进的机器学习来学习一组初始文件。它分两个阶段进行：**培训**和**生成**。
>
> - 在训练模式中：它使用[长短期记忆（LSTM）](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)来学习字节序列的结构。
> - 在生成模式下：它将自动生成损坏或意外的文件，它将尝试使给定的程序崩溃。
>
> Neural-Fuzzer是开源的（GPL3），由[keras](http://keras.io/)驱动，类似于[rnn-char](https://github.com/karpathy/char-rnn)和序列预测中的其他技术。
>
> **相关资料:** 
>
> 1. [源码地址](https://github.com/CIFASIS/neural-fuzzer)

### Pulsar-2015-协议

> Pulsar是一种具有自动协议学习和仿真功能的网络模糊器。该工具允许通过机器学习技术建模协议，例如聚类和隐马尔可夫模型。这些模型可用于模拟Pulsar与真实客户端或服务器之间的通信，这要归功于语义正确的消息，这些消息与一系列模糊测试原语相结合，允许在其协议状态的更深层状态下测试未知协议的实现是否存在错误机。
>
> **相关资料：**
>
> 1. [论文：《PULSAR: Stateful Black-Box Fuzzing of
>    Proprietary Network Protocols》](https://ieeexplore.ieee.org/document/7163057?arnumber=7163057) 
> 2. [源码地址](https://github.com/hgascon/pulsar)

------

## **Kernel Fuzzers**

### JANUS-2019

> 文件系统是操作系统的基本构建块，它太大而且太复杂而且没有bug。然而，文件系统依赖于常规的压力测试工具和正式的检查程序来查找错误，这些错误由于文件系统和操作系统的复杂性不断增加而受到限制。因此，模糊测试，被证明是一种有效和实用的方法，成为一种更好的选择，因为它不需要太多关于目标的知识。但是，模糊文件系统存在三个主要挑战：改变整体性能下降的大图像blob，生成依赖于图像的文件操作，以及再现发现的错误，这对于现有的OS模糊器来说是困难的。因此，我们提出JANUS，这是第一个反馈驱动的模糊器，它探索文件系统的二维输入空间，即在大图像上改变元数据，同时发出图像导向的文件操作。此外，JANUS依靠库操作系统而不是传统的虚拟机进行模糊测试，这使得JANUS能够加载操作系统的新副本，从而提高错误的可重复性。我们在八个文件系统上评估JANUS，在上游Linux内核中发现了90个错误，其中62个已被确认。修复了43个错误，分配了32个CVE。此外，与模糊文件系统的最先进的模糊化器Syzkaller相比，JANUS在模糊12小时后在所有文件系统上实现了更高的代码覆盖率。 JANUS分别在Btrfs和ext4中访问了4.19倍和2.01倍的代码路径。此外，JANUS能够重现88-100％的崩溃，而Syzkaller失败了所有这些。
>
> **相关资料：**
>
> 1. [论文：《Fuzzing File Systems via Two-Dimensional Input Space Exploration》](<https://www.computer.org/csdl/proceedings-article/sp/2019/666000a577/17D45WXIkA8>) 

### RAZZER-2019

> 摘要 - 内核中的数据竞争是一类重要的错误，严重影响了相关系统的可靠性和安全性。由于竞争，内核可能会变得没有响应。更糟糕的是，攻击者可能会启动权限提升攻击以获取root权限。
> 在本文中，我们提出了RAZZER，一种在内核中查找竞争错误的工具。 RAZZER的核心是引导模糊测试，以确保内核中潜在的数据竞争点。 RAZZER采用两种技术有效地发现种族：静态分析和确定性线程交织技术。使用静态分析，RAZZER识别过度近似的潜在数据竞争点，引导模糊器更有效地在内核中搜索数据竞争。使用在管理程序上实现的确定性线程交织技术，RAZZER驯服内核的非确定性行为，以便它可以确定性地触发竞争。我们使用RAZZER实现了RAZZER的原型并运行了最新的Linux内核（从v4.16-rc3到v4.18rc3）。结果，RAZZER在内核中发现了30个新的比赛，其中16个随后得到确认，并在报告后由内核开发人员进行相应修补。
>
> **相关资料：**
>
> 1. [论文：《RAZZER: Finding Kernel Race Bugs through Fuzzing》-SP’19](<https://lifeasageek.github.io/papers/jeong-razzer.pdf>) 

### PeriScope-2019

> 摘要 - 操作系统内核是远程攻击者的一个有吸引力的目标。如果受到攻击，内核会为攻击者提供完整的系统访问权限，包括安装rootkit，提取敏感信息和执行其他恶意操作的能力，同时避开检测。内核的大多数攻击面都位于系统调用边界。正在进行的内核保护工作主要集中于确保这一边界;为此目的已经开发了几种有能力的分析和模糊测试框架。
> 但是，正如最近的一些漏洞所证明的那样，还有其他不涉及系统调用的内核泄露路径。例如，通过破坏外围设备（如Wi-Fi芯片组）的固件并随后将来自Wi-Fi芯片组的恶意输入发送到Wi-Fi驱动程序，攻击者可以在不调用单个内核的情况下获得对内核的控制权系统调用。遗憾的是，目前还没有实用的探测和模糊测试框架可以帮助开发人员找到并修复沿硬件操作系统边界发生的此类漏洞。
> 我们介绍了PERISCOPE，这是一个基于Linux内核的探测框架，可以对设备驱动程序交互进行细粒度分析。 PERISCOPE挂钩内核的页面错误处理机制，可以被动地监视和记录设备驱动程序及其相应硬件之间的流量，或者使用模糊组件PERIFUZZ即时改变数据流，从而模拟主动的对抗攻击。 PERIFUZZ准确地模拟攻击者对外围设备的能力，揭露不同类别的错误，包括但不限于内存损坏错误和双重错误。为了证明外围设备带来的风险以及我们框架的价值，我们在两个流行的芯片组供应商的Wi-Fi驱动程序上评估了PERIFUZZ，在那里我们发现了15个独特的漏洞，其中9个以前是未知的。
>
> **相关资料：**
>
> 1. [论文：《PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary》-NDSS’19](<https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf>) 
> 2. [已发现CVE分析](<https://github.com/securesystemslab/periscope>)

### syzkaller-2017(google)

> syzkaller是一个无监督的覆盖引导内核模糊器。目前还在持续更新，readme上列出了其它相关的文档资料。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/google/syzkaller)
> 2. [基于syzkaller的研究工作](https://github.com/google/syzkaller/blob/master/docs/research.md)
> 3. 来自HardenedLinux项目：
>    - [使用syzkaller和qemu的内核质量保证](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syzkaller_general.md)（关于如何使用qemu设置syzkaller的教程）
>    - [Syzkaller崩溃DEMO](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syzkaller_crash_demo.md)（关于如何使用新的系统调用扩展syzkaller的教程）
>    - [使用syzkaller的内核调试工具](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syz_debug.md)（由syz-manager和gdb创建的调试qemu VM）
>    - [一些syzkaller内部的解释](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syz_analysis.md)
>    - [模糊ceph文件系统的一个例子](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/tree/master/docs/harbian_qa/fuzz_testing/syz_for_ceph)
> 4. [使用syzkaller进行覆盖引导内核模糊测试](https://lwn.net/Articles/677764/)（作者David Drysdale）
> 5. [ubsan，kasan，syzkaller und co](http://www.strlen.de/talks/debug-w-syzkaller.pdf)（[视频](https://www.youtube.com/watch?v=Acp0A9X1254)）（作者：Florian Westphal）
> 6. [调试syzkaller发现的内核崩溃](http://vegardno.blogspot.de/2016/08/sync-debug.html)（作者：Quentin Casasnovas）
> 7. [Linux管道工2016年谈话幻灯片](https://docs.google.com/presentation/d/1iAuTvzt_xvDzS2misXwlYko_VDvpvCmDevMOq2rXIcA/edit?usp=sharing)
> 8. [syzkaller：下一代内核fuzzer](https://www.slideshare.net/DmitryVyukov/syzkaller-the-next-gen-kernel-fuzzer)（操作基础，如何运行syzkaller以及如何将其扩展到模糊新驱动程序的教程）
> 9. [syzbot和一千个内核bug的故事](https://events.linuxfoundation.org/wp-content/uploads/2017/11/Syzbot-and-the-Tale-of-Thousand-Kernel-Bugs-Dmitry-Vyukov-Google.pdf) [ [视频](https://www.youtube.com/watch?v=qrBVXxZDVQY) ]
> 10. [安装和使用介绍](<https://www.freebuf.com/sectool/142969.html>)@by freebuf

### kAFL-2017

>  在本文中，我们以独立于操作系统和硬件辅助的方式处理覆盖引导内核模糊测试的问题：我们使用管理程序和英特尔的处理器跟踪（PT）技术。这使我们能够独立于目标操作系统，因为我们只需要一个与目标操作系统交互的小型用户空间组件。因此，即使在操作系统崩溃的情况下，我们的方法几乎不会引入性能开销，并且在现成的笔记本电脑上每秒执行多达17,000次执行。我们开发了一个名为kernel-AFL（kAFL）的框架来评估Linux，macOS和Windows内核组件的安全性。在许多崩溃中，我们发现了Linux的ext4驱动程序，macOS的HFS和APFS文件系统以及Windows的NTFS驱动程序中的几个缺陷。
>
> **相关资料：**
>
> 1. [论文：《kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels》-Usenix17](<https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-schumilo.pdf>) 
> 2. [源码地址](<https://github.com/RUB-SysSec/kAFL>)

### TriforceAFL-2016

> AFL / QEMU 模糊器具有全系统的仿真。这是AFL的修补版本，支持使用QEMU的全系统模糊测试。它所包含的QEMU已经更新，允许在运行x86_64的系统仿真器时进行分支机构跟踪。它也添加了额外的指令来启动AFL的forkserver，进行模糊设置，并标记测试用例的启动和停止。
>
> **相关资料：**
>
> 1. [project](https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2016/june/project-triforce-run-afl-on-everything/)
> 2. [源代码](https://github.com/nccgroup/TriforceAFL)

### KernelFuzzer-2016

> 跨平台内核Fuzzer框架
>
> **相关资料：**
>
> 1. [主页文档介绍](https://labs.mwrinfosecurity.com/publications/platform-agnostic-kernel-fuzzing/)
> 2. [演讲PPT](<https://labs.mwrinfosecurity.com/assets/BlogFiles/mwri-Platform-Agnostic-Kernel-Fuzzing-FINAL.pdf>)
> 3. [视频文档讲解](https://www.youtube.com/watch?v=M8ThCIfVXow)
> 4. [源代码](https://github.com/mwrlabs/KernelFuzzer)

## **浏览器 Fuzzers**

### IFuzzer-2016]

> 该论文主要是针对脚本引擎的fuzz，只是文中使用了js engine作为目标。核心思想就是：收集大量的测试代码，使用antlr4编写好的语法解析器解析出`非终结符片段`，把输入解析成AST后，在AST上进行变异。变异的方式主要是利用收集的“片段”去替换解析树中相同非终结符，由于采用了遗传算法，通过对每个个体的评估，筛选优秀的个体进行“杂交”产生新的个体进入下一轮fuzz，“杂交”的方法是交换两个个体中相同的非终结符节点，产生两棵新的输。
>
> **相关资料：**
>
> 1. [论文-ESORICS 2016](https://link.springer.com/chapter/10.1007/978-3-319-45744-4_29)
> 2. [论文笔记](http://muhe.live/2018/06/09/%E8%AE%BA%E6%96%87%E9%98%85%E8%AF%BB-IFuzzer-An-Evolutionary-Interpreter-Fuzzer-using-Genetic-Programming/)-@muhe
> 3. [源代码](https://github.com/vspandan/IFuzzer)

### Kitty-2016

> Kitty是一个用python编写的开源模块化和可扩展的模糊测试框架，受OpenRCE的[Sulley](https://github.com/OpenRCE/sulley) 和Michael Eddington（以及现在的Deja Vu Security的）[Peach Fuzzer的](http://community.peachfuzzer.com/)启发。(**还在更新**)
>
> 当我们开始编写Kitty时，我们的目标是帮助我们模糊不寻常的目标 - 意味着通过非TCP / IP通信通道的专有和深奥的协议 - 无需每次都从头开始编写所有内容。一个通用的抽象框架，包括我们可以想到的每个模糊过程的共同功能，并允许用户轻松扩展并使用它来测试他们的特定目标。
>
> [Katnip](https://github.com/cisco-sas/katnip)是[Kitty](https://github.com/cisco-sas/kitty)的实现和扩展的存储库。虽然Kitty定义了基类和语法，但它不包含任何特定的实现。因此，例如，为了通过TCP发送有效负载，您需要创建一些扩展`ServerTarget` 并能够通过TCP发送数据的类，依此类推。Katnip包含这样的课程。目前，Katnip包含以下各种实现：
>
> - 服务器和客户端的控制器
> - 显示器
> - 目标
> - 积木
> - 模板
>
> **相关资料：**
>
> 1. [Kitty介绍](https://kitty.readthedocs.io/en/latest/)
> 2. [Katnip介绍](https://katnip.readthedocs.io/en/latest/)
> 3. [源代码](https://github.com/Cisco-sas/kitty)

### Wadi-fuzzer-2015

> Wadi是基于web浏览器语法的模糊器。 这个语法用于描述浏览器应该如何处理Web内容，Wadi转向并使用语法来打破浏览器。
> Wadi是一个Fuzzing模块，用于NodeFuzz fuzzing Harness并利用AddressSanitizer（ASan）在Linux和Mac OSX上进行测试。
>
> **相关资料：**
>
> 1. [官方文档介绍](https://sensepost.com/blog/2015/wadi-fuzzer/)
> 2. [视频讲解](<https://www.youtube.com/watch?v=MNx0pdFQ_SE>)
> 3. [源代码](https://github.com/sensepost/wadi)
>

### Nightmare-2014

> Nightmare是Segment的高级浏览器自动化库。 目标是探索一些模仿用户操作的简单方法（如goto，type和click），使用对每个脚本块感觉同步的API，而不是深层嵌套的回调。它最初设计用于在没有API的站点之间自动执行任务，但最常用于UI测试和网络爬虫。
>
> github 上start数量16992多。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/segmentio/nightmare)

### gramfuzz-2013

> Web浏览器接受JavaScript，CSS文件以及html作为输入，必须在模糊测试中考虑，而传统的模糊测试技术使用简单的变异策略生成测试用例，忽略语法和代码结构。本文总结了漏洞模式，提出了一种基于输入数据语法分析和代码结构变异的新的模糊测试方法。结合生成和变异的方法，测试用例在Web浏览器的模糊测试中会更有效。应用于Mozilla和IE Web浏览器，
>
> **相关资料：**
>
> 1. [论文:《GramFuzz: Fuzzing testing of web browsers based on grammar analysis and structural mutation-ICIA’13](<https://www.researchgate.net/publication/261089247_GramFuzz_Fuzzing_testing_of_web_browsers_based_on_grammar_analysis_and_structural_mutation>)
> 2. [源代码](https://github.com/d0c-s4vage/gramfuzz)

### NodeFuzz-2012

> NodeFuzz是用于Web浏览器和类似浏览器的应用程序的模糊控制器。NodeFuzz背后有两个主要思想。首先是创建一种简单快速的模糊不同浏览器的方法。第二个是使用新的测试用例生成器和客户端仪器轻松扩展一个线束，而无需对内核进行修改。
>
> **相关资料：**
>
> 1. [介绍](https://code.google.com/archive/p/ouspg/wikis/NodeFuzz.wiki)
> 2. [源代码](https://github.com/attekett/NodeFuzz)

### Grinder-2011

> Grinder是一个自动化Web浏览器模糊测试和大量崩溃管理的系统。Grinder节点提供了一种fuzz浏览器的自动方式，并生成有用的崩溃信息（例如带有符号信息的调用堆栈以及可用于在稍后阶段生成可重现的测试用例的日志信息）。Grinder Server提供了一个整理崩溃的中心位置，并通过Web界面允许多个用户登录和管理所有Grinder节点生成的所有崩溃。
>
> **相关资料：**
>
> 1. [介绍](https://code.google.com/archive/p/ouspg/wikis/NodeFuzz.wiki)
> 2. [源代码](https://github.com/attekett/NodeFuzz)

------

## **ActiveX Fuzzers**

### dranzer-2008

>ActiveX和COM漏洞最近受到了很多关注。ActiveX允许Web浏览器使用Windows机器上安装的软件组件。脚本技术可以允许攻击者控制机器的内存内容。通过结合脚本和ActiveX，攻击者可以利用COM对象中的缺陷，这可能允许执行任意代码，信息泄露或其他安全违规。Dranzer是一个可以检测COM对象中的缺陷的工具。。拥有第二个版本[dranzer2.0](https://sourceforge.net/projects/enhanceddranzer/files/dranzer/)
>
>**相关资料：**
>
>1. [源代码](https://github.com/CERTCC/dranzer)

---

## **Library Fuzeers**

### libFuzzer

> C/C++编写的目标进程内覆盖引导渐进式fuzzing引擎。基于LibFuzzer实现的两个fuzzer：clang-format-fuzzer和clang-fuzzer。Clang格式大多是一个词法分析器，所以给它随机字节格式是会完美运行的，但也伴随着超过20个错误。然而Clang不仅仅是一个词法分析器，给它随机字节时几乎没有划伤其表面，所以除了测试随机字节，我们还在令牌感知模式中模糊了Clang。两种模式中都发现了错误; 其中一些以前被AFL检测到，另一些则不是：我们使用AddressSanitizer运行这个模糊器，结果发现一些错误在没有它的情况下不容易被发现。
>
>
> **相关资料：**
>
> 1. [源代码](http://llvm.org/docs/LibFuzzer.html)
> 2. [libFuzzer教程](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
> 3. [LLVM主页官方文档介绍](http://llvm.org/docs/LibFuzzer.html)
> 4. [libFuzzer研讨会：“C/C++项目的现代fuzzing](https://github.com/Dor1s/libfuzzer-workshop)
> 5. [clang-format-fuzzer](http://llvm.org/viewvc/llvm-project/cfe/trunk/tools/clang-format/)
> 6. [clang-fuzzer](http://llvm.org/viewvc/llvm-project/cfe/trunk/tools/clang-fuzzer/)



---

## **网络协议Fuzzers**

可帮助fuzzing使用基于网络协议（如HTTP, SSH, SMTP等）的应用程序Fuzzers。

###  Sulley-2007

> Sulley是一个积极开发的模糊引擎和模糊测试框架，由多个可扩展组件组成。Sulley（IMHO）超过了此前公布的大所属模糊技术、商业和公共领域的能力。框架的目标是不仅是可以简化数据表示，而且也可以简化数据传输和仪表。Sulley是以 Monsters Inc.的生物来命名的，因为，他是模糊的。写在python内的。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/OpenRCE/sulley)
> 2. [使用手册](<http://www.fuzzing.org/wp-content/SulleyManual.pdf>)

### Sulley_l2-2008

> 有些人可能记得2008年发布的sulley_l2，它是sulley模糊框架的修改版本，增强了第2层发送功能和一堆（L2）模糊脚本。
>
> **相关资料：**
>
> 1. [源代码](<http://ernw.de/download/sulley_l2.tar.bz2>)

###  boofuzz-2012

> Sulley框架的分支和继承。除了许多错误修复，boofuzz旨在扩展性。目标：模糊一切。
>
> **还在更新**
>
> **相关资料：**
>
> 1. [在线官方文档](<https://boofuzz.readthedocs.io/en/latest/>)
> 2. [pdf文档](<https://media.readthedocs.org/pdf/boofuzz/latest/boofuzz.pdf>)
> 3. [演讲PPT](<https://cdn.shopify.com/s/files/1/0177/9886/files/phv2016-jpereyda.pdf>)
> 4. [源代码](https://github.com/jtpereyda/boofuzz)

###  backfuzz-2012

> backfuzz是一款可以用于fuzz多种不同协议(如FTP、HTTP、IMAP)的安全工具等等，但它不仅仅支持协议fuzz，还可以通过插件的方式扩展其功能，使它支持协议之外的fuzz，如文件fuzz。基于backfuzz的functions.py，任何人都可以开发自己的插件，用于 fuzz其他不同的协议。
>
> **相关资料：**
>
> 1. [源代码](https://github.com/localh0t/backfuzz)

###  Spike-2010

> 一个fuzzer开发框架。
>
> ### **相关资料：**
>
> 1. [使用Spike Fuzzing查找溢出](https://null-byte.wonderhowto.com/how-to/hack-like-pro-build-your-own-exploits-part-3-fuzzing-with-spike-find-overflows-0162789/)
> 2. [使用Spike Fuzzing](https://samsclass.info/127/proj/p18-spike.htm) – samclass.info
> 3. [源代码](http://www.immunitysec.com/downloads/SPIKE2.9.tgz)

### Dizzy-2018

> dizzy是一个模糊的框架，用python编写，能够通过大量输出选项进行状态完全和无状态模糊测试。1.可以发送到L2以及上层（TCP / UDP / SCTP）。2.能够处理奇长度分组字段（无需匹配字节边界，因此即使单个标志或7位长字。3.也可以表示和模糊）。4.非常容易的协议定义语法。5.能够做多包状态的完全模糊，能够使用接收到的目标数据作为响应
>
> **相关资料：**
>
> 1. [源代码](https://github.com/ernw/dizzy)

----

## **分布式 Fuzzers**

### ClusterFuzz-2019(google)

> ClusterFuzz是一个可扩展的模糊测试基础设施，可在软件中发现安全性和稳定性问题。
>
> 它被谷歌用于模糊Chrome浏览器，并作为[OSS-Fuzz](https://github.com/google/oss-fuzz)的模糊后端 。
>
> ClusterFuzz提供了许多功能，可以帮助将模糊测试无缝集成到软件项目的开发过程中：
>
> - 高度可扩展。谷歌的内部实例运行在超过25,000台机器上。
> - 准确的重复数据删除崩溃。
> - 问题跟踪器的全自动错误归档和关闭（仅限现在的[单轨](https://opensource.google.com/projects/monorail)）。
> - 测试用例最小化。
> - 通过[二分法找回](https://en.wikipedia.org/wiki/Bisection_(software_engineering))回归。
> - 用于分析模糊器性能和崩溃率的统计信息。
> - 易于使用的Web界面，用于管理和查看崩溃。
> - 支持覆盖引导模糊（例如libFuzzer和AFL）和blackbox模糊测试。
>
>  **相关资料：**
>
> 1. [官方文档](<https://google.github.io/clusterfuzz/>)
> 2. [源代码](<https://github.com/google/clusterfuzz>)

### fuzzinator-2018

> *Fuzzinator*是一个模糊测试框架，可帮助您自动执行模糊会话期间通常需要的任务：
>
> - 运行您最喜欢的测试生成器并将测试用例提供给被测系统，
> - 抓住并保存独特的问题，
> - 减少失败的测试用例，
> - 简化bug跟踪器中问题的报告（例如，Bugzilla或GitHub），
> - 如果需要，定期更新SUT
> - 安排多个SUT和发电机，而不会使工作站过载。
>
> ### **相关资料：**
>
> 1. [PPT](https://www.slideshare.net/hodovanrenata/fuzzinator-in-bug-we-trust)
> 2. [教程](https://github.com/renatahodovan/fuzzinator/blob/master/docs/tutorial.rst)
> 3. [论文《Fuzzinator: An Open-Source Modular Random Testing Framework》-ICST’18](https://ieeexplore.ieee.org/document/8367070)
> 4. [源代码](https://github.com/renatahodovan/fuzzinator)

### OSS-fuzz-2017（google）

> OSS-Fuzz 的目的是利用更新的模糊测试技术与可扩展的分布式执行相结合，提高一般软件基础架构的安全性与稳定性。OSS-Fuzz结合了多种模糊测试技术/漏洞捕捉技术（即原来的libfuzzer）与清洗技术（即原来的AddressSanitizer），并且通过ClusterFuzz为大规模可分布式执行提供了测试环境。
>
> **相关资料：**
>
> 1. [论文:《OSS-Fuzz - Google's continuous fuzzing service for open source software》usenixsecurity17](<https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany>)
> 2. [源代码](https://github.com/google/oss-fuzz)

### FuzzFlow-2016

> Fuzzflow是来自cisco talos的一个分布式的模糊管理框架，它提供虚拟机管理，模糊作业配、可插拔变异引擎、前/后变形脚本、崩溃收集和可插拔崩溃分析。FuzzFlow是一种基于concolic执行的自动化测试生成工具。FuzzFlow利用动态二进制检测来修改x86 ELF二进制文件，以便为污点分析启用数据流跟踪。通过分析附近约束的数据流路径并通过转换二进制来进行符号执行来解决新输入，从而生成新测试。
>
>  **相关资料：**
>
> 1. [主页](https://www.talosintelligence.com/moflow)
> 2. [源代码](https://github.com/talos-vulndev/FuzzFlow)

### BrundleFuzz-2016

> BrundleFuzz是一个分布式Windows模糊器。它的核心是基于[lcamtuf的AFL](http://lcamtuf.coredump.cx/afl/)
>
>  **相关资料：**
>
> 1. [源代码](<https://github.com/carlosgprado/BrundleFuzz>)



---

## **评估 Fuzzers**

### Evaluating Fuzz Testing

> 摘要:Fuzz测试在发现真实软件中的安全性关键错误方面取得了巨大成功。最近，研究人员投入了大量精力来设计新的模糊测试技术，策略和算法。这些新想法主要是通过实验评估的，因此一个重要的问题是：需要哪些实验设置才能产生值得信赖的结果？我们调查了最近的研究文献，并评估了32个模糊论文所进行的实验评估。我们在每次评估中都发现了问题。然后，我们使用现有的模糊器进行了我们自己的广泛实验评估。我们的结果表明，我们在现有实验评估中发现的一般问题确实可以转化为实际的错误或误导性评估。我们总结了一些指导原则，希望这些指南有助于改进模糊测试算法的实验评估，使报告结果更加稳健。
>
> **相关资料：**
>
> 1.[论文：《Evaluating Fuzz Testing》-CCS’18](<http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf>)
>
> 2.[演讲视频](<https://www.youtube.com/watch?v=ID8XtoMn43I>)



# **污点分析相关工具 **

用户输入如何影响执行

### [PANDA](https://github.com/moyix/panda)

> 构建于顶级QEMU系统的新一代动态分析平台

### [QIRA](http://qira.me/)

> QEMU交互式运行时分析器

### [kfetch-toolkit](https://github.com/j00ru/kfetch-toolkit)

> 执行高级记录引用的工具

---

# **符号执行相关工具**

### [Z3](https://github.com/Z3Prover/z3)

> 属于SMT Solver，用于判定First Order Logic公式的可满足性。
>
>  **相关资料：**
>
> 1. Z3 – 指南](https://rise4fun.com/z3/tutorial/guide) – Z3入门指南：指南

### [SMT-LIB](http://smtlib.cs.uiowa.edu/)

> 旨在促进SMT研究与开发的国际计划。

# **辅助工具**

针对exploit开发人员和逆向工程师的工具。

### 调试工具

> [Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools) – windows平台下强大的用户态和内核态调试工具。
>
> [Immunity Debugger](http://debugger.immunityinc.com/)- 专门用于加速漏洞利用程序的开发，辅助漏洞挖掘以及恶意软件分析。
>
> [OllyDbg](http://www.ollydbg.de/) – 一个新的动态追踪工具。
>
> [Mona.py](https://github.com/corelan/mona/)（windbg和Immunity dbg的插件）
>
> [x64dbg](https://github.com/x64dbg/) – 用于Windows的开源x64/x32调试器。
>
> [Evan的调试器（EDB）](http://codef00.com/projects#debugger)- gdb前端。
>
> [GDB – Gnu调试器](http://www.sourceware.org/gdb/) – 最喜欢的Linux调试器。
>
> [PEDA](https://github.com/longld/peda) – 针对GDB的Python Exploit开发助手。
>
> [Radare2](http://www.radare.org/r/) – 用于逆向工程和二进制文件分析的框架。

### **反编译**

> [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml)- 最好的反编译软件
>
> [binnavi](https://github.com/google/binnavi) – 二进制分析IDE，注释控制流程图和调用反编译代码的图形。
>
> [Capstone](https://github.com/aquynh/capstone) – Capstone是一个轻量级的多平台，多架构反编译框架。

### **其它**

> [ltrace](http://ltrace.org/) – 用来跟踪进程调用库函数的情况。
>
> [strace](https://sourceforge.net/projects/strace/) – 跟踪系统调用和信号。

## 漏洞应用程序

> Exploit-DB -[ https://www.exploit-db.com](https://www.exploit-db.com/)（通过搜索相关的应用漏洞，并自行下载漏洞应用及EXP重现漏洞）
>
> PacketStorm - <https://packetstormsecurity.com/files/tags/exploit/>
>
> [Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - 用于测试fuzzers的漏洞C程序。

### 模糊测试样本文件

> <https://files.fuzzing-project.org/>
>
> [来自Mozilla的PDF测试语料库](https://github.com/mozilla/pdf.js/tree/master/test/pdfs)
>
> [MS Office文件格式文档](https://www.microsoft.com/en-us/download/details.aspx?id=14565)
>
> [模糊测试套件](https://github.com/google/fuzzer-test-suite) – fuzzing引擎测试集。包括不同的已知bug，如Heartbleed， c-ares $100K bug等。
