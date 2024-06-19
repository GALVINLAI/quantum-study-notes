# README

本 readme 文件，欢迎大家自由编辑。

github 地址：https://github.com/GALVINLAI/quantum-study-notes

## 项目说明

本项目是用来汇总大家在学习量子计算过程中的各类笔记，以做到取长补短，互通有无。

就内容而言，没有什么特殊要求。无论是个人的学习笔记，还是研读过的优秀学习资料，任何值得记录下来的内容都可放进来。

下面是目前的内容分类：

- Part I - `Notes of NC book/` [Nielsen 和 Chuang - 2011 - Quantum Computation and Quantum Information](https://profmcruz.wordpress.com/wp-content/uploads/2017/08/quantum-computation-and-quantum-information-nielsen-chuang.pdf) 的前几章是比较全面的基础内容汇总。我们可以先以这本书的**第二章**为主线，总结笔记。同时补充一些别的资料中的相关内容，最终形成我们自己的对基础概念的理解。
- Part II - `Notes of Papers/` 中的，是自己研读过的 paper 的详细介绍，另外可以添加一些相关的想法或者自己补充的证明或者说明等。我们目标是，让自己读过的论文有记录，特别是一些高质量或者重点的论文；**当初花几天的时间读懂的论文，下次只要复习自己做的笔记，就能几个小时掌握全部要点和细节**。
- Part III - `Other Notes/` 其他未归类的笔记放这里。

本项目的最终目的是帮助大家共同学习，而不是出版，所以可以直接复制他人的高质量内容。

## Latex 和 overleaf 编译说明

项目的主文档是 `main.tex`，只支持英文和pdfLaTeX编译。有高质量的中文内容也请先找 GPT 翻译成英文。中文一般在注释中使用。

本项目使用模板 [Legrand Orange Book Class](https://www.latextemplates.com/template/legrand-orange-book)。该模板的原始 `main.tex` 被重名为 `main_original.tex` 并放在 `.backup` 文件夹中。为了保证文档风格统一，尽量使用该模板自带各类数学环境。该模板中可用的常见数学环境如下：

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

如果有需求，可以自行定义新的数学环境（在 `LegrandOrangeBook.cls` 中定义，并且按照该模板的方式去自定义）。并将其说明写到本 readme 文档中。

## 其他工作说明

[overleaf 常用快捷键](https://www.overleaf.com/latex/templates/overleaf-keyboard-shortcuts/pphdnzrwmttk.pdf) 例如，`ctrl+/` 可以快速多行 comment 以及 uncomment 代码。（效率提升 +10%）

在 overleaf 中开启 "[Visual Editor]([LaTeX editor features & benefits | Overleaf - Overleaf, Online LaTeX Editor](https://www.overleaf.com/about/features-overview))" 模式可以方便地编写 latex，**做到实时编译**，强烈建议打开。（效率提升 +30%）

可以使用 [mathpix snip web](https://snip.mathpix.com/) 直接将多页的 pdf 文件转化为 tex 文件或者直接在 overleaf 中打开。几乎没有识别误差。软件收费，临时需求可以找赖帮忙弄。

quantikz: Draw quantum circuit diagrams 是专门用来在latex中画出量子电路的包。
请参考学习 [Tutorial on the Quantikz Package](https://mirrors.ibiblio.org/CTAN/graphics/pgf/contrib/quantikz/quantikz.pdf)

add todo notes 通过\usepackage{todonotes}
```latex
\todo{Need to fix my equation here!} % 出现在pdf的右侧
\todo[inline]{Here's an inline comment below the title \& author.} % 出现在pdf的中间
```
另外参考
https://www.overleaf.com/latex/examples/example-formatted-todonotes/qmpbkcqxfgmg
