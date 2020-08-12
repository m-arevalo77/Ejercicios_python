# ejercicio1_prom
Ejercicio para determinar el máximo, mínimo y promedio
Anexo Código python

from numpy import mean
num_list = [24,64,15,74]
avg=mean(num_list)
print("El promedio es", round (avg,2) , "El mayor es: " + str(max(num_list)), "El menor es: " + str(min(num_list)))
