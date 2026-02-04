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
 ### 1. Cargar y explorar:
    
Carga de datos y vista rápida

Exploración de la estructura de los Dataset
   
### 2. Identificación de problemas de calidad de datos:
   
Revisión de valores nulos

Detección de valores inválidos y sentinels

Revisión y estandarización de fechas
   
### 3. Limpieza básica de datos:
   
Corregir sentinels y fechas imposibles

   
### 4. Summary statistics de uso por usuario:
   
Agrupación por comportamiento de uso

Resumen estadístico por usuario durante el 2024
   
### 5. Visualización de distribuciones (uso y clientes) y outliers:
    
Visualización de Distribuciones

Identificación de Outliers

### 6. Segmentación de Clientes:
    
Segmentación de Clientes Por Uso

Segmentación de Clientes Por Edad

Visualización de la Segmentación de Clientes
   
### 7. Insight Ejecutivo para Stakeholders:

Análisis ejecutivo

## Como ejecutar el notebook
Opciones para ejecutar tu notebook:

Google Colab (recomendado):
1. Ve a colab.research.google.com
2. Selecciona "GitHub" en la pestaña
3. Pega tu URL: https://github.com/claulogra/sprint7-final-project/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb
4. Colab abrirá tu notebook directamente

Jupyter local:
1. Descarga el archivo .ipynb desde GitHub
2. Ábrelo en tu entorno Jupyter local
