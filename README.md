# python-day-1
Welcome to my Python learning journey!  
This repository documents what I learn each day as I build my Python skills from scratch.

## What I Learned Today

- What Python is and where it is used
- How to install Python on my system
- How to run Python code from the terminal
- Basic syntax
- `print()` function
- Variables and simple data types

# new line \n    (task-1)
print("Hello World! \nhello world! \nhello world!")

# concatenation string with(+)    (task-2)
print("hello" +" "+ "Atul")  #concatenating string with sapce

# taking values from user    (task-3)
print("hello " + input("what is your name?") + "!")

# finding the length of user provided length using len() function    (task-4)
print(len(input("enter your username:")))
# or
username=input("enter your username?")
length=len(username)
print(length)

# final project    (task-5)
print("welcome to the band name generator.")
city_name=input("enter your city name you grow up in?\n")
pet_name=input("enter your pet name?\n")
print("your band name could be: " + city_name +" "+ pet_name)
