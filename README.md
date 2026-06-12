# Repositorio de Extracción del Conocimiento de Bases de Datos

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Data%20Warehouse-336791?logo=postgresql&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositorio-181717?logo=github&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)

**Repositorio académico para la documentación, análisis, limpieza, visualización e interpretación de datos.**

</div>

---

## Información del alumno

| Dato | Información |
|---|---|
| **Nombre del alumno** | Abiel Ontiveros Calvario |
| **Materia** | Extracción del Conocimiento de Bases de Datos |
| **Cuatrimestre** | Noveno cuatrimestre |
| **Grupo** | 9B |
| **Institución** | Universidad Tecnológica del Centro de Veracruz |
| **Periodo de evaluación** | Primer parcial |
| **Repositorio** | `ECBD-OntiverosCalvarioAbiel` |

---

## Descripción general

Este repositorio contiene las prácticas, ejercicios y proyectos desarrollados durante el primer parcial de la materia **Extracción del Conocimiento de Bases de Datos**.

El trabajo integra distintas etapas del análisis de datos, entre ellas:

- Obtención y carga de datasets.
- Exploración inicial de la información.
- Limpieza y transformación de datos.
- Identificación de valores nulos, duplicados e inconsistencias.
- Análisis descriptivo.
- Elaboración de visualizaciones.
- Interpretación de resultados.
- Generación de conclusiones.
- Aplicación del modelo **DIKW**.
- Construcción y análisis de un **Data Warehouse**.
- Uso de PostgreSQL, Python, Pandas y Jupyter Notebook.
- Control de versiones y documentación mediante Git y GitHub.

El propósito principal del repositorio es demostrar que el análisis de datos no consiste únicamente en ejecutar código, sino también en organizar la información, interpretar los resultados y generar conocimiento útil para apoyar la toma de decisiones.

---

## Objetivo general

Desarrollar un repositorio académico organizado, documentado y actualizado que integre prácticas de limpieza, análisis descriptivo, visualización, interpretación y generación de conocimiento a partir de datasets reales, utilizando herramientas de análisis de datos y buenas prácticas de control de versiones.

---

## Objetivos específicos

- Organizar correctamente los notebooks, datasets y evidencias.
- Aplicar técnicas de limpieza y preparación de datos.
- Realizar análisis descriptivos sobre diferentes conjuntos de datos.
- Crear visualizaciones claras, legibles y correctamente identificadas.
- Interpretar los patrones y resultados obtenidos.
- Aplicar el modelo DIKW para transformar datos en conocimiento.
- Implementar conceptos básicos de Data Warehouse.
- Documentar cada práctica mediante títulos, comentarios y conclusiones.
- Mantener un historial de cambios mediante commits descriptivos.
- Atender correctamente los Issues y observaciones realizadas durante la revisión.

---

## Estructura del repositorio

```text
ECBD-OntiverosCalvarioAbiel/
│
├── DataSet/
│   ├── Data_Limpio_Factura.csv
│   ├── dataset_sucio_practica.csv
│   ├── dfClientes_metadata.json
│   ├── netflix_titles.csv
│   ├── test.csv
│   ├── ventas-por-factura.csv
│   ├── ventas_operacionales.csv
│   ├── clientes.csv
│   ├── productos.csv
│   ├── regiones.csv
│   ├── tiempo.csv
│   └── ventas.csv
│
├── Notebooks/
│   ├── Lab01.ipynb
│   ├── Lab02.ipynb
│   ├── Lab03.ipynb
│   ├── Lab04-DIKW.ipynb
│   ├── Lab05.ipynb
│   ├── Lab06.ipynb
│   ├── Lab07.ipynb
│   ├── Lab09.ipynb
│   ├── Lab10.ipynb
│   └── ProductoDW.ipynb
│
├── Evidencias/
│   ├── analisis_ventas.png
│   ├── limpieza_datos.png
│   └── producto_dw.png
│
├── .gitignore
└── README.md
```

> La carpeta `Evidencias` puede crearse para almacenar capturas de gráficas, resultados, consultas y procesos desarrollados durante las prácticas.

---

## Descripción de las carpetas

