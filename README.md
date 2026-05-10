# Attention Is All You Need 读书报告

**报告人：** 黄鑫 | **日期：** 2026年5月9日 | **原文：** [arXiv:1706.03762](https://arxiv.org/abs/1706.03762)

---

## 📖 关于报告

本报告对 Google Brain 2017年论文《Attention Is All You Need》进行深度解读，从 RNN/CNN 困境到 Transformer 架构设计，从 BLEU 分值到 ChatGPT 时代，完整呈现一次 AI 范式转移的过程。



---

## 🏗️ 核心架构

| 组件 | 说明 |
|:---|:---|
| 缩放点积注意力 | $\mathrm{Attention}(Q,K,V) = \mathrm{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V$ |
| 多头注意力 | 8个并行头，分而治之捕获不同特征 |
| 位置编码 | 正弦/余弦函数，注入顺序信息 |
| 残差+LayerNorm | 稳定训练，加速收敛 |

---

## 📁 仓库结构
