# ИТОГОВАЯ ПРОВЕРОЧНАЯ РАБОТА

Для полноценного выполнения проверочной работы необходимо:

1. Создать репозиторий на GitHub.
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод).
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md).
4. Написать программу, решающую поставленную задачу.
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что все залито одним коммитом, как минимум этапы 2,3 и 4 должны быть расположены в разных коммитах).

## Задача

Написать програму, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание алгоритма решения:

Объявлено два массива: 
* изначальный;
* вторый такой же длины, который покажет конечный результат.

 Потом используется метод, в котором цикл соразмерный длине массива. Внутри цикла указано условие ( <=3 ), если условие выполняется, то элемент первого массива заносится в переменную count второго массива. После занесения каждого элемента в переменную count, данная переменная увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца. Далее используется метод PrintArray и выводит в терминал конечный результат.

Графическое представление метода в папке Schem в двух файлах разных расширениях.


