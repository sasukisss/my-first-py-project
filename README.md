# my-first-py-project
this is my first py project hello world
#!/user/bin/env python
# -*- coding :utf-8 -*-
# Author:Sasuki
username = input("username:")
password = input("pasword:")


name = input("name:")
age: int = int(input("age"))
print(type(age) , type( str(age)))
job = input("job:")
salary = int(input("salary"))

info = '''
--------  info of'''+ name +''' --------
Name:''' + age + '''
Job:''' + job +'''
Salary:''' + salary

#變量拼接

print(info)

info = '''
-------- info of  %s --------
Nmae:%s
Age:%d
Job:%s
Salary:%d
''' % (name,name,age,job,salary)
#格式化拼接語法,變量跟占位符一一對應

print(info)
