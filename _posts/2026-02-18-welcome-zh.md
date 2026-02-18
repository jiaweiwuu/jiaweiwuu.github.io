---
title: "技术博客写作：一个干净的工作流（示例）"
date: 2026-02-18
permalink: /posts/2026/02/welcome-zh/
tags:
  - 写作
  - 数学
  - jekyll
lang: zh
---

English version: [/posts/2026/02/welcome/](/posts/2026/02/welcome/)

这是一篇示例文章，用来确认：

- Markdown 正常渲染
- 代码高亮正常
- MathJax 数学公式正常

## 数学公式（MathJax）

行内公式：$p(x) = \\mathcal{N}(x\\mid 0, 1)$

块级公式：

$$
\\mathrm{ELBO} = \\mathbb{E}_{q(z\\mid x)}[\\log p(x\\mid z)] - \\mathrm{KL}(q(z\\mid x)\\,\\|\\,p(z)).
$$

## 代码块

```python
import math

def softplus(x: float) -> float:
    return math.log1p(math.exp(x))
```

## 写作建议

写之前先画文章大纲：动机 → 方法 → 推导/实现细节 → 实验 → 失败案例/注意事项 → 总结。

