# Crear-números-random-en-Python
'''podemos crear números aleatorios con python dentro de un rango deseeado,
como por ejemplo un dado creando números del 1 al 6, o para un sorteo de con números del 0 al 999.
en este caso creare números del 1 al 6 y llamare "dado" a la aplicacion'''

#Primero importamos random 

import random

#Segundo voy a usar la palabra dado y le voy a indicar que hacer

dado = (random.randint(1, 6))

#los números 1 y 6 indican el rango en el que quiero que se creen los números, ustedes pueden modificarlos y colocar los números que deseen
#una vez tenemos definido lo que queremos usamos print para que la aplicacion corra y nos muestre un resultado

print (dado)

#hemos creado un dado ;)
