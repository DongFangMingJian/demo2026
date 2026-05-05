# 微积分下
## 向量代数
### <!--占位符-->
#### 空间直角坐标系
> 正方向符合*右手法则*
**空间中两点的距离公式**
<div class="boxed-formula"><math><mrow><mrow><mo>|</mo><msub><mi>P</mi><mn>1</mn></msub><msub><mi>P</mi><mn>2</mn></msub><mo>|</mo></mrow><mo>=</mo><msqrt><mrow><msup><mrow><mo>(</mo><msub><mi>x</mi><mn>2</mn></msub><mo>-</mo><msub><mi>x</mi><mn>1</mn></msub><mo>)</mo></mrow><mn>2</mn></msup><mo>+</mo><msup><mrow><mo>(</mo><msub><mi>y</mi><mn>2</mn></msub><mo>-</mo><msub><mi>y</mi><mn>1</mn></msub><mo>)</mo></mrow><mn>2</mn></msup><mo>+</mo><msup><mrow><mo>(</mo><msub><mi>z</mi><mn>2</mn></msub><mo>-</mo><msub><mi>z</mi><mn>1</mn></msub><mo>)</mo></mrow><mn>2</mn></msup></mrow></msqrt></mrow></math></div>

#### 向量
##### 向量的夹角
>  **$\theta = (\widehat{\vec{a},\vec{b}})$或$(\widehat{\vec{b},\vec{a}})$**, 且 **$\theta \in [0,\pi]$**
> *特别地*,若$\color{red}{(\widehat{\vec{a},\vec{b}})=0}$(即$\vec{a}与\vec{b}$**方向相同**)或$\color{blue}{(\widehat{\vec{a},\vec{b}})=\pi}$(即$\vec{a}与\vec{b}$*方向相反*),称$\vec{a}与\vec{b}$**平行或共线**
> **零向量$\vec{0}$平行于任意向量**
##### 向量相等
> 两个向量相等记为$\vec{a}=\vec{b}$,表示**向量大小相等,方向相同**
##### 向量的线性运算
###### 向量加法
> **多边形法则**

|*平行四边形法则*|*三角形法则*|
|--:|:--|
|||
> **三角不等式**
<div class="boxed-formula">
  <math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
    <mrow>
      <mtext>|</mtext>
      <mrow>
        <mtext>|</mtext>
        <mover><mi>a</mi><mo>→</mo></mover>
        <mtext>|</mtext>
        <mo>-</mo>
        <mtext>|</mtext>
        <mover><mi>b</mi><mo>→</mo></mover>
        <mtext>|</mtext>
      </mrow>
      <mtext>|</mtext>
      <mo>≤</mo>
      <mtext>|</mtext>
      <mrow>
        <mover><mi>a</mi><mo>→</mo></mover>
        <mo>±</mo>
        <mover><mi>b</mi><mo>→</mo></mover>
      </mrow>
      <mtext>|</mtext>
      <mo>≤</mo>
      <mtext>|</mtext>
      <mover><mi>a</mi><mo>→</mo></mover>
      <mtext>|</mtext>
      <mo>+</mo>
      <mtext>|</mtext>
      <mover><mi>b</mi><mo>→</mo></mover>
      <mtext>|</mtext>
    </mrow>
  </math>
</div>

> *$|\vec{a}+\vec{b}|$和$|\vec{a}-\vec{b}|$的大小关系*

|||
|--:|:--|


###### 数乘
> 定义任意实数$\lambda $与向量$\vec{a}$的乘积是一个向量,记为$\lambda \vec{a}$,*规定*:
> 1\.$|\lambda \vec{a}| = |\lambda|\cdot \vec{a}$
> 2\.当$\lambda > 0时,\lambda \vec{a}与\vec{a}$同方向;
> &nbsp;当$\lambda < 0时,\lambda \vec{a}与\vec{a}$反方向;
> &nbsp;当$\lambda = 0时,\lambda \vec{a}=\vec{0}$; (~~$\lambda \vec{0} = \vec{0}$~~)

|**向量平行充要定理**|设向量$\vec{a} \neq \vec{0}$,则$\vec{b} // \vec{a}$的充要条件是存在唯一的实数$\lambda$,使$\vec{b}= \lambda \vec{a}$|
|--:|:--|
||即$\vec{b} // \vec{a} \iff \vec{b}= \lambda \vec{a}$ |
|*证明必要性*||

###### 运算律
> 
| **结合律** | \(\lambda (\mu \vec{a}) = (\lambda \mu) \vec{a}\) |
|--:|:--|
| **分配律** | \(\lambda (\vec{a} + \vec{b}) = \lambda \vec{a} + \lambda \vec{b}\)<br>\((\lambda + \mu) \vec{a} = \lambda \vec{a} + \mu \vec{a}\) |
| **零因子律** | \(\lambda \vec{a} = \vec{0} \implies \lambda = 0 \text{ 或 } \vec{a} = \vec{0}\) |
| **消去律** | \(k \vec{a} = k \vec{b}, \, k \neq 0 \implies \vec{a} = \vec{b}\)<br>\(k \vec{a} = l \vec{a}, \, \vec{a} \neq \vec{0} \implies k = l\) |
##### 向量的坐标
###### 标准单位向量
> 在空间直角坐标系$Oxyz$中,分别记与$x$轴、$y$轴、$z$轴正向同方向的单位向量为$\vec{i}$、$\vec{j}$、$\vec{k}$
任给向量$\vec{a}$，设$\overrightarrow{OP} = \vec{a}$, $P$的坐标为 $(x, y, z)$

|**标准分解式**| $\vec{a} = x \vec{i} + y \vec{j} + z \vec{k}$|
| --: | :-- |
| | $x\vec{i},y\vec{j},z\vec{k} $称向量$\vec{a}沿三坐标轴方向的分向量$|
||设点 $ A(x_1, y_1, z_1), B(x_2, y_2, z_2) $，则向量$\vec{a} = \overrightarrow{AB} = (x_2 - x_1, y_2 - y_1, z_2 - z_1)$|
|**坐标表示式**|$\vec{a} = (x,y,z)$|
###### 向量线性运算的坐标表示
若 $\vec{a} = (a_x, a_y, a_z), \vec{b} = (b_x, b_y, b_z)$, 则可得：
> $\vec{a} + \vec{b} = (a_x + b_x, a_y + b_y, a_z + b_z)= (a_x + b_x)\vec{i} + (a_y + b_y)\vec{j} + (a_z + b_z)\vec{k};$
> $\vec{a} - \vec{b} = (a_x - b_x, a_y - b_y, a_z - b_z)= (a_x - b_x)\vec{i} + (a_y - b_y)\vec{j} + (a_z - b_z)\vec{k};$
> $\lambda\vec{a} = (\lambda a_x, \lambda a_y, \lambda a_z)= (\lambda a_x)\vec{i} + (\lambda a_y)\vec{j} + (\lambda a_z)\vec{k}.$
###### 向量的模的坐标表示
|**向量$\vec{a}=(x,y,z)$的模**|$\|\vec{a}\|=\sqrt{x^2+y^2+z^2}$|
|--:|:--|
|若$M(x_1, y_1, z_1), N(x_2, y_2, z_2)$，则:|$\overrightarrow{MN} = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}.$
|**单位向量的模**|$\vec{e}_{\vec{a}} = \frac{\vec{a}}{\|\vec{a}\|} = \left( \frac{a_x}{\|\vec{a}\|}, \frac{a_y}{\|\vec{a}\|}, \frac{a_z}{\|\vec{a}\|} \right)$|
###### 向量的方向角、方向余弦及坐标表示
> 非零向量$\vec{a}$与$x$轴、$y$轴、$z$轴正方向所成的夹角,
> 即与标准单位向量$\vec{i},\vec{j},\vec{k}$所成的夹角$\alpha = (\widehat{\vec{a},\vec{i}}),\beta = (\widehat{\vec{a},\vec{j}}),\gamma = (\widehat{\vec{a},\vec{k}})(保证唯一性，范围\in \color{red}{[0,\pi]})$称$\vec{a}$的方向角,
> $\cos \alpha,\cos \beta,\cos \gamma $称$\vec{a}$的方向余弦,
> ~~方向角或方向余弦完全确定了向量$\vec{a}$的方向.~~
> **坐标表示：**
<div class="boxed-formula"><math><mtable><mtr><mtd><mrow><mi>cos</mi><mo>⁡</mo><mi>α</mi><mo>=</mo><mfrac><mi>x</mi><mrow><mo stretchy="true">|</mo><mover><mi>a</mi><mo>→</mo></mover><mo stretchy="true">|</mo></mrow></mfrac><mo>=</mo><mfrac><mi>x</mi><msqrt><mrow><msup><mi>x</mi><mn>2</mn></msup><mo>+</mo><msup><mi>y</mi><mn>2</mn></msup><mo>+</mo><msup><mi>z</mi><mn>2</mn></msup></mrow></msqrt></mfrac></mrow></mtd></mtr><mtr><mtd><mrow><mi>cos</mi><mo>⁡</mo><mi>β</mi><mo>=</mo><mfrac><mi>y</mi><mrow><mo stretchy="true">|</mo><mover><mi>a</mi><mo>→</mo></mover><mo stretchy="true">|</mo></mrow></mfrac><mo>=</mo><mfrac><mi>y</mi><msqrt><mrow><msup><mi>x</mi><mn>2</mn></msup><mo>+</mo><msup><mi>y</mi><mn>2</mn></msup><mo>+</mo><msup><mi>z</mi><mn>2</mn></msup></mrow></msqrt></mfrac></mrow></mtd></mtr><mtr><mtd><mrow><mi>cos</mi><mo>⁡</mo><mi>γ</mi><mo>=</mo><mfrac><mi>z</mi><mrow><mo stretchy="true">|</mo><mover><mi>a</mi><mo>→</mo></mover><mo stretchy="true">|</mo></mrow></mfrac><mo>=</mo><mfrac><mi>z</mi><msqrt><mrow><msup><mi>x</mi><mn>2</mn></msup><mo>+</mo><msup><mi>y</mi><mn>2</mn></msup><mo>+</mo><msup><mi>z</mi><mn>2</mn></msup></mrow></msqrt></mfrac></mrow></mtd></mtr></mtable></math></div>

> **方向余弦的性质**
> > *归一化*
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mrow><msup><mi>cos</mi><mn>2</mn></msup><mi>α</mi><mo>+</mo><msup><mi>cos</mi><mn>2</mn></msup><mi>β</mi><mo>+</mo><msup><mi>cos</mi><mn>2</mn></msup><mi>γ</mi><mo>=</mo><mn>1</mn></mrow></math></div>

> > *构成单位向量*
<div class="boxed-formula"><math display="block"><mrow><msub><mover><mi>e</mi><mo stretchy="false">→</mo></mover><mover><mi>a</mi><mo stretchy="false">→</mo></mover></msub><mo>=</mo><mrow><mo>(</mo><mrow><mi>cos</mi><mi>α</mi></mrow><mo>,</mo><mrow><mi>cos</mi><mi>β</mi></mrow><mo>,</mo><mrow><mi>cos</mi><mi>γ</mi></mrow><mo>)</mo></mrow><mo>=</mo><mrow><mo>(</mo><mfrac><mi>x</mi><mrow><mo>|</mo><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>|</mo></mrow></mfrac><mo>,</mo><mfrac><mi>y</mi><mrow><mo>|</mo><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>|</mo></mrow></mfrac><mo>,</mo><mfrac><mi>z</mi><mrow><mo>|</mo><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>|</mo></mrow></mfrac><mo>)</mo></mrow><mo>=</mo><mrow><mfrac><mn>1</mn><mrow><mo>|</mo><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>|</mo></mrow></mfrac><mo>⁢</mo><mrow><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo></mrow></mrow><mo>=</mo><mfrac><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mrow><mo>|</mo><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>|</mo></mrow></mfrac></mrow></math></div>

