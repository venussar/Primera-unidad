# TAREA 1 – Programación Científica 

Este notebook contiene la resolución de varios ejercicios enfocados en **funciones, recursión y simulación numérica** en Python.  
Fue desarrollado en **Google Colab**, e incluye el uso de bibliotecas matemáticas y gráficas como `math`, `numpy` y `matplotlib`.

---

## Contenido

### **1. Clasificación de números**

Diseño de funciones que determinan si un número pertenece a distintas clases matemáticas según la suma de sus divisores:

| Tipo de número | Condición matemática | Función |
|----------------|----------------------|----------|
| Defectivo | Suma de divisores < número | `numeros_defectivos(a)` |
| Abundante | Suma de divisores > número | `numeros_abundantes(a)` |
| Semiperfecto | Suma de algunos divisores = número | `numeros_semiperfectos(a)` |
| Perfecto | Suma de todos los divisores = número | `numeros_perfectos(a)` |
| Primo | Divisible solo por 1 y sí mismo | `numeros_primos(a)` |


---

### 2. Recursión en Python

Exploración del concepto de **recursividad** mediante tres funciones matemáticas:

- `factorial(n)`: calcula el factorial de un número de forma recursiva.  
- `catalan(n)`: calcula el número de Catalán \( C_n = \frac{4n - 2}{n + 1} C_{n-1} \).  
- `g(m, n)`: obtiene el **máximo común divisor (MCD)** usando el algoritmo recursivo de **Euclides**.

Ejemplo:
```python
factorial(5)      # 120
catalan(5)        # 42
g(24, 36)         # 12
```

---

### **3. Movimiento parabolico de un proyectil**

Simulacion del movimiento de un proyectil lanzado con:
- Velocidad inicial: `v0 = 4.0 m/s`
- Ángulo: `45°`
- Gravedad: `g = 9.81 m/s²`

Se grafican las ecuaciones de movimiento

 El gráfico muestra la **trayectoria parabólica** hasta que el proyectil toca el suelo.

---

### 4. Órbitas planetarias 

Cálculo de parámetros orbitales de un planeta alrededor del Sol a partir de la **distancia al perihelio** y la **velocidad en el perihelio**:


---

### 5. Series y Aproximaciones Numéricas // EN EL APARTADO LAB_1

Esta sección se enfoca en la implementación y el análisis de series matemáticas para la aproximación de funciones y constantes:

| Ejercicio | Objetivo | Función Clave |
| :--- | :--- | :--- |
| **Aproximación de $\sin(x)$** | Graficar la función seno usando la **Serie de Taylor** (con $N$ términos) y compararla con la implementación de NumPy, analizando la convergencia. | `sine_taylor(x, N)` |
| **Cálculo del Factorial** | Implementación del cálculo factorial (Ejercicio 2). | `calcular_factorial(num)` |
| **Aproximación de $\pi$** | Uso de la **Serie de Leibniz** para aproximar el valor de $\pi$ (Ejercicio 3). | `leibniz_pi(terminos)` |

---

### 📚 Temas Aplicados

* Programación estructurada y modular
* Funciones recursivas
* Lógica matemática y teoría de números
* Física del movimiento parabólico
* Leyes de Kepler y gravitación universal
* Análisis de convergencia de series y aproximaciones
* Visualización de datos y comparación de precisión



##  Autor

**Carolina Andrea Rodas Castañeda**  
Curso: Metodos Computacionales – Universidad De Antioquia  
