# ChallengeTelecom X
# Análisis de Evasión de Clientes (Churn) - TelecomX

## Introducción
Este proyecto forma parte del Challenge de Data Science LATAM. El objetivo es analizar el comportamiento de los clientes de TelecomX y comprender los factores que influyen en la evasión (Churn). La evasión de clientes es un problema crítico para las empresas de telecomunicaciones, ya que impacta directamente en los ingresos y la sostenibilidad del negocio.

## Dataset
El dataset utilizado proviene del archivo JSON:
[TelecomX_Data.json](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json)

Contiene información sobre:
- Datos del cliente (`customerID`, `gender`, `SeniorCitizen`, etc.)
- Servicios contratados (`PhoneService`, `InternetService`, `StreamingTV`, etc.)
- Información de cuenta (`Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`, `Tenure`)
- Variable objetivo: **`Churn`** (Sí/No)

## Limpieza y Tratamiento de Datos
- Normalización de estructuras anidadas (customer, phone, internet, account).
- Verificación y corrección de valores ausentes, duplicados y errores de formato.
- Homogeneización de categorías mediante manipulación de strings.

## Análisis Exploratorio de Datos
- **Descriptivo:** cálculo de métricas como media, mediana y desviación estándar.
- **Distribución de Churn:** visualización de la proporción de clientes que permanecieron vs. los que cancelaron.
- **Variables categóricas:** análisis de género, tipo de contrato y método de pago en relación con Churn.

## Tecnologías Utilizadas
- Python 3
- Pandas
- Seaborn
- Matplotlib
- Google Colab

---
Este repositorio contiene el notebook con todo el flujo de trabajo: importación, limpieza, análisis exploratorio, conclusiones y recomendaciones estratégicas.
# ChallengeTelecomX-Pt2
# ChallengeTelecomX-Pt2
