# python-11
Write a python program to print first n odd numbers in descending order.
n=int(input("Enter the limit:"))
if n%2==0:
    for i in range(n-1,0,-2):
        print(i)
    else:
        for i in range(n,0,-2):
            print(i)
Output
Enter the limit:20
19
17
15
13
11
9
7
5
3
1
20
18
16
14
12
10
8
6
4
2

    
