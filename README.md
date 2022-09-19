#list
my_list1 = ["kiran", "naresh", 123, "vijay"]
my_list2 = ["ganesh", "uday", 878, 465]
print(my_list1)
print(my_list2)

#empty list
my_list = []
print(my_list)

#nested list
my_list = ["python", [8, 4, 6], ['a']]
print(my_list)

my_list = ('a', 's', 's', 'i', 'g', 'n', 'm', 'e', 'n', 't')
print(my_list[0])
print(my_list[1])
print(my_list[-4])
print(my_list[1:5])
print(my_list[:10])

my_list = ["kiran", "shyam", 88, 53, "python", "java"]
my_list1 = ["ganesh", "prudhvi", 73, 59, "project"]
print(my_list)
#update....
my_list[3] = 66
print(my_list)
#append...
my_list.append(82)
print(my_list)
#insert..
my_list1.insert(123, "ram")
print(my_list1)
#delete..__doc__
del my_list[5]
print(my_list)
#remove
my_list1.remove("prudhvi", )
print(my_list1)
#indexing
mylist = [7556, 2776, "data", "name", 565, 8786]
print(mylist[2])
print(mylist[1:3])

#tuple
my_tuple = ("hello", 21, 65, 8.9)
print(my_tuple)
my_tuple = ("key", "mouse", [5, 23, 76], (
    45,
    11,
))
print(my_tuple)
my_tuple = (54, 63, 76), ("hello", "world")
print(my_tuple[0])
print(my_tuple[1])
print(my_tuple[1][1])

#dictionaries
my_dict = {"name": "kiran", "age": 19, "year": 2002, "section": "a"}
print(my_dict)
print(my_dict["name"])
print(my_dict.pop('age'))
print(my_dict.popitem())
#update
my_dict["name"] = "devil"
print(my_dict)
#delete
del my_dict["year"]
print(my_dict)
#add item
my_dict['address'] = 'chennai'
print(my_dict)
#clear
my_dict.clear()
print(my_dict)

#sets
my_set = {"a", "b", "c", 523, "d"}
print(my_set)
print(len(my_set))
my_set.add(5.6)
print(my_set)

set1 = {"hello", "world", "welome"}
set2 = {"data", "kiran", 645}
set3 = set1 & set2
print(set3)
set1 = 500
set2 = 400
print(set1 != set2)
print(set1 == set2)
print((set1) >= (set2))
print((set1) <= (set2))

#set
k="engineer"
print(k[::-4])

#frozen set
list=[1,2,3,4,5,5,6]
list=[frozenset([i,j])for i in list for j in list]
dictionary={}
for element in list:
    dictionary[element]=True
print(dictionary)    
