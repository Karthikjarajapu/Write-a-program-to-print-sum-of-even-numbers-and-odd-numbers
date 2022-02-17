# Write-a-program-to-print-sum-of-even-numbers-and-odd-numbers
n=int(input('enter numb:'))
sum=0 
for i in range (1,n+1):
if i%2==1: 
sum=sum+i 
print(sum) 
if i%2==0:
sum=sum+i 
print(sum)
