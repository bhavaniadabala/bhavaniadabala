n=int(input('enter number:'))
even_sum=0
odd_sum=0

for i in range(1,n+1):
   if(i%2==0):
      even_sum=even_sum+i
   else:
      odd_sum=odd_sum+i

print('The sum of the even numbers is:',even_sum)

print('The sum of the odd numbers is:',odd_sum)

output:
enter number:
100
the sum of the even numbers is:2550
the sum of the odd numbers is:2500
