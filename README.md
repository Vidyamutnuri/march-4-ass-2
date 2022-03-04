# march-4-ass-2
Assignment-2
n=int(input())
l=input().split()
print(l)
t=[]
for i in l:
    t.append([i])
print(t)
x=[]
for i in t:
    if i not in x:
        x.append(i)
print(x)
x.sort(reverse=True)
print(x)
print(x[2])
