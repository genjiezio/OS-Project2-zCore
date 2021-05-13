# Operating System Project 2

## proj19-process-memory-tracker

---

### 项目描述

在linux平台上开发一个工具，此工具可以实时显示想要观察的进程的内存使用情况以及可能的内存泄漏问题，具体要求如下：

- 实时统计系统中各进程及其中包含的线程的内存使用情况；
- 检测某个进程中的内存泄漏问题，包括：内存，文件句柄的泄漏情况，把检测情况实时显示或是输出到指定文件；

---

### 相关资料

- [ccmalloc](http://cs.ecs.baylor.edu/~donahoo/tools/ccmalloc/)－Linux和Solaris下对C和C++程序的简单的使用内存泄漏和malloc调试库。
- [Dmalloc](http://cs.ecs.baylor.edu/~donahoo/tools/ccmalloc/)－Debug Malloc Library.
- [Valgrind](http://valgrind.org/)－Debugging and profiling Linux programs, aiming at programs written in C and C++.
- [查看 Linux 系统中进程和用户的内存使用情况](https://linux.cn/article-11849-1.html)
- [pidstat - 监控并统计Linux进程的数据（内存，进程等监控）](https://developer.aliyun.com/article/71664)

---


## 目标

基础目标：
1. 统计系统进程及其中线程内存使用情况
2. 实现检测具体进程中内存和文件句柄的分配与释放
额外目标：
3. 实时统计系统进程及其中线程内存使用情况

## 规划时间

5月16日 : 了解内存分配释放过程并提出初步方案

5月19日 ： 实现目标一

5月23日 ： 实现检测具体进程内存分配与释放 

5月27日 : 实现检测具体进程文件句柄的分配与释放

5月30日 : 实验总结并汇报

## 小组成员
* 11810115 陈启龙
* 11810420 王照伟

## 分工


