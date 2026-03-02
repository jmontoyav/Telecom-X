# **📊 Análisis de Evasión de Clientes (Churn) - TelecomX**
Este proyecto realiza un diagnóstico profundo sobre la retención de clientes para la empresa Telecom X, utilizando técnicas de análisis exploratorio de datos e ingeniería de características para identificar por qué el 26.5% de los usuarios abandona el servicio.
# **🎯 Objetivo del Proyecto**
Este estudio tiene como objetivo realizar un diagnóstico profundo sobre el comportamiento de los clientes de Telecom X para responder las siguientes preguntas:
1.   ¿Cuál es la magnitud real del abandono?
2.   ¿Quiénes son los clientes con mayor riesgo?
3.   ¿Qué factores financieros y temporales disparan la fuga de clientes?
# **🛠️ Stack Tecnológico**
<ul>
  <li><strong>Lenguaje:</strong> Python 3.x</li>
  <li><strong>Entorno:</strong> Google Colab / Jupyter Notebooks</li>
  <li><strong>Librerías Principales:</strong></li>
  <ul>
    <li><strong>Pandas:</strong> Procesamiento y limpieza de datos anidados (JSON).</li>
    <li><strong>Matplotlib & Seaborn:</strong> Visualización avanzada y estilizada (Paleta Pastel).</li>
    <li><strong>NumPy:</strong> Cálculos estadísticos.</li>
    <li><strong>Scipy:</strong> Pruebas de varianza (Levene).</li>
  </ul>
</ul>

# **🚀 Ingeniería de Datos y Limpieza**
<ol>
  <li><strong>Flattening:</strong> Transformación de estructuras JSON complejas a DataFrames planos.</li>
  <li><strong>Estandarización:</strong> Normalización de encabezados (snake_case) y tipos de datos.</li>
  <li><strong>Codificación Binaria:</strong> Transformación de variables categóricas a valores numéricos (0 y 1) para análisis estadístico.</li>
  <li><strong>Nuevas Métricas (Feature Engineering):</strong></li>
  <ul>
    <li><strong>Cuentas_Diarias:</strong> Normalización del costo del servicio por día.</li>
    <li><strong>Cant_Servicios:</strong> Cuantificación del ecosistema de productos contratados.</li>
  </ul>
</ol>

# **📈 Hallazgos Clave (Insights)**
<ul>
  <li>El riesgo de fuga es máximo en los primeros 12 meses.</li>
  <li>Los clientes que abandonan tienen una antigüedad promedio de 17.98 meses, mientras que los leales superan los 37.57 meses.</li>
  <li>Existe un umbral de dolor financiero; los clientes con mayor costo diario tienden a la evasión, independientemente de la cantidad de servicios adicionales.</li>
  <li>Contratos mes a mes, tecnología de fibra óptica y pagos por cheque electrónico son los principales predictores de fuga.</li>
</ul>

# **📋 Estructura del Informe**
<ol>
  <li>Introducción</li>
  <li>Objetivo</li>
  <li>Limpieza y Tratamiento de Datos</li>
  <li>Análisis Exploratorio de Datos</li>
  <li>Conclusiones e Insights</li>
  <li>Recomendaciones</li>
</ol>

# **🛠️ Cómo ejecutar el proyecto**
<ol>
  <li>Clona este repositorio.</li>
  <li>Sube el archivo .ipynb a Google Colab.</li>
  <li>Ejecuta todas las celdas para visualizar las funciones de diagnóstico y el informe final.</li>
</ol>

# **👨‍💻 Autor**
Jose Luis Montoya Vargas
