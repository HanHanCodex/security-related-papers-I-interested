# Static Detection of Core Structures in Tigress Virtualization-Based Obfuscation Using an LLVM Pass

**研究方向：** Obfuscation, Static Analysis, LLVM

## 📝 原文摘要 (Original Abstract)
> Tigress is a powerful obfuscation tool that employs code virtualization. We propose a static analysis technique, implemented as an LLVM Pass, to detect and locate the core structures (e.g., the dispatcher and virtual registers) introduced by Tigress virtualization. By leveraging the semantics available in the LLVM Intermediate Representation, our method achieves high accuracy in assisting deobfuscators to recover the original control flow and data flow.

## 💡 助理总结 (创新点/Insights)
> **核心洞察：针对最复杂的**虚拟化混淆**进行自动化解构。创新点在于通过 **LLVM Pass** 在编译中间层进行语义分析，精准识别虚拟寄存器和分发器，为后续自动化去混淆提供了精确的起始点。**
