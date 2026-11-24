# Entorno adecuado para el estudio de la ciencia de datos con Python o R


## Requisitos previos
1. Descargar e instalar Python https://www.python.org/downloads/

## Desarrollo y laboratorio
1. VS Code - Installed
2. JupyteLab - Installed
3. RStudio - Installed
4. Anaconda - Installed

### Opcional
1. Git - Installed

## Librerias de uso habitual

### Operaciones
- NumPy: operaciones numéricas y manejo de arreglos multidimensionales.
- Pandas: manipulación y análisis de datos estructurados.
- Polars: manipulación y análisis de datos de alto rendimiento(más de 10gb).
### Visualización
- Matplotlib: visualización de datos con gráficos estáticos.
- Seaborn: visualización de datos con interfaz de alta calidad (se base en Matplotlib).
- Plotly: visualización de datos con gráficos interactivas.

### Validaciones
- Pydantic: validación de datos y gestión de configuraciones.

### ML
- Scikit-learn: *Clasificación*, *regresión* y *clustering*.
- LightGBM: *Clasificación supervisada*, *regresión*. Utiliza algoritmos basados en árboles para el refuerzo de gradientes.
    - Mayor velocidad de entrenamiento y mayor eficiencia.
    - Menor uso de memoria.
    - Mayor precisión.
    - Compatibilidad con aprendizaje paralelo, distribuido y GPU.
    - Capaz de manejar datos a gran escala.
- 

### Presentación web
- Streamlit: conversión de script py en webapp interactivas.

## Utils Commands

pip install jupyterlab
install -c conda-forge jupyterlab

### Py
https://docs.python.org/3/using/windows.html

    py <regular Python options>
                         Launch the default runtime with specified options. This
                         is the equivalent of the python command.
    py -V:<TAG>          Launch runtime identified by <TAG>, which should
                         include the company name if not PythonCore. Regular
                         Python options may follow this option.
    py -3<VERSION>       Equivalent to -V:PythonCore\3<VERSION>. The version
                         must begin with the digit 3, platform overrides are
                         permitted, and regular Python options may follow. py -3
                         is the equivalent of the python3 command.
    py exec <any of the above>
                         Equivalent to any of the above launch options, and the
                         requested runtime will be installed if needed.
    py help [<CMD>]      Show help for Python installation manager commands
    py install <TAG>     Download new Python runtimes, or pass --update to
                         update existing installs.
    py list [<FILTER>]   Show installed Python runtimes, optionally filtering by
                         <FILTER>.
    py uninstall <TAG>   Remove one or more runtimes from your machine. Pass
                         --cleanup to remove cached and unrecognized files while
                         preserving recognized runtimes, or --purge to remove
                         all.

# Referencias

Python, U. (2026, 17 mayo). Python para Data Science: Guía Completa. Universo Python. https://universopython.com/es/blog/python-para-data-science
Ali, M. (2025, December 23). Las 31 mejores bibliotecas de Python para la ciencia de datos en 2026. DataCamp. https://www.datacamp.com/es/blog/top-python-libraries-for-data-science
