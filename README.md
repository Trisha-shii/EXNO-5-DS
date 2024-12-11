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

from google.colab import drive
drive.mount('/content/drive')

<img width="192" alt="Screenshot 2024-12-11 095915" src="https://github.com/user-attachments/assets/b453a669-e3ef-4be8-b543-c39e124eac8a">


import matplotlib.pyplot as plt

x_values = [0,1,2,3,4,5]
y_values = [0,1,4,9,16,25]

plt.plot(x_values, y_values)
plt.show()


<img width="423" alt="Screenshot 2024-12-11 094853" src="https://github.com/user-attachments/assets/9309bc2f-e614-436b-9b42-5f0a97974f0d">

import matplotlib.pyplot as plt

x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('MY FIRST GRAPH!')
plt.show()


<img width="431" alt="Screenshot 2024-12-11 094837" src="https://github.com/user-attachments/assets/7d7d8e83-b0a3-4729-a093-e8ad5457b612">

import matplotlib.pyplot as plt

x1 = [1,2,3]
y1 = [2,4,1]

plt.plot(x1,y1,label = "line 1")

x2 = [1,2,3]
y2 = [4,1,3]
plt.plot(x2,y2,label="line 2")

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("TWO LINES ON SAME GRAPH!")
plt.legend()
plt.show()


<img width="445" alt="Screenshot 2024-12-11 094821" src="https://github.com/user-attachments/assets/ee0fc1a7-63a1-41ad-a035-ed51a564d4ed">


import matplotlib.pyplot as plt

x = [1,2,3,4,5,6]
y = [2,4,1,5,2,6]

plt.plot(x,y,color='green', linestyle='dashed', linewidth = 3, marker = 'o', markerfacecolor='blue', markersize=12)

plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("SOME COOL CUSTOMIZATIONS")
plt.show()


<img width="428" alt="Screenshot 2024-12-11 094801" src="https://github.com/user-attachments/assets/b6138d22-f65b-4295-b199-5dc783de27c0">


yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)


<img width="480" alt="Screenshot 2024-12-11 094747" src="https://github.com/user-attachments/assets/ebbefeb9-729f-4107-8b3a-1c2cb518a2fb">


years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)


<img width="436" alt="Screenshot 2024-12-11 094732" src="https://github.com/user-attachments/assets/519966d3-476c-47b2-9e96-652ebe51f65c">

years = range(2000,2012)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375,0.9372, 0.939]
oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896]


plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')


<img width="456" alt="Screenshot 2024-12-11 094713" src="https://github.com/user-attachments/assets/f07bb8d9-1abd-429b-a059-503da5560055">


plt.plot(years, apples)
plt.plot(years, oranges)

plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')

plt.title("Crop Yields in Kanto")
plt.legend(['Apples','Oranges'])



<img width="439" alt="Screenshot 2024-12-11 094655" src="https://github.com/user-attachments/assets/975abf6c-f3d2-4303-af0c-7f265769c65e">












plt.figure(figsize=(12,6))

plt.plot(years, oranges, marker = 'o')
plt.title("Years of Oranges (tons per hectare)")


<img width="485" alt="Screenshot 2024-12-11 094633" src="https://github.com/user-attachments/assets/c14ab88c-36ae-445a-9bb6-12c8fbc70f57">

plt.plot (years, apples, marker = 'o' )
plt.plot (years, oranges, marker = 'x')

plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')


plt.title("Crop Yields in Kanto")
plt.legend (['Apples','Oranges'])


<img width="446" alt="Screenshot 2024-12-11 094553" src="https://github.com/user-attachments/assets/d14df3cf-0a71-493e-b467-6e3dfb3b1087">

import matplotlib.pyplot as plt

x_values = [0,1,2,3,4,5]
y_values = [0,1,4,9,16,25]
plt.scatter(x_values, y_values, s=30, color = "blue")
plt.show()


<img width="422" alt="Screenshot 2024-12-11 094533" src="https://github.com/user-attachments/assets/020fd754-561b-4f41-b9e7-d6c484424d0b">


