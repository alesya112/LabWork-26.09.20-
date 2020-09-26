# LabWork-26.09.20-
#Упражение 5 "Отображение погрешностей"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
y=int(input())
p=int(input())
p_f = np.poly1d(p)
plt.errorbar(x, y, xerr=0.05, yerr=0.1)
p_f([x])
p_f([y])
plt.grid()
plt.show()
