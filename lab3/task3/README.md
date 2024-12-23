# Задание №3 по выбору  : `Сортировка пугалом`
Студентка ИТМО,  Трусова Светлана Викторовна 467766

## Вариант 22
«Сортировка пугалом» — это давно забытая народная потешка. Участнику
под верхнюю одежду продевают деревянную палку, так что у него оказываются
растопырены руки, как у огородного пугала. Перед ним ставятся n матрёшек в
ряд. Из-за палки единственное, что он может сделать — это взять в руки две
матрешки на расстоянии k друг от друга (то есть i-ую и i + k-ую), развернуться и
поставить их обратно в ряд, таким образом поменяв их местами.
Задача участника — расположить матрёшки по неубыванию размера. Может
ли он это сделать?

## Input / Output

| Input          | Output |
|----------------|--------|
| 3 2            | НЕТ    |
| 2 1 3          |        |
| -----          | ------ |
| 5 3            | ДА     |   
| 1 5 3 4 1      |        |


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
   python task3/src/task3.py
   ```


## Тестирование
Для запуска тестов выполните:
```bash
    python -m unittest -v lab3.task3.tests.test_3_3.py
```