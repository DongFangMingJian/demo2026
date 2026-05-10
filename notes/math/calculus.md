## 微积分下

### 三角函数




### 一、基本定义与关系

#### 1.1 六个基本三角函数

| 函数 | 缩写 | 定义（单位圆） | 定义（直角三角形） |
| :--- | :--- | :--- | :--- |
| 正弦 | $\sin \theta$ | $y$ | $\frac{\text{对边}}{\text{斜边}}$ |
| 余弦 | $\cos \theta$ | $x$ | $\frac{\text{邻边}}{\text{斜边}}$ |
| 正切 | $\tan \theta$ | $\frac{y}{x}$ | $\frac{\text{对边}}{\text{邻边}}$ |
| 余切 | $\cot \theta$ | $\frac{x}{y}$ | $\frac{\text{邻边}}{\text{对边}}$ |
| 正割 | $\sec \theta$ | $\frac{1}{x}$ | $\frac{\text{斜边}}{\text{邻边}}$ |
| 余割 | $\csc \theta$ | $\frac{1}{y}$ | $\frac{\text{斜边}}{\text{对边}}$ |

#### 1.2 倒数关系

$$\large{\sin \theta \cdot \csc \theta = 1 \qquad
\cos \theta \cdot \sec \theta = 1 \qquad
\tan \theta \cdot \cot \theta = 1}$$

#### 1.3 商数关系

$$\large{\tan \theta = \frac{\sin \theta}{\cos \theta} \qquad
\cot \theta = \frac{\cos \theta}{\sin \theta}}$$

#### 1.4 平方关系（毕达哥拉斯恒等式）

$$\large{\sin^2 \theta + \cos^2 \theta = 1}$$
$$\large{1 + \tan^2 \theta = \sec^2 \theta}$$
$$\large{1 + \cot^2 \theta = \csc^2 \theta}$$


### 二、诱导公式（奇变偶不变，符号看象限）

| 角度 | $\sin$ | $\cos$ | $\tan$ | $\cot$ |
| :--- | :--- | :--- | :--- | :--- |
| $-\theta$ | $-\sin\theta$ | $\cos\theta$ | $-\tan\theta$ | $-\cot\theta$ |
| $\pi/2 - \theta$ | $\cos\theta$ | $\sin\theta$ | $\cot\theta$ | $\tan\theta$ |
| $\pi/2 + \theta$ | $\cos\theta$ | $-\sin\theta$ | $-\cot\theta$ | $-\tan\theta$ |
| $\pi - \theta$ | $\sin\theta$ | $-\cos\theta$ | $-\tan\theta$ | $-\cot\theta$ |
| $\pi + \theta$ | $-\sin\theta$ | $-\cos\theta$ | $\tan\theta$ | $\cot\theta$ |
| $3\pi/2 - \theta$ | $-\cos\theta$ | $-\sin\theta$ | $\cot\theta$ | $\tan\theta$ |
| $3\pi/2 + \theta$ | $-\cos\theta$ | $\sin\theta$ | $-\cot\theta$ | $-\tan\theta$ |
| $2\pi - \theta$ | $-\sin\theta$ | $\cos\theta$ | $-\tan\theta$ | $-\cot\theta$ |

#### 周期性公式

$$\large{\sin(\theta + 2k\pi) = \sin\theta, \quad \cos(\theta + 2k\pi) = \cos\theta, \quad \tan(\theta + k\pi) = \tan\theta \quad (k \in \mathbb{Z})}$$



### 三、和角与差角公式

$$\large{\sin(\alpha \pm \beta) = \sin\alpha \cos\beta \pm \cos\alpha \sin\beta}$$
$$\large{\cos(\alpha \pm \beta) = \cos\alpha \cos\beta \mp \sin\alpha \sin\beta}$$
$$\large{\tan(\alpha \pm \beta) = \frac{\tan\alpha \pm \tan\beta}{1 \mp \tan\alpha \tan\beta}}$$
$$\large{\cot(\alpha \pm \beta) = \frac{\cot\alpha \cot\beta \mp 1}{\cot\beta \pm \cot\alpha}}$$



### 四、倍角与半角公式

#### 4.1 二倍角公式

$$\large{\sin 2\alpha = 2\sin\alpha \cos\alpha = \frac{2\tan\alpha}{1+\tan^2\alpha}}$$
$$\large{\cos 2\alpha = \cos^2\alpha - \sin^2\alpha = 2\cos^2\alpha - 1 = 1 - 2\sin^2\alpha = \frac{1-\tan^2\alpha}{1+\tan^2\alpha}}$$
$$\large{\tan 2\alpha = \frac{2\tan\alpha}{1-\tan^2\alpha}}$$

#### 4.2 三倍角公式

$$\large{\sin 3\alpha = 3\sin\alpha - 4\sin^3\alpha = 4\sin(60^\circ-\alpha)\sin\alpha\sin(60^\circ+\alpha)}$$
$$\large{\cos 3\alpha = 4\cos^3\alpha - 3\cos\alpha = 4\cos(60^\circ-\alpha)\cos\alpha\cos(60^\circ+\alpha)}$$
$$\large{\tan 3\alpha = \frac{3\tan\alpha - \tan^3\alpha}{1 - 3\tan^2\alpha}}$$

#### 4.3 半角公式

$$\large{\sin\frac{\alpha}{2} = \pm \sqrt{\frac{1 - \cos\alpha}{2}}}$$
$$\large{\cos\frac{\alpha}{2} = \pm \sqrt{\frac{1 + \cos\alpha}{2}}}$$
$$\large{\tan\frac{\alpha}{2} = \pm \sqrt{\frac{1 - \cos\alpha}{1 + \cos\alpha}} = \frac{1 - \cos\alpha}{\sin\alpha} = \frac{\sin\alpha}{1 + \cos\alpha}}$$

（符号由 $\frac{\alpha}{2}$ 所在象限决定）



### 五、幂降角升公式（降幂公式）

$$\large{\sin^2\alpha = \frac{1 - \cos 2\alpha}{2}, \qquad 
\cos^2\alpha = \frac{1 + \cos 2\alpha}{2}}$$
$$\large{\sin^3\alpha = \frac{3\sin\alpha - \sin 3\alpha}{4}, \qquad 
\cos^3\alpha = \frac{3\cos\alpha + \cos 3\alpha}{4}}$$
$$\large{\tan^2\alpha = \frac{1 - \cos 2\alpha}{1 + \cos 2\alpha}}$$


### 六、积化和差公式

$$\large{\sin\alpha \cos\beta = \frac{1}{2} \big[ \sin(\alpha+\beta) + \sin(\alpha-\beta) \big]}$$
$$\large{\cos\alpha \sin\beta = \frac{1}{2} \big[ \sin(\alpha+\beta) - \sin(\alpha-\beta) \big]}$$
$$\large{\cos\alpha \cos\beta = \frac{1}{2} \big[ \cos(\alpha+\beta) + \cos(\alpha-\beta) \big]}$$
$$\large{\sin\alpha \sin\beta = \frac{1}{2} \big[ \cos(\alpha-\beta) - \cos(\alpha+\beta) \big]}$$


### 七、和差化积公式

$$\large{\sin\alpha + \sin\beta = 2 \sin\frac{\alpha+\beta}{2} \cos\frac{\alpha-\beta}{2}}$$
$$\large{\sin\alpha - \sin\beta = 2 \cos\frac{\alpha+\beta}{2} \sin\frac{\alpha-\beta}{2}}$$
$$\large{\cos\alpha + \cos\beta = 2 \cos\frac{\alpha+\beta}{2} \cos\frac{\alpha-\beta}{2}}$$
$$\large{\cos\alpha - \cos\beta = -2 \sin\frac{\alpha+\beta}{2} \sin\frac{\alpha-\beta}{2}}$$


### 八、万能公式（令 $t = \tan\frac{\alpha}{2}$）

$$\large{\sin\alpha = \frac{2t}{1+t^2}, \qquad 
\cos\alpha = \frac{1-t^2}{1+t^2}, \qquad 
\tan\alpha = \frac{2t}{1-t^2}}$$

（适用于有理函数积分中化三角函数为代数函数）


### 九、反三角函数

#### 9.1 定义与主值区间

| 函数 | 定义域 | 值域 | 恒等式 |
| :--- | :--- | :--- | :--- |
| $y = \arcsin x$ | $[-1,1]$ | $[-\frac{\pi}{2}, \frac{\pi}{2}]$ | $\sin(\arcsin x)=x$ |
| $y = \arccos x$ | $[-1,1]$ | $[0, \pi]$ | $\cos(\arccos x)=x$ |
| $y = \arctan x$ | $\mathbb{R}$ | $(-\frac{\pi}{2}, \frac{\pi}{2})$ | $\tan(\arctan x)=x$ |
| $y = \operatorname{arccot} x$ | $\mathbb{R}$ | $(0, \pi)$ | $\cot(\operatorname{arccot} x)=x$ |
| $y = \operatorname{arcsec} x$ | $(-\infty,-1] \cup [1,\infty)$ | $[0,\frac{\pi}{2}) \cup (\frac{\pi}{2},\pi]$ | $\sec(\operatorname{arcsec} x)=x$ |
| $y = \operatorname{arccsc} x$ | $(-\infty,-1] \cup [1,\infty)$ | $[-\frac{\pi}{2},0) \cup (0,\frac{\pi}{2}]$ | $\csc(\operatorname{arccsc} x)=x$ |

#### 9.2 互余关系

$$\large{\arcsin x + \arccos x = \frac{\pi}{2}, \quad 
\arctan x + \operatorname{arccot} x = \frac{\pi}{2}, \quad 
\operatorname{arcsec} x + \operatorname{arccsc} x = \frac{\pi}{2}}$$

