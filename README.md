# Acerca de mí

Soy **Ingeniero Electrónico** con formación complementaria como **Data Scientist**, comprometido con transformar datos en decisiones estratégicas y soluciones tecnológicas de alto impacto. Combino una sólida base técnica en hardware con habilidades analíticas para desarrollar sistemas inteligentes, automatizados y eficientes.

Mi perfil destaca por la capacidad de identificar oportunidades de mejora, optimizar procesos y generar valor mediante el uso de datos, tanto en entornos operativos como de negocio. He liderado y colaborado en proyectos donde la analítica, la automatización y la innovación tecnológica han sido clave para lograr resultados tangibles.

Con una mentalidad autodidacta y enfoque orientado a resultados, ofrezco soluciones efectivas y escalables que impulsan la eficiencia, la calidad y la toma de decisiones basadas en datos.

## 🛠️ Habilidades tecnológicas

- Programación y análisis con **Python**: `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`
- Manejo y consulta de datos con **SQL**
- Visualización de datos con **Tableau** y **Power BI**
- Automatización y control mediante **microcontroladores, sensores e interfaces electrónicas**
- Uso de plataformas como **Jupyter**, **GitHub**, **Camstar** y **ServiceNow**

## 💡 Habilidades blandas

Pensamiento analítico | Adaptabilidad técnica | Resolución de problemas  
Comunicación efectiva | Colaboración interdisciplinaria | Enfoque autodidacta  
Atención al detalle | Mejora continua

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/marielalegoma/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-raya-tapia-81a736210/)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-295F98?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:Rafaeltap2019@hotmail.com)

* * *
# 📊Proyectos seleccionados

## Predicción de Cancelación de Clientes — Interconnect Telecom

En el sector de telecomunicaciones, anticipar la pérdida de clientes permite reducir el churn, personalizar estrategias de retención y mejorar el valor de vida del cliente. Este proyecto se centra en **predecir qué usuarios tienen mayor probabilidad de cancelar su servicio**, apoyando al área de marketing con decisiones basadas en datos.

