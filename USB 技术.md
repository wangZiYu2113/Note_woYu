
### 1.USB 简介

USB 技术是微软与英特尔共同成立的 USB-IF 组织共同认证的 
同时英特尔与苹果共同制定了雷电系列协议（Thunderbolt）

**雷电协议**
雷电 1/2 MiniDP 接口
雷电 3/4/5 统一使用 type-C

**USB-IF 协议**
![[Pasted image 20260831162018.png]]

1. 命名：
  已取消 3.0 系列命名规则，直接以传输速度命名接口；2.0 系列不变；
  第一代 5 Gbps 速率：USB 3.0  = USB 3.1 Gen1 = USB 3.2 Gen1 =  USB 5Gbps
  第二代 10 Gbps 速率： USB 3.1 = USB 3.1 Gen2 = USB 3.2 Gen2 = USB 10Gbps
  第三代 20 Gbps 速率 ：USB 3.2 = USB 3.2 Gen 2 x 2 = USB 20 Gbps
  4.0 系列第一代最高 40 Gbps 速率：USB 4.0 v1 =  USB 40 Gbps
  4.0 系列第二代最高 80 Gbps 速率：USB 4.0 v2 = USB 80 Gbps
  
2. **带宽** 不等于 **速度** ！图中的速度应更正为带宽；480 Mbps 理论速度为 60 MB/s ，实际为 42 MB/s 
3. **发展历程**
USB‑IF（USB 标准组织）吸收雷电 3 的技术，做成公开标准 USB 4.0。由此出现了 USB 4.0 第一代 40 Gbps 
雷电 4 实在 USB 4.0v1 的基础上做的强制认证版本
后来出现 USB 4.0 第二代，雷电 5 又是在其基础上做的强制认证版本 （80 Gbps）
4. 
### 2.PCB 注意

1. 建议 USB 走线全部差分走线 等长控制 尽量减少过孔 
2. 高速信号要过孔包地
3. 