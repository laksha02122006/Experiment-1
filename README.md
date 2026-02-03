### NAME: V.B.LAKSHA

REG NO: 212224220051

##  Write programs in Python Language to demonstrate the working of
following constructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
### 1) DO WHILE
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
### OUTPUT
<img width="926" height="46" alt="do while exp 1 st" src="https://github.com/user-attachments/assets/eab03846-f3d1-42eb-a196-44c42f68fbdc" />

### 2) WHILE DO
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
### OUTPUT
<img width="927" height="87" alt="while do exp1 st" src="https://github.com/user-attachments/assets/43f98db4-2d53-4e84-9fed-ff28648aca20" />

### 3) IF ELSE
```

def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
```
### OUTPUT 

<img width="923" height="46" alt="if else exp1 st" src="https://github.com/user-attachments/assets/b361d931-e32d-4e00-9034-9bd5b76ab264" />

### 4)SWITCH
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
### OUTPUT

<img width="1844" height="68" alt="Screenshot 2025-08-28 154649" src="https://github.com/user-attachments/assets/5a5ce26a-39f5-430a-adb2-23674930a810" />

### 5) FOR
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
### OUTPUT


<img width="925" height="60" alt="for exp1 st" src="https://github.com/user-attachments/assets/a99a5c6e-e5d9-4fe3-9834-ba52ccc76a78" />


## Result
Successfully find the  output of python programs for do…while, while, for, switch and if…else .
