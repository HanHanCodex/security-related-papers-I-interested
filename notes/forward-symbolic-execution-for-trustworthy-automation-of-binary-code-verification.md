# Forward Symbolic Execution for Trustworthy Automation of Binary Code Verification

**研究方向：** Symbolic Execution, Binary Analysis

## 📝 原文摘要 (Original Abstract)
> We present a theory of forward symbolic execution based on a set of inference rules, where each rule corresponds to an operation in a symbolic execution engine. We implement the theory in the HOL4 theorem prover and instantiate it using the HolBA binary analysis library, providing machine-checked proofs of soundness for symbolic execution. Our application extends HolBA with support for automated verification of functional properties and execution time bounds of RISC-V and ARM Cortex-M0 binaries.

## 💡 助理总结 (创新点/Insights)
> **核心洞察：专注于符号执行的可信赖性。创新点在于**理论的机验证明**（Machine-checked proofs of soundness），并将其应用于 RISC-V 和 ARM Cortex-M0 的功能属性及执行时间界限的自动化验证。**
