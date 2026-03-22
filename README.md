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
 Include the necessary coding and corresponding screenshots
```
import matplotlib.pyplot as plt
import numpy as np

# Simple Examples
x=np.arange(0,10)
y=np.arange(11,21)
print(x, y)

## PLOTING USING MATPLOTLIB
# plt scatter
plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

# plt plot
plt.plot(x,y,'r*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()

# Creating Subplots
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
plt.show()

x = np.arange(1,11) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()

# Compute the x and y coordinates for points on a sine curve 
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.sin(x) 
plt.title("sine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show()

# Bar plot
x = [2,8,10] 
y = [11,16,9]  
x2 = [3,9,11] 
y2 = [6,15,7] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  
plt.show()

# Hist plot
a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()

# Box Plot
data = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(data,vert=True,patch_artist=True);  
plt.show()

# Pie Chart
# Data to plot
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0.4, 0, 0, 0)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()
```

#output



<img width="696" height="558" alt="Screenshot 2026-03-22 175152" src="https://github.com/user-attachments/assets/1f25a61b-4da2-4e1b-aacf-569796f928a5" />


<img width="643" height="509" alt="Screenshot 2026-03-22 175159" src="https://github.com/user-attachments/assets/5d5d3441-4e69-4b6e-a469-ec36ce99d7cf" />

<img width="621" height="471" alt="Screenshot 2026-03-22 175205" src="https://github.com/user-attachments/assets/434cab09-bd31-4016-90e5-365e3a4a646e" />

<img width="654" height="514" alt="Screenshot 2026-03-22 175210" src="https://github.com/user-attachments/assets/3a086396-450f-4466-976a-45d50afb6984" />

<img width="659" height="494" alt="Screenshot 2026-03-22 175216" src="https://github.com/user-attachments/assets/f52d14cb-ba46-44e9-9cf7-4474058d6b87" />


<img width="659" height="515" alt="Screenshot 2026-03-22 175221" src="https://github.com/user-attachments/assets/4ec08036-6506-4ede-a74d-d32ee050f4fc" />

<img width="626" height="486" alt="Screenshot 2026-03-22 175227" src="https://github.com/user-attachments/assets/6c98b776-3e43-4825-884e-329abf6f3183" />

<img width="619" height="459" alt="Screenshot 2026-03-22 175233" src="https://github.com/user-attachments/assets/68a5b038-c962-4447-ad67-62d5583f81e8" />

<img width="493" height="425" alt="Screenshot 2026-03-22 175240" src="https://github.com/user-attachments/assets/e50b463e-e1cf-4ba9-97ea-1058862ed734" />

# Result:
 Include your result here
 Data Visualization using matplot python library is verified
