PROGRAMME:
s=input()
l=list(s)
e=[]
o=[]
res=[]
for i in l:
    i=int(i)
    if i%2!=0:
        o.append(i)
    else:
        e.append(i)
res=o,e
for i in res:
    print(i,end=' ')
OUTPUT:
1243536
[1, 3, 5, 3] [2, 4, 6] 
