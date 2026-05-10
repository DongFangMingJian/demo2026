

### 数量值函数的积分
> 数量值函数的积分区域没有方向性

#### 第一类曲线积分
> 第一类曲线积分与曲线的方向无关, 只依赖于曲线的几何形状
##### 物理意义
> 线密度为 $\rho(x,y,z)$的光滑曲线 $L$ 的质量, 其中 $\mathrm{d}s$ 是弧长微元.
##### 几何意义
> 柱面的准线: $L: \phi(x, y) = 0$ 是一条平面曲线
> 另有一条空间曲线 $L_1$ 由 $\begin{cases} z = f(x, y) \\ \phi(x, y) = 0 \end{cases}$ 给出, 即 $L_1$ 在 $xOy$ 面上的投影与 $L$ 重合, 且高度随 $(x,y)$ 变化.
> 求以 $L$ 为准线, 母线平行于 $z$ 轴, 且介于平面 $z=0$ 与曲面 $z=f(x,y)$ 之间的**柱面的面积**. 




<svg viewBox="0 0 400 400" width = 200 xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="black" />
    </marker>
  </defs>

  <g fill="none" stroke="black" stroke-width="1.5">
    <line x1="150" y1="230" x2="150" y2="50" marker-end="url(#arrow)" />
    <line x1="150" y1="230" x2="350" y2="230" marker-end="url(#arrow)" />
    <line x1="150" y1="230" x2="50" y2="330" marker-end="url(#arrow)" />
  </g>

  <g font-family="Times New Roman, serif" font-style="italic" font-size="22">
    <text x="40" y="340">x</text>
    <text x="360" y="240">y</text>
    <text x="130" y="60">z</text>
    <text x="160" y="245" font-weight="bold">O</text>
  </g>

  <g stroke="#00008b" stroke-width="1.5">
    <line x1="110" y1="270" x2="110" y2="230" />
    <line x1="150" y1="260" x2="150" y2="190" />
    <line x1="195" y1="258" x2="195" y2="145" />
    <line x1="245" y1="270" x2="245" y2="115" />
    <line x1="280" y1="230" x2="280" y2="85" />
  </g>

  <path d="M 110 270 C 135 262, 170 255, 195 258 C 220 261, 265 285, 280 230" fill="none" stroke="black" stroke-width="2" />
  <text x="230" y="325" font-family="Times New Roman, serif" font-style="italic" font-size="24">L</text>

  <path d="M 110 230 C 135 205, 170 160, 195 145 C 220 130, 265 105, 280 85" fill="none" stroke="red" stroke-width="2.5" />
  <text x="295" y="145" font-family="Times New Roman, serif" font-style="italic" font-size="24">L<tspan baseline-shift="sub" font-size="14">1</tspan></text>

  <text x="190" y="90" font-family="Times New Roman, serif" font-size="24">
    <tspan font-style="italic">z = f(x, y)</tspan>
  </text>
</svg>

##### 求解过程
|*分割*|用点 $M_1, \cdots, M_{n-1}$ 分割曲线 $L$|
|-:|:-|
|*近似*|$\Delta A_i \approx f(\xi_i, \eta_i) \Delta s_i$;|
|*求和*|$A = \sum\limits_{i=1}^n \Delta A_i \approx \sum\limits_{i=1}^n f(\xi_i, \eta_i) \Delta s_i$;|
|*取极限*|$A = \lim\limits_{\lambda \to 0} \sum\limits_{i=1}^n f(\xi_i, \eta_i) \Delta s_i$.|


