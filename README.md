# Analisis_Mercadeo_Tesla
En este proyecto se busca examinar la expansión del mercado de Tesla en un periodo de 10 años.

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
4. **Análisis:** Ejecuta el resto de celdas del notebook. 

## Conclusiones:
1. Tras el análisis realizado con respecto a la variable `Ratio_Envios_Por_Unidad`, se infiere que Tesla procura ofrecer una cantidad de vehículos superior a la demanda sin que le genere grandes pérdidas para así mantener a todos sus clientes satisfechos.
2. Considerando el límite inferior del rango del precio promedio en dólares (80,000 USD), se deduce que, a pesar de que Tesla tiene una segmentación propia respectiva a la gamma se sigue considerando una marca de lujo, puesto que, en comparación al promedio del mercado, sus `gammas bajas` continúan siendo modelos de gamma alta.
3. Se considera que Tesla es una marca que no discrimina a sus consumidores según su región, lo que supone una estrategia comercial balanceada, de manera que su distribución es equitativa independientemente del modelo.
4. Se presenta una gran cantidad de vehículos de gamma alta (320 unidades) y de gamma Baja (157 unidades) sobre el 35% de los que tienen mayor ahorro de C02, lo que demuestra que los beneficios de la reducción de carbono no son exclusivos de los vehículos de gamma alta, sino que también están presentes en los modelos más asequibles. Esta comparación es necesaria para la implementación de una estrategia de promoción de los vehículos eléctricos Tesla, debido a que esto valida con más fuerza su ahorro de emisiones C02 frente al mercado.
5. Basándonos en las variables de la base de datos, los modelos no presentan diferencias técnicas significativas, afirmando la equitatividad de la marca respecto a la producción de sus vehículos, lo que sugiere que estos se diferencien en diseño u otras características estéticas y de equipamiento.
