n=int(input())
for i in range(1,n+1):
    if i<=n//2:
        for j in range(0,n-i):
            print(' ',end="")
        for k in range(i):
            print("*",end="")
        for u in range(i-1):
            print("*",end="")
        print()
    else:
        for j in range(0,i-1):
            print(' ',end="")
        for k in range(n-i+1):
            print("*",end="")
        for u in range(n-i):
            print("*",end="")
        print() 

