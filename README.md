# proj-Linux-0.11-riscv

### 项目描述
Linux 0.11 是一个小型操作系统，其基本风格延续到了现在的主流 Linux 操作系统。原始的 Linux 0.11 操作系统是基于 x86 平台的，本项目的目标是将 Linux 0.11 移植到 RISC-V 平台，锻炼学生的操作系统内核程序开发能力。

### 当前项目相关的实现源码：
- [Linux-0.11](http://www.oldlinux.org/linux.old/Linux-0.11)：原始版本的 Linux 0.11
- [Linux_0.11_RISC-V_QEMU](https://gitee.com/luchangcheng2333/linux_0.11_risc-v_qemu.git)：这是国防科技大学卢昶诚同学的初步移植，运行目标平台是 Qemu 模拟器。
- [K210-Linux-0.11](https://github.com/lizhirui/K210-Linux0.11.git)：这是聊城大学李志锐同学的初步移植，运行目标平台是 K210 开发板。

### 所属赛道
全国大学生操作系统设计赛的“功能挑战”赛道。

### 参赛要求
请遵循“全国大学生操作系统设计赛”的章程和技术方案要求。

### 项目导师
文艳军 
- github: https://github.com/yanjun-wen
- email：yjwen@nudt.edu.cn 

### 难度
中等

### 特征
- 使用C语言实现
- 原始版本使用 bochs 模拟器（x86），目标平台可以是 Qemu 模拟器（RISC-V），也可以是 RISC-V 开发板。

### 文档
- [Linux内核0.12完全注释](http://www.oldlinux.org/download/CLK-5.0-WithCover.pdf)
- [The RISC-V Instruction Set Manual](https://riscv.org/technical/specifications/)
- [xv6-riscv-book](https://github.com/mit-pdos/xv6-riscv-book)

### License

- GPL-3 license

## 预期目标

#### （下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标）

- 将 Linux 0.11 操作系统的启动、进程管理和内存管理模块移植到 RISC-V 平台，支持多个进程并发运行并输出信息。
- 移植后的操作系统可以在 Qemu 模拟器中运行。
