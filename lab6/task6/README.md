# Задание №6 по варианту  : `Фибоначчи возвращается`
Студентка ИТМО,  Трусова Светлана Викторовна 467766

## Вариант 22

## Задание 
Вам дается последовательность чисел. Для каждого числа определите, является ли оно числом Фибоначчи. Напомним, что числа Фибоначчи определяются,
например, так:
F0 = F1 = 1 
Fi = Fi−1 + Fi−2 для i ≥2.

## Input / Output

| Input | Output |
|-------|--------|
| 8     | Yes    |
 1      | Yes    |
 2      | Yes    |
 3      | No     |
 4      | Yes    |
 5      | No     |
 6      | No     |
 7      | Yes    |
 8      |        |

## Ограничения по времени и памяти

- Ограничение по времени. 2сек.
- Ограничение по памяти. 128 мб.


## Запуск проекта
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/SvetaTrusova/algorithms-and-data-structures-2.git
   ```
2. Перейдите в папку с проектом:
   ```bash
   cd algorithms-and-data-structures-2/lab6
   ```
3. Запустите программу:
   ```bash
   python task6/src/task6.py
   ```


## Тестирование
Для запуска тестов выполните:
```bash
    python -m unittest -v lab6.task6.tests.test_6_6.py
```