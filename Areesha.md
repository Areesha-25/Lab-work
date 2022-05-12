```python
# Method:1
    
import numpy as np

 

x = np.array([0,20,40,60,80,100],float)
y = np.array([26.0, 48.6, 61.6,71.2,74.8,75.2],float)

 

xp= float(input("enter the value of x:"))
yp=0

 

for xi,yi in zip(x,y):
    yp += yi * np.prod((xp - x[x !=xi])/(xi - x[x !=xi]))
    
print('for x= %.2f, y=%f'%(xp,yp))
```

    enter the value of x:70
    for x= 70.00, y=73.867969
    


```python
# Method:2
    
    
import numpy as np

x = np.array([0,20,40,60,80,100],float)
y = np.array([26.0, 48.6, 61.6,71.2,74.8,75.2],float)

 

xp= float(input("enter the value of x:"))
yp=0

 

for xi,yi in zip(x,y):
    yp += yi * np.prod((xp - x[x !=xi])/(xi - x[x !=xi]))
    
print('for x= %.2f, y=%f'%(xp,yp))
```

    enter the value of x:80
    for x= 80.00, y=74.800000
    


```python

```
