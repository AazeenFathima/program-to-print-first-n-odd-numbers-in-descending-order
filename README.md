# program-to-print-first-n-odd-numbers-in-descending-order

n = int(input("Enter the Limit: "))

if n % 2 == 0:
    # If n is even, start from n-1 to get the largest odd number ≤ n
    for i in range(n - 1, 0, -2):
        print(i)
else:
    # If n is odd, start from n itself
    for i in range(n, 0, -2):
        print(i)

OUTPUT :
Enter the Limit: 10
9
7
5
3
1
