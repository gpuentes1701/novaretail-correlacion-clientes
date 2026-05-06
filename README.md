📊 NovaRetail+: Análisis de comportamiento de clientes

Análisis exploratorio y correlacional enfocado en identificar los principales drivers de ingreso en clientes de una plataforma e-commerce en Latinoamérica.

🎯 Objetivo

Analizar qué factores del comportamiento del cliente están más asociados con el ingreso anual generado.

🧩 Dataset
15,000 clientes
Fuente: NovaRetail+

**Variables clave:**

- visitas_mes
- compras_mes
- satisfacción
- miembro_premium
- abandono
- ingreso_anual (variable objetivo)
  
🛠️ Herramientas
Python (pandas, numpy)
seaborn, matplotlib
Jupyter Notebook

🔍 Análisis realizado
Limpieza y preparación de datos
Visualización (heatmap y scatterplots)
Correlaciones:
Pearson
Spearman
Punto biserial
V de Cramér

📈 Principales hallazgos
La **frecuencia de compra (compras_mes)** es el principal driver del ingreso. <br>
La **membresía premium** tiene una asociación positiva moderada, sugiriendo potencial para estrategias de upselling. <br>
La **satisfacción** muestra una relación débil con el ingreso. <br>
Se identificaron correlaciones que no implican causalidad.

⚠️ Limitaciones

Correlación ≠ causalidad <br>
Variables externas no incluidas <br>
Posible sesgo en datos

🚀 Recomendaciones

Enfocar estrategias en aumentar frecuencia de compra <br>
Optimizar programa premium <br>
Diseñar experimentos A/B para validar causalidad

▶️ Cómo ejecutar

Descargar el repositorio <br>
Abrir el notebook en Jupyter o Google Colab <br>
Ejecutar las celdas en orden
