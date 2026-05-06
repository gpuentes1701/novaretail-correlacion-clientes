</> Markdown
##📊 NovaRetail+: Análisis de comportamiento de clientes

Análisis exploratorio y correlacional enfocado en identificar los principales drivers de ingreso en clientes de una plataforma e-commerce en Latinoamérica.

##🎯 Objetivo

Analizar qué factores del comportamiento del cliente están más asociados con el ingreso anual generado.

##🧩 Dataset
15,000 clientes
Fuente: NovaRetail+

**Variables clave:**

- visitas_mes
- compras_mes
- satisfacción
- miembro_premium
- abandono
- ingreso_anual (variable objetivo)
  
##🛠️ Herramientas
Python (pandas, numpy)
seaborn, matplotlib
Jupyter Notebook

##🔍 Análisis realizado
Limpieza y preparación de datos
Visualización (heatmap y scatterplots)
Correlaciones:
Pearson
Spearman
Punto biserial
V de Cramér

##📈 Principales hallazgos
La **frecuencia de compra (compras_mes)** es el principal driver del ingreso.
La **membresía premium** tiene una asociación positiva moderada, sugiriendo potencial para estrategias de upselling.
La **satisfacción** muestra una relación débil con el ingreso.
Se identificaron correlaciones que no implican causalidad.

##⚠️ Limitaciones
Correlación ≠ causalidad
Variables externas no incluidas
Posible sesgo en datos

##🚀 Recomendaciones
Enfocar estrategias en aumentar frecuencia de compra
Optimizar programa premium
Diseñar experimentos A/B para validar causalidad

##▶️ Cómo ejecutar
Descargar el repositorio
Abrir el notebook en Jupyter o Google Colab
Ejecutar las celdas en orden
