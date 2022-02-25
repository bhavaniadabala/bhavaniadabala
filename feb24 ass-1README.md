my_list=[1,4,67,89,34,56,2,6,7]
 prime=[]
 for i in my_list:
 c=0
 for j in range(1,i): 
if i%j==0:
 c+=1
 if c==1: 
prime.append(i)
 print(prime)
 
 OUTPUT: [67, 89, 2, 7]
Show quoted text
