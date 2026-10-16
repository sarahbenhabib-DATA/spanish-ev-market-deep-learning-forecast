# spanish-ev-market-deep-learning-forecast
Impact EV: Análisis Predictivo y Deep Learning (2025-2028) del mercado de vehículos eléctricos en España. Modelado LSTM en TensorFlow, limpieza con Isolation Forest y análisis de impacto macroeconómico (inflación y combustible).
# ⚡ El vehículo eléctrico en España : ¿Choix écologique ou stratégie de survie financière ?

> **Impact EV : Analyse Prédictive Deep Learning 2025-2028 | Marché Automobile Espagnol**

Ante una coyuntura macroeconómica bajo alta tensión (inflación al 4,5 %, gasolina superando la barrera psicológica de los 2,05 €/L y Euríbor al 3,90 %), este proyecto analiza si el vehículo eléctrico se ha convertido en el mejor escudo financiero para el consumidor en España.

---

## Pipeline de Data Science y Stack Tecnológico
- **Data Pipeline & Mining :** Estructuración de datos temporales tridimensionales (secuencias `(12, 3, 3)`) y depuración de anomalías de producción (como el pico de 211K unidades en marzo de 2026) mediante **Isolation Forest** y **Z-Score**.
- **Modelización Predictiva :** Entrenamiento de una red neuronal recurrente **LSTM** (**TensorFlow / Keras**) con capa *Dropout* (0,2) para anticipar dinámicas no lineales del mercado (¡logrando un **MAPE < 8 %**!).
- **Stack :** `Python`, `TensorFlow`, `Keras`, `Qlik`, `Scikit-Learn`.

---

##  Business Insights y Resultados Clave
- **Elasticidad-precio de ~1 :** 1 % de subida en el precio de la gasolina genera un 1 % de incremento en las ventas de VE.
- **Proyección de mercado :** Se prevé alcanzar las 450 000 unidades comercializadas de aquí a 2028, con los fabricantes chinos (BYD/MG) capturando el 65 % de esta nueva demanda.
- **El Paradoja de la Batería :** Aunque la degradación real de la salud de la batería (*SoH*) es de solo un -1,8 % anual, la ansiedad psicológica de los compradores frena todavía el potencial teórico del mercado en un -25 %.

---

## Recomendaciones Estratégicas
- Focalización geográfica en hubs clave (Madrid y Barcelona).
- Implementación de alertas comerciales basadas en las fluctuaciones del Euríbor.

---

## Estructura del Repositorio
├── data/             # Datasets limpios y anonimizados
├── notebooks/        # Notebooks de Python (EDA, Limpieza y Modelado LSTM)
├── models/           # Modelos de Deep Learning entrenados (.h5)
└── README.md
