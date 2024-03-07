#Approach-1
n=int(input())
a=list(map(int,input().split()))
res=0
r=0
for i in range(n):
  if a[i]%2==0 and a[i]>res: 
    res=res+a[i]
    r=r+1
print(res//r)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
res=0
r=0
for i in a:
  if i%2==0 and i>res: 
    res=res+i
    r=r+1
print(res//r)

#Approach-3
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in range(n):
  if a[i]%2==0 :
    e.append(a[i])
print(sum(e)//len(e))

#Approach-4
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in a:
  if i%2==0 :
    e.append(i)
print(sum(e)//len(e))
