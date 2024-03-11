# python-dictionary
# approach1
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
print(d)

# approach2
d={10:100,20:200,30:300}
for i in d:
  print(i)
for i in d:  
  print(d[i])

# approach3
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
for i in d:
  print(f"{i}->{d[i]}")

# approach4
# addition of values in dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=0
for i in d:
  res=res+d[i]
print(res)

# approach5
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=d.values()
print(sum(res))

# approch6 sum of keys
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=0
for i in d:
  res=res+i
print(res)

# approch7 sum of keys&values
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=0
for i in d:
  res=res+i+d[i]
print(res)

# approch8
# using built-in-methods(. methods)&built-in-function(sum)
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res1=d.values()
res2=d.keys()
print(sum(res1)+sum(res2))
