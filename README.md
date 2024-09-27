# Examen1_Molina_leyva_Luis_Daniel_1201_3W
Examen 1

#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")

print(" ")

#Indica mi apellido Paterno
print ("Apellido Paterno:")
x = input()

print(" ")

#Indica mi apellido Materno
print ("Apellido Materno:")
z = input()

print(" ")

#Indica mi Nombre
print ("Nombre:")
y = input()

print(" ")

![image](https://github.com/user-attachments/assets/8d2145c0-3074-4149-b693-6d8088ece2ea)


Punto 4:

#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Leer tres valores
A = float(input("Ingrese el primer valor (A): "))
B = float(input("Ingrese el segundo valor (B): "))
C = float(input("Ingrese el tercer valor (C): "))

# Verificar si los valores son distintos
if A == B or A == C or B == C:
    print("¡Alerta! Los valores ingresados no deben ser iguales.")
else:
    # Encontrar el mayor y el menor
    mayor = max(A, B, C)
    menor = min(A, B, C)

    # Imprimir resultados
    print(f"El mayor valor es: {mayor}")
    print(f"El menor valor es: {menor}")

![image](https://github.com/user-attachments/assets/aafff5ee-ec63-4c9f-92aa-0e05a70fac76)


Punto 5:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Leer dos valores
valor1 = float(input("Ingrese el primer valor: "))
valor2 = float(input("Ingrese el segundo valor: "))

# Determinar el menor
menor = min(valor1, valor2)

# Imprimir el menor
print(f"El menor valor es: {menor}")
print(" ")
print(" ")
print(" ")

# Leer dos números
numero1 = float(input("Ingrese el primer número: "))
numero2 = float(input("Ingrese el segundo número: "))

# Sumar los números
suma = numero1 + numero2

# Desplegar el resultado
print(f"La suma de {numero1} y {numero2} es: {suma}")

![image](https://github.com/user-attachments/assets/ea86ef56-c636-4ffc-ae3c-97a6db254425)


Punto 6:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Leer la base y la altura del rectángulo
base = float(input("Ingrese la base del rectángulo (b): "))
altura = float(input("Ingrese la altura del rectángulo (h): "))

# Calcular el perímetro
perimetro = 2 * (base + altura)

# Calcular el área
area = base * altura

# Imprimir los resultados
print(f"El perímetro del rectángulo es: {perimetro}")
print(f"El área del rectángulo es: {area}")

![image](https://github.com/user-attachments/assets/bb826583-7278-4ab4-859e-8ebe7458f065)


Punto 7:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Solicitar al usuario un número natural
numero = int(input("Ingrese un número natural: "))

# Verificar si el número está en la primera docena
if 1 <= numero <= 12:
    print(f"El número {numero} se encuentra dentro de la primera docena.")
else:
    print(f"El número {numero} NO se encuentra dentro de la primera docena.")

![image](https://github.com/user-attachments/assets/0806da29-f7df-42b6-ace7-c0ad865ee80b)


Punto 8:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Solicitar al usuario un número natural
numero = int(input("Ingrese un número natural: "))

# Verificar si el número es par o impar
if numero >= 0:
    if numero % 2 == 0:
        print(f"El número {numero} es par.")
    else:
        print(f"El número {numero} es impar.")
else:
    print("Por favor, ingrese un número natural (0 o positivo).")

![image](https://github.com/user-attachments/assets/1ff23cf1-c886-426c-8963-295b4a82b8ad)


Punto 9:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Solicitar al usuario un número entero
numero = int(input("Ingrese un número entero: "))

# Verificar si el número es divisible por 7 y mayor a 40
if numero > 40 and numero % 7 == 0:
    print(f"El número {numero} es divisible por 7 y es mayor a 40.")
else:
    print(f"El número {numero} NO es divisible por 7 o NO es mayor a 40.")

![image](https://github.com/user-attachments/assets/de416d62-185e-4784-8c1e-375cd57e9c59)


Punto 10:

print(" ")
#MI Nombre, grupo y numero de control
print("Molina Leyva Luis Daniel 1201 3W")
print(" ")

# Solicitar al usuario un número entero
n = int(input("Ingrese un número entero no negativo: "))

# Verificar que el número sea no negativo
if n < 0:
    print("El factorial no está definido para números negativos.")
else:
    # Calcular el factorial
    factorial = 1
    for i in range(1, n + 1):
        factorial *= i

    # Imprimir el resultado
    print(f"El factorial de {n} es: {factorial}")

![image](https://github.com/user-attachments/assets/e7b3a341-c959-4e0e-b0ad-1c21a5c58999)