#### 🛠️Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![EDA](https://img.shields.io/badge/Análisis_Exploratorio-295F98?style=for-the-badge)
![Balanceo de clases](https://img.shields.io/badge/Balanceo_de_clases-295F98?style=for-the-badge)
![Modelado predictivo](https://img.shields.io/badge/Modelado_predictivo-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Qué variables afectan más la cancelación de clientes?
2. ¿Cuál es la probabilidad de que un cliente abandone el servicio?
3. ¿Qué perfiles presentan mayor riesgo de churn?

### Metodología

- **Integración y limpieza de datos:** Se consolidaron 4 fuentes de datos (`contract.csv`, `internet.csv`, `phone.csv`, `personal.csv`), tratando valores faltantes y estandarizando variables categóricas.
- **Exploratory Data Analysis (EDA):** Se identificaron patrones como el impacto de contratos mensuales y métodos de pago electrónicos en la cancelación.
- **Balanceo de clases:** Se aplicó upsampling con técnicas de remuestreo para equilibrar la clase objetivo (cancelación vs no cancelación).
- **Modelado predictivo:** Se entrenó un modelo con LightGBM, logrando un AUC-ROC de `0.805`.
- **Interpretabilidad:** Se analizaron las variables más relevantes para comprender las razones detrás de las predicciones.

### ✅Conclusiones y recomendaciones

#### Factores clave del churn:
- **Contratos mensuales** presentan mayor riesgo de abandono.
- **Método de pago "Electronic Check"** asociado con mayor tasa de cancelación.
- **Falta de servicios adicionales** como soporte técnico, seguridad o streaming, correlaciona con clientes que abandonan.

#### Estrategias recomendadas:
- **Campañas de fidelización personalizadas** para clientes en riesgo.
- **Promociones en servicios adicionales** como soporte o antivirus para aumentar el compromiso.
- **Incentivos para contratos anuales o bianuales**, especialmente para usuarios nuevos.
- **Segmentación automatizada de clientes**, integrando el modelo predictivo en procesos de CRM.

### Visualizaciones destacadas
Gráficas de dispersión, histogramas, matriz de correlación, curvas ROC, importancia de características y comparación de modelos de clasificación.


## Predicción de Demanda de Taxis — Sweet Lift Taxi

En el competitivo sector del transporte urbano, anticiparse a los picos de demanda es clave para **mejorar la eficiencia operativa**, **incrementar los ingresos** y **optimizar la experiencia del cliente**. En este proyecto, desarrollé un modelo de predicción horaria de pedidos de taxi con el objetivo de **anticipar la demanda en aeropuertos** y así facilitar la asignación eficiente de unidades durante las horas pico.

#### 🛠️Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-357ebd?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-357ebd?style=for-the-badge&logo=matplotlib&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Statsmodels](https://img.shields.io/badge/statsmodels-295F98?style=for-the-badge)
![Series Temporales](https://img.shields.io/badge/Series_temporales-295F98?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-295F98?style=for-the-badge)
![RMSE](https://img.shields.io/badge/Métrica_RMSE-295F98?style=for-the-badge)

### Objetivo
Construir un modelo de predicción que anticipe la **cantidad de pedidos de taxi por hora**, permitiendo a la empresa tomar decisiones proactivas y estratégicas de operación logística.

### Metodología

- **Preprocesamiento y remuestreo temporal:** Los datos fueron resampleados a una frecuencia de 1 hora para capturar la estacionalidad y patrones horarios.
- **EDA y descomposición estacional:** Se aplicó `seasonal_decompose` para visualizar tendencias, ciclos y residuos en la serie temporal.
- **Ingeniería de características:** Se incorporaron variables como "hora del día", "día de la semana" y estadísticas móviles para enriquecer la información temporal.
- **Modelado predictivo:** Se utilizó **LightGBM** por su eficiencia y rendimiento sobre datos tabulares. Se entrenaron modelos ajustando hiperparámetros y evaluando su desempeño con la métrica RMSE.
- **Validación temporal:** Se dividió el dataset en conjuntos de entrenamiento, validación y prueba, respetando la estructura secuencial de las series temporales.

### Resultados y beneficios

El modelo logró una excelente capacidad de predicción en el conjunto de entrenamiento, con un RMSE de **19.27**, mientras que en la etapa de validación se obtuvo un RMSE de **34.66**. En el conjunto final de prueba, el RMSE fue de **54.91**, manteniéndose dentro de un margen razonable para aplicaciones prácticas.

El tiempo total de ejecución fue de **0.10 segundos**, demostrando que el modelo no solo es preciso, sino también altamente eficiente.

> Esta solución permite prever con anticipación la demanda horaria de taxis en aeropuertos, optimizando la **asignación de unidades**, reduciendo los **tiempos de espera** y mejorando la **experiencia del usuario y la eficiencia operativa**.

### Visualizaciones destacadas
Gráficas de dispersión, histogramas, matriz de correlación, curvas ROC, importancia de características y comparación de modelos de clasificación.


## 🎮 Predicción de Éxito de Videojuegos — Ice Store

### 🧩 Descripción
Proyecto desarrollado para la tienda online **Ice**, especializada en la venta global de videojuegos. Se realizó un análisis completo para **identificar patrones que predicen si un videojuego será exitoso o no**, utilizando datos abiertos de ventas, géneros, plataformas, reseñas de usuarios y expertos.

Este análisis permitió **detectar proyectos con alto potencial comercial y optimizar campañas publicitarias** orientadas al año 2017, mejorando así la toma de decisiones en planeación de lanzamientos.

---

#### 🛠️ Herramientas y tecnologías

![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/pandas-130754?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)  
![Seaborn](https://img.shields.io/badge/seaborn-3b4cc0?style=for-the-badge&logo=python&logoColor=white)  
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)  
![Jupyter](https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📊 Análisis y procesamiento de datos

- Limpieza y transformación del dataset, estandarizando tipos de datos y manejando valores ausentes, incluyendo casos como `TBD`.
- Generación de una nueva variable de **ventas globales** (suma de ventas por región: NA, EU, JP y otras).
- Análisis de más de 16 años de datos para detectar tendencias clave por género, plataforma y clasificación ESRB.

---

## 📈 Insights clave

- **PS4 y XOne** dominaban el mercado en 2016, mientras plataformas como **PS2** presentaban un claro declive.
- Los géneros más rentables fueron **Acción**, **Deportes** y **Disparos**, mientras que géneros como **Aventura** tuvieron menores ventas.
- La clasificación **ESRB** tuvo impacto variable según la región, siendo más influyente en **Norteamérica**.

---

## 🔬 Evaluación estadística

- Análisis de correlaciones entre reseñas (usuarios y críticos) y ventas: las reseñas positivas impactan de forma moderada en las ventas.
- Se probaron hipótesis estadísticas para evaluar:
  - Diferencias entre calificaciones de usuarios en **PC vs Xbox One**.
  - Diferencias entre géneros **Acción vs Deportes**.
- Se utilizó una **prueba t de Student** con nivel de significancia definido por el análisis.

---

## ✅ Resultados y aplicación

- Se construyó un perfil de usuario por región (**NA, EU, JP**) basado en plataformas favoritas, géneros más vendidos y sensibilidad a la clasificación ESRB.
- Los hallazgos pueden utilizarse en estrategias de **desarrollo, distribución y promoción de videojuegos**, mejorando la segmentación y maximizando el ROI.

### Visualizaciones destacadas
Gráficas de dispersión, histogramas, matriz de correlación, curvas ROC, importancia de características y comparación de modelos de clasificación.
