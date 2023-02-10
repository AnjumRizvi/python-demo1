# python-demo1

list1 = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
list2 = []
num1 = len(list1)
print("Number of items in the original lists are:", num1)
i=0
j=0

while i <= num1:
    if list1[j] <= 5:
        list2.insert(j,list1[j])
        print(list2)
        j += 1
    else:
        i += 1
print(“number of items that are less than5 are:”, list2
