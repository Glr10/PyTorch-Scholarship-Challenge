# Guía de uso del repositorio

Este repositorio reúne mis apuntes y ejercicios del **PyTorch Scholarship Challenge**,
un curso introductorio de *deep learning* con PyTorch. Aquí encontrarás cómo abrir,
ejecutar y aprovechar el material.

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `README.md` | Introducción al curso |
| `Notas.ipynb` | Apuntes: qué son los Gists, repaso de Python (bucle `while`) y `numpy.matmul` |
| `Lesson2.ipynb` | Lección 2: perceptrones como operadores lógicos (AND, OR, NOT) y el algoritmo del perceptrón |

## Cómo usar los notebooks

### Opción 1 — Google Colab (recomendada, sin instalar nada)

1. Abre el notebook que quieras en GitHub.
2. Haz clic en el botón **"Open In Colab"** que aparece al inicio del notebook.
   - Alternativa: entra a [colab.research.google.com](https://colab.research.google.com),
     ve a la pestaña **GitHub** y pega `Glr10/PyTorch-Scholarship-Challenge`.
3. Ejecuta cada celda con **Shift + Enter** (o el botón ▶ de la izquierda).

> Nota: algunas celdas de `Lesson2.ipynb` usan `files.upload()` para subir imágenes
> de los cuestionarios (por ejemplo `and-quiz.png`). Si no tienes esas imágenes,
> puedes saltarte esas celdas; no afectan a los cálculos.

### Opción 2 — Jupyter en tu computadora

```bash
git clone https://github.com/Glr10/PyTorch-Scholarship-Challenge.git
cd PyTorch-Scholarship-Challenge
pip install notebook numpy pandas
jupyter notebook
```

Se abrirá el navegador; haz clic en el `.ipynb` que quieras y ejecuta las celdas
con **Shift + Enter**.

### Opción 3 — Solo lectura

Abre los archivos `.ipynb` directamente en GitHub para leer el código y los apuntes
sin ejecutarlos.

## Qué vas a aprender en cada notebook

- **`Notas.ipynb`**
  - Qué es un *Gist* de GitHub para guardar snippets de código.
  - Repaso de Python: recorrer una lista con un bucle `while`.
  - `numpy.matmul`: producto de matrices en 1-D, 2-D y con *broadcasting*.

- **`Lesson2.ipynb`**
  - Perceptrones como operadores lógicos: configurar `weight1`, `weight2` y `bias`
    para reproducir las compuertas **AND**, **OR** y **NOT**.
  - El **algoritmo del perceptrón**: `stepFunction`, `prediction` y cómo se ajustan
    los pesos para clasificar puntos.

## Requisitos

- Python 3
- `numpy` y `pandas`
- (Opcional) Jupyter Notebook si trabajas en local
