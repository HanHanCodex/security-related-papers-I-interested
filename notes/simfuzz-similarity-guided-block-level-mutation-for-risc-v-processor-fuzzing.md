# SimFuzz: Similarity-guided Block-level Mutation for RISC-V Processor Fuzzing

**研究方向：** Fuzzing, Hardware Security, RISC-V

## 📝 原文摘要 (Original Abstract)
> We introduce SimFuzz, a novel fuzzing methodology for RISC-V processors that employs a similarity-guided, block-level mutation strategy. By leveraging control-flow graph information, SimFuzz identifies instruction blocks that are structurally similar to previously bug-inducing blocks and prioritizes their mutation. This approach significantly increases the effectiveness of finding deep, corner-case microarchitectural bugs, achieving state-of-the-art results on several open-source RISC-V implementations.

## 💡 助理总结 (创新点/Insights)
> **核心洞察：将传统的随机变异提升为智能变异。创新点在于**代码块相似性引导**（Similarity-guided），使变异集中在与已知易错代码结构相似的新代码上，极大地提高了硬件级 Fuzzing 的效率和深度。**
