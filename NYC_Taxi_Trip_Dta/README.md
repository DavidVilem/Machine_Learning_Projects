# NYC Taxi Trips Analysis and Predictions
## Descripción del Proyecto

Este repositorio contiene un análisis de datos y modelos predictivos basados en los viajes en taxi de la ciudad de Nueva York (NYC). Utilizando una serie de características de los datos de los taxis, se busca crear varios modelos para predecir diferentes resultados y detectar patrones.

## Datos Utilizados

Los datos incluyen información sobre los viajes en taxi, con las siguientes características:

- **VendorID**: Identificador del proveedor del taxi.
- **tpep_pickup_datetime**: Fecha y hora de recogida.
- **tpep_dropoff_datetime**: Fecha y hora de llegada.
- **passenger_count**: Número de pasajeros en el taxi.
- **trip_distance**: Distancia del viaje en millas.
- **RatecodeID**: Código de la tarifa aplicada.
- **store_and_fwd_flag**: Indicador si los datos del viaje fueron almacenados antes de ser enviados.
- **PULocationID**: Código de la ubicación de recogida.
- **DOLocationID**: Código de la ubicación de destino.
- **payment_type**: Método de pago utilizado.
- **fare_amount**: Monto de la tarifa base del viaje.
- **extra**: Cargos adicionales (ej. nocturno o hora pico).
- **mta_tax**: Impuesto de la MTA.
- **tip_amount**: Monto de la propina.
- **tolls_amount**: Monto de los peajes.
- **improvement_surcharge**: Recargo obligatorio por mejoras.
- **total_amount**: Monto total del viaje, incluyendo todos los cargos.
- **congestion_surcharge**: Recargo por congestión.
- **airport_fee**: Tarifa adicional por viajes hacia o desde aeropuertos.

## Objetivos del Proyecto

### Posibles Modelos a Implementar:

1. **Predicción de la Tarifa Total (Regresión)**
   - **Objetivo**: Predecir el valor de la tarifa total (`total_amount`) basándose en características como la distancia del viaje, número de pasajeros, ubicación de recogida y destino, tipo de pago, entre otros.

2. **Clasificación del Tipo de Pago (Clasificación)**
   - **Objetivo**: Clasificar el tipo de pago (`payment_type`) que el pasajero usará, basado en variables como la distancia, cantidad de pasajeros, ubicación de recogida y destino, etc.

3. **Detección de Anomalías en Tarifas (Anomalía)**
   - **Objetivo**: Detectar anomalías en el valor de la tarifa (`fare_amount`) o propinas (`tip_amount`), ya que algunas tarifas podrían ser mucho más altas o bajas de lo esperado.

4. **Predicción del Tiempo de Viaje (Regresión)**
   - **Objetivo**: Predecir el tiempo de viaje basado en las ubicaciones de recogida y destino, la distancia, y otras características del viaje.

5. **Segmentación de Pasajeros (Clustering)**
   - **Objetivo**: Agrupar viajes en función de patrones como la distancia, número de pasajeros, tarifa total, propina, y otros factores para identificar segmentos de usuarios o tipos de viajes.

6. **Predicción de Congestión de Tráfico (Clasificación/Regresión)**
   - **Objetivo**: Predecir si un viaje estará sujeto a congestión basándote en las ubicaciones, distancia y otras características.


