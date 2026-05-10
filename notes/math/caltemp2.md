### 多元函数的极限
#### 二重极限的定义
#### 证明二重极限不存在
|*单路径法*|找到某一条 $P \to P_0$ 的路径，极限值不存在。|
|-:|:-|
|*两路径法*|找到 $P \to P_0$ 的两条不同路径，极限值不相等。|
|*$y = kx^p$ 路径法*|极限值与 $k$ 有关。|
||~~常用作**齐次化**~~|
|*极坐标换元法*|$\rho \to 0^+$ 时，极限值与 $\theta$ 有关。|






##### 二级结论
1. 当 $(x,y)\to(0,0)$ 时，若分母在 $(0,0)$ 的任意去心邻域内都可取$0$, 
如$x-y, xy$等, 极限往往不存在(非绝对结论)

2. 对于二重极限 $\lim\limits_{(x,y)\to(0,0)} \dfrac{x^p y^q}{x^m + y^n}$ ($m,n \in \mathbb{N}^*,\ p,q>0$), 有以下结论:

(1) 若 $m,n$ 中有奇数, 则极限不存在.

(2) 若 $m,n$ 全为偶数, 则:
   - 当 $\dfrac{p}{m} + \dfrac{q}{n} > 1$ 时, 极限为 $0$;
   - 当 $\dfrac{p}{m} + \dfrac{q}{n} \le 1$ 时, 极限不存在, 可取路径 $y = k x^{\frac{m-p}{q}}$ 说明.











### 偏导数
#### 偏导数的定义


||设函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ 的某邻域内有定义，如果极限|
|-:|:-|
||$\lim\limits_{\Delta x \to 0} \dfrac{f(x_0 + \Delta x, y_0) - f(x_0, y_0)}{\Delta x}$|
||存在，则称此极限值为函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ 处对 $\color{red}{x}$ 的偏导数|
|记为|$\dfrac{\partial z}{\partial x}\rvert_{(x_0,y_0)},\quad \dfrac{\partial f}{\partial x}\rvert_{(x_0,y_0)},\quad z'_x(x_0, y_0)\ \text{或}\ f'_x(x_0, y_0)$，|
|即|

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{l}
f'_x(x_0, y_0) = \lim\limits_{\Delta x \to 0} \dfrac{f(x_0 + \Delta x, y_0) - f(x_0, y_0)}{\Delta x} \\
\text{或} \\
f'_x(x_0, y_0) = \lim\limits_{x \to x_0} \dfrac{f(x, y_0) - f(x_0, y_0)}{x - x_0}
\end{array}
}$
</div>

> ~~偏导数是多元函数沿坐标轴方向的变化率，计算时只对一个变量求导，其余视为常数。类似可定义对 $y$ 的偏导数~~

##### 求 $f(x,y)$ 在某点 $(x_0,y_0)$ 处的偏导数 $f_x(x_0,y_0)$


- **法一**：偏导数定义（多用于分段点处或公式法较麻烦时）。
- **法二**：先求偏导函数 $\dfrac{\partial z}{\partial x}$，再代入指定点 $(x_0,y_0)$。
- **法三**：代入 $y_0$ 降维，求 $\left[ f(x, y_0) \right]'_{x=x_0}$（~~首选, 直指本质~~）。



#### 高阶偏导数
> 函数 $z = f(x,y)$ 在区域 $D$ 内的偏导数 $f'_x(x,y)$ 和 $f'_y(x,y)$ 仍然是 $x,y$ 的二元函数,
如果 $f'_x(x,y)$ 和 $f'_y(x,y)$ 在区域 $D$ 内仍具有偏导数,则称它们的偏导数为函数 $z = f(x,y)$ 的**二阶偏导数**,记作：

$$
\begin{align*}
f''_{xx}(x,y) &= \frac{\partial}{\partial x}\left( \frac{\partial z}{\partial x} \right) = \frac{\partial^2 z}{\partial x^2}, \quad f''_{xy}(x,y) = \frac{\partial}{\partial y}\left( \frac{\partial z}{\partial x} \right) = \frac{\partial^2 z}{\partial x\partial y} \\
f''_{yx}(x,y) &= \frac{\partial}{\partial x}\left( \frac{\partial z}{\partial y} \right) = \frac{\partial^2 z}{\partial y\partial x}, \quad f''_{yy}(x,y) = \frac{\partial}{\partial y}\left( \frac{\partial z}{\partial y} \right) = \frac{\partial^2 z}{\partial y^2}
\end{align*}
$$

