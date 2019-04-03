# database

用于存放本地下载的论文和其它相关学习资料，如PPT，PDF，word文件，小工具等等。（文件大小不要操作100M，超过100M的文件或工具可自己上传到网盘，然后将链接和密码写到对于的资料简介处）



## Paper

> 翻译或总结后的论文原文网上未能公开下载，通过其它方式下载到本地的论文可存放到对应文件夹下，目前包括的论文类别有如下几种：
>
> *  Fuzzing
> * AutomatedExploit
> * ReverseEngineering
> * MaliciousSampleDetecion
> * TaintAnalysis
> * SymbolicExecution

## other

> 存放其它非论文资料，如一些学习资料，包括PPT、PDF、word等。一些好用的工具也可存放到这里。

- 恶意文档检测数据集

  > 上传者：刘露平
  >
  > 时间：2019.03.27
  >
  > 下载链接：[https://drive.google.com/file/d/1WQalJ39wzZ9g6LpxZTdSVQkIHpXDfHNv/view?usp=sharing](https://drive.google.com/file/d/1WQalJ39wzZ9g6LpxZTdSVQkIHpXDfHNv/view?usp=sharing)
  >
  > 摘要：该数据集是通过收集整理自己形成的，目前包含总共样本10381个，其中恶意样本5344个，正常样本5037个。包含Office(rtf,doc,ppt,xls, docx, pptx, xlsx）和PDF几个类别等几个类别。各个样本的统计分布如下图所示![数据集中样本分布情况](E:\网站博客\实验室\BinaryDatabase\database\figures\MaliciousDocument.png)：

- UNSW-NB-15数据集

> 上传者：王炎
>
> 时间：2019.04.03日
>
> UNSW-NB 15数据集的原始网络数据包是由澳大利亚网络安全中心（ACCS）的网络范围实验室中的IXIA PerfectStorm工具创建的，用于生成真实现代正常活动和合成当代攻击行为的混合体。
>
> Tcpdump工具用于捕获100 GB的原始流量（例如，Pcap文件）。此数据集有九种类型的攻击，即Fuzzers，Analysis，Backdoors，DoS，Exploits，Generic，Reconnaissance，Shellcode和Worms。使用了Argus，Bro-IDS工具，开发了12种算法，通过类标签生成49个特征。
>
> 数据分布情况如下所示

| Type           | No of Records | Description                                                  |
| -------------- | ------------- | ------------------------------------------------------------ |
| Fuzzers        | 24,246        | This attack scan to discover flaws and security loopholes in a program, operating system, or network by feeding it with the massive inputting of random data to make it crash. |
| Analysis       | 2,677         | A port based intrusion attack against web applications       |
| Backdoors      | 2,329         | This is a remote attack to gain unauthorized access to a system |
| DoS            | 16,353        | This attack exhaust the destinations resources so that resources required by the is not made available and normal traffic becomes denied |
| Exploits       | 44,525        | a sequence of instructions that takes advantage of a glitch, bug, or vulnerability to be caused by an unintentional or unsuspected behavior on a host or network. |
| Generic        | 58,871        | A techniques works against all block-ciphers (with a given block and key size), without consideration about the structure of the block-cipher |
| Reconnaissance | 13,987        | This is a probe attack that that gathers information about a computer network to evade its security controls |
| Shell code     | 1,511         | Small program with instructions from a shell to compromised the victim’s computer |
| Worms          | 174           | A Self replicating malicious code attack that that spread itself to other computers, mostly over a computer network, without attaching itself to a program like a virus |

> 主页介绍和下载链接：<https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/>
>
> 论文介绍：<https://ieeexplore.ieee.org/abstract/document/7348942>