#### 9.3 诱导公式（负角）

$$\large{\arcsin(-x) = -\arcsin x, \quad 
\arccos(-x) = \pi - \arccos x}$$
$$\large{\arctan(-x) = -\arctan x, \quad 
\operatorname{arccot}(-x) = \pi - \operatorname{arccot} x}$$

#### 9.4 恒等式（三角与反三角复合）

$$\large{\sin(\arccos x) = \sqrt{1-x^2}, \quad 
\cos(\arcsin x) = \sqrt{1-x^2}}$$
$$\large{\tan(\arcsin x) = \frac{x}{\sqrt{1-x^2}}, \quad 
\tan(\arccos x) = \frac{\sqrt{1-x^2}}{x}}$$


### 十、导数和积分

#### 10.1 导数

$$\large{\frac{d}{dx} \sin x = \cos x}$$
$$\large{\frac{d}{dx} \cos x = -\sin x}$$
$$\large{\frac{d}{dx} \tan x = \sec^2 x}$$
$$\large{\frac{d}{dx} \cot x = -\csc^2 x}$$
$$\large{\frac{d}{dx} \sec x = \sec x \tan x}$$
$$\large{\frac{d}{dx} \csc x = -\csc x \cot x}$$

#### 10.2 反三角导数

$$\large{\frac{d}{dx} \arcsin x = \frac{1}{\sqrt{1-x^2}}}$$
$$\large{\frac{d}{dx} \arccos x = -\frac{1}{\sqrt{1-x^2}}}$$
$$\large{\frac{d}{dx} \arctan x = \frac{1}{1+x^2}}$$
$$\large{\frac{d}{dx} \operatorname{arccot} x = -\frac{1}{1+x^2}}$$
$$\large{\frac{d}{dx} \operatorname{arcsec} x = \frac{1}{|x|\sqrt{x^2-1}}}$$
$$\large{\frac{d}{dx} \operatorname{arccsc} x = -\frac{1}{|x|\sqrt{x^2-1}}}$$

#### 10.3 不定积分（基本型）

$$\large{\int \sin x \,dx = -\cos x + C}$$
$$\large{\int \cos x \,dx = \sin x + C}$$
$$\large{\int \tan x \,dx = -\ln\lvert\cos x\rvert + C = \ln\lvert\sec x\rvert + C}$$
$$\large{\int \cot x \,dx = \ln\lvert\sin x\rvert + C}$$
$$\large{\int \sec x \,dx = \ln\lvert\sec x + \tan x\rvert + C}$$
$$\large{\int \csc x \,dx = \ln\lvert\csc x - \cot x\rvert + C = -\ln\lvert\csc x + \cot x\rvert + C}$$
$$\large{\int \sec^2 x \,dx = \tan x + C}$$
$$\large{\int \csc^2 x \,dx = -\cot x + C}$$
$$\large{\int \sec x \tan x \,dx = \sec x + C}$$
$$\large{\int \csc x \cot x \,dx = -\csc x + C}$$

#### 10.4 反三角积分

$$\large{\int \frac{dx}{\sqrt{1-x^2}} = \arcsin x + C}$$
$$\large{\int \frac{dx}{1+x^2} = \arctan x + C}$$
$$\large{\int \frac{dx}{x\sqrt{x^2-1}} = \operatorname{arcsec} |x| + C}$$


### 十一、重要的三角恒等式

#### 11.1 辅助角公式

$$\large{a\sin x + b\cos x = \sqrt{a^2+b^2} \sin(x + \varphi)}$$
其中 $\varphi = \arctan\frac{b}{a}$（注意象限）
或写成 $\sqrt{a^2+b^2} \cos(x - \psi)$，$\psi = \arctan\frac{a}{b}$

#### 11.2 正弦定理与余弦定理（用于三角形）

**正弦定理**：$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$（$R$ 为外接圆半径）

**余弦定理**：
$$\large{a^2 = b^2 + c^2 - 2bc\cos A}$$
$$\large{b^2 = a^2 + c^2 - 2ac\cos B}$$
$$\large{c^2 = a^2 + b^2 - 2ab\cos C}$$

**正切定理**（较少用）：
$$\large{\frac{a-b}{a+b} = \frac{\tan\frac{A-B}{2}}{\tan\frac{A+B}{2}}}$$

#### 11.3 莫尔维德公式

$$\large{\frac{a+b}{c} = \frac{\cos\frac{A-B}{2}}{\sin\frac{C}{2}}, \quad 
\frac{a-b}{c} = \frac{\sin\frac{A-B}{2}}{\cos\frac{C}{2}}}$$


### 十二、常用特殊角的三角函数值

| 角度 $\theta$ | $0$ | $\frac{\pi}{6}$ | $\frac{\pi}{4}$ | $\frac{\pi}{3}$ | $\frac{\pi}{2}$ | $\pi$ | $\frac{3\pi}{2}$ | $2\pi$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\sin\theta$ | $0$ | $\frac{1}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $1$ | $0$ | $-1$ | $0$ |
| $\cos\theta$ | $1$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$ | $0$ | $-1$ | $0$ | $1$ |
| $\tan\theta$ | $0$ | $\frac{\sqrt{3}}{3}$ | $1$ | $\sqrt{3}$ | 不存在 | $0$ | 不存在 | $0$ |
| $\cot\theta$ | 不存在 | $\sqrt{3}$ | $1$ | $\frac{\sqrt{3}}{3}$ | $0$ | 不存在 | $0$ | 不存在 |
| $\sec\theta$ | $1$ | $\frac{2\sqrt{3}}{3}$ | $\sqrt{2}$ | $2$ | 不存在 | $-1$ | 不存在 | $1$ |
| $\csc\theta$ | 不存在 | $2$ | $\sqrt{2}$ | $\frac{2\sqrt{3}}{3}$ | $1$ | 不存在 | $-1$ | 不存在 |



### 十三、三角函数的级数展开（泰勒/麦克劳林）

$$\large{\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n+1)!} x^{2n+1} = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots \quad (x \in \mathbb{R})}$$
$$\large{\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n)!} x^{2n} = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots \quad (x \in \mathbb{R})}$$
$$\large{\tan x = \sum_{n=1}^{\infty} \frac{(-1)^{n-1} 2^{2n}(2^{2n}-1) B_{2n}}{(2n)!} x^{2n-1} = x + \frac{x^3}{3} + \frac{2x^5}{15} + \cdots \quad (|x| < \frac{\pi}{2})}$$
（$B_{2n}$ 为伯努利数）


### 十四、欧拉公式与其他重要关系

#### 欧拉公式

$$\large{e^{i\theta} = \cos\theta + i\sin\theta}$$
由此可得：
$$\large{\cos\theta = \frac{e^{i\theta} + e^{-i\theta}}{2}, \quad 
\sin\theta = \frac{e^{i\theta} - e^{-i\theta}}{2i}}$$

#### 棣莫弗定理

$$\large{(\cos\theta + i\sin\theta)^n = \cos(n\theta) + i\sin(n\theta)}$$


### 十五、记忆口诀与技巧

1. **诱导公式口诀**：奇变偶不变，符号看象限。
2. **和差化积口诀**：正加正，正在前；余加余，余并肩；正减正，余在前；余减余，负正弦。
3. **导数口诀**：正弦导数余弦，余弦导数负正弦；正割方，余割负；正切正割联，余切余割反。



### 附录：常用三角恒等式的推导线索

- **$\sin^2+\cos^2=1$** → 除以 $\sin^2$ 或 $\cos^2$ 得另两个平方关系。
- **二倍角** 来自和角公式令 $\alpha=\beta$。
- **半角** 来自 $\cos2\alpha$ 公式解出 $\sin^2\alpha$ 或 $\cos^2\alpha$。
- **积化和差** 由和差公式相加/减得到。
- **和差化积** 是积化和差的逆用，通过变量替换 $u=\alpha+\beta$, $v=\alpha-\beta$。



> **注**：以上总结了高等数学及工程数学中几乎全部常用的三角函数公式。建议打印或收藏，作为解题手册随时查阅。


## 导数
以下是**基本初等函数**的求导公式（共6类）：



