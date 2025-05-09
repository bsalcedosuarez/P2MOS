# Proyecto C: Optimización en la Planificación de Rutas Nacionales y Estrategia de Recarga para LogistiCo

## Integrantes

- **Julian David Parra Forero**  
- **Brayan Estiven Salcedo Suarez**  
- **Juan Diego Sanchez**

## Descripción General

Este proyecto tiene como objetivo la implementación en Pyomo de un modelo de optimización para la planificación de rutas nacionales de transporte de carga, integrando estrategias óptimas de recarga de combustible. El sistema busca minimizar los costos totales considerando múltiples factores como distancias, peajes, consumo de combustible y restricciones de peso por municipio.

## Objetivo

Desarrollar un modelo de optimización que:
- Minimice los costos totales de transporte.
- Considere distancias, peajes y precios variables de combustible.
- Respete restricciones de capacidad de carga, autonomía y regulaciones locales de peso.

## Contexto

El transporte de carga en Colombia enfrenta diversos desafíos como la variabilidad en precios de combustible, las tarifas de peajes que dependen del peso transportado y las restricciones locales impuestas por los municipios. Esta complejidad requiere una solución computacional robusta que permita tomar decisiones eficientes sobre rutas y puntos de recarga.

## Estructura del Proyecto

### Caso 1: CVRP Estándar
- Modelo básico con origen (puerto) y destinos (municipios).
- Restricciones de capacidad y autonomía.
- Optimización basada en distancia y demanda.

### Caso 2: Incorporación de Recarga
- Extensión del Caso 1 para incluir decisiones de recarga.
- Consideración de precios variables de combustible por estación.
- Garantizar autonomía de los vehículos en todo momento.

### Caso 3: Escenario Complejo
- Añadir restricciones de peso por municipio.
- Inclusión de tarifas de peaje variables según peso y tramo.
- Estrategias conjuntas de ruteo y recarga para minimizar el costo total.

## Datos del Problema


## Archivos de Verificación

Se generarán archivos `.csv` para validar los resultados en cada caso, incluyendo:
- Secuencia de rutas
- Cantidad de demanda satisfecha
- Carga inicial, combustible inicial
- Recargas (en caso 2 y 3)
- Distancia total, tiempo estimado, costos de combustible y totales


