# Detección de Rostros en Imágenes usando OpenCV

Este repositorio contiene los recursos necesarios para el proyecto que utiliza un modelo preentrenado de OpenCV para detectar rostros en imágenes. Utiliza un clasificador Haar Cascade (`haarcascade_frontalface_default.xml`) para identificar y resaltar los rostros presentes en una imagen.

## Requisitos

- Python 3
- Librerías necesarias:
  - `opencv-python`
  - `numpy`
  - `matplotlib`

## Instrucciones para ejecutar el código

### 1. Cargar el repositorio en Google Colab

1. **Clonar el repositorio (opcional)**:
   Puedes clonarlo directamente en Colab usando el comando:

   ```python
   !git clone https://github.com/Matt1300/WhitePaper.git
   ```

2. **Instalar Dependencias (en caso de ser necesario)**

   ```python
   !pip install opencv-python matplotlib numpy
   ```

3. **Verificar que la estructura de archivos se encuentre de la siguiente manera:**
   ```python
   WhitePaper/
   │
   ├── img/
   │   └── imagen.png
   │   └── rostros.png
   └── WhitePaper.ipynb
   └── README.md
   ```
