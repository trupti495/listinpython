# listinpython
list methods functions
<br>
author-trupti shitole
"""
list is ordered data structure which is used to store hetrogeneous data
it is mutable 
enclosed in square bracket
able to access element using indexing

Implement a python program to perform following 
operations on the List: 
1. Create a List 
2. Access List 
3. Update List 
4. Delete List 

"""
list=[10,20,30,40]
print("first element",list[0])
print("index from 0-2",list[0:3])
print("complete list",list)

print("updating")
list[0]=5
list[1]=15
print("modified list:",list)

list.append(50)
list.remove(30)
print(list)

print("delting list")

del list[0]
print(list)
del list

"""
8 Python program to demonstrate the use of   
built-in functions/methods on List (Any Eight 
Functions/methods) 
"""
print(" methods of list")
list=[10,20,30,40,50]
list1=[10,20,30,40,50]

print("min ",min(list))
print("max",max(list))
print("length",len(list))

print(" count of 10",list.count(10))
list.append("trupti")
print(" append",list)
print("insert",list.insert(1,11))

# pop the last element 
print("pop",list.pop())

# remove the specific element from list
list.remove(30)
print("remove 30 ",list)

list2=["tejas","ganesh","shitole"]
list.extend(list2)
print(list)
list2.sort(reverse=1)
print(list2)
