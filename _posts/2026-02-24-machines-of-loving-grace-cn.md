---
layout: single
title: "读 Dario Amodei《Machines of Loving Grace》随记"
date: 2026-02-24
tags: [AI, 读书笔记, 随记, drug-discovery]
category: essays
---

昨天深夜读完了 Dario Amodei 那篇很长很长的 *Machines of Loving Grace*。说实话，读到生物和药物发现那一段的时候，我整个人都坐直了。

## 关于「压缩的21世纪」

Dario 提出了一个让我很兴奋的概念：AI 可能会把人类生物学未来 50-100 年的进展，压缩到 5-10 年里完成。他称之为 "compressed 21st century"。

作为一个每天在 Scripps 做 AI drug discovery 的 PhD 学生，这个概念对我来说不是抽象的——它就是我每天在实验室里感受到的东西的放大版。我们组里用 AI 做分子生成、做靶点预测、做 binding affinity 的建模，每一次模型跑出一个好的结果，都能感觉到：嗯，这个东西真的在 work。但 Dario 说的是更大的图景——不仅仅是用 AI 分析数据，而是让 AI 成为一个 virtual biologist，能设计实验、跑实验、迭代假说。

这一点他说得特别好：**"I am not talking about AI as merely a tool to analyze data."** 太多人把 AI 在生物领域的角色想窄了。AlphaFold 已经证明了 AI 能做到人类几十年物理建模做不到的事，但那只是开始。

## 药物发现的瓶颈

读到他分析 limiting factors 的时候，我疯狂点头。他说的那几个瓶颈——物理世界的速度限制（细胞培养要时间，动物实验要好几个月）、数据质量问题、内在复杂性——这些就是我每天面对的东西。

我现在做的工作很大一部分就是在跟这些瓶颈搏斗。分子设计可以很快，但 wet lab validation 永远是那个 rate-limiting step。有时候一个 compound 的合成路线就要好几周，然后 assay 又要几周。AI 可以在几秒钟内生成一千个候选分子，但验证它们？那是另一个故事了。

不过 Dario 有一个洞察让我觉得很有启发：他说真正推动生物学进步的是少数几个关键发现——CRISPR、mRNA 疫苗、CAR-T 这些。这些发现的共同点是它们都是 **broad measurement tools or techniques**，能够 cut through complexity。而这些发现的 rate of discovery 是可以被 AI 加速的，因为它们更多地依赖 ingenuity 而不是 brute-force 实验。

这让我重新思考自己的研究方向。也许最有价值的不是优化某个具体的分子，而是发明新的方法论——新的 AI-driven experimental paradigm。

## 关于不平等的焦虑

Dario 花了很大篇幅讨论发展中国家能不能也享受到 AI 带来的好处。这一部分让我有点 emotional。我来自中国，我在美国做 cutting-edge AI research，这种 privilege 我是很清楚的。如果 AI 真的能让人类寿命翻倍、消灭大部分癌症，但这些技术只有发达国家的人能用到，那算什么胜利？

他提到了一个我很认同的观点：生物医学创新在部署方面其实有不错的 track record。不像核能被监管和恐惧拖慢了几十年，好的药物一旦被开发出来，通常会被广泛使用。mRNA 疫苗就是个例子——从开发到全球部署，速度快得惊人。

但我也在想，AI drug discovery 本身可能就能帮助解决这个问题。如果 AI 能大幅降低药物开发的成本（现在一个新药从发现到上市平均要花 26 亿美元），那 affordable medicine 就不再是一个空洞的口号了。

## 一些个人感受

读完整篇文章，最让我感动的其实是 Dario 的 tone。作为 Anthropic 的 CEO，他花了大量时间谈论 AI 风险，以至于很多人以为他是个 doomer。但这篇文章展示了他的另一面——一个真正相信技术可以让世界变好的人，只是他觉得我们必须先把风险管好。

**"Fear is one kind of motivator, but it's not enough: we need hope as well."**

这句话我读了好几遍。做 AI safety 的朋友们经常给我一种世界末日的感觉，但 Dario 说得对——你不能只靠恐惧驱动。我们需要一个值得为之奋斗的愿景。

作为一个在 AI 和生物交叉领域工作的人，我觉得自己站在一个很特别的位置。每天写代码、调模型、读文献的时候，偶尔会忘记 big picture。但读完这篇文章，我又被提醒了：我们做的事情，potentially 可以改变无数人的生命。

这不是 hype，这是 responsibility。

好了，写到这里该去看 paper 了。Lab meeting 明天见。☀️

---

*原文链接: [Machines of Loving Grace](https://darioamodei.com/machines-of-loving-grace) — Dario Amodei, October 2024*
