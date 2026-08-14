# Aprendizaje de máquina - estadístico 

Repositorio oficial del curso de **Aprendizaje de máquina - estadístico**.

En este repositorio se publicarán:

- Notas de clase.
- Tareas.
- Ejemplos de código.
- Material complementario (si es que lo hay).

---

# Objetivo del curso

Al finalizar el curso, el estudiante será capaz de formular problemas reales en términos de Machine Learning, seleccionar metodologías apropiadas, construir y evaluar modelos de aprendizaje supervisado y no supervisado, interpretar resultados, cuantificar la incertidumbre de las predicciones y comunicar hallazgos de manera efectiva en un contexto de consultoría analítica.

---

# Contenido del curso

## 1. Introducción al Machine Learning

- Motivación e historia del Machine Learning.
- Tipos de aprendizaje.
- Formulación de problemas.
- Conceptos fundamentales.
- Ciclo de vida de un proyecto de Machine Learning.

---

## 2. Aprendizaje Supervisado: Regresión

- Formulación de problemas de regresión.
- Regresión lineal.
- Optimización y descenso por gradiente.
- Evaluación y generalización.
- Regularización.
- Ingeniería y transformación de variables.
- K-Nearest Neighbors (KNN) para regresión.
- Árboles de decisión para regresión.
- Métricas de evaluación.
- Validación cruzada.
- Selección de hiperparámetros.

** Primer Parcial (Tareas 1–7)**

---

## 3. Aprendizaje Supervisado: Clasificación

- Problemas de clasificación.
- Regresión logística.
- Clasificación multiclase.
- Evaluación de clasificadores.
- K-Nearest Neighbors (KNN).
- Árboles de decisión.
- Máquinas de Vectores de Soporte (SVM).

---

## 4. Aprendizaje No Supervisado

- Clustering.
- K-Means.
- Evaluación de clustering.
- Clustering basado en densidad (DBSCAN).
- Reducción de dimensionalidad.
- Análisis de Componentes Principales (PCA).

---

## 5. Tópicos Avanzados

- Métodos de ensamble.
- No hay almuerzo gratis.
** Segundo Parcial (Tareas 8–14)**
- Redes neuronales.
- Confiabilidad de predicciones.
- Conformal Prediction.
- Buenas prácticas para el desarrollo de modelos.
- Equidad y sesgos algorítmicos.



---

## Temas de las tareas y fechas de entrega
*NOTA*: Me las deberan mandar a mi correo del ITAM. Tienen hasta las 23:59 para mandarlas y que se las tome en cuenta en su evaluación. 


| **Tarea** | **Fecha de entrega** | **Tema** |
|:---------:|:--------------------:|----------|
| 1 | Martes 18 de agosto | Tipos de aprendizaje, formulación de problemas y ciclo de vida de Machine Learning |
| 2 | Martes 25 de agosto | Regresión lineal: intuición, formulación e interpretación geométrica |
| 3 | Martes 1 de septiembre | Función de pérdida, mínimos cuadrados y solución analítica. Optimización: gradiente y descenso por gradiente |
| 4 | Martes 8 de septiembre | Generalización: overfitting, underfitting, sesgo-varianza y regularización |
| 5 | Martes 15 de septiembre | Ingeniería de variables |
| 6 | Martes 22 de septiembre | KNN y estimadores basados en árboles |
| 7 | Martes 29 de septiembre | Evaluación y selección de modelos de regresión. Validación cruzada |
| 8 | Jueves 8 de octubre | Regresión logística, Softmax y métricas de clasificación |
| 9 | Jueves 15 de octubre | KNN, árboles de clasificación y SVM |
| 10 | Jueves 22 de octubre | PCA |
| 11 | Jueves 29 de octubre | K-Means |
| 12–13 | Jueves 5 de noviembre | Evaluación de clustering y DBSCAN |
| 14 | Jueves 12 de noviembre | Ensambles: Random Forest y Gradient Boosting |

# Proyecto Final

El proyecto final consistirá en el desarrollo de un proyecto integral de Machine Learning con enfoque de consultoría analítica.

El trabajo deberá incluir:

- Formulación del problema.
- Comprensión y preparación de datos.
- Ingeniería de variables.
- Construcción de modelos.
- Evaluación y validación.
- Interpretación de resultados.
- Recomendaciones de negocio.
- Presentación ejecutiva.
- Enlace al repositorio con el código fuente.

---

# ML Championship

Durante el semestre se desarrollará una competencia de Machine Learning inspirada en plataformas como Kaggle.

Los estudiantes aplicarán técnicas de:

- Ingeniería de variables.
- Validación de modelos.
- Optimización de hiperparámetros.
- Ensambles.
- Modelado predictivo.

El objetivo será obtener el mejor desempeño predictivo sobre un conjunto de datos de prueba.

---

# Evaluación

| Actividad | Porcentaje |
|-----------|-----------:|
| Examen Parcial 1 | 25% |
| Examen Parcial 2 | 25% |
| Proyecto Final (Escrito + Presentación) | 30% |
| Tareas (14) | 20% |
| Competencia ML (Puntos Extra) | 5% |

---

# Organización del repositorio

```
.
├── tareas/
├── codigo/
├── datasets/
├── slides/
└── README.md
```

---

# Tecnologías

Durante el curso se utilizará principalmente Python para los ejemplos y código, sin embargo, el curso es agnóstico del lenguaje de programación (pueden usar java si quieren, compliquense la vida solos). O pueden usar R. 

---

# Guía de Uso del Repositorio - Aprendizaje Máquina (Estadístico) ITAM

## 1. Verificación de Git

Antes de comenzar, abre tu terminal y ejecuta:


git --version

Si aparece algo similar a git version 2.x.x, Git ya está instalado.

2. Clonar el Repositorio (Solo se hace una vez)

Entra al repositorio en GitHub, presiona Code -> HTTPS y copia la dirección.
Desde tu terminal, navega a la carpeta donde quieras guardarlo (ej. cd Documents o cd Desktop).
Ejecuta el comando:

git clone URL_DEL_REPOSITORIO


Entra a la carpeta del repositorio:

cd curso-machine-learning

Si usas Visual Studio Code, puedes abrirlo directamente con:
code .


3. Obtener Nuevas Notas y Tareas (Flujo de Git)
A lo largo del semestre se agregarán nuevos archivos. No es necesario volver a clonarlo.
Cada vez que quieras actualizar tu copia local con los últimos cambios, entra a la carpeta del repositorio y ejecuta:
git pull


Importante: No modificar directamente los archivos del repositorio
Para evitar conflictos con git pull, se recomienda que copies los ejercicios o notebooks a otra ruta antes de modificarlos:

Ejemplo: Si existe notebooks/regresion_lineal.ipynb, haz una copia como notebooks/regresion_lineal_tu_nombre.ipynb o trabaja en una carpeta personal ajena al repositorio.

Si modificas un archivo y posteriormente se actualiza en GitHub, Git detectará un conflicto al ejecutar git pull.

---

# Licencia

Este material fue desarrollado exclusivamente para fines académicos del curso de Aprendizaje de máquina-estadístico. Su reproducción o distribución fuera del curso es válida siempre y cuando sea con fines de distribución del conocimiento. 

