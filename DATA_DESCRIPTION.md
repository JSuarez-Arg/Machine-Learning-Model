# Descripción del Dataset y Origen

## Descripción del Dataset
El dataset utilizado en este proyecto contiene información sobre la producción de petróleo y gas en pozos no convencionales en Tierra del Fuego. A continuación, se proporciona una descripción detallada de las características del dataset:

- **Cantidad de Instancias**: El dataset contiene un total de `X` instancias.
- **Características (Columnas)**: El dataset incluye las siguientes columnas:
  - `pozo_id`: Identificador único de cada pozo.
  - `fecha`: Fecha de la medición.
  - `produccion_petroleo`: Cantidad de petróleo producido (en barriles).
  - `produccion_gas`: Cantidad de gas producido (en metros cúbicos).
  - `profundidad`: Profundidad del pozo (en metros).
  - `formacion_productiva`: Nombre de la formación geológica productiva.
  - `ubicacion_geografica`: Coordenadas geográficas del pozo (latitud y longitud).
  - `presion`: Presión de operación del pozo (en PSI).
  - `temperatura`: Temperatura medida en el pozo (en grados Celsius).
  - `tipo_pozo`: Tipo de pozo (vertical, horizontal, etc.).

- **Tipos de Datos**:
  - `pozo_id`: Entero
  - `fecha`: Fecha
  - `produccion_petroleo`: Decimal
  - `produccion_gas`: Decimal
  - `profundidad`: Entero
  - `formacion_productiva`: Cadena de texto
  - `ubicacion_geografica`: Cadena de texto
  - `presion`: Decimal
  - `temperatura`: Decimal
  - `tipo_pozo`: Cadena de texto

## Origen del Dataset
El dataset fue recopilado de fuentes oficiales y confiables que monitorean la producción de petróleo y gas en Tierra del Fuego. A continuación, se detallan las fuentes y el proceso de recopilación:

- **Fuente**: Los datos fueron obtenidos del Ministerio de Energía y Minería de Argentina y de reportes públicos proporcionados por las compañías petroleras que operan en la región.
- **Fecha de Adquisición**: Los datos fueron adquiridos en [Fecha de adquisición].
- **Proceso de Recopilación**: 
  - Los datos históricos de producción fueron descargados de los informes mensuales publicados por el Ministerio de Energía y Minería.
  - Se recopiló información adicional directamente de las compañías petroleras a través de solicitudes de datos y acceso a sus bases de datos públicas.
  - Se realizó un proceso de preprocesamiento para limpiar y normalizar los datos, asegurando la consistencia y la precisión de la información antes de su uso en el modelado.

## Archivos de Dataset y Documentos
El dataset y los documentos relacionados están incluidos en el repositorio GIT en las siguientes ubicaciones:
- `data/raw`: Contiene los datos originales sin procesar.
- `data/interim`: Contiene los datos intermedios que han sido transformados.
- `data/processed`: Contiene los datos finales listos para el modelado.
- `references`: Contiene manuales, diccionarios de datos y cualquier otro material explicativo relevante.

Se recomienda revisar estos archivos y documentos para obtener una comprensión completa de los datos y su contexto antes de proceder con el análisis y el desarrollo de modelos de aprendizaje automático.