### 1. 常数函数
$$\large{(C)' = 0 \quad (C \text{ 为常数})}$$


### 2. 幂函数
$$\large{(x^\mu)' = \mu x^{\mu-1} \quad (\mu \in \mathbb{R})}$$

**特例**：
- $(\sqrt{x})' = \dfrac{1}{2\sqrt{x}}$
- $\left(\dfrac{1}{x}\right)' = -\dfrac{1}{x^2}$



### 3. 指数函数
$$\large{(e^x)' = e^x}$$
$$\large{(a^x)' = a^x \ln a \quad (a>0, a\neq 1)}$$


### 4. 对数函数
$$\large{(\ln x)' = \frac{1}{x}}$$
$$\large{(\log_a x)' = \frac{1}{x\ln a} \quad (a>0, a\neq 1)}$$


### 5. 三角函数
| 函数 | 导数 |
|------|------|
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |
| $\tan x$ | $\sec^2 x$ |
| $\cot x$ | $-\csc^2 x$ |
| $\sec x$ | $\sec x \tan x$ |
| $\csc x$ | $-\csc x \cot x$ |


### 6. 反三角函数
| 函数 | 导数 | 定义域 |
|------|------|--------|
| $\arcsin x$ | $\dfrac{1}{\sqrt{1-x^2}}$ | $(-1,1)$ |
| $\arccos x$ | $-\dfrac{1}{\sqrt{1-x^2}}$ | $(-1,1)$ |
| $\arctan x$ | $\dfrac{1}{1+x^2}$ | $\mathbb{R}$ |
| $\operatorname{arccot} x$ | $-\dfrac{1}{1+x^2}$ | $\mathbb{R}$ |
| $\operatorname{arcsec} x$ | $\dfrac{1}{\lvert x\rvert\sqrt{x^2-1}}$ | $\lvert x\rvert > 1$ |
| $\operatorname{arccsc} x$ | $-\dfrac{1}{\lvert x\rvert\sqrt{x^2-1}}$ | $\lvert x\rvert > 1$ |



## 基本初等函数积分公式



### 1. 常数与幂函数

$$\large{\int k \,dx = kx + C \quad (k \text{ 为常数})}$$

$$\large{\int x^\mu \,dx = \frac{x^{\mu+1}}{\mu+1} + C \quad (\mu \neq -1)}$$

$$\large{\int \frac{1}{x} \,dx = \ln\lvert x\rvert + C}$$

### 2. 指数函数

$$\large{\int e^x \,dx = e^x + C}$$

$$\large{\int a^x \,dx = \frac{a^x}{\ln a} + C \quad (a>0,\, a\neq 1)}$$

### 3. 对数函数

$$\large{\int \ln x \,dx = x\ln x - x + C}$$
（注意：$\ln x$ 不是基本积分表中的直接结果，需分部积分，此处作为常用结果列出）

### 4. 三角函数

| 积分 | 结果 |
|------|------|
| $\int \sin x \,dx$ | $-\cos x + C$ |
| $\int \cos x \,dx$ | $\sin x + C$ |
| $\int \tan x \,dx$ | $-\ln\lvert\cos x\rvert + C = \ln\lvert\sec x\rvert + C$ |
| $\int \cot x \,dx$ | $\ln\lvert\sin x\rvert + C$ |
| $\int \sec x \,dx$ | $\ln\lvert\sec x + \tan x\rvert + C$ |
| $\int \csc x \,dx$ | $\ln\lvert\csc x - \cot x\rvert + C$ |
| $\int \sec^2 x \,dx$ | $\tan x + C$ |
| $\int \csc^2 x \,dx$ | $-\cot x + C$ |
| $\int \sec x \tan x \,dx$ | $\sec x + C$ |
| $\int \csc x \cot x \,dx$ | $-\csc x + C$ |

### 5. 反三角函数

| 积分 | 结果 |
|------|------|
| $\int \frac{dx}{\sqrt{1-x^2}}$ | $\arcsin x + C$ |
| $\int -\frac{dx}{\sqrt{1-x^2}}$ | $\arccos x + C$ |
| $\int \frac{dx}{1+x^2}$ | $\arctan x + C$ |
| $\int -\frac{dx}{1+x^2}$ | $\operatorname{arccot} x + C$ |
| $\int \frac{dx}{x\sqrt{x^2-1}}$ | $\operatorname{arcsec} \lvert x\rvert + C$ |
| $\int -\frac{dx}{x\sqrt{x^2-1}}$ | $\operatorname{arccsc} \lvert x\rvert + C$ |

## 第一章 函数、极限、连续

### 1. 常用等价无穷小

#### 普通函数型

当 $x \to 0$ 时，

$$\large{\sin x \sim  \tan x \sim  \arcsin x \sim  \arctan x \sim e^x - 1 \sim  \ln(1 + x) \sim \ln(x + \sqrt{1 + x^2}) \sim x,}$$

$$\large{a^x - 1 = e^{\ln a} - 1 \sim x \ln a \quad (a > 0 \text{ 且 } a \neq 1),}$$
$$\large{1 - \cos x \sim \frac{1}{2}x^2,\quad 1 - \cos^a x \sim \frac{a}{2}x^2,}$$
$$\large{(1 + x)^a - 1 \sim ax \quad (a \neq 0),\quad (1 + x)^x - 1 \sim e^{x \ln(1+x)} - 1 \sim x^2.}$$

#### 差商型

当 $x \to 0$ 时，

$$\large{x - \sin x \sim \frac{1}{6}x^3,\quad x - \arcsin x \sim -\frac{1}{6}x^3,}$$
$$\large{x - \tan x \sim -\frac{1}{3}x^3,\quad x - \arctan x \sim -\frac{1}{3}x^3,}$$
$$\large{x - \ln(1 + x) \sim -\frac{1}{2}x^2,\quad e^x - 1 \sim x - \frac{1}{2}x^2.}$$

### 2. 无穷大量阶的比较

由于

$$\large{\left\{ 
\begin{aligned}
& \text{当 } x \to +\infty \text{ 时}, \quad \ln^p x \ll x^q \ll a^x \ll x^x, \\
& \text{当 } n \to \infty \text{ 时}, \quad \ln^p n \ll n^q \ll a^n \ll n! \ll n^n 
\end{aligned} 
\right. \quad (p, q > 0,\ a > 1)}$$

则

$$\large{\lim_{n \to \infty} \frac{\ln^p n}{n^q} = 0,\quad 
\lim_{n \to \infty} \frac{n^q}{a^n} = 0,\quad 
\lim_{n \to \infty} \frac{a^n}{n!} = 0,\quad 
\lim_{n \to \infty} \frac{n!}{n^n} = 0.}$$

### 3. 常用的几个极限

$$\large{\lim_{n \to \infty} \sqrt[n]{n} = 1,\quad \lim_{x \to +\infty} x^{\frac{1}{x}} = 1.}$$

$$\large{\lim_{x \to 0^+} x^a = 
\begin{cases} 
0, & a > 0, \\ 
1, & a = 0, \\ 
+\infty, & a < 0.
\end{cases}}$$

$$\large{\lim_{n \to \infty} n^x = 
\begin{cases} 
+\infty, & x > 0, \\ 
1, & x = 0, \\ 
0, & x < 0.
\end{cases}}$$

### 4. 常用麦克劳林公式

$$\large{e^x = 1 + x + \frac{1}{2!}x^2 + \cdots + \frac{1}{n!}x^n + o(x^n)}$$

$$\large{\ln(1 + x) = x - \frac{1}{2}x^2 + \frac{1}{3}x^3 - \cdots + (-1)^{n-1}\frac{x^n}{n} + o(x^n)}$$

$$\large{\sin x = x - \frac{1}{3!}x^3 + \cdots + (-1)^n\frac{x^{2n+1}}{(2n+1)!} + o(x^{2n+1})}$$

$$\large{\cos x = 1 - \frac{1}{2!}x^2 + \cdots + (-1)^n\frac{x^{2n}}{(2n)!} + o(x^{2n})}$$

$$\large{\tan x = x + \frac{1}{3}x^3 + o(x^3)}$$

$$\large{\arcsin x = x + \frac{1}{6}x^3 + o(x^3)}$$

$$\large{\arctan x = x - \frac{1}{3}x^3 + o(x^3)}$$

$$\large{\frac{1}{1-x} = 1 + x + x^2 + \cdots + x^n + o(x^n)}$$

$$\large{\frac{1}{1+x} = 1 - x + x^2 + \cdots + (-1)^n x^n + o(x^n)}$$

$$\large{(1+x)^m = 1 + mx + \frac{m(m-1)}{2!}x^2 + \cdots + \frac{m(m-1)\cdots(m-n+1)}{n!}x^n + o(x^n)}$$







## 极坐标

| 直角坐标方程 | 极坐标方程 | 说明 |
| --- | --- | --- |
| $x = a$ | $r = \frac{a}{\cos\theta}$ | 垂直于 $x$ 轴的直线 |
| $y = b$ | $r = \frac{b}{\sin\theta}$ | 平行于 $x$ 轴的直线 |
| $x^2 + y^2 = R^2$ | $r = R$ | 圆心在原点的圆 |
| $x^2 + y^2 = 2ax$ | $r = 2a\cos\theta$ | 圆心 $(a, 0)$, 半径 $\lvert a\rvert$ |
| $x^2 + y^2 = 2by$ | $r = 2b\sin\theta$ | 圆心 $(0, b)$, 半径 $\lvert b\rvert$ |
| $y = kx$ 或 $x\sin\alpha - y\cos\alpha = 0$ | $\theta = \alpha$ ($\alpha = \arctan k$) | 过原点的直线(不含 $x=0$ 时单独取 $\theta = \pi/2$) |
| $Ax + By = C$ ($C \neq 0$) | $r = \frac{C}{A\cos\theta + B\sin\theta}$ | 不经过原点的一般直线 |
| $x^2 + y^2 + Dx + Ey = 0$ | $r = -D\cos\theta - E\sin\theta$ | 圆心在 $(-\frac{D}{2}, -\frac{E}{2})$, 过原点的圆 |
| $(x^2 + y^2)^2 = a^2(x^2 - y^2)$ | $r^2 = a^2\cos 2\theta$ | 双纽线(伯努利双纽线) |
| $x^2 - y^2 = a^2$ | $r^2 = \frac{a^2}{\cos 2\theta}$ | 等轴双曲线(其实轴沿坐标轴) |


## 向量代数
### <!--占位符-->
#### 空间直角坐标系
> 正方向符合*右手法则*
**空间中两点的距离公式**
<div align="center" style="font-size: 13px;">
$\boxed{\lvert P_1 P_2 \rvert = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}}$
</div>

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
<div align="center" style="font-size: 13px;"> $\boxed{\bigl\lvert \lvert\vec{a}\rvert - \lvert\vec{b}\rvert \bigr\rvert \leq \lvert \vec{a} \pm \vec{b} \rvert \leq \lvert\vec{a}\rvert + \lvert\vec{b}\rvert}$ </div>

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
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{l}
\cos\alpha = \dfrac{x}{\lvert\vec{a}\rvert} = \dfrac{x}{\sqrt{x^2+y^2+z^2}} \\[6pt]
\cos\beta = \dfrac{y}{\lvert\vec{a}\rvert} = \dfrac{y}{\sqrt{x^2+y^2+z^2}} \\[6pt]
\cos\gamma = \dfrac{z}{\lvert\vec{a}\rvert} = \dfrac{z}{\sqrt{x^2+y^2+z^2}}
\end{array}
}$
</div>

> **方向余弦的性质**
> > *归一化*
<div align="center" style="font-size: 13px;">
$\boxed{\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1}$
</div>

> > *构成单位向量*
<div align="center" style="font-size: 13px;">
$\boxed{\vec{e}_a = (\cos\alpha, \cos\beta, \cos\gamma) = \left( \frac{x}{\lvert\vec{a}\rvert}, \frac{y}{\lvert\vec{a}\rvert}, \frac{z}{\lvert\vec{a}\rvert} \right) = \frac{1}{\lvert\vec{a}\rvert} (x, y, z) = \frac{\vec{a}}{\lvert\vec{a}\rvert}}$
</div>

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

<div align="center" style="font-size: 13px;"> $\boxed{ \begin{array}{c} \text{若 } \vec{a} = (a_x, a_y, a_z),\; \vec{b} = (b_x, b_y, b_z) \\ \text{则 } \vec{a} \perp \vec{b} \text{ 的充要条件是 } a_x b_x + a_y b_y + a_z b_z = 0 \end{array} }$ </div>

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
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{三向量 } \vec{a}, \vec{b}, \vec{c} \text{ 共面的充要条件是混合积为零:} \\[4pt]
\begin{vmatrix} \vec{a} & \vec{b} & \vec{c} \end{vmatrix} = 0 \\[8pt]
\begin{vmatrix}
a_x & a_y & a_z \\
b_x & b_y & b_z \\
c_x & c_y & c_z
\end{vmatrix} = 0
\end{array}
}$
</div>

## 空间解析几何
### <!--占位符-->
#### 平面
##### 平面的方程
###### 点法式方程
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{过点 } M_0(x_0, y_0, z_0) \text{ 且以 } \vec{n} = (A, B, C) \text{ 为法向量的平面 } \pi \text{ 的方程为} \\
A(x - x_0) + B(y - y_0) + C(z - z_0) = 0 \\
\text{称平面的点法式方程}
\end{array}
}$
</div>

###### 一般方程


<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{三元一次方程} \\
Ax + By + Cz + D = 0 \quad (A, B, C\ \text{不同时为零}) \\
\text{的图形是平面。其中 } x, y, z \text{ 的系数 } A, B, C \text{ 构成的向量 } \vec{n} = (A, B, C) \text{ 是平面的法向量。}
\end{array}
}$
</div>


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
<div align="center" style="font-size: 13px;">
$\boxed{\cos \theta =  | \frac{\overrightarrow{n_1} \cdot \overrightarrow{n_2}}{\lvert\overrightarrow{n_1}\rvert \lvert\overrightarrow{n_2}\rvert} | = \frac{\lvert A_1 A_2 + B_1 B_2 + C_1 C_2\rvert}{\sqrt{A_1^2 + B_1^2 + C_1^2} \sqrt{A_2^2 + B_2^2 + C_2^2}}}$
</div>

##### 点到平面的距离
<div align="center" style="font-size: 13px;"> $\boxed{ \begin{array}{c} \text{求 } P_0(x_0, y_0, z_0) \text{ 到平面 } Ax + By + Cz + D = 0 \text{ 的距离为} \\[4pt] d = \dfrac{\lvert Ax_0 + By_0 + Cz_0 + D\rvert}{\sqrt{A^2 + B^2 + C^2}} \end{array} }$ </div>

> *证明*
##### 两平行平面间的距离
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{两平行平面 } Ax + By + Cz + D_1 = 0 \text{ 与 } Ax + By + Cz + D_2 = 0 \text{ 之间的距离为} \\[4pt]
d = \dfrac{\lvert D_1 - D_2\rvert}{\sqrt{A^2 + B^2 + C^2}}
\end{array}
}$
</div>

> *证明*



#### 直线
##### 直线的方程
> *平行于直线的任一非零向量*称该直线的**方向向量**
###### 点向式方程(对称式方程)与参数方程
> $M_0(x_0, y_0, z_0) $是直线上一点.由于*空间一点 $ M(x, y, z) $ 在直线$L$上的充要条件是向量 $ \overrightarrow{M_0M} // \vec{s} $,即$ \overrightarrow{M_0M} = t \vec{s} \ (t \in \mathbb{R}) $*,现$\overrightarrow{M_0M} = (x - x_0, y - y_0, z - z_0) $,$\vec{s} = (m, n, p)$,从而有 $ x - x_0 = tm,\ y - y_0 = tn,\ z - z_0 = tp $，即

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
x = x_0 + tm, \\
\begin{cases} 
y = y_0 + tn, \\ 
z = z_0 + tp,
\end{cases} \\
\text{或者} \\
\dfrac{x - x_0}{m} = \dfrac{y - y_0}{n} = \dfrac{z - z_0}{p}.
\end{array}
}$
</div>

