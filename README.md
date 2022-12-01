#from life import time
#from daughter import love
#from wife import bills
#from kitchen import dirty_dishes
#from aliexpress import cheap_gadgets

import datetime
import time

def who_am_i():
  today = datetime.date.today()
  who_am_i.name = "Nuno Sousa aka Mr.Wicked"
  who_am_i.age = today.year - 1992
  who_am_i.skills = "Python, VBA and Excel"
  who_am_i.hobbies = "Being a princess in my Daughter's castle"
  who_am_i.email = "nunofvsousa@gmail.com"
  print (f"Hi! 👋\nMy name is {who_am_i.name} and i'm {who_am_i.age} years old!\n")
  time.sleep(3)
  print (f"I like programming in {who_am_i.skills} (seriouly, i can do crazy things in Excel)\n")
  time.sleep(4)
  print (f"When i am not programming, doing the dishes or paying bills i like {who_am_i.hobbies}\n")
  time.sleep(5)
  print(f"For an addicional contact please email me at: 📫 {who_am_i.email} \n")
  
who_am_i()

time.sleep(5)
print ("Please Do Not Disturb... all todays bills are paid... all Dishes are clean... and my daughter is asleep... 💞️\n ")
time.sleep(3)
print("ZZZZzzzzzZzzZ \n")

while True:
  time.sleep(3)
  print("Programming...")
  
