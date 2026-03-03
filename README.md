# hj-backward-reachable-set-notes

后向可达集（Backward Reachable Set, BRS）学习笔记仓库。  
仓库以 Hamilton-Jacobi (HJ) 可达性分析为主线，通过“基础概念 + 示例推导”帮助读者快速建立整体认识。

## 仓库内容

```text
hj-backward-reachable-set-notes/
├─ notes/
│  ├─ BRS_basic/
│  │  ├─ BRS_intro.tex          # BRS/BRT 基础概念与方程说明
│  │  └─ figures/               # 对应插图
│  └─ BRS_example/
│     ├─ DubinCars.tex          # Dubins' Car 示例（建模 + HJ 方程 + 结果解释）
│     ├─ figures/               # 示例插图
│     └─ _minted/               # 文档中的代码高亮缓存文件
├─ code/                        # 预留目录（后续补充示例代码）
└─ README.md
```

## 文档讲了什么

- [notes/BRS_basic/BRS_intro.tex](notes/BRS_basic/BRS_intro.tex)
	- 介绍 BRS/BRT 的核心概念与区别。
	- 说明值函数、零水平集与 HJ 方程之间的关系。
	- 提供示例分析所需的理论框架。

- [notes/BRS_example/DubinCars.tex](notes/BRS_example/DubinCars.tex)
	- 给出 Dubins' Car 的动力学模型与目标集设定。
	- 展示该模型下 HJ 方程的写法及最优控制/扰动分析。
	- 通过有扰动与无扰动对比，帮助读者直观理解 BRS/BRT 差异。

## 阅读建议

建议按“基础概念 → 示例分析”的顺序阅读：

1. [notes/BRS_basic/BRS_intro.tex](notes/BRS_basic/BRS_intro.tex)
2. [notes/BRS_example/DubinCars.tex](notes/BRS_example/DubinCars.tex)

## 代码计划

`code/` 目录将于后续逐步补充，计划包含：

- 与文档对应的最小示例脚本；
- 参数设置与可视化脚本；
- 面向后续扩展模型的代码模板。