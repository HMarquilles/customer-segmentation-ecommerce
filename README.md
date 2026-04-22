# 🚀 Customer Segmentation in E-commerce

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

---

Este proyecto presenta un **análisis de segmentación de clientes en ecommerce** a partir de variables agregadas de comportamiento, valor y sensibilidad al precio.

El objetivo no es construir modelos complejos, sino **identificar tipologías de clientes** y extraer conclusiones accionables desde un punto de vista de negocio.

---

## 📌 Enfoque del análisis

Cada fila del dataset representa **un cliente**, descrito mediante métricas agregadas como:

- Valor total gastado  
- Frecuencia y recencia de compra  
- Uso de promociones  
- Variabilidad de precios  
- Composición de la cesta  
- Preferencia de entrega  
- Ratio de devoluciones  

A partir de estas variables, el análisis sigue un enfoque estructurado que incluye:

- Preparación y normalización de los datos  
- Reducción de dimensionalidad mediante PCA  
- Segmentación de clientes mediante clustering  
- Perfilado e interpretación de cada grupo  

---

## 📂 Estructura del repositorio

```
customer-segmentation-ecommerce
│
├── data
│   └── customers.csv
├── notebooks
│   └── customer_segmentation.ipynb
├── README.md
└── LICENSE
```

---

## 🧪 Dataset

El dataset es **simulado**, pero diseñado para reflejar patrones realistas de comportamiento en ecommerce.

Incluye variables relacionadas con:
- Valor y frecuencia de compra  
- Sensibilidad al precio y a promociones  
- Composición de la cesta  
- Tipo de servicio (express, entrega)  
- Fricción operativa (devoluciones)  

Este enfoque permite analizar no solo el valor económico del cliente, sino también su impacto operativo.

---

## 📊 Análisis

El notebook principal desarrolla los siguientes pasos:

1. Carga y comprensión del dataset  
2. Exploración inicial del comportamiento de los clientes  
3. Preparación y escalado de las variables  
4. Reducción de dimensionalidad mediante PCA  
5. Segmentación de clientes con KMeans  
6. Perfilado e interpretación de los clusters  
7. Conclusiones orientadas a negocio  

---

## 🚀 Objetivo del repositorio

Este repositorio está pensado como:

- Ejemplo divulgativo de segmentación de clientes  
- Punto de partida para análisis de comportamiento en ecommerce  
- Base para conversaciones entre datos y negocio  

---

## 🛠️ Requisitos

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## 📎 Nota final

El foco del proyecto está en **la interpretación y el razonamiento**, priorizando la comprensión del comportamiento del cliente sobre la complejidad técnica del modelo.

## 📄 License

This project is licensed under the MIT License