> 在点向式方程中，*分母可以为0*,**分母为0意味着分子也为0**

###### 一般方程
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{l}
\begin{cases} 
A_1 x + B_1 y + C_1 z + D_1 = 0, \\ 
A_2 x + B_2 y + C_2 z + D_2 = 0, 
\end{cases} \\
\text{其中 } \dfrac{A_1}{A_2} = \dfrac{B_1}{B_2} = \dfrac{C_1}{C_2} \text{ 不成立。}
\end{array}
}$
</div>

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
\end{cases}.$



##### 两直线的夹角
> **两直线方向向量的夹角**称两直线的夹角
> *不取钝角*，即$\color{red}{\theta \in [0,\frac{\pi}{2}]}$
<div align="center" style="font-size: 13px;">
$\boxed{\cos\theta = | \frac{\vec{s_1} \cdot \vec{s_2}}{\lvert\vec{s_1}\rvert \lvert\vec{s_2}\rvert} |= \frac{\lvert m_1 m_2 + n_1 n_2 + p_1 p_2\rvert}{\sqrt{m_1^2 + n_1^2 + p_1^2} \sqrt{m_2^2 + n_2^2 + p_2^2}}}$
</div>

> 从**两向量垂直或者平行的充要条件定理**可得:

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{直线 } L_1 \text{ 和 } L_2 \text{ 互相垂直的充要条件是} \\
m_1m_2 + n_1n_2 + p_1p_2 = 0; \\ \\
\text{直线 } L_1 \text{ 和 } L_2 \text{ 互相平行的充要条件是} \\
\dfrac{m_1}{m_2} = \dfrac{n_1}{n_2} = \dfrac{p_1}{p_2}.
\end{array}
}$
</div>

##### 直线与平面的夹角
> **直线与平面的夹角**:直线与平面*法线*夹角的**余角**

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\vec{s}_1 = (m_1, n_1, p_1), \quad \vec{n} = (A, B, C), \\
\text{则} \quad \sin\varphi = \cos\theta = \dfrac{\lvert\vec{n} \cdot \vec{s}_1\rvert}{\lvert\vec{n}\rvert \lvert\vec{s}_1\rvert} = \dfrac{\lvert A m_1 + B n_1 + C p_1\rvert}{\sqrt{A^2 + B^2 + C^2} \sqrt{m_1^2 + n_1^2 + p_1^2}}
\end{array}
}$
</div>

> 从**两向量垂直或者平行的充要条件定理**可得:
<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{l}
\text{直线与平面垂直的充要条件是 } \dfrac{A}{m} = \dfrac{B}{n} = \dfrac{C}{p}; \\
\text{直线与平面平行的充要条件是 } Am + Bn + Cp = 0.
\end{array}
}$
</div>


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

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{称变元 } x = (x_1, x_2) \text{ 在 } \mathbb{R}^2 \text{ 中趋于 } a = (a_1, a_2) \\
\text{记作 } x \to a \text{，若 } |x - a| \to 0. \\
- \, x \to a \iff x_1 \to a_1,\ x_2 \to a_2.
\end{array}
}$
</div>


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
##### 二元函数
|**定义**|设 $D \subset \mathbb{R}^2$ 是一个非空子集, 若对于每个点 $(x,y) \in D$, 都*存在唯一*确定的实数 $z$ 与之对应, 则称映射 $f: D \to \mathbb{R}$ 为定义在 $D$ 上的一个二元函数, 记作 $z = f(x,y)$.|
|-:|:-|
||称 $(x,y)$ 为 **自变量**, $z$ 为 **因变量**, $D$ 为函数 $f$ 的 **定义域**,|
||$f(D) = \{ f(x,y) \mid (x,y) \in D \}$ 为函数 $f$ 的 **值域**.|

##### $n$元函数
|**定义**|设 $D \subset \mathbb{R}^n$ 是一个非空子集, 映射 $f: D \to \mathbb{R}$, 称 $f$ 为定义在 $D$ 上的 $n$ 元函数, 记作|
|-:|:-|
||$y = f(x) = f(x_1, x_2, \cdots, x_n)$, 其中 $x = <x_1, x_2, \cdots, x_n> \in D$.
||称 $x$ 为 **自变量**, $y$ 为 **因变量**, $D$ 为函数 $f$ 的 **定义域**,|
||$f(D) = \{ f(x) \mid x \in D \}$ 为函数$f$ 的 **值域**.|

~~n元函数是多元函数的一般形式~~

#### 有界闭区域上多元连续函数的性质

