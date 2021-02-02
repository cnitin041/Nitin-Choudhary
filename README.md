# Nitin-Choudhary
import random
a=input("what is your name? ")
print("hello!  "+a.title()+" Nice to meet you")
print("Welcome to Number game")
no_1=int(input("enter a no between 1 to 10  :---"))
no_called=random.randint(1,10)
if no_1==no_called:
	print("You are lucky,You win")
	

#	print("Oo..you loose,you unlucky piece of sh**")
else:
	print("You lost,you unlucky piece of sh*t "+"The no is "+str(no_called))
	

	
