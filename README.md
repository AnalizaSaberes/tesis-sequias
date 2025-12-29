# Predicción de Sequías mediante Modelos de Cópulas y Datos Hidrometeorológicos en la Región Sur del Perú (2024)

[cite_start]Este repositorio contiene la implementación y los resultados visuales de la investigación de tesis para optar el grado de **Maestro en Gestión Sostenible de Cuencas Hidrográficas** en la Universidad Nacional del Centro del Perú[cite: 7, 11].

## 📊 Resumen Ejecutivo
[cite_start]La investigación predice el riesgo de sequías meteorológicas capturando la estructura de dependencia no lineal entre la duración (D) y la severidad (S) de los eventos extremos mediante modelos estocásticos basados en funciones Cópula[cite: 3016].

### 🛠 Metodología Aplicada
* [cite_start]**Imputación de Datos:** Uso del algoritmo MICE (Imputación Múltiple por Ecuaciones Encadenadas) para tratar datos faltantes en 28 estaciones meteorológicas[cite: 3603, 3611].
* [cite_start]**Identificación de Eventos:** Aplicación de la Teoría de Rachas (Run Theory) para aislar periodos de déficit hídrico[cite: 3219, 3713].
* [cite_start]**Modelamiento Bivariado:** Uso de Cópulas Arquimedianas (Gumbel y Clayton) para estimar periodos de retorno conjuntos y probabilidades condicionales[cite: 3019, 3337].
* [cite_start]**Regionalización Geoestadística:** Interpolación espacial mediante Kriging Ordinario (Modelo Esférico) con una precisión de R² = 0.92[cite: 3406, 3738, 4645].

## 📍 Hallazgos Principales
* [cite_start]**Correlación Fuerte:** Se identificó una Tau de Kendall promedio de 0.81 entre duración y severidad[cite: 4122, 4784].
* [cite_start]**Núcleo de Riesgo:** Identificación de un corredor de alta vulnerabilidad (>80% de probabilidad de sequía extrema) en las cabeceras de cuenca de Apurímac y Cusco[cite: 4708, 4795].
* [cite_start]**Subestimación del Riesgo:** Se demostró que los métodos univariados tradicionales subestiman sistemáticamente la amenaza real en comparación con el enfoque multivariado[cite: 3021, 3033].

## 📁 Contenido del Repositorio
* `/css`: Estilos de la plataforma web.
* [cite_start]`/assets/img`: Cartografía de riesgo, isolíneas de probabilidad y curvas de consistencia[cite: 4959].
* [cite_start]`/assets/docs`: Documentación técnica y anexos compilados[cite: 4947].

---
[cite_start]**Autor:** Virgilio Arriaga Gomez [cite: 9, 2983]
[cite_start]**Institución:** Universidad Nacional del Centro del Perú [cite: 1, 2975]
**Contacto:** [Enlace a tu LinkedIn]
