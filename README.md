# First Task

**1. make sure Python & Pip are installed by typing in the terminal:**
```bash
$ python
$ pip
```
**or**
```bash
$ python3
$ pip3
```
**If not installed then install Python & Pip first**

**2. Creat a python script:**

``` python
from random import randint

for _ in range(0, 10):
    value = randint(1, 10)
    print(value)
```
This is a for loop function that uses a range between 0 to 10 and then print a random 10 numbers between 1 to 10 

**3. Save the file as "random_number.py":**

**4. Open the terminal and navigate to the directory where the file located then run the python file using the following command:**

    $ python random_number.py

**4. Output should be a random 10 numbers as shown but it is changing each time you run the file:**

```bash
6
3
10
8
3
3
7
3
5
4
```