def square(x):
    return x**2

numbers = {'a': 1, 'b': 2, 'c': 3}
squared_numbers = {key: square(value) for key, value in numbers.items()}
print(squared_numbers)






my_dict = {'a': 1, 'b': 2, 'c': 3}
print(my_dict.keys())






def multiply_by_ten(item):
    key, value = item
    return key, value * 10

data = {'x': 5, 'y': 8, 'z': 2}
multiplied_data = dict(map(multiply_by_ten, data.items()))
print(multiplied_data)








my_dict = {'a': 1, 'b': 2, 'c': 3}
print(my_dict.items())





dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}
dict1.update(dict2)
print(dict1)




my_dict = {'a': 1, 'b': 2, 'c': 3}
my_dict.clear()
print(my_dict)





my_dict = {'a': 1, 'b': 2}
new_dict = my_dict.copy()
print(new_dict)




keys = ['x', 'y', 'z']
new_dict = dict.fromkeys(keys, 0)
print(new_dict)





my_dict = {'a': 1, 'b': 2}
value = my_dict.setdefault('a', 0)
print(value)
print(my_dict)
value = my_dict.setdefault('c', 3)
print(value)
print(my_dict)






alien_0 = {'color': 'green'}
print(f"The Alien is {alien_0['color']}")
alien_0['color'] = 'yellow'
print(f"The alien is now {alien_0['color']}.")
