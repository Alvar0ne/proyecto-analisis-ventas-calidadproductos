# Proyecto de analisis de ventas y calidad de productos

## Contexto del negocio

La empresa necesita entender cómo las fallas de calidad están afectando ventas, rentabilidad y experiencia de cliente.

Esto dificulta responder preguntas clave como:

- ¿Que productos presentan mas fallas?
- ¿Cuales son los proveedores que entregan productos con mas fallas ?
- ¿Que impacto economico tiene estas devoluciones?
- ¿Qué tan confiables son los datos?

El objetivo de este proyecto es transformar datos desordenados en información accionable para la toma de decisiones.


## Fuentes de datos

Se integraron múltiples archivos de diferentes fuentes:

- Fuente 1: Ventas
  Archivo CSV exportado desde el ERP "ventas_erp_50000.csv"
  
- Fuente 2: Calidad / devoluciones
  Archivo Excel del área de postventa "devoluciones_calidad_2000.xlsx"

- Fuente 3: Catálogo maestro de productos
  Archivo JSON o tabla SQL "catalogo_tecnologia_500_v2.json"



Los datos presentan problemas reales como:

- Nombres inconsistentes
- Espacios
- Formatos distintos
- Diferentes formas de escribir lo mismo
- Registros duplicados
- Valores faltantes


## Proceso de análisis

Parte del proyecto fue desarrollado en Python utilizando pandas y para en analisis PowerBI

Etapas principales:

1. Carga de múltiples fuentes de datos
2. Diagnóstico de calidad de datos
3. Limpieza y estandarización
4. Validaciones de negocio
5. Cruce de tablas (joins)
6. Construcción de base consolidada
7. Cálculo de KPIs
8. Análisis de impacto económico
9. Visualización de resultados


Implementé una tabla calendario en Power BI para habilitar análisis temporal y métricas de inteligencia de tiempo


