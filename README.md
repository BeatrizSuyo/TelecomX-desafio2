
# 📡 Telecom X – Predicción de Cancelación (Churn)

Este proyecto forma parte del desafío de **Data Science – Parte 2**, cuyo objetivo es desarrollar un modelo predictivo para identificar clientes con alta probabilidad de cancelar su servicio (*churn*).

## 🎯 Objetivos
- Preparar y procesar los datos para Machine Learning.
- Realizar análisis de correlación y selección de variables.
- Entrenar múltiples modelos de clasificación.
- Evaluar y comparar el rendimiento de los modelos.
- Interpretar los resultados y proponer estrategias de retención.

## 📂 Contenido del repositorio
- `telecom_churn_model.ipynb` → Notebook con todo el flujo: carga de datos, preprocesamiento, modelado y análisis.
- `data/` → Carpeta de datos (si aplica).
- `README.md` → Este archivo.

## 🛠️ Tecnologías y librerías utilizadas
- **Python 3**
- **Pandas**, **NumPy** → Manejo y procesamiento de datos
- **Matplotlib**, **Seaborn** → Visualización
- **Scikit-learn** → Modelado y métricas
- **XGBoost** (opcional según implementación)

## 📊 Resumen de Hallazgos Clave
- **Factores más influyentes**: Monto total facturado, tiempo de permanencia y tarifa mensual.
- **Mayor riesgo de cancelación**: Clientes con contratos mensuales y pago por cheque electrónico.
- **Protecciones asociadas a menor churn**: Seguridad en línea, soporte técnico y protección de dispositivos.
- **Segmento prioritario para retención**: Clientes nuevos con fibra óptica y contratos flexibles.

## 💡 Estrategias sugeridas
1. Migrar clientes con contrato mes a mes hacia contratos anuales mediante incentivos.
2. Ofrecer descuentos o paquetes a clientes con alta factura mensual.
3. Promover servicios de seguridad online, soporte técnico y protección de dispositivos.
4. Monitorear de cerca a clientes nuevos para mejorar su experiencia inicial.

## 📈 Métricas de desempeño
- **Modelos entrenados**: Random Forest, Logistic Regression (pueden variar según implementación).
- **Evaluaciones**: Accuracy, Precision, Recall, F1-score, Matriz de confusión.
- **Modelo ganador**: (Especificar aquí el que haya tenido mejor desempeño).

## 🏁 Conclusión
El modelo desarrollado permite identificar con anticipación clientes en riesgo de churn, facilitando la implementación de estrategias proactivas de retención y optimizando los recursos de la empresa.

---
✍️ *Proyecto desarrollado por Beatriz como parte del Challenge de Data Science LATAM – Alura*
