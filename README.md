# 🧮 Matrices - Suma de Elementos (PSeInt) 🚀

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PSeInt](https://img.shields.io/badge/PSeInt-3.0-orange.svg)](http://pseint.sourceforge.net/)
[![Stars](https://img.shields.io/github/stars/FeibertGuzman/Matrices?style=social)](https://github.com/FeibertGuzman/Matrices/stargazers)

---

## 🧭 Tabla de Contenido

* [📌 Descripción](#-descripción)
* [🎯 Objetivo](#-objetivo)
* [🧠 Fundamentos](#-fundamentos)
* [🔄 Diagrama de Flujo](#-diagrama-de-flujo)
* [💻 Pseudocódigo](#-pseudocódigo)
* [⚙️ Requisitos](#️-requisitos)
* [🚀 Ejecución](#-ejecución)
* [📥 Instalación](#-instalación)
* [📁 Estructura](#-estructura-del-proyecto)
* [🧪 Ejemplo](#-ejemplo-de-salida)
* [📊 Complejidad](#-complejidad)
* [🔁 Extensiones](#-extensiones)
* [🧪 Testing (didáctico)](#-testing-didáctico)
* [🤝 Contribuciones](#-contribuciones)
* [📜 Licencia](#-licencia)

---

## 📌 Descripción

Implementación en **PSeInt** de un algoritmo para **sumar los elementos de una matriz 3x3**.

Aunque es un ejercicio base, aquí se trata como un micro–proyecto serio: documentación clara, extensibilidad y enfoque pedagógico.

---

## 🎯 Objetivo

* Comprender el recorrido de matrices
* Aplicar ciclos anidados
* Introducir acumuladores
* Preparar base para algoritmos más complejos

---

## 🧠 Fundamentos

Conceptos clave:

* Arreglos bidimensionales
* Iteración controlada
* Acumulación
* Entrada interactiva

---

## 🔄 Diagrama de Flujo

📌 Recomendación profesional:

* Guarda el diagrama en `/docs/diagrama.png`
* Usa herramientas como draw.io o Lucidchart

```md
/docs
  └── diagrama.png
```

---

## 💻 Pseudocódigo

```pseudocode
Proceso SumarElementosMatriz
    Definir matriz[3,3] Como Entero
    Definir suma Como Entero
    suma <- 0

    Para i Desde 1 Hasta 3 Hacer
        Para j Desde 1 Hasta 3 Hacer
            Escribir "Ingrese elemento [", i, ",", j, "] :"
            Leer matriz[i][j]
            suma <- suma + matriz[i][j]
        Fin Para
    Fin Para

    Escribir "La suma de todos los elementos es: ", suma
Fin Proceso
```

---

## ⚙️ Requisitos

* PSeInt 3.0 o superior

---

## 🚀 Ejecución

```bash
# Abrir PSeInt
# Ejecutar archivo .psc
```

Pasos:

1. Abrir PSeInt
2. Cargar el archivo
3. Ejecutar
4. Ingresar datos

---

## 📥 Instalación

```bash
git clone https://github.com/FeibertGuzman/Matrices.git
cd Matrices
```

---

## 📁 Estructura del proyecto

```
Matrices/
│── README.md
│── matriz.psc
│── docs/
│   └── diagrama.png
│── examples/
│   └── output.txt
```

---

## 🧪 Ejemplo de salida

```
Ingrese elemento [1,1]: 2
Ingrese elemento [1,2]: 3
...
La suma de todos los elementos es: 45
```

---

## 📊 Complejidad

* Tiempo: O(n²)
* Espacio: O(n²)

Donde n = dimensión de la matriz.

---

## 🔁 Extensiones

Ideas para escalar el proyecto:

* ✅ Matrices dinámicas (n x m)
* ✅ Validación de entrada
* ✅ Promedio de elementos
* ✅ Búsqueda de máximos/mínimos
* ✅ Versión en Python / Java / C++
* ✅ Interfaz gráfica (nivel pro 😏)

---

## 🧪 Testing (didáctico)

Casos sugeridos:

| Caso      | Entrada | Resultado esperado |
| --------- | ------- | ------------------ |
| Normal    | 1..9    | 45                 |
| Ceros     | todo 0  | 0                  |
| Negativos | -1..-9  | -45                |

---

## 🤝 Contribuciones

Flujo recomendado:

```bash
fork → clone → branch → commit → push → PR
```

Buenas prácticas:

* Commits descriptivos
* Código limpio
* Documentación actualizada

---

## 📜 Licencia

MIT License

---

## 👨‍💻 Autor

**Feibert Guzmán**

---

## ⭐ Apóyalo

Si este repo te ayudó:

👉 Dale estrella ⭐
👉 Compártelo
👉 Úsalo en clase

---

## 🧠 Nota final

Este no es “solo un ejercicio”.

Es la base de estructuras más complejas como:

* Procesamiento de imágenes
* Machine Learning
* Simulación numérica

Sí… todo empieza con un simple `for` bien hecho 😄
