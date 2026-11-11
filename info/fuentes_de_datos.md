# Fuentes de datos del proyecto

## Accidentes de tránsito con víctimas

- Archivo utilizado: data/datos accidentes.xlsx
- Periodo: 2020–2025
- Fuente: Consejo de Seguridad Vial (COSEVI), Consolidado de accidentes de tránsito con víctimas.
- Publicación: https://datosabiertos.csv.go.cr/datasets/193472/consolidado-de-accidentes-de-transito-con-victimas/
- Unidad de análisis: cada fila del archivo.

El archivo contiene estas columnas: Clase de accidente, Tipo de accidente, Año, Hora, Hora recodificada, Provincia, Cantón, Distrito, Ruta, Kilómetro, Rural o urbano, Calzada vertical, Calzada horizontal, Tipo de calzada, Tipo de circulación, Estado del tiempo, Estado de la calzada, Región Mideplan, Tipo ruta, Día y Mes.

## Consideraciones para el análisis

- La base corresponde a accidentes con víctimas; no representa los accidentes que solo tuvieron daños materiales.
- La categoría “Con muertos o graves” se mantiene tal como aparece en los datos.
- La base no incluye volumen de tránsito, cantidad de viajes ni kilómetros recorridos. Por eso, los conteos y porcentajes describen los registros disponibles y no son tasas de riesgo.
- Los meses y días se limpian y ordenan al preparar el análisis; el archivo Excel original se conserva sin cambios.
