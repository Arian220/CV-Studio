# **Computer Vision Annotation Tool (CV Studio)**  

Proyecto para procesar imágenes, crear anotaciones (bounding boxes, segmentación) y generar datasets listos para entrenar modelos de visión por computadora.  

---

## **📌 Características**  

✅ **Carga de imágenes**

- Soporta formatos comunes (JPG, PNG, BMP).  
- Previsualización en la interfaz.  

✅ **Redimensionamiento (Resizing)**

- Ajuste proporcional o forzado a dimensiones personalizadas.  

✅ **Etiquetado (Labeling)**

- Dibuja bounding boxes con clases personalizables.  
- Edición/eliminación de anotaciones existentes.  

✅ **Segmentación (Masking)**

- Herramienta de polígonos para máscaras.  
- Exporta máscaras en formato binario o PNG.  

✅ **Generación de Datasets**

- Guarda imágenes y anotaciones en carpetas locales.  
- Formatos soportados:  
  - **YOLO** (`.txt`): `[class_id, x_center, y_center, width, height]`.  
  - **COCO** (`.json`): Estructura compatible con otros frameworks.  

✅ **Interfaz de Usuario (UI)**  

- Navegación entre imágenes.  
- Lista de clases editables.  
