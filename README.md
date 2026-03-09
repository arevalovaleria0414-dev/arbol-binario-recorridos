# 🌳 Implementación de un Árbol Binario en Python

## 📌 Descripción del Proyecto

Este proyecto implementa una estructura de datos **Árbol Binario de Búsqueda (Binary Search Tree)** utilizando el lenguaje de programación Python.
El programa permite ingresar una serie de números que son almacenados en el árbol y posteriormente realizar diferentes recorridos para acceder a los datos.

Los recorridos implementados en el programa son:

* **InOrder**
* **PreOrder**
* **PostOrder**

Estos recorridos permiten explorar los nodos del árbol en distintos órdenes y son fundamentales en el estudio de estructuras de datos.

---

# 🧠 Conceptos utilizados

Este programa se basa en conceptos fundamentales de estructuras de datos:

### Nodo

Un **nodo** es la unidad básica del árbol. Cada nodo contiene:

* Un valor
* Una referencia al nodo izquierdo
* Una referencia al nodo derecho

### Árbol Binario

Un **árbol binario** es una estructura jerárquica en la que cada nodo puede tener como máximo **dos hijos**:

* Hijo izquierdo
* Hijo derecho

En un **árbol binario de búsqueda**:

* Los valores **menores** se ubican a la izquierda
* Los valores **mayores** se ubican a la derecha

---

# 🔁 Tipos de Recorridos

El programa implementa tres tipos de recorridos sobre el árbol.

### InOrder

Orden de recorrido:

Izquierda → Raíz → Derecha

Este recorrido permite obtener los valores **ordenados de menor a mayor**.

---

### PreOrder

Orden de recorrido:

Raíz → Izquierda → Derecha

Este recorrido se utiliza comúnmente para **copiar o reconstruir árboles**.

---

### PostOrder

Orden de recorrido:

Izquierda → Derecha → Raíz

Este recorrido se utiliza frecuentemente en procesos como **eliminación de árboles**.

---

# ⚙️ Funcionamiento del Programa

El programa realiza los siguientes pasos:

1. Solicita al usuario la cantidad de números que desea ingresar.
2. Inserta los números dentro del árbol binario.
3. Organiza los nodos automáticamente según las reglas del árbol binario de búsqueda.
4. Realiza los recorridos:

   * InOrder
   * PreOrder
   * PostOrder
5. Muestra los resultados en pantalla.

---

# ▶️ Ejecución del Programa

Para ejecutar el programa es necesario tener **Python instalado** en el sistema.

En la terminal o consola ejecutar:

```
python arbol_binario.py
```

---

# 💻 Ejemplo de Ejecución

Entrada del usuario:

```
¿Cuántos números desea ingresar?: 5

Ingrese número: 8
Ingrese número: 3
Ingrese número: 10
Ingrese número: 1
Ingrese número: 6
```

Resultado del programa:

```
Recorrido InOrder:
1 3 6 8 10

Recorrido PreOrder:
8 3 1 6 10

Recorrido PostOrder:
1 6 3 10 8
```

---

# 📂 Estructura del Proyecto

```
arbol-binario
│
├── arbol_binario.py
└── README.md
```

---

# 🎯 Objetivo Académico

El objetivo de este proyecto es comprender el funcionamiento de las **estructuras de datos dinámicas**, especialmente los **árboles binarios**, y analizar cómo los diferentes recorridos permiten acceder y procesar la información almacenada en el árbol de distintas maneras.

Este ejercicio forma parte del estudio de **estructuras de datos y algoritmos**, fundamentales en el desarrollo de software.

---

# 👨‍💻 Autor

Brayan Felipe Ortega López

---

# 📚 Referencias

Algar, M., & Fernández de Sevilla, M. (2019). *Introducción práctica a la programación con Python*. Editorial Universidad de Alcalá.

Joyanes, L. (2020). *Fundamentos de programación: algoritmos, estructuras de datos y objetos*. McGraw-Hill.

Lopez, B. (2012). *Estructuras de datos orientadas a objetos*. Alfaomega.
