# Ventas_cel_1mes
Análisis de ventas - empresa telecomunicaciones - ventana: 1 mes


📌 Objetivo

Realizar un análisis integral de las ventas de una empresa de telecomunicaciones durante un mes, con el fin de identificar patrones, relaciones y tendencias relevantes que apoyen la toma de decisiones estratégicas. El análisis se desarrolla en Python, aplicando técnicas de limpieza, exploración y visualización de datos para obtener conclusiones respaldadas por sus respectivos análisis.

📂 Descripción de la base de datos

La base contiene información de ventas de un mes específico, organizada en formato tabular. Características principales: Datos anonimizados y adaptados de un proyecto personal de bootcamp (respetando la privacidad). Fuente original: archivo Excel importado y tratado en Python. Variables incluyen: gama y marca de productos de telefonía, costos, ingresos, márgenes, rentabilidad, fechas de venta, entre otras.

🔍 Metodología

Carga y exploración de datos: revisión de estructura, tipos de variables y contenido.

Limpieza y preprocesamiento: tratamiento de valores nulos(, estandarización de formatos y ajuste de variables categóricas).

Análisis exploratorio (EDA): estadísticas descriptivas, visualización de distribuciones y relaciones entre variables.

Análisis específicos: revisión de correlaciones, tendencias de interés o variaciones temporales.

Interpretación de resultados: síntesis de hallazgos clave con implicaciones prácticas.

🎯 Resultados esperados

Detección de relaciones significativas entre variables clave (por ejemplo, costo vs. rentabilidad).

Obtención de insights visuales y numéricos que respalden la interpretación.

Generación de insumos claros para reportes, dashboards o presentaciones ejecutivas.

Base sólida para hipótesis y análisis futuros.



Conclusiones
🎯 Hallazgos Estratégicos Principales

Paradoja de Rentabilidad
El análisis revela un hallazgo contraintuitivo crítico: los productos más costosos son los menos rentables.

Desbalance de Representación de Datos
El dataset muestra un sesgo significativo hacia gamas bajas: Low, Entry Smart y Mid representan más del 90% de los datos, mientras que Premium y High apenas alcanzan el 3%. Este desbalance: Explica la mayor dispersión visual en gamas bajas. Puede estar sesgando las interpretaciones sobre rentabilidad por gama. Sugiere una dependencia excesiva en productos de bajo margen

Segmentación Clara del Mercado
El análisis por marca revela estrategias comerciales diferenciadas. Donde, Bmobile: Dominio absoluto en gama Low (4,500 unidades) con eficiencia excepcional. Apple: Enfoque exclusivo en segmentos premium pero con márgenes problemáticos. Samsung: Estrategia diversificada con presencia fuerte en múltiples gamas. Motorola y Xiaomi: Posicionamiento en valor por dinero (Entry Smart y Mid)


📊 Problemas Críticos Identificados

Márgenes Negativos Generalizados
Presencia de márgenes negativos en múltiples gamas y marcas. LG presenta su distribución completa en territorio negativo. Especialmente problemático en canales Retail y Tiendas. Indica productos vendidos por debajo del costo, problemas de inventarios o errores estructurales.

Ineficiencia Operativa Premium
Los productos de alto costo no generan rentabilidad proporcional. Apple, a pesar de su posicionamiento premium, muestra problemas de margen. Sugiere sobrecostos operativos o estrategias de pricing inadecuadas


🚀 Oportunidades Estratégicas

Optimización del Modelo Bmobile
Bmobile demuestra que es posible lograr: Márgenes altos con costos bajos. Rentabilidades excepcionales incluso en la gama Low. Se podría replizar su modelo en otras marcas o gamas

Aprovechamiento del Canal Islas
Aunque con menor volumen, presenta operaciones de alta rentabilidad. Márgenes más consistentes y positivos que otros canales. Potencial para productos exclusivos o estrategias estacionales

Mercado Premium Desaprovechado
Segmento Premium poco saturado con alta barrera de entrada. Oportunidad para marcas establecidas de diversificar hacia arriba. Necesidad de repensar la estrategia de costos para este segmento


📈 Recomendaciones Accionables

Inmediatas (0-3 meses)
Auditoría de productos con margen negativo - Descontinuar o reestructurar

Análisis profundo del modelo Bmobile - Identificar factores de éxito replicables

Revisión de estructura de costos Premium - Especialmente Apple y Samsung en gamas altas

Mediano Plazo (3-6 meses)
Rebalanceo del portafolio - Incrementar proporción de productos rentables

Optimización del canal Islas - Escalar las mejores prácticas identificadas

Estrategia diferenciada por gama - Políticas de pricing específicas por segmento
Largo Plazo (6+ meses)
Entrada estratégica al segmento Premium - Con estructura de costos optimizada

Diversificación controlada - Evitar la dependencia excesiva en gamas Low

Implementación de métricas ROI - Sistema de monitoreo continuo de rentabilidad
