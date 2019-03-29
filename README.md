# BinaryDatabase

Collate and collect binary related materials, including papers, tools, etc

* ## Fuzzing-学习资源汇总
> 本文主要是收集和整理与**fuzzing**相关的资料，包括fuzzing书籍，fuzzing 学习视频、教程和博客、Fuzzer工具等，旨在能更方便的学习`fuzzing`，为后续做相关研究做铺垫。

* ## 恶意样本检测-学习资源汇总
> 本文主要是收集和整理与**恶意样本检测**相关的资料，包括学习资料，论文、工具等，旨在能更方便的学习`恶意样本检测`技术，为后续做相关研究做铺垫。

* ## 符号执行-学习资源汇总
> 本文主要是收集和整理与**符号执行**相关的资料，包括学习资料，论文、工具等，旨在能更方便的学习`符号执行`技术，为后续做相关研究做铺垫。

* ## 逆向工程-学习资源汇总
> 本文主要是收集和整理与**逆向工程**相关的资料，包括学习资料，论文、工具等，旨在能更方便的学习`逆向工程`技术，为后续做相关研究做铺垫。

* ## 污点分析-学习资源汇总
> 本文主要是收集和整理与**污点分析**相关的资料，包括学习资料，论文、工具等，旨在能更方便的学习`污点分析`技术，为后续做相关研究做铺垫。

* ## 工作面试复习资料汇总
> 本文主要是收集和整理研三同学在工作面试中遇到的问题及其相应的回答，以及个人整理的复习资料汇总


* ## Paper
> 阅读过的历年与二进制安全相关的论文笔记，翻译或总结后的论文笔记。
>
> * ### Fuzzing
>> 历年与fuzzing相关的论文阅读笔记
>
>* ###  AutomatedExploit
>> 历年与自动化漏洞利用相关的论文阅读笔记
>
> * ### ReverseEngineering
>> 历年与逆向工程相关的论文阅读笔记
>
> * ### MaliciousSampleDetecion
>> 历年与恶意样本检测相关的论文阅读笔记
>
> * ### TaintAnalysis
>> 历年与污点分析相关的论文阅读笔记
>
> * ### SymbolicExecution
>> 历年与污点分析相关的论文阅读笔记

* ## database
> 用于存放本地下载的论文和其它相关学习资料，如PPT，PDF，word文件，小工具等等。（文件大小不要操作100M，超过100M的文件或工具可自己上传到网盘，然后将链接和密码写到对于的资料简介处）

## BinaryDatabase文件结构

```
├── _book                     // gitbook build自动生成的文件夹，复制除里面docs文件夹的内容到docs文件夹
├── docs                      // github 根据该文件夹的内容生成page
├── node_modules              // npm包的安装目录,包含gitbook安装的插件
├── database                  // 存放本地上传的文档资料
│   ├── papers                 // 存放论文原文
│   ├── other                 // 存放其它资料或工具
├── Paper                     // 论文阅读笔记
│   ├── README.md             // 论文类型的间接
│   ├── AutomatedExploit      // 自动化漏洞利用相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── AutomatedExploit      // 自动化漏洞利用相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── Fuzzing      		 // 漏洞挖掘相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── AutomatedExploit      // 自动化漏洞利用相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── MaliciousSampleDetecion // 恶意样本检测相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── ReverseEngineering    // 逆向工程相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   ├── SymbolicExecution     // 符号执行相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
│   └── TaintAnalysis         // 符号执行相关论文阅读笔记
│   │	├── papers			 //论文阅读笔记md文件存放位置 
│   │	├── README.md		 //论文阅读笔记摘要和索引
├── Fuzzing-学习资源汇总.md    // Fuzzing学习相关资料的汇总和索引
├── 恶意样本检测-学习资源汇总.md   // 恶意样本检测学习相关资料的汇总和索引
├── Fuzzing-学习资源汇总.md    // Fuzzing学习相关资料的汇总和索引
├── 符号执行-学习资源汇总.md    // 符号执行-学习资源汇总学习相关资料的汇总和索引
├── 逆向工程-学习资源汇总.md    // 逆向工程学习相关资料的汇总和索引
├── 污点分析-学习资源汇总.md    // 污点分析学习相关资料的汇总和索引
├── 工作面试复习资料汇总.md    // 工作面试复习相关资料的汇总和索引
├── 信息安全相关会议期刊汇总.md    // 信息安全相关会议期刊汇总
├── .gitignore                // git 的忽略文件
├── book.json                 // 整个gitbook的配置文件，插件配置
├── package-lock.json         // gitbook build 自动生成，不用管
├── README.md                 // 整个BinaryDatabase的简介
└── SUMMARY.md                // 整个BinaryDatabase的目录索引

```