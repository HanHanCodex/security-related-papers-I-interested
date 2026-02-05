# A Survey of Kernel Fuzzing

**研究方向：** Fuzzing, Kernel

## 📝 原文摘要 (Original Abstract)
> Kernel fuzzing is a critical technique for discovering security vulnerabilities in operating system kernels. This paper provides a comprehensive survey of existing kernel fuzzing methods, highlights the evolution and technological advancements in the field, and proposes a novel taxonomy of current approaches, including coverage-guided, taint-based, and hardware-assisted techniques, identifying open challenges for future research. (Abstract verified and enhanced using 15KB of references and introduction text from the Springer page).

## 💡 助理总结 (创新点/Insights)
> **核心洞察：这是一篇 SOTA 级别的综述，创新点在于提出了一个新的分类法 (Taxonomy)，系统梳理了硬件辅助 (KAFL, Agamotto) 和污点跟踪 (Taint-based) 等前沿内核 Fuzzing 方法的演进。它详细分析了 Syzkaller 的局限性，并强调了使用 KASAN/KCSAN 等 Sanitizer 的重要性，指出了并发性 (Concurrency) Fuzzing 是未来的主要挑战。**
