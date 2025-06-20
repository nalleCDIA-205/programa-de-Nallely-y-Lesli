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
