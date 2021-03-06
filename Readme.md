# Основы С++. Лабораторная работа 1 (Одномерные массивы)

## Содержение
1. [Описание задания](#Описание-лабораторной)
2. [Спецификация](#Спецификация)

## Описание лабораторной

### Задание 1.

Одномерный массив, состоящий из `N` целых чисел, преобразовать таким образом, чтобы сначала располагались все отрицательные элементы, а потом - все неотрицательные.

### Задание 2.

Объединить две строки `p` и `q` по правилу: `p[0], q[0], p[1], q[1], ….` Строки могут иметь разную длину.

## Спецификация

**Примечание 1.** Считывание происходит из файла.\
**Примечание 2.** Первая цифра спецификации позывает номер задания

| № | Входные данные (формальное описание) | Результат |
|---|---|---|
| 1.1.1 | Префикс файла задан не целым числом. | ```File prefix must be integer. Program is closing.``` |
| 1.1.2 | Файла с заданным префиксом не существует | ```couldn't find file "<_prefix_>inputTask1.txt". Program is clоsing.``` |
| 1.2.1 | Файл пуст | ``` File is empty. File "<_prefix_>inputTask1.txt" maybe is corrupted Program is closing.  ``` |
| 1.2.2 | Количество элементов массива не соответствует её размеру | ```Values must beintegers File "<_prefix_>inputTask1.txt " maybe is corrupted Program is closing. ``` |
| 1.3.1 | Размеры массива заданы не целыми числами | ```Array's length must be positive integer. Program is closing.``` |
| 1.3.2 | Значения массива заданы не целыми числами | ```Array's values must be integers. Program is closing.``` |
| 2.1.1 | Префикс файла задан не целым числом. | ```Program is closing...``` |
| 2.1.2 | Файла с заданным префиксом не существует | ```File doesn't exist. Program is clоsing``` |
| 2.2.1 | Файл пуст | ```File is empty. Program is closing...``` |
| 2.3.1 | Файл содержит только одну строку. | ```File must contain two strings. Program is closing.``` |

