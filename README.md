# A-Day-at-the-Supermarket
codecademy lesson

#BeFOR We Begin
names = ["Adam","Alex","Mariah","Martine","Columbus"]
for x in names :
    print x
    
#This is KEY!
webster = {
	"Aardvark" : "A star of a popular children's cartoon show.",
    "Baa" : "The sound a goat makes.",
    "Carpet": "Goes on the floor.",
    "Dab": "A small amount."
}
for x in webster :
    print webster[x]
    
    
#Control Flow and Looping
a = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
for x in a :
    if x %2 == 0:
        print x
        
        
#Lists + Functions
def fizz_count(x):
    count = 0
    for item in x :
        if item == "fizz":
            count += 1
    return count
a = ["fizz","cat","fizz"]
print fizz_count(a)


#Keeping Track of the Produce
prices = {
    "banana":4,
    "apple":2,
    "orange":1.5,
    "pear":3
}
stock = {
    "banana":6,
    "apple":0,
    "orange":32,
    "pear":15
}
for key in prices:
    print key
    print "price: %s" %  prices[key]
    print "stock: %s" % stock[key]
    
    
#Something of Value
prices = {
    "banana" : 4,
    "apple"  : 2,
    "orange" : 1.5,
    "pear"   : 3,
}
stock = {
    "banana" : 6,
    "apple"  : 0,
    "orange" : 32,
    "pear"   : 15,
}
total = 0 
for key in prices:
    total = prices[key] * stock[key] + total
    print key 
    print total
    
    
    #
