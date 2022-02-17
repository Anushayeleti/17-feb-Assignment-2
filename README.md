Number = int(input("Enter the Fibonacci Number Range = "))

First = 0
Second = 1
Sum = 0

for Num in range(0, Number):
    print(First, end = '  ')
    Sum = Sum + First
    Next = First + Second
    First = Second
    Second = Next

print("\nThe Sum of Fibonacci Series Numbers = %d" %Sum)

output:Enter the Fibonacci Number Range = 9
       0 1 1 2 3 5 8 13 21
       The Sum of Fibonacci Series Numbers = 54
