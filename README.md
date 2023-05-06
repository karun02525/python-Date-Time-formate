# python-Date-Time-formate
Date Time format
from datetime import datetime

now = datetime.now() # current date and time

year = now.strftime("%Y")
print("year:", year)

month = now.strftime("%m")
print("month:", month)

day = now.strftime("%d")
print("day:", day)

time = now.strftime("%H:%M:%S")
print("time:", time)

date_time = now.strftime("%m/%d/%Y, %H:%M:%S")
print("date and time:",date_time)

#Timestamp
timestamp = 1608727129
date_time = datetime.fromtimestamp(timestamp)

print("Date time object:", date_time)

d = date_time.strftime("%m/%d/%Y, %H:%M:%S")
print("Output 2:",d)

d = date_time.strftime("%d %b, %Y")
print("Output 3:",d)

d = date_time.strftime("%d %B, %Y")
print("Output 4:",d)

d = date_time.strftime("%I%p")
print("Output 5:",d)
![image](https://user-images.githubusercontent.com/36824081/236602447-aa15cd5c-cb18-4ba3-9a8a-029a6b7fdbfb.png)
![image](https://user-images.githubusercontent.com/36824081/236602386-927fb3d3-a06f-4d80-b0b3-b7d9a5082700.png)
![image](https://user-images.githubusercontent.com/36824081/236602420-5ab01e7c-1c71-4206-9970-31e8e3f8b88d.png)
