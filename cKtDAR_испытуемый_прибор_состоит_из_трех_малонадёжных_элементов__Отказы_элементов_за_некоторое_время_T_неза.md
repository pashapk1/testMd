

**Закон распределения**

Отказы элементов независимы, поэтому их суммарная вероятность отказа будет равна сумме вероятностей отказа каждого элемента по отдельности.

Закон распределения будет биноминальным:

$$P(X = k) = C_n^k \cdot P_1^k \cdot P_2^{n-k} \cdot P_3^{3-n},$$
где $C_n^k$ - число сочетаний из n по k.

**Математическое ожидание и дисперсия**

Математическое ожидание для данной задачи:

$$M(X) = np = 3 \cdot (0.04 \cdot 0.02 \cdot 0.01) = 0.0024$$

Дисперсия для данной задачи:

$$D(X) = np(1-p) = 3 \cdot (0.04 \cdot 0.02 \cdot 0.01) \cdot (1 - 0.04 \cdot 0.02 \cdot 0.01) = 0.002376$$

**Функция распределения**

Функция распределения для данной задачи будет иметь вид:

$$F(X) = \sum_{i=0}^k C_n^i \cdot P_1^i \cdot P_2^{n-i} \cdot P_3^{3-n}$$

**Вероятность того, что отказавших элементов будет не более n**

Вероятность $P(X \le n)$ отказавших элементов не более n равна:

$$P(X \le n) = \sum_{i=0}^n C_n^i \cdot P_1^i \cdot P_2^{n-i} \cdot P_3^{3-n}$$

Для заданных параметров, если n = 2, то:

$$P(X \le 2) = C_3^2 \cdot 0.04^2 \cdot 0.02^1 \cdot 0.01^0 + C_3^3 \cdot 0.04^3 \cdot 0.02^0 \cdot 0.01^0 = 0.2688$$