title: 博客中Markdown公式编辑问题
categories: Technique
tags:
  - markdown
  - latex
  - github-pages
date: 2013-11-21 00:00:00
---

发现[hexo-math](https://github.com/akfish/hexo-math)蛮好用的。测试一下 

### The Lorentz Equations

{% math %}
\begin{aligned}
\dot{x} = \sigma(y-x) \\
\dot{y} = \rho x - y - xz \\
\dot{z} = -\beta z + xy
\end{aligned}
{% endmath %}

### The Cauchy-Schwarz Inequality

{% math %}\begin{aligned}
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\end{aligned}{% endmath %}

### A Cross Product Formula

{% math %}
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j}	& \mathbf{k} \\
\frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0
\end{vmatrix}
{% endmath %}

### The probability of getting k heads when flipping n coins is

{% math %}\begin{aligned}
P(E) = {n \choose k} p^k (1-p)^{ n-k}
\end{aligned}{% endmath %}

### An Identity of Ramanujan

{% math %}
\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} =
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
{1+\frac{e^{-8\pi}} {1+\ldots} } } }
{% endmath %}

### A Rogers-Ramanujan Identity

{% math %}
1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots =
\prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})},
\quad\quad \text{for $|q|<1$}.
{% endmath %}

### Maxwell&rsquo;s Equations

{% math %}
\begin{aligned}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} = \frac{4\pi}{c}\vec{\mathbf{j}} \\
\nabla \cdot \vec{\mathbf{E}}  = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} = 0 \end{aligned}
{% endmath %}

使用过程不知道会不会有bug，日后有碰到再补上。  
