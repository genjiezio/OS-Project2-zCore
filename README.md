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

      


## Implementation

For basic part:
1. According the [route](https://github.com/rcore-os/zCore-Tutorial), realized the zCore by step.
2. Realized more Linux systemcall

If we still have enouh time:

3. According to rCore's  `smoltcp` protocal stack, transtorming it to zCore to impelement the request of Linux web request
4. Improve the structure of OS to support and improve the kernel level asynchronous scheduling mechanism

## Timeline

May 4th : learning the `rust` language

May 18th : According the tutorial, impelement the request of zCore

May 25th ：Realized more Linux systemcall

May 30th : Reserved time, also for finnal report

## Meterial

* [route](https://github.com/rcore-os/zCore-Tutorial)

## Member
* 11810115 陈启龙
* 11810420 王照伟

## Team work
