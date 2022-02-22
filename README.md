# Итоговая проверочная работа.

Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе разработчик. Мы должны убедиться что базовое знакомство с it прошло успешно.

Задача алгоритмически не самая сложная, однако для полценного выполнения проверочной работы необходимо:
1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах)

Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []


---
## Выполнение задания

1. Задаем исходный массив строк, который необходимо подвергнуть анализу.(arrayStrings)
2. Созданием метод печати массива в консоль.
    + указываем тип метода (void)
    + указываем тип аргумента метода (stringArray)
    + выводим массив при помощи цикла for на консоль.
3. Создаем метод для подсчета элементов для нового массива.
    + указываем тип метода (int)
    + указываем тип аргумента метода (stringArray)
    + перебираем массив при помощи цикла for и подсчитываем элементы    содержащие менее 4 символов.
    + возвращаем коллчичество элементов соответствующих условию
4. Создаем метод для создания сортированного массива в соответсвии с условием (элементы массива содержат менее 4х символов)
    + указываем тип метода (string[])
    + указываем тип аргументов метода (string[], int arraylenght)
    + создаем новый массив длинной arraylenght
    + перебираем массив при помощи цикла for и записываем в новый массив элементы, которые соответсвуют условию (длинна элемента <4)
    + возвращаем новый массив.
5. Используя ранее созданный метод (пункт2) выводим на консоль новый массив.

## результаты работы программы
    Исходные данные:
    ["Russia", "Denmark", "Kazan", Ufa]
    Рeзультат сортировки:
    [Ufa]
