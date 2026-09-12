# 🚀 Optimización de Algoritmos: Ajuste de Regresión Lineal

<!-- Animación de Código/Matemáticas -->
<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcG9wYWw0b2c3dXZyd3R6bTczcWFmMGh5aGhqbTl5aGhqbTl5aGhqbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/2IudUHdI075HL02Pkk/giphy.gif" width="180" alt="Algorithm Animation" />
</div>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab" />
  <img src="https://img.shields.io/badge/Optimización-Matemática-blueviolet?style=for-the-badge" alt="Math" />
</p>

> **Objetivo del Proyecto:** Diseño, implementación y evaluación de tres algoritmos computacionales de optimización para ajustar los parámetros (β0 y β1) de un modelo de regresión lineal simple, minimizando el Error Cuadrático Medio (ECM).

---

### 🧬 Algoritmos Evaluados

El proyecto compara tres paradigmas diferentes de optimización aplicados a un dataset nutricional real (menú de McDonald's):

1.  🔍 **Búsqueda en Malla (Grid Search):** 
    *   *Enfoque:* Búsqueda a ciegas / exhaustiva.
    *   *Resultado:* Garantiza encontrar la mejor solución en el espacio definido, pero con un alto costo computacional (101,101 iteraciones evaluadas).
2.  ⛰️ **Ascenso de la Colina (Hill Climbing):**
    *   *Enfoque:* Búsqueda local determinista.
    *   *Resultado:* Convergencia rápida y eficiente hacia un óptimo local mediante pequeñas variaciones de parámetros.
3.  🧬 **Algoritmo Genético:**
    *   *Enfoque:* Búsqueda poblacional (selección por torneo, cruza aritmética y mutación gaussiana).
    *   *Resultado:* Estabilidad y consistencia en múltiples ejecuciones, logrando una optimización rápida en menos de 100 generaciones.

---

### 📊 Resultados y Desempeño

Mediante 30 ejecuciones independientes por método, se analizó la eficiencia, el tiempo de ejecución y la reducción del error (ECM). 

*   El modelo logró modelar con éxito la fuerte relación lineal entre los **Carbohidratos** (variable predictora) y las **Calorías** (variable objetivo).
*   Se generaron mapas de calor y superficies 3D para visualizar la forma convexa de la función objetivo y la evolución de la convergencia.

---

### 💻 Código Fuente

Los algoritmos fueron desarrollados completamente en lenguaje R. Puedes explorar y ejecutar los notebooks directamente en Google Colab:

*   [Abrir Búsqueda en Malla en Colab](https://colab.research.google.com/drive/1K1cQLX9eHtVRoDp4je8JbRGlGGXHpZFy?usp=sharing)
*   [Abrir Ascenso de la Colina en Colab](https://colab.research.google.com/drive/1RqIcjyuwbNazkUOVJT-R1IKvIQVgjjpX?usp=sharing)
*   [Abrir Algoritmo Genético en Colab](https://colab.research.google.com/drive/1e80ibcEdhstdI1WdhxbVm7b9Jw5mMbj6?usp=sharing)

<div align="center">
  <a href="https://github.com/vanemendez25/optimizacion-algoritmos-regresion/blob/main/Protecto%20final_Algoritmos.pdf">
    <img src="https://img.shields.io/badge/📄_Ver_Reporte_Completo-PDF-red?style=for-the-badge" alt="Ver PDF" />
  </a>
</div>

---

### 👩🏻‍💻 Equipo de Desarrollo
Proyecto para la experiencia educativa *Algoritmos de Optimización y Simulación* (Universidad Veracruzana):
*   **Vanessa Méndez Lara** - [@vanemendez25](https://github.com/vanemendez25)
*   **Karla Valeria Fernández Mendoza**- [@Karla800](https://github.com/karla800)
*   **Vanessa Lizeth Rivera Baez**- [@vanessarivera-bw](https://github.com/vanessarivera-bw)
