# ⚽ Análisis de Resultados Históricos de Fútbol (1872 - 2017)

Un proyecto de análisis de datos que explora la historia completa del fútbol internacional masculino desde sus inicios hasta 2017. Este análisis revela tendencias, equipos dominantes y estadísticas fascinantes derivadas de más de 40,000 partidos.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet?logo=matplotlib)
![Jupyter](https://img.shields.io/badge/Colab-Notebook-orange?logo=jupyter)
![Data Science](https://img.shields.io/badge/Data-Science-brightgreen)

## 📊 Descripción del Dataset

El proyecto utiliza el dataset ["Resultados de fútbol entre 1872 y 2017"](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017) de Kaggle, que contiene:

- **Fecha**: Fecha del partido
- **Equipos**: `home_team` (local) y `away_team` (visitante)
- **Resultados**: `home_score` y `away_score`
- **Torneo**: Tipo de competición (Amistoso, Mundial, Eurocopa, etc.)
- **Ciudad, País y Neutral**: Ubicación y condición del partido

## 🎯 Objetivos del Análisis

El análisis se centró en responder las siguientes preguntas:

1.  ¿Qué equipos han jugado más partidos como local y como visitante?
2.  ¿Qué equipos tienen el mayor número de partidos en total (local + visitante)?
3.  **¿Cuáles son los equipos con más victorias en la historia de la Copa del Mundo?**
4.  Visualización clara y efectiva de estos hallazgos.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje de programación**: Python 3
- **Librerías principales**:
  - `pandas` - Para manipulación y análisis de datos
  - `matplotlib` & `seaborn` - Para la creación de gráficos y visualizaciones
  - `numpy` - Para operaciones numéricas
- **Entorno**: Google Colab / Jupyter Notebook

## 📈 Hallazgos Clave (Key Insights)

### 1. Top 10 Equipos con Más Partidos Jugados (Local + Visitante)<img width="1490" height="790" alt="image" src="https://github.com/user-attachments/assets/f7ea6b38-b5c6-4cd8-afa1-a023257db416" />

![Total Matches](<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/3991fe6a-e6ce-494e-a924-1c15bed602d5" />
) <!-- Reemplaza con el link real a tu gráfico -->
Suecia, Inglaterra y Brasil lideran la tabla histórica de partidos jugados.

### 2. Los Reyes como Local
Brasil, Argentina y México son los equipos que más partidos han jugado en condición de local.

### 3. Máximos Ganadores en Copas del Mundo
![World Cup Wins](![Uploading image.png…]()
) <!-- Reemplaza con el link real a tu gráfico -->
El análisis confirma el dominio histórico de **Brasil (73 victorias)**, seguido por **Alemania (67)** e **Italia (45)** en partidos de fase final de Mundiales.

## 📁 Estructura del Proyecto
