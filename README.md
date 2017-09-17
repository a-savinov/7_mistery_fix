# Решатель квадратных уравнений

Модуль содержит функцию quadratic_equation для расчета корней квадратного уравнения.

Квадратное уравнение — алгебраическое уравнение общего вида  - _**a x 2 + b x + c = 0**_  

Элементы квадратного уравнения имеют собственные названия:

    a называют первым или старшим коэффициентом,
    b называют вторым, средним или коэффициентом при x ,
    c называют свободным членом.


# Как использовать

```python
import quadratic_equation

print(quadratic_equation(1, 2, -3))

```
Функция _**quadratic_equation(a, b, c)**_  принимает на вход соответствующие элементы квадратного уравнения и возвращает корни квадратного уравнения 
В случае если корень расчитать невозможно возвращается заначение _**None**_


# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
