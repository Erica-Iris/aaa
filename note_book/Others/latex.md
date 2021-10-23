### 一、 Markdown排版格式

###### 1）行内公式排版

```ruby
 $ c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}} $
```

![c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}}](https://math.jianshu.com/math?formula=c%20%3D%20%5Csqrt%7Ba%5E%7B2%7D%2Bb_%7Bxy%7D%5E%7B2%7D%2Be%5E%7Bx%7D%7D)

###### 2）块公式排版

```ruby
$$ c = \sqrt{a^{2}+b_{xy}^{2} +e^{x}} $$
```

![c = \sqrt{a^{2}+b_{xy}^{2} +e^{x}}](https://math.jianshu.com/math?formula=c%20%3D%20%5Csqrt%7Ba%5E%7B2%7D%2Bb_%7Bxy%7D%5E%7B2%7D%20%2Be%5E%7Bx%7D%7D)

### 二、LaTex的公式规则

##### 常用规则

###### 1）转义

> 一下几个字符: # $ % & ~ _ ^ \ { }有特殊意义，需要表示这些字符时，需要转义，即在每个字符前加上 \ 。
>
> \boxed命令给公式加一个方框。

```ruby
$E = mc^2 $
$ \boxed{E=mc^2} $
```

![E = mc^2 \quad \boxed{E=mc^2}](https://math.jianshu.com/math?formula=E%20%3D%20mc%5E2%20%5Cquad%20%5Cboxed%7BE%3Dmc%5E2%7D)

###### 2）希腊字母

![](//upload-images.jianshu.io/upload_images/3187098-f9884c349c6d36df.png?imageMogr2/auto-orient/strip|imageView2/2/w/870/format/webp)

###### 3）上下标和根号

> 用^来表示上标
>
> 用_来表示下标
>
> 用\sqrt表示根号

注意：上下标如果多余一个字符或符号，需要用{}括起来。

```ruby
$ \sum_{i=1}^n a_i $
```

![\sum_{i=1}^n a_i](https://math.jianshu.com/math?formula=%5Csum_%7Bi%3D1%7D%5En%20a_i)

\sqrt[开方次数，默认为2]{开方公式}， 例如：

```cpp
$$ x_{ij}^2\quad \sqrt{x}\quad \sqrt[3]{x} $$
```

$$
x_{ij}^2\quad \sqrt{x}\quad \sqrt[3]{x}
$$

其中\quad表示添加空格。

###### 4）分数

> 分数用\frac表示。

> 字号工具环境设置：
>
> \dfrac命令把字号设置为独立公式中的大小；
>
> \tfrac则把字号设置为行间公式中的大小。

```ruby
$$ \frac{1}{2} \tfrac{1}{2} $$ 
```

$$
\frac{1}{2} \tfrac{1}{2}
$$

###### 5）运算符

> + - * / = 直接输入；

> 特殊运算则用以下特殊命令 `\pm\; \times\; \div\; \cdot\; \cap\; \cup\; \geq\; \leq\; \neq\; \approx\; \equiv`
>
> ![\pm<span data-type=](https://math.jianshu.com/math?formula=%5Cpm%5C%3B%20%5Ctimes%5C%3B%20%5Cdiv%5C%3B%20%5Ccdot%5C%3B%20%5Ccap%5C%3B%20%5Ccup%5C%3B%20%5Cgeq%5C%3B%20%5Cleq%5C%3B%20%5Cneq%5C%3B%20%5Capprox%5C%3B%20%5Cequiv)\; \times\; \div\; \cdot\; \cap\; \cup\; \geq\; \leq\; \neq\; \approx\; \equiv" />

> 和、积、极限、积分等运算符用\sum, \prod, \lim, \int,这些公式在行内公式被压缩，以适应行高，可以通过\limits和\nolimits命令显示制动是否压缩。
>
> ![\sum<span data-type=](https://math.jianshu.com/math?formula=%5Csum%5C%3B%20%5Cprod%5C%3B%20%5Clim%5C%3B%20%5Cint%5C%3B)\; \prod\; \lim\; \int\;" />

```ruby
$ \sum_{i=1}^n i 

$ \prod_{i=1}^n 

$\lim_{x\to0}x^2 

$\int_{a}^{b}x^2 dx 

$\sum_{i=1}^n i \quad\prod_{i=1}^n 
\quad
\lim_{x\to0}x^2 \quad\int_{a}^{b}x^2 dx 
$
```

![\sum_{i=1}^n i \quad\prod_{i=1}^n \quad \lim_{x\to0} x^2 \quad\int_a^b x^2 dx $$$$ \sum_{i=1}^n i \quad\prod_{i=1}^n\quad\lim_{x\to0} x^2 \quad\int_a^b x^2 dx \sum\nolimits_{i=1}^n\quad\prod\nolimits_{i=1}^n \quad \lim\nolimits_{x\to0} x^2 \quad\int\nolimits_a^b x^2 dx](https://math.jianshu.com/math?formula=%5Csum_%7Bi%3D1%7D%5En%20i%20%5Cquad%5Cprod_%7Bi%3D1%7D%5En%20%5Cquad%20%5Clim_%7Bx%5Cto0%7D%20x%5E2%20%5Cquad%5Cint_a%5Eb%20x%5E2%20dx%20%24%24%24%24%20%5Csum_%7Bi%3D1%7D%5En%20i%20%5Cquad%5Cprod_%7Bi%3D1%7D%5En%5Cquad%5Clim_%7Bx%5Cto0%7D%20x%5E2%20%5Cquad%5Cint_a%5Eb%20x%5E2%20dx%20%5Csum%5Cnolimits_%7Bi%3D1%7D%5En%5Cquad%5Cprod%5Cnolimits_%7Bi%3D1%7D%5En%20%5Cquad%20%5Clim%5Cnolimits_%7Bx%5Cto0%7D%20x%5E2%20%5Cquad%5Cint%5Cnolimits_a%5Eb%20x%5E2%20dx)

###### 6）多重积分

> 使用如下形式：\int、\iint、\iiint、\iiiint、\idotsint

```cpp
$$ \int \int \quad \int \int \int \quad 
 \int \int \int \int \quad \int \dots \int $$

$$ \iint \quad \iiint \quad \iiiint \quad \idotsint $$
```

![\int\int\quad\int\int\int\quad\int\int\int\int\quad\int\dots\int$$$$ \iint\quad\iiint\quad\iiiint\quad\idotsint](https://math.jianshu.com/math?formula=%5Cint%5Cint%5Cquad%5Cint%5Cint%5Cint%5Cquad%5Cint%5Cint%5Cint%5Cint%5Cquad%5Cint%5Cdots%5Cint%24%24%24%24%20%5Ciint%5Cquad%5Ciiint%5Cquad%5Ciiiint%5Cquad%5Cidotsint)

```ruby
$ \leftarrow $ 
```

$\leftarrow$

```ruby
$ \rightarrow $ 
```

$ \rightarrow $

```ruby
$ \leftrightarrow $ 
```

$ \leftrightarrow $

```ruby
$ \longleftarrow $
```

$ \longleftarrow $

```ruby
$longleftrightarrow$
```

![\Longleftarrow](https://math.jianshu.com/math?formula=%5CLongleftarrow)

```ruby
$ \Longrightarrow $
```

![\Longleftrightarrow](https://math.jianshu.com/math?formula=%5CLongleftrightarrow)

```ruby
$\xleftarrow和$\xrightarrow可根据内容自动调整
```

###### 7）注音和标注

```ruby
$ \bar{x} $
```

$\bar{x}$

```ruby
$ \acute{x}$
```

$\acute{x}$

```ruby
$ \mathring{x}$
```

$\mathring{x}$

```ruby
$ \vec{x}$
```

$\vec{x}$

```ruby
$ \grave{x} $
```

$\grave{x}$

```ruby
$ \dot{x}$
```

$\dot{x}$

```ruby
$ \hat{x}$
```

$\hat{x}$

```ruby
$ \tilde{x}$
```

$\tilde{x}$

```ruby
$ \ddot{x}$
```

$\ddot{x}$

```ruby
$ \check{x} $
```

$\check{x}$

```ruby
$ \breve{x}$
```

$\breve{x}$

```ruby
$ \dddot{x} $
```

###### 8）分隔符

> 括号用() [] {} \lange \rangle表示 ()  []  {}  ⟨⟩

```ruby
$ \overline{xxx}$
```

![\overline{xxx}](https://math.jianshu.com/math?formula=%5Coverline%7Bxxx%7D)

```ruby
$\overleftrightarrow{xxx}$
```

![\overleftrightarrow{xxx}](https://math.jianshu.com/math?formula=%5Coverleftrightarrow%7Bxxx%7D)

```ruby
$\underline{xxx}$
```

![\underline{xxx}](https://math.jianshu.com/math?formula=%5Cunderline%7Bxxx%7D)

```ruby
$\underleftrightarrow{xxx}$
```

![\underleftrightarrow{xxx}](https://math.jianshu.com/math?formula=%5Cunderleftrightarrow%7Bxxx%7D)

```ruby
$\overleftarrow{xxx}$
```

![\overleftarrow{xxx}](https://math.jianshu.com/math?formula=%5Coverleftarrow%7Bxxx%7D)

```ruby
$\overbrace{xxx}$
```

![\overbrace{xxx}](https://math.jianshu.com/math?formula=%5Coverbrace%7Bxxx%7D)

```ruby
$\underleftarrow{xxx}$
```

![\underleftarrow{xxx}](https://math.jianshu.com/math?formula=%5Cunderleftarrow%7Bxxx%7D)

```ruby
$\underbrace{xxx}$
```

![\underbrace{xxx}](https://math.jianshu.com/math?formula=%5Cunderbrace%7Bxxx%7D)

```ruby
$\overrightarrow{xxx}$
```

![\overrightarrow{xxx}](https://math.jianshu.com/math?formula=%5Coverrightarrow%7Bxxx%7D)

```ruby
$\widehat{xxx}$
```

![\widehat{xxx}](https://math.jianshu.com/math?formula=%5Cwidehat%7Bxxx%7D)

```ruby
$\underrightarrow{xxx}$
```

![\underrightarrow{xxx}](https://math.jianshu.com/math?formula=%5Cunderrightarrow%7Bxxx%7D)

```ruby
$\widetilde{xxx}$
```

![\widetilde{xxx}](https://math.jianshu.com/math?formula=%5Cwidetilde%7Bxxx%7D)

```ruby
$$
\Bigg( \bigg( \Big( \big((x) \big) \Big) \bigg) \Bigg)

\quad

\Bigg[ \bigg[ \Big[ \big[[x] \big] \Big] \bigg] \Bigg]

\quad

\Bigg\{ \bigg\{ \Big\{ \big\{\{x\} \big\} \Big\} \bigg\} \Bigg\}
$$
```

![\Bigg(\bigg(\Big(\big((x)\big)\Big)\bigg)\Bigg) \quad\Bigg[\bigg[\Big[\big[[x]\big]\Big]\bigg]\Bigg]\quad\Bigg<span data-type=](https://math.jianshu.com/math?formula=%5CBigg(%5Cbigg(%5CBig(%5Cbig((x)%5Cbig)%5CBig)%5Cbigg)%5CBigg)%20%5Cquad%5CBigg%5B%5Cbigg%5B%5CBig%5B%5Cbig%5B%5Bx%5D%5Cbig%5D%5CBig%5D%5Cbigg%5D%5CBigg%5D%5Cquad%5CBigg%5C%7B%5Cbigg%5C%7B%5CBig%5C%7B%5Cbig%5C%7B%5C%7Bx%5C%7D%5Cbig%5C%7D%5CBig%5C%7D%5Cbigg%5C%7D%5CBigg%5C%7D)\{\bigg\{\Big\{\big\{\{x\}\big\}\Big\}\bigg\}\Bigg\}" />

```ruby
$$
\Bigg\langle \bigg\langle \Big\langle \big\langle\langle x \rangle \big\rangle \Big\rangle \bigg\rangle \Bigg\rangle 

\quad

\Bigg\lvert \bigg\lvert \Big\lvert \big\lvert\lvert x \rvert \big\rvert \Big\rvert \bigg\rvert \Bigg\rvert

\quad

\Bigg\lVert \big \lVert \Big\lVert \big\lVert \lVert x \rVert \big\rVert \Big\rVert \bigg\rVert \Bigg\rVert
$$
```

![\Bigg\langle \bigg\langle \Big\langle \big\langle\langle x \rangle \big \rangle\Big\rangle\bigg\rangle\Bigg\rangle \quad\Bigg\lvert\bigg\lvert\Big\lvert\big\lvert\lvert x \rvert\big\rvert\Big\rvert\bigg\rvert\Bigg\rvert \quad\Bigg\lVert\bigg\lVert\Big\lVert\big\lVert\lVert x \rVert\big\rVert\Big\rVert\bigg\rVert\Bigg\rVert](https://math.jianshu.com/math?formula=%5CBigg%5Clangle%20%5Cbigg%5Clangle%20%5CBig%5Clangle%20%5Cbig%5Clangle%5Clangle%20x%20%5Crangle%20%5Cbig%20%5Crangle%5CBig%5Crangle%5Cbigg%5Crangle%5CBigg%5Crangle%20%5Cquad%5CBigg%5Clvert%5Cbigg%5Clvert%5CBig%5Clvert%5Cbig%5Clvert%5Clvert%20x%20%5Crvert%5Cbig%5Crvert%5CBig%5Crvert%5Cbigg%5Crvert%5CBigg%5Crvert%20%5Cquad%5CBigg%5ClVert%5Cbigg%5ClVert%5CBig%5ClVert%5Cbig%5ClVert%5ClVert%20x%20%5CrVert%5Cbig%5CrVert%5CBig%5CrVert%5Cbigg%5CrVert%5CBigg%5CrVert)

###### 9）省略号

> 省略号用 \dots \cdots \vdots \ddots表示 ，\dots和\cdots的纵向位置不同，前者一般用于有下标的序列

```ruby
$$ x_1, x_2, \dots, x_n\quad 1,2,\cdots,n\quad \vdots\quad \ddots $$
```

![x_1, x_2, \dots, x_n\quad 1,2,\cdots,n\quad \vdots\quad \ddots](https://math.jianshu.com/math?formula=x_1%2C%20x_2%2C%20%5Cdots%2C%20x_n%5Cquad%201%2C2%2C%5Ccdots%2Cn%5Cquad%20%5Cvdots%5Cquad%20%5Cddots)

###### 10）空白间距

| 语法         | 格式           | 实例                                                                      | 显示             |
| ------------ | -------------- | ------------------------------------------------------------------------- | ---------------- |
| quad空格     | `a \quad b`  | ![a \quad b](https://math.jianshu.com/math?formula=a%20%5Cquad%20b)         | 一个*m*的宽度  |
| 两个quad空格 | `a \qquad b` | ![a \qquad b](https://math.jianshu.com/math?formula=a%20%5Cqquad%20b)       | 两个*m*的宽度  |
| 大空格       | `a \: b`     | ![a<span data-type=](https://math.jianshu.com/math?formula=a%5C%3Ab)\:b" /> | 1/3*m*宽度     |
| 中等空格     | `a \; b`     | ![a<span data-type=](https://math.jianshu.com/math?formula=a%5C%3Bb)\;b" /> | 2/7*m*宽度     |
| 小空格       | `a \, b`     | ![a<span data-type=](https://math.jianshu.com/math?formula=a%5C%2Cb)\,b" /> | 1/6*m*宽度     |
| 没有空格     | `ab`         | ![ab](https://math.jianshu.com/math?formula=ab)                             | 没有空格         |
| 缩进空格     | `a \! b`     | ![a<span data-type=](https://math.jianshu.com/math?formula=a%5C!b)\!b" />   | 缩进1/6*m*宽度 |

##### 复杂公式

###### 1）矩阵

```ruby
$$
\begin{array}{ccc}
x_1 & x_2 &\dots\\
x_3 & x_4 &\dots\\
\vdots&\vdots&\ddots
\end{array}
$$
```

$$
\begin{array}{ccc}
x_1 & x_2 &\dots\\
x_3 & x_4 &\dots\\
\vdots&\vdots&\ddots
\end{array}
$$

```ruby
$$
\begin{pmatrix} 
a & b\\ 
c & d \\
\end{pmatrix}

\quad

\begin{bmatrix} 
a & b \\ 
c & d \\
\end{bmatrix}

\quad

\begin{Bmatrix} 
a & b \\ 
c & d \\
\end{Bmatrix}

\quad

\begin{vmatrix} 
a & b \\ 
c & d \\
\end{vmatrix}

\quad

\begin{Vmatrix} 
a & b \\ 
c & d \\
\end{Vmatrix}
$$
```

$$
\begin{pmatrix} 
a & b\\ 
c & d \\
\end{pmatrix}

\quad

\begin{bmatrix} 
a & b \\ 
c & d \\
\end{bmatrix}

\quad

\begin{Bmatrix} 
a & b \\ 
c & d \\
\end{Bmatrix}

\quad

\begin{vmatrix} 
a & b \\ 
c & d \\
\end{vmatrix}

\quad

\begin{Vmatrix} 
a & b \\ 
c & d \\
\end{Vmatrix}
$$

```ruby
$$
(
\begin{smallmatrix} 
a & b \\ 
c & d 
\end{smallmatrix}
) 
$$
```

$$
(
\begin{smallmatrix} 
a & b \\ 
c & d 
\end{smallmatrix}
)
$$

###### 2）长公式

> 无需对齐可使用multline；
>
> 需要对齐使用split；
>
> 用\\来分行；
>
> 用&设置对齐的位置

```ruby
$$
\begin{multline}  
x = a+b+c+{} \\   
d+e+f+g  
\end{multline}
$$
```

```ruby
$$
\begin{split}
x = {} & a + b + c +{}\\  
       & d + e + f + g
\end{split}
$$
```

![\begin{split} x = {} & a + b + c +{}<span data-type=](https://math.jianshu.com/math?formula=%5Cbegin%7Bsplit%7D%20x%20%3D%20%7B%7D%20%26%20a%20%2B%20b%20%2B%20c%20%2B%7B%7D%5C%5C%20%26%20d%20%2B%20e%20%2B%20f%20%2B%20g%20%5Cend%7Bsplit%7D)\\ & d + e + f + g \end{split}" />

###### 3）公式组

> 不需要对齐的公式组用gather；
>
> 需要对齐使用align:

```ruby
$\begin{gather}
a = b+c+d\\
x = y+z\\
5 = 4+1\\
\end{gather}$
```

```ruby
$\begin{align}
a &=b+c+d \\
x &=y+z\\
5 &= 4+1
\end{align}$
```

![\begin{align} a &=b+c+d <span data-type=](https://math.jianshu.com/math?formula=%5Cbegin%7Balign%7D%20a%20%26%3Db%2Bc%2Bd%20%5C%5C%20x%20%26%3Dy%2Bz%5C%5C%205%20%26%3D%204%2B1%20%5Cend%7Balign%7D)\\ x &=y+z\\ 5 &= 4+1 \end{align}" />

###### 4）分支公式

> **分段函数**通常用cases次环境携程分支公式

```ruby
$ y=\begin{cases}
-x,\quad x\leq 0\\
x, \quad x>0
\end{cases} $
```

![y=\begin{cases}-x,\quad x\leq 0<span data-type=](https://math.jianshu.com/math?formula=y%3D%5Cbegin%7Bcases%7D-x%2C%5Cquad%20x%5Cleq%200%5C%5Cx%2C%20%5Cquad%20x%3E0%5Cend%7Bcases%7D)\\x, \quad x>0\end{cases}" />

###### 5）定理、引理、证明、假设
