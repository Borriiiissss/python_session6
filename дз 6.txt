# Напишите программу, которая найдёт произведение пар чисел списка. 

# import math
# import random
# multiple = 0
# list = [random.randint(1, 100) for item in range (10)]    # List Comprehension
# print (list)
# for i in range(math.ceil(len(list)/2)):
#     multiple = list[i] * list[(-i)-1]
#     print(f'{list[i]} * {list[-i-1]} = {multiple}')


# Задайте список из вещественных чисел. Напишите программу, которая найдёт разницу
# между максимальным и минимальным значением дробной части элементов.
# Пример:
# - [1.1, 1.2, 3.1, 10.01] => 0.19

# import random
# lst = [random.uniform(1.99, 100.99) for item in range (5)]
# min = lst[0] % 1
# max = lst[0] % 1
# for i in lst:
#     item = i % 1    
#     if item < min: min = item
#     if item > max: max = item
# print ('{} min = {} max = {} => {}'.format(lst, round(min,2), round(max,2), round(max - min, 2)))