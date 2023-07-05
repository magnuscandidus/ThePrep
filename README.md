# ThePrep
# cook your dish here
t=int(input())
while t:
    m,n,k=map(int,input().split())
    if(m>(n*k)):
        print("YES")
    else:
        print("NO")
    t-=1
    
