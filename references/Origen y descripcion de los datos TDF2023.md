

 DESCRIPCION COMPLETA DEL DATASET

 Información General

El dataset `delitos-tdf-2023.xlsx` contiene información detallada sobre incidentes delictivos registrados en la provincia de Tierra del Fuego durante el año 2023. Este conjunto de datos es esencial para analizar patrones de criminalidad y para ayudar en la mejora de la seguridad pública, prevención y posteriro esclareciemeintos de delitos.

Cantidad de Instancias:
- El dataset cuenta con un total de 2272 registros o filas, cada una representando un incidente delictivo individual.

Características (Columnas):
- El dataset contiene 14 características o columnas, cada una proporcionando detalles específicos sobre los incidentes delictivos. A continuación se detalla cada columna:

DICCIONARIO DE DATOS

| Nombre de la Columna     |   Tipo de Dato   |     Descripción |
|--------------------------|------------------|-----------------|
| `Fecha`                  | datetime64       | Fecha en la que ocurrió el   incidente delictivo. |
| `Día`                    | object           | Día de la semana en que ocurrió el delito (Ej: Lunes, Martes, etc.). |
| `Años`                   | int64            | Año en el que ocurrió el incidente delictivo. |
| `Zona`                   | object           | Zona geográfica donde ocurrió el incidente. |
| `Franja horaria`         | object           | Periodo del día durante el cual ocurrió el delito (Ej: Mañana, Tarde, Noche). |
| `Tipo de Acceso`         | object           | Método de acceso utilizado en el delito (Ej: Puerta forzada, Ventana rota, etc.). |
| `Latitud`                | float64          | Latitud geográfica donde ocurrió el delito. |
| `Longitud`               | float64          | Longitud geográfica donde ocurrió el delito. |
| `Lugar`                  | object           | Lugar específico donde ocurrió el delito (Ej: Casa, Calle, Tienda, etc.). |
| `Elementos Sustraidos`   | object           | Descripción de los objetos robados o afectados por el delito. |
| `Tipo de Lugar`          | object           | Tipo de establecimiento o ubicación donde ocurrió el delito (Ej: Residencial, Comercial). |
| `modus operandi`         | object           | Método o procedimiento utilizado para cometer el delito. |
| `Hechos`                 | object           | Descripción general de los hechos delictivos caratulado judicialmente. |
| `Esclarecido`            | object           | Indicador de si el delito fue esclarecido (`SI` o `NO`). |


 ORIGEN DEL DATASET

Fuente:

- Los datos provienen del gobierno de Tierra del Fuego de registros oficiales de organismos de seguridad pública de la provincia de Tierra del Fuego. Estos registros son recopilados y mantenidos por entidades gubernamentales encargadas de la seguridad y la justicia en la región.

FECHA DE ADQUISICION:

- El dataset fue adquirido en 2023 y abarca incidentes delictivos reportados durante todo el año.

PROCESO DE RECOPILACION Y PREPROCESAMIENTO:

- Los datos fueron recolectados de informes de delitos y bases de datos de incidentes delictivos mantenidos en el ano 2023.

- Se realizó un preprocesamiento para asegurar la calidad y privacidad de los datos, incluyendo la eliminación de columnas que no son relevantes para el analisis(NOMBRES, DOCUMENTOS, IMPUTADOS), se resguradaron datos sensibles, optimizando los registros necesarios para el posterior analisis del modelo.

Esta información detallada proporciona una visión completa del dataset utilizado en este proyecto, destacando su origen, contenido y preparación para el análisis y modelado predictivo.