> 其中 $\displaystyle \frac{\partial^2 z}{\partial x\partial y}$ 和 $\displaystyle \frac{\partial^2 z}{\partial y\partial x}$ 称为**二阶混合偏导数**。类似地，可以定义更高阶的偏导数。

~~混合偏导数两种记号中, 都是哪个自变量写在前面就先对谁偏~~

|**混合偏导数可交换定理**|如果在点 $(x, y)$ 的邻域内函数 $z = f(x, y)$ 的偏导数|
|-:|:-|
||$\frac{\partial z}{\partial x}, \frac{\partial z}{\partial y}$ 及 $\frac{\partial^2 z}{\partial x \partial y}$ 都存在,|
||且 $\frac{\partial^2 z}{\partial x \partial y}$ 在点 $(x, y)$ 处连续,|
||那么混合偏导数 $\frac{\partial^2 z}{\partial y \partial x}$ 在点 $(x, y)$ 处也存在, 且 $\frac{\partial^2 z}{\partial x \partial y} = \frac{\partial^2 z}{\partial y \partial x}$.|

~~二阶混合偏导数在连续的条件下与求导次序无关. 高阶偏导数在偏导连续的条件下, 也与求导的次序无关, 比如 $f_{xyy} = f_{yyx}$.~~


##### 求高阶偏导数值

在计算多元函数在某点处的偏导数值时，可根据求导的“层次”选择是否先代入常量：

- *最后一层偏导*：指最终对目标变量的偏导。  
  例如计算 $f_x(x_0,y_0)$，可先代入 $y=y_0$ 得到一元函数 $g(x)=f(x,y_0)$，再求 $g'(x_0)$ 得到偏导数值。  
  **即：先代后求是可行的。**

- *最后一层之前*：即需要先对某个中间变量求偏导，再对最终变量求偏导。  
  例如计算混合偏导 $f_{xy}(x_0,y_0)$，必须先求出偏导函数 $f_{xy}(x,y)$，再代入点 $(x_0,y_0)$。  
  若先代入 $y=y_0$ 再对 $x$ 求导得 $f_x(x,y_0)$，此时已丢失 $y$ 的变量，无法继续对 $y$ 求导。  
  **因此：不可先代后求，必须先求偏导函数。**

- *例外情况*：如果对**同一变量**求**二阶纯偏导**（如 $f_{xx}(x_0,y_0)$），则仍可先代入 $y=y_0$，再对 $x$ 求二阶导。  
  因为求导变量始终是 $x$，与代入的 $y$ 无关。

**总结**：
- 最终对单一变量的偏导（一阶） → 可以“先代后求”。
- 混合偏导（先对 $x$ 再对 $y$，或反之） → 必须先求偏导函数再代点。
- 二阶纯偏导（对同一变量两次） → 可以“先代后求”。

~~该技巧能有效简化计算，但需谨慎判断求导次序与代入时机。~~

### 全微分
#### 偏增量与偏微分



> 若 $z = f(x, y)$ 在点 $(x_0, y_0)$ 处可偏导，则分别有对 $x$ 和对 $y$ 的线性近似：

|对 $x$ 的偏增量与偏微分|$f(x_0 + \Delta x, y_0) - f(x_0, y_0) =$|$f_x(x_0, y_0)\Delta x + o(\Delta x)$|
|-:|-:|:-|
|对 $y$ 的偏增量与偏微分|$f(x_0, y_0 + \Delta y) - f(x_0, y_0) =$|$f_y(x_0, y_0)\Delta y + o(\Delta y)$|
||$z=f(x,y)$在$(x_0,y_0)$对$x$和$y$的*偏增量*|$z=f(x,y)$在$(x_0,y_0)$对$x$和$y$的*偏微分*|
   
其中 $o(\Delta x)$ 和 $o(\Delta y)$ 为高阶无穷小。

上式说明一元函数的微分概念可推广到多元函数的偏增量，即固定其他变量时，函数增量可由偏导数线性主部加上高阶无穷小近似。

~~偏微分是沿着坐标轴方向的线性近似, **全微分是沿任意方向的线性近似**~~

#### 全微分的定义

