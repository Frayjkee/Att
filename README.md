# Att

Конечная задача заключается в написании программы на Python, которая принимает массив строк и возвращает новый массив, содержащий только те строки, длина которых меньше или равна 3 символам. Важно решить эту задачу, используя только массивы без использования коллекций.

Для этого нам понадобятся две функции:

Функция filter_short_strings(arr): Принимает массив строк arr и возвращает новый массив, содержащий только строки длиной не более 3 символов.
Функция main(): Используется для ввода массива строк с клавиатуры, вызова функции filter_short_strings и вывода результата.
Программа начинается с вызова функции main(), которая:

Запрашивает у пользователя ввод массива строк через пробел.
Разбивает введенную строку на отдельные элементы массива с помощью метода split().
Вызывает функцию filter_short_strings для обработки введенного массива.
Выводит результат в консоль.
Функция filter_short_strings(arr) перебирает каждую строку во входном массиве arr и добавляет её в новый массив result, если её длина не превышает 3 символа. После обработки всех строк возвращается полученный массив result.

Таким образом, решение задачи основано на простых итерациях по элементам массива строк и фильтрации по длине строки без использования встроенных коллекций Python, таких как списки или словари.





