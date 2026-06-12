# Repositorio de Extracción del Conocimiento de Bases de Datos

<div align="center">

<img src="https://img.shields.io/badge/Python-3.x-1f6feb?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Jupyter-Notebook-f97316?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
<img src="https://img.shields.io/badge/PostgreSQL-Data%20Warehouse-2563eb?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/GitHub-Repositorio-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">

<br><br>

<table>
  <tr>
    <td align="center">
      <strong>Repositorio académico para limpieza, análisis, visualización, interpretación y generación de conocimiento a partir de datos.</strong>
    </td>
  </tr>
</table>

</div>

---

## Información del alumno

<table>
  <tr style="background-color:#1f4e79; color:white;">
    <th align="left">Dato</th>
    <th align="left">Información</th>
  </tr>
  <tr><td><strong>Nombre del alumno</strong></td><td>Abiel Ontiveros Calvario</td></tr>
  <tr><td><strong>Materia</strong></td><td>Extracción del Conocimiento de Bases de Datos</td></tr>
  <tr><td><strong>Cuatrimestre</strong></td><td>Noveno cuatrimestre</td></tr>
  <tr><td><strong>Grupo</strong></td><td>9B</td></tr>
  <tr><td><strong>Institución</strong></td><td>Universidad Tecnológica del Centro de Veracruz</td></tr>
  <tr><td><strong>Periodo de evaluación</strong></td><td>Primer parcial</td></tr>
  <tr><td><strong>Repositorio</strong></td><td>ECBD-OntiverosCalvarioAbiel</td></tr>
</table>

---

## Descripción general

Este repositorio contiene las prácticas desarrolladas durante el primer parcial de la materia **Extracción del Conocimiento de Bases de Datos**. Su finalidad es integrar evidencias académicas relacionadas con la limpieza, análisis, visualización, interpretación y generación de conocimiento a partir de conjuntos de datos reales o utilizados en clase.

El repositorio está organizado para demostrar el avance del alumno mediante notebooks, datasets, documentación y evidencias visuales. Además, se emplean buenas prácticas de Git y GitHub para mantener un historial claro de cambios y una estructura ordenada.

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="left">Área de trabajo</th><th align="left">Descripción</th></tr>
  <tr><td><strong>Limpieza de datos</strong></td><td>Identificación de valores nulos, duplicados, errores de formato e inconsistencias.</td></tr>
  <tr><td><strong>Análisis descriptivo</strong></td><td>Obtención de medidas, conteos, agrupaciones y resúmenes de información.</td></tr>
  <tr><td><strong>Visualización</strong></td><td>Creación de gráficas para representar patrones, tendencias y comparaciones.</td></tr>
  <tr><td><strong>Interpretación</strong></td><td>Explicación de los resultados obtenidos, no solo presentación de código.</td></tr>
  <tr><td><strong>Modelo DIKW</strong></td><td>Transformación de datos en información, conocimiento y recomendaciones.</td></tr>
  <tr><td><strong>Data Warehouse</strong></td><td>Organización de datos mediante dimensiones y tabla de hechos para análisis.</td></tr>
</table>

---

## Objetivo general

Desarrollar un repositorio académico en GitHub que integre prácticas de limpieza de datos, análisis descriptivo, visualización, interpretación de resultados y generación de conocimiento mediante el modelo DIKW, utilizando datasets reales o académicos, con una estructura clara, documentación completa y evidencias organizadas.

---

## Objetivos específicos

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="center">No.</th><th align="left">Objetivo específico</th></tr>
  <tr><td align="center">1</td><td>Organizar correctamente los notebooks, datasets y evidencias del repositorio.</td></tr>
  <tr><td align="center">2</td><td>Aplicar técnicas de limpieza y preparación de datos.</td></tr>
  <tr><td align="center">3</td><td>Realizar análisis descriptivos sobre diferentes conjuntos de datos.</td></tr>
  <tr><td align="center">4</td><td>Crear visualizaciones claras, legibles y relacionadas con el análisis.</td></tr>
  <tr><td align="center">5</td><td>Interpretar los resultados obtenidos en cada práctica.</td></tr>
  <tr><td align="center">6</td><td>Aplicar el modelo DIKW para transformar datos en conocimiento útil.</td></tr>
  <tr><td align="center">7</td><td>Documentar cada práctica mediante títulos, explicaciones, comentarios y conclusiones.</td></tr>
  <tr><td align="center">8</td><td>Mantener actualizado el repositorio mediante commits descriptivos.</td></tr>
