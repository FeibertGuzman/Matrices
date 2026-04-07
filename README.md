# 🧮 Matrices - Suma de Elementos (PSeInt)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PSEINT](https://img.shields.io/badge/PSEINT-3.0-orange.svg)](http://pseint.sourceforge.net/)
[![GitHub stars](https://img.shields.io/github/stars/FeibertGuzman/Matrices.svg?style=social\&label=Star)](https://github.com/FeibertGuzman/Matrices/stargazers)

---

## 📌 Descripción

Este repositorio contiene un algoritmo desarrollado en **PSeInt** que permite **sumar los elementos de una matriz de 3x3**, solicitando los valores al usuario y mostrando el resultado final.

Es un ejemplo básico pero fundamental para comprender:

* Uso de **arreglos bidimensionales**
* Estructuras de control (**ciclos anidados**)
* Entrada y salida de datos

---

## 🎯 Objetivo

Demostrar de forma clara y práctica cómo recorrer una matriz y acumular valores utilizando pseudocódigo estructurado.

---

## 🧠 Lógica del algoritmo

1. Inicializar una variable acumuladora en 0
2. Recorrer la matriz usando dos ciclos (filas y columnas)
3. Solicitar cada valor al usuario
4. Sumar cada elemento a la variable acumuladora
5. Mostrar el resultado final

---

## 🔄 Diagrama de Flujo

Puedes incluir aquí el diagrama del algoritmo. Herramientas recomendadas:

* [https://lucidchart.com](https://lucidchart.com)
* [https://draw.io](https://draw.io)

> 💡 Sugerencia: Exporta el diagrama como imagen y colócalo en una carpeta `/docs` para mantener el repo organizado.

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

* Tener instalado **PSeInt 3.0 o superior**

---

## 🚀 Ejecución

1. Abrir PSeInt
2. Copiar el pseudocódigo o abrir el archivo `.psc`
3. Ejecutar el programa
4. Ingresar los valores solicitados

---

## 📥 Instalación / Clonar repositorio

```bash
git clone https://github.com/FeibertGuzman/Matrices.git
```

---

## 📁 Estructura del proyecto

```
Matrices/
│── README.md
│── matriz.psc
│── docs/
│   └── diagrama.png
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

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Puedes:

* Mejorar el algoritmo
* Agregar validaciones
* Extender a matrices dinámicas

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👨‍💻 Autor

**Feibert Guzmán**

---

## ⭐ Apóyalo

Si este proyecto te sirvió, dale una estrella ⭐ al repositorio. No cuesta nada y motiva bastante 😄
