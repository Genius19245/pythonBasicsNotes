# Dictionaries

<mark style="color:$danger;">Key</mark> <mark style="color:$success;">value</mark> pairs, where key is the identifies for the data and the value is the catual data

```python
student = {'name':'Jason', 'age':25}
print(student)
```

```python
print(student["name"])
#gives the data of the value stored for the specific key,
```

These keys are normally strings, but can be integers

```python
print(student.get("name"))
# If data is found value is returned, otherwise none is outputted
```

```python
student["age"] = 35
print(student)
```

This can be used to manually changes the data stored in the value, if the key isn't given a new key with the corresponding data is added to the dictionary as a new key value pair

```python
student.update({"name":"Jason", "age":25})
```

Can be used to update a value in the dictionary and takes a emplt dictionary as an argument, and can be used to add a new key value pair

```python
del student["name"]
print(student)
```

The <mark style="color:green;">del</mark> keyword can be used to delete a key value pair from the dictionary



```python
student.pop("name")
print(student)
```

Remove the key value pair as well as returning the value stored if needed to a variable

```python
student.keys()
student.values()
student.items()
```

items is for both keys and pairs

```python
for key in student.items():
    print(key)
```

To loop through both key and values

