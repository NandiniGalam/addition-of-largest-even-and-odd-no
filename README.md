# addition-of-largest-even-and-odd
n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in range(n):
  if a[i]%2==0 and a[i]>e:
    e=a[i]
  elif a[i]>o :
    o=a[i]
print(e+o)

#largest even and odd addition without using range
n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in a:
  if i%2==0 and i>e:
    e=i
  elif i>o :
    o=i
print(e+o)
