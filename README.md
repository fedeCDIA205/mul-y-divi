# mul-y-divi
programa de federico 
# Programa que multiplica y divide dos números

# Pedir al usuario los dos números
num1 = float(input("Ingresa el primer número: "))
num2 = float(input("Ingresa el segundo número: "))

# Multiplicación
multiplicacion = num1 * num2
print(f"La multiplicación de {num1} y {num2} es: {multiplicacion}")

# División (verificando que el segundo número no sea cero)
if num2 != 0:
    division = num1 / num2
    print(f"La división de {num1} entre {num2} es: {division}")
else:
    print("No se puede dividir entre cero.")
