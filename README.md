# Proyecto_Final_ST002115
Este repositorio contiene el flujo de trabajo y la documentación correspondiente al análisis metabolómico del estudio ST002115 del Metabolomics Workbench, titulado "LC-MS analysis of metabolic changes induced by GPX4 inhibitor treatment in cultured HT1080 cells".
# Proyecto Final - Análisis metabolómico ST002115

## Descripción

Este repositorio contiene el análisis metabolómico realizado sobre el estudio ST002115 del repositorio Metabolomics Workbench, utilizando la plataforma MetaboAnalyst 6.0.

## Objetivo

Evaluar los cambios en el perfil metabolómico de células HT1080 tratadas con los inhibidores de GPX4 (ML162, ML210 y RSL3) en comparación con el control DMSO.

## Contenido del repositorio

data/
Archivos de entrada utilizados para el análisis.

figures/
Figuras obtenidas durante el análisis (PCA, Scree Plot, Loading Plot, Biplot, Heatmap y ANOVA).

scripts/
Descripción del pipeline utilizado en MetaboAnalyst.

## Pipeline analítico

1. Descarga de datos procesados (ST002115).
2. Verificación de integridad de los datos.
3. Normalización: None.
4. Transformación: Log10.
5. Escalamiento: Pareto Scaling.
6. Análisis PCA.
7. Scree Plot.
8. Loading Plot.
9. Biplot.
10. Heatmap jerárquico.
11. ANOVA con corrección FDR.
12. Interpretación biológica.

## Software utilizado

MetaboAnalyst 6.0

## Dataset

Study ID: ST002115

DOI: 10.21228/M8HD8Q

## Reproducibilidad

Para reproducir el análisis:

- Descargar los archivos contenidos en la carpeta data/.
- Ingresar a MetaboAnalyst 6.0.
- Seleccionar el módulo "Statistical Analysis".
- Configurar:
  - Normalización: None
  - Transformación: Log10
  - Escalamiento: Pareto Scaling
- Ejecutar PCA, Scree Plot, Loading Plot, Biplot, Heatmap y ANOVA.

## Autores
Angie Carolina Fuerte
Clara sofia Ordoñez
Daniela Domínguez Castaño
Correo: (danieladominguez24@gmail.coom)
