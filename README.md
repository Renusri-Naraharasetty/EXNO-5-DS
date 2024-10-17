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

LINE GRAPH
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/e16ba86b-b146-41fe-a2c3-daeeee9d25de)


SIMPLE LINE
```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph !')
plt.show()
```
![image](https://github.com/user-attachments/assets/1aaa140f-7af6-442c-bcb8-59ba98fc861d)


SIMPLE 2 LINES
```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/653ac23f-5f30-43a4-89e9-62f3e75057d3)

CUSTOMIZATION OF PLOTS
```
x = [1, 2, 3, 4, 5, 6]
y = [2, 4, 1, 5, 2, 6]
plt.plot(x,y, color='red', linewidth=3, linestyle='--', marker = 'o', markerfacecolor='blue', markersize=10)
plt.ylim(1, 8)
plt.xlim(1, 8)
plt.xlabel("x-axis")
plt.ylabel("y-axis")
plt.title("Some cool customization")
plt.show()
```
![image](https://github.com/user-attachments/assets/92e5e764-eb77-4661-8397-be17a039e734)


SCATTER PLOT
```
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color='Blue')
plt.show()
````
![image](https://github.com/user-attachments/assets/4deec4ac-cf94-4600-9e1e-011e0a88332a)

# Result:
Thus the graphs are obtained.
