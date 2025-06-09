## Análisis de Datos Educativos en Colombia :wave:

## Descripción del Proyecto

Este proyecto presenta un análisis completo de datos educativos de Colombia, enfocándose en indicadores clave como cobertura educativa, tasas de aprobación, deserción y repitencia a nivel municipal y departamental durante el período 2011-2023.

## Objetivos :point_down:

•	Analizar la calidad y acceso educativo en Colombia

•	Identificar patrones y tendencias en indicadores educativos

•	Evaluar diferencias regionales en el desempeño educativo

•	Detectar outliers y valores atípicos que requieran atención especial

## Metodología :point_right:
## 1. Limpieza y Preparación de Datos
   
## Corrección de Tipos de Datos:

•	Se convirtió la variable POBLACIÓN_5_16 de formato texto a numérico, eliminando comas como separadores de miles
Manejo de Valores Faltantes:

•	Se identificó que las columnas TAMAÑO_PROMEDIO_DE_GRUPO y SEDES_CONECTADAS_A_INTERNET tenían aproximadamente 50% de datos faltantes

•	Estas columnas fueron eliminadas por no ser relevantes para el objetivo del análisis

•	Los valores faltantes restantes (menos del 6%) fueron imputados con la mediana de cada variable

## Estandarización:
•	Se corrigieron inconsistencias en nombres de departamentos (ej: "Bogotá, D.C." → "Bogotá D.C.")

•	Se eliminaron registros con valor "NACIONAL" para mantener solo datos a nivel departamental



## 3. Análisis Exploratorio de Datos (EDA) :point_down:

## Estadísticas Descriptivas:

•	El análisis reveló una alta variabilidad en los indicadores educativos

•	Se identificó la presencia significativa de valores atípicos en múltiples variables

## Análisis de Outliers:

•	Los outliers representan realidades importantes (municipios con crisis educativa) que requieren atención especial

•	Se decidió mantenerlos en el análisis por su relevancia contextual

•	La alta variabilidad sugiere diferencias significativas entre municipios

## Principales Hallazgos

## 1. Análisis de Cobertura por Departamento

## Observaciones Clave: :point_down:

•	Todos los departamentos presentan múltiples outliers en cobertura bruta

•	Departamentos como Cundinamarca, Cauca y Boyacá muestran mayor concentración de outliers superiores

•	Esto sugiere posible exceso de matrícula o repetición escolar en ciertas zonas

## 2. Evolución Temporal (2011-2023)

## Tendencias Identificadas:

•	Se mantiene una cantidad significativa de outliers a lo largo del tiempo

•	Los años 2016 y 2017 mostraron mayor concentración de valores atípicos

•	La distribución central es relativamente estable, pero persisten inequidades

## 3. Variables Educativas Clave

## Patrones Observados:

•	Variables como Tasa de Matrícula, Cobertura Neta y Aprobación presentan muchos outliers altos

•	Deserción y Reprobación muestran valores extremos con menor dispersión general

•	Alta variabilidad entre regiones y años


## 4. Análisis de Correlaciones

## Relaciones Identificadas:

•	La cobertura escolar alta no garantiza automáticamente mejor calidad educativa

•	Los indicadores de calidad (aprobación, repitencia) no dependen directamente de la cobertura

•	Se requiere un enfoque integral que combine acceso y calidad

## 5. Comparación por Años

## Evolución de Indicadores:

•	Cobertura Neta: Relativamente estable, oscilando entre 83% y 87%

•	Aprobación: Tendencia descendente de 92.8% (2011) a 89.8% (2023)

•	Reprobación: Tendencia ascendente de 2.4% (2011) a 6.5% (2023)

## 6. Ranking Departamental por Aprobación

## Mejores Desempeños:

1.	Nariño (95.5%)
   
3.	Amazonas (95.0%)
4.	Bogotá D.C. (95.0%)
5.	San Andrés y Providencia (94.8%)
6.	Cundinamarca (94.8%)
   
## Menores Desempeños:

•	Guainía (79.0%)
•	Vaupés (83.7%)
•	Vichada (84.0%)





## Conclusiones y Recomendaciones

## Interpretación de Cobertura Bruta

Los outliers en cobertura bruta están asociados con:

•	Repetición de grados
•	Ingreso tardío o anticipado al sistema educativo
•	Cobertura superior al 100% (posible en cobertura bruta)

## Recomendaciones Estratégicas :point_down:

1.	Enfoque Integral: La ampliación de cobertura debe ir acompañada de estrategias pedagógicas y de apoyo académico
   
3.	Atención Focalizada: Los departamentos con menor desempeño (territorios nacionales) requieren intervención prioritaria
   
5.	Mejora de Calidad: Implementar intervenciones que fortalezcan el aprendizaje y reduzcan el rezago escolar
   
## 7.	Monitoreo Continuo:

Establecer sistemas de seguimiento a los municipios con indicadores atípicos

## Consideraciones Metodológicas

•	Los outliers representan realidades importantes que no deben ignorarse

•	La alta variabilidad refleja inequidades que requieren políticas públicas focalizadas

•	El análisis temporal muestra una preocupante tendencia hacia el deterioro de algunos indicadores de calidad

:point_right: Este análisis proporciona una base sólida para la toma de decisiones en política educativa, identificando tanto fortalezas como áreas de mejora en el sistema educativo colombiano.

