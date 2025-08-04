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