|**有界性**|有界闭区域 $D$ 上的多元连续函数是 $D$ 上的有界函数.|
|-:|:-|
|**最值定理**|有界闭区域 $D$ 上的多元连续函数在 $D$ 上存在最大值和最小值.|
|**介值定理**|有界闭区域 $D$ 上的多元连续函数可取介于最大值和最小值之间的任何值.|

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
    .label-p { font-family: "Times New Roman", Times, serif; font-style: italic; font-size: 10px; fill: blue; }
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
  <text x="65" y="75" class="label-p">∂f/∂u</text>
  <!-- f→v 标签在线的右下方 -->
  <text x="65" y="135" class="label-p">∂f/∂v</text>
  <!-- u→x 标签在线下方 -->
  <text x="135" y="48" class="label-p">∂u/∂x</text>
  <!-- u→y 标签在线下方 -->
  <text x="135" y="85" class="label-p">∂u/∂y</text>
  <!-- v→x 标签在线下方 -->
  <text x="135" y="138" class="label-p">∂v/∂x</text>
  <!-- v→y 标签在线下方 -->
  <text x="135" y="175" class="label-p">∂v/∂y</text>
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
||且有

<div align="center" style="font-size: 13px;">

$\boxed{\frac{\partial f}{\partial l} = \frac{\partial f}{\partial x} \cos \alpha + \frac{\partial f}{\partial y} \cos \beta}$

</div>

|*证明*||
|-:|:-|
||~~**此公式仅适用于可微前提下,若不可微,必回归定义**~~|





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

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{函数的法向导数为梯度在该方向上的投影:} \\
\dfrac{\partial f}{\partial l} = \nabla f(x, y) \cdot \vec{e}_l
\end{array}
}$
</div>


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

<div align="center" style="font-size: 13px;">
$\boxed{
\begin{array}{c}
\text{切线的方向向量为} \\
\vec{t} = (x'(t_0), y'(t_0), z'(t_0)) \\ \\
\text{曲线在 } M_0 \text{ 处的切线方程为:} \\
\dfrac{x - x_0}{x'(t_0)} = \dfrac{y - y_0}{y'(t_0)} = \dfrac{z - z_0}{z'(t_0)} \\ \\
\text{法平面(过切点且与切线垂直的平面)的方程为:} \\
x'(t_0)(x - x_0) + y'(t_0)(y - y_0) + z'(t_0)(z - z_0) = 0
\end{array}
}$
</div>

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



<div align="center" style="font-size: 15px;">
$$\boxed{
\begin{array}{c}
\text{曲面上过点 } M_0 \text{ 的切平面的法向量为:} \\
\vec{n} = (F_x(x_0, y_0, z_0), F_y(x_0, y_0, z_0), F_z(x_0, y_0, z_0)) \\ \\
\text{曲面上过点 } M_0 \text{ 的切平面方程为:} \\
F_x(x_0, y_0, z_0)(x - x_0) + F_y(x_0, y_0, z_0)(y - y_0) + F_z(x_0, y_0, z_0)(z - z_0) = 0 \\ \\
\text{曲面上过点 } M_0 \text{ 的法线方程为:} \\
\large{\frac{x - x_0}{F_x(x_0, y_0, z_0)} = \frac{y - y_0}{F_y(x_0, y_0, z_0)} = \frac{z - z_0}{F_z(x_0, y_0, z_0)}}
\end{array}
}$$
</div>


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




<div align="center" style="font-size: 12px;"> $\boxed{ \begin{array}{c} \text{切线的方向向量为} \\ \vec{\tau} = \nabla F \times \nabla G\big|_{M_0} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ F_x & F_y & F_z \\ G_x & G_y & G_z \end{vmatrix}_{M_0} = \left( \begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}_{M_0},\; \begin{vmatrix} F_z & F_x \\ G_z & G_x \end{vmatrix}_{M_0},\; \begin{vmatrix} F_x & F_y \\ G_x & G_y \end{vmatrix}_{M_0} \right) \\ \\ \text{切线方程(对称式)为} \\ \frac{\large{x - x_0}}{\begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}_{M_0}} = \frac{\large{y - y_0}}{\begin{vmatrix} F_z & F_x \\ G_z & G_x \end{vmatrix}_{M_0}} = \frac{\large{z - z_0}}{\begin{vmatrix} F_x & F_y \\ G_x & G_y \end{vmatrix}_{M_0}} \\ \\ \text{法平面方程为} \\ \begin{vmatrix} F_y & F_z \\ G_y & G_z \end{vmatrix}_{M_0} (x - x_0) + \begin{vmatrix} F_z & F_x \\ G_z & G_x \end{vmatrix}_{M_0} (y - y_0) + \begin{vmatrix} F_x & F_y \\ G_x & G_y \end{vmatrix}_{M_0} (z - z_0) = 0 \end{array} }$ </div>




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




<div align="center" style="font-size: 13px;">

$\boxed{
\begin{array}{c}
\text{设函数 } f(x, y) \text{ 与 } \varphi(x, y) \text{ 具有连续的偏导数，作拉格朗日函数} \\
L(x, y, \lambda) = f(x, y) + \lambda \varphi(x, y), \\ \\
\text{如果 } x = x_0, y = y_0 \text{ 是方程组 } L_x = 0, L_y = 0, L_{\lambda} = 0 \text{ 即} \\
\begin{cases} 
f_x(x_0, y_0) + \lambda \varphi_x(x_0, y_0) = 0, \\ 
f_y(x_0, y_0) + \lambda \varphi_y(x_0, y_0) = 0, \\ 
\varphi(x_0, y_0) = 0 
\end{cases} \\
\text{的解，那么点 } (x_0, y_0) \text{ 是目标函数 } f(x, y) \text{ 在约束条件 } \varphi(x, y) = 0 \text{ 下的可疑极值点.}
\end{array}
}$


</div>



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


### 二重积分

> 二重积分的值只与被积函数和积分区域有关,
与积分变量的选取和区域的划分无关.


#### 性质



|**线性性**|若 $f(x,y), g(x,y)$ 均在 $D$ 上可积, 则|
|-:|:-|
||$\iint\limits_D [\alpha f(x,y) \pm \beta g(x,y)] \, \mathrm{d}\sigma = \alpha \iint\limits_D f(x,y) \, \mathrm{d}\sigma \pm \beta \iint\limits_D g(x,y) \, \mathrm{d}\sigma.$|
|||
|**区域可加性**|若 $D = D_1 \cup D_2$ (且 $D_1, D_2$ 无公共内点), 则|
||$\iint\limits_D f(x,y) \, \mathrm{d}\sigma = \iint\limits_{D_1} f(x,y) \, \mathrm{d}\sigma + \iint\limits_{D_2} f(x,y) \, \mathrm{d}\sigma.$|
|||
|**单调性**|若 $f(x,y)$ 在 $D$ 上可积且 $f(x,y) \ge 0$, 则 $\iint\limits_D f(x,y) \, \mathrm{d}\sigma \ge 0$.|
||*推论:* 若 $f(x,y), g(x,y)$ 均在 $D$ 上可积, 且 $f(x,y) \ge g(x,y)$, 则|
||$\iint\limits_D f(x,y) \, \mathrm{d}\sigma \ge \iint\limits_D g(x,y) \, \mathrm{d}\sigma.$|
|||
|**绝对值不等式**|若 $f(x,y)$ 在 $D$ 上可积, 则 $|f(x,y)|$ 也在 $D$ 上可积, 且|
||$\lvert \iint\limits_D f(x,y) \, \mathrm{d}\sigma\rvert \le \iint\limits_D \lvert f(x,y)\rvert \, \mathrm{d}\sigma.$|
|||
|**估值不等式**|若 $f(x,y)$ 在 $D$ 上可积, 且 $m \le f(x,y) \le M$, 则|
||$m \cdot \mu(D) \le \iint\limits_D f(x,y) \, \mathrm{d}\sigma \le M \cdot \mu(D)$, 其中 $\mu(D)$ 为 $D$ 的面积.|
|||
|**积分中值定理**|若 $f(x,y)$ 在 $D$ 上**连续**, 则存在 $(\xi,\eta) \in D$ 使得|
||$\iint\limits_D f(x,y) \, \mathrm{d}\sigma = f(\xi,\eta) \cdot \mu(D).$|
|||






#### 二重积分的计算


##### 直角坐标系

###### 积分区域类型
> ~~积分区域是什么型, 谁就放在逐次积分的(外层)前面, 也即**先对另外一个积分**~~

###### 计算步骤

1. 画出积分区域 $D$;
2. 选择恰当的积分区域类型 (如 $X$-型或 $Y$-型);
3. 定出积分限, 通过二次积分求出二重积分.
> *投影穿刺法* — ~~一种确定积分限的方法: 将区域投影到坐标轴上, 用平行于坐标轴的直线穿过区域, 根据穿入穿出的边界确定上下限.~~

||*选择积分次序的依据*|
|-:|:-|
|1.|积分区域 $D$ 不分块或少分块|
||即尽量使区域为 $X$-型或 $Y$-型, 避免分割成多块;|
|2.|被积函数 $f(x,y)$ 易积或可积|
||优先选择能使原函数容易求出的积分次序, 避免出现无法积出的函数形式(如 $\int e^{x^2}dx$ 等).|
|3.|实际计算中需权衡区域形状与积分难度, 有时需交换积分次序以简化计算.|

###### 交换积分次序


