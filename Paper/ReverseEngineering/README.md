## 论文目录
---
### 2019年
#### 综述

#### 研究性工作

---
### 2018年
#### 综述

#### 研究性工作

- **Lord of the X86 Rings: A Portable User Mode Privilege Separation Architecture on X86(CCS)**

> **Abstract**
> 前heartbleed漏洞导致的敏感信息常泄露一直是人们要解决的问题，即如何保护程序中的隐私数据不被任意的访问到。研究人员想到的方法根本出发点为，将隐私数据隔离，即使存在程序漏洞，也不能任意访问到这些敏感数据。而将隐私数据存放于什么位置，是人们一直以来需要解决的问题。此前的解决办法包括，线程隔离，进程隔离，使用可以信执行区域(如Intel SGX)等。这些方法或者性能影响比较大，或者受限到CPU型号。***而在这篇论文里作者使用Intel x86处理器一直以来存在的r0-r3四个特权等级来将数据隔离访问，一方面解决了处理器兼容问题(几乎所有Intel AMD处理器均支持这四个特权级别)，一方面解决了性能问题。***

- **Superset Disassembly: Statically Rewriting X86 Binaries Without Heuristics Disassembly（NDSS）**

> **Abstract**
> 静态代码重写是系统安全应用的一项核心技术，它的使用场景包括性能分析，优化和软件错误定位等。之前的许多静态二进制程序重写方法，例如CCFIR, PITTSFIELD, Google’s Native Client, BinCFI, UROBOROS等，在保证重写正确时，提出了有关二进制程序的许多假定，例如完全正确的反汇编，编译器要求，调试符号等等，给实际应用在Commercial off-the-shelf（COTS）二进制程序上制造了困难。作者提供了`multiverse`，一个新的二进制程序重写器，它不基于上述的任何假定并能够重写intel x86 COTS程序。在COTS二进制程序重写中，存在着两大挑战： （1）如何反汇编二进制代码并包含所有合法指令 （2）如何重新汇编重写后的指令并保留原程序的语义。**`multiverse`使用了两种技术分别解决这两大挑战：（1）superset disassembly：通过对所有offset起始的地址进行反汇编获得合法代码的superset。 （2）instruction rewriter：通过替换控制流转移指令，中转到一个映射表，能够将原程序中所有的指令重定位到任意其他位置。

---
### 2017年
#### 综述

#### 研究性工作

---
### 2016年
#### 综述

#### 研究性工作

---
### 2015年
#### 综述

#### 研究性工作

---
### 未整理






* 

