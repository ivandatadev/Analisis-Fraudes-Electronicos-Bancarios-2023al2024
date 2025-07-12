# Analisis-Fraudes-Electronicos-Bancarios-2023al2024
Fraudes electronicos bancarios años 2023 y 2024

# 🔐 Análisis de Reclamos por Fraudes Electrónicos Bancarios

Este proyecto analiza datos mensuales de reclamos únicos, montos involucrados y clientes afectados por fraudes electrónicos en la banca chilena durante los años 2023 y 2024. El objetivo principal es generar métricas ejecutivas y visualizaciones que permitan identificar tendencias, riesgos y oportunidades de mejora en la gestión financiera.

---

## 📌 Objetivos

- Identificar estacionalidades en la ocurrencia de fraudes por canal financiero
- Calcular indicadores clave: total de reclamos, montos involucrados, clientes afectados
- Visualizar ratios como monto promedio por reclamo y reclamos por cliente
- Proponer próximos pasos para modelado predictivo

---

## 📊 Dataset

Formato: Excel  
Fuente: [Usuario privado]  
Estructura: Reclamos únicos, montos y clientes por canal (tarjetas de crédito, débito, TPPF, transferencias, cajeros y otros)  
Frecuencia: Mensual (24 períodos entre 2023–2024)

---

## ⚙️ Tecnologías

- Python (pandas, seaborn, matplotlib)
- Jupyter Notebook
- GitHub para versionado y portafolio

---

## 📈 Visualizaciones incluidas

- Evolución mensual de reclamos totales (`evolucion_reclamos.png`)
- Evolución mensual de montos reclamados (`monto_total.png`)
- Evolución de clientes únicos (`clientes_unicos.png`)
- Ratio de reclamos por cliente (`ratio_reclamos_cliente.png`)
- Monto promedio por reclamo (`ratio_monto_promedio.png`)

Los puntos máximos están anotados automáticamente para facilitar el análisis ejecutivo.

---

## 🧠 Conclusiones

- 📈 Los reclamos muestran picos estacionales hacia fin de año, especialmente en octubre y diciembre
- 💸 Transferencias electrónicas concentran el mayor monto de fraude por evento
- 👥 Ratios mensuales revelan que ciertos períodos tienen alta severidad por cliente
- ✅ La estructura permite escalar el análisis a modelos predictivos o dashboards interactivos

---

## 🚀 Próximos pasos

- Modelado con XGBoost o Random Forest para predecir meses de mayor riesgo, permitiendo alertas tempranas o segmentación proactiva de clientes.
- Visualización comparativa por canal mediante gráficos apilados, para dimensionar el impacto por tipo de transacción.
- Integración con benchmarks bancarios, estadísticas regulatorias o datos externos para contextualizar la severidad del fraude.
- Posibilidad de implementar detección de anomalías o clustering de meses atípicos mediante algoritmos no supervisados.


## 🧠 Autor
Proyecto desarrollado por Iván Pino Z. como parte de su portafolio en análisis de riesgo, inteligencia financiera y data science aplicado.