###### 向量的夹角及坐标表示
|**向量$\vec{a}与\vec{b}$的夹角满足**| $ \cos \theta = \frac{\vec{a}\cdot \vec{b}}{\lvert \vec{a}\rvert \lvert \vec{b}\rvert}$,$\theta \in [0,\pi] $ |
|--:|:--|
|若$\vec{a} = (a_x, a_y, a_z),\vec{b} = (b_x, b_y, b_z)$,则|$$\cos\theta = \frac{a_x b_x + a_y b_y + a_z b_z}{\sqrt{a_x^2 + a_y^2 + a_z^2}\,\sqrt{b_x^2 + b_y^2 + b_z^2}}$$|
###### 向量的投影
> 设$\theta = (\widehat{\vec{a},\vec{b}})$,定义向量$\vec{b}$在向量$\vec{a}$上的投影$\color{red}{\operatorname{Prj}_{\vec{a}} \vec{b} = |\vec{b}| \cos \theta}$
> ~~$\vec{b}$的投影与$\vec{a}$的长度$(即|\vec{a}|)$无关,$\vec{a}$只为投影提供方向~~
> > 若$\theta \in [0,\frac{\pi}{2})$,则$\operatorname{Prj}_{\vec{a}} \vec{b} > 0$;
> > 若$\theta = \frac{\pi}{2}$,则$\operatorname{Prj}_{\vec{a}} \vec{b} = 0$;
> > 若$\theta \in (\frac{\pi}{2},\pi]$,则$\operatorname{Prj}_{\vec{a}} \vec{b} < 0$.

> 由向量点积亦得$\color{red}{\operatorname{Prj}_{\vec{a}} \vec{b} = |\vec{b}| \cos \theta} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|} = \vec{e}_{\vec{a}}\cdot \vec{b}$
##### 向量的乘法
###### 点积
|**定义**| $\vec{a} \cdot\vec{b} = \lvert \vec{a} \rvert \cdot \lvert \vec{b}\rvert \cdot \cos \theta$,其中$\theta = (\widehat{\vec{a},\vec{b}})$ |
|--:|:--|
||~~点积的结果是一个数~~|
|*与投影的关系*|$\vec{a} \cdot \vec{b} = \lvert \vec{a}\rvert \cdot \operatorname{Prj}_{a} \vec{b} = \lvert \vec{b}\rvert \cdot \operatorname{Prj}_{b} \vec{a}$|
|*坐标运算*|$\vec{a} \cdot \vec{b} =(a_x, a_y, a_z)\cdot(b_x, b_y, b_z)= a_x b_x + a_y b_y + a_z b_z$|

> 点积的**运算律**

|*幂律*| $\vec{a} \cdot \vec{a} = \lvert \vec{a}\rvert ^2$ *约定：*$\vec{a}^2 = \vec{a} \cdot \vec{a} = \lvert \vec{a} \rvert^2$|
|--:|:--|
|*零元*|$\vec{a} \cdot \vec{0} = \vec{0} \cdot \vec{a} = 0$|
|*交换律*|$\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$|
|*分配律*|$(\vec{a} + \vec{b}) \cdot \vec{c} = \vec{a} \cdot \vec{c} + \vec{b} \cdot \vec{c}$|
|*数乘结合律*|$(\lambda \vec{a}) \cdot (\mu \vec{b}) = \lambda \mu (\vec{a} \cdot \vec{b})$|

|**两向量垂直的充要条件定理**|**$\vec{a} \perp \vec{b} \iff \vec{a} \cdot\vec{b} = 0 $**|
|--:|:--|
|*证明*||
|**坐标形式表述**||

<div class="boxed-formula"><math  display="block"><mtable><mtr><mtd><mrow><mtext>若</mtext><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>=</mo><mo>(</mo><msub><mi>a</mi><mi>x</mi></msub><mo>,</mo><msub><mi>a</mi><mi>y</mi></msub><mo>,</mo><msub><mi>a</mi><mi>z</mi></msub><mo>)</mo><mo>,</mo><mover><mi>b</mi><mo stretchy="false">→</mo></mover><mo>=</mo><mo>(</mo><msub><mi>b</mi><mi>x</mi></msub><mo>,</mo><msub><mi>b</mi><mi>y</mi></msub><mo>,</mo><msub><mi>b</mi><mi>z</mi></msub><mo>)</mo></mtr></mtd><mtable><mtr><mtd><mtext>则</mtext><mover><mi>a</mi><mo stretchy="false">→</mo></mover><mo>⟂</mo><mover><mi>b</mi><mo stretchy="false">→</mo></mover><mtext>的充要条件是</mtext><msub><mi>a</mi><mi>x</mi></msub><msub><mi>b</mi><mi>x</mi></msub><mo>+</mo><msub><mi>a</mi><mi>y</mi></msub><msub><mi>b</mi><mi>y</mi></msub><mo>+</mo><msub><mi>a</mi><mi>z</mi></msub><msub><mi>b</mi><mi>z</mi></msub><mo>=</mo><mn>0</mn></mtable></mtr></mtd></mrow></mtable></math></div>

###### 叉积
> 设$\vec{a},\vec{b}$是两个向量,*规定*$\vec{a}与\vec{b}$的**向量积是一个向量**,记为$\vec{a} \times \vec{b}$
> > $\color{red}{\vec{a} \times \vec{b} = \begin{vmatrix}a_y & a_z \\b_y & b_z \end{vmatrix} \vec{i} +\begin{vmatrix}a_z & a_x \\b_z & b_x \end{vmatrix} \vec{j}+\begin{vmatrix}a_x & a_y \\b_x & b_y \end{vmatrix} \vec{k}} $(轮换对称)
> > $或\color{red}{\vec{a} \times \vec{b} = \begin{vmatrix}\vec{i}&\vec{j}&\vec{k} \\ a_x&a_y&a_z\\ b_x&b_y&b_z\end{vmatrix}}$

|$\vec{a} \times \vec{b}$的**模** | $\lvert\vec{a} \times \vec{b}\rvert = \lvert \vec{a}\rvert \lvert \vec{b}\rvert \sin \theta (\theta = (\widehat{\vec{a},\vec{b}}))$ |
|--:|:--|
|$\vec{a} \times \vec{b}$的**方向**|$\vec{a} \times \vec{b}$同时垂直于$\vec{a}和\vec{b},且\vec{a}, \vec{b},\vec{a} \times \vec{b}$符合*右手法则*|
|叉积的*几何意义*|$\lvert\vec{a} \times \vec{b}\rvert$表示以 **$\vec{a}, \vec{b}$为邻边的平行四边形的面积** |

> 叉积的**运算律**

|*反交换律*|$\vec{a} \times \vec{b} = -\vec{b} \times \vec{a}$|
|--:|:--|
|*分配律*|$\vec{a} \times (\vec{b} + \vec{c}) = \vec{a} \times \vec{b} + \vec{a} \times \vec{c}$|
|*数乘结合律*|$(\lambda \vec{a}) \times (\mu \vec{b}) = \lambda \mu (\vec{a} \times \vec{b})$|

> > ~~运用运算律要保证两向量叉积的顺序不变.~~

|**两向量平行的充要条件定理**|**$\vec{a} // \vec{b} \iff \vec{a} \times \vec{b} = 0 $**|
|--:|:--|
|*证明*||

> 标准单位向量间的叉积运算：
> 
||$\vec{i} \times \vec{j}$|$\vec{j} \times \vec{k}$|$\vec{k} \times \vec{i}$|
|--:|-|-|-|
|*轮换对称*|$=\vec{k}$|$=\vec{i}$|$=\vec{j}$|
###### 混合积
|**定义**|设$\vec{a},\vec{b},\vec{c}$是三个向量,*先叉积$\vec{a} \times \vec{b}$*,*再作$\vec{a} \times \vec{b}与\vec{c}$点积*,得到的数$\color{red}{(\vec{a} \times \vec{b})\cdot \vec{c}}$称向量$\vec{a},\vec{b},\vec{c}$的**混合积**,记为$[\vec{a} \: \vec{b} \: \vec{c}] $|
|--:|:--|
|混合积的*几何意义*|$\lvert [\vec{a} \: \vec{b} \: \vec{c}] \rvert $是以$\vec{a},\vec{b},\vec{c}$为相邻三棱的平行六面体的*体积*|

> > $\color{red}{[\vec{a} \: \vec{b} \: \vec{c}]  = (\vec{a} \times \vec{b})\cdot \vec{c} = \begin{vmatrix}a_y & a_z \\b_y & b_z \end{vmatrix} c_x +\begin{vmatrix}a_z & a_x \\b_z & b_x \end{vmatrix} c_y+\begin{vmatrix}a_x & a_y \\b_x & b_y \end{vmatrix} c_z} $
> > $即\color{red}{[\vec{a} \: \vec{b} \: \vec{c}]  = (\vec{a} \times \vec{b})\cdot \vec{c} = \begin{vmatrix} a_x&a_y&a_z\\ b_x&b_y&b_z \\ c_x&c_y&c_z \end{vmatrix}}$

|*性质*||~~由行列式的性质得到~~|
|--:|:--|:--|
|**轮换对称性**|**$[\vec{a} \: \vec{b} \: \vec{c}] = [\vec{b} \: \vec{c} \: \vec{a}] =[ \vec{c} \:\vec{a} \: \vec{b}]  $**|~~行列式经过两次换行不改变式的值~~|
|**零值性质**|有两个相同向量的混合积的值为0|~~有两行相同的行列式的值为0~~|
||$[\vec{a} \: \vec{a} \: \vec{b}] = 0 $||


> **三向量共面的充要条件定理**
<div class="boxed-formula"><!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>行列式（竖线长度自由控制）</title>
    <style>
        /* 行列式容器：用border做竖线，padding控制竖线长度 */
        .det-container {
            display: inline-flex; /* 行内弹性布局，适配数学排版 */
            border-left: 1.5px solid black; /* 左侧竖线：宽度/颜色可自定义 */
            border-right: 1.5px solid black; /* 右侧竖线：和左侧保持一致 */
            padding: 8px 5px; /* 关键：上下padding控制竖线长度，数值越大竖线越长；左右padding是内容间距 */
            vertical-align: middle;
        }
        /* 行列式表格：只需控制内部排版 */
        .det-table {
            border-collapse: collapse; /* 合并单元格间距，排版更紧凑 */
        }
        /* 可选：调整单元格间距，让内容更美观 */
        .det-table mtd {
            padding: 2px 8px; /* 单元格内边距：上下/左右 */
        }
    </style>
    <!-- 引入MathJax确保跨浏览器兼容 -->
    <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<body>
    <math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>三向量</mtext><mover><mi>a</mi><mo>→</mo></mover><mo>,</mo><mover><mi>b</mi><mo>→</mo></mover><mo>,</mo><mover><mi>c</mi><mo>→</mo></mover><mtext>共面的充要条件是混合积为零：</mtext></mtd></mtr><mtr><mtd><mo>[</mo><mover><mi>a</mi><mo>→</mo></mover><mspace width="0.1em"/><mover><mi>b</mi><mo>→</mo></mover><mspace width="0.1em"/><mover><mi>c</mi><mo>→</mo></mover><mo>]</mo><mo>=</mo><mn>0</mn></mtd></mtr><mtr><mtd><mrow><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>a</mi><mi>x</mi></msub></mtd><mtd><msub><mi>a</mi><mi>y</mi></msub></mtd><mtd><msub><mi>a</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>b</mi><mi>x</mi></msub></mtd><mtd><msub><mi>b</mi><mi>y</mi></msub></mtd><mtd><msub><mi>b</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>c</mi><mi>x</mi></msub></mtd><mtd><msub><mi>c</mi><mi>y</mi></msub></mtd><mtd><msub><mi>c</mi><mi>z</mi></msub></mtd></mtr></mtable></mstyle><mo>=</mo><mn>0</mn></mrow></mtd></mtr></mtable></math>
