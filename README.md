# ☕ JavaTabular: Data Processing Library (Diseño y Arquitectura)

## 📌 Descripción del Proyecto
Diseño y conceptualización de una librería de software nativa en Java para la lectura, procesamiento y análisis de datos tabulares (formatos CSV). Este documento detalla la estructura lógica y los algoritmos propuestos para demostrar fundamentos sólidos de Programación Orientada a Objetos (POO), manejo de estructuras de datos y eficiencia algorítmica, sin depender de librerías externas.

## 🎯 Objetivos
- Diseñar la arquitectura lógica de una herramienta nativa y liviana para la ingesta de archivos CSV.
- Estructurar la lógica para la implementación de algoritmos de filtrado, ordenamiento y limpieza de datos desde cero.
- Definir patrones de diseño para manipular datos en entornos con restricciones de memoria o sin herramientas de alto nivel.

## 🛠️ Tecnologías y Herramientas Utilizadas
- **Lenguaje:** Java
- **Conceptos Aplicados:** Programación Orientada a Objetos, Estructuras de Datos, Complejidad Algorítmica (Notación Big O), Manejo de I/O.

## 🏗️ Arquitectura y Componentes Clave
El diseño de la librería se basa en los siguientes módulos conceptuales:
- **Módulo de I/O (Lectura/Escritura):** Lógica de parseo optimizada para mapear texto plano hacia estructuras de memoria eficientes (como `ArrayList` o `HashMap`), gestionando el manejo de excepciones.
- **Módulo de Filtrado:** Diseño de interfaces y métodos para iterar y extraer subconjuntos de datos basándose en criterios multicondicionales.
- **Módulo de Ordenamiento:** Conceptualización de algoritmos eficientes (como *Merge Sort* o *Quick Sort*) para ordenar grandes volúmenes de datos, priorizando un tiempo de ejecución óptimo de $O(n \log n)$.

## 🚀 Resultados del Diseño
- Se definió una arquitectura modular que facilita el mantenimiento, la escalabilidad y las pruebas unitarias del código.
- Se establecieron las bases lógicas para procesar datos tabulares puros priorizando el bajo consumo de memoria y la velocidad de ejecución nativa.

---
**Autor:** Matías Kronemberger | (Enlace a tu LinkedIn]](https://www.linkedin.com/in/matias-kronemberger/)
