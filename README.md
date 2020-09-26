# LabWork-26.09.20-
#Упражение 4 "Построение графиков"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
text=str(input())
x = np.arange(x)

eval("('text')")
plt.xkcd()
with plt.xkcd():
    plt.pie([x])
    plt.title('x')
