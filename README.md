# 🎮 Proyecto ICE – Análisis de Videojuegos

Este proyecto analiza datos históricos de ventas, reseñas y características de videojuegos para **identificar patrones de éxito**, seleccionar plataformas y géneros prometedores, y planificar campañas publicitarias estratégicas para 2017.

---

## 🌐 Objetivo del proyecto

* Explorar el comportamiento del mercado de videojuegos hasta diciembre de 2016.
* Analizar plataformas, géneros, ventas y clasificaciones ESRB.
* Predecir qué juegos tienen mayor potencial de éxito en 2017.
* Proporcionar recomendaciones estratégicas para marketing y promociones regionales.

---

## 🧰 Herramientas y tecnologías utilizadas

**Lenguaje y entornos:**

* Python 🐍
* Jupyter Notebook / VS Code

**Bibliotecas de análisis de datos:**

* **pandas** → Limpieza, transformación y manipulación de datasets.
* **NumPy** → Operaciones numéricas y cálculos estadísticos.
* **matplotlib** y **seaborn** → Visualización de tendencias y relaciones.
* **scipy.stats** → Pruebas de hipótesis y análisis estadístico.

---

## 📊 Proceso de análisis

1. **Preparación de los datos:**

   * Limpieza de valores ausentes y corrección de tipos de datos.
   * Estructuración de datasets para análisis confiable.

2. **Análisis histórico de plataformas y ventas:**

   * Identificación de ciclos de vida de consolas.
   * Comparación de plataformas consolidadas (PS4, XOne) y portátiles (3DS, PSV).

3. **Distribución por género y clasificación ESRB:**

   * Identificación de géneros más rentables: *Action, Shooter, Role-Playing*.
   * Análisis de tendencias de contenido por edad, destacando la categoría "M" para adultos.

4. **Análisis regional:**

   * Diferencias de ventas y preferencias en América del Norte, Europa y Japón.
   * Ajuste de estrategias de marketing según regiones.

5. **Pruebas de hipótesis:**

   * Comparación de calificaciones promedio entre Xbox One y PC.
   * Comparación de calificaciones entre géneros *Action* y *Sports*.
   * Validación estadística mediante valor p y nivel de significancia 0.05.

---

## 💡 Principales hallazgos

* La mayoría de las plataformas sigue un ciclo de vida predecible: crecimiento inicial → pico de ventas → declive.
* PlayStation muestra la mayor consistencia a través de generaciones.
* PS4 y XOne aún en fase de maduración generan ingresos importantes, pero con disminución del ritmo de crecimiento.
* Los géneros más rentables son *Action*, *Shooter* y *Role-Playing*.
* Las preferencias regionales difieren: Japón prefiere plataformas portátiles, mientras que América del Norte y Europa dominan PS4, XOne y 3DS.
* La categoría ESRB "M" (adultos) muestra una tendencia hacia contenido más maduro, útil para campañas focalizadas.

---

## 📦 Estructura del repositorio

```
📦 ICE_video_games/
 ┣ 📜 data/                  # Datasets históricos de videojuegos
 ┣ 📜 notebooks/             # Notebooks de análisis
 ┣ 📜 images/                # Gráficos y visualizaciones
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## ⚙️ Requisitos

* Python 3.7 o superior
* Dependencias:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

---

## 📈 Aprendizajes clave

* Comprender el **ciclo de vida de consolas** y su impacto en ventas.
* Identificar géneros y plataformas con mayor potencial de éxito.
* Aplicar **análisis estadístico y pruebas de hipótesis** para respaldar decisiones.
* Planificar campañas publicitarias basadas en datos históricos y preferencias regionales.

---

## 👨‍💻 Autor

**Desarrollado por:** Carlos Ortiz
**Rol:** Data Analyst
💬 *Proyecto educativo para aprendizaje en análisis de datos, marketing y videojuegos.*
