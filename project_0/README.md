# Проект 0. Угадай число  (# Задание 9.1. Модуль 8 (HW-01))





## Оглавление




[1.Описание проекта](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Описание-проекта)

[2.Какой кейс решаем?](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Какой-кейс-решаем)

[3.Краткая информация о данных](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Краткая-информация-о-данных)

[4.Этапы работы над проектом](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Этапы-работы-над-проектом)

[5.Результат](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Результат) 

[6.Выводы](https://github.com/valah75/sf_data_science/tree/main/project_0/README.md#Выводы)










### Описание проекта
Угадать загаданное компьютером число за минимальное число попыток.


### Какой кейс решаем?
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.


**Метрика качества**
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**
Учимся писать хороший код на руthon

**Критерии оценивания:**
1 балл 	Программа находит число меньше чем за 20 попыток. Если данное условие не выполняется,
 выставляется 0 баллов за это и все остальные условия.
1 балл 	Код решения загружен на GitHub.
1 балл 	GitHub оформлен соответствующим образом.
1 балл 	Код соответствует стандарту PEP8.
1 балл 	Код воспроизводим.
Максимально возможное количество баллов за задание — 5

### Краткая информация о данных
Компьютер загадывает последовательность псевдослучайных чисел в указанном диапазоне(целое число от 0 до 100).
Длинна этой последовательности равна 1000(количество повторений)

### Этапы работы над проектом
Разрабока оптимального алгоритма, чтобы уменьшить количество попыток угадывания.
Используем сокращение диапазона поиска в два раза при каждом шаге.

### Результат
Результат хороший. 
Среднее количество попыток равно 5.

### Выводы
Полученный алгоритм более оптимальный чем простой перебор чисел диапазона.
Среднее количество попыток зависит от длины диапазона поиска.