
# 📘 Markdown 数学公式大全（LaTeX 语法）

> ✅ 行内公式：`$...$`  
> ✅ 块级公式：`$$...$$`

---

## 1. ✅ 上下标

```
$x_i \quad x^2 \quad x_{i+1}^{n}$
```
$x_i \quad x^2 \quad x_{i+1}^{n}$
---

## 2. ✅ 希腊字母

```
$\alpha\ \beta\ \gamma\ \Gamma\ \pi\ \Pi\ \theta\ \Theta$
```
$\alpha\ \beta\ \gamma\ \Gamma\ \pi\ \Pi\ \theta\ \Theta$
---

## 3. ✅ 分数、根式、绝对值

```
$\frac{a}{b} \quad \sqrt{x} \quad \sqrt[n]{x} \quad |x| \quad \left| \frac{a}{b} \right|$
```
$\frac{a}{b} \quad \sqrt{x} \quad \sqrt[n]{x} \quad |x| \quad \left| \frac{a}{b} \right|$
---

## 4. ✅ 常用运算符

```
$+ \quad - \quad \times \quad \cdot \quad \div \quad = \quad \neq \quad \approx \quad \pm \quad \mp$
```
$+ \quad - \quad \times \quad \cdot \quad \div \quad = \quad \neq \quad \approx \quad \pm \quad \mp$
---

## 5. ✅ 括号自动大小

```
$\left( \frac{a}{b} \right) \quad \left[ x^2 \right] \quad \left\{ 1, 2 \right\}$
```
$\left( \frac{a}{b} \right) \quad \left[ x^2 \right] \quad \left\{ 1, 2 \right\}$
---

## 6. ✅ 求和、极限、积分

```
$\sum_{i=1}^n i \quad \prod_{i=1}^n i \quad \lim_{x \to 0} \frac{\sin x}{x} \quad \int_a^b x^2 \, dx$
```
$\sum_{i=1}^n i \quad \prod_{i=1}^n i \quad \lim_{x \to 0} \frac{\sin x}{x} \quad \int_a^b x^2 \, dx$
---

## 7. ✅ 向量、点积、单位符号

```
$\vec{v} \quad \overrightarrow{AB} \quad \hat{i} \quad \cdot \quad \times$
```
$\vec{v} \quad \overrightarrow{AB} \quad \hat{i} \quad \cdot \quad \times$
---

## 8. ✅ 常用函数

```
$\sin x \quad \cos x \quad \tan x \quad \log x \quad \ln x \quad \exp(x)$
```
$\sin x \quad \cos x \quad \tan x \quad \log x \quad \ln x \quad \exp(x)$
---

## 9. ✅ 关系符号与集合

```
$\in \quad \notin \quad \subset \quad \subseteq \quad \cup \quad \cap \quad \emptyset \quad \forall \quad \exists$
```
$\in \quad \notin \quad \subset \quad \subseteq \quad \cup \quad \cap \quad \emptyset \quad \forall \quad \exists$
---

## 10. ✅ 矩阵

```markdown
$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
$$
```
$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
$$
---

## 11. ✅ 分段函数

```markdown
$$
f(x) = \begin{cases}
x^2, & x \ge 0 \\
-x, & x < 0
\end{cases}
$$
```
$$
f(x) = \begin{cases}
x^2, & x \ge 0 \\
-x, & x < 0
\end{cases}
$$
---

## 12. ✅ 多行对齐

```markdown
$$
\begin{aligned}
a &= b + c \\
  &= d + e
\end{aligned}
$$
```

---

## 13. ✅ 逻辑符号

```
$\land \quad \lor \quad \lnot \quad \Rightarrow \quad \Leftarrow \quad \Leftrightarrow$
```
$\land \quad \lor \quad \lnot \quad \Rightarrow \quad \Leftarrow \quad \Leftrightarrow$
---

## 14. ✅ 空格与换行

```
$a\ b\quad c\qquad d \\e$
```
$a\ b\quad c\qquad d \\e$
---

## 15. ✅ 特殊符号

```
$\infty \quad \because \quad \therefore \quad \angle \quad \degree$
```
$\infty \quad \because \quad \therefore \quad \angle \quad \degree$
---

## 16. ✅ 组合公式示例

```
$\binom{n}{k} = \frac{n!}{k!(n-k)!}$
```
$\binom{n}{k} = \frac{n!}{k!(n-k)!}$
---

## 📦 支持这些公式的平台

| 平台               | 支持数学公式         |
| ---------------- | -------------- |
| Typora           | ✅ 支持           |
| Obsidian         | ✅ 支持           |
| GitHub README    | ❌ 不支持 LaTeX 数学 |
| Jupyter Notebook | ✅ 支持           |
| Notion           | ✅ 支持           |
| HackMD           | ✅ 支持           |
| VS Code Preview  | ✅ 支持           |