</table>

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
│   ├── Lab01/
│   ├── Lab02/
│   ├── Lab04-DIKW/
│   ├── ProductoDW/
│   └── General/
│
├── .gitignore
└── README.md
```

---

## Descripción de carpetas

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="left">Carpeta</th><th align="left">Contenido</th><th align="left">Uso</th></tr>
  <tr><td><strong>DataSet</strong></td><td>Archivos CSV y JSON utilizados en las prácticas.</td><td>Almacenar los datos separados de los notebooks.</td></tr>
  <tr><td><strong>Notebooks</strong></td><td>Laboratorios desarrollados en Jupyter Notebook.</td><td>Documentar código, análisis, gráficas e interpretación.</td></tr>
  <tr><td><strong>Evidencias</strong></td><td>Capturas o imágenes de resultados importantes.</td><td>Mostrar gráficas, consultas, resultados y procesos realizados.</td></tr>
</table>

---

## Datasets utilizados

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="left">Dataset</th><th align="left">Descripción</th><th align="left">Uso principal</th></tr>
  <tr><td><code>Data_Limpio_Factura.csv</code></td><td>Dataset limpio relacionado con información de facturación.</td><td>Análisis y comparación después de procesos de limpieza.</td></tr>
  <tr><td><code>dataset_sucio_practica.csv</code></td><td>Datos con errores, valores nulos o inconsistencias.</td><td>Prácticas de limpieza y preparación de datos.</td></tr>
  <tr><td><code>dfClientes_metadata.json</code></td><td>Archivo de metadatos relacionado con clientes.</td><td>Referencia y documentación de información de clientes.</td></tr>
  <tr><td><code>netflix_titles.csv</code></td><td>Dataset de títulos de Netflix.</td><td>Exploración, análisis descriptivo y visualización.</td></tr>
  <tr><td><code>test.csv</code></td><td>Dataset de prueba utilizado en ejercicios del curso.</td><td>Validación y práctica de carga de datos.</td></tr>
  <tr><td><code>ventas-por-factura.csv</code></td><td>Información de ventas organizada por factura.</td><td>Análisis de ventas y facturación.</td></tr>
  <tr><td><code>ventas_operacionales.csv</code></td><td>Datos operacionales relacionados con ventas.</td><td>Origen de datos para práctica de Data Warehouse.</td></tr>
  <tr><td><code>clientes.csv</code></td><td>Información de clientes.</td><td>Dimensión de clientes.</td></tr>
  <tr><td><code>productos.csv</code></td><td>Información de productos.</td><td>Dimensión de productos.</td></tr>
  <tr><td><code>regiones.csv</code></td><td>Información de regiones o ubicaciones.</td><td>Dimensión geográfica.</td></tr>
  <tr><td><code>tiempo.csv</code></td><td>Información temporal.</td><td>Dimensión de tiempo.</td></tr>
  <tr><td><code>ventas.csv</code></td><td>Información procesada de ventas.</td><td>Tabla de hechos o análisis de ventas.</td></tr>
</table>

---

## Prácticas y notebooks

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="left">Notebook</th><th align="left">Contenido esperado</th><th align="left">Estatus</th></tr>
  <tr><td><code>Lab01.ipynb</code></td><td>Introducción, carga y exploración inicial de datos.</td><td>Documentado</td></tr>
  <tr><td><code>Lab02.ipynb</code></td><td>Manipulación de datos y revisión de información.</td><td>Documentado</td></tr>
  <tr><td><code>Lab03.ipynb</code></td><td>Análisis descriptivo y preparación de datos.</td><td>Documentado</td></tr>
  <tr><td><code>Lab04-DIKW.ipynb</code></td><td>Aplicación del modelo Datos, Información, Conocimiento y Sabiduría.</td><td>Documentado</td></tr>
  <tr><td><code>Lab05.ipynb</code></td><td>Limpieza, transformación o visualización de datos.</td><td>Documentado</td></tr>
  <tr><td><code>Lab06.ipynb</code></td><td>Análisis con interpretación de resultados.</td><td>Documentado</td></tr>
  <tr><td><code>Lab07.ipynb</code></td><td>Procesamiento y análisis de datasets del curso.</td><td>Documentado</td></tr>
  <tr><td><code>Lab09.ipynb</code></td><td>Práctica de análisis y documentación de resultados.</td><td>Documentado</td></tr>
  <tr><td><code>Lab10.ipynb</code></td><td>Práctica desarrollada durante el primer parcial.</td><td>Documentado</td></tr>
  <tr><td><code>ProductoDW.ipynb</code></td><td>Construcción y análisis de un Data Warehouse de productos y ventas.</td><td>Documentado</td></tr>
</table>

---

## Herramientas utilizadas

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="left">Herramienta</th><th align="left">Función dentro del proyecto</th></tr>
  <tr><td><strong>Python</strong></td><td>Lenguaje principal para limpieza, análisis y procesamiento de datos.</td></tr>
  <tr><td><strong>Pandas</strong></td><td>Lectura, manipulación y transformación de DataFrames.</td></tr>
  <tr><td><strong>NumPy</strong></td><td>Operaciones numéricas y apoyo al tratamiento de datos.</td></tr>
  <tr><td><strong>Matplotlib</strong></td><td>Creación de gráficas y visualizaciones.</td></tr>
  <tr><td><strong>Jupyter Notebook</strong></td><td>Desarrollo, ejecución y documentación de prácticas.</td></tr>
  <tr><td><strong>Anaconda</strong></td><td>Administración del entorno de trabajo.</td></tr>
  <tr><td><strong>PostgreSQL</strong></td><td>Creación, consulta y análisis de estructuras de base de datos.</td></tr>
  <tr><td><strong>Visual Studio Code</strong></td><td>Edición de archivos y administración del repositorio.</td></tr>
  <tr><td><strong>Git</strong></td><td>Control de versiones local.</td></tr>
  <tr><td><strong>GitHub</strong></td><td>Almacenamiento del repositorio, documentación y revisión.</td></tr>
</table>

---

## Requisitos previos

Para ejecutar correctamente las prácticas se recomienda contar con:

```text
Python 3.10 o superior
Jupyter Notebook o JupyterLab
Pandas
NumPy
Matplotlib
PostgreSQL
Git
```

Instalación de librerías principales:

```bash
pip install pandas numpy matplotlib jupyter
```

---

## Instrucciones generales de ejecución

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="center">Paso</th><th align="left">Acción</th><th align="left">Comando o indicación</th></tr>
  <tr><td align="center">1</td><td>Clonar el repositorio</td><td><code>git clone https://github.com/Abiel252005/ECBD-OntiverosCalvarioAbiel.git</code></td></tr>
  <tr><td align="center">2</td><td>Entrar a la carpeta del repositorio</td><td><code>cd ECBD-OntiverosCalvarioAbiel</code></td></tr>
  <tr><td align="center">3</td><td>Instalar dependencias</td><td><code>pip install pandas numpy matplotlib jupyter</code></td></tr>
  <tr><td align="center">4</td><td>Iniciar Jupyter Notebook</td><td><code>jupyter notebook</code></td></tr>
  <tr><td align="center">5</td><td>Abrir la carpeta de prácticas</td><td><code>Notebooks/</code></td></tr>
  <tr><td align="center">6</td><td>Ejecutar el notebook</td><td><code>Kernel → Restart Kernel and Run All Cells</code></td></tr>
</table>

---

## Uso de rutas relativas

Los notebooks se encuentran dentro de la carpeta `Notebooks`, mientras que los datasets están dentro de `DataSet`.

Por esa razón, al cargar archivos desde un notebook se debe utilizar la ruta relativa:

```python
import pandas as pd

