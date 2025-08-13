# 📊 | Challenge Telecom X: análisis de evasión de clientes

Este proyecto corresponde al desafío de análisis de datos propuesto en el curso de Alura LATAM y Oracle ONE.  
El objetivo fue identificar patrones y factores asociados a la evasión (churn) de clientes en una compañía de telecomunicaciones, utilizando métricas y visualizaciones que permitan fundamentar estrategias de retención.

---

## 📌 | Objetivo principal
Analizar el comportamiento de los clientes para:
- Determinar los principales factores que influyen en la cancelación del servicio.
- Explorar la relación entre variables demográficas, contractuales y de uso con la evasión.
- Proveer información para estrategias de retención más efectivas.

---

## 🧪 | Tecnologías y herramientas usadas
- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab** (entorno de desarrollo)
- **GitHub** (control de versiones y publicación)

---

## 📷 | Visualizaciones generadas
Se crearon múltiples gráficos con breves descripciones explicativas:

1. **Gráfico de barras: Distribución de evasión por tipo de contrato**  
   Compara la tasa de cancelación entre clientes con contrato mensual, anual o bianual.

2. **Gráfico de barras horizontales: Tasa de evasión por tipo de servicio de internet**  
   Muestra qué tipo de conexión (Fibra óptica, DSL, ninguno) presenta mayor proporción de cancelaciones.

3. **Gráfico de barras agrupadas: Relación entre método de pago y evasión**  
   Visualiza cómo varía la tasa de cancelación según el método de pago elegido.

4. **Gráfico de pastel: Proporción de clientes que permanecen vs. que cancelan**  
   Representa de forma porcentual la distribución entre clientes activos y cancelados.

5. **Mapa de calor (heatmap): Correlación entre variables numéricas y evasión**  
   Permite identificar qué variables numéricas (tenure, monthly charges, total charges) tienen mayor relación con la cancelación.

Entre otros vistos en el archivo.

---

## 📄 | Informe de resultados
El análisis permitió identificar que:
- Los contratos mensuales presentan una tasa de evasión significativamente más alta que los contratos de mayor duración.
- Los clientes con servicio de fibra óptica registran más cancelaciones que quienes tienen DSL o no poseen internet.
- Determinados métodos de pago, especialmente los automáticos con tarjeta de crédito, presentan menor tasa de evasión.
- Existe una correlación negativa entre la antigüedad del cliente (*tenure*) y la probabilidad de cancelación.
  
El informe detallado con todos los hallazgos y conclusiones se encuentra incluido dentro del proyecto.

---

## 📝 | Cómo ejecutar
Clona este repositorio:

```bash
git clone https://github.com/RamsRD/desafio-alura-telecom-x-1
