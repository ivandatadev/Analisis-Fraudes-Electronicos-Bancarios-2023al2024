# 🔐 Análisis de Reclamos por Fraudes Electrónicos Bancarios

Este proyecto analiza datos mensuales de reclamos únicos, montos involucrados y clientes afectados por fraudes electrónicos en distintos canales financieros. El objetivo es generar métricas ejecutivas y visualizaciones que revelen tendencias, riesgos y oportunidades para la banca chilena durante 2023 y 2024.

---

## 📌 Objetivos

- Identificar estacionalidades y picos de riesgo
- Calcular indicadores clave para visualización ejecutiva
- Explorar ratios como monto promedio por reclamo y reclamos por cliente
- Proponer próximos pasos hacia modelado predictivo

---

## 📊 Dataset

- Formato: Excel
- Estructura: Reclamos, montos y clientes por canal
- Periodo: 24 meses (2023–2024)
- Fuente: [Privada]

---

## ⚙️ Tecnologías

- Python: `pandas`, `matplotlib`, `seaborn`
- Jupyter Notebook
- GitHub para documentación y visibilidad

---

## 📈 Visualizaciones incluidas

| Indicador                             | Archivo PNG                            |
|--------------------------------------|----------------------------------------|
| Evolución mensual de reclamos        | `output/graficos/evolucion_reclamos.png` |
| Monto total reclamado                | `output/graficos/monto_total.png`        |
| Clientes afectados mensualmente      | `output/graficos/clientes_unicos.png`    |
| Monto promedio por reclamo           | `output/graficos/ratio_monto_promedio.png` |
| Ratio de reclamos por cliente        | `output/graficos/ratio_reclamos_cliente.png` |

Cada gráfico incluye la anotación automática del punto más alto para facilitar el análisis gerencial.

---

## 🧠 Conclusiones analíticas

- 📈 Octubre y diciembre muestran picos críticos de fraude, posibles meses de alta vulnerabilidad operativa
- 💸 Las transferencias electrónicas concentran los montos más altos por evento
- 👥 En 2024, los ratios superan el promedio histórico, revelando mayor severidad por cliente afectado

---

## 🚀 Próximos pasos

- Modelado con XGBoost o Random Forest para predecir meses de mayor riesgo
- Visualización comparativa por canal mediante gráficos apilados
- Integración con benchmarks bancarios y datos regulatorios
- Implementación de detección de anomalías y clustering de meses atípicos

---

## 📂 Estructura del proyecto

```text
fraudes-electronicos-bancarios/
├── data/
│   └── base_reclamos.xlsx
├── notebooks/
│   └── análisis_fraudes.ipynb
├── output/
│   └── graficos/
│       └── *.png
├── README.md
├── requirements.txt


## 🧠 Autor
Proyecto desarrollado por Iván Pino Z. como parte de su portafolio en análisis de riesgo, inteligencia financiera y data science aplicado.
