## 项目说明

本项目是用来汇总大家在学习量子计算过程中的各类笔记，以做到取长补短，互通有无。

就内容而言，没有什么特殊要求。无论是个人的学习笔记，还是研读过的优秀学习资料，任何值得记录下来的内容都可放进来。

下面是目前的内容分类：

- PART I - `Notes of NC book` [Nielsen 和 Chuang - 2011 - Quantum Computation and Quantum Information](https://profmcruz.wordpress.com/wp-content/uploads/2017/08/quantum-computation-and-quantum-information-nielsen-chuang.pdf)  的前几章是比较全面的基础内容汇总。我们可以先以这本书为主线，总结笔记。同时补充一些别的资料中的内容，最终形成我们自己的理解。
- PART II - `Notes of NC book` 也可以是自己读过的paper的详细介绍，比如相关的想法或者自己写的证明过程等
- PART III - `Notes of NC book` 本项目的最终目的是帮助大家共同学习，而不是出版，所以可以直接复制他人的高质量内容。

核心文档main.tex正文只支持英文。有高质量的中文内容也请先找GPT翻译成英文。

## latex模板说明

主要文档是 `main.tex`

本项目使用模板 [Legrand Orange Book Class](https://www.latextemplates.com/template/legrand-orange-book)。该模板的原始`main.tex` 被重名为 `main_original.tex` 并放在`.backup` 文件夹中。为了保证文档风格统一，尽量使用该模板自带各类数学环境。该模板中可用的常见数学环境如下：

```latex
\begin{theorem}[name of theorem]
\begin{definition}[Definition name]
\begin{notation}
\begin{remark}
\begin{corollary}[Corollary name]
\begin{proposition}[Proposition name]
\begin{example}[Example name]
\begin{exercise}
\begin{problem}
```

如果有需求，可以自行定义新的数学环境。并将其说明写到本readme文档中。

## 其他工作说明

overleaf常用快捷键（效率提升+10%）
https://www.overleaf.com/latex/templates/overleaf-keyboard-shortcuts/pphdnzrwmttk.pdf

在overleaf中开启“Visual Editor”模式可以方便地编写latex，做到实时编译，强烈建议打开。（效率提升+30%）

可以使用mathpix直接将多页的pdf文件转化为tex文件或者直接在overleaf中打开。几乎没有识别误差。软件收费，可以找赖帮忙弄。
https://snip.mathpix.com/



