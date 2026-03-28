# Prevencion de cancelacion de suscripcion de gimnasio
![Static Badge](https://img.shields.io/badge/-Python-%233776AB?logo=python&logoColor=white)

## Descripción del proyecto
El proyecto pide desarrollar una estrategia de interacción con clientes basada en datos analíticos para una hipotética cadena de gimnasios.  En este caso, consideramos que un/a cliente se ha ido si no visita el gimnasio durante un mes.

## Objetivo del proyecto
Con el fin de evitar la cancelación, el objetivo del proyecto consiste en:
* Aprender a predecir la probabilidad de pérdida (para el próximo mes) para cada cliente
* Elaborar retratos de usuarios físicos: crear grupos de clientes con características similares
* Analizar los factores que más impactan la pérdida.

## Metodologia
1. Cargar dataset
2. Data Cleaning (Preparación): Remover errores, inconsistencias, duplicados, procesar datos faltantes y unir varias tablas.
3. Análisis exploratorio de los datos (EDA): Realizar un análisis preliminar del comportamiento de los clientes del gimnasio
4. Modelado de datos e interpretación: Aplicar modelo de  agrupación  K-Means, identificar grupo de clientes en riesgo de cancelar.
5. Visualización (Matplotlib) y reportar

## Descripción de los datos:
* gender: genero
* Near_Location: si el usuario vive o trabaja en el vecindario donde se encuentra el gimnasio
* Partner: si el usuario trabaja en una compañía asociada.
* Promo_friends: si el usuario originalmente se inscribe mediante una oferta ‘trae un amigo’
* Phone: si el usuario aportó el número de telefono
* Age: edad
* Lifetime: los meses que el usuario lleva en el gimnasio
* Contract_period: Periodo del contrato
* Month_to_end_contract: los meses que faltan hasta que expire el contrato
* Group_visits: si el usuario participa en sesiones grupales
* Avg_class_frequency_total: frecuencia media de visitas por semana en total
* Avg_class_frequency_current_month: frecuencia media de visitas por semana durante el mes en curso
* Avg_additional_charges_total: cantidad total de dinero gastado en otros servicios del gimnasio.
