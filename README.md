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
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.plot(x,y)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```

 <img width="1187" height="756" alt="image" src="https://github.com/user-attachments/assets/570002cd-48f7-40bd-b5d6-2c0f18df1c99" />

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
<img width="768" height="568" alt="image" src="https://github.com/user-attachments/assets/1d914586-dd8a-4d2c-807f-4c0766c3eb6a" />

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color="red",linewidth=9,linestyle="dashed",marker='o',markerfacecolor='green',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```
<img width="742" height="570" alt="image" src="https://github.com/user-attachments/assets/c0bac367-01ae-4160-ae52-6fa761a37b9e" />

```
years = range(2000, 2012)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]
oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.897, 0.894, 0.891, 0.886, 0.9, 0.896]

plt.plot(years, apples)
plt.plot(years, oranges)

plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples', 'Oranges'])
```
<img width="870" height="612" alt="image" src="https://github.com/user-attachments/assets/9d62ca7d-2a9d-4d33-bb19-1dc074313de8" />

```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```

<img width="840" height="567" alt="image" src="https://github.com/user-attachments/assets/7a7057e4-2ba2-4bf1-bb8c-3f0c85f0a062" />

```
years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)
plt.xlabel('YEAR')
plt.ylabel('YIELD(tons per hectare)')
```
<img width="832" height="582" alt="image" src="https://github.com/user-attachments/assets/36e48096-2733-4a43-8d7c-6f75cae3e22f" />

```
plt.figure(figsize=(10,6))
y=list(range(2000,2012))
plt.plot(y,oranges,marker='o')
plt.title("YIELD OF ORANGES(tons per hectare)")
```

<img width="871" height="510" alt="image" src="https://github.com/user-attachments/assets/81a48cac-e04c-45ba-b33a-57dbdf8f0073" />

```
plt.plot(y,oranges,marker='x')
plt.plot(y,apples,marker='o')
plt.xlabel("YEAR")
plt.ylabel("YIELD(tons per hectare)")
plt.title("YIELD OF ORANGES AND APPLES(tons per hectare)")
plt.legend(["oranges","apples"])
```

<img width="862" height="606" alt="image" src="https://github.com/user-attachments/assets/d8578800-7da8-4a35-a746-daf8d36e8f71" />

```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,s=30,color="red")
plt.show()

```

<img width="767" height="522" alt="image" src="https://github.com/user-attachments/assets/8a277d15-b73b-4bf1-93c3-dd5ea21f7fd3" />


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

<img width="773" height="547" alt="image" src="https://github.com/user-attachments/assets/f9d34201-6107-43d3-9cb6-717029ab3857" />

```

import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x

```

<img width="507" height="36" alt="image" src="https://github.com/user-attachments/assets/c0b73ab9-ee20-4680-9d83-40c948a4f7a7" />

```
y
```

<img width="576" height="40" alt="image" src="https://github.com/user-attachments/assets/027fc6b6-9358-4da0-a4a1-774ea84f09dd" />

```
plt.scatter(x,y,c="r")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH IN 2D")
plt.savefig("Test.png")
```

<img width="777" height="567" alt="image" src="https://github.com/user-attachments/assets/72c2fd52-9150-4c57-9e8e-506815467219" />


```
y=x*x
y
```

<img width="592" height="42" alt="image" src="https://github.com/user-attachments/assets/a5e06f2d-19ec-4e50-949e-9a47cb6fdc5a" />

```
plt.plot(x,y,'g*',linestyle="dashed",linewidth=2,markersize=12)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("2D GRAPH")
```
<img width="731" height="567" alt="image" src="https://github.com/user-attachments/assets/9b3ed56b-c56d-42ee-aadb-515a8209f379" />

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
<img width="822" height="580" alt="image" src="https://github.com/user-attachments/assets/c96167b8-bf8e-4747-aa86-79f59d7f5338" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()

```
<img width="742" height="542" alt="image" src="https://github.com/user-attachments/assets/de283714-c421-40f4-a2f6-310345f20fa9" />


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
<img width="725" height="513" alt="image" src="https://github.com/user-attachments/assets/ebc4593c-87b9-4424-8b70-200bdb90d9ef" />

```
plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
<img width="758" height="557" alt="image" src="https://github.com/user-attachments/assets/971f52f5-59d8-47f9-b22f-cd27358fb54a" />

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


<img width="766" height="547" alt="image" src="https://github.com/user-attachments/assets/6a8cd446-25c6-459c-9f0b-a85b727b4b32" />

```
val=[5,4,8,6,3]
names=["A","B","C","D","E"]
plt.bar(names,val,color="red")
plt.title("BAR GRAPH")
plt.show()
```
<img width="718" height="562" alt="image" src="https://github.com/user-attachments/assets/d9454cd1-aac3-4200-b8d3-7544b4f5e22f" />

```
plt.barh(names,val,color="pink")
plt.title("BAR GRAPH(horizontal)")
plt.show()
```
<img width="815" height="547" alt="image" src="https://github.com/user-attachments/assets/d17c50d9-2913-4198-b185-b35b14c243df" />

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
<img width="762" height="543" alt="image" src="https://github.com/user-attachments/assets/134055ce-4932-4d7d-a0b7-d0f8d41ad96c" />

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
<img width="762" height="561" alt="image" src="https://github.com/user-attachments/assets/29bcba3d-c28d-4df2-a157-6608520cd833" />

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

<img width="776" height="553" alt="image" src="https://github.com/user-attachments/assets/689004a0-1614-42a9-993e-e928071457ae" />

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()

```
<img width="792" height="508" alt="image" src="https://github.com/user-attachments/assets/35243454-dd54-4d63-856d-20521240c52e" />

```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
<img width="827" height="442" alt="image" src="https://github.com/user-attachments/assets/6b2a22d6-a0b3-40db-9d8e-be3ba22a4b77" />

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_title("BOX PLOT")
ax.set_ylabel("Y-AXIS")
ax.set_xlabel("X-AXIS")

```

<img width="842" height="617" alt="image" src="https://github.com/user-attachments/assets/8ff1c254-40dc-4965-b871-0bd450f2548e" />

```

activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90, 
        shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()
```
<img width="813" height="497" alt="image" src="https://github.com/user-attachments/assets/4b403cfc-1deb-4091-8445-789f59325733" />

```
labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210] 
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] 
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
<img width="682" height="462" alt="image" src="https://github.com/user-attachments/assets/e70e30e4-3655-4a64-8efa-975873ecd918" />





# Result:
 Data Visualization using matplot python library for the given datas is successfully performed.
