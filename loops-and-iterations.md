# Loops and Iterations

```python
numbers = [1,2,3,4,5,6,7,8,9]
for num in numbers:
    print(num)
```

Used to every item is a list , or list of characters, used when the items in the list is sorted

```python
numbers = [1,2,3,4,5,6,7,8,9]
for num in numbers:
    for character in "abc":
        print(num,character)
```

You can have nested for loops by which the inside can repeat over if its length is shorter than one outside the nestation&#x20;

```python
for i in range(10):
    print(i)
    
# Can be used to loop a list a set number of times 
```

The <mark style="color:cyan;">break</mark> keyword can be used to completley  stop the loop and move on to the next instruction after the loop

While the <mark style="color:$warning;">continue</mark> keyword is used to move on to the next iteration of the loop

```python

for i in range(10):
    print(i)

# Can be used to loop a list a set number of times
for i in range(0,10,2):
    print(i)
# The first argument takes in the inclusive number, the second is where to stop however it is exclusive and the last argument takes in the step
```

```python
x = 0
while x < 10:
    print(x)


while True:
    print("hahahahahahahah")
    break
#Here this create an infinite loop however, the break keyword is the only way to exit the infinite loop
```

use <mark style="color:purple;">cntrl c</mark> to get out of the infinite loop
