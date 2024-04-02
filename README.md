# Лабораторная работа №6. Взаимодействие с переменными и преобразование типов данных.
    
    ## Практическое задание
    1.  Проверка на четность/нечетность: Запросите у пользователя целое число и определите, является ли оно четным или нечетным. Выведите соответствующее сообщение.
    2. Поиск максимума: Попросите пользователя ввести три числа. Найдите и выведите максимальное из них, используя условный оператор.
    3. Факториал числа: Запросите у пользователя целое неотрицательное число и вычислите его факториал. Факториал числа n, вычисляется как n! = 1 × 2 × 3 × … × n.
    4. Проверка на простоту: Попросите пользователя ввести целое число больше 1. Определите, является ли это число простым (т.е., делится только на себя и на 1).
    5. Таблица умножения: Выведите таблицу умножения от 1 до 10 для заданного пользователем числа.
    6. Палиндром: Проверьте, является ли введенная пользователем строка палиндромом (читается одинаково как слева направо, так и справа налево, игнорируя пробелы, знаки препинания и регистр).
    7. Подсчет гласных и согласных: Попросите пользователя ввести строку. Посчитайте количество гласных и согласных букв в этой строке.
    8. Сумма элементов списка: Создайте список чисел. Вычислите и выведите сумму всех элементов списка.
    9. Обратный порядок чисел: Запросите у пользователя натуральное число n. Выведите все числа от n до 1 в обратном порядке.
    10. FizzBuzz: Напишите программу, которая выводит числа от 1 до 100. Но для чисел, кратных трём, вместо числа выведите “Fizz”, а для чисел, кратных пяти, выведите “Buzz”. Для чисел, кратных как трём, так и пяти, выведите “FizzBuzz”.


## Ответы на контрольные вопросы
**1. Что из себя представляют ветвления в python, какие конструкции языка используються?**

***Ответ:*** Ветвления в Python представляют собой конструкции, которые позволяют выполнять определенные блоки кода в зависимости от условий. Для ветвлений в Python используются конструкции if, elif и else. Конструкция if проверяет условие и выполняет блок кода, если условие истинно. Конструкция elif (сокращение от "else if") позволяет проверить дополнительные условия, если предыдущие не были выполнены. Конструкция else выполняет блок кода, если все предыдущие условия ложны.

**2. Что из себя представляют циклы в python, какие конструкции языка используються? В чем их отличие?**

***Ответ:*** Циклы в Python представляют собой конструкции, которые позволяют повторять выполнение определенного блока кода. Для циклов в Python используются конструкции for и while. Цикл for используется для перебора элементов в последовательности (например, в списке) или выполнения итераций определенное количество раз. Цикл while выполняет блок кода до тех пор, пока условие истинно. Основное отличие между циклами for и while заключается в том, что цикл for удобнее использовать, когда известно количество итераций, а цикл while - когда условие завершения неизвестно заранее. 

**3. Что из себя представляют списки, кортежи, словари?**

***Ответ:*** Списки, кортежи и словари в Python представляют различные типы коллекций для хранения данных: 
   - Списки (lists) - упорядоченные изменяемые коллекции объектов. Элементы списка могут быть изменены, добавлены или удалены. Список создается с использованием квадратных скобок []. 
   - Кортежи (tuples) - упорядоченные неизменяемые коллекции объектов. Элементы кортежа не могут быть изменены после создания. Кортеж создается с использованием круглых скобок (). 
   - Словари (dictionaries) - неупорядоченные изменяемые коллекции объектов, представленные в форме пар ключ-значение. Ключи уникальны в словаре, а значения могут быть изменены. Словарь создается с использованием фигурных скобок {} и имеет вид {ключ: значение}.