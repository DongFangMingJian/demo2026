## 重积分

### 第一类曲面积分

#### 物理意义
> 面密度为连续函数$\mu (x ,y, z)$的光滑曲面$\varSigma$ 的质量

#### 求解过程
|*分割*|将曲面 $\Sigma$ 分割为若干小块曲面 $\Delta S_i$, $(\xi_i, \eta_i, \zeta_i)$ 为其中任一点.| 
|-:|:-|
|*近似*|$\Delta m_i \approx \mu(\xi_i, \eta_i, \zeta_i)\Delta S_i$.|
|*求和*| 求面密度为连续函数 $\mu(x, y, z)$ 的光滑曲面 $\Sigma$ 的质量.|
|*取极限*|  $M = \lim\limits_{\lambda \to 0} \sum_{i=1}\limits^n \mu(\xi_i, \eta_i, \zeta_i)\Delta S_i$.|

#### 定义

<div class="boxed-formula"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable><mtr><mtd><mtext>称</mtext><munder><mrow><mo>∬</mo></mrow><mi>Σ</mi></munder><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mspace width="0.1em"/><mi>d</mi><mi>S</mi><mo>=</mo><munder><mo>lim</mo><mrow><mi>λ</mi><mo>→</mo><mn>0</mn></mrow></munder><munderover><mo>∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mi>f</mi><mo>(</mo><msub><mi>ξ</mi><mi>i</mi></msub><mo>,</mo><msub><mi>η</mi><mi>i</mi></msub><mo>,</mo><msub><mi>ζ</mi><mi>i</mi></msub><mo>)</mo><mi>Δ</mi><msub><mi>S</mi><mi>i</mi></msub></mtd></mtr><mtr><mtd><mtext>为数量值函数</mtext><mi>f</mi><mo>(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo>)</mo><mtext>在曲面</mtext><mi>Σ</mi><mtext>上的曲面积分，也叫第一类曲面积分或对面积的曲面积分</mtext></mtd></mtr></mtable></math></div>

> ~~第一类曲面积分与曲面方向无关, 类似于重积分推广到曲面上.~~


$$\iint\limits_{\colorbox{lightblue}{$\varSigma$}} f(x, y, z) \, \mathrm{d}S = {\lim\limits_{\lambda \to 0} \sum\limits_{i=1}^n f(\xi_i, \eta_i, \zeta_i) \Delta S_i}$$


#### 性质
