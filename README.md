# Proyecto de Análisis de Datos con Pandas

Este repositorio contiene un proyecto de análisis de datos realizado con Python, Pandas y Jupyter Notebook. El objetivo es demostrar diversas técnicas de manipulación y análisis de un conjunto de datos, desde la creación de estructuras de datos hasta la exportación de resultados.

## 📜 Descripción del Proyecto

El proyecto consiste en un notebook de Jupyter (`analisis.ipynb`) que sigue una serie de pasos para procesar y analizar un DataFrame. Las operaciones realizadas son un ejemplo práctico de las capacidades de la librería Pandas para la limpieza, transformación, filtrado y resumen de datos.

## ✨ Características del Análisis

El notebook cubre las siguientes operaciones de manipulación de datos:

- **Series**: Creación a partir de listas y diccionarios, acceso a elementos, modificación y operaciones matemáticas.
- **DataFrame**: Creación a partir de un diccionario, exploración de columnas y acceso a filas mediante `loc` e `iloc`.
- **Operaciones Básicas**: Creación de columnas derivadas y aplicación de operaciones vectorizadas.
- **Manejo de Datos Faltantes**: Detección de valores nulos (`NaN`) y su imputación con valores específicos.
- **Selección y Filtrado**: Aplicación de condiciones lógicas para filtrar filas del DataFrame.
- **Ordenamiento de Datos**: Clasificación del DataFrame en base a los valores de sus columnas.
- **Estadísticas Descriptivas**: Cálculo de métricas resumen como media, conteo, etc., con `describe()` y `value_counts()`.
- **Lectura y Escritura**: Interacción con el sistema de archivos para leer y guardar datos en formato CSV.
- **Ejercicio Integrado**: Un flujo de trabajo completo que combina varios de los pasos anteriores para generar un informe final.

## 🔧 Requisitos

Para ejecutar este proyecto, necesitarás tener instalado lo siguiente:

- Python 3.8 o superior
- Un gestor de paquetes como `pip`
- Las librerías de Python especificadas en el archivo `requirements.txt`. Las principales son:
  - `pandas`
  - `numpy`
  - `jupyterlab` o `notebook`

## ⚙️ Instalación

Sigue estos pasos para configurar el entorno de desarrollo local:

1.  **Clonar el repositorio (opcional):**
    Si has descargado el código como un ZIP, puedes omitir este paso.

    ```bash
    git clone <URL_DEL_REPOSITORIO>
    cd <NOMBRE_DEL_DIRECTORIO>
    ```

2.  **Crear un entorno virtual:**
    Se recomienda encarecidamente utilizar un entorno virtual para aislar las dependencias del proyecto.

    ```bash
    python -m venv .venv
    ```

3.  **Activar el entorno virtual:**

    - En Windows:
      ```bash
      .venv\Scripts\activate
      ```
    - En macOS/Linux:
      ```bash
      source .venv/bin/activate
      ```

4.  **Instalar las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Uso

Una vez que el entorno esté configurado y las dependencias instaladas:

1.  **Iniciar Jupyter:**
    Ejecuta el siguiente comando en tu terminal:

    ```bash
    jupyter lab
    ```

    o si prefieres la interfaz clásica de Notebook:

    ```bash
    jupyter notebook
    ```

2.  **Abrir el notebook:**
    En la interfaz de Jupyter que se abrirá en tu navegador, busca y abre el archivo `analisis.ipynb`.

3.  **Ejecutar el análisis:**
    Puedes ejecutar todas las celdas del notebook secuencialmente para ver el proceso completo de análisis de datos.

## 📁 Contenido del Repositorio

- `.gitignore`: Archivo para ignorar archivos y directorios en Git.
- `analisis.ipynb`: El notebook de Jupyter con todo el código y las explicaciones del análisis.
- `actividad_semana4.csv`: El conjunto de datos original utilizado en el notebook.
- `requirements.txt`: Lista de todas las dependencias de Python necesarias para el proyecto.
- `README.md`: Este archivo, con la documentación del proyecto.
- `inventario_procesado.csv`: Archivo CSV generado como resultado del ejercicio integrado (punto 9).
- `inventario_simple.csv`: Archivo CSV generado como resultado del ejercicio de escritura (punto 8).
