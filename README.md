# SUNDAY-PROJECT-17-09-2023- calculator and string methods with indexing , slicing , escaping


# make a calculator with/without user input which calculates addition,multiplication,subtraction,divide and power multiply(modula)

a = 4
b = 6
print("The value by adding a + b is: =", a+b)
print("The value by adding a + b is: =", a-b)
print("The value by adding a + b is: =", a*b)
print("The value by adding a + b is: =", a/b)
print("The value by adding a + b is: =", a**b)


c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
sum = (c+d)
print(sum)

sub = (c-d)
print(sub)

div = (c/d)
print(div)

mul = (c*d)
print(mul)

modula = (c**d)
print(modula)



c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
sum = (c+d)
print(sum)

c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
sub = (c-d)
print(sub)

c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
div = (c/d)
print(div)

c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
mul = (c*d)
print(mul)

c = int(input("Enter a no: "))
d = int(input("Enter a no: "))
modula = (c**d)
print(modula)



#string slicing and indexing

q = "hello harsh whatsapp \nwhat are you doing right now!"
print(len(q))
print(q[:5])

#STRING METHODS


#it will print true because q is ending with now!
print(q.endswith("now!"))
#it will print false because q is not endingh with hello
print(q.endswith("hello"))
#it will "find" whatsapp in q
print(q.find("whatsapp"))
#it will convert string in upper case
print(q.upper())
#it will convert the string in lower case
print(q.lower())
#it will shift our string in center by which value we will give it to it
print(q.center(100))
#it will remove the given sentence or word here i have given "!" this
print(q.rstrip("!"))
#it will capitalize the first letter of string here it will capitalize "hello"
print(q.capitalize())
#it will replace the existing sentence with new given sentence
print(q.replace("hello","hii "))
