# programa-de-Nallely-y-Lesli
def suma(a, b):
    """Devuelve la suma de a y b."""
    return a + b

def resta(a, b):
    """Devuelve la resta de a menos b."""
    return a - b

def main():
    print("Programa que suma y resta dos números.")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))

    print(f"La suma de {num1} y {num2} es: {suma(num1, num2)}")
    print(f"La resta de {num1} menos {num2} es: {resta(num1, num2)}")

if __name__ == "__main__":
    main()
def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "No se puede dividir por cero."
    return a / b

def main():
    print("Elige una opción:")
    print("1. Multiplicar")
    print("2. Dividir")
    opcion = input("Opción (1/2): ")

    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))

    if opcion == '1':
        resultado = multiplicar(a, b)
        print(f"El resultado de multiplicar es: {resultado}")
    elif opcion == '2':
        resultado = dividir(a, b)
        print(f"El resultado de dividir es: {resultado}")
    else:
        print("Opción inválida.")

if __name__ == "__main__":
    main()
