a=[45,36,54,27,63,72,61,18]
heap=list()
heap.append(a[0])
n=1
pos=n
while(n!=len(a)):
    heap.append(a[n])
    pos=n
    par=(n-1)//2
    #print("before",heap,pos,par)
    while(par>-1 and heap[par]<heap[pos]):
        swap=heap[par]
        heap[par]=heap[pos]
        heap[pos]=swap
    #    print("middle",heap)
        pos=par
        par=(par-1)//2
    #    print(pos,par)
    n=n+1

print(heap)