###### 对称性的应用
|*若$D$关于$x$轴对称,*|$f(x,y)$ 关于 $y$ 为奇(偶)函数, 记 $D_1$ 为 $x$ 轴上半部分区域, 则|
|-:|:-|
||$\iint\limits_D f(x,y)\,\mathrm{d}x\mathrm{d}y = \begin{cases} 0, & f(x,-y) = -f(x,y) \\ 2\iint\limits_{D_1} f(x,y)\,\mathrm{d}x\mathrm{d}y, & f(x,-y) = f(x,y) \end{cases}$|
|||
|*若$D$关于$y$轴对称,*|$f(x,y)$ 关于 $x$ 为奇(偶)函数, 记 $D_1$ 为 $y$ 轴右半部分区域, 则|
||$\iint\limits_D f(x,y)\,\mathrm{d}x\mathrm{d}y = \begin{cases} 0, & f(-x,y) = -f(x,y) \\ 2\iint\limits_{D_1} f(x,y)\,\mathrm{d}x\mathrm{d}y, & f(-x,y) = f(x,y) \end{cases}$|
||~~奇偶性要求区域对称且被积函数具有相应奇偶性~~|
|*轮换对称性*|若 $D$ 关于直线 $y=x$ 对称(即区域对称), 则$D_{xy}=D_{yx}$|
||$\iint\limits_D f(x, y) \, \mathrm{d}\sigma = \iint\limits_D f(y, x) \, \mathrm{d}\sigma = \frac{1}{2} \left[ \iint\limits_D f(x, y) \, \mathrm{d}\sigma + \iint\limits_D f(y, x) \, \mathrm{d}\sigma \right].$(*那么被积函数的$x, y$可交换*)|
|特别地,有|$\iint\limits_D f(x) \, \mathrm{d}x\mathrm{d}y = \iint\limits_D f(y) \, \mathrm{d}x\mathrm{d}y = \frac{1}{2} \iint\limits_D [f(x) + f(y)] \, \mathrm{d}x\mathrm{d}y.$|



##### 极坐标系(二重积分的极坐标换元法)
###### 适用范围

|(1)|当积分区域 $D$ 是圆域或其一部分, |
|-:|:-|
|(2)|或被积函数形如 $f(x^2 + y^2)$.|

###### 计算法





> 极坐标下面积元素 $\mathrm{d}\sigma = \mathrm{d}x\mathrm{d}y = {\color{red}{r}}\,\mathrm{d}r\mathrm{d}\theta$

<svg viewBox="0 0 500 400" width = 200 xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="black" />
    </marker>
  </defs>
  <g stroke="#ddd" stroke-width="1" fill="none">
    <line x1="50" y1="350" x2="430" y2="350" stroke="black" stroke-width="1.5" marker-end="url(#arrow)" /> <line x1="50" y1="350" x2="424.2" y2="284.0" /> <line x1="50" y1="350" x2="407.1" y2="220.1" /> <line x1="50" y1="350" x2="379.1" y2="160.0" stroke="#999" stroke-dasharray="4,2" /> <line x1="50" y1="350" x2="341.0" y2="105.3" stroke="#999" stroke-dasharray="4,2" /> <line x1="50" y1="350" x2="294.3" y2="58.9" />  <line x1="50" y1="350" x2="240.0" y2="21.0" />  <path d="M 150 350 A 100 100 0 0 0 100 263.4" />
    <path d="M 250 350 A 200 200 0 0 0 150 176.8" stroke="#999" /> <path d="M 320 350 A 270 270 0 0 0 185 116.5" stroke="#999" /> <path d="M 400 350 A 350 350 0 0 0 225 47.0" />
  </g>
  <path d="M 150 250 C 180 150, 380 150, 350 280 C 320 380, 200 350, 150 250 Z" 
        fill="none" stroke="black" stroke-width="2.5" opacity="0.8" />
  <text x="170" y="270" font-family="Times New Roman" font-style="italic" font-size="24">D</text>
  <path d="M 223.2 250.0 
           A 200 200 0 0 0 203.2 221.4 
           L 256.8 176.4 
           A 270 270 0 0 1 283.8 215.0 Z" 
        fill="red" stroke="black" stroke-width="1.2" />
  <text x="230" y="235" font-family="Times New Roman" font-style="italic" font-size="18" fill="white">dσ</text>
  <g font-family="Times New Roman, serif" font-style="italic" font-size="20">
    <text x="40" y="370">O</text>
    <text x="435" y="370">A</text>
    <text x="390" y="175">θ + dθ</text>
    <text x="415" y="235">θ</text>
    <text x="240" y="375">r</text>
    <text x="310" y="375">r + dr</text>
  </g>
</svg>


<div align="center" style="font-size: 14px;">


$\boxed{
\begin{aligned}
\iint\limits_D f(x,y)\,\mathrm{d}x\mathrm{d}y &= \iint\limits_D f(\rho\cos\theta,\rho\sin\theta)\,\rho\,\mathrm{d}\rho\mathrm{d}\theta = \int_{\alpha}^{\beta}\mathrm{d}\theta \int_{\rho_1(\theta)}^{\rho_2(\theta)} f(\rho\cos\theta,\rho\sin\theta)\,\rho\,\mathrm{d}\rho,\\
\text{其中 } D' &\text{ 是 } D \text{ 在对应极坐标系中的区域。}\\
D' &= \{(\rho,\theta): \rho_1(\theta)\le \rho\le \rho_2(\theta),\ \alpha\le\theta\le\beta\}.
\end{aligned}
}$

</div>

#### 二重积分的一般换元法

