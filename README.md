# 平均场博弈数值方法：原稿与中文译稿

本仓库保存 Mathieu Lauriere 的讲义 *Numerical Methods for Mean Field Games and Mean Field Type Control* 及其中文研究译稿。

## 内容

- `original/mathieu_lauriere_numerical_methods_mfg.pdf`：英文原稿 PDF。
- `original/source/`：英文 LaTeX 源稿、参考文献表与原始插图。
- `translation/平均场博弈与平均场型控制的数值方法_中文译稿.pdf`：71 页中文 PDF。
- `translation/lauriere_AMS20_zh.tex`：中文 LaTeX 源稿。
- `translation/术语表.md`：核心术语的统一译法。
- `translation/structure_audit.json`：英中文档结构一致性审计。

原文来源：[arXiv:2106.06231](https://arxiv.org/abs/2106.06231)。

## 编译

中文稿需要 XeLaTeX、`ctex` 及正文引用的数学宏包。在 `translation` 目录中依次运行：

```text
xelatex lauriere_AMS20_zh.tex
makeindex lauriere_AMS20_zh.idx
xelatex lauriere_AMS20_zh.tex
xelatex lauriere_AMS20_zh.tex
```

中文 PDF 已使用 XeLaTeX 完成编译和抽样检查，共 71 页。结构审计确认英中文稿的章节、标签、交叉引用、文献引用、插图及 LaTeX 环境数量一致。

## 版权说明

英文原稿版权归原作者所有。本仓库为私有研究存档；中文稿属于非官方研究译稿，尚未经过原作者授权或数学领域专家逐句审校，不应公开传播、出版或用于商业用途。正式引用请以英文原文为准。
