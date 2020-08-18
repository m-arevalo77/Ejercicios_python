# ejercicio1_prom
Ejercicio para determinar el máximo, mínimo y promedio

from numpy import mean
num_list = [24,64,15,74]
avg=mean(num_list)
print("El promedio es", round (avg,2) , "El mayor es: " + str(max(num_list)), "El menor es: " + str(min(num_list)))


#Ejercicio edad de la población

from random import randint 
edad_habitantes = [randint(1, 100) for i in range(randint(1000, 75000))] 
menores, mayores = len(list((filter(lambda edad: edad<18 , edad_habitantes)))), len(list(filter(lambda edad: edad>=18, edad_habitantes))) 
print(f"Población total: {len(edad_habitantes)}") 
print(f"Porcentaje de menores de edad: {menores/len(edad_habitantes)*100}. Porcentaje de mayores de edad: {mayores/len(edad_habitantes)*100}")

#Ejercicio municipalidad


import random 
municipality = [random.sample(range(1, 45001), 6) 
for x in range(0, 124)] 
results = [sum(col) for col in zip(*municipality)] 
print("The winner was: " + str(results.index(max(results))))


#Ejecicio partidos políticos


import numpy as np
partidos = ["socio-democratico","ultra-derechista","primero-los-ricos","centro demoniaco","cambio invertido","alianza queremos más pobres"]
votos=np.random.randint(1,4500,(123,6)) 
print(f"El ganador es el partido 
{partidos[np.argmax(votos.sum(axis=0))]} con {max(votos.sum(axis=0))} votos"

#Determinar ¿cuál es el número par?


numero_1 = int(input("Escriba un número entero: ")) 
numero_2 = int(input(f"Escriba un número entero mayor o igual que {numero_1}: ")) 
for i in range(numero_1, numero_2 + 1): 
 if i % 2 == 0:print(f"El número {i} es par.")



