<py-script>
#from life import time <br />
#from daughter import love <br />
#from wife import bills <br />
#from kitchen import dirty_dishes <br />
#from aliexpress import cheap_gadgets <br /><br />

def who_am_i():<br />
    today = datetime.date.today()<br />
    who_am_i.name = "Nuno Sousa aka Mr.Wicked"<br />
    who_am_i.age = today.year - 1992<br />
    who_am_i.skills = "Python, VBA and Excel"<br />
    who_am_i.hobbies = "Being a princess in my Daughter's castle"<br />
    who_am_i.email = "nunofvsousa@gmail.com"<br /><br />
  
    print(f"Hi! 👋\nMy name is {who_am_i.name} and i'm {who_am_i.age} years old!\n")<br />
    print(f"I like programming in {who_am_i.skills} (seriouly, i can do crazy things in Excel)\n")<br />
    print(f"When i am not programming, doing the dishes or paying bills i like {who_am_i.hobbies}\n")<br />
    print(f"For an addicional contact please email me at: 📫 {who_am_i.email} \n")<br /><br />

who_am_i()<br /><br />

print("Please Do Not Disturb... all todays bills are paid... all Dishes are clean... and my daughter is asleep... 💞️\n ")<br />
print("ZZZZzzzzzZzzZ \n") <br /><br />

while True:<br />
    time.sleep(3)<br />
    print("Programming...")<br />
  </py-script><br />
