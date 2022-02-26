l=[]
p=[]
n=[]
num=int(input('enter the number'))
for i in range(1,num+1):
    x=int(input())
    l.append(x)
for j in range(num):
    if(l[j]>=0):
        p.append(l[j])
    else:
        n.append(l[j])
print('positive list:',p)
print('negative list:',n)

enter the number5
-25
48
-35
58
15
positive list: [48, 58, 15]
negative list: [-25, -35]
