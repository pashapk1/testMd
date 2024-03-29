

# Оценивание уравнения с помощью Метода Наименьших Квадратов

Дано уравнение $Y_i = b_1 + b_2 x_i + \varepsilon_i$, где $b_1 = 5$ и $b_2 = -0.3$ и мы хотим получить оценку для этих коэффициентов с помощью Метода Наименьших Квадратов (МНК).

Пусть $t_1$ и $t_2$ будут коэффициентами для уравнения $Y_i = t_1 + t_2 \frac{x_i}{10} + \varepsilon_i$. Заменим первое уравнение на второе и получим следующее уравнение:

$$Y_i = \frac{10t_1}{9} + \frac{10t_2}{9}x_i + \varepsilon_i - \frac{10b_2}{9}x_i$$

Таким образом, МНК-оценка для коэффициентов $t_1$ и $t_2$ равна следующему: 

$$ \hat{t}_1 = \frac{90b_1 - 10b_2\overline{x}}{9} $$

$$ \hat{t}_2 = \frac{10b_2}{9} $$

где $\overline{x}$ - среднее значение переменной $x$.

# Решение на русском языке

Для оценивания уравнения используется Метод Наименьших Квадратов, что позволяет получить оценку для коэффициентов $t_1$ и $t_2$ в уравнении $Y_i = t_1 + t_2 \frac{x_i}{10} + \varepsilon_i$. Оценка равна $\hat{t}_1 = \frac{90b_1 - 10b_2\overline{x}}{9}$ и $\hat{t}_2 = \frac{10b_2}{9}$, где $\overline{x}$ - среднее значение переменной $x$.