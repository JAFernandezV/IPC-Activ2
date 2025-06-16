# IPC-Activ2
"Proyecto de análisis de expresión génica usando R"
## Descripción
Este proyecto tiene como objetivo analizar la expresión génica de un conjunto de muestras incluidas en un archivo csv, utilizando datos de expresión génica. A través de herramientas bioinformáticas, se realizará el procesamiento, limpieza y análisis de datos para obtener información sobre los genes diferencialmente expresados.

## Objetivos
•	Procesar datos de expresión génica para identificar genes diferencialmente expresados en cáncer de mama, cáncer renal y cáncer de pulmón.
•	Implementar herramientas bioinformáticas, mediante librerías específicas de R, para el análisis y visualización de resultados.
•	Comparar los efectos de dos tratamientos distintos sobre la expresión génica considerando tipos de tumor 

## Estructura del proyecto
├── Expresión genica/  #Carpeta madre para estructurar las subcarpetas y mejorar el orden
│   ├── data/ 
│       └── Dataset_expresión_genes.csv    # Datos originales para el análisis tipo CSV
│   ├── docs/ 								#esta carpeta contiene varios papers que usamos como guía para determinar qué vale la pena analizar
│   ├── Graficas/ 							# Aquí se muestran los resultados obtenidos al ejecutar el script
│       ├── Boxplot.png   		# Comparación segun tratamiento en la expresión de distintos genes
│       ├── heatmap.png   		# Comparación clusterizada en los niveles de expresión según pacientes 
│       ├── Histogramas1.png   # Análisis de normalidad en la distribución de datos del primer set de variables bioquímicas analizadas 
│       └── Histogramas1.png   # Análisis de normalidad en la distribución de datos del segundo set de variables bioquímicas analizadas 
├── scripts/
│       ├── borrador.R    # Contiene los códigos originales, algunos análisis complementarios y modificaciones
│       └── definitivo    # Script con el análisis usado para generar los plots en la carpeta de Graficas
├── README.md          # Documentación principal
└── LICENSE            # Archivo de licencia  

## Tablas de resultados

Las siguientes tablas fueron generadas a partir del análisis estadístico realizado con R y contienen los datos procesados:

- `normality_results.csv`: Resultado de las pruebas de normalidad para distintos conjuntos de variables bioquímicas.
- `tabla_modelo2.csv`: Tabla de resultados del segundo modelo lineal ajustado.
- `tabla_modelo3_edad.csv`: Modelo lineal con interacción entre tratamiento, edad y tipo de tumor.

Ubicación: `/Expresión genica/results/tables/`

