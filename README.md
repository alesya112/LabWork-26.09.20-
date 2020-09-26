# LabWork-26.09.20-
#Упражнение 1 "Запись алгебраических выражений"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
y=np.log(((np.e**(1/(np.sin(x)+1))/(5/4+1/x**15))))/np.log((1+x**2))
print(y)
