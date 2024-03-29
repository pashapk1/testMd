

Закон распределения числа неотказавших элементов будет биноминальным с параметрами n и p. Здесь n – это количество элементов (n = 3), а p – вероятность неотказа для каждого элемента (p = 1-Р, для каждого элемента).

Математическое ожидание числа неотказавших элементов будет равно:

M(X) = np

где n – количество элементов, p – вероятность неотказа для каждого элемента.

M(X) = 3 * (1 - 0,04 - 0,02 - 0,01) = 2,91

Дисперсия числа неотказавших элементов будет равна:

D(X) = npq

где n – количество элементов, p – вероятность неотказа для каждого элемента, q = 1 – p.

D(X) = 3 * (1 - 0,04 - 0,02 - 0,01) * (0,04 + 0,02 + 0,01) = 0,091

Мода числа неотказавших элементов будет равна 3, так как вероятность того, что все три элемента не откажутся, равна (1 - 0,04 - 0,02 - 0,01) = 0,93.

Функция распределения числа неотказавших элементов будет выглядеть следующим образом:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;P(X=k) = \binom{n}{k}p^kq^{n-k}, \quad k=0,1,\ldots,n" title="\Large P(X=k) = \binom{n}{k}p^kq^{n-k}, \quad k=0,1,\ldots,n" />
</p>

где n – количество элементов, p – вероятность неотказа для каждого элемента, q = 1 – p.

Вероятность того, что отказавшихся элементов будет не более 2, равна:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;P(X\leq2)=\binom{3}{0}(1-0,04-0,02-0,01)^3+\binom{3}{1}(1-0,04-0,02-0,01)^2(0,04+0,02+0,01)+\binom{3}{2}(1-0,04-0,02-0,01)(0,04+0,02+0,01)^2=0,972" title="\Large P(X\leq2)=\binom{3}{0}(1-0,04-0,02-0,01)^3+\binom{3}{1}(1-0,04-0,02-0,01)^2(0,04+0,02+0,01)+\binom{3}{2}(1-0,04-0,02-0,01)(0,04+0,02+0,01)^2=0,972" />
</p>

Таким образом, вероятность того, что отказавшихся элементов будет не более 2, равна 0,972.

**Решение на русском языке**

Закон распределения числа неотказавших элементов является биноминальным с параметрами n и p. Здесь n – это количество элементов (n = 3), а p – вероятность неотказа для каждого элемента (p = 1-Р, для каждого элемента). Математическое ожидание числа неотказавших элементов равно 2,91, дисперсия равна 0,091, а мода равна 3. Функция распределения числа неотказавших элементов вычисляется по формуле. Вероятность того, что отказавшихся элементов будет не более 2, равна 0,972.