0x02. Minimum Operations
 By Carrie Ybay, Software Engineer at Holberton School
 Weight: 1
 Project over - took place from 07-26-2021 to 07-30-2021 - you're done with 0% of tasks.
 QA review fully automated.
In a nutshell…
Auto QA review: 0.0/12 mandatory
Altogether:  0.0%
Mandatory: 0.0%
Optional: no optional tasks
 linear time python

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should be documented
Your code should use the PEP 8 style (version 1.7.x)
All your files must be executable
## Tasks {.gap}
```
### 0. Minimum Operations
mandatory
Score: 0.00% (Checks completed: 0.00%)
In a text file, there is a single character H. Your text editor can execute only two operations in this file: Copy All and Paste. Given a number n, write a method that calculates the fewest number of operations needed to result in exactly n H characters in the file.

Prototype: def minOperations(n)
Returns an integer
If n is impossible to achieve, return 0
Example:

n = 9

H => Copy All => Paste => HH => Paste =>HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6
```

```
carrie@ubuntu:~/0x02-minoperations$ cat 0-main.py
#!/usr/bin/python3
"""
Main file for testing
"""

minOperations = __import__('0-minoperations').minOperations

n = 4
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))

n = 12
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))
````
```
carrie@ubuntu:~/0x02-minoperations$
carrie@ubuntu:~/0x02-minoperations$ ./0-main.py
Min number of operations to reach 4 characters: 4
Min number of operations to reach 12 characters: 7
carrie@ubuntu:~/0x02-minoperations$
```
Repo:

GitHub repository: alx-interview
Directory: 0x02-minimum_operations
File: 0-minoperations.py
    
