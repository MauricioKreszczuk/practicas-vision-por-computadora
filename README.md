# Introducción a Visión por Computadora - Trabajos Prácticos

Este repositorio contiene las resoluciones de las guías de trabajos prácticos desarrolladas para la materia Introducción a Visión por Computadora de la Licenciatura en Ciencia de Datos (UNSAM). El espacio está diseñado para almacenar y documentar el avance en el procesamiento digital de imágenes, análisis matricial y modelos de visión.

## Tecnologías Utilizadas

* Python 3
* OpenCV (cv2): Para lectura, transformaciones y operaciones de interpolación sobre imágenes.
* NumPy (np): Para el procesamiento algebraico matricial, rebanado (slicing) de tensores y manipulación de arreglos multidimensionales.
* Matplotlib (plt): Para la visualización de canales de color, histogramas y renderizado de resultados.

---

## Proyectos y Guías Implementadas

### Guía 0: Fundamentos de Procesamiento de Imágenes
* Exploración Estructural: Carga de archivos y análisis de dimensiones, tamaños y canales de una imagen digital.
* Conversión de Espacios de Color: Corrección explícita del orden de canales BGR a RGB para garantizar consistencia cromática en visualizaciones.
* Manipulación Algebraica de Píxeles: Extracción de vectores de color individuales y truncamiento de canales (clipping) con NumPy para evitar el desbordamiento de enteros.
* Aislamiento de Planos: Separación y re-ensamblado de componentes cromáticos independientes mediante la reconstrucción de tensores con np.stack.
* Región de Interés (ROI): Recorte de sub-matrices y reescalado mediante interpolación por vecinos cercanos (INTER_NEAREST) para evidenciar la estructura discreta de los píxeles.

*(Nota: Los enunciados y soluciones de las siguientes guías se irán incorporando a este repositorio a lo largo del semestre).*

---

## Estructura del Proyecto

```text
├── entrega_0.ipynb       # Notebook con la implementación de la Guía 0
├── orangutan.jpg         # Imagen de prueba utilizada en los experimentos iniciales
└── README.md             # Documentación general del repositorio
