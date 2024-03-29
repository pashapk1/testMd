

**Закон распределения**

Закон распределения числа неотказавших элементов прибора будет иметь биномиальное распределение с параметрами:

$n$ - общее число элементов: 3

$p$ - вероятность появления неотказавшего элемента: $P_1P_2P_3 = 0.0008$

**Функция распределения**

Функция распределения биномиального распределения имеет вид:

$F(x) = 
\begin{cases}
0, & x < 0 \\
\sum\limits_{i=0}^x C_n^i p^i (1 - p)^{n - i}, & 0 \le x \le n \\
1, & x > n
\end{cases}$,

где $C_n^i$ - это число сочетаний из n по i.

**Математическое ожидание и дисперсия**

Математическое ожидание и дисперсия биномиального распределения равны:

$M(X) = np$

$D(X) = np(1 - p)$

Для нашей задачи получаем:

$M(X) = 3 \cdot 0.0008 = 0.0024$

$D(X) = 3 \cdot 0.0008 \cdot 0.9992 = 0.002376$

**Мода**

Мода биномиального распределения равна числу элементов, для которого вероятность появления максимальна. Так как вероятность появления неотказавшего элемента $P_1P_2P_3 = 0.0008$, то модой будет число 3.

**Вероятность того, что отказавших элементов будет не более n**

Для того, чтобы найти вероятность того, что отказавших элементов будет не более n, необходимо воспользоваться функцией распределения:

$P(X \le n) = F(n) = \sum\limits_{i=0}^n C_3^i 0.0008^i 0.9984^{3 - i}$

Для нашей задачи, где n = 2, получаем:

$P(X \le 2) = 0.99984$