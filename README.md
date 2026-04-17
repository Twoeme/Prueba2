# Introducción a la Ciencia de Datos

Este repositorio es material de apoyo para una clase de introducción a la ciencia de datos. Contiene notebooks, ejemplos en Python y conjuntos de datos que permiten practicar conceptos básicos de programación, manipulación y análisis de datos.

## Estructura del repositorio

- `clase_python_notebook.ipynb` - Notebook con ejemplos y explicaciones de Python.
- `Prueba.py` - Script Python simple que muestra operadores y estructuras de control.
- `Pruebas_retos.ipynb` - Notebook con ejercicios prácticos y retos de programación.
- `Numpy_Class/` - Carpeta con un notebook de NumPy (`clase_numpy_notebook.ipynb`) y recursos de apoyo.
- `Pandas_Class/` - Carpeta con un notebook de pandas (`clase_pandas_notebook.ipynb`) y archivos de datos (`CSV` y `XLSX`).
- `prueba_3/` - Entorno virtual local con un notebook adicional (`prueba.ipynb`).
- `trabajadero/` - Otro entorno virtual local con notebooks y datos de ejemplo.
- `Trabajo_final/` - Carpeta con `Index.py`, un archivo de ejemplo que muestra la carga de datos desde GitHub (comentado).
- `Preguntas analiticas.txt` - Lista de preguntas analíticas útiles para la clase.
- `REPOSITORIO_RESUMEN.md` - Resumen del contenido del repositorio.
- `.gitignore` - Archivo de exclusión de archivos y carpetas que no deben subirse a Git.

## Archivos de datos principales

- `Pandas_Class/layoffs.csv`
- `Pandas_Class/companias_NY.xlsx`
- `Pandas_Class/companias_SF.xlsx`
- `Pandas_Class/companias_NY_SF_concatenadas.xlsx`

## Requisitos

- Python 3.x
- pandas
- numpy
- matplotlib
- jupyter

## Uso recomendado

1. Abre los notebooks con Jupyter Notebook o JupyterLab.
2. Activa un entorno virtual.
3. Instala los paquetes necesarios si aún no están instalados.
4. Ejecuta las celdas paso a paso y revisa los datos de `Pandas_Class/`.

## Activación de entornos locales

Para usar el entorno virtual `prueba_3`:

```powershell
cd c:\Users\twoem\OneDrive\Documentos\GitHub\Prueba\Prueba2\prueba_3
.\Scripts\Activate.ps1
```

Para usar el entorno virtual `trabajadero`:

```powershell
cd c:\Users\twoem\OneDrive\Documentos\GitHub\Prueba\Prueba2\trabajadero
.\Scripts\Activate.ps1
```

Instala dependencias si es necesario:

```powershell
python -m pip install pandas numpy matplotlib jupyter
```

## Buenas prácticas para el curso

- Usa los notebooks para experimentar e iterar sobre el código.
- No subas los entornos virtuales al repositorio si no forman parte del material compartido.
- Usa `.gitignore` para ignorar carpetas como `prueba_3/` y `trabajadero/`.
- Añade comentarios y explicaciones en los notebooks para facilitar el aprendizaje.

## Propósito

El objetivo es proporcionar recursos y ejercicios introductorios para enseñar a los estudiantes a cargar, explorar y manipular datos con Python, NumPy y pandas.
