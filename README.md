## Juan Pablo Cano

📊 Industrial Engineer & Data Analyst | Data Storyteller | Pythonista

---

## 🚀 Sobre mí

Soy un **Ingeniero Industrial** apasionado por los datos, la automatización y la visualización. Me especializo en convertir datos complejos en historias claras para la toma de decisiones. Siempre estoy aprendiendo algo nuevo para mejorar mis habilidades y entregar valor.

---

## Skills

<!-- Herramientas de análisis y ciencia de datos -->

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-0A192F?style=for-the-badge&logo=google&logoColor=white)
![Statistics](https://img.shields.io/badge/-Statistics-2E7D32?style=for-the-badge)

<!-- Visualización de datos -->

![Seaborn](https://img.shields.io/badge/-Seaborn-4B8BBE?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

<!-- Herramientas BI y Dashboards -->

![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
[<img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Tableau_Logo.png" height="28"/>](https://www.tableau.com/)
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Dash](https://img.shields.io/badge/-Dash-00AEEF?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

<!-- Bases de datos -->

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)




---

## 📈 Últimos proyectos

# 🎮 Análisis de Ventas de Videojuegos

## 🧠 Descripción del Proyecto

Trabajas para una tienda online llamada *Ice* que vende videojuegos a nivel mundial. A partir de reseñas de usuarios y críticos, géneros, plataformas (como Xbox y PlayStation) y datos históricos de ventas, tu objetivo es **identificar patrones que determinan si un videojuego será exitoso o no**, con el fin de detectar proyectos prometedores y planificar campañas publicitarias efectivas para 2017.

Este análisis se basa en datos disponibles hasta el año 2016.

---

## 📁 Dataset Utilizado

- Fuente: `/datasets/games.csv`
- Columnas destacadas:
  - `Name`, `Platform`, `Year_of_Release`, `Genre`
  - `NA_sales`, `EU_sales`, `JP_sales`, `Other_sales`
  - `Critic_Score`, `User_Score`, `Rating`

---

## 🧰 Herramientas Utilizadas

- Python (Jupyter Notebook)
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy.stats`

---

## 🔍 Metodología de Análisis

1. **Carga y preprocesamiento de datos**
   - Estandarización de nombres de columnas
   - Conversión de tipos de datos
   - Tratamiento de valores ausentes (incluyendo valores "TBD")
   - Cálculo de las ventas totales por juego (`total_sales`)

2. **Análisis exploratorio**
   - Juegos lanzados por año
   - Tendencias de ventas por plataforma
   - Ciclo de vida de consolas: aparición y desaparición
   - Análisis de plataformas líderes y emergentes

3. **Análisis de correlaciones**
   - Relación entre reseñas de críticos/usuarios y ventas
   - Análisis de ventas por género

4. **Segmentación por región**
   - Principales plataformas y géneros en NA, EU y JP
   - Impacto de la clasificación ESRB por región

5. **Pruebas de hipótesis**
   - Comparación de medias: Xbox One vs PC
   - Diferencia de calificaciones: Acción vs Deportes

---

## 📈 Resultados Clave

- Algunas plataformas (como PS2) fueron líderes en el pasado, pero ya no generan ventas.
- Las ventas en Norteamérica son significativamente mayores que en otras regiones.
- Las calificaciones de los críticos muestran una **correlación débil o moderada** con las ventas.
- Los géneros de Acción y Deportes dominan el mercado en cantidad, pero no necesariamente en rentabilidad.
- Las pruebas de hipótesis revelaron diferencias estadísticamente significativas entre ciertos géneros.

---

## 🌍 Perfil Regional

- **NA (Norteamérica):** Domina Xbox y géneros como Acción y Deportes.  
- **EU (Europa):** Similar a NA, con ligera preferencia por PlayStation.  
- **JP (Japón):** Preferencia clara por Nintendo y géneros como Rol (RPG).  
- **ESRB:** Su impacto varía por región, con más relevancia en NA.

---

## ✅ Conclusiones

Este análisis permite seleccionar plataformas y géneros con mayor potencial para futuras campañas de marketing. Se sugiere enfocar esfuerzos en consolas emergentes con crecimiento reciente y géneros con mayor rentabilidad ajustada por ventas promedio. Además, los patrones regionales son clave para personalizar estrategias publicitarias.

---

## 👨‍💻 Autor

**Juan David Cano**  
- GitHub: [@juancanoanalyst](https://github.com/juancanoanalyst)  
- Portafolio: [juancanoanalyst.github.io/Portafolio](https://juancanoanalyst.github.io/Portafolio/)  
- LinkedIn: [Juan Pablo Cano Chaparro](https://www.linkedin.com/in/juan-pablo-cano-chaparro-1aa685209/)

---

## 📎 Archivos

- `video_games_sales_analysis.ipynb`: Notebook completo con el análisis
- `README.md`: Este archivo

---

## 📌 Nota

Este proyecto forma parte de un bootcamp en análisis de datos realizado en TripleTen. Se trabajó con un enfoque de negocio y análisis estadístico aplicado, empleando herramientas reales utilizadas en la industria.



---


