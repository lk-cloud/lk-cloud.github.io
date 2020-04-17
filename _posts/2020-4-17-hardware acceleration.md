---
layout: post
title: 加速技术
---

#### 硬件加速概念
> （Hardware Acceleration）就是利用硬件模块来替代软件算法以充分利用硬件所固有的快速特性（硬件加速通常比软件算法的效率要高），从而达到性能提升、成本优化的一种技术。

> 引入硬件加速的计算架构又称为异构计算（Heterogeneous Computing），相对于通用计算（又称同构计算）来说，异构就是CPU、SoC、GPU、ASIC、FPGA等各种使用不同类型指令集、不同体系架构的计算单元，组成一个混合的系统，执行计算的特殊方式。

- Soc：比较小，相对固定成型，需要和DSP等周边系统进行协同组成操作系统
- GPU：固定成型，计算时候全部工作，不计算时候全部空闲，适用于图像处理等场景
- ASIC：固定成型，价格低，速度快，不改动
- FPGA：前期经常修改重写，从FPGA逐步发展为ASIC
