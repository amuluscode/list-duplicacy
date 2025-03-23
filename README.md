# list-duplicacy
code for reducing duplicacy in list in python
a= [1,2,3,4,5,4,5,6,5,5,3]
b=a.copy()
 for j in b:
     for i in a:
       if i==j:
         c=a.count(j)
         if c>1:
             a.remove(i)
print(a)
