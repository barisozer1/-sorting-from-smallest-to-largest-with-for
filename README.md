list1 = [1,4,2,6,84,642,4578,1234,324,1234,1234,526]
list2 = []
list1 = list(set(list1))
a = 0
for i in list1:
    if i > a:
        a =i
for i in range(a+1):
    if i in list1:
        list2.append(i)
print(list2)
