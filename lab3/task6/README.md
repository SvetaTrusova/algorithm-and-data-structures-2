# Задание №6 по выбору  : `Сортировка целых чисел`
Студентка ИТМО,  Трусова Светлана Викторовна 467766

## Вариант 22
В этой задаче нужно будет отсортировать много неотрицательных целых чисел.
Вам даны два массива, A и B, содержащие соответственно n и m элементов.
Числа, которые нужно будет отсортировать, имеют вид Ai · Bj , где 1 ≤ i ≤ n и
1 ≤ j ≤ m. Иными словами, каждый элемент первого массива нужно умножить
на каждый элемент второго массива.
Пусть из этих чисел получится отсортированная последовательность C длиной
n · m. Выведите сумму каждого десятого элемента этой последовательности (то
есть, C1 + C11 + C21 + ...). расположить матрёшки по неубыванию размера. Может
ли он это сделать?

## Input / Output

| Input    | Output |
|----------|--------|
| 4 4      | 51     |
| 7 1 4 9  |        |
| 2 7 8 11 |        |


## Ограничения по времени и памяти

- Ограничение по времени. 2сек.
- Ограничение по памяти. 256 мб.


## Запуск проекта
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/SvetaTrusova/algorithms-and-data-structures-2.git
   ```
2. Перейдите в папку с проектом:
   ```bash
   cd algorithms-and-data-structures-2/lab3
   ```
3. Запустите программу:
   ```bash
   python task6/src/task6.py
   ```


## Тестирование
Для запуска тестов выполните:
```bash
    python -m unittest -v lab3.task6.tests.test_3_6
```