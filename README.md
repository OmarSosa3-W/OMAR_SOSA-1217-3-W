![image](https://github.com/user-attachments/assets/ff4885c0-3239-457b-9f7e-e5ffae0047b2)# OMAR_SOSA-1217-3-W
Envío de 12 códigos
# PROGRAMA 1 
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")
#Se le pide al usuario su edad
edad=int(input("Escriba su edad: "))

#Si edad es menor o mayor a 18 imprimira un mensaje distinto en cada caso 
if edad<18:
    print("Usted no es mayor de edad")
elif edad>=18:
    print("Usted es mayor de edad")

![image](https://github.com/user-attachments/assets/1f3dfde3-f895-401f-8ab2-a18e07c5d753)
![image](https://github.com/user-attachments/assets/c412e5ba-0ec8-4d37-928d-3992018283e9)

# PROGRAMA 2
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Define una lista
mi_lista = [10, 20, 30, 40, 50]

#Inicia un índice
indice = 0

#Usa un bucle while para recorrer la lista
while indice < len(mi_lista):
    print(mi_lista[indice])  #Imprime el elemento en la posición indicada
    indice += 1  

![image](https://github.com/user-attachments/assets/8a9b7012-3d0d-4190-ae5a-b5605d50ff31)
![image](https://github.com/user-attachments/assets/ec64f223-ab41-489f-9a99-f8adc5b1b1d0)

# PROGRAMA 3
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

# Definir la cadena de texto
cadena = "Hola soy Omar de 3°W"

# Usar un bucle for para recorrer e imprimir cada carácter
for caracter in cadena:
    print(caracter)

![image](https://github.com/user-attachments/assets/d97a65e9-e876-46e9-8aab-f6500d6d04a7)
![image](https://github.com/user-attachments/assets/49ba84e1-c63c-4e5d-bd61-6cb72ed6cc3d)

# PROGRAMA 4
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

# Parte hacia arriba
for i in range(1, 6):  # De 1 a 5
    print('*' * i)

# Parte hacia abajo
for i in range(4, 0, -1):  # De 4 a 1
    print('*' * i)

![image](https://github.com/user-attachments/assets/a7f5425c-14cb-4733-8b30-c61a7253e7db)
![image](https://github.com/user-attachments/assets/ce6de78f-eed2-4791-9349-71e04730ba07)

# PROGRAMA 5
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Se le pide al usuario su Calificacion
califa=float(input("Escriba su calificacion: "))

#Dependiendo de la calificacion imprimira un mensaje u otro
if califa>=0 and califa<5:
    print("Suspendiste")
elif califa>=5 and califa<6:
    print("Suficiente")
elif califa>=6 and califa<7:
    print("Bien")
elif califa>=7 and califa<9:
    print("Notable")
elif califa>=9 and califa<=10:
    print("Sobresaliente")

![image](https://github.com/user-attachments/assets/b356c39e-b0b8-4301-ba43-1e5515420790)
![image](https://github.com/user-attachments/assets/38294e5d-4266-4076-b376-fe419018f146)

# PROGRAMA 6
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Se le pide al usuario un apellido un un nombre
nombre=str(input("Ingrese un nombre: "))
apellido=str(input("Ingrese un apellido: "))

#Dependiendo si el usuario uso el nombre y apelllido corrrectos imprimira un mensaje u otro
if nombre=="Daniel" and apellido=="Ramos":
    print(nombre, apellido)
elif nombre=="Daniel" and apellido != "Ramos" :
    print("Apellido incorrecto ")

elif nombre != "Daniel" and apellido == "Ramos" :
    print("Usuario desconocido")
else:
    print("Error...")

![image](https://github.com/user-attachments/assets/6a367e34-e53f-4032-bc9d-c9f9c35e1f08)
![image](https://github.com/user-attachments/assets/a5f3589d-cf96-482a-8a1f-53abae75c68f)

# PROGRAMA 7
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Se le piden a los usuarios 4 calificaciones
l1=float(input("Ingrese una calificacion: "))
print(" ")
l2=float(input("Ingrese la segunda calificacion: "))
print(" ")
l3=float(input("Ingrese la tercera calificacion: "))
print(" ")
l4=float(input("Ingrese la cuarta calificacion: "))
print(" ")

#Se declara una lista y la imprime
califas=[l1,l2,l3,l4]
print(califas)
print("Las calificaciones se ordenaran de menor a mayor a  continuacion")
print(" ")
califas.sort()#Ordena las calificaciones de menor a mayor
print(califas) #Imprime las calificaciones ordenadas

![image](https://github.com/user-attachments/assets/393b4c37-c7d3-4fc6-99c8-d11168a41ce3)
![image](https://github.com/user-attachments/assets/e26c66d2-1c1f-4115-a5f6-58dba10f72f9)

# PROGRAMA 8
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Declara una lista
frutas=["Platano","Frambuesa", "Manzana", "Cereza"]

#Si la cereza esta en la lista imprimira un mensaje si no imprimira otro mensaje
if "Cereza" in frutas:
    print("Cereza se encuentra en la lista")
else:
    print("Cereza no esta en la lista")

![image](https://github.com/user-attachments/assets/1c709eab-64e2-4d32-b331-9e3fcecab723)
![image](https://github.com/user-attachments/assets/e226e13c-b595-4a08-a9c8-924ee2dc44f1)

# PROGRAMA 9
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#Declara lista
nombre_apellido=["Luis", "Omar", "Sosa"]

#Imprime solo los apellidos
print(nombre_apellido)

![image](https://github.com/user-attachments/assets/89338b9c-8980-40d0-9900-ef1b018220c4)
![image](https://github.com/user-attachments/assets/204478ea-b882-4d61-820c-443c1c155027)

# PROGRAMA 10
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

#La variable que guardará la suma
suma = 0

#Usamos range para obtener solo los números pares entre 2 y 100
for i in range(2, 101, 2):  #El tercer parámetro (2) es el paso, que hace que se tome solo los pares
    suma += i

#Imprime el resultado
print("La suma de los números pares entre 2 y 100 es:", suma)

![image](https://github.com/user-attachments/assets/3bc3aaa9-68a8-4524-9611-67c68c18e58c)
![image](https://github.com/user-attachments/assets/31641261-e577-4acf-8bfa-b3ede5bc516c)

# PROGRAMA 11
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")


# Define un numero
numero = 7

# Usar un bucle for con un rango de 1 a 10 para imprimir la tabla
for i in range(1, 11):  # El rango va de 1 a 10 
    resultado = numero * i
    print(f"{numero} x {i} = {resultado}")

![image](https://github.com/user-attachments/assets/5254681c-81ca-4de0-99ea-664028ff3664)
![image](https://github.com/user-attachments/assets/04f4b17c-0b19-47de-8d80-9f02677a8278)

# PROGRAMA 12
print(" ")
print("Sosa Luis Omar 1217: Practica 3")
print(" ")

# Definir una lista
mi_lista = [10, 20, 30, 40, 50]

# Usa un bucle for para recorrer e imprimir los elementos de la lista
for elemento in mi_lista:
    print(elemento)

![image](https://github.com/user-attachments/assets/531cc5aa-bd97-432b-ae9c-8f86599105e9)
![image](https://github.com/user-attachments/assets/d7bd0d7b-2aed-42fe-9f41-83be7fa82bcf)


