# Using a Hypervisor for Enforcing Control Flow Integrity in Native Compiled Programs

**研究方向：** Control Flow Integrity, Hypervisor

## 📝 原文摘要 (Original Abstract)
> Control Flow Integrity (CFI) is a crucial defense against memory corruption attacks. This paper proposes a novel approach utilizing hardware virtualization (Hypervisor) to enforce CFI without requiring source code modification or recompilation. The hypervisor intercepts control flow transfers (e.g., calls, returns, jumps) and verifies them against a pre-computed safe target set, effectively stopping ROP and JOP attacks with minimal performance overhead.

## 💡 助理总结 (创新点/Insights)
> **核心洞察：一种零源码修改的 CFI 方案。创新点在于利用 **Hypervisor** 在底层硬件级别拦截和验证控制流，实现了对原生二进制程序的透明且高效的 CFI 保护。**
