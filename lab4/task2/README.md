# Задание №2 по варианту  : `Очередь`
Студентка ИТМО,  Трусова Светлана Викторовна 467766

## Вариант 22

## Задание 
Реализуйте работу очереди. Для каждой операции изъятия элемента выведите
ее результат.
На вход программе подаются строки, содержащие команды. Каждая строка
содержит одну команду. Команда — это либо «+ N», либо «–». Команда «+
N» означает добавление в очередь числа N, по модулю не превышающего 109
.
Команда «–» означает изъятие элемента из очереди. Гарантируется, что размер
очереди в процессе выполнения команд не превысит 106
элементов.


## Input / Output

| Input                                  | Output        |
|----------------------------------------|---------------|
| 4 <br/> + 1 <br/> + 10 <br/> - <br/> - | 10 <br/> 1234 |


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
   cd algorithms-and-data-structures-2/lab4
   ```
3. Запустите программу:
   ```bash
   python task2/src/task2.py
   ```


## Тестирование
Для запуска тестов выполните:
```bash
    python -m unittest -v lab4.task2.tests.test_4_2.py
```