##### 定义
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>设</mtext><mi>Γ</mi><mtext>是以</mtext><mi>A</mi><mo>,</mo><mi>B</mi><mtext>为端点的平面光滑曲线弧，函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>在</mtext><mi>Γ</mi><mtext>上有界。若</mtext></mtd></mtr><mtr><mtd><munder><mo>lim</mo><mrow><mi>λ</mi><mo>→</mo><mn>0</mn></mrow></munder><munderover><mo>∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mi>f</mi><mo>(</mo><msub><mi>ξ</mi><mi>i</mi></msub><mo>,</mo><msub><mi>η</mi><mi>i</mi></msub><mo>)</mo><mi>Δ</mi><msub><mi>s</mi><mi>i</mi></msub></mtd></mtr><mtr><mtd><mtext>记为</mtext><munder><mo>∫</mo><mi>Γ</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mi mathvariant="normal">d</mi><mi>s</mi><mo>.</mo></mtd></mtr><mtr><mtd><mtext>存在,称此极限为数量值函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>在</mtext><mi>Γ</mi><mtext>上的曲线积分,也叫</mtext><mtext>第一类曲线积分</mtext><mtext>或对弧长的曲线积分。</mtext></mtd></mtr><mtr><mtd><mtext>其中</mtext><mi>λ</mi><mo>=</mo><mi>max</mi><mo>{</mo><mi>Δ</mi><msub><mi>s</mi><mi>i</mi></msub><mo>}</mo><mo>.</mo></mtd></mtr></mtable></math></div>

> 若 $L$ 为封闭曲线, 常记作 $\oint_L f(x, y) \, \mathrm{d}s$.

##### 性质 (以二元函数为例)
|*存在性*|若 $f \in C(L)$, 则 $\int_L f(x, y) \, \mathrm{d}s$ 存在;|
|-:|:-|
|*求弧长*|当 $f(x, y) \equiv 1$ 时, $\int_L \, \mathrm{d}s$ 等于曲线弧 $L$ 的长度;|
|*线性性*|$\int_L [\alpha f(x, y) + \beta g(x, y)] \, \mathrm{d}s = \alpha \int_L f(x, y) \, \mathrm{d}s + \beta \int_L g(x, y) \, \mathrm{d}s$;|
|*区域可加性*|若 $L = L_1 \cup L_2$ (且 $L_1$, $L_2$ 只在端点相交), 则 $\int_L f(x, y) \, \mathrm{d}s = \int_{L_1} f(x, y) \, \mathrm{d}s + \int_{L_2} f(x, y) \, \mathrm{d}s$;|

> ~~第一类曲线积分与曲线方向无关~~


##### 对称性及应用

|若 $L$ 关于 $y$ 轴对称,|$f(x,y)$ 关于 $x$ 为奇(偶)函数, 记 $L_1$ 为 $y$ 轴右半部分区域, 则|
|-:|:-|
||$\int_L f(x,y) \, \mathrm{d}s = \begin{cases} 0, & f(-x,y) = -f(x,y) \\ 2 \int_{L_1} f(x,y) \, \mathrm{d}s, & f(-x,y) = f(x,y) \end{cases}$|
|若 $L$ 关于 $x$ 轴对称,|$f(x,y)$ 关于 $y$ 为奇(偶)函数, 记 $L_1$ 为 $x$ 轴上(或右)半部分区域, 则|
||  $\int_L f(x,y) \, \mathrm{d}s = \begin{cases} 0, & f(x,-y) = -f(x,y) \\ 2 \int_{L_1} f(x,y) \, \mathrm{d}s, & f(x,-y) = f(x,y) \end{cases}$|
|轮换对称性|若曲线 $L$ 关于直线 $y=x$ 对称 (即 $L_{xy} = L_{yx}$), 则|
||  $\int_L f(x,y) \, \mathrm{d}s = \int_L f(y,x) \, \mathrm{d}s = \frac{1}{2} \int_L [f(x,y) + f(y,x)] \, \mathrm{d}s$.|


##### 计算法

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>设平面光滑曲线弧</mtext><mi>L</mi><mtext>由参数方程</mtext></mtd></mtr><mtr><mtd><mfenced open="{" close=""><mtable><mtr><mtd><mi>x</mi><mo>=</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo></mtd></mtr><mtr><mtd><mi>y</mi><mo>=</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr></mtable></mfenced><mo>,</mo><mtext> </mtext><mo>(</mo><mi>α</mi><mo>≤</mo><mi>t</mi><mo>≤</mo><mi>β</mi><mo>)</mo><mtext>给出，</mtext></mtd></mtr><mtr><mtd><mtext>函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mtext>在</mtext><mi>L</mi><mtext>上连续，则</mtext></mtd></mtr><mtr><mtd><munder><mo>∫</mo><mi>L</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>s</mi><mo>=</mo><msubsup><mo>∫</mo><mi>α</mi><mi>β</mi></msubsup><mi>f</mi><mo>[</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>]</mo><msqrt><mrow><mo>[</mo><msup><mi>x</mi><mo>′</mo></msup><mo>(</mo><mi>t</mi><mo>)</mo><msup><mo>]</mo><mn>2</mn></msup><mo>+</mo><mo>[</mo><msup><mi>y</mi><mo>′</mo></msup><mo>(</mo><mi>t</mi><mo>)</mo><msup><mo>]</mo><mn>2</mn></msup></mrow></msqrt><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>t</mi><mo>.</mo></mtd></mtr><mtr><mtd><mtext>其中下限</mtext><mi>α</mi><mtext>小于上限</mtext><mi>β</mi><mo>.</mo></mtd></mtr></mtable></math></div>