import matplotlib.pyplot as plt


x = [1,2,3,4,5,6,7,8,9,10]
y = [2,4,5,7,6,8,9,11,12,12]

plt.scatter(x,y,label="stars", color = "green", marker = "*", s=30 )
plt.xlabel('x-axis')
plt.ylabel('y-axis')

plt.title("MY SCATTER PLOT!")
plt.legend()
plt.show()


<img width="431" alt="Screenshot 2024-12-11 094512" src="https://github.com/user-attachments/assets/830b234b-07e6-45eb-a65a-90ab699ad115">

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

x = np.arange(0,10)
y = np.arange(11,21)

x

<img width="226" alt="Screenshot 2024-12-11 094454" src="https://github.com/user-attachments/assets/b968aec5-7784-4caf-811a-098d77a5f17e">


y

<img width="279" alt="Screenshot 2024-12-11 094432" src="https://github.com/user-attachments/assets/2583c0ef-48be-4e73-9560-798cb4d438dd">

plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')


<img width="442" alt="Screenshot 2024-12-11 094414" src="https://github.com/user-attachments/assets/f2d57f09-bd7b-4f94-8424-a0d96a2ceee1">

y = x*x
y


<img width="277" alt="Screenshot 2024-12-11 094351" src="https://github.com/user-attachments/assets/248d994a-e0de-4b14-98b3-23c1c18a616f">

plt.plot(x,y,'g*', linestyle = 'dashed', linewidth = 2, markersize = 12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')

<img width="425" alt="Screenshot 2024-12-11 094331" src="https://github.com/user-attachments/assets/628df5d1-1209-4ea8-8f37-5a4175e33803">

plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')

<img width="444" alt="Screenshot 2024-12-11 094247" src="https://github.com/user-attachments/assets/be035999-c7b1-464e-8547-10b8de303a0a">

np.pi


<img width="122" alt="Screenshot 2024-12-11 094304" src="https://github.com/user-attachments/assets/7c4cea9e-d85d-40fe-9e71-1579a129bf35">

x = np.arange(0,4*np.pi,0.1)
y = np.sin(x)
plt.title("SINE WAVE FORM")


<img width="437" alt="Screenshot 2024-12-11 094226" src="https://github.com/user-attachments/assets/e284f0cd-5c2d-40b7-9c73-f9c1233ed3da">

plt.plot(x,y)
plt.show()

import matplotlib.pyplot as plt
import numpy as np

x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]

plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'green')

plt.plot(x, y1, color = 'red')
plt.plot(x, y2, color = 'black')

plt.legend(['y1', 'y2'])
plt.show()

<img width="424" alt="Screenshot 2024-12-11 094203" src="https://github.com/user-attachments/assets/4ae9773d-b153-43a8-b863-71f1bbc55078">

plt.stackplot(x, y1, y2, y3, labels = ['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')

plt.show()


<img width="445" alt="Screenshot 2024-12-11 094144" src="https://github.com/user-attachments/assets/8fd590c3-625e-4605-89a8-d3fa4ebf4089">

import numpy as np
import matplotlib.pyplot as plt

from scipy.interpolate import make_interp_spline
x = np.array([1,2,3,4,5,6,7,8,9,10])
y = np.array([2,4,5,7,8,8,9,10,11,12])

spl = make_interp_spline(x,y)

x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)

plt.plot(x,y,'o',label='data')
plt.plot(x_smooth, y_smooth, '-', label = 'spline')
plt.legend()
plt.show()


<img width="419" alt="Screenshot 2024-12-11 094104" src="https://github.com/user-attachments/assets/32ea1704-9c88-417f-8684-b778a7215510">


import matplotlib.pyplot as plt
values = [5,6,3,7,2]
names = ['A','B','C','D','E']

plt.bar(names, values, color = "green")
plt.show()


<img width="406" alt="Screenshot 2024-12-11 094022" src="https://github.com/user-attachments/assets/d80ff289-1dbf-474d-bb83-40dd819f07bc">

import matplotlib.pyplot as plt
values = [5,6,3,7,2]
names = ["A","B","C","D","E"]

