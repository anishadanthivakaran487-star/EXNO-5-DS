# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
## Date: 17/10/2025
## Name: ANISH ADAN THIVAKARAN
## Ref.No: 25017997
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
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

<img width="804" height="581" alt="Screenshot 2025-10-17 114222" src="https://github.com/user-attachments/assets/21e0a973-5ac6-489a-a4f9-674f3c58d645" />

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,3,5,1,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=10)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```

<img width="740" height="580" alt="Screenshot 2025-10-17 114232" src="https://github.com/user-attachments/assets/a5c832cd-dd21-4ad9-a8f0-fab23e4db150" />

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="762" height="565" alt="Screenshot 2025-10-17 114241" src="https://github.com/user-attachments/assets/c69fb22e-22e2-4378-bae8-2f649aa7d557" />

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

<img width="755" height="567" alt="Screenshot 2025-10-17 114251" src="https://github.com/user-attachments/assets/9dd17b6d-4200-41c1-a35a-2e1954c049f3" />

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
grapes=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, grapes)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields')
plt.legend(['Apples','grapes']);
```

<img width="798" height="587" alt="Screenshot 2025-10-17 114301" src="https://github.com/user-attachments/assets/ca58fdae-0824-41df-a178-af1433dc1752" />

```
plt.figure(figsize=(14,6))
plt.plot(years,grapes,marker='o')
plt.title("Yield of grapes (tons per hectare)");
```

<img width="1392" height="643" alt="Screenshot 2025-10-17 114326" src="https://github.com/user-attachments/assets/b7e8ac2d-eb00-4953-8b4f-7dc24ece4ebb" />

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```

<img width="365" height="50" alt="Screenshot 2025-10-17 114337" src="https://github.com/user-attachments/assets/3bd4ee07-5092-4073-8a41-7381396520c1" />

```
y
```

<img width="449" height="51" alt="Screenshot 2025-10-17 114343" src="https://github.com/user-attachments/assets/31e9a7a3-ff4c-4f7e-b382-ff1be9449c43" />

```
plt.scatter(x,y,c='b')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

<img width="770" height="585" alt="Screenshot 2025-10-17 114354" src="https://github.com/user-attachments/assets/7abc0f6e-5510-4446-854e-6a67938369b7" />

```
y=x*x
y
```

<img width="437" height="51" alt="Screenshot 2025-10-17 114402" src="https://github.com/user-attachments/assets/e29db0d0-191b-4352-9cb1-e28b66c126a1" />

```
plt.plot(x,y,'y*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```

<img width="776" height="622" alt="Screenshot 2025-10-17 114414" src="https://github.com/user-attachments/assets/9e0b217e-b667-4659-b1f9-46f1f65623ca" />

```
np.pi
```

<img width="174" height="49" alt="Screenshot 2025-10-17 114422" src="https://github.com/user-attachments/assets/c30f6b3c-ea80-40f3-9b36-654832d3838a" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

<img width="793" height="559" alt="Screenshot 2025-10-17 114430" src="https://github.com/user-attachments/assets/186d8934-daf2-42a5-be8d-ceb87a95d19b" />

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='red')
plt.fill_between(x,y2,color='yellow')
plt.fill_between(x,y3,color='red')
```

<img width="758" height="567" alt="Screenshot 2025-10-17 114440" src="https://github.com/user-attachments/assets/65346c56-f01e-4022-ac53-e77c5fbb5da7" />

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
```

<img width="759" height="564" alt="Screenshot 2025-10-17 114449" src="https://github.com/user-attachments/assets/c28e1b5c-d94f-4abe-99b6-84193f49027a" />

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```

<img width="769" height="580" alt="Screenshot 2025-10-17 114459" src="https://github.com/user-attachments/assets/98cb10b9-b89a-420a-982b-0bc7f18c4494" />

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('Xaxis')
plt.show()
```

<img width="771" height="584" alt="Screenshot 2025-10-17 114520" src="https://github.com/user-attachments/assets/657d6bff-3436-41b1-af21-9f8a843d3913" />

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='lightblue',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```

<img width="761" height="574" alt="Screenshot 2025-10-17 114534" src="https://github.com/user-attachments/assets/f559f236-e4c5-479e-84c2-9210f8317cde" />

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

<img width="693" height="448" alt="Screenshot 2025-10-17 114547" src="https://github.com/user-attachments/assets/23cd3107-1afb-48ca-afed-3fd8ff00fcaa" />

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="791" height="617" alt="Screenshot 2025-10-17 114558" src="https://github.com/user-attachments/assets/e514b899-411a-46d6-9a00-c8ba65992e10" />

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

<img width="651" height="496" alt="Screenshot 2025-10-17 114609" src="https://github.com/user-attachments/assets/a5411dbf-39d2-4730-ab34-19a7bf265758" />

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

<img width="627" height="549" alt="Screenshot 2025-10-17 114622" src="https://github.com/user-attachments/assets/a90fd695-04c3-47c3-bece-e9fac2e88e04" />

# Result:
Thus, the program to Perform Data Visualization using matplot python library for the given data was implemented.
