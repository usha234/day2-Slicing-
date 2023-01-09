# day2-Slicing-
fav_pizza=['vegpizza','chickenpizza','periperipizza']
print(fav_pizza)
frn_pizza=fav_pizza[:]
fav_pizza.append('chillipizza')
frn_pizza.append('pepporonipizza')
print('my favourite pizzas are')
for i in fav_pizza:
    print(i)
print('My friend favourite pizzas are') 
for i in frn_pizza:
    print(i)   


ai=['supervised','unsupervised','reinforcement','clustering','classification','regression','dbscan','kmeans','svm','logistic']
print("the first three algorithms are:",ai[0:3])
print("the algorithms from the middle of the ai list:",ai[3:6])
print("the last three algorithms are:",ai[6:9])
for i in range(1,21):
    print(i)

numbers=list(range(1,1000001))
s=0
for i in numbers:
    s=s+i
print(s)
print(min(numbers))
print(max(numbers))

odd=list(range(1,21))
print('the odd numbers are:',odd[0:21:2])

b=[]
for i in range(1,11):
    a=3*i
    b.append(a)
print(b)
d=[]
for i in range(1,11):
    c=i**3
    d.append(c)
print(d)

cubes=[e**3 for e in range(1,11)]
print(cubes)


