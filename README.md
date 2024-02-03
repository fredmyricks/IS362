# IS362
 Data Acquisition and Management IS 362 Asignments

#Comprehensions in Python provide us with a short and compact way to create new sequences.

#Code:

# set comprehension
# for creating new set

Set = [10, 28, 35, 15, 66, 79] 


Set_comp = {var for var in Set if var % 4 == 0} 

print("New Set using set comprehensions:",Set_comp)
#%%
#Documentation of Zip Function :

#The zip() function returns a zip object contains a paired iterator, which is an iterator of tuples.In this pair, it basically pairs the first element from two tuples and so on.

a = ("Fred", "Marcus", "Jesus")
b = ("Mary", "Peter", "Paul")

x = zip(a, b)

#convert zip object into tuple so that it can be iterable
print(tuple(x))
