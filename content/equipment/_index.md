---
# Page settings
title: 信息安全实验室设备介绍
subtitle: Information Security Laboratory Equipment Overview
date: 2025-09-04
type: landing  # 让页面使用 landing layout，可自由拼接 block

# 页面级参数
summary: 本栏目罗列实验室核心硬件、专用仪器、软件环境与安全管理规范，方便师生快速了解实验资源。
---

<!-- Hero -->
{{< block "hero" >}}
  <div class="hero-overlay py-5">
    <div class="container">
      <h1 class="display-4 fw-bold">信息安全实验室设备介绍</h1>
      <p class="lead">Information Security Laboratory Equipment Overview</p>
    </div>
  </div>
{{< /block >}}

<!-- 目录锚点导航 -->
{{< toc mobile_only=false >}}

<!-- 第一部分 -->
{{< block "section-1" >}}
## 核心硬件设备 | Core Hardware
- **网络攻防靶场平台**  
  虚拟化多租户靶标网络，支持红蓝对抗、APT沙盘、IoT/工控场景仿真。  
  典型型号：CybExer Range、Cisco Cyber Range、Kali Purple Box。

- **高速流量生成与回放系统**  
  以 40–100 Gbps 线速回放 PCAP，测试 IDS/IPS、DPI、防火墙性能极限。  
  典型型号：Keysight BreakingPoint、Spirent CyberFlood。

- **硬件逆向与侧信道分析平台**  
  激光/红外显微探针、电磁探针台、功耗示波器、FPGA SoC 测试座。  
  用途：芯片开封、固件提取、差分功耗分析 (DPA)、故障注入 (FI)。

- **无线安全测试套件**  
  USRP B210、HackRF One、Wi-Fi Pineapple、BladeRF 2.0 micro。  
  应用：2.4/5 GHz Wi-Fi 渗透、蓝牙 BLE 嗅探、ZigBee/LoRa 协议 fuzz。

- **可信执行环境 (TEE) 开发板**  
  NXP i.MX8QXP (ARM TrustZone)、Intel SGX NUC、AMD SEV-SNP 服务器。  
  用途：SGX/TrustZone/SEV 代码审计、TEE 漏洞复现。
{{< /block >}}

<!-- 第二部分 -->
{{< block "section-2" >}}
## 专用仪器 | Specialized Instruments
- **协议分析仪**  
  Wireshark-customized 10 GbE TAP、Ellisys BEX400（USB 3.2/4 协议）。

- **激光故障注入系统**  
  Riscure Laser Station、ChipSHOUTER PicoEMP。

- **电磁兼容 (EMC) 测试接收机**  
  Rohde & Schwarz ESR 26.5 GHz，用于侧信道辐射测量。
{{< /block >}}

<!-- 第三部分 -->
{{< block "section-3" >}}
## 软件与虚拟化环境 | Software & Virtualization
- **云原生靶标编排**  
  Kubernetes + Calico、Metasploit Pro、Atomic Red Team。

- **数字取证工作站**  
  Autopsy, Volatility 3, YARA, Rekall, Magnet AXIOM。

- **安全开发生命周期 (SDL) 工具链**  
  - SAST: Fortify, CodeQL  
  - DAST: OWASP ZAP, Burp Suite Enterprise  
  - Fuzzing: AFL++, Peach Fuzzer, libFuzzer
{{< /block >}}

<!-- 第四部分 -->
{{< block "section-4" >}}
## 辅助与通用设备 | Auxiliary & General Equipment
- 机架式服务器集群：Dell PowerEdge R750/R940xa，GPU (A100) 用于密码破解。  
- 全闪存储阵列：Pure Storage FlashArray//C，低延迟日志留存。  
- 智能配电与 KVM：Raritan Dominion KX III、Schneider APC Smart-UPS。  
- 实验室级静电防护：防静电地垫、离子风机、湿度 40–60 % RH 控制。
{{< /block >}}

<!-- 第五部分 -->
{{< block "section-5" >}}
## 安全与管理规范 | Security & Management Policy
- **物理隔离**：核心靶场网络与办公网通过单向光闸隔离。  
- **零信任访问**：802.1X + NAC + MFA，所有资产纳入 SIEM 统一审计。  
- **分级保密**：设备按“红(外网攻击区)、黄(隔离分析区)、绿(管理区)”三色标签管理。  
- **合规标准**：ISO/IEC 27001、NIST SP 800-53、Common Criteria (CC) EAL4+。
{{< /block >}}

<!-- 结尾 -->
{{< block "section-6" >}}
通过以上设备与管理措施，本信息安全实验室可同时支撑：  
- 高校科研：漏洞挖掘、密码工程、可信计算研究；  
- 企业培训：红蓝对抗演练、安全开发实训；  
- 认证测试：产品 CC EAL、PCI-DSS、渗透测试报告。
{{< /block >}}