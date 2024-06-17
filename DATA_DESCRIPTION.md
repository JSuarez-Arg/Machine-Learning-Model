# Descripción del Dataset y Origen

## Descripción del Dataset : "14_2_01-Produccion-de-Petroleo-y-Gas.-2"
El dataset utilizado en este proyecto contiene información sobre la producción de petróleo y gas en pozos no convencionales en Tierra del Fuego. A continuación, se proporciona una descripción detallada de las características del dataset:

- **Cantidad de Instancias**: El dataset contiene un total de `13` instancias.
  - `Total Anual`: Indica las Cantidades Totales de Petróleo en m3 y gas en Mm3 producidos anualmente.
  - `Mes`: Indica los diferentes meses del año (Enero, Febrero, Marzo, Abril, Mayo, Junio, Julio, Agosto, Septiembre, Octubre, Noviembre y Diciembre).
- **Características (Columnas)**: El dataset incluye las siguientes columnas:
  - `año`: Año de la medición. (Cuenta con Datos Históricos que van desde el año 2001 al 2024).
  - `Petróleo`: Cantidad de petróleo producido, medido en m3.
  - `Gas`: Cantidad de gas producido, medido en Mm3.
  

- **Tipos de Datos**:
  - `Total Anual`: Entero
  - `Mes`: Fecha
  - `año`: Decimal
  - `Petróleo`: Decimal
  - `Gas`: Entero

## Origen del Dataset
El dataset fue recopilado de fuentes oficiales y confiables que monitorean la producción de petróleo y gas en Tierra del Fuego. A continuación, se detallan las fuentes y el proceso de recopilación:

- **Fuente**: Los datos fueron obtenidos del "IPIEC: Instituto Provincial de Análisis e Investigación, Estadísticas y Censos"
- **Fecha de Adquisición**: Los datos fueron adquiridos en 16/06/2024.
- **Proceso de Recopilación**: 
  - Los datos históricos de producción fueron descargados de los informes mensuales publicados por el "IPIEC: Instituto Provincial de Análisis e Investigación, Estadísticas y Censos".
  - Se recopiló información adicional directamente de sitios web confiables como https://datos.gob.ar/ para tener acceso a bases de datos públicas.

    Dataset: "produccin-de-pozos-de-gas-y-petrleo-no-convencional"
  - Se recopiló información adicional directamente de sitios web confiables como https://www.argentina.gob.ar/eiti/visualizaciones/prod_petroleo_prom_diaria_por_provincia para tener acceso a bases de datos públicas y tableros dinámicos realizados en Power BI.

    Dataset: "produccin-de-petrleo-promedio-diaria-por-provincia"
  - Se realizó un proceso de preprocesamiento para limpiar y normalizar los datos, asegurando la consistencia y la precisión de la información antes de su uso en el modelado.

## Archivos de Dataset y Documentos
El dataset y los documentos relacionados están incluidos en el repositorio GIT en las siguientes ubicaciones:
- `data/raw`: Contiene los datos originales sin procesar.
- `data/interim`: Contiene los datos intermedios que han sido transformados.
- `data/processed`: Contiene los datos finales listos para el modelado.
- `references`: Contiene manuales, diccionarios de datos y cualquier otro material explicativo relevante.

Se recomienda revisar estos archivos y documentos para obtener una comprensión completa de los datos y su contexto antes de proceder con el análisis y el desarrollo de modelos de aprendizaje automático.
