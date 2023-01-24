# Задача

1. Создать **репозиторий** на GitHub
2. Нарисовать **блок-схему** алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным *текстовым описанием* решения (файл README.md)
4. Написать **программу**, решающую поставленную задачу
5. Использовать **контроль версий** в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

**Задача**: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

# Решение
1. Репозиторий создан.
2. Блок-схема в файле "Final_task_block_diagram" - файл drawio и скрин картинка.
3. Текстовое описание решения: принимаем на вход два строчных массива. Длину первого задаем в программе (=6 словам), длина второго = длине первого.
Затем используем два метода типа void. 
**Первый метод** в рамках цикла (CheckInitialArray) проверяет длину слов в первом массиве и, если она <=3, то записывает слово во второй массив, переходя далее к следующему элементу второго массива, а затем переходит ко второму слову (i+1) в первом массиве. **Второй метод** (ShowArray) выводит массив на экран, проверяя его на количество символов (<array.Length) в рамках цикла. 
*Вне методов*: создание первого массива, как упоминалось ранее и приравнивание второго массива к первому, затем вызов метода Check и Show для обоих массивов.

4. Программа написана в файле Program.cs
5. Контроль версий применен, сделано множество коммитов.


