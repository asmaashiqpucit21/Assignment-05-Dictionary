# Assignment 05: -

### 1.  "Create an empty dictionary and print it."


```python
empty_dictionary = {}
print(empty_dictionary)


```

    {}
    




    Dictionary



 ### 2.   "Create a dictionary representing a person with keys such as 'name', 'age', and 'city'."
   

```python
person_dictionary = {
	    'name': 'Ahmer',
	    'age': 25,
	    'city': 'Lahore'
}
print(person_dictionary)

```

   {'name': 'Ahmer', 'age': 25, 'city': 'Lahore'}




    dictionary



### 3.  "Create a dictionary that includes keys with different data types (strings, integers)."
   

```python
diff_data_types = {
	    'string': 'GIS & RS',
	    'integer': 25,
}
print(diff_data_types)

```

    {'string': 'GIS & RS', 'integer': 25}
    




    dictionary



### 4. "Access and print the value associated with a specific key."
   

```python
	mixed_dict = {
	'name': 'Ahmer',
	'age': 25,
	'city': 'karachi',
	'is_student': True,
	'grades': [90, 85, 92]
}
print(mixed_dict)
```

    {'name': 'Ahmer', 'age': 25, 'city': 'karachi', 'is_student': True, 'grades': [90, 85, 92]}

    

### 5.   "Use the get() method to access a value, providing a default value if the key is not present."
 

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
apple_count = my_dict.get('apple', 0)
print(apple_count)
grape_count = my_dict.get('grape', 0)
print(grape_count)
```



    apple: 3
    grape: 0




### 6.  "Iterate through the keys of a dictionary and print each key."
  


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
for key in my_dict.keys():
print(key)
```

    apple
    banana
    orange
    

### 7. "Add a new key-value pair to a dictionary."


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
my_dict['grape'] = 4
print(my_dict)
```
   
    {'apple': 3, 'banana': 2, 'orange': 5, 'grape': 4}



### 8.  "Modify the value associated with an existing key."


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
my_dict['banana'] = 7
print(my_dict)
```

    {'apple': 3, 'banana': 7, 'orange': 5}
    

### 9. "Remove a specific key-value pair from a dictionary using the pop() method.\n",
    
   

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
removed_value = my_dict.pop('banana')
print(removed_value)
```

    removed_value = 2
    

### 10.   "Remove a specific key-value pair from a dictionary using the del statement."
   
```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
del my_dict['banana']
print(my_dict)
```

    {'apple': 3, 'orange': 5}
    

### 11. "Convert a dictionary to a list of keys."
   


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
keys_list = list(my_dict.keys())
print(keys_list)
```

    ['apple', 'banana', 'orange']
    

### 12.   "Convert a dictionary to a list of values."
  

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
	values_list = list(my_dict.values())
	print(values_list)
```

    [3, 2, 5]
    

### 13.   "Convert a list of tuples to a dictionary."


```python
list_of_tuples = [('apple', 3), ('banana', 2), ('orange', 5)]
	my_dict = dict(list_of_tuples)
	print(my_dict)
```

    {'apple': 3, 'banana': 2, 'orange': 5}
    

### 14.   "Use the keys() method to get a list of keys in a dictionary."
   

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
	keys_list = list(my_dict.keys())
	print(keys_list)

```

    ['apple', 'banana', 'orange']
    

### 15.   "Use the values() method to get a list of values in a dictionary."
   


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
       values_list = list(my_dict.values())
       print(values_list)


```

    [3, 2, 5]

### 16.   "Use the items() method to get a list of key-value pairs in a dictionary."
 


```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
     items_list = list(my_dict.items())
     print(items_list)


```

    [('apple', 3), ('banana', 2), ('orange', 5)]
    

### 17.   "Check if a key is present in a dictionary using the in operator."
   

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
	key_to_check = 'banana'
	if key_to_check in my_dict:
	    print(key_to_check)
```

    
    banana


### 18.  "Use the setdefault() method to add a key with a default value if it doesn't exist."

   

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
my_dict.setdefault('grape', 0)
print(my_dict)
```

    {'apple': 3, 'banana': 2, 'orange': 5, 'grape': 0}
    

### 19.  "Merge two dictionaries using the update() method."

   

```python
dict1 = {'apple': 3, 'banana': 2, 'orange': 5}
dict2 = {'grape': 4, 'kiwi': 1, 'banana': 3}
dict1.update(dict2)
print(dict1)

```

    {'apple': 3, 'banana': 3, 'orange': 5, 'grape': 4, 'kiwi': 1}
   

### 20.  "Use the clear() method to remove all elements from a dictionary."
  

```python
my_dict = {'apple': 3, 'banana': 2, 'orange': 5}
	my_dict.clear()
	print(my_dict)
```

   {}