# OS-Project2-zCore

## Project Background

**Description**：

**ZCore** is the Zircon micro kernel rewritten in Rust language.This project explores the modern system language RUST, OS-level asynchronous mechanism, multi-kernel mechanism, flexible and open instruction set architecture RISC-V, etc. The design and implementation innovation of the operating system in this project, is an attempt of the future operating system.

**Feature**：

- Based on RUST，which take full advantage of Asynchronous mechanism provided by RUST.
- Support most syscall of Zircpn micor kernel, and some syscall of linux.
- Can run in User mode in the form of LibOS, or run in bare computer in the form of traditional OS.
- Can run in X86_64 and RISC_V. 

**Relevant materials**:

- [Instruction of implement OS based on Rust](https://github.com/rcore-os/rCore/wiki/os-tutorial-summer-of-code)
- [Release news of zCore](https://zhuanlan.zhihu.com/p/137733625)
- [Diploma Project and Design document](https://github.com/rcore-os/zCore/wiki/documents-of-zCore)
- [zCore-Tutorial](https://github.com/rcore-os/zCore-Tutorial)
- [rust](https://github.com/rcore-os/rCore/wiki/os-tutorial-summer-of-code)


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