### `Notebooks`

Contiene los archivos desarrollados en Jupyter Notebook. Cada práctica debe incluir, según corresponda:

- Título de la práctica.
- Introducción.
- Objetivo.
- Explicación del procedimiento.
- Código comentado.
- Resultados obtenidos.
- Gráficas legibles.
- Interpretación de los resultados.
- Conclusiones.

### `DataSet`

Contiene los archivos de datos utilizados durante las prácticas. Los datasets se mantienen separados de los notebooks para conservar una estructura ordenada y facilitar su localización.

### `Evidencias`

Contiene capturas de pantalla o imágenes de los análisis realizados, como:

- Gráficas.
- Resultados de limpieza.
- Consultas en PostgreSQL.
- Creación de tablas.
- Carga de datos.
- Resultados del Data Warehouse.
- Evidencias de ejecución de los notebooks.

---

## Datasets utilizados

Durante el primer parcial se utilizaron diferentes conjuntos de datos con fines académicos.

| Dataset | Descripción general |
|---|---|
| `Data_Limpio_Factura.csv` | Dataset procesado y limpio relacionado con información de facturación. |
| `dataset_sucio_practica.csv` | Conjunto de datos con errores, valores nulos o inconsistencias utilizado para prácticas de limpieza. |
| `dfClientes_metadata.json` | Archivo con metadatos relacionados con clientes. |
| `netflix_titles.csv` | Dataset de títulos disponibles en Netflix utilizado para exploración, análisis y visualización. |
| `test.csv` | Dataset de prueba utilizado en ejercicios de análisis. |
| `ventas-por-factura.csv` | Información de ventas organizada por factura. |
| `ventas_operacionales.csv` | Datos operacionales utilizados para la práctica de Data Warehouse. |
| `clientes.csv` | Dimensión o catálogo de clientes. |
| `productos.csv` | Dimensión o catálogo de productos. |
| `regiones.csv` | Información relacionada con regiones o ubicaciones. |
| `tiempo.csv` | Dimensión temporal utilizada en el análisis de ventas. |
| `ventas.csv` | Tabla o conjunto de hechos relacionado con las ventas. |

---

## Prácticas y notebooks

| Notebook | Descripción |
|---|---|
| `Lab01.ipynb` | Introducción al análisis de datos y exploración inicial. |
| `Lab02.ipynb` | Manipulación y revisión de información mediante Python y Pandas. |
| `Lab03.ipynb` | Análisis descriptivo y preparación de datos. |
| `Lab04-DIKW.ipynb` | Aplicación del modelo Datos, Información, Conocimiento y Sabiduría. |
| `Lab05.ipynb` | Limpieza, transformación o visualización de datos. |
| `Lab06.ipynb` | Desarrollo de análisis con interpretación de resultados. |
| `Lab07.ipynb` | Procesamiento y análisis de datasets del curso. |
| `Lab09.ipynb` | Práctica de análisis y documentación de resultados. |
| `Lab10.ipynb` | Práctica desarrollada durante el primer parcial. |
| `ProductoDW.ipynb` | Construcción y análisis de un Data Warehouse de productos y ventas. |

> La descripción de cada notebook puede ajustarse de acuerdo con el contenido final de cada práctica.

---

## Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| **Python** | Procesamiento, limpieza y análisis de datos. |
| **Pandas** | Manipulación de DataFrames y archivos CSV. |
| **NumPy** | Operaciones numéricas y tratamiento de datos. |
| **Matplotlib** | Creación de gráficas y visualizaciones. |
| **Jupyter Notebook** | Desarrollo y documentación de las prácticas. |
| **Anaconda** | Administración del entorno de trabajo y ejecución de notebooks. |
| **PostgreSQL** | Creación y consulta de bases de datos y Data Warehouse. |
| **Visual Studio Code** | Edición y organización de archivos. |
| **Git** | Control de versiones local. |
| **GitHub** | Almacenamiento, documentación y seguimiento del repositorio. |
| **PowerShell** | Ejecución de comandos de Git y administración de archivos. |

---

## Requisitos previos

