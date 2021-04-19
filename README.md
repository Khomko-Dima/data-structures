# Связный список (связанный, список узлов и ссылок или указателей) (Linked List)

Буквально, связный список — это цепочечная структура данных, где каждый узел состоит из двух частей: данных узла и указателя на следующий узел. Связный список и условный массив являются линейными структурами данных с сериализованным хранилищем. Отличия состоят в следующем:

|Критерий   | Массив  | Список  |
| ------------ | ------------ | ------------ |
| Выделение памяти | Статическое, происходит последовательно во время компиляции  |  Динамическое, происходит асинхронно во время запуска (выполнения |
| Получение элементов  | Поиск по индексу, высокая скорость  | Поиск по всем узлам очереди, скорость менее высокая  |
| Добавление/удаление элементов  | В связи с последовательным и статическим распределением памяти скорость ниже  | В связи с динамическим распределением памяти скорость выше  |
|  Структура | Одно или несколько направлений  | Однонаправленный, двунаправленный или циклический  |

------------

# Быстрая сортировка (Quicksort)
Существует две базовые операции в алгоритме: замена элемента на месте и разбиение массива на части. Основные шаги для разделения массива:
1. Найти опорный элемент в массиве. Этот элемент — основа для сравнения за одни проход.
2. Установить указатель (левый указатель) с первого элемента в массиве.
3. Установить указатель (правый указатель) с последнего элемента в массиве.
4. Пока значение левого указателя в массиве меньше, чем значение опорного элемента, сдвигать левый указатель вправо (добавить 1). Продолжить пока значение левого указателя не станет большим или равным опорному.
5. Пока значение правого указателя в массиве больше, чем значение опорного элемента, сдвигать правый указатель влево (вычитать 1). Продолжать пока значение правого указателя не станет меньшим или равным значению разделителя.
6. Если левый указатель меньше или равен правому указателю, поменять значения в этих местах в массиве.
7. Сдвинуть левый указатель вправо на одну позицию и правый указатель на одну позицию влево.
8. Если левый указатель и правый указатель не встретятся, перейти к шагу 1.


------------
# Бинарный поиск (BinarySearch)
Бинарный поиск выполняется путем проверки того, является ли искомое значение больше, меньше или равно среднему значению в нашем массиве:

- Если оно меньше, мы можем удалить правую половину массива.
- Если оно больше, мы можем удалить левую половину массива.
- Если оно равно, мы возвращаем значение

------------
