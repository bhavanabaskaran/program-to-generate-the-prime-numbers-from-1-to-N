# program-to-generate-the-prime-numbers-from-1-to-N
num =int(input(&quot;Enter the range: &quot;))
for n in range(1,num):
for i in range(2,n):
if(n%i==0):
break

else:
print(n)
