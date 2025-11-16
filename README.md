# Analisis_Mercadeo_Tesla
En este proyecto se busca examinar la expansión del mercado de tesla en un periodo de 10 años.

## Integrantes:
- Ramírez Cárdenas Ianis.
- Rojas Rojas Jean Paul.
- Silva Arevalo Juan Esteban.
- Uribe Vanegas Mariana.

## Estructura De Los Datos:
Este *dataset* ofrece un análisis exhaustivo del **rendimiento global de los vehículos eléctricos (EV) de Tesla** en el período comprendido entre **2015 y 2025**.

La información cubre variables críticas en detalle, incluyendo las entregas, las unidades de producción, los costos promedio de los vehículos, la capacidad de la batería, las autonomías de conducción y las emisiones de $\text{CO}_2$ ahorradas a través de varios modelos y regiones.

El conjunto de datos tiene como objetivo principal demostrar el **crecimiento de diez años de Tesla, sus avances tecnológicos y sus logros medioambientales**. En el sector de los coches eléctricos, esta información es fundamental para tareas de **forecasting, análisis de datos, visualización y estudios de sostenibilidad**.

*Este *dataset* fue obtenido directamente de la **plataforma Kaggle**

## Diccionario De La Base De Datos:

| Columna | Descripción | Tipo de Dato (`Dtype`) | Nivel de Medición |
|:---:|:---:|:---:|:---:|
| **Year** | Año del registro de datos. | `int64` | De Intervalo |
| **Month** | Número del mes del registro. | `int64` | De Intervalo/Ordinal |
| **Region** | Región geográfica donde se registraron los datos. | `object` | Nominal |
| **Model** | Modelo específico del vehículo (ej. Model 3, Model Y). | `object` | Nominal |
| **Estimated\_Deliveries** | Número estimado de vehículos entregados en el período. | `int64` | De Razón |
| **Production\_Units** | Número total de unidades de producción. | `int64` | De Razón |
| **Avg\_Price\_USD** | Precio promedio del vehículo en Dólares Americanos (USD). | `float64` | De Razón |
| **Battery\_Capacity\_kWh** | Capacidad nominal de la batería en kilovatios-hora (kWh). | `int64` | De Razón |
| **Range\_km** | Rango o autonomía del vehículo en kilómetros (km). | `int64` | De Razón |
| **CO2\_Saved\_tons** | Estimación de toneladas de $\text{CO}_2$ ahorradas. | `float64` | De Razón |
| **Source\_Type** | Tipo o naturaleza de la fuente de donde provienen los datos. | `object` | Nominal |
| **Charging\_Stations** | Número de estaciones de carga disponibles. | `int64` | De Razón |

## Pasos De Ejecución:
1. **Acceso Al NoteBook:** Descarga o accede al link del notebook de **Colab en la pagina principal del proyecto. 
3. **Instalacion De Dependencias:** Ejecuta La primera Celda de codigo. Esta instalara todas las dependencias  y librerias Necesarias que se describen en el Requirements.txt .
4. **Analisis:** Ejecuta el resto de celdas del notebook. 

## Concluciones:
