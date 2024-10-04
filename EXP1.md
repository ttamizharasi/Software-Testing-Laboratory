## Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212222040170

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
i.)do…while:
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Please enter valid positive numbers.")

display()
```
ii.) while…do:
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
    print("Enter a valid positive number.")
```
iii.) switch:
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
iv.) if else:
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
v.) for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```

### Output:
![do while](https://github.com/user-attachments/assets/f3b65032-d4d6-47fd-b930-d72e2a84ac84)

![while do](https://github.com/user-attachments/assets/020a5dce-4938-4edc-8c88-a091e17720a4)

![switch](https://github.com/user-attachments/assets/f3d3a629-748b-40b7-9cb2-dfabd2012cfb)

![if else](https://github.com/user-attachments/assets/05f77ea5-958a-483e-a15d-2c4b31378b37)

![for](https://github.com/user-attachments/assets/f925a212-1f1a-4aaf-b02e-d1a2b1bc6dbf)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


