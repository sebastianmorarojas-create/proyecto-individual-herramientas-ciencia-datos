# Proyecto individual - Carta al estudiante

Proyecto individual del curso C0204 Herramientas de Ciencia de Datos I (2026). El análisis explora datos de accidentes de tránsito mediante R y Quarto.

## Estructura

- `cod/`: documentos Quarto y código fuente, ordenados por ejecución.
- `data/`: datos de entrada locales. Los archivos Excel se excluyen de Git según las indicaciones del curso.
- `info/`: contexto, referencias y documentación del proyecto.
- `config/`: parámetros de ejemplo; no guardar credenciales.
- `res/`: resultados generados que pueden regenerarse.

## Para abrir y ejecutar

1. Abrir `proyecto-individual.Rproj` en RStudio.
2. Confirmar que el archivo de datos `datos accidentes.xlsx` esté dentro de `data/`.
3. Abrir `cod/01_exploracion_accidentes.qmd` y renderizarlo con Quarto.

El archivo Excel se conserva localmente y no se publica en este repositorio, conforme a la guía del curso. Si se clona el repositorio en otra computadora, colocar una copia autorizada del archivo dentro de `data/` antes de renderizar.

## Historial de cambios

Los cambios se guardan en commits pequeños con mensajes `tipo: descripción` (por ejemplo, `feat: agrega gráfico por provincia`). Para trabajo nuevo, usar ramas como `feat/nuevo-grafico` y fusionarlas a `main`.