</body>
</html></div>

## 空间解析几何
### <!--占位符-->
#### 平面
##### 平面的方程
###### 点法式方程
<div class="boxed-formula"><math display="block"><mtable><mtr><mtd><mtext>过点</mtext><msub><mi>M</mi><mn>0</mn></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mtext>且以</mtext><mover><mi>n</mi><mo>→</mo></mover><mo>=</mo><mo>(</mo><mi>A</mi><mo>,</mo><mi>B</mi><mo>,</mo><mi>C</mi><mo>)</mo><mtext>为法向量的平面</mtext><mi>Π</mi><mtext>的方程为</mtext></mtd></mtr><mtr><mtd><mi>A</mi><mo>(</mo><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mi>B</mi><mo>(</mo><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mi>C</mi><mo>(</mo><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn></mtd></mtr><mtr><mtd><mtext>称平面的点法式方程</mtext></mtd></mtr></mtable></math></div>

###### 一般方程


<div class="boxed-formula"><math display="block"><mtable><mtr><mtd><mtext>三元一次方程</mtext></mtd></mtr><mtr><mtd><mi>A</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>y</mi><mo>+</mo><mi>C</mi><mi>z</mi><mo>+</mo><mi>D</mi><mo>=</mo><mn>0</mn></mtd></mtr><mtr><mtd><mo>(</mo><mi>A</mi><mo>,</mo><mi>B</mi><mo>,</mo><mi>C</mi><mtext>不同时为零</mtext><mo>)</mo><mtext>的图形是平面</mtext></mtd></mtr><mtr><mtd><mtext>其中</mtext><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mtext>的系数</mtext><mi>A</mi><mo>,</mo><mi>B</mi><mo>,</mo><mi>C</mi><mtext>构成的向量</mtext><mover><mi>n</mi><mo>→</mo></mover><mo>=</mo><mo>(</mo><mi>A</mi><mo>,</mo><mi>B</mi><mo>,</mo><mi>C</mi><mo>)</mo><mtext>是平面的法向量。</mtext></mtd></mtr></mtable></math></div>

> 三点式方程：~~可由三向量共面的充要条件定理得到~~
> >过三点$A(a_1,a_2,a_3),B(b_1,b_2,b_3),C(c_1,c_2,c_3)$的平面方程:
$$\begin{vmatrix}
\color{red}{x} \color{black}{-}\color{blue}{a_1} & \color{red}{y} \color{black}{-}\color{blue}{a_2} &\color{red}{z} \color{black}{-}\color{blue}{a_3}\\ b_1 \color{black}{-}\color{blue}{a_1} & b_2\color{black}{-}\color{blue}{a_2} & b_3\color{black}{-}\color{blue}{a_3} & \\ c_1 \color{black}{-}\color{blue}{a_1} & c_2\color{black}{-}\color{blue}{a_2} & c_3\color{black}{-}\color{blue}{a_3}\end{vmatrix} = 0$$


|*特殊形式的一般方程*|||
|-:|-|:--|
|*$D = 0:Ax+By+Cz=0$*||平面**过原点**|
|*$A = 0:By+Cz+D=0$*|$\vec{n}= (0,B,C)\perp x轴$|平面**平行于$x$轴**|
|*$A=D=0$*||平面**经过$x$轴**|
|*$A=B=0$*||平面**平行于$xOy$平面**|

###### 截距式方程
>　**$$\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1$$**

|↙|↓|↘|
|-:|:-:|:-|
|$a$|$b$|$c$|
|$x$轴上截距|$y$轴上截距|$z$轴上截距|

##### 两平面夹角
> **两平面法向量的夹角**称两平面的夹角
> *不取钝角*，即$\color{red}{\theta \in [0,\frac{\pi}{2}]}$
> 设平面$\varPi_1和\varPi_2$的法向量分别为$\vec{n}_1 = (A_1,B_1,C_1)和\vec{n}_2 = (A_2,B_2,C_2)$,有
<div class="boxed-formula"><math display="block"><mrow><mrow><mi>cos</mi><mo>⁡</mo><mi>θ</mi></mrow><mo>=</mo><mrow><mo>|</mo><mfrac><mrow><msub><mover><mi>n</mi><mo>→</mo></mover><mn>1</mn></msub><mo>·</mo><msub><mover><mi>n</mi><mo>→</mo></mover><mn>2</mn></msub></mrow><mrow><mo>|</mo><msub><mover><mi>n</mi><mo>→</mo></mover><mn>1</mn></msub><mo>|</mo><mspace width="0.1em"/><mo>|</mo><msub><mover><mi>n</mi><mo>→</mo></mover><mn>2</mn></msub><mo>|</mo></mrow></mfrac><mo>|</mo></mrow><mo>=</mo><mfrac><mrow><mo>|</mo><mrow><msub><mi>A</mi><mn>1</mn></msub><msub><mi>A</mi><mn>2</mn></msub><mo>+</mo><msub><mi>B</mi><mn>1</mn></msub><msub><mi>B</mi><mn>2</mn></msub><mo>+</mo><msub><mi>C</mi><mn>1</mn></msub><msub><mi>C</mi><mn>2</mn></msub></mrow><mo>|</mo></mrow><mrow><msqrt><mrow><msubsup><mi>A</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>B</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>C</mi><mn>1</mn><mn>2</mn></msubsup></mrow></msqrt><mspace width="0.1em"/><msqrt><mrow><msubsup><mi>A</mi><mn>2</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>B</mi><mn>2</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>C</mi><mn>2</mn><mn>2</mn></msubsup></mrow></msqrt></mrow></mfrac></mrow></math></div>

##### 点到平面的距离
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>求</mtext><msub><mi>P</mi><mn>0</mn></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mtext>到平面</mtext><mi>A</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>y</mi><mo>+</mo><mi>C</mi><mi>z</mi><mo>+</mo><mi>D</mi><mo>=</mo><mn>0</mn><mtext>的距离为</mtext></mtd></mtr><mtr><mtd><mi>d</mi><mo>=</mo><mfrac><mrow><mo>|</mo><mrow><mi>A</mi><mo>⁢</mo><msub><mi>x</mi><mn>0</mn></msub><mo>+</mo><mi>B</mi><mo>⁢</mo><msub><mi>y</mi><mn>0</mn></msub><mo>+</mo><mi>C</mi><mo>⁢</mo><msub><mi>z</mi><mn>0</mn></msub><mo>+</mo><mi>D</mi></mrow><mo>|</mo></mrow><mrow><msqrt><mrow><msup><mi>A</mi><mn>2</mn></msup><mo>+</mo><msup><mi>B</mi><mn>2</mn></msup><mo>+</mo><msup><mi>C</mi><mn>2</mn></msup></mrow></msqrt></mrow></mfrac></mtd></mtr></mtable></math></div>

> *证明*
##### 两平行平面间的距离
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>两平行平面</mtext><mi>A</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>y</mi><mo>+</mo><mi>C</mi><mi>z</mi><mo>+</mo><msub><mi>D</mi><mn>1</mn></msub><mo>=</mo><mn>0</mn><mtext>与</mtext><mi>A</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>y</mi><mo>+</mo><mi>C</mi><mi>z</mi><mo>+</mo><msub><mi>D</mi><mn>2</mn></msub><mo>=</mo><mn>0</mn><mtext>之间的距离为</mtext></mtd></mtr><mtr><mtd><mi>d</mi><mo>=</mo><mfrac><mrow><mo>|</mo><msub><mi>D</mi><mn>1</mn></msub><mo>-</mo><msub><mi>D</mi><mn>2</mn></msub><mo>|</mo></mrow><mrow><msqrt><mrow><msup><mi>A</mi><mn>2</mn></msup><mo>+</mo><msup><mi>B</mi><mn>2</mn></msup><mo>+</mo><msup><mi>C</mi><mn>2</mn></msup></mrow></msqrt></mrow></mfrac></mtd></mtr></mtable></math></div>

> *证明*



#### 直线
##### 直线的方程
> *平行于直线的任一非零向量*称该直线的**方向向量**
###### 点向式方程(对称式方程)与参数方程
> $M_0(x_0, y_0, z_0) $是直线上一点.由于*空间一点 $ M(x, y, z) $ 在直线$L$上的充要条件是向量 $ \overrightarrow{M_0M} // \vec{s} $,即$ \overrightarrow{M_0M} = t \vec{s} \ (t \in \mathbb{R}) $*,现$\overrightarrow{M_0M} = (x - x_0, y - y_0, z - z_0) $,$\vec{s} = (m, n, p)$,从而有 $ x - x_0 = tm,\ y - y_0 = tn,\ z - z_0 = tp $，即

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mrow><mo fence="true" stretchy="true">{</mo><mtable><mtr><mtd><mi>x</mi><mo>=</mo><msub><mi>x</mi><mn>0</mn></msub><mo>+</mo><mi>t</mi><mi>m</mi><mo>,</mo></mtd></mtr><mtr><mtd><mi>y</mi><mo>=</mo><msub><mi>y</mi><mn>0</mn></msub><mo>+</mo><mi>t</mi><mi>n</mi><mo>,</mo></mtd></mtr><mtr><mtd><mi>z</mi><mo>=</mo><msub><mi>z</mi><mn>0</mn></msub><mo>+</mo><mi>t</mi><mi>p</mi><mo>,</mo></mtd></mtr></mtable></mrow></mtd></mtr><mtr><mtd><mtext>或者</mtext></mtd></mtr><mtr><mtd><mfrac><mrow><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub></mrow><mi>m</mi></mfrac><mo>=</mo><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub></mrow><mi>n</mi></mfrac><mo>=</mo><mfrac><mrow><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub></mrow><mi>p</mi></mfrac><mo>.</mo></mtd></mtr></mtable></math></div>

> 在点向式方程中，*分母可以为0*,**分母为0意味着分子也为0**

###### 一般方程
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mrow><mo fence="true" stretchy="true">{</mo><mtable><mtr><mtd><msub><mi>A</mi><mn>1</mn></msub><mi>x</mi><mo>+</mo><msub><mi>B</mi><mn>1</mn></msub><mi>y</mi><mo>+</mo><msub><mi>C</mi><mn>1</mn></msub><mi>z</mi><mo>+</mo><msub><mi>D</mi><mn>1</mn></msub><mo>=</mo><mn>0</mn><mo>,</mo></mtd></mtr><mtr><mtd><msub><mi>A</mi><mn>2</mn></msub><mi>x</mi><mo>+</mo><msub><mi>B</mi><mn>2</mn></msub><mi>y</mi><mo>+</mo><msub><mi>C</mi><mn>2</mn></msub><mi>z</mi><mo>+</mo><msub><mi>D</mi><mn>2</mn></msub><mo>=</mo><mn>0</mn><mo>,</mo></mtd></mtr></mtable></mrow></mtd></mtr><mtr><mtd><mtext>其中</mtext><mfrac><msub><mi>A</mi><mn>1</mn></msub><msub><mi>A</mi><mn>2</mn></msub></mfrac><mo>=</mo><mfrac><msub><mi>B</mi><mn>1</mn></msub><msub><mi>B</mi><mn>2</mn></msub></mfrac><mo>=</mo><mfrac><msub><mi>C</mi><mn>1</mn></msub><msub><mi>C</mi><mn>2</mn></msub></mfrac><mtext>不成立。</mtext></mtd></mtr></mtable></math></div>

> ~~原理:两个不不平行的平面的交线是一条直线(公理)~~

##### 对称式方程和一般方程的联系
###### 一般方程$\to$对称式方程

> 由直线的一般方程，可得直线的方向向量

> $\vec{s} = \vec{n}_1 \times \vec{n}_2 = (A_1, B_1, C_1) \times (A_2, B_2, C_2)$

$$= \left(\begin{vmatrix}B_1 & C_1 \\B_2 & C_2\end{vmatrix},\;\begin{vmatrix}C_1 & A_1 \\C_2 & A_2\end{vmatrix},\;\begin{vmatrix}A_1 & B_1 \\A_2 & B_2\end{vmatrix}\right)$$

> 任取满足一般方程的一组数 $x_0, y_0, z_0$,则可得直线的对称式方程：

$$\frac{x-x_0}{\begin{vmatrix}B_1 & C_1\\ B_2 & C_2\end{vmatrix}} = \frac{y-y_0}{\begin{vmatrix}C_1 & A_1\\ C_2 & A_2\end{vmatrix}} = \frac{z-z_0}{\begin{vmatrix}A_1 & B_1\\ A_2 & B_2\end{vmatrix}}$$

###### 对称式方程$\to$一般方程
> 反之，若直线的对称式方程为

$$
\frac{x - x_0}{m} = \frac{y - y_0}{n} = \frac{z - z_0}{p},
$$

> 则直线的一般方程：

> > $
\begin{cases}
\frac{x - x_0}{m} - \frac{y - y_0}{n} = 0 \\
\frac{x - x_0}{m} - \frac{z - z_0}{p} = 0
\end{cases}.
$


##### 两直线的夹角
> **两直线方向向量的夹角**称两直线的夹角
> *不取钝角*，即$\color{red}{\theta \in [0,\frac{\pi}{2}]}$
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mrow><mrow><mi>cos</mi><mo>⁡</mo><mi>θ</mi></mrow><mo>=</mo><mtext>|</mtext><mfrac><mrow><msub><mover><mi>s</mi><mo>→</mo></mover><mn>1</mn></msub><mo>·</mo><msub><mover><mi>s</mi><mo>→</mo></mover><mn>2</mn></msub></mrow><mrow><mtext>|</mtext><msub><mover><mi>s</mi><mo>→</mo></mover><mn>1</mn></msub><mtext>|</mtext><mspace width="0.1em"/><mtext>|</mtext><msub><mover><mi>s</mi><mo>→</mo></mover><mn>2</mn></msub><mtext>|</mtext></mrow></mfrac><mtext>|</mtext><mo>=</mo><mfrac><mrow><mtext>|</mtext><mrow><msub><mi>m</mi><mn>1</mn></msub><msub><mi>m</mi><mn>2</mn></msub><mo>+</mo><msub><mi>n</mi><mn>1</mn></msub><msub><mi>n</mi><mn>2</mn></msub><mo>+</mo><msub><mi>p</mi><mn>1</mn></msub><msub><mi>p</mi><mn>2</mn></msub></mrow><mtext>|</mtext></mrow><mrow><msqrt><mrow><msubsup><mi>m</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>n</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>p</mi><mn>1</mn><mn>2</mn></msubsup></mrow></msqrt><mspace width="0.1em"/><msqrt><mrow><msubsup><mi>m</mi><mn>2</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>n</mi><mn>2</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>p</mi><mn>2</mn><mn>2</mn></msubsup></mrow></msqrt></mrow></mfrac></mrow></math></div>

> 从**两向量垂直或者平行的充要条件定理**可得:
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>直线</mtext><msub><mi>L</mi><mn>1</mn></msub><mtext>和</mtext><msub><mi>L</mi><mn>2</mn></msub><mtext>互相垂直的充要条件是</mtext><msub><mi>m</mi><mn>1</mn></msub><msub><mi>m</mi><mn>2</mn></msub><mo>+</mo><msub><mi>n</mi><mn>1</mn></msub><msub><mi>n</mi><mn>2</mn></msub><mo>+</mo><msub><mi>p</mi><mn>1</mn></msub><msub><mi>p</mi><mn>2</mn></msub><mo>=</mo><mn>0</mn><mo>;</mo></mtd></mtr><mtr><mtd><mtext>直线</mtext><msub><mi>L</mi><mn>1</mn></msub><mtext>和</mtext><msub><mi>L</mi><mn>2</mn></msub><mtext>互相平行的充要条件是</mtext><mfrac><msub><mi>m</mi><mn>1</mn></msub><msub><mi>m</mi><mn>2</mn></msub></mfrac><mo>=</mo><mfrac><msub><mi>n</mi><mn>1</mn></msub><msub><mi>n</mi><mn>2</mn></msub></mfrac><mo>=</mo><mfrac><msub><mi>p</mi><mn>1</mn></msub><msub><mi>p</mi><mn>2</mn></msub></mfrac><mo>.</mo></mtd></mtr></mtable></math></div>

##### 直线与平面的夹角
> **直线与平面的夹角**:直线与平面*法线*夹角的**余角**

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><msub><mover><mi>s</mi><mo>→</mo></mover><mn>1</mn></msub><mo>=</mo><mo>(</mo><msub><mi>m</mi><mn>1</mn></msub><mo>,</mo><msub><mi>n</mi><mn>1</mn></msub><mo>,</mo><msub><mi>p</mi><mn>1</mn></msub><mo>)</mo><mo>,</mo><mspace width="1em"/><mover><mi>n</mi><mo>→</mo></mover><mo>=</mo><mo>(</mo><mi>A</mi><mo>,</mo><mi>B</mi><mo>,</mo><mi>C</mi><mo>)</mo><mo>,</mo><mspace width="1em"/><mtext>则</mtext></mtd></mtr><mtr><mtd><mrow><mi>sin</mi><mo>⁡</mo><mi>φ</mi></mrow><mo>=</mo><mrow><mi>cos</mi><mo>⁡</mo><mi>θ</mi></mrow><mo>=</mo><mfrac><mrow><mtext>|</mtext><mrow><mover><mi>n</mi><mo>→</mo></mover><mo>·</mo><mover><mi>s</mi><mo>→</mo></mover></mrow><mtext>|</mtext></mrow><mrow><mtext>|</mtext><mover><mi>n</mi><mo>→</mo></mover><mtext>|</mtext><mspace width="0.1em"/><mtext>|</mtext><mover><mi>s</mi><mo>→</mo></mover><mtext>|</mtext></mrow></mfrac><mo>=</mo><mfrac><mrow><mtext>|</mtext><mrow><mi>A</mi><mi>m</mi><mo>+</mo><mi>B</mi><mi>n</mi><mo>+</mo><mi>C</mi><mi>p</mi></mrow><mtext>|</mtext></mrow><mrow><msqrt><mrow><msup><mi>A</mi><mn>2</mn></msup><mo>+</mo><msup><mi>B</mi><mn>2</mn></msup><mo>+</mo><msup><mi>C</mi><mn>2</mn></msup></mrow></msqrt><mspace width="0.1em"/><msqrt><mrow><msup><mi>m</mi><mn>2</mn></msup><mo>+</mo><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><msup><mi>p</mi><mn>2</mn></msup></mrow></msqrt></mrow></mfrac></mtd></mtr></mtable></math></div>

> 从**两向量垂直或者平行的充要条件定理**可得:

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>直线</mtext><mi>L</mi><mtext>与平面</mtext><mi>&#x03A0;</mi><mtext>垂直的充要条件是</mtext><mfrac><mi>A</mi><mi>m</mi></mfrac><mo>=</mo><mfrac><mi>B</mi><mi>n</mi></mfrac><mo>=</mo><mfrac><mi>C</mi><mi>p</mi></mfrac><mo>;</mo></mtd></mtr><mtr><mtd><mtext>直线</mtext><mi>L</mi><mtext>与平面</mtext><mi>&#x03A0;</mi><mtext>平行的充要条件是</mtext><mi>A</mi><mi>m</mi><mo>+</mo><mi>B</mi><mi>n</mi><mo>+</mo><mi>C</mi><mi>p</mi><mo>=</mo><mn>0</mn><mo>.</mo></mtd></mtr></mtable></math></div>

##### 过直线的平面束
> 设直线$L$由一般方程确定,作含有参数$\lambda$的方程
> $A_{1} x +B_{1} y +C_{1} z +D_1+ \lambda (A_{2} x +B_{2} y +C_{2} z + D_2) = 0$
> 即
> $(A_1 + \lambda A_2)x+(B_1 + \lambda B_2)x+(C_1 + \lambda C_2)x+(D_1 + \lambda D_2)x = 0$
> 称通过直线$L$的平面束(族)方程

#### 曲面
##### 柱面
> 平行于*定直线$L$*(母线)并沿*定曲线$C$*(准线)移动的直线所形成的曲面
> > 在空间直角坐标系中,*缺少一个变量*的方程总表示一个柱面,**哪个坐标缺省则母线平行于哪个坐标轴**

##### 旋转曲面
> 平面上的*曲线$C$*(母线)绕该平面上的一条*定直线$L$*(轴)旋转而形成的曲面.
> > 若在曲线$ C $的方程 $ f(y, z) = 0 $ 中 $ z $ 保持不变而*将 $ y $ 改写成 $\pm \sqrt{x^2 + y^2}$*，就得到曲线 $ C $ **绕 $ z $ 轴旋转而成的曲面**的方程$f\left(\pm \sqrt{x^2 + y^2}, z\right) = 0;$
> > 若在曲线$ C $的方程 $ f(y, z) = 0 $ 中 $ y $ 保持不变，*将 $ z $ 改成 $\pm \sqrt{x^2 + z^2}$*，就得到曲线 $ C $ **绕 $ y $ 轴旋转而成的曲面**的方程$f\left(y, \pm \sqrt{x^2 + z^2}\right) = 0.$
> > 其余情况类似.

##### 截痕法
> 用坐标面或特殊的平面与曲线相截,考察截痕的形状
##### 二次曲面
###### 椭球面
$$\color{red}{\frac{x^2}{a^2} + \frac{y^2}{b^2} + \frac{z^2}{c^2} = 1},(长半轴 a > 0,中半轴b>0,短半轴c>0)$$
|平面|截痕|截痕的形状|
|--:|:-:|:--|
|$xOy$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = 1 - \dfrac{h^2}{c^2},\\ z = h\end{cases}$|一点或椭圆|
|$yOz$面及其平行平面|$\begin{cases}\dfrac{y^2}{b^2} + \dfrac{z^2}{c^2} = 1 - \dfrac{h^2}{a^2},\\ x = h\end{cases}$|一点或椭圆|
|$xOz$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{z^2}{c^2} = 1 - \dfrac{h^2}{b^2},\\ y = h\end{cases}$|一点或椭圆|
###### 椭圆抛物面
$$\color{red}{\frac{x^2}{a^2} + \frac{y^2}{b^2} = z}, (a > 0, b > 0)$$

|平面|截痕|截痕的形状|
|--:|:-:|:--|
|$xOy$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = h,\\ z = h\end{cases}$|一点( $h = 0$ )或椭圆( $h > 0$ )|
|$yOz$面及其平行平面|$\begin{cases} y^2 = b^2(z - \dfrac{h^2}{a^2}),\\ x = h\end{cases}$|抛物线|
|$xOz$面及其平行平面|$\begin{cases} x^2 = a^2(z - \dfrac{k^2}{b^2}),\\ y = k\end{cases}$|抛物线|

###### 双曲抛物面(马鞍面)
$$
\color{red}{-\frac{x^2}{a^2} + \frac{y^2}{b^2} = z}, \quad (a > 0,\ b > 0)
$$

> *截痕分析*
> > 1. 用坐标面 \(yOz\)(\(x = 0\))截曲面得抛物线
\[
\begin{cases}
-\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = z \\
x = 0
\end{cases}
\implies
\begin{cases}
\dfrac{y^2}{b^2} = z \\
x = 0
\end{cases}
\]
这是开口向上的抛物线，位于 \(yOz\) 平面内，顶点在原点。

> > 2. 用平行于 \(xOz\) 的平面 \(y = k\) 截曲面得抛物线
\[
\begin{cases}
-\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = z \\
y = k
\end{cases}
\implies
\begin{cases}
z - \dfrac{k^2}{b^2} = -\dfrac{x^2}{a^2} \\
y = k
\end{cases}
\]
这是开口向下的抛物线，顶点为 \(\left(0,\ k,\ \dfrac{k^2}{b^2}\right)\)。该**顶点恰好落在第一条抛物线(开口向上的抛物线)上**。因此，*无数条开口向下的抛物线的顶点全部“挂”在一条开口向上的抛物线上*

> > 3. 用平行于 \(xOy\) 的平面 \(z = h\) 截曲面得双曲线
\[
\begin{cases}
-\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = h \\
z = h
\end{cases}
\]

> > - 当 \(h > 0\) 时，方程化为 \(\dfrac{y^2}{b^2 h} - \dfrac{x^2}{a^2 h} = 1\)，实轴在 \(y\) 轴上，虚轴在 \(x\) 轴上；
> > - 当 \(h < 0\) 时，方程化为 \(\dfrac{x^2}{a^2 |h|} - \dfrac{y^2}{b^2 |h|} = 1\)，实轴在 \(x\) 轴上，虚轴在 \(y\) 轴上；
> > - 当 \(h = 0\) 时，截得两条相交直线：\(\dfrac{y}{b} = \pm \dfrac{x}{a}\)。

###### 单叶双曲面
$$\color{red}{\frac{x^2}{a^2} + \frac{y^2}{b^2} - \frac{z^2}{c^2} = 1}, (a > 0, b > 0, c > 0)$$

|平面|截痕|截痕的形状|
|--:|:-:|:--|
|$xOy$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = 1 + \dfrac{h^2}{c^2},\\ z = h\end{cases}$|椭圆|
|$yOz$面及其平行平面|$\begin{cases}\dfrac{y^2}{b^2} - \dfrac{z^2}{c^2} = 1 - \dfrac{h^2}{a^2},\\ x = h\end{cases}$|双曲线(或两条相交直线当 $\|h\| = a$)|
|$xOz$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} - \dfrac{z^2}{c^2} = 1 - \dfrac{k^2}{b^2},\\ y = k\end{cases}$|双曲线(或两条相交直线当 $\|k\| = b$)|

###### 双叶双曲面
$$\color{red}{\frac{x^2}{a^2} + \frac{y^2}{b^2} - \frac{z^2}{c^2} = -1}, (a > 0, b > 0, c > 0)$$

|平面|截痕|截痕的形状|
|--:|:-:|:--|
|$xOy$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = \dfrac{h^2}{c^2} - 1,\\ z = h\end{cases}$|一点( $\|h\| = c$ )或椭圆( $\|h\| > c$ )；当 $\|h\| < c$ 时无图形|
|$yOz$面及其平行平面|$\begin{cases}\dfrac{y^2}{b^2} - \dfrac{z^2}{c^2} = -1 - \dfrac{h^2}{a^2},\\ x = h\end{cases}$|双曲线|
|$xOz$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} - \dfrac{z^2}{c^2} = -1 - \dfrac{k^2}{b^2},\\ y = k\end{cases}$|双曲线|

###### 椭圆锥面
$$\color{red}{\frac{x^2}{a^2} + \frac{y^2}{b^2} = z^2}, (a > 0, b > 0)$$

|平面|截痕|截痕的形状|
|--:|:-:|:--|
|$xOy$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = h^2,\\ z = h\end{cases}$|一点( $h = 0$ )或椭圆( $h \neq 0$ )|
|$yOz$面及其平行平面|$\begin{cases}\dfrac{y^2}{b^2} - z^2 = -\dfrac{h^2}{a^2},\\ x = h\end{cases}$|双曲线(或两条相交直线当 $h = 0$)|
|$xOz$面及其平行平面|$\begin{cases}\dfrac{x^2}{a^2} - z^2 = -\dfrac{k^2}{b^2},\\ y = k\end{cases}$|双曲线(或两条相交直线当 $k = 0$)|

#### 曲线
##### 曲线的方程
###### 一般方程
> 空间曲线$\varGamma $可以看成是两个曲面 $\varSigma_1$ 与 $\varSigma_2$ 的交线,设方程分别是

$$
F(x, y, z) = 0 \quad \text{与} \quad G(x, y, z) = 0,
$$

> 则点 $M(x, y, z)$ 位于曲线 $\varGamma$ 上的充要条件是它的坐标 $x, y, z$ 同时满足曲面 $\varSigma_1$ 的方程和曲面 $\varSigma_2$ 的方程，即满足方程组

$$
\color{red}{\begin{cases}
F(x, y, z) = 0, \\
G(x, y, z) = 0.
\end{cases}}
$$

###### 参数方程
> ~~参数方程一般用于表示螺线~~
> 把曲线上动点的坐标 $x, y, z$ 分别表示成参数 $t$ 的函数

$$
\begin{cases} 
x = x(t), \\
y = y(t), \\
z = z(t).
\end{cases}
$$

##### 曲线的投影

## 多元函数微分学






### 多元函数的基本概念

#### n维空间

|**n元有序实数组**|$x = <x_1, x_2, \cdots, x_n>$|
|-:|:-|
|**$R^n$**|n元有序实数组构成的集合|
|即|$R^n = \{ <x_1, x_2, \cdots, x_n> \mid x_k \in R, k = 1, 2, \cdots, n \}$|
|**$x = <x_1, x_2, \cdots, x_n>$**|称为$n$维空间中的一点或一个$n$维向量.|
||$x_k$称为第k个坐标或分量.|
|$0 = <0,0,\cdots,0>$|称为$R^n$中的坐标原点, $n$维零向量或零元.|

> ~~$n$维空间是平面和三维空间的推广, 每个点由n个坐标唯一确定.~~


#### 平面点集
> **平面两点距离**  
> > 设平面上两点 $x = (x_1, x_2)$，$y = (y_1, y_2)$，则它们之间的距离为  
$$\color{red}{\rho(x, y) = |x - y| = \sqrt{(x_1 - y_1)^2 + (x_2 - y_2)^2}}$$  

> **平面上趋于定点**  

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>称变元</mtext><mi>x</mi><mo>=</mo><mo>(</mo><msub><mi>x</mi><mn>1</mn></msub><mo>,</mo><msub><mi>x</mi><mn>2</mn></msub><mo>)</mo><mtext>在</mtext><msup><mi>R</mi><mn>2</mn></msup><mtext>中趋于</mtext><mi>a</mi><mo>=</mo><mo>(</mo><msub><mi>a</mi><mn>1</mn></msub><mo>,</mo><msub><mi>a</mi><mn>2</mn></msub><mo>)</mo></mtd></mtr><mtr><mtd><mtext>记作</mtext><mi>x</mi><mo>→</mo><mi>a</mi><mo>,</mo><mtext>若</mtext><mtext>|</mtext><mi>x</mi><mo>-</mo><mi>a</mi><mtext>|</mtext><mo>→</mo><mn>0</mn><mo>.</mo></mtd></mtr><mtr><mtd><mtext>■</mtext><mspace width="0.2em"/><mi>x</mi><mo>→</mo><mi>a</mi><mtext>⇔</mtext><msub><mi>x</mi><mn>1</mn></msub><mo>→</mo><msub><mi>a</mi><mn>1</mn></msub><mo>,</mo><mspace width="0.2em"/><msub><mi>x</mi><mn>2</mn></msub><mo>→</mo><msub><mi>a</mi><mn>2</mn></msub><mo>.</mo></mtd></mtr></mtable></math></div>


##### 平面上点与点集的关系
> 对任意一点 $P \in \mathbb{R}^2$ 与任意一个点集 $E \subset \mathbb{R}^2$，点 $P$ 与集合 $E$ 必定有以下三种关系之一
###### 1.内点
> *存在*点 $P$ 的某邻域 $U(P)$，使得 *$U(P) \subset E$*，则称点 $P$ 是集合 $E$ 的**内点**
> ~~若 $P$ 是 $E$ 的内点，则必有 $P \in E$~~


###### 2.外点

> *存在* $P$ 的某邻域 $U(P)$，使得 *$U(P) \cap E = \varnothing$*，则称 $P$ 是 $E$ 的**外点**  
> ~~若 $P$ 是 $E$ 的外点，则必有 $P \not\in E$~~



###### 3.边界点 
> 对 $P$ 的*任一*邻域 $U(P)$，都有 *$U(P) \cap E \neq \varnothing$ 且 $U(P) \cap E^c \neq \varnothing$*，则称 $P$ 是 $E$ 的**边界点**

> 集合 $E$ 的*全体边界点*称为 $E$ 的**边界**，记作 $\partial E$


> ~~若 $P$ 是 $E$ 的边界点，则可 $P \in E$ 可 $P \not\in E$~~


###### 聚点
> 设 $E$ 是平面上的一个点集,$P$ 是平面上的一点。如果点 $P$ 的任何邻域内总有无限多个点属于 $E$,则称 $P$ 为 $E$ 的**聚点**

|1.| 内点一定是聚点|
|-:|:-|
|2.|边界点可以是聚点,也可以不是聚点)如单点集、离散的点集)|
|3.|聚点可以属于 $E$(如内点)，也可以不属于 $E$|

###### 开集与闭集
||根据集合 $E \subset \mathbb{R}^2$ 的点的特征，定义|
|-:|:-|
|**开集**|若 $\forall x \in E$,点 $x$ 都是集合 $E$ 的内点,则称 $E$ 是 $\mathbb{R}^2$ 中的开集|
||~~边界点被排斥在外,即开集没有边界~~|
|**闭集**|若 $E^c$ 是开集, 则称 $E$ 是 $\mathbb{R}^2$ 中的闭集|
|*规定*|*$\varnothing$* 与 *$\mathbb{R}^2$* 既是 $\mathbb{R}^2$ 中的开集, 又是闭集|

###### 连通集
|**定义**|若 $\forall P, Q \in E$, 存在一条完全包含于集合 $E$ 中的折线将 $P, Q$ 连接起来, 则称 $E$ 为 $\mathbb{R}^2$ 中的连通集.|
|-:|:-|

###### 开区域与闭区域
|**开区域**|若 $E$ 为连通的开集,称 $E$ 为 $\mathbb{R}^2$ 的开区域|
|-:|:-|
|**闭区域**|开区域连同其边界点所成的点集称为闭区域.|



###### 
|**定义**|若 *$\exists K > 0$, 使得 $E \subset U(0, K)$*, 则称集合 $E$ 为有界集.|
|-:|:-|
||否则称为 **无界集**|




#### 邻域
|**定义**|设 $P_0(x_0, y_0) \in \mathbb{R}^2$,$\delta > 0$|
|-:|:-|
||在 $\mathbb{R}^2$ 中与点 $P_0$ 的距离小于 $\delta$ 的点 $P(x, y)$ 的全体,称为点 $P_0$ 的 **$\delta$ 邻域**,记作 $U(P_0, \delta)$,即|
||$U(P_0, \delta) = \{ P \in \mathbb{R}^2 \mid \lvert P - P_0\rvert < \delta \}$|
||$= \{ (x, y) \mid \sqrt{(x - x_0)^2 + (y - y_0)^2} < \delta \}$|
|*去心邻域*|$\mathring{U}(P_0, \delta) = U(P_0, \delta) \setminus \{P_0\}$(去掉中心点)|



<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 520" width="100%" height="auto" style="display: block;">
  <defs>
    <marker id="arrow" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,1 L7,4 L0,7 Z" fill="#2c7da0"/></marker>
  </defs>

  <rect x="270" y="20" width="160" height="40" rx="8" fill="#e6f2ff" stroke="#2c7da0" stroke-width="1.5"/>
  <text x="350" y="45" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a4d6b">邻域</text>

  <!-- 点的分类 -->
  <rect x="40" y="120" width="120" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="100" y="145" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">内点</text>

  <rect x="180" y="120" width="120" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="240" y="145" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">边界点</text>

  <rect x="320" y="120" width="120" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="380" y="145" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">外点</text>

  <rect x="460" y="120" width="120" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="520" y="145" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">聚点</text>

  <!-- 连线：邻域 → 点 -->
  <line x1="350" y1="60" x2="100" y2="120" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="350" y1="60" x2="240" y2="120" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="350" y1="60" x2="380" y2="120" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="350" y1="60" x2="520" y2="120" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>

  <!-- 开集、闭集 -->
  <rect x="60" y="240" width="140" height="40" rx="8" fill="#d9f0e3" stroke="#2d6a4f" stroke-width="1.5"/>
  <text x="130" y="265" text-anchor="middle" font-size="13" font-weight="bold" fill="#1b4d3e">开集</text>

  <rect x="280" y="240" width="140" height="40" rx="8" fill="#f0d9e6" stroke="#7b2c6e" stroke-width="1.5"/>
  <text x="350" y="265" text-anchor="middle" font-size="13" font-weight="bold" fill="#4a1d40">闭集</text>
  <line x1="100" y1="160" x2="130" y2="240" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="240" y1="160" x2="310" y2="240" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="520" y1="160" x2="400" y2="240" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <text x="105" y="205" font-size="10" fill="#2d6a4f">所有点都是内点</text>
  <text x="245" y="205" font-size="10" fill="#7b2c6e">包含所有边界点</text>
  <text x="425" y="205" font-size="10" fill="#7b2c6e">包含所有聚点</text>
  <text x="380" y="195" font-size="10" fill="#6f5b47" font-style="italic">(补集的内点)</text>
  <rect x="60" y="380" width="150" height="40" rx="8" fill="#ffe6cc" stroke="#b85c00" stroke-width="1.5"/>
  <text x="135" y="405" text-anchor="middle" font-size="13" font-weight="bold" fill="#7a3b00">开区域</text>
  <rect x="340" y="380" width="160" height="40" rx="8" fill="#ffe6cc" stroke="#b85c00" stroke-width="1.5"/>
  <text x="420" y="405" text-anchor="middle" font-size="13" font-weight="bold" fill="#7a3b00">有界闭区域</text>
  <line x1="130" y1="280" x2="135" y2="380" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <line x1="350" y1="280" x2="420" y2="380" stroke="#2c7da0" stroke-width="1.5" marker-end="url(#arrow)"/>
  <text x="100" y="340" font-size="10" fill="#b85c00">+ 连通性</text>
  <text x="370" y="340" font-size="10" fill="#b85c00">+ 有界性</text>
  <rect x="20" y="460" width="660" height="45" rx="6" fill="#f8f9fa" stroke="#ccc" stroke-width="0.5"/>
  <text x="40" y="478" font-size="11" fill="#2c7da0">→ 定义/蕴含关系</text>
  <text x="220" y="478" font-size="11" fill="#2d6a4f">开集由内点定义</text>
  <text x="420" y="478" font-size="11" fill="#7b2c6e">闭集包含所有聚点和边界点</text>
  <text x="40" y="495" font-size="11" fill="#b85c00">开区域 = 开集+连通；有界闭区域 = 闭集+有界</text>
</svg>

#### 多元函数定义
#### 二元函数
|**定义**|设 $D \subset \mathbb{R}^2$ 是一个非空子集, 若对于每个点 $(x,y) \in D$, 都*存在唯一*确定的实数 $z$ 与之对应, 则称映射 $f: D \to \mathbb{R}$ 为定义在 $D$ 上的一个二元函数, 记作 $z = f(x,y)$.|
|-:|:-|
||称 $(x,y)$ 为 **自变量**, $z$ 为 **因变量**, $D$ 为函数 $f$ 的 **定义域**,|
||$f(D) = \{ f(x,y) \mid (x,y) \in D \}$ 为函数 $f$ 的 **值域**.|

#### $n$元函数
|**定义**|设 $D \subset \mathbb{R}^n$ 是一个非空子集, 映射 $f: D \to \mathbb{R}$, 称 $f$ 为定义在 $D$ 上的 $n$ 元函数, 记作|
|-:|:-|
||$y = f(x) = f(x_1, x_2, \cdots, x_n)$, 其中 $x = <x_1, x_2, \cdots, x_n> \in D$.
||称 $x$ 为 **自变量**, $y$ 为 **因变量**, $D$ 为函数 $f$ 的 **定义域**,|
||$f(D) = \{ f(x) \mid x \in D \}$ 为函数$f$ 的 **值域**.|

~~n元函数是多元函数的一般形式~~

### 多元函数的极限



### 偏导数


<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 560 360" width="100%" height="100%" style=" font-family: sans-serif;">
  <defs>
    <marker id="arrF" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,1 L7,4 L0,7 Z" fill="#2c7da0"/></marker>
    <marker id="arrR" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,1 L7,4 L0,7 Z" fill="#c44536"/></marker>
  </defs>

  <!-- ========== 正向箭头（蓝色实线，居中） ========== -->
  <line x1="280" y1="90" x2="280" y2="140" stroke="#2c7da0" stroke-width="2" marker-end="url(#arrF)"/>
  <line x1="230" y1="180" x2="170" y2="260" stroke="#2c7da0" stroke-width="2" marker-end="url(#arrF)"/>
  <line x1="330" y1="180" x2="390" y2="260" stroke="#2c7da0" stroke-width="2" marker-end="url(#arrF)"/>

  <!-- ========== 反向箭头（红色虚线，偏移避免重叠） ========== -->
  <!-- 可微 ⇏ 偏导连续：向左偏移6px -->
  <line x1="274" y1="140" x2="274" y2="90" stroke="#c44536" stroke-width="1.5" stroke-dasharray="4,3" marker-end="url(#arrR)"/>
  <text x="264" y="118" font-size="18" fill="#c44536" font-weight="bold">✗</text>

  <!-- 连续 ⇏ 可微：向左偏移6px -->
  <line x1="164" y1="260" x2="224" y2="180" stroke="#c44536" stroke-width="1.5" stroke-dasharray="4,3" marker-end="url(#arrR)"/>
  <text x="180" y="226" font-size="18" fill="#c44536" font-weight="bold">✗</text>

  <!-- 可偏导 ⇏ 可微：向右偏移6px -->
  <line x1="396" y1="260" x2="336" y2="180" stroke="#c44536" stroke-width="1.5" stroke-dasharray="4,3" marker-end="url(#arrR)"/>
  <text x="380" y="226" font-size="18" fill="#c44536" font-weight="bold">✗</text>

  <!-- ========== 双向互不蕴含：直接连接连续底部(170,300) 到可偏导底部(390,300) ========== -->
  <line x1="170" y1="300" x2="390" y2="300" stroke="#8b5cf6" stroke-width="1.5" stroke-dasharray="4,3" marker-start="url(#arrR)" marker-end="url(#arrR)"/>
  <text x="270" y="296" font-size="20" fill="#8b5cf6" font-weight="bold">✗</text>

  <!-- ========== 节点 ========== -->
  <rect x="190" y="50" width="180" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="280" y="75" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">偏导数连续</text>

  <rect x="200" y="140" width="160" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="280" y="165" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">可微</text>

  <rect x="100" y="260" width="140" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="170" y="285" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">连续</text>

  <rect x="320" y="260" width="140" height="40" rx="8" fill="#fef9e8" stroke="#b0a088" stroke-width="1.2"/>
  <text x="390" y="285" text-anchor="middle" font-size="13" font-weight="bold" fill="#2d3e50">可偏导</text>
</svg>





### 全微分

### 复合函数求导

### 隐函数求导


### 方向导数

### 梯度
#### 梯度的定义
|*推导过程*|函数在一点处沿哪一方向具有最大方向导数?|
|-:|:-|
||方向导数公式:|
||$\frac{\partial f}{\partial l} = \frac{\partial f}{\partial x} \cos \alpha + \frac{\partial f}{\partial y} \cos \beta = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right) \cdot (\cos \alpha, \cos \beta)$|
||$= \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right) \cdot e_l$|
||当 $\cos \theta = 1$ 时,$\frac{\partial f}{\partial l}$ 有最大值;|
||当 $\cos \theta = 0$ 时,$\frac{\partial f}{\partial l}$ 为零;|
||当 $\cos \theta = -1$ 时,$\frac{\partial f}{\partial l}$ 有最小值|


