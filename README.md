# Pto1

from pprint import pprint
import math
from numpy import array, zeros, diag, diagflat, dot
import numpy as np 
def vaciarVector(vector)
     for j in range (0,tamano)
         vectoraux[i] = 0

if __name__== '__main__':
     tamano = int(input("Ingrese el numero de filas de la matriz cuadrada"))
     suma = 0.0
     vectoraux = []
     matriz = array([])
     
     for j in range (0,tamano)
         a = int(input("Ingrese un numero"))
         vectoraux.append(a)
     matriz.append(vectoraux)
     vaciarVector(vectoraux)
     
     for i in range (0,tamano)
             for j in range (0,tamano)
             a = int(input("Ingrese un numero"))
             vectoraux[j] = a
         matriz.append(vectoraux)
         vaciarVector(vectoraux)
         
     for i in range (0,tamano)
         for j in range (0,tamano)
         if((i-j) <= 0)
          suma = suma + matriz[i][j]
          
     print (suma)
