---
title: Blog
layout: "page"
icon: fa-pencil-alt
order: 3
---

# ***Impresión de datos en C++. "Hola mundo".***


Uno de los primeros pasos con los que se encuentra una persona que quiere aprender un lenguaje de programación es la impresión en pantalla de texto y de variables (además de saber definir éstas). Lo que entendemos todos como el ya clásico "Hola mundo".

C++ también cuenta, como C, con unas librerías estándar para esta tarea. A diferencia de C, las funciones de estas librerías para la impresión de datos no requieren especificar el formato de las variables. Esto puede resultar cómodo en la mayoría de ocasiones, pero en otras no. Para todo lo demás, siempre se pueden incluir librerías de C en un código en C++.

**Cómo imprimir en C++.**

La librería que nos dará la posibilidad de imprimir texto y variables en C++ será <iostream>. Vamos a poner un ejemplo de cómo usarlo para imprimir texto además de dos variables.


1. #include <iostream>
2.  
3. using namespace std;
4.  
5. int main() {
6.     int a = 345;
7.     char b = 'x';
8.  
9.     cout <<"Hola mundo"<<endl<<"a es "<<a<<" y b es "<<b<<endl;
10.  
11.     system("PAUSE");
12.     return 0;
13. }


# ***Máximo común divisor y mínimo común múltiplo. Algoritmo de Euclides en C.***

Máximo común divisor: es el mayor número entero que divide a dos o más números enteros dejando una división exacta (su residuo o resto es 0).

Mínimo común múltiplo: es el número que es el menor múltiplo común de dos o más números.

**¿Qué es el algoritmo de Euclides?**

Es un proceso lógico por el cual, dados dos números enteros, se calcula su máximo común divisor. Llamemos a y b a esos dos números.

Calculamos el resto de la división entera a/b.
Si el resto es 0, a es el mínimo común múltiplo.
Si el resto no es 0, le damos a a ese valor. Repetimos el primer paso.
Esto tiene su base en que a y b tienen el mismo M.C.D. que b y el resto de a/b. 

mcd(a,b) = mcd(b,(a%b));

a%b es el resto de la división a/b.
Implementación en C/C++ del algoritmo de Euclides. Función para el M.C.D.

1. int mcd(int a,int b) {
2.     if(b == 0) return a;
3.     else return mcd(b,a%b);
4. }
Calcular el mínimo común múltiplo.

Resultará del cocientre entre el producto de los números y el máximo común divisor de éstos.

1. int mcm(int a,int b) {
2.     return (a*b)/mcd(a,b);
3. }