|**定义**|函数 $z = f(x, y)$ 在可微点 $(x_0, y_0)$ 处的梯度|
|-:|:-|
||$\operatorname{grad}f(x_0, y_0) = \nabla f(x_0, y_0) = (f_x(x_0, y_0), f_y(x_0, y_0))$|
||$= f_x(x_0, y_0)\vec{i} + f_y(x_0, y_0)\vec{j}$|
||~~方向导数是一个数, 梯度是一个*向量*.~~|

#### 梯度与方向导数的关系式

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>函数的</mtext><mtext>方向导数</mtext><mtext>为梯度在该方向上的投影：</mtext></mtd></mtr><mtr><mtd><mfrac><mrow><mo>∂</mo><mi>f</mi></mrow><mrow><mo>∂</mo><mi>l</mi></mrow></mfrac><mo>=</mo><mo>∇</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>·</mo><msub><mover><mi>e</mi><mo>→</mo></mover><mi>l</mi></msub></mtd></mtr></mtable></math></div>


#### 梯度的性质
##### 梯度与方向导数的关系
> 1.梯度是方向导数取最大值的方向, 其模等于最大方向导数值.
$$\lvert \nabla f(x, y) \rvert = \sqrt{\left(\frac{\partial f}{\partial x}\right)^2 + \left(\frac{\partial f}{\partial y}\right)^2} = \max \frac{\partial f}{\partial l}$$

