# Procesamiento de Imágenes — Portafolio de Prácticas 📷🖥️

**Cristian Sombra** · Tecnicatura en Ciencias de Datos e Inteligencia Artificial · 2026

Este repositorio documenta mi progreso y las actividades prácticas de la materia **Procesamiento de Imágenes**, dictada en el **Centro Politécnico Superior Malvinas Argentinas**.

El objetivo es transformar los conocimientos teóricos en implementaciones con Python para comprender cómo las computadoras representan, procesan y analizan imágenes digitales.

---

## 📚 Temas abordados

### Semana 1 — Fundamentos y Filtrado Digital

Bases conceptuales de la visión por computadora y el procesamiento digital de imágenes.

- **Teoría e historia:** evolución del procesamiento digital de imágenes hasta la inteligencia artificial moderna.
- **Análisis crítico:** impacto ético y cultural de los filtros en herramientas como Photoshop y GIMP.
- **Práctica con código:** aplicación de desenfoque gaussiano con Python y `scikit-image`.

### Semana 2 · Clase 4 — Laboratorio de Espacios de Color

Trabajo con notebooks para explorar la estructura y representación de una imagen digital.

- **Manipulación matricial:** lectura, modificación y dibujo sobre píxeles con arrays de NumPy.
- **Espacios de color:** análisis y conversión entre RGB, HSV, CMYK y LAB.
- **Segmentación por color:** creación de máscaras y detección de objetos mediante HSV y OpenCV.
- **Formatos y compresión:** comparación de calidad, PSNR y tamaño de archivo entre JPEG y PNG.

### Semana 4 · Clase 8 — Operaciones de Filtrado y Frecuencia

Laboratorio de suavizado, detección de bordes y análisis en el dominio de la frecuencia.

- **Filtros espaciales:** comparación de promedio, gaussiano y mediana; análisis del efecto del tamaño del kernel.
- **Ruido:** incorporación de ruido gaussiano y sal y pimienta para comparar los filtros visualmente y mediante el error cuadrático medio (MSE).
- **Gradientes y bordes:** cálculo de diferencias finitas, componentes Sobel y magnitud del gradiente.
- **Detector Canny:** comparación de umbrales y del efecto del pre-suavizado sobre los bordes detectados.
- **Transformada de Fourier:** cálculo de FFT 2D y visualización de magnitud y fase.
- **Filtrado en frecuencia:** construcción de máscaras pasa-bajos, pasa-altos y pasa-banda, con reconstrucción mediante FFT inversa.
- **Radio de corte:** comparación de distintos radios del filtro pasa-bajos para observar la pérdida de detalles y el grado de suavizado.
- **Patrones periódicos:** exploración de las frecuencias dominantes de una imagen sintética.
- **Pipeline integrado:** combinación de reducción de ruido, suavizado, detección de bordes y análisis de frecuencia.
- **Actividad de foro:** preparación de imágenes de entrada y salida, tres líneas de procesamiento y justificación del uso de mediana ante ruido sal y pimienta simulado.

## 🔬 Prácticas de la Clase 8

| Actividad | Implementación |
|---|---|
| Ejercicio 1 | Comparación de promedio, gaussiano y mediana sobre la misma imagen con ruido gaussiano, incluyendo MSE. |
| Ejercicio 2 | Comparación de Canny sin pre-suavizado y con kernels gaussianos de 3×3 y 9×9, manteniendo los mismos umbrales. |
| Ejercicio 3 | Filtrado pasa-bajos con radios de 10, 30, 60 y 100, con visualización de máscaras y resultados. |
| Ejercicio final | Pipeline de ruido gaussiano, suavizado y Canny sobre la imagen base de Lena, con justificación de los parámetros. |
| Preparación del foro | Aplicación de mediana 5×5 a una imagen con ruido sal y pimienta simulado y exportación de imágenes para la publicación. |

Las comparaciones permiten observar cómo cada técnica modifica el ruido, los contornos y las texturas. Los resultados dependen de la imagen y de los parámetros utilizados.

## 🛠️ Tecnologías y Librerías

| Herramienta | Uso |
|---|---|
| **Python 3** | Implementación de las prácticas. |
| **Jupyter Notebook / JupyterLab** | Desarrollo interactivo y documentación de resultados. |
| **NumPy** | Manipulación matricial, generación de ruido y transformadas de Fourier. |
| **OpenCV (`cv2`)** | Conversión de color, filtrado, detección de bordes y exportación de imágenes. |
| **scikit-image** | Procesamiento de imágenes en las primeras prácticas. |
| **Matplotlib** | Visualización de imágenes, máscaras, espectros y comparaciones. |
| **Pillow** | Lectura y manipulación de imágenes. |

## ▶️ Cómo explorar las prácticas

1. Abrir el notebook correspondiente en Jupyter Notebook, JupyterLab o Google Colab.
2. Instalar las dependencias indicadas en sus celdas de configuración.
3. Ejecutar las celdas en orden para crear las imágenes y variables utilizadas por los ejercicios.
4. Revisar las visualizaciones, métricas y comentarios de análisis.

---

Repositorio académico de **Cristian Sombra** · Procesamiento de Imágenes · **2026**.
