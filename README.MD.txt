# Análisis de Ventas y Rendimiento Comercial — Superstore USA 2017-2020

## Descripción
Proyecto de análisis de ventas de una tienda retail en Estados Unidos
con datos de 2017 a 2020. El objetivo fue identificar qué categorías,
regiones y segmentos de clientes generan más valor para el negocio,
y detectar patrones estacionales en las ventas.

Este es mi tercer proyecto de portafolio, desarrollado de forma
autodidacta aplicando el flujo completo de análisis de datos.

## Contexto del negocio
Se simuló un escenario real donde el Gerente Comercial necesitaba
información para decidir en qué categorías invertir más y qué
regiones reforzar antes de la junta directiva.

## Herramientas utilizadas
- MySQL Workbench — limpieza de datos y consultas SQL
- Power BI Desktop — visualización y construcción de dashboard

## Flujo de trabajo aplicado
1. Recibir los datos
2. Entender el objetivo — preguntas al cliente
3. Limpiar en Excel
4. Cargar en MySQL
5. Analizar con SQL
6. Visualizar en Power BI
7. Comunicar con la Escalera Analítica

## Preguntas de negocio respondidas
1. ¿Qué categoría de producto genera más ventas totales?
2. ¿Qué categoría genera más ventas promedio por orden?
3. ¿Qué región está rindiendo por debajo en ventas?
4. ¿En qué mes las ventas han caído históricamente?
5. ¿Qué segmento de cliente gasta más por compra?

## Hallazgos principales y Escalera Analítica

### Hallazgo 1 — Categoría líder
- **Qué pasó:** Furniture generó $5,428,811 liderando sobre
  Technology ($3,213,386) y Office Supplies ($2,505,450)
- **Por qué:** Furniture tiene menos registros que Office Supplies
  pero sus productos tienen mayor valor unitario — ticket promedio
  de $2,612 vs $424 de Office Supplies
- **Decisión:** Mantener y reforzar el inventario de Furniture.
  Revisar qué productos de Office Supplies tienen bajo desempeño

### Hallazgo 2 — Región más débil
- **Qué pasó:** South es la región que menos vende con $1,512,981
  — menos de la mitad que West con $3,602,157
- **Por qué:** South tiene menos productos registrados (1,598)
  comparado con West (3,140) lo que limita su volumen
- **Decisión:** Analizar qué productos funcionan en West y evaluar
  si tienen demanda en South antes de invertir en inventario

### Hallazgo 3 — Patrón estacional
- **Qué pasó:** Febrero es el mes más bajo con $193,833.
  Noviembre y Diciembre son los más altos con +$1.5M cada uno
- **Por qué:** Comportamiento típico del retail — pico en temporada
  navideña y caída en los primeros meses del año
- **Decisión:** Preparar inventario en Octubre para el pico de
  fin de año. Lanzar campañas de reactivación en Febrero

### Hallazgo 4 — Segmentos de clientes
- **Qué pasó:** Los 3 segmentos tienen promedio muy similar —
  Consumer $1,162, Corporate $1,116, Home Office $1,099
- **Por qué:** Consumer llega a ese promedio por alto volumen
  (5,101 registros). Corporate y Home Office con menos volumen
  generan el mismo promedio — son más eficientes
- **Decisión:** Enfocar campañas de alto valor en Corporate y
  Home Office — generan el mismo ticket con menos esfuerzo

## Fuente de datos
Kaggle — Superstore Sales Dataset

## Autor
**Luis David Broquis**
Técnico en Desarrollo de Software (SENA)
Orientado al Análisis de Datos — Aprendizaje Autodidacta
Buenaventura, Valle del Cauca — Colombia
GitHub: github.com/Davidbroquis