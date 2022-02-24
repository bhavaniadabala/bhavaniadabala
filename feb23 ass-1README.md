l=[]
n=int(input('enter n:'))
for i in range(n):
    e=int(input())
    l.append(e)
min=l[0]
for i in range(1,n):
    if l[i]<min:
        min=l[i]
print(min)
max=l[0]
for i in range(1,n):
    if l[i]>max:
        max=l[i]
print(max)

output:
enter n:5
25
50
-20
-25
64
-25
64
