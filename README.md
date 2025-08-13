# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto analiza la evasión de clientes (*churn*) en Telecom X con el objetivo de identificar patrones y factores asociados a la pérdida de usuarios. El trabajo incluye limpieza de datos, análisis exploratorio (EDA), visualizaciones y recomendaciones estratégicas.

---

## 📌 Objetivo
Entender qué variables influyen en la cancelación de clientes y proporcionar insights para desarrollar estrategias de retención efectivas.

---

## 🛠️ Instalación y configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/usuario/telecomx-churn.git
cd telecomx-churn

---

## 📂 Contenido del proyecto
- **`URL:'https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json`** → Con información de clientes.
- **`TelecomX_LATAM.ipynb`** → Proceso completo de ETL, EDA y generación de insights.
- **Visualizaciones** → Gráficos comparativos por:
  - Género
  - Tipo de contrato
  - Método de pago
  - Tipo de servicio de internet
  - Servicio telefónico
  - Variables numéricas (meses de contrato, cuentas totales, cuentas mensuales y diarias)

---
## 🛠️ Proceso de análisis

### 1. Limpieza y tratamiento de datos
- Importación de datos desde la API TelecomX
- Integración de estructuras anidadas del JSON en un único DataFrame.
- Comprobacion de inconsitencias en los datos.
- Conversión a tipos numéricos de variables clave.
- Creación de variables derivadas como `cuentas_diarias`.

---

### 2. Análisis exploratorio (EDA)
- **Distribución general del churn**: proporción de clientes que cancelaron vs los que permanecen.
- **Segmentación por variables categóricas**:
  - Género
  - Tipo de contrato
  - Método de pago
  - Tipo de internet
  - Servicio telefónico
- **Variables numéricas**:
  - Meses de contrato (`meses_contrato`)
  - Gasto total (`cuentas_totales`)
  - Gasto mensual (`cuentas_mensuales`)
  - Gasto diario (`cuentas_diarias`)
- Uso de histogramas, boxplots y violin plots para identificar patrones.

---

## 📈 Conclusiones
1. **Churn significativo**: existe un volumen importante de cancelaciones.
2. **Contratos mensuales**: concentran la mayor tasa de evasión.
3. **Método de pago**: *electronic check* se asocia con mayor churn que pagos automáticos.
4. **Tipo de internet**: la tecnología influye en la retención.
5. **Servicio telefónico**: posible relación con satisfacción y retención.
6. **Cancelación temprana**: clientes que se van suelen tener pocos meses de contrato.
7. **Relación con gasto**: cancelados tienen menor gasto total y en algunos casos gasto mensual/diario más alto.

---

## 💡 Recomendaciones
- **Onboarding y retención temprana**: programas de fidelización en los primeros 3–6 meses.
- **Incentivar contratos anuales**: descuentos o beneficios para migrar desde contratos mensuales.
- **Optimizar métodos de pago**: incentivar pagos automáticos.
- **Revisar calidad/precio del internet**: ajustar oferta en segmentos con alta cancelación.
- **Analizar el servicio telefónico**: mejorar valor percibido o precio.
- **Monitorear segmentos sensibles al precio**: ofrecer planes flexibles o descuentos preventivos.

---

## 🚀 Próximos pasos
- Implementar un modelo predictivo de churn para priorizar acciones de retención.
- Integrar variables externas como quejas y uso de servicio para mejorar la precisión del análisis.
- Automatizar reportes mensuales de métricas clave.

---

## 🖥️ Tecnologías utilizadas
- **Python** (pandas, numpy)
- **Visualización**: plotly, matplotlib
- **EDA**: análisis estadístico y segmentación
- **Jupyter Notebook** para documentación del proceso

---

## 📄 Licencia
Este proyecto se publica con fines educativos y de análisis interno para Telecom X.

---

##
