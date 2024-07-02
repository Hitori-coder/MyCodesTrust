# MyCodesTrust
Variables: 1.Str 2.Int 3.bool 4.float
Author - Ahmed Aslam
1.Str
first_name='hitori'
last_name='gotoh'
full_name=first_name+' '+last_name
print('i love '+full_name)
print(type(full_name)) to check the type of variable
2.Int
age=96
age=654+143-age
print(age)
age=96
print('my grandmothers age is '+str(age)) type cast age because its not a string
print(type(age)) to check the type of variable
3.Bool
water=True
print('i think everyone should drink water '+str(water))
print(type(water))
4.Float
height=100.5
print('my height is '+str(height),'cm')
print(type(height))

Type Cast
a = 1
b = 2.8
c = '9'
#print(a)
#print(b)
#print(c*2)
b=int(b)
c=int(c)
print(b)
print(c)

ASSIGNMENTS (different)
name = 'hitori'
age = 16
water = False
name,age,water = 'hitori',16,False
print(name)
print(age)
print(water)
ASSIGNMENTS (same)
Ahmed = 16
Ali = 16
Junaid = 16
Ahmed = Ali = Junaid = 16
print(Ahmed)
print(Ali)
print(Junaid)

STRING METHODS
name = 'hitori'
print=(len(name)) tell how many alphabets are in the name
print(name.find('i')) finds the no of letters in the name
print(name.capitalize()) capitalizes the first letter of the name
print(name.upper()) writes the whole name in upper case letters
print(name.lower()) writes the whole name in lower case letters
print(name.isdigit()) tells if there is any digit in the name 
print(name.isalpha()) tells if there is any alphabets in the name 
print(name.count('o')) self explanatory
print(name.replace('o','a') self explanatory
print(name*6) self explanatory
