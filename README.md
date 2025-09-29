# python-ejercicios-de-list-comprehension-y-normales-

# Ejercicios en Python – Comparación con y sin List Comprehension  

Este repositorio contiene **notebooks de Python** con ejercicios resueltos de programación básica, en dos versiones:  

- ✅ **Versión 1 – Sin list comprehension** → ejercicios resueltos con bucles tradicionales (`for`).  
- 🔜 **Versión 2 – Con list comprehension** → los mismos ejercicios reescritos de forma más compacta y “pythónica”.  

El objetivo es **comparar ambas aproximaciones** y comprender las ventajas e inconvenientes de cada estilo.  

---

## 📘 Contenido de la Versión 1 (sin list comprehension)  

Notebook: `sin_list_comprehension_ejercicios.ipynb`  

Ejercicios incluidos:  

- **Generación de listas de números**  
  - Crear una lista de los números del 1 al 10.  
  - Crear una lista con los números pares en un rango.  

- **Transformación de datos**  
  - Elevar al cuadrado cada número de una lista.  
  - Convertir una lista de strings a mayúsculas.  

- **Filtrado de datos**  
  - Obtener solo los números mayores que 5.  
  - Extraer palabras con más de 4 letras.  

- **Ejercicios combinados**  
  - Generar listas a partir de condiciones dentro de un bucle.  
  - Construir nuevas listas usando iteraciones anidadas.  

Todos los ejercicios están implementados con **bucles explícitos** (`for`, `while`) y variables auxiliares para mostrar el proceso paso a paso.  

---

## 📘 Contenido de la Versión 2 (con list comprehension)  

Notebook: `con_list_comprehension_ejercicios.ipynb` (pendiente de completar).  

Será la versión equivalente de los ejercicios anteriores, pero usando **list comprehensions** para:  

- Escribir menos código.  
- Hacer las soluciones más concisas y legibles.  
- Comparar con el enfoque tradicional.  

Ejemplo comparativo esperado:  

```python
# Versión sin list comprehension
numeros = []
for i in range(1, 11):
    numeros.append(i)

# Versión con list comprehension
numeros = [i for i in range(1, 11)]