||*特殊形式*:|
|-:|:-|
||**代曲线**|


$\boxed{
\begin{array}{l}
(1)\ \text{若 } L: y = y(x),\ a \le x \le b,\ \text{则} \\
\displaystyle \int\limits_L f(x,y)\,\mathrm{d}s = \int_a^b f[x, y(x)] \sqrt{1+[y'(x)]^2}\,\mathrm{d}x; \\
(2)\ \text{若 } L: x = x(y),\ c \le y \le d,\ \text{则} \\
\displaystyle \int\limits_L f(x,y)\,\mathrm{d}s = \int_c^d f[x(y), y] \sqrt{1+[x'(y)]^2}\,\mathrm{d}y; \\
(3)\ \text{若 } L: r = r(\theta),\ \alpha \le \theta \le \beta\ \text{(极坐标), 则} \\
\displaystyle \int\limits_L f(x,y)\,\mathrm{d}s = \int_\alpha^\beta f[r(\theta)\cos\theta, r(\theta)\sin\theta] \sqrt{[r(\theta)]^2 + [r'(\theta)]^2}\,\mathrm{d}\theta.
\end{array}
}$

推广到空间中:

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mtext>在空间曲线上的第一类曲线积分：</mtext></mtd></mtr><mtr><mtd><mtext>设空间光滑曲线弧</mtext><mi>Γ</mi><mtext>:</mtext><mfenced open="{" close=""><mtable><mtr><mtd><mi>x</mi><mo>=</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr><mtr><mtd><mi>y</mi><mo>=</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr><mtr><mtd><mi>z</mi><mo>=</mo><mi>z</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr></mtable></mfenced><mtext> </mtext><mo>(</mo><mi>a</mi><mo>≤</mo><mi>t</mi><mo>≤</mo><mi>β</mi><mo>)</mo><mo>,</mo></mtd></mtr><mtr><mtd><mtext>函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mtext>在</mtext><mi>Γ</mi><mtext>上连续，则：</mtext></mtd></mtr><mtr><mtd><munder><mo>∫</mo><mi>Γ</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>s</mi><mo>=</mo><msubsup><mo>∫</mo><mi>α</mi><mi>β</mi></msubsup><mi>f</mi><mo>[</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo><mi>z</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>]</mo><msqrt><mrow><msup><mi>x</mi><mo>′</mo></msup><msup><mo>(</mo><mi>t</mi><mo>)</mo><mn>2</mn></msup><mo>+</mo><msup><mi>y</mi><mo>′</mo></msup><msup><mo>(</mo><mi>t</mi><mo>)</mo><mn>2</mn></msup><mo>+</mo><msup><mi>z</mi><mo>′</mo></msup><msup><mo>(</mo><mi>t</mi><mo>)</mo><mn>2</mn></msup></mrow></msqrt><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>t</mi><mo>.</mo></mtd></mtr></mtable></math></div>

#### 第一类曲面积分

##### 物理意义
> 面密度为连续函数$\mu (x ,y, z)$的光滑曲面$\varSigma$ 的质量

##### 求解过程
|*分割*|将曲面 $\Sigma$ 分割为若干小块曲面 $\Delta S_i$, $(\xi_i, \eta_i, \zeta_i)$ 为其中任一点.| 
|-:|:-|
|*近似*|$\Delta m_i \approx \mu(\xi_i, \eta_i, \zeta_i)\Delta S_i$.|
|*求和*| 求面密度为连续函数 $\mu(x, y, z)$ 的光滑曲面 $\Sigma$ 的质量.|
|*取极限*|  $M = \lim\limits_{\lambda \to 0} \sum_{i=1}\limits^n \mu(\xi_i, \eta_i, \zeta_i)\Delta S_i$.|

##### 定义

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>称</mtext><munder><mrow><mo>∬</mo></mrow><mi>Σ</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mspace width="0.1em"/><mi>d</mi><mi>S</mi><mo>=</mo><munder><mo>lim</mo><mrow><mi>λ</mi><mo>→</mo><mn>0</mn></mrow></munder><munderover><mo>∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mi>f</mi><mo>(</mo><msub><mi>ξ</mi><mi>i</mi></msub><mo>,</mo><msub><mi>η</mi><mi>i</mi></msub><mo>,</mo><msub><mi>ζ</mi><mi>i</mi></msub><mo>)</mo><mi>Δ</mi><msub><mi>S</mi><mi>i</mi></msub></mtd></mtr><mtr><mtd><mtext>为数量值函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mtext>在曲面</mtext><mi>Σ</mi><mtext>上的曲面积分，也叫第一类曲面积分或对面积的曲面积分</mtext></mtd></mtr></mtable></math></div>

> ~~第一类曲面积分与曲面方向无关, 类似于重积分推广到曲面上.~~

$$\iint\limits_{\underset{\text{\large 积分区域}}{\colorbox{lightblue}{$\varSigma$}}} 
\underset{\text{\large 被积函数}}{\colorbox{lightgreen}{$f(x, y, z)$}} \, \mathrm{d}S = 
{\lim\limits_{\lambda \to 0} \sum\limits_{i=1}^n 
\underset{\text{\large 被积函数}}{\colorbox{lightgreen}{$f(\xi_i, \eta_i, \zeta_i)$}} \Delta S_i}$$

*闭曲面*: 若 $\varSigma$ 为闭曲面, 常记作 $\oiint\limits_{\varSigma} f(x, y, z) \, \mathrm{d}S$



<svg viewBox="0 0 450 400" width = 200 xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="black" />
    </marker>
  </defs>

  <g stroke="black" stroke-width="1.5" fill="none">
    <line x1="80" y1="280" x2="80" y2="40" marker-end="url(#arrow)" />
    <line x1="80" y1="280" x2="400" y2="280" marker-end="url(#arrow)" />
    <line x1="80" y1="280" x2="20" y2="360" marker-end="url(#arrow)" />
  </g>

  <g font-family="Times New Roman, serif" font-style="italic" font-size="22" fill="black">
    <text x="10" y="360">x</text>
    <text x="405" y="300">y</text>
    <text x="95" y="50">z</text>
    <text x="55" y="275" font-style="normal" font-weight="bold">O</text>
  </g>

  <path d="M 120 200 C 150 80, 280 60, 360 100 C 400 120, 380 200, 350 230 C 280 280, 160 260, 120 200 Z" fill="#FFA07A" fill-opacity="0.1" stroke="#FFA07A" stroke-width="3" />
  <text x="130" y="210" font-family="Times New Roman, serif" font-style="italic" font-size="28">Σ</text>

  <g stroke="black" stroke-width="1.5" stroke-dasharray="4,3">
    <line x1="200" y1="206" x2="200" y2="336" />
    <line x1="220" y1="158" x2="220" y2="308" />
    <line x1="240" y1="196" x2="240" y2="336" />
    <line x1="260" y1="148" x2="260" y2="308" />
  </g>

  <polygon points="220,308 260,308 240,336 200,336" fill="#F4D03F" fill-opacity="0.8" stroke="black" stroke-width="1.5" />
  <text x="245" y="340" font-family="Times New Roman, serif" font-style="italic" font-weight="bold" font-size="24">D<tspan baseline-shift="sub" font-size="14">i</tspan></text>

  <path d="M 220 158 Q 240 148 260 148 Q 255 172 240 196 Q 220 206 200 206 Q 205 182 220 158 Z" fill="white" stroke="black" stroke-width="2.5" />
  
  <line x1="280" y1="120" x2="260" y2="140" stroke="black" stroke-width="1.5" marker-end="url(#arrow)" />
  <text x="285" y="115" font-family="Times New Roman, serif" font-style="italic" font-size="22" font-weight="bold">Σ<tspan baseline-shift="sub" font-size="14">i</tspan></text>

  <line x1="230" y1="177" x2="230" y2="322" stroke="#FF7F50" stroke-width="2" />

  <circle cx="230" cy="177" r="4.5" fill="#FFA07A" stroke="black" stroke-width="0.5" />
  <circle cx="230" cy="322" r="4.5" fill="red" />

  <text x="245" y="185" fill="#00008b" font-family="Times New Roman, serif" font-size="22">
    <tspan font-style="italic">M(ξ</tspan><tspan baseline-shift="sub" font-size="14">i</tspan>
    <tspan font-style="italic">, η</tspan><tspan baseline-shift="sub" font-size="14">i</tspan>
    <tspan font-style="italic">, ζ</tspan><tspan baseline-shift="sub" font-size="14">i</tspan><tspan>)</tspan>
  </text>

  <text x="265" y="315" fill="#00008b" font-family="Times New Roman, serif" font-size="22">
    <tspan font-style="italic">(ξ</tspan><tspan baseline-shift="sub" font-size="14">i</tspan>
    <tspan font-style="italic">, η</tspan><tspan baseline-shift="sub" font-size="14">i</tspan><tspan>)</tspan>
  </text>
  
  <line x1="262" y1="311" x2="236" y2="320" stroke="#FF7F50" stroke-width="1.5" />
</svg>



##### 性质
|**存在性**|若 $f(x, y, z) \in C(\Sigma)$, 则 $\iint\limits_{\Sigma} f(x, y, z) \, \mathrm{d}S$ 存在.|
|-:|:-|
||~~积分存在条件为 $f$ 在 $\varSigma$ 上连续.~~|
|**面积公式**|若 $f(x, y, z) \equiv 1$, 则 $\iint\limits_{\varSigma} \, \mathrm{d}S = \varSigma$ 的面积.
|**线性性**|$\iint\limits_{\varSigma} [\alpha f(x, y, z) + \beta g(x, y, z)] \, \mathrm{d}S = \alpha \iint\limits_{\varSigma} f(x, y, z) \, \mathrm{d}S + \beta \iint\limits_{\varSigma} g(x, y, z) \, \mathrm{d}S$.
|**曲面可加性**|若 $\varSigma = \varSigma_1 + \varSigma_2$, 则  $\iint\limits_{\varSigma} f(x, y, z) \, \mathrm{d}S = \iint\limits_{\varSigma_1} f(x, y, z) \, \mathrm{d}S + \iint\limits_{\varSigma_2} f(x, y, z) \, \mathrm{d}S$|

> ~~第一类曲面积分与二重积分类似, 具有线性、可加性, 且当被积函数为1时给出曲面面积.~~ 

##### 对称性及应用

> 当区域 $\varSigma$ 关于 $xOy$ ($z=0$) 平面对称时:
> $\iint\limits_{\varSigma} f(x, y, z) \, \mathrm{d}S = \begin{cases} 0, & f(x, y, -z) = -f(x, y, z) \\ 2 \iint\limits_{\varSigma_1} f(x, y, z) \, \mathrm{d}S, & f(x, y, -z) = f(x, y, z) \end{cases}$
> 其中 $\varSigma_1$ 是 $\varSigma$ 位于 $xOy$ 平面上半部分的区域.
> 若关于其它坐标面对称, 也有相应的性质.
> ~~利用对称性简化曲面积分计算, 类似于重积分中奇偶性在对称区域上的应用~~




##### 计算法

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>设</mtext><mi>Σ</mi><mtext>:</mtext><mi>z</mi><mo>=</mo><mi>z</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>,</mo><mtext>其中</mtext><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>∈</mo><msub><mi>D</mi><mrow><mi>x</mi><mi>y</mi></mrow></msub><mo>.</mo></mtd></mtr><mtr><mtd><munder><mo>∬</mo><mi>Σ</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>S</mi><mo>=</mo><munder><mo>∬</mo><msub><mi>D</mi><mrow><mi>x</mi><mi>y</mi></mrow></msub></munder><mi>f</mi><mo>[</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>]</mo><msqrt><mrow><mn>1</mn><mo>+</mo><msup><mrow><mo>(</mo><msubsup><mi>z</mi><mi>x</mi><mo>′</mo></msubsup><mo>)</mo></mrow><mn>2</mn></msup><mo>+</mo><msup><mrow><mo>(</mo><msubsup><mi>z</mi><mi>y</mi><mo>′</mo></msubsup><mo>)</mo></mrow><mn>2</mn></msup></mrow></msqrt><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>x</mi><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>y</mi><mo>.</mo></mtd></mtr></mtable></math></div>



|*同理*|若 $\Sigma: y = y(x, z)$, $(x, z) \in D_{xz}$, 则|
|-:|:-|
||$\iint\limits_{\Sigma} f(x, y, z) \, \mathrm{d}S = \iint\limits_{D_{xz}} f[x, y(x, z), z] \sqrt{1 + (y_x')^2 + (y_z')^2} \, \mathrm{d}x\mathrm{d}z.$|
||若 $\Sigma: x = x(y, z)$, $(y, z) \in D_{yz}$, 则|
||$\iint\limits_{\Sigma} f(x, y, z) \, \mathrm{d}S = \iint\limits_{D_{yz}} f[x(y, z), y, z] \sqrt{1 + (x_y')^2 + (x_z')^2} \, \mathrm{d}y\mathrm{d}z.$|

>  ~~第一类曲面积分通过投影化为二重积分, 其中根号项为曲面面积元与坐标面面积元的比例因子, 即 **$\sqrt{1 + z_x^2 + z_y^2}$** 等.~~


### 向量值函数的积分
#### 第二类曲线积分
##### 定向曲线及其切向量
|*定向曲线*|规定了走向的曲线, 记为 $L$, 则其反方向记为 $L^-$.|
|-:|:-|
||$L = \overrightarrow{AB}$ 表示曲线 $L$ 的起点为 $A$, 终点为 $B$.|
|*定向光滑曲线上的切向量*|规定切向量的方向与曲线的走向一致.|


##### 定义
||设 $L$ 是 $xOy$ 面上的一条光滑的定向曲线弧,
|-:|:-|
||$\vec{F}(x, y) = (P(x, y), Q(x, y))$ 在 $L$ 上有界,|
||记 $\vec{e}_{\tau}(x, y) = (\cos\alpha, \cos\beta)$ 为 $L$ 上点 $(x, y)$ 处的单位切向量. |
||若 $\int_L P(x, y) \cos\alpha \, \mathrm{d}s$ 与 $\int_L Q(x, y) \cos\beta \, \mathrm{d}s$ 均存在,|
||则称它们的和为 $F$ 沿 $L$ 的第二类曲线积分, 记作 $\int_L P\, \mathrm{d}x + Q\, \mathrm{d}y$,|
|即||
<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mrow><munder><mo>∫</mo><mi>L</mi></munder><mover><mi>F</mi><mo>→</mo></mover><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mo>·</mo><mi mathvariant="normal">d</mi><mover><mi>s</mi><mo>→</mo></mover><mo>=</mo><munder><mo>∫</mo><mi>L</mi></munder><mi>P</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>x</mi><mo>+</mo><mi>Q</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>y</mi><mo>=</mo><munder><mo>∫</mo><mi>L</mi></munder><mrow><mo>[</mo><mi>P</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mi>cos</mi><mo>⁡</mo><mi>α</mi><mo>+</mo><mi>Q</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mi>cos</mi><mo>⁡</mo><mi>β</mi><mo>]</mo></mrow><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>s</mi><mo>.</mo></mrow></math></div>


<svg viewBox="0 0 240 220" width = 100 xmlns="http://www.w3.org/2000/svg">
  <polygon points="40,160 160,160 160,40" fill="none" stroke="#00008b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" />

  <g font-family="Times New Roman, serif" fill="black" font-style="italic">
    <text x="100" y="190" font-size="28" text-anchor="middle">dx</text>
    <text x="175" y="105" font-size="28" text-anchor="start">dy</text>
    <text x="80" y="85" font-size="28" text-anchor="middle">ds</text>
  </g>
  <g font-family="Times New Roman, serif" fill="black" font-style="italic">
    <text x="75" y="150" font-size="26" text-anchor="middle">α</text>
    <text x="140" y="90" font-size="26" text-anchor="middle">β</text>
  </g>
</svg>


##### 性质
> 如果把被积函数看作一个整体，它是第一类曲线积分，具有第一类曲线积分的所有性质。
> 作为第二类曲线积分，有如下两个独有的性质：
> 
|*方向性*|$\int\limits_{L^-} \vec{F}(x,y) \cdot \mathrm{d}\vec{s} = -\int\limits_L \vec{F}(x,y) \cdot \mathrm{d}\vec{s}$ (其中 $L^-$ 为 $L$ 的反向曲线).|
|-:|:-|
|*线性性,曲线弧可加性*|$\int_{L_{AB}} \vec{F}(x,y) \cdot \mathrm{d}\vec{s} = \int_{L_{AC}} \vec{F}(x,y) \cdot \mathrm{d}\vec{s} + \int_{L_{CB}} \vec{F}(x,y) \cdot \mathrm{d}\vec{s}$.|



##### 计算法


<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>设平面上定向光滑曲线</mtext><mi>L</mi><mtext>:</mtext><mfenced open="{" close=""><mtable><mtr><mtd><mi>x</mi><mo>=</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr><mtr><mtd><mi>y</mi><mo>=</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo></mtd></mtr></mtable></mfenced><mtext> </mtext><mi>t</mi><mtext>:</mtext><mi>a</mi><mo>→</mo><mi>b</mi><mo>,</mo></mtd></mtr><mtr><mtd><munder><mo>∫</mo><mi>L</mi></munder><mi>P</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>x</mi><mo>+</mo><mi>Q</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>)</mo><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>y</mi></mtd></mtr><mtr><mtd><mo>=</mo><msubsup><mo>∫</mo><mi>a</mi><mi>b</mi></msubsup><mrow><mo>{</mo><mi>P</mi><mo>[</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>]</mo><msup><mi>x</mi><mo>′</mo></msup><mo>(</mo><mi>t</mi><mo>)</mo><mo>+</mo><mi>Q</mi><mo>[</mo><mi>x</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>,</mo><mi>y</mi><mo>(</mo><mi>t</mi><mo>)</mo><mo>]</mo><msup><mi>y</mi><mo>′</mo></msup><mo>(</mo><mi>t</mi><mo>)</mo><mo>}</mo></mrow><mspace width="0.1em"/><mi mathvariant="normal">d</mi><mi>t</mi><mo>.</mo></mtd></mtr></mtable></math></div>


|*特别地*,|若 $L: y = y(x)$, $x: a \to b$, 则|
|-:|:-|
||$\int\limits_L P(x, y)\,\mathrm{d}x + Q(x, y)\,\mathrm{d}y = \int_a^b \bigl\{P[x, y(x)] + Q[x, y(x)]\, y'(x)\bigr\}\,\mathrm{d}x.$|
||若 $L: x = x(y)$, $y: c \to d$, 则|
||$\int\limits_L P(x, y)\,\mathrm{d}x + Q(x, y)\,\mathrm{d}y = \int_c^d \bigl\{P[x(y), y]\, x'(y) + Q[x(y), y]\bigr\}\,\mathrm{d}y.$|
||~~注意积分方向与参数增加方向一致~~.|
|*类似地*,|可以定义三维向量值函数$F(x, y, z) = (P(x, y, z), Q(x, y, z), R(x, y, z))$|
||在空间定向光滑曲线上的第二类曲线积分为|
||$\int\limits_{\Gamma} F(x, y, z) \cdot \mathrm{d}\vec{s} = \int\limits_{\Gamma} P(x, y, z)\,\mathrm{d}x + Q(x, y, z)\,\mathrm{d}y + R(x, y, z)\,\mathrm{d}z$.|
||其中 $\mathrm{d}\vec{s} = (\mathrm{d}x, \mathrm{d}y, \mathrm{d}z)$ 为有向弧长微元, 积分与方向有关.|