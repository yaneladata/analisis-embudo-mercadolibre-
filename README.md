## 📊  MercadoLibre: Conversion Funnel & User Retention Analysis

Un análisis exhaustivo de analítica de producto enfocado en el comportamiento transaccional y la retención de usuarios activos de MercadoLibre en 10 países de Latinoamérica, durante el periodo 01/01/2025 - 31/08/2025.

 ## 🎯 Contexto y Problema Analizado

MercadoLibre buscaba evaluar la eficiencia de su experiencia de compra y la sostenibilidad de la base de usuarios registrados. Este análisis resuelve dos preguntas estratégicas de negocio:

Fricción en el Embudo de Conversión: ¿En qué paso del proceso de compra se pierde la mayor proporción de usuarios y cómo varía este comportamiento según el mercado geográfico?

Sostenibilidad del Engagement (Retención): ¿Cómo evoluciona el retorno de usuarios activos a los 7, 14, 21 y 28 días (D7, D14, D21, D28) y en qué momentos ocurren las mayores fugas de retención?

 ## 🛠️ Herramientas y Metodología

Herramienta Principal: Google Sheets / Excel (Tablas dinámicas, agregaciones avanzadas y modelado de cohortes).

 ## Técnicas de Análisis:

- Funnel Analysis: Evaluación cuantitativa de conversión acumulada y drop-off incremental en 6 etapas (select_item ➡️ purchase).

- Cohort & Retention Analysis: Seguimiento de curvas de retención por cohorte mensual de registro (2025-01 a 2025-08) y segmentación por país.

- Enfoque de Negocio: Formato de informe ejecutivo C → F → I (Contexto, Hallazgos e Implicaciones).

 ## 🔄 Proceso de Análisis

- Estructuración y Normalización: Limpieza de datos transaccionales de eventos y estandarización de tasas de retención por país y cohorte.

- Mapeo del Embudo Global y Regional: Identificación de tasas de conversión punta a punta y puntos de fuga crítica por país.

- Análisis de Cohortes de Retención: Medición del porcentaje de usuarios activos que regresan a la plataforma en los hitos D7, D14, D21 y D28.

- Síntesis Ejecutiva: Elaboración de recomendaciones priorizadas por retorno de inversión (ROI) e impacto en UX/UI.

 ## 💡 Principales Hallazgos

1. Embudo de Conversión (Funnel Analysis)

Caída Crítica (Drop-off Máximo): El 85.7% de los usuarios que seleccionan un producto abandonan antes de añadirlo al carrito (select_item 76.90% ➡️ add_to_cart 11.01%), representando una pérdida de 65.89 puntos porcentuales.

Conversión Final Global: La tasa de compra completada (purchase) a nivel LATAM es del 1.25%.

<img width="1628" height="756" alt="image" src="https://github.com/user-attachments/assets/d10cb651-0c96-4951-97f4-c387e7b90724" />




## 📁 Archivos
- `embudo_general.csv`: resumen global del embudo.
- `embudo_por_pais.csv`: análisis comparativo por país.
- `retencion_datos.csv`: métricas de retención de usuarios.

## 🚀 Impacto esperado
Este análisis permite comprender los puntos críticos del embudo de conversión en MercadoLibre y las variaciones de retención entre países.
- Equipos de marketing: obtienen información para diseñar campañas más efectivas, enfocadas en reducir la caída entre select_item y add_to_cart.
- Áreas de producto: pueden priorizar mejoras en la experiencia de usuario durante el checkout y la navegación.
- Gestión regional: facilita la comparación entre países y la identificación de mercados con mayor potencial de optimización.






