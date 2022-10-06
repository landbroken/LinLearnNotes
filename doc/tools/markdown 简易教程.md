<h1><center> markdown cfg</center></h1>
# vscode 使用 markdown
## 配置插件
1. Markdown All in One。 主要的 markdown 功能
2. Markdown Preview Enhanced。 显示预览增强
3. Markdown Preview Github Styling。 显示风格采用 GitHub
4. Markdown Image. 允许复制、插入图片、主动上传图床

# Typora

感觉很好用，但现在开始收费了

https://typora.io/#download

# 数学公式
### 行内公式

> \$ 公式 \$

效果：
123 $ 公式 $ 456

### 单行公式
> \$\$ 公式 \$\$

效果：
$$ 公式 $$

### 上标

> \$\$ x\^2 \$\$

效果：
$$ x^2 $$

### 下标

括号


$$
f(x)=\begin{cases} 
		1, & x>0\\ 
		0, & x=0\\
		-1, & x<0
\end{cases}
$$

### 上取整
$$ \lceil \frac{x}{2} \rceil $$

### 下取整
$$ \lfloor x \rfloor $$

注意： 原始括号不会缩放,如

$$
    \lbrace  \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1}   \rbrace
$$

需要缩放括号的时候，可以加入 \left \right

$$  
\left\lbrace 
\sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1}                            
\right\rbrace 
$$

### 求和与积分
\sum 表示求和， 下标表示求和下限，上标表示求和上限 如:

$$
\sum_i^n
$$

\int 表示积分， 同样的，下标表示积分下限，上标表示积分上限.如:

$$ \int_{1}^{\infty} $$

类似符号还有

$$
\prod_{1}^{n} \\
\bigcup_{1}^{n} \\
\iint_{1}^{n}
$$

### 分式与根式
分式

$$
\frac ab
$$

$$
\frac{1}{2}
$$

也可以
$$
{a+1 \over b+1}
$$

根式
$$
\sqrt[x+1]{x^2}
$$

## 字体
黑板粗体字: \mathbb

### 特殊函数与符号
#### 求和符号

$$\sum_{i=0}^{n}$$
​	
#### 累乘符号

$$\prod$$

#### 极限符号

 $\lim_{x\to +\infty}$

#### 收敛

$$x_n\stackrel{p}\longrightarrow0$$

#### 向量

$$\vec{a}$$

或

 $$\overrightarrow{a} $$

$$\hat y=a\hat x+b$$

#### 转置符号

$$\mathtt{X}'$$

#### 异或

⨁ $\bigoplus$

![图 5](../../images/markdown%20%E7%AE%80%E6%98%93%E6%95%99%E7%A8%8B_pic_1665046035203_7ad3cf136f11e69178ff9fdfd5ba6d84cafff2ce2082d8a21c4e1046b4a93974.png)  

## 矩阵
$$
  \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix} \tag{1}
$$

$$
 \left\{
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right\} \tag{2}
$$

$$
 \left[
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right] \tag{3}
$$

$$
\left[
\begin{matrix}
 1      & 2      & \cdots & 4      \\
 7      & 6      & \cdots & 5      \\
 \vdots & \vdots & \ddots & \vdots \\
 8      & 9      & \cdots & 0      \\
\end{matrix}
\right]
$$

$$ 
\left[
    \begin{array}{cc|c}
      1 & 2 & 3 \\
      4 & 5 & 6
    \end{array}
\right] \tag{7}
$$

## 公式对齐
$$
\begin{aligned}
a &= b + c\\
  &= d + e + f
\end{aligned}
$$

# 参考文献
1. [markdown数学公式（常用版介绍）](https://blog.csdn.net/RNG_uzi_/article/details/108947641)