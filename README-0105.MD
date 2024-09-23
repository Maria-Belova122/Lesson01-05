# Задание по теме "Неизменяемые и изменяемые объекты. Кортежи и списки"
immutable_var = (1, 2.5, 'apple', [7, 8, 9])            # Кортеж
print(immutable_var)
mutable_list = [1, 2.5, 'apple', 'melon', ('c', 'd')]   # Список
print(mutable_list)
mutable_list[0] = 10.0
mutable_list[1] = 6
mutable_list[3] = 'peach'
mutable_list[-1] = 'melon'
print(mutable_list)