# Day7_Non-adjacent-sum
a=list(map(int,input().strip().split()))
it1=0
it2=0
for i in a:
    n=max(it1,it2)
    it1=it2+i
    it2=n
print(max(it1,it2))
        
