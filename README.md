# **Análisis Exploratorio de Datos: World Happiness Report (2015-2024)**

## **📊 Descripción del Proyecto**
Este repositorio contiene un Análisis Exploratorio de Datos (EDA) completo del **World Happiness Report**, abarcando el período 2015-2024. El objetivo principal es identificar y comprender los factores determinantes de la felicidad a nivel mundial, con especial atención al impacto de la pandemia de COVID-19 en los indicadores de bienestar.

## **🎯 Objetivos de Investigación**
1. Analizar la evolución temporal de los indicadores de felicidad global (2017-2024)
2. Identificar correlaciones entre factores socioeconómicos y el puntaje de felicidad
3. Evaluar el impacto diferenciado de la pandemia COVID-19 por regiones
4. Validar hipótesis sobre los determinantes de la felicidad nacional

## **📁 Dataset**
- **Fuente**: World Happiness Report (2015-2024)
- **Período analizado**: 2017-2024 (tras limpieza de datos)
- **Registros**: 1,186 observaciones
- **Países**: 163 países únicos
- **Variables principales**: 6 indicadores numéricos + 5 variables categóricas

**Variables clave analizadas**:
- `Happiness Score` (Variable objetivo)
- `GDP per capita`
- `Social Support`
- `Healthy Life Expectancy`
- `Freedom to make life choices`
- `Generosity`
- `Perceptions of Corruption`

## **🔍 Hallazgos Clave**

### **Correlaciones Principales**
- **Factor más influyente**: Apoyo Social (r = 0.744, R² = 55.4%)
- **Segundo factor**: Esperanza de Vida Saludable (r = 0.660)
- **Tercer factor**: PIB per cápita (r = 0.635)
- **Factores marginales**: Generosidad y Percepción de Corrupción

### **Impacto de la Pandemia COVID-19**
- **Caída global en felicidad (2020)**: -0.21 puntos (4.1% vs 2019)
- **Recuperación completa**: Alcanzada en 2022, con tendencia positiva posterior
- **Impacto desigual**: Países con sistemas de salud robustos y alto apoyo social mostraron mayor resiliencia

### **Ranking por Continente (Promedio 2017-2024)**
1. **Europa**: 6.25 puntos
2. **América**: 5.89 puntos
3. **Asia**: 5.32 puntos
4. **África**: 4.15 puntos

### **Casos Destacados**
- **Países Nórdicos**: Dominan consistentemente el Top 5 global
- **Paradoja Latinoamericana**: Alta felicidad relativa pese a PIB moderado
- **Recuperación Asiática**: Rápida recuperación post-COVID en Asia Oriental

## **🛠️ Metodología y Herramientas**

### **Tecnologías Utilizadas**
- **Lenguaje**: Python 3.9+
- **Librerías principales**: Pandas, NumPy, Matplotlib, Seaborn
- **Entorno**: Jupyter Notebook
- **Control de versiones**: Git y GitHub

### **Proceso de Análisis**
1. **Limpieza y preprocesamiento**: Corrección de tipos de datos, manejo de valores nulos, estandarización geográfica
2. **Análisis univariante**: Distribuciones y estadísticas descriptivas
3. **Análisis bivariante/multivariante**: Correlaciones y relaciones entre variables
4. **Análisis temporal**: Tendencias y evolución (2017-2024)
5. **Análisis geográfico**: Comparativas por regiones y continentes

## **📂 Estructura del Repositorio**
```
world-happiness-eda/
├── data/                    # Datasets originales y procesados
├── notebooks/               # Cuadernos de análisis
│   ├── Limpieza.ipynb
│   ├── Exploratorio.ipynb
├── src/                     
├── reports/                 # Reportes y presentaciones
│   ├── Dashboard.pptx
|   |── Dashboard.pdf
│   └── MEMORIA.md
├── README.md                # Este archivo
└── .gitignore
```

## **📈 Conclusiones Principales**

### **Validación de Hipótesis**
✅ **Confirmadas**:
- Impacto significativo de COVID-19 en las diferentes variables.
- Apoyo social como factor más correlacionado
- Dominancia consistente de países nórdicos
- Efectos en cadena de conflictos socio-económicos

⚠️ **Parcialmente confirmada**:
- Relación entre PIB y felicidad (presenta outliers significativos)


## **✍️ Autor**
**[Andrea Altamirano]** - Estudiante del Bootcamp de Data Science

---
*Última actualización: [05-12-2025]*

**Nota**: Este proyecto fue desarrollado con fines educativos como parte de un bootcamp de Data Science. Los datos pueden estar sujetos a actualizaciones por parte de las fuentes oficiales.