||设 $f(x, y)$ 在 $xOy$ 平面上的闭区域 $D$ 上连续, 变换 $T: x = x(u, v), y = y(u, v)$ 将 $uOv$ 平面上的闭区域 $D'$ 变为 $xOy$ 平面上的 $D$, 且:|
|-:|:-|
|1.|变换 $T: D' \to D$ 是一一对应;|
|2.|$x(u, v), y(u, v) \in C^{(1)}(D')$;即有一阶连续偏导数/一阶导函数连续|
|3.|$D'$ 上的雅可比行列式|
||$$J(u, v) = \dfrac{\partial (x, y)}{\partial (u, v)} = \begin{vmatrix} \dfrac{\partial x}{\partial u} & \dfrac{\partial x}{\partial v} \\ \dfrac{\partial y}{\partial u} & \dfrac{\partial y}{\partial v} \end{vmatrix}\neq 0.$$|
||~~雅可比行列式用于描述多元函数变换下面积（或体积）的局部**伸缩因子**~~|
|则||
||面积微元满足 $\mathrm{d}x\mathrm{d}y = {\color{red}{\lvert}} J(u, v){\color{red}{\rvert}} \, \mathrm{d}u\mathrm{d}v$,|
||$\iint\limits_D f(x, y) \, \mathrm{d}x\mathrm{d}y = \iint\limits_{D'} f[x(u, v), y(u, v)] \, \lvert J(u, v) \rvert \, \mathrm{d}u\mathrm{d}v$.|
||二重积分变量替换的一般公式, 常用于简化积分区域或被积函数, 变换需满足一一对应且具有连续偏导, 雅可比行列式非零保证局部可逆. 公式中的绝对值确保面积元素为正.|


### 三重积分
#### 求解过程
||设 $f(x, y, z)$ 是空间有界闭区域 $\Omega$ 上的有界函数.|
|-:|:-|
|*分割*|将 $\Omega$ 任意分成 $n$ 个小闭区域 $\Delta v_1, \Delta v_2, \dots, \Delta v_n$ ($\Delta v_i$ 也表示体积).|
|*近似*|在每个 $\Delta v_i$ 上任取一点 $(\xi_i, \eta_i, \zeta_i)$, 作乘积 $f(\xi_i, \eta_i, \zeta_i) \Delta v_i$.|
|*求和*|作和式 $\sum\limits_{i=1}^n f(\xi_i, \eta_i, \zeta_i) \Delta v_i$.|
|*取极限*|如果当各小闭区域的直径最大值 $\lambda \to 0$ 时, 上述和式的极限存在, 则称此极限为 $f(x, y, z)$ 在 $\Omega$ 上的**三重积分**, 记为|
||$\iiint\limits_{\Omega} f(x, y, z) \, \mathrm{d}v = \lim\limits_{\lambda \to 0} \sum\limits_{i=1}^n f(\xi_i, \eta_i, \zeta_i) \Delta v_i$.|


#### 性质
> 三重积分具有二重积分的所有性质


#### 计算法

##### 直角坐标


###### 坐标面投影法(先一后二)
> 先对竖直方向($z$)积分得到截面积函数, 再在投影区域上二重积分. 
> 类似可得到 $yz$ 型(先 $x$ 后 $y,z$)和 $xz$ 型(先 $y$ 后 $x,z$)的公式.

**核心思想**:
1. 将空间区域 $\Omega$ 投影到 $xOy$ 平面, 得到投影区域 $D_{xy}$.
2. 对于 $D_{xy}$ 内任意一点 $(x,y)$, 沿 $z$ 方向穿过 $\Omega$, 下边界为 $z = z_1(x,y)$, 上边界为 $z = z_2(x,y)$.
3. 先对 $z$ 积分(把区域切成无数垂直“细丝”), 得到截面上的积分值 $\Phi(x,y) = \int_{z_1}^{z_2} f(x,y,z)\,\mathrm{d}z$.
4. 再在投影区域 $D_{xy}$ 上对 $\Phi(x,y)$ 作二重积分, 即得三重积分.

**适用情形**: 区域 $\Omega$ 为 **$xy$ 型**(或 $yz$ 型, $xz$ 型), 即过区域内任一点作垂直于 $xOy$ 平面的直线与 $\Omega$ 的边界*至多交于两点*.

**基本公式**:
设 $\Omega = \{ (x,y,z) \mid (x,y) \in D_{xy},\; z_1(x,y) \le z \le z_2(x,y) \}$, 则
$$\iiint\limits_{\Omega} f(x,y,z) \, \mathrm{d}V = \iint\limits_{D_{xy}} \left( \int_{z_1(x,y)}^{z_2(x,y)} f(x,y,z) \, \mathrm{d}z \right) \mathrm{d}x\mathrm{d}y$$.

通常写作 **先 $z$ 后 $x,y$**:



$$\boxed{\iiint\limits_{\Omega} f \, \mathrm{d}V = \iint\limits_{D_{xy}} \mathrm{d}x \, \mathrm{d}y \int_{z_1(x,y)}^{z_2(x,y)} f(x,y,z) \, \mathrm{d}z}$$

更进一步, 若投影区域 $D_{xy}$ 是 $X$-型(或$Y$-型): $D_{xy} = \{ (x,y) \mid a \le x \le b,\; y_1(x) \le y \le y_2(x) \}$, 则化为三次积分:
$\iiint\limits_{\Omega} f \, \mathrm{d}V = \int_{x=a}^{b} \int_{y=y_1(x)}^{y_2(x)} \int_{z=z_1(x,y)}^{z_2(x,y)} f(x,y,z) \, \mathrm{d}z \, \mathrm{d}y \, \mathrm{d}x$.

**解题步骤**:
1. 画出空间区域 $\Omega$, 判断其是否为 $xy$ 型(或选择方便的投影面).
2. 写出上下边界曲面方程: $z = z_1(x,y)$ (下), $z = z_2(x,y)$ (上).
3. 确定投影区域 $D_{xy}$ 及其类型($X$-型或 $Y$-型).
4. 代入公式计算.

###### 坐标轴投影法(截面法/切片法/先二后一)

> 先求竖直线段积分再投影.


**核心思想**:
1. 将空间区域 $\Omega$ 向某坐标轴(如 $z$ 轴)投影, 得到投影区间 $[c, d]$.
2. 对每个固定的 $z \in [c, d]$, 用平行于 $xOy$ 的平面截 $\Omega$, 得到截面区域 $D_z$.
3. 先计算截面上的二重积分 $F(z) = \iint\limits_{D_z} f(x,y,z)\,\mathrm{d}x\mathrm{d}y$ (将 $z$ 视为常数).
4. 再对 $z$ 在 $[c,d]$ 上积分: $\int_c^d F(z)\,\mathrm{d}z$.

**基本公式**:
$\iiint\limits_{\Omega} f(x,y,z)\,\mathrm{d}V = \int_{z=c}^{d} \left( \iint\limits_{D_z} f(x,y,z)\,\mathrm{d}x\mathrm{d}y \right) \mathrm{d}z$,
常写作 **先二后一**: 




<div align="center" style="font-size: 14px;">

$\boxed{
\begin{array}{c}
\iiint\limits_{\Omega} f \, \mathrm{d}V = \int_{c}^{d} \mathrm{d}z \iint\limits_{D_z} f(x, y, z) \, \mathrm{d}x \, \mathrm{d}y \\
\text{通常用于被积函数仅与 } z \text{ 有关：} \\
\text{若 } f(x, y, z) = f(z) \text{，且截面面积 } \mu(z) = \iint\limits_{D_z} \mathrm{d}x\mathrm{d}y \text{ 容易求得，则} \\
\iiint\limits_{\Omega} f(z) \, \mathrm{d}V = \int_{c}^{d} f(z) \cdot \mu(z) \, \mathrm{d}z
\end{array}
}$

</div>

**适用情形**:
- 区域 $\Omega$ 容易用垂直于坐标轴的平面截得简单截面(如圆域、椭圆域、三角形、矩形等).
- 被积函数与截面变量无关(或可分离), 从而简化计算.

##### 柱坐标
$\begin{cases} x = \rho\cos\theta \\ y = \rho\sin\theta \\ z = z \end{cases}$.



<svg viewBox="0 0 550 500" width = 300 xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="black" />
    </marker>
    <marker id="arrow-blue" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#0044CC" />
    </marker>
  </defs>

  <style>
    .axis { stroke: black; stroke-width: 1.5; marker-end: url(#arrow); }
    .solid { stroke: black; stroke-width: 2.2; fill: none; stroke-linecap: round; stroke-linejoin: round; }
    .dashed { stroke: #555; stroke-width: 1.2; stroke-dasharray: 4,3; fill: none; }
    .guideline { stroke: #999; stroke-width: 1; stroke-dasharray: 6,4; fill: none; }
    .label { font-family: 'Times New Roman', serif; font-style: italic; font-size: 20px; }
    .label-blue { fill: #0044CC; font-weight: bold; font-family: 'Times New Roman', serif; font-style: italic; font-size: 20px;}
    .dot { fill: black; }
  </style>

  <!-- 1. 坐标轴 (z轴已缩短) -->
  <g class="axis">
    <line x1="150" y1="380" x2="150" y2="120" /> <!-- y2从40改为120 -->
    <line x1="150" y1="380" x2="480" y2="380" /> 
    <line x1="150" y1="380" x2="50" y2="450" />
  </g>
  <text x="160" y="130" class="label">z</text> <!-- y从55改为130 -->
  <text x="465" y="370" class="label">y</text>
  <text x="40" y="470" class="label">x</text>
  <text x="125" y="390" class="label" style="font-weight:bold">O</text>

  <!-- 2. 高度定位点 -->
  <circle cx="150" cy="280" r="3" class="dot" />
  <text x="135" y="285" class="label">z</text>
  <circle cx="150" cy="220" r="3" class="dot" />
  <text x="100" y="225" class="label">z+dz</text>

  <!-- 3. xy平面投影 (原封不动) -->
  <g class="guideline">
    <line x1="150" y1="380" x2="230" y2="435.4" />
    <line x1="150" y1="380" x2="300.4" y2="401.9" />
    <path d="M 200 414.6 A 100 40 0 0 0 244.0 393.7" />
    <path d="M 230 435.4 A 160 64 0 0 0 300.4 401.9" />
  </g>

  <!-- 4. 垂直投影线 (原封不动) -->
  <g class="guideline">
    <line x1="200" y1="414.6" x2="200" y2="314.6" />
    <line x1="230" y1="435.4" x2="230" y2="335.4" />
    <line x1="244.0" y1="393.7" x2="244.0" y2="293.7" />
    <line x1="300.4" y1="401.9" x2="300.4" y2="301.9" />
  </g>

  <!-- 5. 空间放射线 (原封不动) -->
  <g class="dashed">
    <line x1="150" y1="280" x2="200" y2="314.6" />
    <line x1="150" y1="280" x2="244.0" y2="293.7" />
    <line x1="150" y1="220" x2="200" y2="254.6" />
    <line x1="150" y1="220" x2="244.0" y2="233.7" />
  </g>

  <!-- 6. 体积微元实线 (原封不动) -->
  <g class="solid">
    <path d="M 200 254.6 A 100 40 0 0 0 244.0 233.7" /> 
    <line x1="244.0" y1="233.7" x2="300.4" y2="241.9" />
    <path d="M 300.4 241.9 A 160 64 0 0 1 230 275.4" /> 
    <line x1="230" y1="275.4" x2="200" y2="254.6" />
    <line x1="230" y1="275.4" x2="230" y2="335.4" />
    <line x1="300.4" y1="241.9" x2="300.4" y2="301.9" />
    <path d="M 300.4 301.9 A 160 64 0 0 1 230 335.4" /> 
    <line x1="244.0" y1="233.7" x2="244.0" y2="293.7" />
    <line x1="244.0" y1="293.7" x2="300.4" y2="301.9" />
  </g>

  <!-- 7. 微元内部隐线 (原封不动) -->
  <g class="dashed">
    <line x1="200" y1="254.6" x2="200" y2="314.6" />
    <path d="M 200 314.6 A 100 40 0 0 0 244.0 293.7" /> 
    <line x1="200" y1="314.6" x2="230" y2="335.4" />
  </g>

  <!-- 8. 修正后的标注 (基于上一版正确标注) -->
  <g class="label">
    <path d="M 180 401 Q 190 395 200 387" stroke="black" stroke-width="1.2" fill="none" marker-end="url(#arrow)" />
    <text x="195" y="415">dθ</text>
    <line x1="150" y1="380" x2="200" y2="414.6" stroke="black" stroke-width="1.2" stroke-dasharray="2,2" />
    <text x="165" y="415" style="font-weight:bold">ρ</text>
    <text x="260" y="222" class="label-blue">dρ</text>
    <line x1="244" y1="228" x2="300.4" y2="236" stroke="#0044CC" stroke-width="1.5" /> 
    <line x1="244" y1="225" x2="244" y2="231" stroke="#0044CC" stroke-width="1.5" />   
    <line x1="300.4" y1="233" x2="300.4" y2="239" stroke="#0044CC" stroke-width="1.5" /> 
    <text x="160" y="225" class="label-blue">ρ dθ</text>
    <path d="M 185 230 Q 200 240 215 244" fill="none" stroke="#0044CC" stroke-width="1.2" marker-end="url(#arrow-blue)" />
    <text x="320" y="277" class="label-blue">dz</text>
    <line x1="310" y1="241.9" x2="310" y2="301.9" stroke="#0044CC" stroke-width="1.5" /> 
    <line x1="305" y1="241.9" x2="315" y2="241.9" stroke="#0044CC" stroke-width="1.5" />   
    <line x1="305" y1="301.9" x2="315" y2="301.9" stroke="#0044CC" stroke-width="1.5" />   
  </g>
</svg>

###### 体积元素
|**柱坐标系中的体积元素**|$\mathrm{d}V = \rho\,\mathrm{d}\rho\,\mathrm{d}\theta\,\mathrm{d}z$|
|-:|:-|
|推导过程：||
|*由雅可比行列式推得*|变换 $x=\rho\cos\theta,\ y=\rho\sin\theta,\ z=z$ 的雅可比行列式为|
||$$J = \frac{\partial(x,y,z)}{\partial(\rho,\theta,z)} = \begin{vmatrix} \cos\theta & -\rho\sin\theta & 0 \\ \sin\theta & \rho\cos\theta & 0 \\ 0 & 0 & 1 \end{vmatrix} = \rho $$|
|故|$\mathrm{d}x\mathrm{d}y\mathrm{d}z = \lvert J\rvert \,\mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z = \rho\,\mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z$.|
|*由几何关系推得*|取微小区域: $\rho$ 增加 $\mathrm{d}\rho$, $\theta$ 增加 $\mathrm{d}\theta$, $z$ 增加 $\mathrm{d}z$.|
||该区域近似为长方体,|
||边长分别为 $\mathrm{d}\rho$, $\rho\mathrm{d}\theta$(由弧长公式$\mathrm{d}s=\rho\mathrm{d}\theta$得出),$\mathrm{d}z$|
||体积为 $\mathrm{d}\rho \cdot \rho\mathrm{d}\theta \cdot \mathrm{d}z = \rho\,\mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z$.|



###### 适用场景
> 当$\Omega$在$xOy$面上的投影区域$D$是*圆域或部分圆域*时,用柱面坐标计算三重积分比较方便。
柱面坐标常用于*圆柱体,圆锥体等立体上的三重积分*



###### 三重积分柱坐标公式  




$$\boxed{\iiint\limits_{\Omega} f(x,y,z) \, \mathrm{d}x\mathrm{d}y\mathrm{d}z = \iiint\limits_{\Omega} f(\rho\cos\theta, \rho\sin\theta, z) \, \rho \, \mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z}$$

##### 球坐标
$\begin{cases} x = \rho \sin\theta \cos\varphi \\ y = \rho \sin\theta \sin\varphi \\ z = \rho \cos\theta \end{cases}$，且 $x^2 + y^2 + z^2 = \rho^2$。
|*规定*|$\theta$为**俯仰**角, 以$z$轴为0度向下展开|
|-:|:-| 
||$\phi$为**偏航**角, 以$x$轴为0度|

||*新元对应的坐标面*|
|-:|:-|
|$\rho = \text{常数}$|球面|
|$\theta = \text{常数}$|锥面| 
|$\varphi = \text{常数}$|半平面|

<svg viewBox="0 0 550 550" width=200 xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- 标准黑色箭头 -->
    <marker id="arrow" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="black" />
    </marker>
  </defs>
  <style>
    .axis { stroke: black; stroke-width: 1.5; fill: none; marker-end: url(#arrow); }
    .line-rho { stroke: #FF8E6E; stroke-width: 3.5; fill: none; stroke-linecap: round; } /* 矢量rho */
    .line-proj { stroke: #FF0000; stroke-width: 3.5; fill: none; stroke-linecap: round; } /* 投影OP */
    .line-dash { stroke: black; stroke-width: 1.5; stroke-dasharray: 6,4; fill: none; }
    .label { font-family: 'Times New Roman', serif; font-style: italic; font-weight: bold; font-size: 24px; }
    .label-small { font-family: 'Times New Roman', serif; font-style: italic; font-size: 20px; }
    .dot-m { fill: #FF4400; }
    .dot-p { fill: black; }
  </style>
  <!-- 1. 坐标轴 (原点 O 设在 180, 350) -->
  <g class="axis">
    <line x1="180" y1="350" x2="180" y2="40" />   <!-- z轴 -->
    <line x1="180" y1="350" x2="520" y2="350" />  <!-- y轴 -->
    <line x1="180" y1="350" x2="40" y2="490" />   <!-- x轴 (斜率-1) -->
  </g>
  <text x="195" y="60" class="label">z</text>
  <text x="500" y="385" class="label">y</text>
  <text x="50" y="520" class="label">x</text>
  <text x="145" y="360" class="label">O</text>
  <!-- 2. 几何投影点定义 -->
  <!-- M 点坐标 (350, 160) -->
  <!-- P 点坐标 (350, 420) -> M的投影 -->
  <!-- A 点坐标 (110, 420) -> P在x轴上的投影 (x轴方程 y = -x + 530) -->
  <!-- 投影虚线 -->
  <line x1="350" y1="160" x2="350" y2="420" class="line-dash" /> <!-- PM (z高度) -->
  <line x1="110" y1="420" x2="350" y2="420" class="line-dash" /> <!-- AP (y分量, 水平) -->
  <!-- 3. 核心矢量线 -->
  <line x1="180" y1="350" x2="350" y2="420" class="line-proj" /> <!-- OP (红色投影) -->
  <line x1="180" y1="350" x2="350" y2="160" class="line-rho" />  <!-- OM (橙色矢量) -->
  <!-- 4. 关键点打点 -->
  <circle cx="350" cy="160" r="4.5" class="dot-m" /> <!-- M点 -->
  <circle cx="350" cy="420" r="4" class="dot-p" />   <!-- P点 -->
  <!-- 5. 文本标注 (根据新坐标微调位置) -->
  <text x="365" y="160" class="label">M(x, y, z)</text>
  <text x="330" y="465" class="label">P(x, y, 0)</text>
  <text x="80" y="435" class="label">A</text>
  <text x="260" y="260" class="label" style="font-size:30px;">ρ</text> <!-- 矢量rho -->
  <text x="360" y="310" class="label-small">z</text> <!-- 高度z -->
  <text x="220" y="445" class="label-small">y</text> <!-- 长度y -->
  <text x="125" y="395" class="label-small">x</text> <!-- 长度x -->
  <!-- 6. 角度标注 (严格计算圆心角度) -->
  <!-- θ (极角): 从z轴到OM -->
  <!-- 角度范围: -90度 到 -48度 -->
  <path d="M 180 270 A 80 80 0 0 1 233 290" fill="none" stroke="black" stroke-width="1.5" marker-end="url(#arrow)" />
  <text x="205" y="240" class="label" style="font-size:28px;">θ</text>
  <!-- φ (方位角): 从x轴到OP -->
  <!-- x轴方向 135度, OP方向约 22度 -->
  <path d="M 130 400 A 70 70 0 0 0 196 385" fill="none" stroke="black" stroke-width="1.5" marker-end="url(#arrow)" />
  <text x="160" y="450" class="label" style="font-size:28px;">φ</text>
</svg>


###### 体积元素

|**球面坐标系中的体积元素**|$\mathrm{d}V = r^2 \sin\theta \,\mathrm{d}r\,\mathrm{d}\theta\,\mathrm{d}\varphi$|
|-:|:-|
|推导过程：||
|*由雅可比行列式推得*|变换 $x = r\sin\theta\cos\varphi,\ y = r\sin\theta\sin\varphi,\ z = r\cos\theta$ 的雅可比行列式为|
||$J = \frac{\partial(x,y,z)}{\partial(r,\theta,\varphi)} = \begin{vmatrix} \sin\theta\cos\varphi & r\cos\theta\cos\varphi & -r\sin\theta\sin\varphi \\ \sin\theta\sin\varphi & r\cos\theta\sin\varphi & r\sin\theta\cos\varphi \\ \cos\theta & -r\sin\theta & 0 \end{vmatrix} = r^2\sin\theta$,|
|故| $\mathrm{d}x\mathrm{d}y\mathrm{d}z = \lvert J\rvert\,\mathrm{d}r\mathrm{d}\theta\mathrm{d}\varphi = r^2\sin\theta\,\mathrm{d}r\mathrm{d}\theta\mathrm{d}\varphi$.|
|*由几何关系推得*|取微小区域: $r$ 增加 $\mathrm{d}r$, $\theta$ 增加 $\mathrm{d}\theta$, $\varphi$ 增加 $\mathrm{d}\varphi$.|
||该区域近似为长方体, 边长分别为 $\mathrm{d}r$, $r\,\mathrm{d}\theta$, $r\sin\theta\,\mathrm{d}\varphi$,|
||体积为 $\mathrm{d}r \cdot r\,\mathrm{d}\theta \cdot r\sin\theta\,\mathrm{d}\varphi = r^2\sin\theta\,\mathrm{d}r\mathrm{d}\theta\mathrm{d}\varphi$.|


###### 三重积分球坐标公式  


$\boxed{
\iiint\limits_{\Omega} f(x,y,z)\,dV
= \iiint\limits_{\Omega} f(\rho\sin\theta\cos\varphi,\; \rho\sin\theta\sin\varphi,\; \rho\cos\theta) \; \rho^2 \sin\theta \; d\rho \, d\theta \, d\varphi
= \int_{0}^{2\pi} d\varphi \int_{0}^{\pi} d\theta \ \int_{0}^{R} f(\rho\sin\theta\cos\varphi,\; \rho\sin\theta\sin\varphi,\; \rho\cos\theta) \; \rho^2 \sin\theta \; d\rho \
}$


> ~~先积$\rho$, 后积$\theta$, 最后积$\phi$~~


###### 适用场景
|若|被积函数 $f(x, y, z)$ 中含有 $x^2 + y^2 + z^2$|
|-:|:-|
|或者|立体 $\Omega$ 是球体或部分球体|





<!-- |||
|-:|:-|









切向量（方向向量）为
$\vec{\tau} = \nabla F \times \nabla G \big|{M_0} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \ F_x & F_y & F_z \ G_x & G_y & G_z \end{vmatrix}{M_0}$
即 $\vec{\tau} = \left( \begin{vmatrix} F_y & F_z \ G_y & G_z \end{vmatrix}{M_0}, \begin{vmatrix} F_z & F_x \ G_z & G_x \end{vmatrix}{M_0}, \begin{vmatrix} F_x & F_y \ G_x & G_y \end{vmatrix}_{M_0} \right)$.

切线方程（对称式）：
$\frac{x - x_0}{\tau_x} = \frac{y - y_0}{\tau_y} = \frac{z - z_0}{\tau_z}$，其中 $\tau_x, \tau_y, \tau_z$ 为 $\vec{\tau}$ 的分量.

法平面方程（过切点且与切线垂直的平面）：
$\tau_x (x - x_0) + \tau_y (y - y_0) + \tau_z (z - z_0) = 0$.

 -->
