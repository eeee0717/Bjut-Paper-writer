---
theme: default
layout: cover
title: Welcome to LaTeX
---

# Welcome to LaTeX!

<img src="https://www.latex-project.org/img/latex-project-logo.svg" alt="SVG Image" width="300">

---


# What is LaTeX?
LaTeX 是一种优质的<span class="text-orange-500/90 font-bold">排版系统</span>，专门设计用于生成技术与科学类文档。

<div grid="~ cols-2 gap-4" m-10>
<div>

## LaTeX vs. Word
| LaTeX | Word |
|:---:|:---:|
| 使用语法编排 | 🌟所见即所得 |
| 专注于内容 | 专注于样式 |
| 适合长文档 | 适合短文档 |
| 适合数学公式 | 适合纯文本排版 |

</div>
<div>
<!--TODO: 渐变展开 -->
<div class="relative w-[200px] h-[200px] m-b-2">
  <img src="/images/example3.png" alt="图片1" class="absolute left-5 origin-bottom-left rotate-[-5deg]">
  <img src="/images/example2.png" alt="图片2" class="absolute bottom left-30 origin-bottom-left rotate-[0deg]">
  <img src="/images/example1.png" alt="图片3" class="absolute left-55 origin-bottom-left rotate-[10deg]">
</div>
</div>
</div>
---

# How to use LaTeX?

<div grid="~ cols-2 gap-4">
<div>
<div text-center>

## LaTeX Code

</div>

```latex {2|6-7|all}
\begin{aligned}
\nabla \cdot \vec{E} &= \frac{\rho}{\varepsilon_0} \\

\nabla \cdot \vec{B} &= 0 \\

\nabla \times \vec{E} &= -\frac{\partial\vec{B}}\\
{\partial t} \\

\nabla \times \vec{B} &= \mu_0\vec{J} \\ 
+ \mu_0\varepsilon_0\\
\frac{\partial\vec{E}}{\partial t}
\end{aligned}
```
</div>

<div>
<div text-center>

## LaTeX Output
</div>
<div>
$$ {1|3|all}{at:1}
\begin{aligned}
\nabla \cdot \vec{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \vec{B} &= 0 \\
\nabla \times \vec{E} &= -\frac{\partial\vec{B}}{\partial t} \\
\nabla \times \vec{B} &= \mu_0\vec{J} + \mu_0\varepsilon_0\frac{\partial\vec{E}}{\partial t}
\end{aligned}
$$
</div>
</div>
</div>
<div m-t-10>

> 相比于在Word中编写公式，即使使用MathType等插件，仍需要多次点击才可完成，<span v-mark.red="3">步骤繁琐、效率较低。</span>
</div>

---

# Awesome Tools
## Overleaf——LaTeX 在线编辑器


<div grid="~ cols-2 gap-4">


<div>

<video class="h-80%" muted autoplay loop>
  <source src="https://www.overleaf.com/img/website-redesign/visual-editor.mp4" type="video/mp4"/>
</video>

</div>

<div>

<video class="h-80%" muted autoplay loop>
  <source src="/images/template.mp4" type="video/mp4"/>
</video>
</div>
</div>



---

# Awesome Tools
## LaTeX with AI

<div grid="~ cols-2 gap-4">


<img v-click src="/images/chatgpt.png" />

<!-- right -->
<div >
<div v-click>
```latex
H_{\text{mol}} = \sum_{n=1}^{N_{\text{mol}}} \\
\left[ \sum_{i=1}^{3} \left( \frac{1}{2} G_{ii}^{(0)} \\
p_{n,i}^2 + V_{n,i}(q_{n,i}) \right) + \sum_{i,j}^{3} \\
G_{ij}^{(0)} p_{n,i} p_{n,j} \right],\\
H_{\text{F}} = \sum_k \left[ \frac{1}{2} P_k^2 + \\
\frac{1}{2} \omega_k^2 \left( Q_k - \\
\frac{\lambda_k}{\omega_k} \boldsymbol{\mu} \\
\cdot \boldsymbol{\xi} \right)^2 \right].
```
</div>
<div class="text-sm" v-click>
$$
H_{\text{mol}} = \sum_{n=1}^{N_{\text{mol}}} \left[ \sum_{i=1}^{3} \left( \frac{1}{2} G_{ii}^{(0)} p_{n,i}^2 + V_{n,i}(q_{n,i}) \right) \\
 + \sum_{i,j}^{3} G_{ij}^{(0)} p_{n,i} p_{n,j} \right],\\
H_{\text{F}} = \sum_k \left[ \frac{1}{2} P_k^2 + \frac{1}{2} \omega_k^2 \left( Q_k - \frac{\lambda_k}{\omega_k} \boldsymbol{\mu} \cdot \boldsymbol{\xi} \right)^2 \right].

$$
</div>

</div>

</div>

---
layout: center
class: text-center
---

# Thanks

<PoweredBySlidev class="text-sm" />