|设|函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ 的某邻域内有定义,|
|-:|:-|
||且函数在点 $(x_0, y_0)$ 处的全增量|
||$\Delta z = f(x_0 + \Delta x, y_0 + \Delta y) - f(x_0, y_0)$
||可表示为
||$\Delta z = A\Delta x + B\Delta y + o(\rho)$,|
||其中系数 $A$ 和 $B$ 不依赖于 $\Delta x$ 和 $\Delta y$, $\rho = \sqrt{(\Delta x)^2 + (\Delta y)^2}$.|
||那么称函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ **可微**,|
||而线性主部 $A\Delta x + B\Delta y$ 称为函数 $z = f(x, y)$ 在点 $(x_0, y_0)$ 的**全微分**,|
||记作$dz$ 或 $df$,
|即|$dz = A\Delta x + B\Delta y$|
||如果函数在区域 $D$ 内各点处都可微, 那么称这函数在 $D$ 内可微.

~~全微分是函数增量的线性近似,且误差为 $\rho$ 的高阶无穷小.~~

#### $\mathrm{d}z = f_x(x_0, y_0)\,\mathrm{d}x + f_y(x_0, y_0)\,\mathrm{d}y$

> $f(x, y)$ 在点 $(x_0, y_0)$ 处可偏导，且 $z = f(x, y)$ 在点 $(x_0, y_0)$ 的全微分为：


<div align="center" style="font-size: 13px;">

$\boxed{dz = f_x(x_0, y_0)\,\mathrm{d}x + f_y(x_0, y_0)\,\mathrm{d}y}$
</div>

> *证明*:


#### 全微分求近似值

**第一步**，将原式看作 $f(x_0 + \Delta x, y_0 + \Delta y)$，写出 $x_0, y_0, \Delta x, \Delta y$；

**第二步**，由全微分近似公式 $f(x_0 + \Delta x, y_0 + \Delta y) \approx f(x_0, y_0) + A\Delta x + B\Delta y$，
其中 $A = f_x'(x_0, y_0),\ B = f_y'(x_0, y_0)$, 代入计算即可。

~~适用于求函数在某点附近值的近似~~


#### 可微的等价定义



|函数$z = f(x, y)$在点$(x_0, y_0)$可微|  $\Leftrightarrow \Delta z = A\Delta x + B\Delta y + o\left(\sqrt{(\Delta x)^2 + (\Delta y)^2}\right)$|
|-:|:-| 
||$\Leftrightarrow \lim\limits_{\substack{\Delta x \to 0 \\ \Delta y \to 0}} \dfrac{\Delta z - (A\Delta x + B\Delta y)}{\sqrt{(\Delta x)^2 + (\Delta y)^2}} = 0$|  
||$\Leftrightarrow \lim\limits_{\substack{\Delta x \to 0 \\ \Delta y \to 0}} \dfrac{\Delta z - \bigl(f_x(x_0,y_0)\Delta x + f_y(x_0,y_0)\Delta y\bigr)}{\sqrt{(\Delta x)^2 + (\Delta y)^2}} = 0$|

> *证明*

##### 判断二元函数的可微性
判定步骤:

**第一步**，求 $A = f_x'(x_0, y_0),\; B = f_y'(x_0, y_0)$.

**第二步**，令 $\Delta z = f(x_0 + \Delta x, y_0 + \Delta y) - f(x_0, y_0)$，求极限
\[
\lim_{\substack{\Delta x \to 0 \\ \Delta y \to 0}} \frac{\Delta z - (A\Delta x + B\Delta y)}{\sqrt{(\Delta x)^2 + (\Delta y)^2}}.
\]
*若该极限为 $0$，则可微；若不为 $0$ 或不存在，则不可微.*


#### 原函数连续、偏导数连续、可微、可偏导之间的关系


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


##### 可微的充分条件(能推出可微)




##### 可微的必要条件(由可微推出)


### 复合函数求导
#### 链式法则




##### 求一阶偏导

