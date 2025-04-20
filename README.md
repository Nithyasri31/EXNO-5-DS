# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
NAME:NITHYASRI M
REG.NO:212224040226
```
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.plot(x,y)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
``
![Screenshot 2025-04-19 203235](https://github.com/user-attachments/assets/08435205-54e3-47dc-a1f4-947c307c0175)

```
x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.plot(x1,y1,label="line 1")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.legend()
plt.show()
```
![Screenshot 2025-04-19 203258](https://github.com/user-attachments/assets/ccedaf3f-2b7b-41fa-8dfb-0b60455fb076)
```
import matplotlib.pyplot
 as plt

x = [1, 2, 3, 4, 5, 6]
y = [2, 4, 1, 5, 2, 6]

plt.plot(x, y, color="red", linewidth=2, linestyle="dashed", marker='o', markerfacecolor='blue')
plt.ylim(1, 8)
plt.xlim(1, 8)
plt.show()
```
![image](https://github.com/user-attachments/assets/8e2e7a35-b83b-4ca9-8684-5db3be47cb55)
```
import matplotlib.pyplot as plt

years = range(2000, 2010)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.93]
oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.897, 0.894, 0.891, 0.89]

plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples', 'Oranges'])
plt.show()
```
![image](https://github.com/user-attachments/assets/ff9cb91a-bb90-4c60-9584-7892fcb25d7f)
```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/32e79d44-7454-4dbe-80b8-5ce02e200a6d)
```
years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)
plt.xlabel('YEAR')
plt.ylabel('YIELD(tons per hectare)')
```
![image](https://github.com/user-attachments/assets/2deb4329-4d78-43a3-b78b-322181e6b19d)
```
plt.figure(figsize=(10, 6))
y=list(range(2000,2012))
plt.plot(years, oranges, marker='o')
plt.title("YIELD OF ORANGES (tons per hectare)")
```
![image](https://github.com/user-attachments/assets/f5f6286c-c2d7-4137-aa98-354f52d27a1c)
```
plt.plot(years, oranges, marker='x')
plt.plot(years, apples, marker='o')
plt.xlabel("YEAR")
plt.ylabel("YIELD (tons per hectare)")
plt.title("YIELD OF ORANGES AND APPLES (tons per hectare)")
plt.legend(["Oranges", "Apples"])
```
![image](https://github.com/user-attachments/assets/73b070c6-d548-4ef4-a2ca-a7272c259584)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,s=30,color="red")
plt.show()
```
![image](https://github.com/user-attachments/assets/8c6b6901-cf1a-4616-a92d-ab2935ff2b65)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,marker="*",color="blue")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("SCATTER PLOT")
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/10ef0870-f03f-4f52-9ba1-3c2fc4e9accc)
```
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/39b4c5d6-eafe-4bd5-b642-464ad5923853)
```
y
```
![image](https://github.com/user-attachments/assets/3712ac95-1281-4b49-a57c-00e2e4c34e6f)
```
plt.scatter(x,y,c="r")
 plt.xlabel("X-AXIS")
 plt.ylabel("Y-AXIS")
 plt.title("GRAPH IN 2D")
 plt.savefig("Test.png")
```
![image](https://github.com/user-attachments/assets/ebb5ad9e-74ae-4db7-9c2f-4b6c50a028e1)
```
y=x*x
 y
```
![image](https://github.com/user-attachments/assets/ecd9b4c0-6993-455b-a54f-48ebc31b215b)
```
plt.plot(x,y,'g*',linestyle="dashed",linewidth=2,markersize=12)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("2D GRAPH")
```
![image](https://github.com/user-attachments/assets/673d508a-948c-403a-93d3-3762e884830b)
```
plt.subplot(2, 2, 1)
plt.plot(x, y, 'r--')
plt.subplot(2, 2, 2)
plt.plot(x, y, 'g*--')
plt.subplot(2, 2, 3)
plt.plot(x, y, 'bo')
plt.subplot(2, 2, 4)
plt.plot(x, y, 'go')
```
![image](https://github.com/user-attachments/assets/1bf68deb-cfb6-4145-99dd-d804e3e7e7bb)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()
```
![image](https://github.com/user-attachments/assets/5d87a80b-d11c-4556-9224-756ed3f0dc59)
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2=[5, 7, 9, 11, 13]
y3=[2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/a0daab29-dd05-4440-ac6b-8ed9b9b772ba)
```
plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/08660915-dd0e-4816-80d4-590eade6ce63)
```
from scipy.interpolate import make_interp_spline
x= np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
spl = make_interp_spline(x, y)
x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)
plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.title("SPLINE CHART")
plt.show()
```
![image](https://github.com/user-attachments/assets/3f93a909-1ead-4920-96a5-288f7ef4bff7)
```
val=[5,4,8,6,3]
 names=["A","B","C","D","E"]
 plt.bar(names,val,color="red")
 plt.title("BAR GRAPH")
 plt.show()
```
![image](https://github.com/user-attachments/assets/de586915-a352-4787-8096-dd5b665c922c)
```
plt.barh(names,val,color="pink")
plt.title("BAR GRAPH(horizontal)")
plt.show()
```
![image](https://github.com/user-attachments/assets/73416760-7b9a-4b27-ad5c-cb87a03c98a8)
```
height=[10,24,36,37,45]
 names=['one','two','three','four','five']
 c1=['red','blue']
 c2=['b','g']
 plt.bar(names,height,color=c1,width=0.8)
 plt.xlabel("names")
 plt.ylabel("height")
 plt.title("BAR CHART")
 plt.show()
```
![image](https://github.com/user-attachments/assets/5c293761-9bf8-4c45-9b9e-ed0b645cb316)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x, y,color='yellowgreen')
plt.bar(x2, y2, color = 'purple')
plt.title("Bar graph")
plt.ylabel('Y axis')
plt.xlabel('x axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/71e6c963-fa8a-4fbd-84b0-8427254617b7)
```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0, 100)
bins=10
plt.hist(ages, bins, range, color='cyan', histtype='bar', rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('Histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/c02f6264-7905-45f0-ae71-48b3b6251bac)
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/710ab5da-166c-4690-9e0e-0731a17ba294)
```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

![Screenshot 2025-04-19 205629](https://github.com/user-attachments/assets/b9cc683e-3bea-4027-abaa-873f59a1cc34)
```
fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_title("BOX PLOT")
 ax.set_ylabel("Y-AXIS")
 ax.set_xlabel("X-AXIS")
```

![image](https://github.com/user-attachments/assets/3e2fea28-de4f-4b93-b589-ba80e6ec34c4)
```
activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,
shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()
```
![image](https://github.com/user-attachments/assets/91d11252-068b-4ebd-9206-1892fcbed0b4)
```
labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210]
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f')
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/f8af2473-53ec-4abd-b8c7-4fab0529acb4)

# Result:
 Data Visualization using matplot python library for the given datas is successfully performed.
