# Attestation1

# Решение задачи
Код состоит из двух фунций: **finish** и **PrintArray**.
## Функция *finish*
 Функция принимает массив строк `(string[] strings)` в качестве исходных данных. Она создает новый массив строк `(string[] new_arr)` той же длины, что и исходный массив. После чего проходит по каждому элементу  массива. Если длина текущей строки меньше или равна 3, эта строка добавляется в новый массив. В конце функция возвращает новый массив. 
## Функция *PrintArray*
Эта функция принимает массив строк `(string[] arr)` в качестве входных данных. Она проходит по каждому элементу массива и выводит его на консоль. Элементы разделяются пробелом.
## Использование 
Код создает массив строк, затем использует функцию `PrintArray` для вывода всех элементов массива. Затем он вызывает функцию `finish`, чтобы получить новый массив, содержащий только те строки, длина которых меньше или равна 3. Этот новый массив выводится с помощью функции `PrintArray`.