> 2.沿与梯度垂直方向的方向导数为零.

|*证明*|设函数 $f(x, y)$ 在点 $(x_0, y_0)$ 可微, 梯度向量记为 $\vec{\nabla} f = (f_x, f_y)$. |
|-:|:-|
||方向导数沿单位方向向量 $\vec{e}_l = (\cos\alpha, \cos\beta)$ 为:|
||$\frac{\partial f}{\partial l} = f_x \cos\alpha + f_y \cos\beta = \vec{\nabla} f \cdot \vec{e}_l$.|
||若 $\vec{e}_l \perp \vec{\nabla} f$,|
||则 $\vec{\nabla} f \cdot \vec{e}_l = 0$,~~梯度与方向导数的关系式~~|
||故 $\frac{\partial f}{\partial l} = 0$.|



##### 梯度算子 $\nabla$ 的基本运算性质
||若 $u$ 可微, $\nabla u = (\frac{\partial u}{\partial x}, \frac{\partial u}{\partial y}, \frac{\partial u}{\partial z})$|
|-:|:-|
|1.|$\nabla C = \vec{0}$|
|2.|$\nabla(Cu) = C\nabla u$|
|3.|$\nabla(u \pm v) = \nabla u \pm \nabla v$|
|4.|$\nabla(u \cdot v) = u\nabla v + v\nabla u$|
|5.|$\nabla(\frac{u}{v}) = \frac{v\nabla u - u\nabla v}{v^2}$|
|证明:||
|||
|||

