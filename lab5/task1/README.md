# Задание №1 по варианту  : `Куча ли?`
Студентка ИТМО,  Трусова Светлана Викторовна 467766

## Вариант 22

## Задание 
Структуру данных «куча», или, более конкретно, «неубывающая пирамида»,
можно реализовать на основе массива.
Для этого должно выполнятся основное свойство неубывающей пирамиды,
которое заключается в том, что для каждого 1 ≤ i ≤ n выполняются условия:
1. если 2i ≤ n, то ai ≤ a2i,
2. если 2i + 1 ≤ n, то ai ≤ a2i+1.
Дан массив целых чисел. Определите, является ли он неубывающей пирамидой.
## Input / Output

| Input             | Output |
|-------------------|--------|
| 5 <br/> 1 0 1 2 0 | NO     |
| 5 <br/> 1 3 2 5 4 | YES    |
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
   cd algorithms-and-data-structures-2/lab5
   ```
3. Запустите программу:
   ```bash
   python task1/src/task1.py
   ```


## Тестирование
Для запуска тестов выполните:
```bash
    python -m unittest -v lab5.task1.tests.test_5_1.py
```