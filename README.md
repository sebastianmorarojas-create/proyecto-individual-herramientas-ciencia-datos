# Proyecto individual: accidentes de tránsito en Costa Rica

Este proyecto del curso C0204 Herramientas de Ciencia de Datos I describe los accidentes de tránsito con víctimas registrados en Costa Rica entre 2020 y 2025. El análisis compara los registros por año, mes, día, hora, provincia y tipo de accidente.

## Cómo generar el informe

1. Abra proyecto-individual.Rproj en RStudio.
2. Abra patrones_accidentes_transito_costa_rica.qmd dentro de cod.
3. Pulse Render para generar el informe HTML.

Se necesita R con los paquetes tidyverse y readxl, además de Quarto. La base de datos se encuentra en data. La descripción de su fuente, columnas y limitaciones está en info/fuentes_de_datos.md.

## Carpetas

- cod contiene el documento Quarto con el código y el análisis.
- data contiene la base de accidentes.
- info contiene la documentación sobre los datos y el proyecto.
- config queda reservado para opciones de configuración si el análisis llega a necesitarlas.
- res se reserva para el informe final, tablas o gráficos preparados para la entrega.

## Fuente

Los datos provienen del Consolidado de accidentes de tránsito con víctimas publicado por el Consejo de Seguridad Vial (COSEVI).
