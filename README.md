# 🧮 TAREA 1 – Programación Científica (Python + Colab)

Este notebook contiene la resolución de varios ejercicios enfocados en **funciones, recursión y simulación numérica** en Python.  
Fue desarrollado en **Google Colab**, e incluye el uso de bibliotecas matemáticas y gráficas como `math`, `numpy` y `matplotlib`.

---

## 📘 Contenido

### **1️⃣ Clasificación de números**

Diseño de funciones que determinan si un número pertenece a distintas clases matemáticas según la suma de sus divisores:

| Tipo de número | Condición matemática | Función |
|----------------|----------------------|----------|
| Defectivo | Suma de divisores < número | `numeros_defectivos(a)` |
| Abundante | Suma de divisores > número | `numeros_abundantes(a)` |
| Semiperfecto | Suma de algunos divisores = número | `numeros_semiperfectos(a)` |
| Perfecto | Suma de todos los divisores = número | `numeros_perfectos(a)` |
| Primo | Divisible solo por 1 y sí mismo | `numeros_primos(a)` |

🧩 **Ejercicio opcional:** se muestran los primeros 30 números de cada clase.

---

### **2️⃣ Recursión en Python**

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

### **3️⃣ Movimiento parabólico de un proyectil**

Simulación del movimiento de un proyectil lanzado con:
- Velocidad inicial: `v0 = 4.0 m/s`
- Ángulo: `45°`
- Gravedad: `g = 9.81 m/s²`

Se grafican las ecuaciones de movimiento:

\[
x(t) = v_0 \cos(\theta)t, \quad
y(t) = v_0 \sin(\theta)t - \frac{1}{2}gt^2
\]

📈 El gráfico muestra la **trayectoria parabólica** hasta que el proyectil toca el suelo.

---

### **4️⃣ Órbitas planetarias (Problema adicional)**

Cálculo de parámetros orbitales de un planeta alrededor del Sol a partir de la **distancia al perihelio** y la **velocidad en el perihelio**:

\[
v_2^2 - 2GM\frac{v_1}{\ell_1}v_2 - [v_1^2 - 2GM/\ell_1] = 0
\]

Una vez obtenido \(v_2\), se calculan:

| Parámetro | Fórmula | Descripción |
|------------|----------|-------------|
| \( \ell_2 \) | \( \ell_1 v_1 / v_2 \) | Distancia en el afelio |
| \( a \) | \( \frac{1}{2}(\ell_1 + \ell_2) \) | Semieje mayor |
| \( b \) | \( \sqrt{\ell_1 \ell_2} \) | Semieje menor |
| \( T \) | \( \frac{2\pi ab}{\ell_1 v_1} \) | Período orbital |
| \( e \) | \( \frac{\ell_2 - \ell_1}{\ell_2 + \ell_1} \) | Excentricidad |

Se prueban los resultados con:
- 🌍 **Tierra:** \( \ell_1 = 1.4710×10^{11} \, m \), \( v_1 = 3.0287×10^4 \, m/s \)
- ☄️ **Cometa Halley:** \( \ell_1 = 8.7830×10^{10} \, m \), \( v_1 = 5.4529×10^4 \, m/s \)

---

## 🧠 Temas aplicados

- Programación estructurada y modular  
- Funciones recursivas  
- Lógica matemática y teoría de números  
- Física del movimiento parabólico  
- Leyes de Kepler y gravitación universal  

---

## ⚙️ Requisitos

- Python 3.x  
- Google Colab o Jupyter Notebook  
- Bibliotecas:
  ```bash
  pip install numpy matplotlib
  ```

---

## 🚀 Ejecución

1. Abrir el archivo **`TAREA_1.ipynb`** en Google Colab.  
2. Ejecutar las celdas en orden.  
3. Observar los resultados en consola y gráficos generados.  

---

## 📚 Autor

**[Tu nombre aquí]**  
Curso: Programación Científica – Universidad X  
Profesor: [Nombre del docente]  
Fecha: [Mes/Año]
