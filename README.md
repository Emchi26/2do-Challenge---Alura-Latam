# 2do-Challenge---Alura-Latam
Análisis de Evasión de Clientes (Churn) en TelecomX
Este proyecto tiene como objetivo analizar la evasión de clientes (churn) en TelecomX para identificar los factores clave que contribuyen a la pérdida de clientes y proponer estrategias efectivas para la retención.

Fuente de Datos
Los datos utilizados para este análisis fueron obtenidos de un archivo JSON alojado en la siguiente URL:

https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json

Metodología
El análisis se llevó a cabo siguiendo un proceso estructurado que incluyó las siguientes etapas principales:

Extracción de Datos: Los datos iniciales fueron obtenidos de una fuente JSON.
Limpieza y Tratamiento de Datos: Se realizó un proceso exhaustivo para manejar inconsistencias en los datos, incluyendo la normalización de estructuras anidadas, la estandarización de formatos (como el uso de minúsculas y el manejo de valores faltantes), y la corrección de entradas inconsistentes en columnas categóricas.
Transformación de Datos: Se crearon nuevas características relevantes para el análisis, como el cálculo de la facturación diaria. Además, se estandarizaron valores categóricos binarios a formato numérico (0 y 1) para facilitar análisis posteriores.
Análisis Exploratorio de Datos: Se realizó un análisis descriptivo para entender la distribución de las variables clave. Posteriormente, se exploró la relación entre la variable objetivo (Churn) y otras variables categóricas y numéricas mediante visualizaciones (gráficos de barras, boxplots e histogramas) para identificar patrones y tendencias significativas.

Hallazgos Clave
El análisis exploratorio de datos reveló varios factores clave asociados con la evasión de clientes en TelecomX:

Tipo de Contrato: Los clientes con contratos mes a mes muestran una tasa de evasión significativamente mayor en comparación con aquellos con contratos a largo plazo (uno o dos años).
Método de Pago: El método de pago de cheque electrónico está asociado con una mayor propensión a la evasión.
Servicio de Internet: Los clientes con servicio de fibra óptica presentan una tasa de evasión considerable.
Tiempo de Permanencia (Tenure): Los clientes con menor tiempo de permanencia en la empresa tienen una mayor probabilidad de darse de baja.
Cargos Mensuales/Diarios: Los clientes con cargos mensuales y diarios más altos tienden a tener una mayor tasa de evasión.
Estos hallazgos sugieren que la evasión es un fenómeno multifactorial influenciado por el tipo de compromiso del cliente, las preferencias de pago, el tipo de servicio de internet, la antigüedad como cliente y el costo percibido del servicio.

Recomendaciones
Basado en los hallazgos clave identificados en el análisis, se proponen las siguientes recomendaciones estratégicas para que TelecomX reduzca la evasión de clientes:

Incentivar Contratos a Largo Plazo: Ofrecer descuentos, beneficios exclusivos o promociones para motivar a los clientes a elegir contratos de uno o dos años sobre los contratos mes a mes.
Optimizar Métodos de Pago: Investigar las razones detrás de la alta tasa de evasión en clientes que usan cheque electrónico y explorar la implementación de métodos de pago alternativos más atractivos o la mejora de la comunicación sobre las ventajas de otros métodos.
Mejorar la Experiencia con Fibra Óptica: Analizar y abordar posibles problemas de calidad o estabilidad en el servicio de fibra óptica. Gestionar activamente las expectativas del cliente y fortalecer el soporte técnico para usuarios de fibra óptica.
Implementar Programas de Retención Temprana: Desarrollar estrategias de engagement y seguimiento proactivo durante los primeros meses de servicio, como programas de onboarding personalizados y ofertas especiales para clientes nuevos.
Revisar la Estructura de Precios: Evaluar la relación entre los cargos y la percepción de valor. Considerar planes más flexibles o transparentes, o explorar opciones para ajustar la estructura de precios para segmentos de clientes con mayor propensión a la evasión debido a los costos.
Segmentación para Campañas Dirigidas: Utilizar los datos para segmentar a los clientes en grupos de riesgo de evasión y diseñar campañas de retención personalizadas y dirigidas a cada segmento identificado.
Monitoreo Continuo: Establecer un sistema para monitorear continuamente los indicadores de evasión y realizar análisis periódicos para evaluar la efectividad de las estrategias de retención y adaptarse a nuevas tendencias.

Cómo Reproducir el Análisis
Para reproducir este análisis, puedes seguir los siguientes pasos:

Accede al notebook de Google Colab a través del siguiente enlace: https://colab.research.google.com/drive/1p_z_q3_p0Y5S7f7l0k9j1l2l8m8d8c8c?usp=drive_url
Una vez que el notebook esté abierto en Google Colab, puedes ejecutar cada celda de código secuencialmente. Esto cargará los datos, realizará la limpieza y transformación, y ejecutará el análisis exploratorio de datos, mostrando los resultados y visualizaciones generadas.