ventas = pd.read_csv("../DataSet/ventas.csv")
clientes = pd.read_csv("../DataSet/clientes.csv")
productos = pd.read_csv("../DataSet/productos.csv")
regiones = pd.read_csv("../DataSet/regiones.csv")
tiempo = pd.read_csv("../DataSet/tiempo.csv")
```

Ejemplo para otros datasets:

```python
netflix = pd.read_csv("../DataSet/netflix_titles.csv")
facturas = pd.read_csv("../DataSet/ventas-por-factura.csv")
```

---

## Modelo DIKW

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="left">Nivel</th><th align="left">Descripción</th><th align="left">Ejemplo aplicado</th></tr>
  <tr><td><strong>Datos</strong></td><td>Registros originales sin interpretación.</td><td>Cliente, producto, cantidad, precio, fecha y región.</td></tr>
  <tr><td><strong>Información</strong></td><td>Datos organizados, limpiados y resumidos.</td><td>Ventas totales por producto o región.</td></tr>
  <tr><td><strong>Conocimiento</strong></td><td>Interpretación de patrones y relaciones.</td><td>Identificar productos con mayor demanda o regiones con más ventas.</td></tr>
  <tr><td><strong>Sabiduría</strong></td><td>Recomendaciones basadas en el análisis.</td><td>Aumentar inventario, crear promociones o mejorar la planeación comercial.</td></tr>
</table>

---

## Práctica de Data Warehouse

El notebook `ProductoDW.ipynb` desarrolla una práctica relacionada con la construcción y análisis de un Data Warehouse basado en ventas, productos, clientes, regiones y tiempo.

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="left">Elemento</th><th align="left">Descripción</th></tr>
  <tr><td><strong>Datos operacionales</strong></td><td>Información original de ventas antes de ser organizada para análisis.</td></tr>
  <tr><td><strong>Dimensión cliente</strong></td><td>Datos descriptivos de los clientes.</td></tr>
  <tr><td><strong>Dimensión producto</strong></td><td>Datos de los productos analizados.</td></tr>
  <tr><td><strong>Dimensión región</strong></td><td>Información geográfica o de ubicación.</td></tr>
  <tr><td><strong>Dimensión tiempo</strong></td><td>Información de fechas, periodos o temporalidad.</td></tr>
  <tr><td><strong>Tabla de hechos</strong></td><td>Registros principales de ventas utilizados para el análisis.</td></tr>
</table>

---

## Evidencias de los análisis

Esta sección explica cómo agregar capturas o imágenes representativas de las prácticas. Las evidencias permiten comprobar visualmente los resultados obtenidos en los notebooks, como gráficas, tablas, procesos de limpieza, consultas, creación de estructuras y análisis realizados.

Las imágenes deben guardarse dentro de la carpeta `Evidencias` para que puedan visualizarse correctamente en GitHub.

### Cómo obtener las capturas

En Windows se pueden tomar capturas con las siguientes opciones:

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="left">Opción</th><th align="left">Uso recomendado</th></tr>
  <tr><td><strong>Windows + Shift + S</strong></td><td>Seleccionar una parte específica de la pantalla.</td></tr>
  <tr><td><strong>Impr Pant</strong></td><td>Capturar toda la pantalla.</td></tr>
  <tr><td><strong>Herramienta Recortes</strong></td><td>Capturar, editar y guardar imágenes.</td></tr>
  <tr><td><strong>Desde Jupyter</strong></td><td>Capturar directamente gráficas, tablas o salidas del notebook.</td></tr>
</table>

### Capturas recomendadas

<table>
  <tr style="background-color:#1f4e79; color:white;"><th align="left">Evidencia</th><th align="left">Archivo sugerido</th><th align="left">Descripción</th></tr>
  <tr><td>Limpieza de datos</td><td><code>Evidencias/limpieza_datos.png</code></td><td>Valores nulos, duplicados, corrección de datos o dataset limpio.</td></tr>
  <tr><td>Análisis de ventas</td><td><code>Evidencias/analisis_ventas.png</code></td><td>Gráficas o tablas de ventas por producto, región o periodo.</td></tr>
  <tr><td>Data Warehouse</td><td><code>Evidencias/producto_dw.png</code></td><td>Dimensiones, tabla de hechos, consultas o resultados del DW.</td></tr>
  <tr><td>Modelo DIKW</td><td><code>Evidencias/modelo_dikw.png</code></td><td>Evidencia de datos, información, conocimiento y sabiduría.</td></tr>
  <tr><td>Consulta PostgreSQL</td><td><code>Evidencias/consulta_postgresql.png</code></td><td>Consulta ejecutada correctamente en PostgreSQL.</td></tr>
</table>

### Crear la carpeta de evidencias

Si la carpeta `Evidencias` todavía no existe, puede crearse desde PowerShell:

```bash
mkdir Evidencias
```

También puede crearse manualmente desde Visual Studio Code o desde el explorador de archivos.

### Organización opcional por práctica

Si el repositorio se sigue utilizando durante más prácticas, se pueden crear carpetas internas para separar las evidencias por laboratorio:

```text
Evidencias/
│
├── Lab01/
├── Lab02/
├── Lab03/
├── Lab04-DIKW/
├── ProductoDW/
└── General/
```

Comandos para crear carpetas internas:

```bash
mkdir Evidencias\Lab01
mkdir Evidencias\Lab02
mkdir Evidencias\Lab03
mkdir Evidencias\Lab04-DIKW
mkdir Evidencias\ProductoDW
mkdir Evidencias\General
```

### Ejemplo para insertar imágenes en el README

Cuando la imagen ya exista dentro del repositorio, puede insertarse de esta forma:

```markdown
![Análisis de ventas](Evidencias/analisis_ventas.png)
```

Ejemplo dentro de una carpeta específica:

```markdown
![Consulta PostgreSQL](Evidencias/ProductoDW/consulta_postgresql.png)
```

Importante: las rutas locales de la computadora no funcionan en GitHub. No se debe usar una ruta como esta:

```text
C:\Users\abiel\Pictures\analisis_ventas.png
```

La imagen debe estar dentro del repositorio y referenciarse mediante una ruta relativa.

---

## Resultados generales

Durante el desarrollo de las prácticas se realizaron actividades relacionadas con la exploración, limpieza, procesamiento, análisis, visualización e interpretación de datos.

<table>
  <tr style="background-color:#2f5597; color:white;"><th align="left">Actividad</th><th align="left">Resultado obtenido</th></tr>
  <tr><td>Exploración inicial</td><td>Se identificaron columnas, tipos de datos, dimensiones y estructura de los datasets.</td></tr>
  <tr><td>Limpieza de datos</td><td>Se detectaron valores nulos, duplicados e inconsistencias.</td></tr>
  <tr><td>Transformación</td><td>Se ajustaron tipos de datos y se preparó la información para análisis.</td></tr>
  <tr><td>Análisis descriptivo</td><td>Se obtuvieron conteos, agrupaciones, estadísticas y resúmenes.</td></tr>
  <tr><td>Visualización</td><td>Se generaron gráficas para representar patrones y tendencias.</td></tr>
  <tr><td>Interpretación</td><td>Se explicaron los resultados obtenidos para generar conocimiento.</td></tr>
  <tr><td>Data Warehouse</td><td>Se trabajó con dimensiones y hechos para organizar información de ventas.</td></tr>
</table>

---

## Interpretación de resultados

La interpretación es una parte esencial del repositorio, ya que no se evalúa únicamente el código, sino también la capacidad para explicar los resultados obtenidos.

Cada notebook debe responder preguntas como:

```text
¿Qué muestra la gráfica?
¿Qué variable tiene mayor frecuencia?
¿Qué tendencia se observa?
¿Qué valores parecen atípicos?
¿Qué relación existe entre las variables?
¿Qué conocimiento se obtiene?
¿Qué decisión podría tomarse con base en el análisis?
```

---

## Consideraciones importantes

<table>
  <tr style="background-color:#7f1d1d; color:white;"><th align="center">No.</th><th align="left">Consideración</th></tr>
  <tr><td align="center">1</td><td>No se deben subir notebooks vacíos o incompletos.</td></tr>
  <tr><td align="center">2</td><td>Se debe evaluar e incluir interpretación, no únicamente código.</td></tr>
  <tr><td align="center">3</td><td>Los Issues realizados durante la revisión deben atenderse correctamente.</td></tr>
  <tr><td align="center">4</td><td>El repositorio debe mostrar evidencia de organización y documentación.</td></tr>
  <tr><td align="center">5</td><td>No se deben subir carpetas temporales como <code>.ipynb_checkpoints</code>.</td></tr>
  <tr><td align="center">6</td><td>Los datasets deben estar en <code>DataSet</code> y los notebooks en <code>Notebooks</code>.</td></tr>
</table>

---

## Flujo de actualización del repositorio

Antes de comenzar una nueva práctica:

```bash
git pull origin main
```

Después de guardar cambios:

```bash
git status
git add .
git commit -m "Agrega descripcion clara de la practica realizada"
git push origin main
```

Ejemplos de commits recomendados:

```text
Agrega analisis descriptivo del dataset de Netflix
Corrige rutas de datasets en Lab06
Añade interpretacion y conclusiones al modelo DIKW
Agrega practica ProductoDW y dimensiones de ventas
Actualiza evidencias y documentacion del repositorio
```

---

## Conclusiones generales

El desarrollo de las prácticas permitió comprender las principales etapas del proceso de extracción de conocimiento a partir de bases de datos. Mediante Python, Pandas y Jupyter Notebook fue posible cargar, explorar, limpiar, transformar y analizar diferentes conjuntos de datos.

El uso de visualizaciones permitió identificar patrones, tendencias y relaciones que no siempre son evidentes al observar únicamente los datos originales. Además, la interpretación de resultados permitió transformar los análisis en conocimiento útil.

La aplicación del modelo DIKW ayudó a comprender cómo los datos pueden convertirse en información organizada, después en conocimiento interpretado y finalmente en recomendaciones para apoyar la toma de decisiones.

La práctica de Data Warehouse permitió reconocer la importancia de separar la información en dimensiones y tablas de hechos, facilitando el análisis histórico de ventas, productos, clientes, regiones y periodos.

Finalmente, el uso de Git y GitHub permitió mantener una estructura organizada, documentar avances y conservar evidencia del trabajo mediante commits. Este repositorio representa el avance académico del primer parcial y demuestra la importancia de combinar código, análisis, documentación e interpretación.

---

## Estado del proyecto

<table>
  <tr style="background-color:#166534; color:white;"><th align="left">Elemento</th><th align="left">Estado</th></tr>
  <tr><td>Estructura del repositorio</td><td>Organizada</td></tr>
  <tr><td>Notebooks</td><td>Integrados en la carpeta correspondiente</td></tr>
  <tr><td>Datasets</td><td>Organizados en DataSet</td></tr>
  <tr><td>README</td><td>Documentado</td></tr>
  <tr><td>Evidencias</td><td>Carpeta disponible para capturas</td></tr>
</table>

---

<div align="center">

<strong>Universidad Tecnológica del Centro de Veracruz</strong>

<strong>Extracción del Conocimiento de Bases de Datos</strong>

<strong>Noveno cuatrimestre, grupo 9B</strong>

<strong>Abiel Ontiveros Calvario</strong>

</div>