<svg width="320" height="220" viewBox="0 0 320 220" xmlns="http://www.w3.org/2000/svg">
  <style>
    .math { font-family: "Times New Roman", Times, serif; font-style: italic; font-size: 15px; fill: #1a1a1a; }
    .label { font-family: "Times New Roman", Times, serif; font-style: italic; font-size: 10px; fill: blue; }
    .line { stroke: #1a1a1a; stroke-width: 1; fill: none; }
  </style>
  <!-- 第一列：z = f -->
  <text x="8" y="110" class="math">z =</text>
  <text x="40" y="110" class="math">f</text>
  <!-- 从 f 到 u（右上）和 v（右下） -->
  <line x1="52" y1="105" x2="100" y2="60" class="line" />
  <line x1="52" y1="115" x2="100" y2="150" class="line" />
  <!-- 第二列：u, v -->
  <text x="108" y="64" class="math">u</text>
  <text x="108" y="154" class="math">v</text>
  <!-- 从 u 到 x（上）和 y（下） -->
  <line x1="120" y1="62" x2="170" y2="30" class="line" />
  <line x1="120" y1="62" x2="170" y2="90" class="line" />
  <!-- 从 v 到 x（上）和 y（下） -->
  <line x1="120" y1="152" x2="170" y2="120" class="line" />
  <line x1="120" y1="152" x2="170" y2="180" class="line" />
  <!-- 第三列：x, y, x, y -->
  <text x="178" y="34" class="math">x</text>
  <text x="178" y="94" class="math">y</text>
  <text x="178" y="124" class="math">x</text>
  <text x="178" y="184" class="math">y</text>
  <!-- 偏导数标签（放在线段旁边，避免重叠） -->
  <!-- f→u 标签在线的右上方 -->
  <text x="65" y="75" class="label">∂f/∂u</text>
  <!-- f→v 标签在线的右下方 -->
  <text x="65" y="135" class="label">∂f/∂v</text>
  <!-- u→x 标签在线下方 -->
  <text x="135" y="48" class="label">∂u/∂x</text>
  <!-- u→y 标签在线下方 -->
  <text x="135" y="85" class="label">∂u/∂y</text>
  <!-- v→x 标签在线下方 -->
  <text x="135" y="138" class="label">∂v/∂x</text>
  <!-- v→y 标签在线下方 -->
  <text x="135" y="175" class="label">∂v/∂y</text>
</svg>



###### 抽象函数求偏导
- $f_i'$：对函数 $f$ 的第 $i$ 个中间变量求（偏）导
- $f_{ij}''$：先对函数 $f$ 的第 $i$ 个中间变量求（偏）导，再对第 $j$ 个中间变量求（偏）导


###### 求高阶偏导

> 若 $z = f(u, v)$, 且 $u = u(x, y)$, $v = v(x, y)$, 则 $\frac{\partial z}{\partial x}$ 的表达式仍为关于 $u, v$ 的函数, 而 $u, v$ 依然依赖于 $x, y$
因此，依赖图的拓扑结构(即变量间的依赖关系)在求导后没有改变。
> 多元复合函数的偏导数(无论阶数)与原函数具有相同的变量依赖图, 
> 即中间变量集和作用关系保持不变,仅函数本身被其偏导替换。

### 隐函数求导

#### 一个方程的情形

##### 直接法


##### 一个方程的隐函数存在定理
|**二元隐函数存在定理**|设二元函数 $F(x, y)$ 在区域 $D$ 内具有连续偏导数,|
|-:|:-|
||点  $(x_0, y_0) \in D$ 且满足: $F(x_0, y_0) = 0, F_y(x_0, y_0) \neq 0$,|
||则方程 $F(x, y) = 0$ 在点 $(x_0, y_0)$的某邻域内唯一确定了一个有连续导数的一元函数 $y = y(x)$,|
||它满足条件 $y_0 =  y(x_0)$, 且有  
<div align="center" style="font-size: 13px;">

$\boxed{\dfrac{\mathrm{d}y}{\mathrm{d}x} = -\dfrac{F_x}{F_y}}$
</div>

|*证明:*||
|-:|:-|


|推论:**三元隐函数存在定理**|设三元函数 $F(x, y, z)$ 在区域 $\Omega$ 内具有连续偏导数,|
|-:|:-|
||点  $(x_0, y_0, z_0) \in \Omega$ 且满足: $F(x_0, y_0, z_0) = 0$, $F_z(x_0, y_0, z_0) \neq 0$,|
||则方程 $F(x, y, z) = 0$ 在|
||点 $(x_0, y_0, z_0)$ 的某邻域内唯一确定了一个有连续偏导数的二元函数 $z = z(x, y)$,|
||它满足条件 $z_0 = z(x_0, y_0)$, 且有 |


<div align="center" style="font-size: 13px;">

$\boxed{\dfrac{\partial z}{\partial x} = -\dfrac{F_x}{F_z},\quad \dfrac{\partial z}{\partial y} = -\dfrac{F_y}{F_z}}$
</div>

#### 方程组的情形
~~若 $n$ 个方程, $m$ 个未知量满足隐函数存在定理的条件, 可确定 $n$ 个 $m-n$ 元函数~~
##### 方程组的隐函数存在定理
1. 对方程组$\begin{cases}
  F(x,y,z)=0 \\ G(x,y,z)=0
\end{cases}$ 的每个方程, 分别对目标自变量求偏导(直接法)

2. 得到关于偏导数$\large{\frac{\mathrm{d}y}{\mathrm{d}x}, \frac{\mathrm{d}z}{\mathrm{d}x}}$的线性方程组$$\large{\begin{cases}
  F_x + F_y \frac{\mathrm{d}y}{\mathrm{d}x} +F_z \frac{\mathrm{d}z}{\mathrm{d}x} = 0, \\ G_x + G_y \frac{\mathrm{d}y}{\mathrm{d}x} +G_z \frac{\mathrm{d}z}{\mathrm{d}x} = 0
\end{cases}}$$
即$$\large{\begin{cases}
  F_y \frac{\mathrm{d}y}{\mathrm{d}x} +F_z \frac{\mathrm{d}z}{\mathrm{d}x} = -F_x, \\  G_y \frac{\mathrm{d}y}{\mathrm{d}x} +G_z \frac{\mathrm{d}z}{\mathrm{d}x} = -G_x
\end{cases}}$$
3. 用克莱姆法则求解线性方程组:
系数行列式 $J = \begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix} = F_y G_z - F_z G_y \neq 0$ (隐函数存在条件).
则$\large{\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{\Delta_y}{J},\quad \frac{\mathrm{d}z}{\mathrm{d}x} = \frac{\Delta_z}{J}}$,
其中
$\Delta_y = \begin{vmatrix} -F_x & F_z \\ -G_x & G_z \end{vmatrix}, \Delta_z = \begin{vmatrix} F_y & -F_x \\ G_y & -G_x \end{vmatrix}$.
因此
<div align="center" style="font-size: 13px;">
$\boxed{\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{\begin{vmatrix} -F_x & F_z \\ -G_x & G_z \end{vmatrix}}{\begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}},\qquad 
\frac{\mathrm{d}z}{\mathrm{d}x} = \frac{\begin{vmatrix} F_y & -F_x \\ G_y & -G_x \end{vmatrix}}{\begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}}}$.
</div>


