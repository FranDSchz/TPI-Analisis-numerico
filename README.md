# Trabajos Prácticos de Análisis Numérico 🧠💻

Este repositorio contiene los Trabajos Prácticos Integradores (TPI) desarrollados para la materia **Análisis Numérico**  de la carrera de Ingeniería en Sistemas de Información (UTN-FRRe).

El objetivo de estos trabajos es aplicar los fundamentos del cálculo numérico y simbólico para resolver problemas matemáticos complejos, utilizando herramientas clave del ecosistema de Data Science en Python como Jupyter, NumPy, SciPy y Matplotlib.

### Aporte Personal

Aunque este repositorio es un fork del trabajo grupal, mi contribución principal se centró en la **implementación de los algoritmos, el análisis de los resultados y la generación de las visualizaciones de datos** en los Jupyter Notebooks.

---

## 🔬 Tareas y Métodos Implementados

El repositorio cubre dos grandes áreas de la materia, cada una con su propio notebook y objetivos, basados en las consignas oficiales.

### 1. Fundamentos de Métodos Numéricos

* **Notebook:** [`Grupo14_TPMetodosNumericos.ipynb`](./notebooks/Grupo14_TPMetodosNumericos.ipynb)

En este trabajo se programaron desde cero los algorittmos numéricos fundamentales para:

* **Derivación Numérica:**
    * Implementación de diferencias finitas (hacia adelante, hacia atrás y centradas).
    * Análisis del error relativo de cada método.

* **Integración Numérica:**
    * Implementación de la **Regla del Trapecio** y las **Reglas de Simpson (1/3 y 3/8)**.

* **Resolución de Ecuaciones Diferenciales Ordinarias (EDOs):**
    * Implementación de los métodos de **Euler**, **Euler Mejorado** y **Runge-Kutta de 4º Orden (RK4)**.

### 2. Sistemas de Ecuaciones Diferenciales y Estabilidad

* **Notebooks:**
    * Investigación: [`Grupo14_TPsistemasInvest.ipynb`](./notebooks/Grupo14_TPsistemasInvest.ipynb)
    * Actividades: [`Grupo14_TPsistemasActividades.ipynb`](./notebooks/Grupo14_TPsistemasActividades.ipynb)

Este trabajo se enfocó en el análisis de sistemas de EDOs y la comparación entre herramientas simbólicas y numéricas:

* **Investigación de Librerías:**
    * Análisis comparativo de `NumPy`, `SymPy` y `SciPy` para cálculo matricial, resolución de ecuaciones, y transformada de Laplace.

* **Análisis de Sistemas y Estabilidad:**
    * Resolución de sistemas de EDOs homogéneos y no homogéneos.
    * Clasificación y análisis de la estabilidad de puntos de equilibrio.
    * Graficación de campos vectoriales asociados a los sistemas.

---

## 🛠️ Stack Tecnológico

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-313131?style=for-the-badge&logo=matplotlib&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-80C942?style=for-the-badge&logo=scipy&logoColor=white)
![SymPy](https://img.shields.io/badge/SymPy-3B5524?style=for-the-badge&logo=sympy&logoColor=white)

---

## ⚙️ Cómo Ejecutar los Notebooks

Para explorar el análisis en tu máquina local:

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/FranDSchz/TPI-Analisis-numerico.git
    cd TPI-Analisis-numerico
    ```
2.  **Crea y activa un entorno virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    # venv\Scripts\activate    # Windows
    ```
3.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Inicia Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
Esto abrirá tu navegador. Navega a la carpeta `notebooks/` y abre cualquiera de los archivos `.ipynb`.