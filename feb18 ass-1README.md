start_val = 1
n = int(input("Enter the n number:"))
for num in range(start_val, n+1):
    if(num>1):
        for i in range(2,num):
            if(num%i)==0:
                break
        else:
            print(num)
   
  output:
  
Enter the n number:
20
2
3
5
7
11
13
17
19