plt.barh(names,values,color = "yellowgreen")
plt.show()

<img width="416" alt="Screenshot 2024-12-11 094000" src="https://github.com/user-attachments/assets/d007d304-ba62-4db7-a236-6bdc79312e6c">

import matplotlib.pyplot as plt

height = [10,24,36,40,5]
names = ['one','two','three','four','five']

c1 = ["red", "green"]
c2 = ["b","g"]
plt.bar(names,height,width=0.8,color=c1)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("MY BAR CHART!")

plt.show()


<img width="430" alt="Screenshot 2024-12-11 093938" src="https://github.com/user-attachments/assets/a3f2f698-ef7b-4910-8a95-de4c40c9d6ec">

x = [2,8,10]
y = [11,16,9]

x2 = [3,9,11]
y2 = [6,15,7]

plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title("Bar Graph")
plt.xlabel("X AXIS")
plt.ylabel("Y AXIS")
plt.show()


<img width="432" alt="Screenshot 2024-12-11 093920" src="https://github.com/user-attachments/assets/bd35746b-70dc-452e-b0e7-f5d034aae19f">


import matplotlib.pyplot as plt
ages = [2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]

range = (0,100)
bins = 10

plt.hist(ages, bins, range, color="green", histype="bar",rwidth=0.8)

plt.xlabel("age")
plt.ylabel("No Of People")
plt.title("MY HISTOGRAM")
plt.show()


<img width="413" alt="Screenshot 2024-12-11 093847" src="https://github.com/user-attachments/assets/85f609e2-a4f3-40ea-9fb9-bcf6bc63cc65">

import matplotlib.pyplot as plt

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x,bins=10,color="blue",alpha=0.5)
plt.show()


<img width="416" alt="Screenshot 2024-12-11 093828" src="https://github.com/user-attachments/assets/9f1b7876-0527-4d3f-ad8f-d7e2cb469b3b">

import matplotlib.pyplot as plt
import numpy as np

np.random.seed(0)
data = np.random.normal(loc=0, scale=1, size=100)
data


<img width="437" alt="Screenshot 2024-12-11 093731" src="https://github.com/user-attachments/assets/1d56d9d4-3dca-4454-a45d-f890ee69b760">

fig,ax = plt.subplots()
ax.boxplot(data)
ax.set_xlabel("Data")
ax.set_ylabel("Values")
ax.set_titles("Box Plot")


<img width="443" alt="Screenshot 2024-12-11 093702" src="https://github.com/user-attachments/assets/80b3bccf-7279-4c62-81b1-c0117872361a">


import matplotlib.pyplot as plt

activities = ['eat','sleep','work','play']
slices = [3,7,8,6]
colors = ['r','y','g','b']
plt.pie(slices, labels = activities, colors=colors, startangle=90, shadow=True, explode=(0,0,0.1,0),radius = 1.2, autopct = '%1.1f%%')
plt.legend()
plt.show()


<img width="344" alt="Screenshot 2024-12-11 093630" src="https://github.com/user-attachments/assets/b36cfd6b-e4f6-4530-ba7c-36a4c858c594">

labels = 'Python','C++','Ruby','Java'
sizes = [215,130,245,210]
colors = ['gold','yellowgreen','lightcoral','lightskyblue']
explode = (0,0.4,0,0.5)

plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()


<img width="397" alt="Screenshot 2024-12-11 093610" src="https://github.com/user-attachments/assets/d697fb58-bc21-4a6b-afe2-bb29f0afa12f">

activities = ['eat','sleep','work','play']
slices = [3,7,8,6]
colors = ['r','y','g','b']
plt.pie(slices, labels = activities, colors = colors, startangle = 90, shadow = True, explode=(0,0,0.1,0),radius= 1.2, autopct = '%1.1f%%')
plt.legend()


<img width="335" alt="Screenshot 2024-12-11 093418" src="https://github.com/user-attachments/assets/8f0a8319-9ce1-4726-9428-12cada667b31">






























# Result:
 Include your result here
