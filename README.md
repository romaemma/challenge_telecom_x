
📊 Análisis de Retención de Clientes: Proyecto TelecomX
Este proyecto consiste en un pipeline completo de Data Science que abarca desde la extracción de datos en formato JSON
hasta el análisis exploratorio (EDA) y la generación de insights estratégicos para reducir la tasa de abandono (Churn)
en una empresa de telecomunicaciones.

🚀 Estructura del Proyecto
El flujo de trabajo se divide en tres etapas principales:

Extracción y Limpieza: Consumo de API/JSON y normalización.

Transformación (ETL): Traducción de variables, manejo de nulos y tipado de datos.

Análisis Visual: Identificación de patrones mediante gráficos estadísticos.

🛠️ Stack Tecnológico
Python 3.x

Pandas: Manipulación y limpieza de datos.

Matplotlib / Plotly: Visualización interactiva y estática.

Requests: Obtención de datos vía HTTP.

🔧 Transformación de Datos (ETL)
El dataset original presentaba una estructura anidada que fue procesada para facilitar su análisis:

Normalización: Se utilizó json_normalize para convertir objetos anidados (customer, phone, account) en columnas individuales.

Tratamiento de Críticos: * Se eliminaron 224 registros con valores vacíos en la columna Churn.

Se convirtieron los Total Charges a tipo numérico, eliminando registros nulos resultantes.

Localización: Se tradujeron todas las categorías y nombres de columnas al español para mejorar la interpretabilidad del informe final.

📈 Hallazgos Principales (EDA)
Tras el análisis visual, se determinaron los siguientes puntos clave:

1. Perfil de Riesgo
Tipo de Contrato: Los clientes con contrato mes a mes tienen la tasa de deserción más alta.

Método de Pago: El uso de Cheque Electrónico está fuertemente correlacionado con el abandono.

Servicios: Los clientes que NO contratan Soporte Técnico o Seguridad Online tienden a irse con mayor frecuencia.

2. Factores de Retención
Antigüedad: A mayor tiempo_contrato, la probabilidad de Churn disminuye drásticamente.

Fidelidad: Los contratos anuales y bienales muestran una estabilidad superior al 90%.

📄 Informe Final y Estrategia
Estado Actual: Tasa de Churn del 26.1%.

Recomendaciones Estratégicas:
Migración de Contratos: Crear campañas de descuento para convertir clientes mensuales a contratos anuales.

Bundling de Servicios: Empaquetar el servicio de Internet con Soporte Técnico para aumentar la "barrera de salida".

Focalización: Diseñar programas de lealtad específicos para el segmento de Ciudadanos Mayores (Seniors).
