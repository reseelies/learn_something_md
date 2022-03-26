<a id="0" href="https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">官方文档</a>

## <span id="menu">目录</span>：  
* [0.官方文档](#0)  
* [1.行内公式与独行公式](#1)  
* [2.希腊字母](#2)
* * [2.1 小写希腊字母](#2.1)
* * [2.2 大写希腊字母](#2.2)
* [3.字母修饰](#3)
* * [3.1 上下角标](#3.1)
* * [3.2 上下标](#3.2)
* * [3.3 字体](#3.3)
* * [3.4 分组](#3.4)
* * [3.5 括号](#3.5)
* [4.运算符号](#4)
* * [4.1 四则运算](#4.1)
* * [4.2 逻辑运算](#4.2)
* [5.大型运算符号](#5)
* * [5.1 求和、极限和积分](#5.1)
* * [5.2 分式和根号](#5.2)
* [6.特殊符号](#6)
* * [6.1 数学符号](#6.1)
* * [6.2 箭头](#6.2)
* [7.矩阵](#7)
* * [7.1 基本语法](#7.1)
* * [7.2 矩阵边框](#7.2)
* * [7.3 省略号](#7.3)
* * [7.4 阵列](#7.4)
* * [7.5 方程组](#7.5)
* [8.特殊函数](#8)
* [9.特殊用法](#special)

<h2 id="1">行内公式与行间公式</h2>

|描述|符号|效果|
|:--|:--|:--|
|行内公式|`$x=1$`|$x=1$|
|行间公式|`$$x=1$$`|$$x=1$$|
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="2">希腊字母</h2>
<h3 id="2.1">小写希腊字母</h2>

|字母|指令|字母|指令|
|:--|:--|:--|:--|
|$\alpha$|`\alpha`|$\beta$|`\beta`|
|$\gamma$|`\gamma`|$\delta$|`\delta`|
|$\epsilon$|`\epsilon`|$\zeta$|`\zeta`|
|$\eta$|`\eta`|$\theta$|`\theta`|
|$\iota$|`\iota`|$\kappa$|`\kappa`|
|$\lambda$|`\lambda`|$\mu$|`\mu`|
|$\nu$|`\nu`|$\xi$|`\xi`|
|$\pi$|`\pi`|$\rho$|`\rho`|
|$\sigma$|`\sigma`|$\tau$|`\tau`|
|$\upsilon$|`\upsilon`|$\phi$|`\phi`|
|$\chi$|`\chi`|$\psi$|`\psi`|
|$\omega$|`\omega`|||

<h3 id="2.2">大写希腊字母</h3>

|字母|指令|字母|指令|
|:--|:--|:--|:--|
|$\Alpha$|`\Alpha`|$\Beta$|`\Beta`|
|$\Gamma$|`\Gamma`|$\Delta$|`\Delta`|
|$\Epsilon$|`\Epsilon`|$\Zeta$|`\Zeta`|
|$\Eta$|`\Eta`|$\Theta$|`\Theta`|
|$\Iota$|`\Iota`|$\Kappa$|`\Kappa`|
|$\Lambda$|`\Lambda`|$\Mu$|`\Mu`|
|$\Nu$|`\Nu`|$\Xi$|`\Xi`|
|$\Pi$|`\Pi`|$\Rho$|`\Rho`|
|$\Sigma$|`\Sigma`|$\Tau$|`\Tau`|
|$\Upsilon$|`\Upsilon`|$\Phi$|`\Phi`|
|$\Chi$|`\Chi`|$\Psi$|`\Psi`|
|$\Omega$|`\Omega`|||
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="3">字母修饰</h2>
<h3 id="3.1">上下角标</h3>

**上角标**：`x^2` -- $x^2$  
**下角标**：`x_1` -- $x_1$  
**上下角标同时出现**：`C_n^2` -- $C_n^2$  

<h3 id="3.2">上下标</h3>

|名称|符号|指令|
|:-:|:-:|:-:|
|**上标**|||
|矢量|$\vec a$|`\vec a`|
|矢量|$\overrightarrow{xy}$|`\overrightarrow{xy}`|
|平均数算符|$\bar x$|`\bar x`|
|平均数算符|$\overline x$|`\overline x`|
|估计值算符|$\hat x$|`\hat x`|
|估计值算符|$\widehat x$|`\widehat x`|
||$\check x$|`\check x`|
||$\breve x$|`\breve x`|
||$\acute x$|`\acute x`|
||$\grave x$|`\grave x`|
||$\mathring x$|`\mathring x`|
|颚化符号|$\tilde x$|`\tilde x`|
|颚化符号|$\widetilde x$|`\widetilde x`|
|一阶导数|$\dot x$|`\dot x`|
|二阶导数|$\ddot x$|`\ddot x`|
|**下标**|||
|下划线|$\underline x$|`\underline x`|

<h3 id="3.3">字体</h3>

**字体风格强制转化**：行内公式和行间公式的显示风格不同，可使用`\displaystyle`强制将行内公式以行间公式的风格显示；`\textstyle`强制将行间公式以行内公式的风格显示。  
**Typewriter**：`\mathtt{ABCDEFG}` -- $\mathtt{ABCDEFG}$  
**Blackboard Bold**：`\mathbb{ABCDEFG}` -- $\mathbb{ABCDEFG}$  
**Sans Serif**：`\mathsf{ABCDEFG}` -- $\mathsf{ABCDEFG}$

<h3 id="3.4">分组</h3>

使用`{}`进行分组，如 `10^{10}` -- $10^{10}$，
`10^10` -- $10^10$  
**组合公式**：  
* 带括号的：`{上位公式 \choose 下位公式}` -- ${上位公式 \choose 下位公式}$  
* 不带括号的：`{上位公式 \atop 下位公式}` -- ${上位公式 \atop 下位公式}$  

<h3 id="3.5">括号</h3>

**小括号**：`()`  
**中括号**：`[]`  
**尖括号**：`\langle, \rangle` -- $\langle, \rangle$  
使用`left( 或 \right)`使符号大小与相邻公式相适应  
**上大括号**：`\overbrace{x+y+z}` -- $\overbrace{x+y+z}$  
**下大括号**：`\underbrace{x+y+z}` -- $\underbrace{x+y+z}$  
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="4">运算符号</h2>
<h3 id="4.1">四则运算</h3>

|运算|符号|指令|
|:-:|:-:|:-:|
|加减|$\pm$|`\pm`|
|减加|$\mp$|`\mp`|
|乘|$\times$|`\times`|
|点乘|$\cdot$|`\cdot`|
|星乘|$\ast$|`\ast`|

<h3 id="4.2">逻辑运算</h3>

|运算|符号|指令|
|:-:|:-:|:-:|
|大于等于|$\geq$|`\geq`|
|大于等于|$\geqq$|`\geqq`|
|小于等于|$\leq$|`\leq`|
|小于等于|$\leqq$|`\leqq`|
|不等于|$\neq$|`\neq`, `\not=`|
|不大于等于|$\ngeq$|`\ngeq`, `\not\geq`|
|不小于等于|$\nleq$|`\nleq`, `\not\leq`|
|约等于|$\approx$|`\approx`|
|恒等于|$\equiv$|`\equiv`|
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="5">大型运算符号</h2>
<h3 id="5.1">求和、极限和积分</h3>

**求和**：`\sum`  
示例：`\sum_{i=1}^N{x_i}` -- $\sum_{i=1}^N{x_i}$  
$$\sum_{i=1}^N{x_i}$$  
**极限**：`\lim`  
示例：`\lim_{x\to 0}` -- $\lim_{x\to 0}$  
$$\lim_{x\to 0}$$  
**积分**：`\int`  
示例：`\int_0^1{xdx}` -- $\int_0^1{xdx}$  
$$\int_0^1{xdx}$$  

<h3 id="5.2">分式和根式</h3>

**分式**：`\frac{分子}{分母}` -- $\frac{分子}{分母}$  
$$\frac{分子}{分母}$$  
`{分子}\over{分母}` -- ${分子}\over{分母}$  
**根式**：`\sqrt[根数]{被开根数}` -- $\sqrt[根数]{被开根数}$  
$$\sqrt[根数]{被开根数}$$  
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="6">特殊符号</h2>
<h3 id="6.1">数学符号</h3>

|名称|符号|指令|
|:--:|:--:|:--:|
|无穷大|$\infty$|`\infty`|
|虚数|$\imath$, $\jmath$|`\imath`, `\jmath`|
|并集|$\cup$|`\cup`|
|交集|$\cap$|`\cap`|
|包含于|$\subset$|`\subset`|
|真包含于|$\subseteq$|`\subseteq`|
|包含|$\supset$|`\supset`|
|属于|$\in$|`\in`|
|不属于|$\notin$|`\notin`|
|空集|$\varnothing$, $\emptyset$|`\varnothing`, `\emptyset`|
|全称量词|$\forall$|`\forall`|
|存在量词|$\exist$|`\exists` or `\exist`|
|否定量词|$\lnot$|`\lnot`|
|梯度算子|$\nabla$|`\nabla`|
|偏导符号|$\partial$|`\partial`|
|空格|$a\ b$|`a\ b`|
|一个tab|$a\quad b$|`a\quad b`|
|两个tab|$a\qquad b$|`a\qquad b`|

<h3 id="6.2">箭头</h3>

**上箭头**：`\uparrow` -- $\uparrow$
`\Uparrow` -- $\Uparrow$
**下箭头**：`\downarrow` -- $\downarrow$
`\Downarrow` -- $\Downarrow$
**左箭头**：`\leftarrow` -- $\leftarrow$
`\Leftarrow` -- $\Leftarrow$
**右箭头**：`\rightarrow` -- $\rightarrow$
`\Rightarrow` -- $\Rightarrow$
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="7">矩阵</h2>
<h3 id="7.1">基本语法</h3>

起始标记：`\begin{matrix}`，结束标记：`\end{matrix}`，每一行末尾标记：`\\`，行间元素之间以`&`分割。  
示例：
$$\begin{matrix}
    1&0&0\\
    0&1&0\\
    0&0&1\\
\end{matrix}$$

<h3 id="7.2">矩阵边框</h3>

在起始、结束标记处用下列词替换 `matrix`：  
小括号边框：`pmatrix`  
中括号边框：`bmatrix`  
大括号边框：`Bmatrix`  
单竖线边框：`vmatrix`  
双竖线边框：`Vmatrix`  
示例：  
$$\begin{bmatrix}
    1&0&0\\
    0&1&0\\
    0&0&1\\
\end{bmatrix}$$

<h3 id="7.3">省略号</h3>

底端对齐横省略号：`\ldots`  
中线对齐横省略号：`\cdots`  
竖省略号：`\vdots`  
斜省略号：`\ddots`  
示例：  
$$\begin{bmatrix}
{a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\
{a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\
{\vdots}&{\vdots}&{\ddots}&{\vdots}\\
{a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\
\end{bmatrix}$$

<h3 id="7.4">阵列</h3>

* 起始、结束处以`{array}`声明；  
* 对齐方式：在`{array}`后以`{}`逐行统一声明；  
* * 左对齐 -- l；居中 -- c；右对齐 -- r；
* * 竖直线：在声明对齐方式时，插入`|`建立竖直线；  
* 插入水平线：`\hline`  

示例：
$$\begin{array}{c|lll}
{↓}&{a}&{b}&{c}\\
\hline
{R_1}&{c}&{b}&{a}\\
{R_2}&{b}&{c}&{c}\\
\end{array}$$

<h3 id="7.5">方程组</h3>

起始、结束处以`{cases}`声明  
示例：
$$\begin{cases}
a_1x+b_1y+c_1z=d_1\\
a_2x+b_2y+c_2z=d_2\\
a_3x+b_3y+c_3z=d_3\\
\end{cases}$$
<p align="right"><a href="menu">返回目录</a></p>

<h2 id="8">特殊函数</h2>

`\函数名`  
|函数|指令|
|:--|:--|
|sin|$\sin$|
|cos|$\cos$|
|ln|$\ln$|
略...  

<h2 id="special">特殊用法</h2>

**标签**：`\tag{}`, `\label{}` -- 这个是给公式做标号使用的，且必须是带等号的式子，还只能是行间公式。`y=ax+b\tag{*}` -- $$y=ax+b\tag{*}$$  
`\label{} -- eqref{} -- \ref{}`组合在Markdown中无法使用  
**`\stackrel{a}{b}`**：这个能把a放在b上，$\stackrel{s=2}{=}$