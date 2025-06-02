# 19CS301-Module3
Exp.No:3(a)	STRING
### AIM
To write a python function that accepts a string and removes the nth index value from the string.
### ALGORITHM
Step 1:	 Start the program.

Step 2:	 Define a function remove(s) that takes a string s as input.

Step 3:	 Inside the function, initialize an empty string c to store the result.

Step 4:	 Input an integer n (the index of the character to be removed).

Step 5:	 Loop through each character in the string using index i from 0 to len(s) - 1:

Step 6:	 If i is not equal to n, append s[i] to the string c.

Step 7:	 After the loop, print the string c, which now excludes the character at index n.

Step 8:	 End the function.

### PROGRAM
```
def remove(s):
    c=""
    n=int(input())
    for i in range(len(s)):
        if i!=n:
            c=c+s[i]
    print(c)
```
### OUTPUT
 ![image](https://github.com/23013357/19CS301-Module33/blob/main/pp.png)

### RESULT
Thus the python program of string and remove is implemented and executed successfully.


Exp.No:3(b)	REGEX

### AIM
To write a Python program that matches a string that has an a followed by two to three 'b'.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept a string str1 from the user.

Step 3:	 Define a regular expression pattern as r"[a]+b{2,3}".

Step 4:	 Use the re.match() function to check if the string str1 matches the given pattern. If the string str1 matches the pattern, proceed to step 5. Else If the string str1 does not 
          match the pattern, proceed to step 6.

Step 5:	 Print "Found a match!" if the string matches the pattern.

Step 6:	 Print "Not matched!" if the string does not match the pattern.

Step 7:	 Terminate the program.

### PROGRAM
```import re
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
 ![image](https://github.com/23013357/19CS301-Module33/blob/main/aa.png)

### RESULT
Thus the python program for pattern matching using regular expression was  implemented and executed successfully.

Exp.No:3(c)	LIST

### AIM
To write a python program to display the sum of all the values which are ending with 2 from a list.
### ALGORITHM

Step 1:	 Start the program.

Step 2:	 Input a list of numbers and store it in the variable numbers.

Step 3:	 Initialize a variable sum with 0 to keep track of the total.

Step 4:	 Loop through each number num in the list numbers:

Step 5:	 If num % 10 == 2 (i.e., the number ends with digit 2), then:

Step 6:	 Add num to sum.

Step 7:	 After the loop ends, print the final value of sum.

Step 8:	 End the program.
### PROGRAM
```
numbers=eval(input())
sum=0
for num in numbers:
    if num%10==2:
        sum+=num
print("Sum=",sum)
```
### OUTPUT
 ![image](https://github.com/23013357/19CS301-Module33/blob/main/ss.png)

### RESULT
Thus the python program  display the sum of all the values which are ending with 2 from a list was implemented and executed successfully.

Exp.No:3(d)	TUPLES
### AIM
To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer N from the user.

Step 3:	 Define an empty tuple multiples_of_5.

Step 4:	 Loop through the numbers starting from 5, up to N-1 (not including N), with a step size of 5 For each value of i, add i to the tuple multiples_of_5.

Step 5:	 Return the multiples_of_5 tuple.

Step 6:	 print the resultant tuple.

Step 7:	 Terminate the program.
### PROGRAM
```
def create_tuple(N):
    multiples_of_5 = tuple(i for i in range(5, N, 5))
    return multiples_of_5
N = int(input())
result = create_tuple(N)
print(f"{result}")
```
### OUTPUT
![image](https://github.com/23013357/19CS301-Module33/blob/main/dd.png)


 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.
