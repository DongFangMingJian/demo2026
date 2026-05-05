


# 格作为代数系统的定义

**定理11.2**  
设 $<S, *, \circ>$ 是具有两个二元运算的代数系统, 若对于 $*$ 和 $\circ$ 运算适合交换律, 结合律, 吸收律, 则可以适当定义 $S$ 中的偏序 $\preceq$, 使得 $<S, \preceq>$ 构成格, 且 $\forall a, b \in S$ 有  
$a \land b = a * b$, $a \lor b = a \circ b$.

根据定理11.2, 可以给出格的另一个等价定义.

**定义11.3**  
设 $<S, *, \circ>$ 是代数系统, $*$ 和 $\circ$ 是二元运算, 如果 $*$ 和 $\circ$ 满足交换律, 结合律和吸收律, 则 $<S, *, \circ>$ 构成格.

(批注: 此定义从代数运算角度刻画格, 与偏序定义等价.)
































# 离散数学
## 数理逻辑
### <!--占位符-->
#### 命题

|**定义**|*判断结果唯一、非真即假*的*陈述句*|
| --: | :-- |
|命题的**真值**|判断的结果|
||**取值**：*真*(真命题)/*假*(假命题)|

> ~~感叹句、祈使句、疑问句都不是命题.~~
> 陈述句中的~~悖论、判断结果不唯一确定的不是命题~~.
> 作为命题，~~是否知道它的真值不重要，重要的是它有唯一的真值~~.

**简单命题**(原子命题)：不能被分解为更简单的命题.
|简单命题*符号化*：|用小写英文字母$p,q,r,...,p_i,q_i,r_i$表示简单命题|
|--:|:--|
||用“1”表示真，“0”表示假|

**复合命题**：由*简单命题通过联结词联结*而成的命题.
#### 联结词
##### 否定
|**定义**|设$p$为命题，复合命题“*非$p$*”(或“$\textcolor{blue}p$*的否定*”)称$\textcolor{red}p$**的否定式**|
| --: | :-- |
||记作$\textcolor{red}{\lnot p}$|
||符号$\textcolor{blue}{\lnot}$称**否定联结词**|
||*规定*$\textcolor{red}{\lnot p}$**为真***当且仅当*$\textcolor{red}p$**为假**|
##### 合取
|**定义**|设$p,q$为两个命题，复合命题“*$p并且q$*”(或“*$p与q$*”)称$\textcolor{red}{p与q}$**的合取式**|
| --: | :-- |
||记作$\textcolor{red}{p\land q}$|
||符号$\textcolor{blue}{\land}$称**合取联结词**|
||*规定*$\textcolor{red}{p\land q}$**为真***当且仅当*$\textcolor{red}{p与q}$**同时为真**|

##### 析取
|**定义**|设$p,q$为两个命题，复合命题“*$p或q$*”称$\textcolor{red}{p与q}$**的析取式**|
| --: | :-- |
||记作$\textcolor{red}{p\lor q}$|
||符号$\textcolor{blue}{\lor}$称**析取联结词**|
||*规定*$\textcolor{red}{p\lor q}$**为假***当且仅当*$\textcolor{red}{p与q}$**同时为假**|

自然语言中的“或”：
|**相容或**|联结的两个命题*可以同时为真*|$\textcolor{red}{p\lor q}$|
|--:|:--|:--|
|**排斥或**|*只有当一个为真、另一个为假时，才为真*|$\textcolor{red}{(p\land \lnot q) \lor (\lnot p \land q)}$|

##### 蕴涵
|**定义**|设$p,q$为两个命题，复合命题“*$如果p，则q$*”称$\textcolor{red}{p与q}$**的蕴涵式**|
| --: | :-- |
||记作$\textcolor{red}{p\to q}$|
||符号$\textcolor{blue}{\to}$称**蕴涵联结词**，$p$称蕴涵式的**前件**，$q$称蕴涵式的**后件**|
||$\textcolor{blue}{p\to q}$的逻辑关系为$\textcolor{red}p$**是$q$的充分条件($q$是$p$的必要条件)**|
||*规定*$\textcolor{red}{p\to q}$**为假***当且仅当*$\textcolor{red}{p为真q为假}$|
|**空证明**|**当$p$为假时，${p\to q}$恒为真**|


> 1\.~~在自然语言中,“如果$p$,则$q$”$p和q$往往具有内存联系.~~
> 2\.~~逻辑学的$p\to q$,$p和q$不关心二者的内在联系,只和二者的真值有关.~~
> 3\.~~命题逻辑属于形式逻辑,只关心命题真值(0/1)之间的推导关系,而不关心命题的真值是如何来的.~~


“$\textcolor{blue}{p\to q}$”的*等价描述*：



##### 等价
|**定义**|设$p,q$为两个命题，复合命题“*$p当且仅当q$*”称$\textcolor{red}{p与q}$**的等价式**|
| --: | :-- |
||记作$\textcolor{red}{p\leftrightarrow q}$|
||符号$\textcolor{blue}{\leftrightarrow}$称**等价联结词**
||$\textcolor{blue}{p\to q}$的逻辑关系为$\textcolor{red}p$**与$q$的充分条件($q$是$p$的必要条件)**|
||*规定*$\textcolor{red}{p\to q}$**为真***当且仅当*$\textcolor{red}{p与q}$**同时为真或为假**|


##### 与非、或非(复合联结词)
|**定义**|设$p,q$为两个命题，复合命题“*$p与q的否定式$*”称$\textcolor{red}{p与q}$**的与非式**|
| --: | :-- |
||记作$\textcolor{red}{p\uparrow q}$,即$\color{red}{p \uparrow q \Leftrightarrow \lnot (p \land q)}$|
||符号$\textcolor{blue}{\uparrow}$称**与非联结词**|
||设$p,q$为两个命题，复合命题“*$p或q的否定式$*”称$\textcolor{red}{p与q}$**的或非式**|
||记作$\textcolor{red}{p\downarrow q}$,即$\color{red}{p \downarrow q \Leftrightarrow \lnot (p \lor q)}$|
||符号$\textcolor{blue}{\downarrow}$称**或非联结词**|
|*完备性*|$\{\uparrow\},\{\downarrow\}$都是联结词完备集|


##### 联结词优先级
> **(),$\lnot,\land,\lor,\to,\leftrightarrow$**
##### 联结词真值表

<table class="bordered-table">
  <tr>
    <th><math><mi>p</mi><mspace width="1em"/><mi>q</mi></math></th>
    <th><math><mrow><mo>&not;</mo><mi>p</mi></mrow></math></th>
    <th><math><mrow><mi>p</mi><mo>&and;</mo><mi>q</mi></mrow></math>(有0则0,一假全假)</th>
    <th><math><mrow><mi>p</mi><mo>&or;</mo><mi>q</mi></mrow></math>(有1则1,一真全真)</th>
    <th><math><mrow><mi>p</mi><mo>&rarr;</mo><mi>q</mi></mrow></math></th>
    <th><math><mrow><mi>p</mi><mo>&harr;</mo><mi>q</mi></mrow></math></th>
  </tr>
  <tr>
    <td>0<math><mspace width="1em"/></math>0</td>
    <td>1</td>
    <td>0</td>
    <td>0</td>
    <td>1(空证明)</td>
    <td>1</td>
  </tr>
  <tr>
    <td>0<math><mspace width="1em"/></math>1</td>
    <td>1</td>
    <td>0</td>
    <td>1</td>
    <td>1(空证明)</td>
    <td>0</td>
  </tr>
  <tr>
    <td>1<math><mspace width="1em"/></math>0</td>
    <td>0</td>
    <td>0</td>
    <td>1</td>
    <td>0</td>
    <td>0</td>
  </tr>
  <tr>
    <td>1<math><mspace width="1em"/></math>1</td>
    <td>0</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
  </tr>
</table>

#### 命题公式
|**命题常项(命题常元)**:|即*简单命题*,真值是确定的|
|--:|:--|
|**命题变项(命题变元)**:|*真值可以变化的陈述句*|
||~~命题变项不是命题~~|
##### 合式公式
|**定义**|将命题变项*用联结词和圆括号按照一定的逻辑关系联结起来*的**符号串**称合式公式|
|--:|:--|
|*递归定义*|单个命题变项是合式公式,并称为原子命题公式.|
||&nbsp;若$A$是合式公式,则(*$\lnot A$*)是合式公式|
||&nbsp;若$A,B$是合式公式,则$(A\land B),(A\lor B),(A\to B),(A\leftrightarrow B)$是合式公式|
||&nbsp;&nbsp;**有限次地应用**以上定义形成的符号串是合式公式|

##### 公式层次
|**定义**|(1)若公式$A$是单个的命题变项,则称$A$为0层公式|
|--:|:--|
||(2)称$A$是$n + 1(n\ge 0)$层应满足:|
||&nbsp;(a)$A = \lnot B$,其中$B,C$分别为$i$层和$j$层,且$n = \max(i,j)$;|
||&nbsp;(b)$A = B \lor C$,其中$B,C$分别为$i$层和$j$层,且$n = \max(i,j)$;|
||&nbsp;(c)$A = B \land C$,其中$B,C$分别为$i$层和$j$层,且$n = \max(i,j)$;|
||&nbsp;(d)$A = B \to C$,其中$B,C$分别为$i$层和$j$层,且$n = \max(i,j)$;|
||&nbsp;(e)$A = B \leftrightarrow C$,其中$B,C$分别为$i$层和$j$层,且$n = \max(i,j)$;|
||(3)若公式$A$的层次为$k$,则称$A$为$k$层公式|
||~~即进行一次运算,层数+1~~|
##### 赋值
##### 真值表
##### 命题公式的分类
||设$A$为任一命题公式|
|--:|:--|
|**重言式**|若$A$在它的各种赋值下取值均为真,则称$A$为重言式(永真式)|
||~~重言式一定是可满足式~~|
|**矛盾式**|若$A$在它的各种赋值下取值均为假,则称$A$为矛盾式(永假式)|
|**可满足式**|若$A$不是矛盾式,则称$A$为可满足式|
||*等价定义*:$A$至少存在一个成真赋值|
|**非重言式的可满足式**|若公式$A$是可满足式,且它至少存在一个成假赋值,则称$A$为非重言式的可满足式|

#### 等值演算
##### 等值式模式
|1.**双重否定律**|*$A$* $\iff$ *$\lnot \lnot A$*|
|--:|---|
| 2.**幂等律** | *$A \land A$* $\iff$ *$A$* ,*$A \lor A$* $\iff$ *$A$* |
| 3.**交换律** | *$A \land B$* $\iff$ *$B \land A$* , *$A \lor B$* $\iff$ *$B \lor A$* |
| 4.**结合律** | *$(A \land B) \land C$* $\iff$ *$A \land (B \land C)$* , *$(A \lor B) \lor C$* $\iff$ *$A \lor (B \lor C)$* |
| 5.**分配律** | *$A \land (B \lor C)$* $\iff$ *$(A \land B) \lor (A \land C)$*,($\land 对 \lor 的分配$)|
|~~相互对偶~~|*$A \lor (B \land C)$* $\iff$ *$(A \lor B) \land (A \lor C)$*,($\lor 对 \land 的分配$)|
|推论:|$(A \lor B) \land (C \lor D) \iff (A \land C) \lor (A \land D) \lor (B \land C) \lor (B \land D)$|
||$(A \land B) \lor (C \land D) \iff (A \lor C) \land (A \lor D) \land (B \lor C) \land (B \lor D)$|
| 6.**德摩根律** | *$\lnot (A \land B)$* $\iff$ *$\lnot A \lor \lnot B$* , *$\lnot (A \lor B)$* $\iff$ *$\lnot A \land \lnot B$* |
| 7.**吸收律** | *$A \land (A \lor B)$* $\iff$ *$A$* , *$A \lor (A \land B)$* $\iff$ *$A$* |
| 8.**零律** | *$A \land 0$* $\iff$ *$0$* , *$A \lor 1$* $\iff$ *$1$* |
| 9.**同一律** | *$A \land 1$* $\iff$ *$A$* , *$A \lor 0$* $\iff$ *$A$* |
| 10.**排中律** | *$A \lor \lnot A$* $\iff$ *$1$* |
| 11.**矛盾律** | *$A \land \lnot A$* $\iff$ *$0$* |
| 12.**蕴涵等值式** | *$A \rightarrow B$* $\iff$ *$\lnot A \lor B$* |
| 13.**等价等值式** | *$A \leftrightarrow B$* $\iff$ *$(A \rightarrow B) \land (B \rightarrow A)$* |
| 14.**假言易位** | *$A \rightarrow B$* $\iff$ *$\lnot B \rightarrow \lnot A$* |
| 15.**等价否定等值式** | *$A \leftrightarrow B$* $\iff$ *$\lnot A \leftrightarrow \lnot B$* |
| 16.**归谬论** | *$(A \rightarrow B) \land (A \rightarrow \lnot B)$* $\iff$ *$\lnot A$* |

|*置换规则*|设$\varPhi (A)$是含公式$A$的命题公式,$\varPhi (B)$是用公式$B$置换$\varPhi (A)$是$A$的所有出现后得到的命题公式.|
|--:|:--|
||若$B \Leftrightarrow A$,则$\varPhi (A) \Leftrightarrow \varPhi (B)$.|

##### 析取范式与合取范式
|**定义**|*命题变项及其否定*统称**文字**|
|--:|:--|
||仅由*有限个文字*构成的*析取式*称**简单析取式**|
||仅由*有限个文字*构成的*合取式*称**简单合取式**|
||~~一个文字~~**既**~~是简单析取式,~~**又**~~是简单合取式~~|

|**简单析取式重言式判定定理**|一个*简单析取式*是**重言式**当且仅当它**同时含某个命题变项及它的否定式**|
|--:|:--|
|**简单合取式矛盾式判定定理**|一个*简单合取式*是**矛盾式**当且仅当它**同时含某个命题变项及它的否定式**|

|由*有限个简单合取式的析取*构成的命题公式称**析取范式**|$A_1 \lor A_2\lor ...\lor A_s$|
|--:|:--|
|由*有限个简单析取式的合取*构成的命题公式称**合取范式**|$B_1 \land B_2\land ...\land B_t$|
|||

|**范式存在定理**|*任一命题公式***都存在与之等值的析取范式与合取范式**|
|--:|:--|

|**求给定公式范式**的步骤:|1.消去$\to ,\leftrightarrow$|~~蕴涵等值式,等价等值式~~|
|--:|:--|:--|
||2.$\lnot$内移或消去|~~德摩根律,双重否定律~~|
||3.分配律|求析取范式: $\land$对$\lor$分配|
|||求合取范式: $\lor$对$\land$分配|

###### 极小项与极大项
|**定义**|在含$n$个命题变项的简单合取式(简单析取式)中,若每个命题变项均以文字的形式在其中*出现且仅出现一次*,而且第个文字出现在左起第i位上($1 \leq i \leq n$),称这样的简单合取式(简单单析取式)为极小项(极大项).|
|--:|:--|


  <table class="bordered-table">
    <!-- 表头：六列，分别对应极小项表达式、成真赋值、极小项名称、极大项表达式、成假赋值、极大项名称 -->
    <tr>
      <th><math><mi>极小项</mi> <mspace width="0.5em"/></math></th>
      <th><math><mi>成真赋值</mi></math></th>
      <th><math><mi>名称</mi></math></th>
      <th><math><mi>极大项</mi> <mspace width="0.5em"/></math></th>
      <th><math><mi>成假赋值</mi></math></th>
      <th><math><mi>名称</mi></math></th>
    </tr>
    <tr>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">0 0 0</td>
      <td><math><msub><mi>m</mi><mn>0</mn></msub></math></td>
      <td>
        <math>
          <mi>p</mi> <mo>∨</mo> <mi>q</mi> <mo>∨</mo> <mi>r</mi>
        </math>
      </td>
      <td class="assignment">0 0 0</td>
      <td><math><msub><mi>M</mi><mn>0</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∧</mo>
          <mi>r</mi>
        </math>
      </td>
      <td class="assignment">0 0 1</td>
      <td><math><msub><mi>m</mi><mn>1</mn></msub></math></td>
      <td>
        <math>
          <mi>p</mi> <mo>∨</mo> <mi>q</mi> <mo>∨</mo> <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">0 0 1</td>
      <td><math><msub><mi>M</mi><mn>1</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∧</mo>
          <mi>q</mi> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">0 1 0</td>
      <td><math><msub><mi>m</mi><mn>2</mn></msub></math></td>
      <td>
        <math>
          <mi>p</mi> <mo>∨</mo> <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∨</mo> <mi>r</mi>
        </math>
      </td>
      <td class="assignment">0 1 0</td>
      <td><math><msub><mi>M</mi><mn>2</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∧</mo>
          <mi>q</mi> <mo>∧</mo>
          <mi>r</mi>
        </math>
      </td>
      <td class="assignment">0 1 1</td>
      <td><math><msub><mi>m</mi><mn>3</mn></msub></math></td>
      <td>
        <math>
          <mi>p</mi> <mo>∨</mo> <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∨</mo> <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">0 1 1</td>
      <td><math><msub><mi>M</mi><mn>3</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mi>p</mi> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">1 0 0</td>
      <td><math><msub><mi>m</mi><mn>4</mn></msub></math></td>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∨</mo> <mi>q</mi> <mo>∨</mo> <mi>r</mi>
        </math>
      </td>
      <td class="assignment">1 0 0</td>
      <td><math><msub><mi>M</mi><mn>4</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mi>p</mi> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∧</mo>
          <mi>r</mi>
        </math>
      </td>
      <td class="assignment">1 0 1</td>
      <td><math><msub><mi>m</mi><mn>5</mn></msub></math></td>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∨</mo> <mi>q</mi> <mo>∨</mo> <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">1 0 1</td>
      <td><math><msub><mi>M</mi><mn>5</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mi>p</mi> <mo>∧</mo>
          <mi>q</mi> <mo>∧</mo>
          <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">1 1 0</td>
      <td><math><msub><mi>m</mi><mn>6</mn></msub></math></td>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∨</mo> <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∨</mo> <mi>r</mi>
        </math>
      </td>
      <td class="assignment">1 1 0</td>
      <td><math><msub><mi>M</mi><mn>6</mn></msub></math></td>
    </tr>
    <tr>
      <td>
        <math>
          <mi>p</mi> <mo>∧</mo>
          <mi>q</mi> <mo>∧</mo>
          <mi>r</mi>
        </math>
      </td>
      <td class="assignment">1 1 1</td>
      <td><math><msub><mi>m</mi><mn>7</mn></msub></math></td>
      <td>
        <math>
          <mrow><mo>¬</mo><mi>p</mi></mrow> <mo>∨</mo> <mrow><mo>¬</mo><mi>q</mi></mrow> <mo>∨</mo> <mrow><mo>¬</mo><mi>r</mi></mrow>
        </math>
      </td>
      <td class="assignment">1 1 1</td>
      <td><math><msub><mi>M</mi><mn>7</mn></msub></math></td>
    </tr>
  </table>

|**极小项与极大项的互否定关系定理**|设 $ m_i $ 与 $ M_i $ 是命题变项含 $ p_1, p_2, \cdots, p_n $ 的极小项和极大项，则|
|--:|:-:|
||$\color{red}{\neg m_i \Leftrightarrow M_i, \quad \neg M_i \Leftrightarrow m_i.}$|
||~~德摩根律的多元推广~~|

###### 主析/合取范式

|**定义**|所有**简单合取式**(*简单析取式*)都是**极小项**(*极大项*)的**析取范式**(*合取范式*)称为**主析取范式**(*主合取范式*)|
|--:|:--|

|**主范式存在定理**|*任何命题公式***都存在与之等值的主析取范式与主合取范式**,并且是**唯一的**|
|--:|:--|
|*证明*||


> **求主析取范式**的步骤：

> >设公式 $A$ 含命题变项 $p_1, p_2, \dots, p_n$。

> > 1\. *求析取范式*  
   求 $A$ 的析取范式 $A' = B_1 \lor B_2 \lor \dots \lor B_s$，其中 $B_j$ 是简单合取式，$j = 1, 2, \dots, s$。

> > 2\. *展开缺失变项*  
   若某个 $B_j$ 既不含 $p_i$，又不含 $\neg p_i$，则将 $B_j$ 展开为  
   $B_j \Leftrightarrow B_j \land (p_i \lor \neg p_i) \Leftrightarrow (B_j \land p_i) \lor (B_j \land \neg p_i)$  ~~同一律、排中律~~
   重复此过程，直到所有简单合取式都是长度为 $n$ 的极小项为止。

> > 3\. *消去重复项*  
   消去重复出现的极小项，即用 $m_i$ 代替 $m_i \lor m_i$。

> > 4\. *排序*  
   将极小项按下标从小到大排列。

> **求主合取范式**的步骤：

> > 设公式 $A$ 含命题变项 $p_1, p_2, \dots, p_n$。

> > 1\. *求合取范式*  
   求 $A$ 的合取范式 $A' = B_1 \land B_2 \land \dots \land B_s$，其中 $B_j$ 是简单析取式，$j = 1, 2, \dots, s$。

> > 2\. *展开缺失变项*  
   若某个 $B_j$ 既不含 $p_i$，又不含 $\neg p_i$，则将 $B_j$ 展开为
   $B_j \Leftrightarrow B_j \lor (p_i \land \neg p_i) \Leftrightarrow (B_j \lor p_i) \land (B_j \lor \neg p_i)$ ~~零律、矛盾律~~
   重复此过程，直到所有简单析取式都是长度为 $n$ 的极大项为止。

> > 3\. *消去重复项*  
   消去重复出现的极大项，即用 $M_i$ 代替 $M_i \land M_i$。

> > 4\. *排序*  
   将极大项按下标从小到大排列。

> 主范式的**应用**

> > 1\. *求公式的成真、成假赋值*
> > > 设公式 $A$ 含 $n$ 个命题变项，$A$ 的主析取范式有 $s$ 个极小项，则 $A$ 有 $s$ 个成真赋值，它们是极小项下标的二进制表示，其余 $2^n - s$ 个赋值都是成假赋值。
> > > 类似地，由主合取范式也立即求出成假赋值和成真赋值。

> > 2\. *判断*公式的*类型*
> > > 设 $A$ 含 $n$ 个命题变项。

> > > - $A$ 为重言式  
  $\iff$ $A$ 的主析取范式含全部 $2^n$ 个极小项  
  $\iff$ $A$ 的主合取范式不含任何极大项。

> > > - $A$ 为矛盾式  
  $\iff$ $A$ 的主合取范式含全部 $2^n$ 个极大项  
  $\iff$ $A$ 的主析取范式不含任何极小项。

> > > - $A$ 为非重言式的可满足式  
  $\iff$ $A$ 的主析取范式中至少含一个、但不是全部极小项  
  $\iff$ $A$ 的主合取范式中至少含一个、但不是全部极大项。

> > 3\. *判断两个公式是否等值*  ~~主范式存在定理~~
> > 4\. 解实际问题
##### 联结词完备集

|**定义**|设 $S$ 是一个联结词集合，如果*任何 $n(n \geq 1)$ 元真值函数都可以由仅含 $S$ 中的联结词构成的公式表示*，则称 $S$ 是联结词完备集。|
|--:|:--|
||~~若 $S$ 是联结词完备集，则任何命题公式都可由 $S$ 中的联结词表示。~~|
|**联结词完备集定理**|$S = \{ \neg, \land, \lor \}$ 是联结词完备集|
||~~由范式存在定理可证。~~|
|*联结词完备集推论*|1.$S = \{\lnot,\land,\lor,\rightarrow \}$ 是联结词完备集|
||2.$S = \{\lnot,\land,\lor,\rightarrow,\leftrightarrow \}$ 是联结词完备集|
||3.$S = \{\lnot,\land \}$ 是联结词完备集|
||*证明*:|
||4.$S = \{\lnot,\lor \}$ 是联结词完备集|
||*证明*:|
||5.$S = \{\lnot,\rightarrow \}$ 是联结词完备集|
||*证明*:|
||6.$S = \{\lnot,\lor \}$ 是联结词完备集|
||*证明*:|
||7.$S = \{\uparrow \}$和$S = \{\downarrow \}$ 都是联结词完备集|
||*证明*:|


##### 真值函数

|**定义**|真值函数是*从所有可能的输入真值组合到输出真值的映射*。|
|-:|:-|  
|用数学语言表述|$F : \{0,1\}^n \to \{0,1\}$|

> \(\{0,1\}^n\)：由 \(n\) 个 0/1 组成的所有可能序列，共有 \(2^n\) 种(n为命题变元的个数)。
> 对于所有可能序列的每个输入组合，输出可以是 0 或 1，因此不同的 \(n\) 元真值函数总数为：**$2^{2^n}$**


> > 二元真值函数:
<table class="bordered-table">
    <thead>
        <tr>
            <th><math><mo>(</mo><mi>p</mi><mo>,</mo><mi>q</mi><mo>)</mo></math></th>
            <th><math><msubsup><mi>F</mi><mn>0</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>1</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>2</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>3</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>4</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>5</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>6</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>7</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
        </tr>
    </thead>
    <tbody>
        <tr><td>(0,0)</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td></tr>
        <tr><td>(0,1)</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>1</td><td>1</td></tr>
        <tr><td>(1,0)</td><td>0</td><td>0</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td></tr>
        <tr><td>(1,1)</td><td>0</td><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td></tr>
    </tbody>
</table>

<table class="bordered-table">
    <thead>
        <tr>
            <th><math><mo>(</mo><mi>p</mi><mo>,</mo><mi>q</mi><mo>)</mo></math></th>
            <th><math><msubsup><mi>F</mi><mn>8</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>9</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>10</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>11</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>12</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>13</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>14</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
            <th><math><msubsup><mi>F</mi><mn>15</mn><mrow><mo>(</mo><mn>2</mn><mo>)</mo></mrow></msubsup></math></th>
        </tr>
    </thead>
    <tbody>
        <tr><td>(0,0)</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr>
        <tr><td>(0,1)</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>1</td><td>1</td></tr>
        <tr><td>(1,0)</td><td>0</td><td>0</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td></tr>
        <tr><td>(1,1)</td><td>0</td><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td></tr>
    </tbody>
</table>




> 1\.~~每个逻辑联结词（如 \(\neg, \land, \lor, \to\)）都对应一个具体的真值函数。~~
> 2\.~~反过来，任意一个真值函数都可以用联结词构成的公式表示(例如通过主析取范式或主合取范式)。这体现了“语法”(公式)与“语义”(真值函数)的对应关系。~~



#### 推理理论
##### 推理的形式结构
|**定义**|设 $A_1, A_2, \dots, A_k, B$ 为命题公式。若对于每组赋值，
|-:|:-|  
||$A_1 \land A_2 \land \dots \land A_k$ 为假，或当 $A_1 \land A_2 \land \dots \land A_k$ 为真时，$B$ 也为真，|
||则称由前提 $A_1, A_2, \dots, A_k$ 推出结论 $B$ 的推理是**有效的**或**正确的**，并称 $B$ 是**有效结论**。|
|1.|前提：$A_1, A_2, \dots, A_k$  |
||结论：$B$
|2.|推理记为:|
||$\{A_1, A_2, \dots, A_k\} \vdash B$|
||若推理正确，记为| 
||$\{A_1, A_2, \dots, A_n\} \models B$|
||~~推理正确不能保证结论一定正确(前提错误,即空证明)~~|
|*判断推理是否正确*的方法:|1.真值表法|
||2.等值演算法|
||3.主析取范式法|
##### 推理定律

|**推理正确性判定定理**|由命题公式 $ A_1, A_2, \cdots, A_k $ 推导出 $ B $ 的推理正确当且仅当 $\color{red}{A_1 \land A_2 \land \cdots \land A_k \to B} $为**重言式**|
|--:|:--|

| 1.**附加律** | $A \Rightarrow (A \lor B)$ |
| ---: | :--- |
| 2.**化简律** | $(A \land B) \Rightarrow A$ |
| 3.**假言推理** | $(A \rightarrow B) \land A \Rightarrow B$ |
| 4.**拒取式** | $(A \rightarrow B) \land \neg B \Rightarrow \neg A$ |
| 5.**析取三段论** | $(A \lor B) \land \neg B \Rightarrow A$ |
| 6.**假言三段论** | $(A \rightarrow B) \land (B \rightarrow C) \Rightarrow (A \rightarrow C)$ |
| 7.**等价三段论** | $(A \leftrightarrow B) \land (B \leftrightarrow C) \Rightarrow (A \leftrightarrow C)$ |
| 8.**构造性二难** | $(A \rightarrow B) \land (C \rightarrow D) \land (A \lor C) \Rightarrow (B \lor D)$ |
| 构造性二难（*特殊形式*） | $(A \rightarrow B) \land (\neg A \rightarrow B) \Rightarrow B$ |
| 9.**破坏性二难** | $(A \rightarrow B) \land (C \rightarrow D) \land (\neg B \lor \neg D) \Rightarrow (\neg A \lor \neg C)$ |

> **每个等值式可以产生两个推理定律**
> > 例如，由等值式 $A \Leftrightarrow \neg\neg A$(双重否定律)可得到：  
> > - $A \Rightarrow \neg\neg A$  
> > - $\neg\neg A \Rightarrow A$  


##### 自然推理系统 $P$
###### 证明
|**定义**|一个描述推理过程的*命题公式序列*;|
|-:|:-|
||每个公式或者是已知前提，或者是由前面公式应用推理规则得到的结论。|
###### 推理系统的分类
|**自然推理系统**|从*任意给定的前提出发*，应用推理规则进行推理演算，最后得到结论.|
|-:|:-|
|公理推理系统|从若干条给定的公理出发，应用推理规则进行推理演算，最后得到结论.|
###### 自然推理系统 $P$ 的定义
|1\.字母表|(1) 命题变项符号：$p, q, r, \dots, p_i, q_i, r_i, \dots$  |
|-:|:-|
||(2) 联结词符号：$\neg, \land, \lor, \rightarrow, \leftrightarrow$|
||(3) 括号与逗号：$(，)，,$|
|2\.合式公式||
|3\.推理规则|(1) 前提引入规则|
||&nbsp;在证明的任何步骤中都可以引入前提|
||(2) 结论引入规则|
||&nbsp;由证明的任何步骤得到的结论都可以作为后继证明的前提|
||(3) 置换规则|
||&nbsp;在证明的任何步骤中,命题公式中的子公式都可以用等值的公式置换,得到公式序列中的又一个公式.|
||由 9 条推理定律和结论引入规则可以导出以下各条推理规则:|
||(5) 附加规则 |
|| $\begin{array}{c} A \\ \hline \therefore A \lor B \end{array}$ |
||(6) 化简规则 |
|| $\begin{array}{c} A \land B \\ \hline \therefore A \end{array}$ |
||(7) 拒取式规则 |
|| $\begin{array}{c} A \rightarrow B \\ \neg B \\ \hline \therefore \neg A \end{array}$ |
||(8) 假言三段论规则 |
|| $\begin{array}{c} A \rightarrow B \\ B \rightarrow C \\ \hline \therefore A \rightarrow C \end{array}$ |
||(9) 析取三段论规则 |
|| $\begin{array}{c} A \lor B \\ \neg B \\ \hline \therefore A \end{array}$ |
||(10) 构造性二难推理规则 |
|| $\begin{array}{c} A \rightarrow B \\ C \rightarrow D \\ A \lor C \\ \hline \therefore B \lor D \end{array}$ |
|| (11) 破坏性二难推理规则 |
||$\begin{array}{c} A \rightarrow B \\ C \rightarrow D \\ \lnot B \lor \lnot D \\ \hline \therefore \lnot A \lor \lnot C \end{array}$ |
|| (12) 合取引入规则 |
|| $\begin{array}{c} A \\ B \\ \hline \therefore  A \land B \end{array}$ |

###### 构造证明
> 设前提 $A_1, A_2, \dots, A_k$，结论 $B$ 及公式序列 $C_1, C_2, \dots, C_l$.

> 如果每一个 $C_i (1 \leq i \leq l)$ 是某个 $A_j$，或者可由序列中前面的公式应用推理规则得到，并且 $C_i = B$，则称这个公式序列是由 $A_1, A_2, \dots, A_k$ 推出 $B$ 的**证明**。
1. 直接证明法
直接使用推理规则，从前提出发，逐步推导出结论。
2. *附加前提证明法*
> ~~适用于结论为蕴涵式~~

|欲证|前提：$A_1, A_2, \dots, A_k$|
|-:|:-|
||结论：$C \rightarrow B$| 
|等价地证明|前提：$A_1, A_2, \dots, A_k, C$|
||结论：$B$  |
|理由(两者的等价性证明)|$(A_1 \land A_2 \land \dots \land A_k) \rightarrow (C \rightarrow B)$|
|$\iff$|$\neg (A_1 \land A_2 \land \dots \land A_k) \lor (\neg C \lor B)$|
|$\iff $|$\neg (A_1 \land A_2 \land \dots \land A_k \land C) \lor B$|
|$\iff$|$ (A_1 \land A_2 \land \dots \land A_k \land C) \rightarrow B$|

3.*归谬法(反证法)*
> 将结论的否定式作为附加前提引入并推出矛盾


|欲证|前提：$A_1, A_2, \dots, A_k$|
|-:|:-|
||结论：$B$|
|做法:|在前提中加入 $\neg B$，推出矛盾。
|理由:|$A_1 \land A_2 \land \cdots \land A_k \rightarrow B$|
|$\iff$|$\neg (A_1 \land A_2 \land \cdots \land A_k) \lor B$|
|$\iff$|$\neg (A_1 \land A_2 \land \cdots \land \neg A_k \land \neg B)$|
|$\iff$|$\neg (A_1 \land \neg A_2 \land \cdots \land \neg A_k \land \neg B) \lor 0$|
|$\iff$|$\neg A_1 \land A_2 \land \cdots \land \neg A_k \land \neg B \rightarrow 0$|




## 集合论
### 集合代数


#### 集合的基本概念

> ~~集合没有精确的数学定义,有着相当宽泛的范畴~~

|常见的数集||
|-:|:-|
|$\mathbb{N}$|自然数集|
||~~离散数学中认为0也是自然数~~|
|$\mathbb{Z}$|整数集|
|$\mathbb{Q}$|有理数集|
|$\mathbb{R}$|实数集|
|$\mathbb{C}$|复数集|

##### 集合的表示法
|枚举法|通过列出全体元素来表示集合|
|-:|:-|
|*谓词表示法*|通过谓词概括集合元素的性质|

##### 集合的元素具有的性质

|无序性|相异性|确定性|任意性(~~集合也可以是集合的元素~~)|
|-|-|-|-|

##### 集合与元素之间的关系
|*隶属关系*|$\in$或$\notin$|
|-:|:-|

##### 集合与集合之间的关系
###### 包含关系
|**定义**|设$A, B$是两个集合, 如果$ A $中每个元素都是$B $中的元素, 则称$ A $是$ B $的子集合, 也称$ A $包含于$ B$, 或$ B $包含$ A$|
|-:|:-|
||记作$A \subseteq B$|
||如果$A$不被$B$包含,记为$A \nsubseteq B$|
|*符号表示*|$A \subseteq B \Leftrightarrow \forall x(x \in A {\color{red}{\rightarrow }} B)$|
||$A \not\subseteq B \Leftrightarrow \exists x (x \in A {\color{red}{\land}} x \notin B)$|
|**真子集**|$A\subset B \Leftrightarrow A \subseteq B \land A \not ={B}$|

###### 集合相等
||记作$A = B$|
|-:|:-|
||如果不相等,记为$A \not ={B}$|
|*符号表示*|$A = B \Leftrightarrow A{\color{red}{\subseteq}} B \land B {\color{red}{\subseteq}}A$|
||$A \not ={B} \Leftrightarrow A{\color{red}{\not\subseteq}}B {\color{red}{\lor}} B{\color{red}{\not\subseteq}}A$|

##### 空集
|**定义**|不含任何元素的集合|
|-:|:-|
|*符号表示*|$\varnothing = \{x\|x \not ={x}\}$|

|**空集即子集定理**|空集是一切集合的**子集**|
|-:|:-|
|*证明*|$\forall A(\forall x(x\in \varnothing \to x \in A))$ ~~空证明,前件恒假,命题恒真~~|
|$\Leftrightarrow$|$\varnothing \subseteq A$ ~~子集的定义~~|
|**空集唯一定理**|空集是唯一的|
|*证明*|假设存在空集$\varnothing_1, \varnothing_2$|
||由*空集即子集定理*有$\varnothing_1 \subseteq \varnothing_2$和$\varnothing_2 \subseteq \varnothing_1$|
||即$\varnothing_1 \subseteq \varnothing_2 \land \varnothing_2 \subseteq \varnothing_1$|
|$\Leftrightarrow$|$\varnothing_1 = \varnothing_2$ ~~集合相等的定义~~|

##### 幂集
|**定义**|集合$A$的全体子集构成的集合称为$ A $的幂集$ P (A)$|
|-:|:-|
|*符号表示*|$P(A) = \{x\|x\subseteq A \}$|
|*计数*|若$\|A\| = n$,则$\|P(A)\| = 2^n$|
##### 全集
|**定义**|在一个具体问题中，若所涉及的集合都是某个集合的子集，则称这个集合为全集$E$|
|-:|:-|
||全集具有相对性:与问题有关,不存在绝对的全集|

#### 集合的运算



##### 并
|**定义**|$A \cup B = \{ x \mid x \in A \lor x \in B \}$|
|-:|:-|
|*有限推广性*|可以推广到有穷个集合上|
||$A_1 \cup A_2 \cup \dots \cup A_n = \{ x \mid x \in A_1 \lor x \in A_2 \lor \dots \lor x \in A_n \}$|

<svg width="100" height="75" viewBox="0 0 200 150" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="150" fill="#f9f9f9" stroke="#ccc" />
  <circle cx="70" cy="70" r="50" fill="rgba(255,0,0,0.4)" stroke="black" stroke-width="1.5" />
  <circle cx="110" cy="70" r="50" fill="rgba(0,0,255,0.4)" stroke="black" stroke-width="1.5" />
  <text x="45" y="130" font-size="12">A</text>
  <text x="135" y="130" font-size="12">B</text>
  <text x="10" y="20" font-size="14">A ∪ B</text>
</svg>

##### 交
|**定义**|$A \cap B = \{ x \mid x \in A \land x \in B \}$|
|-:|:-|
|*有限推广性*|可以推广到有穷个集合上|
||$A_1 \cap A_2 \cap \dots \cap A_n = \{ x \mid x \in A_1 \land x \in A_2 \land \dots \land x \in A_n \}$|

<svg width="100" height="75" viewBox="0 0 200 150" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="150" fill="#f9f9f9" stroke="#ccc" />
  <defs>
    <clipPath id="intersect">
      <circle cx="70" cy="70" r="50" />
      <circle cx="110" cy="70" r="50" />
    </clipPath>
  </defs>
  <rect x="0" y="0" width="200" height="150" fill="rgba(0,128,0,0.5)" clip-path="url(#intersect)" />
  <circle cx="70" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <circle cx="110" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <text x="45" y="130" font-size="12">A</text>
  <text x="135" y="130" font-size="12">B</text>
  <text x="10" y="20" font-size="14">A ∩ B</text>
</svg>

##### 相对补(差集)
|**定义**|$A - B = \{ x \mid x \in A \land x \notin B \}$|
|-:|:-|
|**子集的差集刻画定理**|$A \subseteq B \iff A - B = \varnothing$|
|*证明*|$\forall x(x \in A \to x \in B)$|
|$\Leftrightarrow$|$\forall x(\lnot(x \in A)\lor x \in B)$|
|$\Leftrightarrow$|$\forall x\lnot(x \in A \land \lnot (x \in B))$|
|$\Leftrightarrow$|$\forall x\lnot(x \in A \land x \not \in B)$|
|$\Leftrightarrow$|$A - B = \varnothing$|
|**交集空与差集不变等价定理**|$A \cap B = \varnothing \iff A - B = A $|
|*证明*|$\forall x \lnot (x \in A \land x \in B)$|
|$\Leftrightarrow$|$\forall x  (\lnot(x \in A) \lor \lnot(x \in B))$|
|$\Leftrightarrow$|$\forall x  ((\lnot(x \in A) \lor (x \in A)) \land (\lnot(x \in A) \lor \lnot(x \in B)))$|
||~~排中律合取单位元构造出可以提公因式的项~~|
|$\Leftrightarrow$|$\forall x  (\lnot (x \in A) \lor((x \in A) \land \lnot(x \in B)))$|
|$\Leftrightarrow$|$\forall x  (x \in A) \to ((x \in A) \land (x \not\in B))$|
|$\Leftrightarrow$|$\forall x  ((x \in A) \to x \not \in B)$|

<svg width="100" height="75" viewBox="0 0 200 150" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="150" fill="#f9f9f9" stroke="#ccc" />
  <defs>
    <clipPath id="A_minus_B">
      <circle cx="70" cy="70" r="50" />
    </clipPath>
    <mask id="maskB">
      <rect x="0" y="0" width="200" height="150" fill="white" />
      <circle cx="110" cy="70" r="50" fill="black" />
    </mask>
  </defs>
  <rect x="0" y="0" width="200" height="150" fill="rgba(255,0,0,0.5)" clip-path="url(#A_minus_B)" mask="url(#maskB)" />
  <circle cx="70" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <circle cx="110" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <text x="45" y="130" font-size="12">A</text>
  <text x="135" y="130" font-size="12">B</text>
  <text x="10" y="20" font-size="14">A − B</text>
</svg>

##### 对称差
|**定义**|$A \oplus B = (A - B) \cup (B - A)$|
|-:|:-|
|另一种定义|$A \oplus B = (A \cup B) - (A \cap B)$|
|证明:|$A \oplus B = (A - B) \cup (B - A) \iff A \oplus B = (A \cup B) - (A \cap B)$|
|*证明*||


<svg width="100" height="75" viewBox="0 0 200 150" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="150" fill="#f9f9f9" stroke="#ccc" />
  <defs>
    <clipPath id="A_circle"><circle cx="70" cy="70" r="50" /></clipPath>
    <clipPath id="B_circle"><circle cx="110" cy="70" r="50" /></clipPath>
    <mask id="mask_B">
      <rect x="0" y="0" width="200" height="150" fill="white" />
      <circle cx="110" cy="70" r="50" fill="black" />
    </mask>
    <mask id="mask_A">
      <rect x="0" y="0" width="200" height="150" fill="white" />
      <circle cx="70" cy="70" r="50" fill="black" />
    </mask>
  </defs>
  <!-- A - B -->
  <rect x="0" y="0" width="200" height="150" fill="rgba(255,0,0,0.5)" clip-path="url(#A_circle)" mask="url(#mask_B)" />
  <!-- B - A -->
  <rect x="0" y="0" width="200" height="150" fill="rgba(0,0,255,0.5)" clip-path="url(#B_circle)" mask="url(#mask_A)" />
  <circle cx="70" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <circle cx="110" cy="70" r="50" fill="none" stroke="black" stroke-width="1.5" />
  <text x="45" y="130" font-size="12">A</text>
  <text x="135" y="130" font-size="12">B</text>
  <text x="10" y="20" font-size="14">A ⊕ B</text>
</svg>

##### 绝对补
|**定义**|$\sim A = E - A$|
|-:|:-|

<svg width="100" height="75" viewBox="0 0 200 150" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="150" fill="#ccc" stroke="black" stroke-width="1.5" />
  <circle cx="90" cy="70" r="50" fill="white" stroke="black" stroke-width="1.5" />
  <text x="65" y="130" font-size="12">A</text>
  <text x="10" y="20" font-size="14">∼A = E − A</text>
</svg>

##### 广义并
|**定义**|设$ A $为一个集族,由$ A $中**全体元素的元素**组成的集合称作$ A $的广义并|
|-:|:-|
||$\cup A = \{ x \mid \exists z \, (z \in A \land x \in z) \}$|
|*规定*|**$\cup \varnothing = \varnothing$**|
|一般情况下可以转变成*初级运算*|$\cup \{A_1, A_2, \dots, A_n\} = A_1 \cup A_2 \cup \dots \cup A_n$|



##### 广义交
|**定义**|设$ A $为一个非空集族，由$ A $中**全体元素的公共元素**组成的集合称作$ A$的广义并|
|-:|:-|
||$\cap A = \{ x \mid \forall z \, (z \in A {\color{red}{\to}} x \in z) \}$|
|*规定*|**$\cap \varnothing$无意义**|
||~~空集$\varnothing$不可以广义交,因为$\cap \varnothing$不是集合,在集合论中无意义~~|
|一般情况下可以转变成*初级运算*|$\cap \{A_1, A_2, \dots, A_n\} = A_1 \cap A_2 \cap \dots \cap A_n$|


##### 运算优先级
|*二类运算*|初级运算$\cup,\cap,-,\oplus$|
|-:|:-|
||优先顺序由**括号**确定|
|*一类运算*|广义运算,幂集,绝对补运算$\sim$|
||运算**由右向左**进行|
|*混合运算*|二类优先于一类|

#### 有穷集的计数
##### 文氏图
##### 包含排斥原理(容斥原理)

|**容斥原理**|设集合 $S$ 上定义了 $n$ 条性质，其中具有第 $i$ 条性质的元素构成子集 $A_i$，那么集合中*不具有任何性质的元素数*为|
|-:|:-|
|$\lvert \overline{A_1} \cap \overline{A_2} \cap \cdots \cap \overline{A_n} \rvert =$|$ \lvert S \rvert - \sum\limits_{i=1}^n \lvert A_i\rvert + \sum\limits_{1 \le i < j \le n} \lvert A_i \cap A_j \rvert - \sum\limits_{1 \le i < j < k \le n} \lvert A_i \cap A_j \cap A_k\rvert + \cdots + {\color{red}{(-1)^n}} \lvert A_1 \cap A_2 \cap \cdots \cap A_n\rvert$|
|*具有一条性质的元素数推论*|S中至少具有一条性质的元素数为|
|$\lvert A_1 \cup A_2 \cup \cdots \cup A_n \rvert =$|$ \sum\limits_{i=1}^n \lvert A_i \rvert - \sum\limits_{1 \le i < j \le n} \lvert A_i \cap A_j \rvert + \sum\limits_{1 \le i < j < k \le n} \lvert A_i \cap A_j \cap A_k \rvert - \cdots + (-1)^{n-1} \lvert A_1 \cap A_2 \cap \cdots \cap A_n \rvert$|
###### 求欧拉函数的值

#### 集合恒等式

> 只涉及一个运算的算律：交换律、结合律、幂等律

|   | *$\cup$* | *$\cap$* | *$\oplus$* |
| :--: | :-- | :-- |:--|
| 1.**交换律** | $A \cup B = B \cup A$ | $A \cap B = B \cap A$ | $A \oplus B = B \oplus A$ |
| 2.**结合律** | $(A \cup B) \cup C = A \cup (B \cup C)$ | $(A \cap B) \cap C = A \cap (B \cap C)$ | $(A \oplus B) \oplus C = A \oplus (B \oplus C)$ |
| 3.**幂等律** | $A \cup A = A$ | $A \cap A = A$ |   |

> 涉及两个不同运算的算律：分配律、吸收律

|4.**分配律** | *$\cup$ 对 $\cap$* | $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$ |
| :--: | :--: | :-- |
| | *$\cap$ 对 $\cup$* | $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$ |
| | *$\cap$ 对 $\oplus$* | $A \cap (B \oplus C) = (A \cap B) \oplus (A \cap C)$ |
|5.**吸收律** | *$\cup$ 与 $\cap$* | $A \cup (A \cap B) = A$，$A \cap (A \cup B) = A$ |

> 涉及补运算的算律：德摩根律、双重否定律

| | *差集 $-$* | *绝对补 $\sim$* |
| :--: | :-- | :-- |
| 7.**德摩根律** | $A - (B \cup C) = (A - B) \cap (A - C)$<br>$A - (B \cap C) = (A - B) \cup (A - C)$ | $\sim(B \cup C) = \sim B \cap \sim C$<br>$\sim(B \cap C) = \sim B \cup \sim C$ |
| 8.**双重否定律** | | $\sim\sim A = A$ |

> 涉及全集和空集的算律：补元律、零律、同一律、否定律

|  | *空集 $\varnothing$* | *全集 $E$* |
| :--: | :-- | :-- |
| 9.**补元律** | $A \cap \sim A = \varnothing$ | $A \cup \sim A = E$ |
| 10.**零律** | $A \cap \varnothing = \varnothing$ | $A \cup E = E$ |
| 11.**同一律** | $A \cup \varnothing = A$ | $A \cap E = A$ |
| 12.**否定** | $\sim\varnothing = E$ | $\sim E = \varnothing$ |

##### 集合证明题


### 二元关系
#### 有序对
|**定义**|由两个元素$x$和$y$,按照一定的顺序组成的二元组称为有序对,记作$<x,y>$|
|-:|:-|

|**性质**|*有序性*|$<x, y> \neq <y, x>$(当 $x \neq y$ 时)|
|-:|-|-|
||*唯一性*|$<x, y>$ 与 $<u, v>$ 相等的充要条件是$<x, y >= <u, v>\iff x = u \land y = v.$|


#### 笛卡尔积
|**定义**|设 $A, B$ 为集合，$A$ 与 $B$ 的笛卡儿积记作 $A \times B$|
|-:|:-|
|| 且 *$A \times B = \{ <x, y> \mid x \in A \land y \in B \}$*|

##### 笛卡尔积的性质

|1.**空集性质**|若 $A$ 或 $B$ 中有一个为空集，则 $A \times B$ 就是空集。|
|-:|:-|  
||$A \times \varnothing = \varnothing \times B = \varnothing$|
|2.**不满足交换律**|$A \times B \neq B \times A$ （当 $A \neq B$，$A \neq \varnothing$，$B \neq \varnothing$ 时）|
|3.**不满足结合律**  |$(A \times B) \times C \neq A \times (B \times C) $（$A \neq \varnothing$，$B \neq \varnothing$，$C \neq \varnothing$）|
|4.**分配律**(对*并*、*交*)|$A \times (B \cup C) = (A \times B) \cup (A \times C)$,$(B \cup C) \times A = (B \times A) \cup (C \times A)$|
||$A \times (B \cap C) = (A \times B) \cap (A \times C)$,$(B \cap C) \times A = (B \times A) \cap (C \times A)$|
|*证明*||
|5.**计数性质**|若 $\lvert A \rvert = m$，$\lvert B \rvert = n$，则 $\lvert A \times B \rvert = mn$|
|*证明*||
|6.**子集关系的保持性**|若 $A \subseteq C$ 且 $B \subseteq D$，则 $A \times B \subseteq C \times D$|
|即|$A \subseteq C \land B \subseteq D \Rightarrow A \times B \subseteq C \times D$|
||~~逆命题不成立~~|
|*证明*||

#### 二元关系的定义
|**定义**|如果一个集合满足以下条件*之一*:|
|-:|:-|
|1.|集合非空，且它的*元素都是有序对*|
|2.|集合是空集|
||则称该集合为一个二元关系，简称关系，记作 $R$|
||如果 $<x, y> \in R$，可记作 $x R y$|
||如果 $<x, y> \notin R$，则记作 $x\cancel R y$|

##### $A$到$B$的关系及$A$上的关系
|**定义**|设 $A, B$ 为集合，$A \times B$ 的任何子集所定义的二元关系叫做从 $A$ 到 $B$ 的二元关系|
|-:|:-|
|特别地,|当 $A = B$ 时则叫做 $A$ 上的二元关系|
|*二元关系的计数*|$\lvert A\rvert =n$,则$\lvert A \times A\rvert =n^2$ ~~有序对的计数性质~~|
||所以$A$ 上有 $2^{n^2}$ 个不同的二元关系|
||~~子集的计数性质~~|

###### $A$上重要的关系
|**空关系**|$\varnothing$ ~~对于任何集合 $A$，空集 $\varnothing$ 是 $A \times A$ 的子集~~|
|-:|:-|
|**全域关系**| $E_A = \{< x, y> \mid x \in A \land y \in A\} = A \times A$|
|**恒等关系**|$I_A = \{< x, x> \mid x \in A\}$|
|**小于等于关系**|$L_A = \{< x, y> \mid x, y \in A \land x \leq y\}$，$A$ 为实数子集|
|整除关系|$D_A = \{< x, y> \mid x, y \in A \land x$整除$y\}$，$A$ 为非0整数子集|
|包含关系|$R_\subseteq = \{< x, y> \mid x, y \in A \land x \subseteq y\}$，$A$ 是集合族|

#### 关系的数学表示
##### 关系矩阵
> 若 $A = \{x_1, x_2, \dots, x_m\}$，$B = \{y_1, y_2, \dots, y_n\}$，$R$ 是从 $A$ 到 $B$ 的关系，$R$ 的**关系矩阵**是布尔矩阵 $M_R = [r_{ij}]_{m \times n}$，其中  
> $r_{ij} = 1 \iff <x_i, y_j> \in R$

关系矩阵适合表示从$ A $到$ B $的关系或$ A $上的关系 ($A,B$为有穷集)
##### 关系图
> 若 $A = \{x_1, x_2, \dots, x_m\}$，$R$ 是 $A$ 上的关系，$R$ 的**关系图**是$G_R = <A, R>$  
> 其中 $A$ 为结点集，$R$ 为边集。如果 $< x_i, x_j> \in R$，在图中就有一条从 $x_i$ 到 $x_j$ 的有向边

关系图适合表示有穷集$ A $上的关系

#### 关系的运算
| **定义域** | ${\color{blue}{\operatorname{dom}}}R$ | $\operatorname{dom}R = \{ x \mid \exists y ( <x,y> \in R ) \}$ |
| --- | --- | --- |
| **值域** | ${\color{blue}{\operatorname{ran}}}R$ | $\operatorname{ran}R = \{ y \mid \exists x ( <x,y> \in R ) \}$ |
| **域** | ${\color{blue}{\operatorname{fld}}}R$ | $\operatorname{fld}R = \operatorname{dom}R \cup \operatorname{ran}R$ |
| **逆运算** | $R^{\color{blue}{-1}}$ | $R^{-1} = \{ <y,x> \mid <x,y> \in R \}$ |
| **合成运算** | $R {\color{blue}{\circ}} S$ | $R \circ S = \{ <x,z> \mid \exists y ( <x,y> \in R \land <y,z> \in S ) \}$ |
| **限制** | $R {\color{blue}{\upharpoonright}}A$ | $R \upharpoonright A = \{ <x,y> \mid xRy \land x \in A \}$ |
|||显然,$R\upharpoonright A$是$R$上的子关系,即$\color{blue}{R \upharpoonright A \subseteq R}$|
| **像** | $R[A]$ | $R[A] = \operatorname{ran}(R \upharpoonright A)$ |
|||显然,$R[A]$是$ \operatorname{ran}R$的子集,即$\color{blue}{R[A] \subseteq \operatorname{ran}R}$|

##### 基本运算的性质
|**逆运算的基本性质定理**|设 $F$ 是任意的关系，则|
|-:|:-|
|1.*逆运算的对合性*|$(F^{-1})^{-1} = F$|
|证明:||
|2.*逆运算交换定义域与值域*|$\operatorname{dom}F^{-1} = \operatorname{ran}F$，$\operatorname{ran}F^{-1} = \operatorname{dom}F$|
|证明:||

|**关系的合成运算性质定理**|设 $F, G, H$ 是任意的关系,则|
|-:|:-|
|1.*合成运算的结合律*|$(F \circ G) \circ H = F \circ (G \circ H)$|
|证明:||
|2.*逆运算与合成的交换次序*|$(F \circ G)^{-1} = G^{-1} \circ F^{-1}$|
|证明:||

|**恒等关系的单位元性质**|设 $R$ 为 $A$ 上的关系，则|
|-:|:-|
||$R \circ I_A = I_A \circ R = R $ ~~恒等关系是合成运算的单位元~~|
|证明:||


|**合成运算对并、交的分配律**|设 $F, G, H$ 为任意关系，则|
|-:|:-|
|1.|$F \circ (G \cup H) = (F \circ G) \cup (F \circ H)$|
|证明:||
|推广到有限个|$R \circ (R_1 \cup R_2 \cup \cdots \cup R_n) = (R \circ R_1) \cup (R \circ R_2) \cup \cdots \cup (R \circ R_n)$|
|证明:||
|2.|$(G \cup H) \circ F = (G \circ F) \cup (H \circ F)$|
|证明:||
|推广到有限个|$(R_1 \cup R_2 \cup \cdots \cup R_n) \circ R = (R_1 \circ R) \cup (R_2 \circ R) \cup \cdots \cup (R_n \circ R)$|
|证明:||
|3.|$F \circ (G \cap H) {\color{red}{\subseteq}} (F \circ G) \cap (F \circ H)$|
|证明:||
|推广到有限个|$R \circ (R_1 \cap R_2 \cap \cdots \cap R_n) {\color{red}{\subseteq}} (R \circ R_1) \cap (R \circ R_2) \cap \cdots \cap (R \circ R_n)$|
|证明:||
|4.|$(G \cap H) \circ F {\color{red}{\subseteq}} (G \circ F) \cap (H \circ F)$|
|证明:||
|推广到有限个|$(R_1 \cap R_2 \cap \cdots \cap R_n) \circ R {\color{red}{\subseteq}} (R_1 \circ R) \cap (R_2 \circ R) \cap \cdots \cap (R_n \circ R)$|
|证明:||

|**限制与像对集合运算的分配律**|设 $F$ 为关系，$A, B$ 为集合，则|
|-:|:-|
|1.*限制运算对并的分配律*|$F \upharpoonright (A \cup B) = (F \upharpoonright A) \cup (F \upharpoonright B)$|
|证明:||
|2.*像运算对并的分配律*|$F[A \cup B] = F[A] \cup F[B]$|
|证明:||
|3.*限制运算对交的分配律*|$F \upharpoonright (A \cap B) = (F \upharpoonright A) \cap (F \upharpoonright B)$|
|证明:||
|4.*像运算对交的包含关系*|$F[A \cap B] \subseteq F[A] {\color{red}{\cap}} F[B]$|
|证明:||
##### 关系的幂运算
> ~~在右复合运算的基础上定义~~

|**定义**|设 $R$ 为 $A$ 上的关系，$n$ 为自然数，则 $R$ 的 $n$ 次幂定义为|
|-:|:-|
|1.|$R^0 = { <x,x> \mid x \in A } = I_A$|
|2.|$R^{n+1} = R^n \circ R$|
|*由定义可知*|对 $A$ 上任何关系 $R_1, R_2$，有 $R_1^0 = R_2^0 = I_A$，即任何关系的 0 次幂都等于 $A$ 上的恒等关系.|
||对 $A$ 上任何关系 $R$，有 $R^1 = R^0 \circ R = I_A \circ R = R$，即 1 次幂等于自身.|

###### 幂的求法
|集合表达式求|通过 $n-1$ 次右复合 $R^{n} = R^{n-1} \circ R$ 计算|
|-|-|
|关系矩阵求|$R^n$ 的矩阵为 $M^n$,其中矩阵乘法中加法为逻辑加|
||${\color{red}{1+1=1}},1+0=0,0+1=1,0+0=0$|
|关系图求|如果 $R$ 是用关系图 $G$ 给出的，那么可以直接由图 $G$ 得到 $R^n$ 的关系图 $G^n$:|
||$G^n$ 的顶点集与 $G$ 相同；|
||考察 $G$ 的每个顶点 $x_i$，若在 $G$ 中从 $x_i$ 出发经过 $n$ 步长的路径到达顶点 $x_j$，则在 $G^n$ 中加一条从 $x_i$ 到 $x_j$ 的边。在把所有这样的边都找到以后，就得到图 $G^n$|

###### 幂的性质
|**关系幂的周期性定理**|设 $A$ 为 $n$ 元集，$R$ 是 $A$ 上的关系，则|
|-:|:-|
||*存在*自然数 $s$ 和 $t$（$s < t$）使得 **$R^s = R^t$**|
|证明||



|**关系幂的指数法则**|设 $R$ 是 $A$ 上的关系，$m, n \in \mathbb{N}$，则|
|-:|:-|
|1.*指数加法*|$R^m \circ R^n = R^{m+n}$|
|证明||
|2.*指数乘法*|$(R^m)^n = R^{mn}$|
|证明||



|**关系幂的周期性定理**|设 $R$ 是 $A$ 上的关系|
|-:|:-|
||若存在自然数 $s, t$（$s < t$）使得 $R^s = R^t$，则|
|1.*指数平移不变性*|对任何 $k \in \mathbb{N}$ 有 $R^{s+k} = R^{t+k}$|
|证明||
|2.*指数模周期性*|对任何 $k, i \in \mathbb{N}$ 有 $R^{s+kp+i} = R^{s+i}$，其中 $p = t - s$|
|证明||
|3.*幂的有限封闭性*|$S = \{R^0, R^1, \dots, R^{t-1}\}$，则对于任意的 $q \in \mathbb{N}$ 有 $R^q \in S$|
|证明||





#### 关系的性质
##### 自反、反自反
|**定义**|设 $R$ 为 $A$ 上的关系,|
|-:|:-|
||若 $\forall x (x \in A \to <x,x> \in R)$，则称 $R$ 在 $A$ 上是自反的|
||若 $\forall x (x \in A \to <x,x> \notin R)$，则称 $R$ 在 $A$ 上是反自反的|

|*实例*||
|-:|:-|
|全域关系 $E_A$|自反|
|恒等关系 $I_A$|自反|
|小于等于关系 $L_A$|自反|
|整除关系 $D_A$|自反|
|实数集上的小于关系|反自反|
|幂集上的真包含关系|反自反|

##### 对称、反对称
|**定义**|设 $R$ 为 $A$ 上的关系,|
|-:|:-|
||若 $\forall x \forall y (x, y \in A \land <x, y> \in R {\color{red}{\rightarrow}} <y, x> \in R)$，则称 $R$ 为 $A$ 上对称的关系|
||若 $\forall x \forall y (x, y \in A \land <x, y> \in R \land <y, x> \in R {\color{red}{\rightarrow}} x = y)$，则称 $R$ 为 $A$ 上的反对称关系|
||~~前件若为*假*,则该命题恒*真*~~|

|*实例*||
|-:|:-|
|全域关系 $E_A$|对称|
|恒等关系 $I_A$|对称且反对称|
|空关系 $\varnothing$|对称且反对称|

##### 传递关系
|**定义**|设 $R$ 为 $A$ 上的关系，若|
|-:|:-|
||$\forall x \forall y \forall z (x, y, z \in A \land <x, y> \in R \land <y, z> \in R \rightarrow <x, z> \in R)$|
||则称 $R$ 是 $A$ 上的传递关系|

|*实例*|$E_A$(全域关系)、$I_A$(恒等关系)、$L_A$(小于等于关系)、$D_A$(整除关系)、实数集上的小于关系、幂集上的真包含关系：都是传递关系|
|-:|:-|

##### 关系性质反映在关系矩阵和关系图上
|性质|集合表达式|关系矩阵|关系图|
|-|-|-|-|
|自反| $I_A \subseteq R$| 主对角线元素全为 $1$| 每个顶点都有自环|
|反自反| $R \cap I_A = \varnothing$ | 主对角线元素全为 $0$| 每个顶点都没有自环|
| 对称 | $R = R^{-1}$| 矩阵关于主对角线对称| 若两顶点间有边，则必为双向边|
| 反对称 | $R \cap R^{-1} \subseteq I_A$ | 对 $i \neq j$，$r_{ij}$ 与 $r_{ji}$ 不同时为 $1$ | 若两顶点间有边，则最多只有一条有向边 |
| 传递   | $R \circ R \subseteq R$| 若 $M^2$ 中某位置为 $1$，则 $M$ 中对应位置也为 $1$ | 若 $x_i \to x_j$ 且 $x_j \to x_k$，则 $x_i \to x_k$ |

##### 关系性质成立的充要条件
|**关系性质的等价刻画**|设 $R$ 为 $A$ 上的关系，则|
|-:|:-|
|1.*自反的包含刻画*|$R$ 在 $A$ 上自反 $\iff I_A \subseteq R$|
|证明:||
|2.*反自反的交集为空刻画*|$R$ 反自反 $\iff R \cap I_A = \varnothing$|
|证明:||
|3.*对称的逆等刻画*|$R$ 对称 $\iff R = R^{-1}$|
|证明:||
|4.*反对称的与逆交含于恒等刻画*|$R$ 反对称 $\iff R \cap R^{-1} \subseteq I_A$|
|证明:||
|5.*传递的复合刻画*|$R$ 传递 $\iff R \circ R \subseteq R$|
|证明:||



#### 关系的闭包
~~关系的闭包就是给原关系*添加最少*的有序对，使其*扩充*为满足自反性、对称性或传递性的新关系~~

|**定义**|设 $R$ 是非空集合 $A$ 上的关系,$R$ 的闭包是 $A$ 上的关系 $R'$，使得 $R'$ 满足以下条件|
|-:|:-|
||1. $R'$ 是自反(对称/传递)的|
||2. $R \subseteq R'$;~~扩充原关系~~|
||3. 对 $A$ 上任何包含 $R$ 的自反(对称/传递)关系 $R''$，都有 $R' \subseteq R''$ ~~确保最小(添加最少)~~|

##### 构造闭包
||设$R$为$A$上的关系,则有|
|-:|:-|
|**构造自反闭包**|$r(R) = R \cup R^0 = R \cup I_A$|
|*证明*||
|**构造对称闭包**|$s(R) = R \cup R^{-1}$ |
|*证明*||
|**构造传递闭包**|$t(R) = R \cup R^2 \cup R^3 \cup \dots$|
|*证明*||
|||

|**有限幂次构造推论**|设 $R$ 是有穷集 $A$ 上的关系，则存在正整数 $r$ 使得|
|-:|:-|
||$t(R) = R \cup R^2 \cup R^3 \cup \dots \cup R^r$|
||~~有穷集上的关系幂次会重复(周期性)，因此传递闭包只需取到某个幂次~~|
|*证明*||

##### 构造闭包的关系矩阵表示
 
||设关系 $R$, $r(R)$, $s(R)$, $t(R)$ 的关系矩阵分别为 $M, M_r, M_s$ 和 $M_t$,则|
|-:|:-|
|**自反闭包**|$M_r = M + E$|
||~~自反闭包矩阵=原矩阵+单位矩阵(主对角线元素置为1),加法为逻辑加~~|
|**对称闭包**|$M_s = M + M'$|
||~~对称闭包矩阵=原矩阵+其转置矩阵,使矩阵对称~~|
|**传递闭包**|$M_t = M + M^2 + M^3 + \dots$|
||~~传递闭包矩阵=所有正幂次矩阵的逻辑加.对有限集,求和到某个幂次即可~~|

##### 构造闭包的关系图表示
||设关系 $R, r(R), s(R), t(R)$ 的关系图分别记为 $G, G_r, G_s, G_t$,则 $G_r, G_s, G_t$ 的顶点集与 $G$ 的顶点集相等.除了$G$的边以外,以下述方法添加新的边:|
|-:|:-|
|**自反闭包**|考察 $G$ 的每个顶点,若没环就加一个环,得到 $G_r$|
||~~保证每个顶点有自环~~|
|**对称闭包**|考察 $G$ 的每条边,若有一条 $x_i$ 到 $x_j$ 的单向边,$i \neq j$,则在 $G$ 中加一条 $x_j$ 到 $x_i$ 的反向边,得到 $G_s$|
||~~使所有边成为双向~~|
|**传递闭包**|考察 $G$ 的每个顶点 $x_i$,找 $x_i$ 可达的所有顶点 $x_j$（允许 $i = j$）,如果没有从 $x_i$ 到 $x_j$ 的边,就加上这条边,得到图 $G_t$|
||~~将任意长度路径的端点直接连边~~|

##### 闭包的性质
|**闭包特征定理**|设 $R$ 是非空集合 $A$ 上的关系,则|
|-:|:-|
||1. $R$ 是自反的 $\iff$ $r(R) = R$|
|*证明*||
||2. $R$ 是对称的 $\iff$ $s(R) = R$|
|*证明*||
||3. $R$ 是传递的 $\iff$ $t(R) = R$|
|*证明*||

|**闭包有序性定理**|设 $R$ 是非空集合 $A$ 上的关系,则|
|-:|:-|
||~~自反/对称/传递闭包运算都保持子集关系，即若原关系包含，则其闭包也包含~~|
||1. $r(R_1) \subseteq r(R_2)$|
|*证明*||
||2. $s(R_1) \subseteq s(R_2)$|
|*证明*||
||3. $t(R_1) \subseteq t(R_2)$|
|*证明*||

|**闭包性质保持定理**|设 $R$ 是非空集合 $A$ 上的关系,则|
|-:|:-|
||~~自反/对称/传递闭包运算都保持子集关系，即若原关系包含，则其闭包也包含~~|
||1.若 $R$ 是自反的，则 $s(R)$ 与 $t(R)$ 也是自反的|
||~~若$ R $是自反或对称的，则三种闭包后仍保持自反或对称~~|
|*证明*||
||2.若 $R$ 是对称的，则 $r(R)$ 与 $t(R)$ 也是对称的|
|*证明*||
||3.若 $R$ 是传递的，则 $r(R)$ 是传递的 ~~$s(R)$不一定传递,即只有自反闭包保持传递性~~|
|*证明*||
|||
|||
|*多次闭包运算*|如果需要进行多个闭包运算,比如求R的自反、对称、传递的闭包$tsr(R)$,为了尽量不失去传递性(~~构造传递闭包时只有自反闭包保持传递性~~),运算顺序:|
||$tsr(R) = t(s(r(R)))$|
|||

#### 等价关系
~~等价关系刻画了集合中元素的一种“等同”概念.如同“等于”关系一样:每个元素都和自己等同(自反);若甲等同乙,则乙等同甲(对称);若甲等同乙且乙等同丙,则甲等同丙(传递)~~

|**定义**|设 $R$ 是非空集合 $A$ 上的关系,如果 $R$ 是**自反的**、**对称的**和**传递的**,则称 $R$ 是 $A$ 上的**等价关系**|
|-:|:-|
||设 $R$ 是一个等价关系,若 $<x, y> \in R$,称 $x$ *等价于* $y$,记作 $x \sim y$|

##### 等价类

~~等价类是将集合 $A$ 中所有相互等价的元素归为一组形成的子集~~

|**定义**|设 $R$ 为非空集合 $A$ 上的等价关系,$\forall x \in A$,令|
|-:|:-|
||$[x]_R = \{ y \mid y \in A \land xRy \}$|
||称 $[x]_R$ 为 $x$ 关于 $R$ 的等价类,简称为 $x$ 的等价类,简记为 $[x]$|


##### 等价类的性质
|**等价类划分定理**|设 $R$ 是非空集合 $A$ 上的等价关系, 则|
|-:|:-|
|1. *非空性*|$\forall x \in A$, $[x]$ 是 $A$ 的非空子集.|
|证明:||
|2. *相等性*|$\forall x, y \in A$, 如果 $x R y$, 则 $[x] = [y]$|
|证明:||
|3. *不相交性*|$\forall x, y \in A$, 如果 $x \cancel R y$, 则 $[x] \cap [y] = \varnothing$.|
|证明:||
|4. *覆盖性*|$\bigcup \{ [x] \mid x \in A \} = A$, 即所有等价类的并集就是 $A$.|
|证明:||

> ~~等价关系将集合划分成互不相交的等价类, 每个类非空, 且所有类的并集为整个集合.~~


##### 商集
|**定义**|设 $R$ 为非空集合 $A$ 上的等价关系, 以 $R$ 的所有等价类作为元素的集合称为 $A$ 关于 $R$ 的**商集**, 记做 $A/R$,|
|-:|:-|
||$A/R = \{ [x]_R \mid x \in A \}$.|
||~~商集是等价类的集合~~|

##### 集合的划分
|**定义**|设 $A$ 为非空集合, 若 $A$ 的子集族 $\pi \subseteq P(A)$ 满足下面条件:|
|-:|:-|
|1. *非空*|$\varnothing \notin \pi$|
|2. *不相交*|$\forall x \forall y (x, y \in \pi \land x \neq y \rightarrow x \cap y = \varnothing)$|
|3. *并集为整个集合*|$\cup \pi = A$|
||则称 $\pi$ 是 $A$ 的一个**划分**, 称 $\pi$ 中的元素为 $A$ 的**划分块**.|

##### 等价关系与划分的一一对应
> 比较商集 $A/R$ 和划分的定义可知, *商集就是 $A$ 的一个划分*, 且不同的商集对应不同的划分.
> 反之, 给定 $A$ 的一个划分 $\pi$, 定义 $A$ 上的关系 $R$ 为  
> $R = \{ <x, y> \mid x, y \in A, x \text{与} y \text{在} \pi \text{的同一划分块中} \}$,
> 则可以证明 $R$ 是 $A$ 上的等价关系, 且该等价关系所确定的商集就是 $\pi$.
> 因此, $A$ 上的等价关系与 $A$ 的划分之间存在着**一一对应**的关系.

#### 偏序关系
|**定义**|非空集合 $A$ 上的*自反、反对称和传递*的关系, 称为 $A$ 上的**偏序关系**|
|-:|:-|
||记作 $\preceq$|
||如果 $<x, y> \in \preceq$, 则记作 $x \preceq y$|
|*举例*|恒等关系 $I_A$|
||实数集上的小于等于关系|
||正整数集上的整除关系|
||集合族上的包含关系|

##### 可比
|**定义**|设 $R$ 为非空集合 $A$ 上的偏序关系 (记作 $\preceq$),|
|-:|:-|
||(1) $x \prec y$,如果 $x \preceq y$ 且 $x \neq y$ ~~定义严格小于~~|
||(2) $x$ 与 $y$ 是 $\preceq$ 可比的,如果 $x \preceq y$ 或 $y \preceq x$|

||由以上两个定义可知,在具有偏序关系 $\preceq$ 的集合 $A$ 中任取两个元素 $x$ 和 $y$|
|-:|:-|
||可能有下列几种情况发生|
||1.$x \prec y$ (或 $y \prec x$)|
||2.$x = y$|
||3.$x$ 与 $y$ 不是可比的|

##### 全序关系(线序关系)
|**定义**|设 $R$ 为非空集合 $A$ 上的偏序关系 (记作 $\preceq$),|
|-:|:-|
||若 $\forall x, y \in A$, $x$ 与 $y$ 都是可比的, 则称 $R$ 为**全序关系**|
|*实例*|数集上的小于等于关系是全序关系.  
||整除关系不是正整数集合上的全序关系 (例如 2 和 3 不可比).|
||~~全序关系要求集合中任意两个元素都能比较大小,~~|
||~~而偏序允许存在不可比较的元素.~~|
||~~即偏序关系 $>$ 全序关系~~|



##### 偏序集
|**定义**|集合 $A$ 和 $A$ 上的偏序关系 $\preceq$ 一起叫做**偏序集**, 记作 $<A, \preceq>$.|
|-:|:-|
|*实例*|整数集和小于等于关系构成偏序集 $<\mathbb{Z}, \le>$| 
||幂集 $P(A)$ 和包含关系构成偏序集 $<P(A), \subseteq>$|

##### 覆盖
|**定义**|设 $R$ 为非空集合 $A$ 上的偏序关系 (记作 $\preceq$), $x, y \in A$,|
|-:|:-|
||如果 $x \prec y$ (即 $x \preceq y$ 且 $x \neq y$) 且不存在 $z \in A$ 使得 $x \prec z \prec y$, 则称 $y$ **覆盖** $x$.|
||~~覆盖关系描述了偏序集中*紧邻*的上下关系~~|

##### 哈斯图 
||哈斯图是利用偏序关系的自反、反对称、传递性简化后的关系图.|
|-:|:-|
|**特点**|1. 每个结点没有自环 (省略自反性带来的环).|
||2. 两个连通的结点之间的序关系通过结点位置的高低表示: |
||&nbsp;位置低的元素顺序在前 (即 $x \preceq y$ 时 $x$ 在 $y$ 下方).|
||3. 仅当 $y$ 覆盖 $x$ 时, 才在 $x$ 与 $y$ 之间连边.|
||~~哈斯图省略了所有由自反和传递性产生的边, 只保留覆盖关系, 从而清晰展示偏序集的结构.~~|

##### 最元和极元
|**定义**|设 $<A, \preceq>$ 为偏序集, $B \subseteq A$, **$y \in B$**.|
|-:|:-|
|*最小元*|若 $\forall x (x \in B \rightarrow y \preceq x)$ 成立, 则称 $y$ 为 $B$ 的最小元.|
|*最大元*|若 $\forall x (x \in B \rightarrow x \preceq y)$ 成立, 则称 $y$ 为 $B$ 的最大元.|
||~~最小元和最大元要求与所有元素可比且小于(或大于)所有元素,*可以不存在,存在时唯一*~~|
|*极小元*|若 $\forall x (x \in B \land x \preceq y \rightarrow x = y)$ 成立, 则称 $y$ 为 $B$ 的极小元.|
|*极大元*|若 $\forall x (x \in B \land y \preceq x \rightarrow x = y)$ 成立, 则称 $y$ 为 $B$ 的极大元.|
||~~极小元和极大元只要求没有更小(或更大)的元素, 可以有多个, 且不必与所有元素可比~~|

> 最小元一定是极小元; 最大元一定是极大元.
> 在哈斯图上,孤立结点既是极小元, 也是极大元.


##### 上下界
|**定义**|设 $<A, \preceq>$ 为偏序集, $B \subseteq A$, **$y \in A$**.|
|-:|:-|
|*上界*|若 $\forall x (x \in B \rightarrow x \preceq y)$ 成立, 则称 $y$ 为 $B$ 的上界.
|*下界*|若 $\forall x (x \in B \rightarrow y \preceq x)$ 成立, 则称 $y$ 为 $B$ 的下界.
|*最小上界 (上确界)*|令 $C = \{ y \mid y \text{ 为 } B \text{ 的上界} \}$, 则称 $C$ 的最小元为 $B$ 的最小上界|
|*最大下界 (下确界)*|令 $D = \{ y \mid y \text{ 为 } B \text{ 的下界} \}$, 则称 $D$ 的最大元为 $B$ 的最大下界|
||下界、上界、下确界、上确界*不一定存在*.|
||下界、上界存在时不一定唯一.|
||下确界、上确界如果存在, 则唯一.|
|与最元的关系|集合的最小元就是它的下确界, 最大元就是它的上确界; 反之不对.|

###### 求最大上界(上确界)/最小下界(下确界)的运算符
|$x{\color{red}{\lor}} y$|$\{x,y\}的最小上界(**上**确界)$|
|-:|:-|
|$x{\color{red}{\land}} y$|$\{x,y\}的最大下界(**下**确界)$|

## 代数结构
### 代数系统
#### 二元运算
##### 二元运算相关定义
|**定义**|设S为集合, 函数 $f: S \times S \to S$ 称为S上的**二元运算**|
|-:|:-|
|*注意*|1.S中任何两个元素都可以进行运算, 且运算的结果惟一.|
||2.S中任何两个元素的运算结果都属于S, 即S对该运算封闭.|
||~~即二元运算要求集合对运算封闭且结果唯一~~|
###### 一元运算
|**定义**|设S为集合, 函数 $f: S \to S$ 称为S上的**一元运算**|
|-:|:-|

##### 算符
> 可以用 $\circ, *, \cdot, \oplus, \otimes, \Delta$ 等符号表示二元或一元运算, 称为*算符*.  
> 对二元运算 $\circ$, 如果 $x$ 与 $y$ 运算得到 $z$, 记做 $x \circ y = z$.  
> 对一元运算 $\Delta$, $x$ 的运算结果记作 $\Delta x$.



##### 二元与一元运算的表示
|*解析公式*|用数学表达式直接定义运算结果|
|-:|:-|
|*运算表*|通常用于有限集合，逐条列出所有元素对的结果|

##### 二元运算的性质
###### 只涉及一个二元运算的性质
设 $\circ$ 为 $S$ 上的二元运算,
|**交换律**|若对任意 $x, y \in S$ 有 *$x \circ y = y \circ x$*, 则称运算在 $S$ 上满足交换律|
|-:|:-|
|**结合律**|若对任意 $x, y, z \in S$ 有 *$(x \circ y) \circ z = x \circ (y \circ z)$*, 则称运算在 $S$ 上满足 结合律|
|**幂等律**|若对任意 $x \in S$ 有 *$x \circ x = x$*, 则称运算在 $S$ 上满足幂等律|
||*幂等元*:如果 $S$ 中的某些 $x$ 满足 *$x \circ x = x$*, 则称 $x$ 为运算 $\circ$ 的幂等元|
||显然,如果 $S$ 上的二元运算满足幂等律, 那么 $S$ 中的所有元素都是幂等元|

###### 涉及两个二元运算的性质
|**分配律**|设 $\circ$ 和 $*$ 是 $S$ 上的两个二元运算, 如果对任意的 $x, y, z \in S$ 有|
|-:|:-|
||$x * (y \circ z) = (x * y) \circ (x * z)$,   (左分配律)|
||$(y \circ z) * x = (y * x) \circ (z * x)$,   (右分配律)|
||那么称运算 $*$ 对 $\circ$ 是可分配的, 或者说 $*$ 对 $\circ$ 满足分配律.|
|*广义分配律推广*|若 $*$ 对 $\circ$ 运算分配律成立, 则 $*$ 对 $\circ$ 运算广义分配律也成立|
||即 $\forall x, y_1, y_2, \cdots, y_n \in S$ 有|
||$x * (y_1 \circ y_2 \circ \cdots \circ y_n) = (x * y_1) \circ (x * y_2) \circ \cdots \circ (x * y_n)$,|
||$(y_1 \circ y_2 \circ \cdots \circ y_n) * x = (y_1 * x) \circ (y_2 * x) \circ \cdots \circ (y_n * x)$成立|
|证明:||

~~讲到分配律时应该指明哪个运算对哪个运算可分配, 不要笼统地讲它们满足分配律.因为往往是一个运算对另一个运算可分配, 但反之不对.~~

|**吸收律**|设 $\circ$ 和 $*$ 是 $S$ 上两个可交换的二元运算, 如果对于任意的 $x, y \in S$ 都有|
|-:|:-|
||$x * (x \circ y) = x$,|
||$x \circ (x * y) = x$,|
||那么称 $\circ$ 和 $*$ 满足吸收律.|

~~强调两个运算可交换是因为吸收律通常出现在格等代数结构中, 其中交和并运算本身满足交换律. 若运算不可交换, 则吸收律的表述需区分左右, 但这里为简化而假设可交换.~~

###### 有关二元运算的特异元素
|**单位元**|设 $\circ$ 为 $S$ 上的二元运算, 如果存在 $e_l \in S$ (或 $e_r \in S$), 使得对任何 $x \in S$ 都有|
|-:|:-|
||$e_l \circ x = x$ (或 $x \circ e_r = x$),|
||那么称 $e_l$ (或 $e_r$) 是 $S$ 中关于 $\circ$ 运算的一个**左单位元**(或**右单位元**).|
||若 $e$ 关于 $\circ$ 运算*既是左单位元又是右单位元*, 则称 $e$ 为 $S$ 上关于 $\circ$ 运算的**单位元**.|



|**单位元唯一性定理**|设 $\circ$ 为 $S$ 上的二元运算, $e_l$ 和 $e_r$ 分别为 $\circ$ 运算的左单位元和右单位元, 则有|
|-:|:-|
||$e_l = e_r = e$,|
||且 $e$ 为 $S$ 上关于 $\circ$ 运算唯一的单位元.|
||~~左单位元和右单位元若同时存在则必然相等, 且成为唯一的单位元~~|
|*证明*||

|**零元**|设 $\circ$ 为 $S$ 上的二元运算, 若存在元素 $\theta_l \in S$ (或 $\theta_r \in S$), 使得对于任意的 $x \in S$ 有|
|-:|:-|
||$\theta_l \circ x = \theta_l$ (或 $x \circ \theta_r = \theta_r$), |
||则称 $\theta_l$ (或 $\theta_r$) 是 $S$ 上关于 $\circ$ 运算的**左零元**(或**右零元**).|
||若 $\theta \in S$ 关于 $\circ$ 运算*既是左零元又是右零元*, 则称 $\theta$ 为 $S$ 上关于 $\circ$ 运算的**零元**|



|**零元唯一性定理**|设 $\circ$ 为 $S$ 上的二元运算, $\theta_l$ 和 $\theta_r$ 分别为 $\circ$ 运算的左零元和右零元, 则有| 
|-:|:-|
||$\theta_l = \theta_r = \theta$,|
||且 $\theta$ 是 $S$ 上关于 $\circ$ 运算的唯一的零元.|
||则称 $\theta_l$ (或 $\theta_r$) 是 $S$ 上关于 $\circ$ 运算的**左零元**(或**右零元**).|
|*证明*||

|**单位元与零元的区分定理**|设 $\circ$ 为 $S$ 上的二元运算, $e$ 和 $\theta$ 分别为 $\circ$ 运算的单位元和零元.|
|-:|:-|
||如果 $S$ 至少有两个元素, 那么 $e \neq \theta$.|
||~~若集合元素个数大于1, 则单位元不能等于零元, 否则会导致所有元素相等, 矛盾.~~|
|*证明*||

#### 代数系统相关概念
##### 代数系统的成分与表示
|**定义**|非空集合$S$和$S$上$k$个一元或二元运算 $f_1, f_2, \dots, f_k$ 组成的系统|
|-:|:-|
||称为**代数系统**, 简称代数, 记做 $<S, f_1, f_2, \dots, f_k>$.|
||**代数常数**是代数系统中具有特殊身份的元素(如单位元、零元), 它们与运算一起构成系统的特征.|
||有时为了强调某个代数系统是含有代数常数的系统, 也可以把这些代数常数列到系统的表达式中. |
||如$<\mathbb{Z}, +, 0>, <P(S), \cup, \cap, \sim, \varnothing, S>$|


~~代数系统是抽象代数的基本研究对象, 例如格、半群、群、环、域等都是带有特定运算的代数系统.~~

||*构成代数系统的成分*|
|-:|:-|
|1.|集合 (规定参与运算的元素)|
|2.|运算 (有限个二元或一元运算)|
|3.|代数常数 (运算相关的特异元素: 如单位元等)|


##### 同类型与同种代数系统

|**同类型**|两个代数系统中*运算的个数相同*, *对应运算的元数相同*, 且*代数常数的个数也相同*|
|-:|:-|
|**同种**|两个*同类型*的代数系统规定的*运算性质也相同*|
||~~同类型只关心运算个数、元数和常数个数, 不关心具体运算律; 同种则在同类型基础上要求运算律一致(如结合律、交换律等).~~|













##### 子代数系统
|**定义**|设 $V=<S, f_1, f_2, \dots, f_k>$ 是代数系统, $B$ 是 $S$ 的*非空子集*,|
|-:|:-|
||如果 $B$ 对 $f_1, f_2, \dots, f_k$ 都是*封闭的*, 且 $B$ 和 $S$ 含*有相同的代数常数*, |
||则称 $<B, f_1, f_2, \dots, f_k>$ 是 $V$ 的子代数系统, 简称**子代数**. 有时将子代数系统简记为 $B$.|
||~~显然,子代数和原代数是*同种*的代数系统~~|
|**最大的子代数**|$V$ 本身|
|**最小的子代数**|如果令 $V$ 中所有*代数常数构成的集合*是 $B$, 且 $B$ 对 $V$ 中所有的运算都是封闭的,|
||则 $B$ 就构成了 $V$ 的最小的子代数.|
|**平凡的子代数**|最大和最小的子代数|
|**真子代数**|若 $B$ 是 $S$ 的真子集, 则 $B$ 构成的子代数称为 $V$ 的真子代数|
||~~任何代数系统至少有两个平凡子代数: 自身(最大)和代数常数生成的子代数(最小, 若常数集封闭). 真子代数是严格包含于原集合的子代数.~~|





##### 积代数与因子代数
|**定义**|设 $V_1 = <A, \circ>$ 和 $V_2 = <B, *>$ 是*同类型的代数系统*, $\circ$ 和 $*$ 为二元运算, 在集合 $A \times B$ 上定义二元运算如下:|
|-:|:-|
||$\forall <a_1, b_1>, <a_2, b_2> \in A \times B$,|
||有 $<a_1, b_1> \cdot <a_2, b_2> = <a_1 \circ a_2, b_1 * b_2>$,|
||称 $V = <A \times B, \cdot>$ 为 $V_1$ 与 $V_2$ 的**积代数**, 记作 $V_1 \times V_2$. 这时也称 $V_1$ 和 $V_2$ 为 $V$ 的因子代数.|

###### 积代数的性质
|**积代数性质保持定理**|设 $V_1=<A, \circ>$ 和 $V_2=<B, *>$ 是同类型的代数系统,|
|-:|:-|
||$V_1 \times V_2 = <A \times B, \cdot>$ 是它们的积代数。|
|1.*保持交换、结合、幂等*|如果 $\circ$ 和 $*$ 运算是**可交换**(可结合、幂等)的,那么 $\cdot$ 运算也是**可交换**(可结合、幂等)的;|
|*证明*||
||~~不保留消去律~~|
|2.*保持代数常数*|如果 $e_1$ 和 $e_2$ ($\theta_1$ 和 $\theta_2$) 分别为 $\circ$ 和 $*$ 运算的单位元(零元),那么 $<e_1, e_2>$ ($<\theta_1, \theta_2>$) 也是 $\cdot$ 运算的单位元(零元)|
|*证明*||
|3.*保持可逆*|如果 $x$ 和 $y$ 分别为 $\circ$ 和 $*$ 运算的可逆元素,那么 $<x, y>$ 也是 $\cdot$ 运算的可逆元素,其逆元为 $<x^{-1}, y^{-1}>$.|
|*证明*||