### 等量面与等高线



### 多元函数微分学的几何应用
#### 空间曲线的切线与法平面
##### 参数曲线的切线与法平面
|*推导过程*|设空间曲线的方程 $\Gamma$:|
|-:|:-|
||$\begin{cases} x = x(t) \\ y = y(t) \\ z = z(t) \end{cases}$|
||对应参数 $t = t_0$ 点 $M_0(x_0, y_0, z_0) \in \Gamma$,$x'(t), y'(t), z'(t)$ 连续,且|
||$[x'(t)]^2 + [y'(t)]^2 + [z'(t)]^2 \neq 0$~~说明曲线光滑~~|
|则|任取 $M(x_0 + \Delta x, y_0 + \Delta y, z_0 + \Delta z) \in \Gamma$,对应参数 $t = t_0 + \Delta t$|
||割线 $M_0M$ 的方向向量 $\overrightarrow{M_0M} = \{\Delta x, \Delta y, \Delta z\}$|
||则$\frac{\Delta x}{\Delta t}, \frac{\Delta y}{\Delta t}, \frac{\Delta z}{\Delta t}$也是 $M_0M$ 的方向向量|
||当 $M \to M_0$,即 $\Delta t \to 0$ ($\lim_{\Delta t \to 0} \frac{\Delta x}{\Delta t} = x'(t_0)$)|
||则 $M_0M$ 方向向量的极限 $\{x'(t_0), y'(t_0), z'(t_0)\}$|
||所以|

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>切线的方向向量为</mtext></mtd></mtr><mtr><mtd><mover><mi>τ</mi><mo>→</mo></mover><mo>=</mo><mo>(</mo><msup><mi>x</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>,</mo><msup><mi>y</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>,</mo><msup><mi>z</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>)</mo></mtd></mtr><mtr><mtd><mtext>曲线在</mtext><msub><mi>M</mi><mn>0</mn></msub><mtext>处的切线方程为：</mtext></mtd></mtr><mtr><mtd><mfrac><mrow><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub></mrow><mrow><msup><mi>x</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub></mrow><mrow><msup><mi>y</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub></mrow><mrow><msup><mi>z</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac></mtd></mtr><mtr><mtd><mtext>法平面（过切点且与切线垂直的平面）的方程为：</mtext></mtd></mtr><mtr><mtd><msup><mi>x</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><msup><mi>y</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><msup><mi>z</mi><mo>′</mo></msup><mo>(</mo><msub><mi>t</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn></mtd></mtr></mtable></math></div>

##### 


#### 曲面的切平面与法线
|*推导过程*|设光滑曲面方程为 $\varSigma: F(x, y, z) = 0$,|
|-:|:-|
||求曲面在点 $M_0(x_0, y_0, z_0)$ 处的切平面方程.|
||在曲面$\varSigma: F(x, y, z) = 0$上任取一条通过点 $M_0(x_0, y_0, z_0)$ 的曲线, |
||设其参数方程为:$\varGamma: \begin{cases} x = x(t) \\ y = y(t), \\ z = z(t) \end{cases}$|
||则相应的切向量为: $\vec{\tau} = (x'(t_0), y'(t_0), z'(t_0))$|
||因为 $\varGamma$ 恒在 $\varSigma$ 上, 所以 $F(x, y, z) = F(x(t), y(t), z(t)) \equiv 0$|
||对上式两边在 $M(t = t_0)$ 处求导, |
|有|$F_x(x_0, y_0, z_0)x'(t_0) + F_y(x_0, y_0, z_0)y'(t_0) + F_z(x_0, y_0, z_0)z'(t_0) = 0$|
||记 $\vec{n} = (F_x(x_0, y_0, z_0), F_y(x_0, y_0, z_0), F_z(x_0, y_0, z_0))$|
||则 $\vec{\tau} \cdot \vec{n} = 0$, 即 $\nabla F(M_0) \cdot \vec{\tau} = 0$.|
|故|曲面上过点 $M_0$ 的切平面的法向量为:|
||  $\vec{n} = (F_x(x_0, y_0, z_0), F_y(x_0, y_0, z_0), F_z(x_0, y_0, z_0))$|
||曲面上过点 $M_0$ 的切平面方程为:|
||  $F_x(x_0, y_0, z_0)(x - x_0) + F_y(x_0, y_0, z_0)(y - y_0) + F_z(x_0, y_0, z_0)(z - z_0) = 0$|
||~~过$M(x_0, y_0, z_0)$而垂直切平面的直线称曲面在该点的法线~~|
||曲面上过点 $M_0$ 的法线方程为:|
||  $\frac{x - x_0}{F_x(x_0, y_0, z_0)} = \frac{y - y_0}{F_y(x_0, y_0, z_0)} = \frac{z - z_0}{F_z(x_0, y_0, z_0)}$|
||~~曲面上任一点处的切平面由梯度向量 $\nabla F$ 作为法向量确定~~|
||~~所有过该点的曲线的切向量均垂直于 $\nabla F$~~|
||~~即法线是沿 $\nabla F$ 方向的直线~~|


<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>曲面上过点</mtext><msub><mi>M</mi><mn>0</mn></msub><mtext>的切平面的法向量为：</mtext></mtd></mtr><mtr><mtd><mover><mi>n</mi><mo>→</mo></mover><mo>=</mo><mo>(</mo><msub><mi>F</mi><mi>x</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>,</mo><msub><mi>F</mi><mi>y</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>,</mo><msub><mi>F</mi><mi>z</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>)</mo></mtd></mtr><mtr><mtd><mtext>曲面上过点</mtext><msub><mi>M</mi><mn>0</mn></msub><mtext>的切平面方程为：</mtext></mtd></mtr><mtr><mtd><msub><mi>F</mi><mi>x</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><msub><mi>F</mi><mi>y</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><msub><mi>F</mi><mi>z</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>(</mo><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn></mtd></mtr><mtr><mtd><mtext>曲面上过点</mtext><msub><mi>M</mi><mn>0</mn></msub><mtext>的法线方程为：</mtext></mtd></mtr><mtr><mtd><mfrac><mrow><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub></mrow><mrow><msub><mi>F</mi><mi>x</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub></mrow><mrow><msub><mi>F</mi><mi>y</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub></mrow><mrow><msub><mi>F</mi><mi>z</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>,</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo></mrow></mfrac></mtd></mtr></mtable></math></div>



|*特别地*, |设曲面方程为 $z = f(x, y)$,|
|-:|:-|
||$\vec{n} = (f_x(x_0, y_0), f_y(x_0, y_0), -1)$|
||也可以 $\vec{n} = (-f_x(x_0, y_0), -f_y(x_0, y_0), 1)$|
||曲面在 $M_0(x_0, y_0, z_0)$ 处的切平面方程:|
||*$f_x(x_0, y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0) = z - z_0$*|
||法线方程:|
||*$$\frac{x - x_0}{f_x(x_0, y_0)} = \frac{y - y_0}{f_y(x_0, y_0)} = \frac{z - z_0}{-1}$$*|

#### 一般曲线的切线与法平面
##### 两曲面法向量叉乘法
|*推导过程*|设空间曲线方程为 $\Gamma: \begin{cases} F(x, y, z) = 0 \\G(x, y, z) = 0 \end{cases}$|
|-:|:-|
||$\Gamma$ 在 $M_0(x_0, y_0, z_0)$ 处的切向量|
||分别求出两个面的切平面|
||$\begin{cases} F_x \cdot (x - x_0) + F_y \cdot (y - y_0) + F_z \cdot (z - z_0) = 0 \\G_x \cdot (x - x_0) + G_y \cdot (y - y_0) + G_z \cdot (z - z_0) = 0 \end{cases}$|
||切线的方向向量为|
||$\begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\F_x & F_y & F_z \\G_x & G_y & G_z \end{vmatrix}{M_0} = \begin{Bmatrix} \begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}{M_0}, \begin{vmatrix} F_z & F_x \\ G_z & G_x \end{vmatrix}{M_0}, \begin{vmatrix} F_x & F_y \\ G_x & G_y \end{vmatrix}_{M_0} \end{Bmatrix}$|
||$= { F_x, F_y, F_z } \times { G_x, G_y, G_z }$|
||$= \nabla F \times \nabla G$|
||~~叉乘求得与两平面法向量垂直的向量,即切线的方向向量~~|


<div class="boxed-formula"><style>.det-container{display:inline-flex;border-left:1.5px solid black;border-right:1.5px solid black;padding:2px 2px;vertical-align:middle;}.det-table{border-collapse:collapse;}.det-table mtd{padding:0px 2px;}</style><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>切线的方向向量为</mtext></mtd></mtr><mtr><mtd><mover><mi>τ</mi><mo>→</mo></mover><mo>=</mo><mo>∇</mo><mi>F</mi><mo>×</mo><mo>∇</mo><mi>G</mi><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>=</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><mi mathvariant="bold">i</mi></mtd><mtd><mi mathvariant="bold">j</mi></mtd><mtd><mi mathvariant="bold">k</mi></mtd></mtr><mtr><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>=</mo><mrow><mo>(</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>,</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>,</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>)</mo></mrow></mtd></mtr><mtr><mtd><mtext>切线方程(对称式)为</mtext></mtd></mtr><mtr><mtd><mfrac><mrow><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub></mrow><mrow><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub></mrow><mrow><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub></mrow></mfrac><mo>=</mo><mfrac><mrow><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub></mrow><mrow><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub></mrow></mfrac><mo>.</mo></mtd></mtr><mtr><mtd><mtext>法平面方程为</mtext></mtd></mtr><mtr><mtd><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>(</mo><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>z</mi></msub></mtd><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>z</mi></msub></mtd><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>(</mo><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mstyle class="det-container"><mtable class="det-table"><mtr><mtd><msub><mi>F</mi><mi>x</mi></msub></mtd><mtd><msub><mi>F</mi><mi>y</mi></msub></mtd></mtr><mtr><mtd><msub><mi>G</mi><mi>x</mi></msub></mtd><mtd><msub><mi>G</mi><mi>y</mi></msub></mtd></mtr></mtable></mstyle><msub><mo></mo><msub><mi>M</mi><mn>0</mn></msub></msub><mo>(</mo><mi>z</mi><mo>-</mo><msub><mi>z</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn><mo>.</mo></mtd></mtr></mtable></math></div>

##### 隐函数求导法
> ~~把曲线看作以 $x$ 为自变量的一元函数 $y = y(x)$, $z = z(x)$, 切向量天然为 $(1, y_x, z_x)$.~~

|1.|将$\begin{cases}F(x, y, z) = 0\\G(x, y, z) = 0\end{cases}$看作$\begin{cases} x = x \\ y = y(x) \\ z = z(x) \end{cases}$|
|-:|:-|
|2.|对 $F = 0$, $G = 0$ 两边关于 $x$ 求导, 列方程组:|
|3.|$\begin{cases} F_x + F_y \cdot \frac{\mathrm{d}y}{\mathrm{d}x} + F_z \cdot \frac{\mathrm{d}z}{\mathrm{d}x} = 0 \\ G_x + G_y \cdot \frac{\mathrm{d}y}{\mathrm{d}x} + G_z \cdot \frac{\mathrm{d}z}{\mathrm{d}x} = 0 \end{cases}$|
||代入 $M_0$, 解出 $\frac{\mathrm{d}y}{\mathrm{d}x}\big \rvert_{M_0}$, $\frac{\mathrm{d}z}{\mathrm{d}x}\big \rvert_{M_0}$|
|4.|切向量: $\mathbf{T} = ( 1, \frac{\mathrm{d}y}{\mathrm{d}x}\big \rvert_{M_0}$, $\frac{\mathrm{d}z}{\mathrm{d}x}\big \rvert_{M_0})$|
|5.|代入此切向量求得切线、法平面方程|

### 多元函数的极值
#### 极大值和极小值
|**定义**|设 $(x_0, y_0)$ 是 $z = f(x, y)$ 的定义域的内点|
|-:|:-|
||若存在 $U(x_0, y_0)$ (某个邻域), 使得对任意 $(x, y) \in \mathring{U}(x_0, y_0)$ (去心邻域), 有|
||$f(x, y) < f(x_0, y_0)$ (或 $f(x, y) > f(x_0, y_0)$),|
||则称 $f(x_0, y_0)$ 为函数的**极大值**(或**极小值**).|
||~~极值是局部概念~~|
|*驻点*|使所有一阶偏导数同时为零的点.|
|*可疑极值点*|1.$f(x, y)$ 的驻点 (即 $f_x = 0$ 且 $f_y = 0$ 的点);|
||2.$f_x(x, y)$ 与 $f_y(x, y)$ 中至少有一个不存在的点.|

##### 多元函数取得极值的条件
|**取得极值的必要条件**|若函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ 有极值, 且在点 $(x_0, y_0)$ 可偏导, 则必有:|
|-:|:-|
||$f_x(x_0, y_0) = 0$, $f_y(x_0, y_0) = 0$.|
|*证明*||




|**取得极值的充分条件**|设函数 $z = f(x, y) \in C^{(2)}(D)$, 点 $(x_0, y_0)$ 是 $f(x, y)$ 的驻点. 记|
|-:|:-|
||$A = f_{xx}(x_0, y_0)$, $B = f_{xy}(x_0, y_0)$, $C = f_{yy}(x_0, y_0)$.|
|则1.|若 $AC - B^2 > 0$, 则 $f(x_0, y_0)$ 是极值|
|| 当 $A < 0$ 时为极大值,|
|| 当 $A > 0$ 时为极小值;|
|2.|若 $AC - B^2 < 0$, 则 $f(x_0, y_0)$ 不是极值;|
|3.|若 $AC - B^2 = 0$, 则无法确定, 需另作讨论.|
||~~即$\begin{vmatrix}A & B \\ B & C \end{vmatrix}$~~|
|*证明*|利用二元函数的泰勒公式.|




##### 求二阶连续可微函数极值的一般步骤
> 1. 解方程组 $f_x(x, y) = 0$, $f_y(x, y) = 0$ 得驻点.
> 2. 对于每个驻点 $(x_0, y_0)$, 求出对应的 $A = f_{xx}(x_0, y_0)$, $B = f_{xy}(x_0, y_0)$, $C = f_{yy}(x_0, y_0)$.
> 3. 计算 $AC - B^2$ 的符号, 根据充分条件判定是否为极值.

#### 条件极值
|*无条件极值*|对自变量只有定义域的限制|
|-:|:-|
|**条件极值**|对函数的自变量有约束条件的极值.|
||目标函数: $f(x, y)$|
||约束条件: $\phi(x, y) = 0$|
|解法:|1.代入法|
||2.拉格朗日乘子法|

##### 拉格朗日乘子法
|*推导过程*|求 $z = f(x, y)$ 在约束 $\phi(x, y) = 0$ 下的极值|
|-:|:-|
||设 $(x_0, y_0)$ 是极值点,则满足 $\phi(x_0, y_0) = 0$|
||假设在 $(x_0, y_0)$ 的邻域内 $f, \phi$ 有连续偏导数且 $\phi_y(x_0, y_0) \neq 0$|
||则由*隐函数定理*可确定 $y = y(x)$,代入得一元函数 $z = f(x, y(x))$|
||该函数在 $x = x_0$ 处取极值,故|
|| $$ \frac{\mathrm{d}z}{\mathrm{d}x} \big \rvert_{x=x_0} = f_x(x_0, y_0) + f_y(x_0, y_0) \frac{\mathrm{d}y}{\mathrm{d}x} \big \rvert_{x=x_0} = 0 $$ |
||由 $\phi(x, y(x)) = 0$ 两边对 $x$ 求导,得|
||$\phi_x(x, y) + \phi_y(x, y) \frac{\mathrm{d}y}{\mathrm{d}x} = 0$,于是|
|| $$ \frac{\mathrm{d}y}{\mathrm{d}x} = -\frac{\phi_x(x, y)}{\phi_y(x, y)} ,$$|
|代入得| $$ f_x(x_0, y_0) - f_y(x_0, y_0) \frac{\phi_x(x_0, y_0)}{\phi_y(x_0, y_0)} = 0, $$|
|即| $$ f_x(x_0, y_0) + \phi_x(x_0, y_0) \left( -\frac{f_y(x_0, y_0)}{\phi_y(x_0, y_0)} \right) = 0 $$ |
|令|$$ \lambda = -\frac{f_y(x_0, y_0)}{\phi_y(x_0, y_0)} $$则上式变为|
||$$f_x(x_0, y_0) + \lambda \phi_x(x_0, y_0) = 0$$|
||同时由 $\lambda$ 的定义有|
||$$f_y(x_0, y_0) + \lambda \phi_y(x_0, y_0) = 0$$|
||再加上约束 $\phi(x_0, y_0) = 0$，得到方程组|
||$\begin{cases}f_x(x_0, y_0) + \lambda \phi_x(x_0, y_0) = 0 \\f_y(x_0, y_0) + \lambda \phi_y(x_0, y_0) = 0 \\\phi(x_0, y_0) = 0\end{cases}$|
||满足该方程组的点 $(x_0, y_0)$ 称为可能的极值点|
|||

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>设函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>与</mtext><mi>φ</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>具有连续的偏导数，作拉格朗日函数</mtext></mtd></mtr><mtr><mtd><mi>L</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>λ</mi><mo>)</mo><mo>=</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>+</mo><mi>λ</mi><mi>φ</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>,</mo></mtd></mtr><mtr><mtd><mtext>如果</mtext><mi>x</mi><mo>=</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><mi>y</mi><mo>=</mo><msub><mi>y</mi><mn>0</mn></msub><mtext>是方程组</mtext><msub><mi>L</mi><mi>x</mi></msub><mo>=</mo><mn>0</mn><mo>,</mo><msub><mi>L</mi><mi>y</mi></msub><mo>=</mo><mn>0</mn><mo>,</mo><msub><mi>L</mi><mi>λ</mi></msub><mo>=</mo><mn>0</mn><mtext>即</mtext></mtd></mtr><mtr><mtd><mrow><mo fence="true" stretchy="true">{</mo><mtable><mtr><mtd><msub><mi>f</mi><mi>x</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mi>λ</mi><msub><mi>φ</mi><mi>x</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn><mo>,</mo></mtd></mtr><mtr><mtd><msub><mi>f</mi><mi>y</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>+</mo><mi>λ</mi><msub><mi>φ</mi><mi>y</mi></msub><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn><mo>,</mo></mtd></mtr><mtr><mtd><mi>φ</mi><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mo>=</mo><mn>0</mn></mtd></mtr></mtable></mrow></mtd></mtr><mtr><mtd><mtext>的解，那么点</mtext><mo>(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo>)</mo><mtext>是目标函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>在约束条件</mtext><mi>φ</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>=</mo><mn>0</mn><mtext>下的可疑极值点。</mtext></mtd></mtr></mtable></math></div>

~~拉格朗日乘数法将条件极值问题转化为无条件极值问题, 通过引入乘数 $\lambda$ 将约束融入目标函数. 对于 $n$ 个自变量 $m$ 个约束的情形, 需引入 $m$ 个乘数.~~


|拉格朗日乘数法求条件极值的步骤||
|-:|:-|
|1. *构造拉格朗日函数*|$L(x, y, \lambda) = f(x, y) + \lambda \varphi(x, y)$|
|2. *解方程组得可疑极值点*|$\begin{cases}L_x = f_x(x, y) + \lambda \varphi_x(x, y) = 0 \\L_y = f_y(x, y) + \lambda \varphi_y(x, y) = 0 \\L_\lambda = \varphi(x, y) = 0\end{cases}$|
|3.*判断*|极大值点或极小值点需进一步判断,一般在实际问题中根据问题本身来判定|

#### 多元函数的最值
||求有界闭区域 $D$ 上的有连续偏导数的函数 $z = f(x, y)$ 的最值||
|-|-|:-|
|1.|求 $f(x, y)$ 在 $D$ 内部的所有驻点|无条件极值|
|2.|求 $f(x, y)$ 在 $\partial D$ 上的极值|条件极值|
|3.|比较上述函数值, 最大(小)者即为最值.||




## 重积分



|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|
|||
|-:|:-|









切向量（方向向量）为
$\vec{\tau} = \nabla F \times \nabla G \big|{M_0} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \ F_x & F_y & F_z \ G_x & G_y & G_z \end{vmatrix}{M_0}$
即 $\vec{\tau} = \left( \begin{vmatrix} F_y & F_z \ G_y & G_z \end{vmatrix}{M_0}, \begin{vmatrix} F_z & F_x \ G_z & G_x \end{vmatrix}{M_0}, \begin{vmatrix} F_x & F_y \ G_x & G_y \end{vmatrix}_{M_0} \right)$.

切线方程（对称式）：
$\frac{x - x_0}{\tau_x} = \frac{y - y_0}{\tau_y} = \frac{z - z_0}{\tau_z}$，其中 $\tau_x, \tau_y, \tau_z$ 为 $\vec{\tau}$ 的分量.

法平面方程（过切点且与切线垂直的平面）：
$\tau_x (x - x_0) + \tau_y (y - y_0) + \tau_z (z - z_0) = 0$.


