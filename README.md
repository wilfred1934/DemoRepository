# DemoRepository
PythonDemoRepository


from datetime import date
##
## date object of today's date
today = date.today() 
##
print("Current year:", today.year)
print("Current month:", today.month)
print("Current day:", today.day)



##To Get Tomorrows DATE:

from datetime import date
from datetime import timedelta

##Lets print todays DATE:

today = date.today()
print("Today is:", today)

##Lets print tomorrows Date:

tomorrow = today + timedelta(days = 1)
print("Tomorrow will be:", tomorrow)



#STRFTIME:

from datetime import datetime
now = datetime.now()
a = now.strftimw(" %H: %M: %S")
print("time:", a)

x = now.strftime("%d/%m/%Y, %H: %M: %S")
print("STRFTIME:", x)
