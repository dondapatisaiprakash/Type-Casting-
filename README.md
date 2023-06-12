#type casting
# int to float
x = 9
y = float(x)
print(y)  
# int to string
x = 5
y = str(x)
print(y)  
# float to int
x = 3.4
y = int(x)
print(y)  
# float to string
x = 3.4
y = str(x)
print(y)  
# string to int
x = "34"
y = int(x)
print(y)  
# string to float
x = "9.5"
y = float(x)
print(y)  
# string to tuple
x = "1, 2, 3"
y = tuple(map(int, x.split(', ')))
print(y)  
# string to dict
x = '{"name": "sai", "age": 24}'
y = eval(x)
print(y)  
# string to char
x = "H"
y = ord(x)
print(y) 
# tuple to dict
x = ((1, "one"), (2, "two"), (3, "three"))
y = dict(x)
print(y) 
# dict to string
x = {1: 'one', 2: 'two', 3: 'three'}
y = str(x)
print(y)
