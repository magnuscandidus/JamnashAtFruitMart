# JamnashAtFruitMart
for i in range(int(input())):
    x,a,b,c=map(int,input().split())
    m1=min(a,b,c)
    m2=max(a,b,c)
    print((x-1)*m1 + (a+b+c-m1-m2))
