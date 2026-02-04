# sprint7-final-project

## Objetivo del Proyecto
1. Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
2. Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
3. Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
4. Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
5. Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
6. Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.

## Datasets utilizados
plans.csv: Catálogo de planes con sus precios y beneficios.
users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn).
usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud.

## Etapas de análisis realizadas
  Cargar y explorar:
1. Carga de datos y vista rápida
2. Exploración de la estructura de los Dataset
   
  Identificación de problemas de calidad de datos:
1. Revisión de valores nulos
2. Detección de valores inválidos y sentinels
3. Revisión y estandarización de fechas
   
   Limpieza básica de datos
1. Corregir sentinels y fechas imposibles
   
   Summary statistics de uso por usuario
1. Agrupación por comportamiento de uso
2. Resumen estadístico por usuario durante el 2024
   
   Visualización de distribuciones (uso y clientes) y outliers
1. Visualización de Distribuciones
2. Identificación de Outliers
   
   Segmentación de Clientes
1. Segmentación de Clientes Por Uso
2. Segmentación de Clientes Por Edad
3. Visualización de la Segmentación de Clientes
   
   Insight Ejecutivo para Stakeholders
1. Análisis ejecutivo

## Como ejecutar el notebook
Opciones para ejecutar tu notebook:
Google Colab (recomendado):
Ve a colab.research.google.com
Selecciona "GitHub" en la pestaña
Pega tu URL: https://github.com/claulogra/sprint7-final-project/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb
Colab abrirá tu notebook directamente
Jupyter local:
Descarga el archivo .ipynb desde GitHub
Ábrelo en tu entorno Jupyter local
