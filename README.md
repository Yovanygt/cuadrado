
<h3> Ejercicio 4: solicite al usuario ingresar un numero que sera el lado de un cuadrado y escriba un
programa que dibuje dicho cuadrado de la siguiente manera: suponga que el usuario ingreso 4 </h3>

<H1>C++</H1>

``````C
#include <iostream>
using namespace std;

int main() {
    int lado;
    char caracter;

    cout << "Ingrese el lado del cuadrado: ";
    cin >> lado;

    cout << "Ingrese el caracter a utilizar: ";
    cin >> caracter;

    for (int i = 0; i < lado; i++) {
        for (int j = 0; j < lado; j++) {
            if (i == 0 || i == lado - 1 || j == 0 || j == lado - 1) {
                cout << caracter << " ";
            } else {
                cout << "  "; // Espacio en blanco para el interior del cuadrado
            }
        }
        cout << endl;
    }

    return 0;
}
``````

<h1>PHYTON </H1>
`````````` C++


lado = int(input("Ingrese el lado del cuadrado: "))
caracter = input("Ingrese el caracter a utilizar: ")

for i in range(lado):
    for j in range(lado):
        if i == 0 or i == lado - 1 or j == 0 or j == lado - 1:
            print(caracter, end=' ')
        else:
            print('  ', end=' ')  # Espacio en blanco para el interior del cuadrado
    print()  # Salto de línea para pasar a la siguiente fila



#   c u a d r a d o  
 