# Лабораторная работа №5 СПП

Создать на языке C# пользовательский атрибут с именем ExportClass, применимый только к классам, и реализовать консольную программу, которая:

- принимает в параметре командной строки путь к сборке .NET (EXE- или DLL-файлу);
- загружает указанную сборку в память;
- выводит на экран полные имена всех public-типов данных этой сборки, помеченные атрибутом ExportClass.

Создать на языке C# обобщенный (generic-) класс DynamicList<T>, который:

- реализует динамический массив с помощью обычного массива T[];
- имеет свойство Count, показывающее количество элементов;
- имеет свойство Items для доступа к элементам по индексу;
- имеет методы Add, Remove, RemoveAt, Clear для соответственно добавления, удаления, удаления по индексу и удаления всех элементов;
- реализует интерфейс IEnumerable<T>.
- реализовать простейший пример использования класса DynamicList<T> на языке C#.