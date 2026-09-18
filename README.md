# 📉 Análisis de fricción en la experiencia de usuario (UX) del E-commerce combinada con limpieza de datos

[![Open In Colab]()

## 📌 Introducción y Enfoque UX
En el diseño de producto digital, las decisiones estratégicas no pueden basarse únicamente en la intuición visual. Este proyecto demuestra la capacidad de extraer, limpiar y analizar **datos cuantitativos de comportamiento (User Analytics)** para identificar cuellos de botella en la experiencia de usuario de una tienda online.

## 🛠️ Pipeline de Datos (Proceso del Cuaderno)
El cuaderno de Google Colab simula un entorno real de investigación cuali-cuantitativa, ejecutando tres etapas clave:

1. **Limpieza y Normalización de Datos (Data Wrangling):**
   * Corrección de redundancias en variables categóricas (`Mobile`, `mobile`, `MOBILE`).
   * Imputación de valores nulos utilizando análisis de tendencia central (Mediana) para evitar sesgos en el comportamiento de la muestra.
2. **Análisis de Métricas de Interacción:** Mapeo de la relación entre el esfuerzo de navegación (*clicks*) y el tiempo empleado en completar la tarea (*checkout*).
3. **Visualización Orientada al Producto:** Creación de dashboards minimalistas para comunicar problemas complejos al equipo de desarrollo y negocio de forma directa.

## 📸 Descubrimientos Clave (Insights Visuales)
> ⚠️ **Nota de Portafolio:** Reemplaza la imagen de abajo con la captura de pantalla real de los gráficos generados por tu Colab (la gráfica de barras y el gráfico de dispersión).

![Dashboard de Analítica UX]<img width="1384" height="584" alt="download" src="https://github.com/user-attachments/assets/8beeb621-6a5f-4647-a66c-4a2c7cfd7a7c" />
)

### 🚨 Diagnóstico de UX Research:
* **Fricción Crítica en Mobile:** Los usuarios móviles experimentan una tasa de abandono drásticamente superior. El gráfico de dispersión revela un patrón de **"Fatiga por Clicks"**: a mayor número de interacciones obligadas en pantallas pequeñas, el tiempo se dispara y el carrito se abandona.
* **Acción de Diseño (Next Steps):** Rediseñar el flujo de checkout móvil eliminando campos innecesarios de entrada de texto e integrando métodos de pago rápidos (como Apple Pay o Mercado Pago) para reducir drásticamente la carga cognitiva y el conteo de clicks.

## 🧰 Stack Técnico Usado
* **Pandas:** Estructuración y curación del set de datos.
* **Numpy:** Gestión de matrices y datos nulos.
* **Matplotlib & Seaborn:** Visualización avanzada y diseño estético del dashboard con enfoque en accesibilidad.
