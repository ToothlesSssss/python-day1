# Python day 1

```python
#you can write a comment using a hashtag# sign in front

first_name = 'hanna'
age = 32
height = 11.8
print(type(first_name))

print(type(age))

print(type(height))

#list
students_list = ['hanna', 'john', 'besh']
students_list.insert(3,"hailu")
print(students_list[1])

for index, value in enumerate (students_list):
        print(value)

#tuple
names = {'hanna' , 'kebede', 'yakob','maki'}
print(type(names))

#set
# set cannot hold any duplicated list
names = {'hanna' , 'kebede', 'yakob','maki','maki'}
print(names)

student_info={'name':'hanna',
              'age':12,
              'sec':'B',
              'height':1.3,
              'skills':['java','javascript','python','django','mongo']
              }  
print(student_info)

print(student_info['height'])

```

loop

```python
#loop
#for loop
for i in range(0,12):
    print(i)
    print('hello')

    for index, value in enumerate (students_list):
        print(value)
  #you can also use like this
   for value in (students_list):
        print(value)

# if else loop
if age> 18:
             print('adult')
        elif (age<18):
             print('underage')
        else:
             print('error')
```

**function**

```python
#function
def greet():
 print ('hello world')

 def greet_with_name(name):
   print(f'hello {name}')

   greet()
   greet_with_name('hanna')

def greet_with_name( age, name, last_name = 'kebede'):
  print(f'hello {name} age: {age}
         last name: {last_name}')

greet_with_name('hanna',age= 44)

#positional arguments
 #keyword args
 #default args
 #string formatting using f string  
  

greet_with_name(*numbers):
for name in numbers:
  
  print(f'hello{name}')

  greet_with_name('hanna','kebede','dawit','yakob')

 # scrap data from a local website transfer to telegram
```