### 方向导数
#### 方向导数的定义

设 $l$ 为 $xOy$ 平面上以点 $P_0(x_0,y_0)$ 为起点的一条射线，$\boldsymbol{e}_l = (\cos\alpha, \cos\beta)$ 是与 $l$ 同方向的单位向量。射线 $l$ 的参数方程为：
$$
\begin{cases}
x = x_0 + t\cos\alpha, \\
y = y_0 + t\cos\beta,
\end{cases}
$$
若极限
$$
\lim_{t \to 0^+} \frac{f(x_0 + t\cos\alpha,\ y_0 + t\cos\beta) - f(x_0,y_0)}{t}
$$
存在，则称此极限为函数 $f(x,y)$ 在 $(x_0,y_0)$ 点沿 $l$ 方向的**方向导数**，记为 $\frac{\partial f}{\partial l} \rvert_{(x_0,y_0)}$。

方向导数 $\left.\frac{\partial f}{\partial l}\right|_{(x_0,y_0)}$ 是函数在 $P_0(x_0,y_0)$ 处沿指定方向 $l$ 的变化率。
~~习惯上 $l$ 为射线，而非向量，无需写向量符号。~~


#### 方向导数存在的条件和计算公式
|**方向导数存在条件定理**|如果函数 $z = f(x, y)$ 在点 $P(x, y)$ 是可微分的,|
|-:|:-|
||那么对于任意单位向量 $\vec{e_l} = (\cos \alpha, \cos \beta)$,|
||函数 $z = f(x, y)$ 在该点方向 $l$ 的方向导数都存在,|
||且有$\large{\frac{\partial f}{\partial l} = \frac{\partial f}{\partial x} \cos \alpha + \frac{\partial f}{\partial y} \cos \beta}.$
|*证明*||
||~~**此公式仅适用于可微前提下,若不可微,必回归定义**~~