Para ejecutar correctamente los notebooks se recomienda tener instalado:

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.
- Pandas.
- NumPy.
- Matplotlib.
- PostgreSQL, cuando la práctica lo requiera.
- Git.

Instalación de las principales librerías:

```bash
pip install pandas numpy matplotlib jupyter
```

También se puede utilizar Anaconda para administrar las dependencias y ejecutar los notebooks.

---

## Instrucciones generales de ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/Abiel252005/ECBD-OntiverosCalvarioAbiel.git
```

### 2. Entrar a la carpeta del repositorio

```bash
cd ECBD-OntiverosCalvarioAbiel
```

### 3. Instalar las dependencias

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Iniciar Jupyter Notebook

```bash
jupyter notebook
```

### 5. Abrir la carpeta `Notebooks`

Dentro del navegador de Jupyter, ingresar a:

```text
Notebooks/
```

### 6. Abrir la práctica deseada

Por ejemplo:

```text
ProductoDW.ipynb
```

### 7. Ejecutar todas las celdas

En Jupyter Notebook seleccionar:

```text
Kernel → Restart Kernel and Run All Cells
```

Esto permite comprobar que el notebook se ejecuta correctamente desde el inicio y que no depende de resultados almacenados previamente.

---

## Evidencias de los análisis

Esta sección debe contener capturas o imágenes representativas de las prácticas.

### Limpieza de datos

![Limpieza de datos](Evidencias/limpieza_datos.png)

### Análisis de ventas

![Análisis de ventas](Evidencias/analisis_ventas.png)

### Data Warehouse de productos

![Data Warehouse](Evidencias/producto_dw.png)

> Para que las imágenes se visualicen correctamente en GitHub, deben almacenarse dentro de la carpeta `Evidencias` y utilizar rutas relativas.

---

## Resultados generales

Durante el desarrollo de las prácticas se realizaron actividades como:

- Exploración inicial de datasets.
- Identificación de tipos de datos.
- Detección de valores nulos.
- Localización de registros duplicados.
- Corrección de inconsistencias.
- Conversión de tipos de datos.
- Creación de nuevas columnas.
- Agrupación y resumen de información.
- Cálculo de estadísticas descriptivas.
- Generación de gráficas.
- Interpretación de tendencias.
- Aplicación del modelo DIKW.
- Construcción de dimensiones y tablas de hechos.
- Análisis de ventas mediante un Data Warehouse.

Los resultados permitieron observar que una buena organización y limpieza de los datos es indispensable para obtener análisis confiables.

---


## Conclusiones generales

El desarrollo de las prácticas permitió comprender las principales etapas del proceso de extracción de conocimiento a partir de bases de datos.

Mediante Python, Pandas y Jupyter Notebook fue posible cargar, explorar, limpiar, transformar y analizar diferentes conjuntos de datos. Asimismo, el uso de gráficas facilitó la identificación de patrones, tendencias y relaciones que no siempre son evidentes al observar únicamente los registros originales.

La aplicación del modelo DIKW permitió entender cómo los datos sin procesar pueden transformarse primero en información organizada, después en conocimiento interpretado y finalmente en recomendaciones útiles para la toma de decisiones.

La práctica de Data Warehouse permitió reconocer la importancia de separar la información en dimensiones y tablas de hechos para facilitar el análisis histórico de ventas, productos, clientes, regiones y periodos.

Por otra parte, el uso de Git y GitHub contribuyó a mantener una estructura organizada, documentar los avances y conservar un historial de cambios mediante commits. Esto facilita la revisión de las prácticas, la atención de Issues y la actualización periódica del repositorio.

En conclusión, este repositorio integra tanto el desarrollo técnico como la interpretación de resultados, demostrando que la extracción de conocimiento requiere código, organización, análisis, documentación y capacidad para comunicar los hallazgos obtenidos.

---




## 📌 Estado del proyecto

El repositorio se encuentra en proceso de actualización durante el primer parcial. Cada práctica se agrega y documenta conforme se desarrolla en clase.

---

<div align="center">

### Universidad Tecnológica del Centro de Veracruz

**Extracción del Conocimiento de Bases de Datos — 9B**

**Abiel Ontiveros Calvario**

</div>
