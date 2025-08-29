# 🔬 Trabajo 1 - Análisis de Ventas del Supermercado

Este directorio contiene la solución completa para el **primer trabajo práctico** del curso de Probabilidad y Estadística para la Inteligencia Artificial.

## 🧰 Prerrequisitos y Setup

Desde la raíz del repositorio:
```bash
uv sync
```

## 📊 Descripción del Proyecto

El trabajo consiste en un análisis estadístico comprehensivo de un dataset de ventas de supermercado, aplicando técnicas de estadística descriptiva e inferencial para extraer insights significativos sobre patrones de compra, comportamientos de clientes y tendencias de ventas.

## 📁 Estructura del Directorio

```
trabajo1/
├── code/                                           # Código fuente del análisis
│   └── analisis3.ipynb                           #   Notebook Jupyter principal
├── data/                                           # Dataset del trabajo
│   └── Datos_primer_TP_22Co2024_a2217.xlsx       #   Datos de ventas del supermercado
├── docs/                                           # Documentación y enunciados
│   ├── PrimerExamenPEIA-22Co2025-a2217.pdf       #   Enunciado del primer examen
│   ├── SolucionPrimerExamenPEIA-22Co2025-a2217.pdf  #   Solución final en PDF
│   └── SolucionPrimerExamenPEIA-22Co2025-a2217.tex  #   Código LaTeX de la solución
└── entregable.zip                                  # Archivo comprimido para entrega
```

## 🎯 Objetivos del Análisis

- **Análisis Descriptivo:** Caracterización del dataset y variables clave
- **Análisis Exploratorio:** Identificación de patrones y correlaciones
- **Visualización de Datos:** Gráficos informativos para comunicar hallazgos
- **Análisis Inferencial:** Aplicación de técnicas estadísticas avanzadas
- **Interpretación de Resultados:** Conclusiones basadas en evidencia estadística

## 🚀 Ejecución del Proyecto

### Método Recomendado - JupyterLab
```bash
# Desde el directorio raíz del proyecto
cd trabajo1
uv run jupyter lab

# Abrir el notebook: code/analisis3.ipynb
```

### Método Alternativo - Jupyter Notebook
```bash
cd trabajo1
uv run jupyter notebook code/analisis3.ipynb
```

### Visualización Directa
```bash
# Ver el notebook sin ejecutar
uv run jupyter nbconvert --to html code/analisis3.ipynb --stdout
```

## 📈 Contenido del Análisis

El notebook `analisis3.ipynb` contiene las siguientes secciones:

1. **📋 Carga y Exploración Inicial de Datos**
   - Importación del dataset
   - Inspección de variables y tipos de datos
   - Detección de valores faltantes

2. **🔍 Análisis Descriptivo**
   - Estadísticas resumidas por variable
   - Distribuciones de frecuencia
   - Medidas de tendencia central y dispersión

3. **📊 Visualización Exploratoria**
   - Histogramas y gráficos de densidad
   - Diagramas de caja y bigotes
   - Matrices de correlación

4. **🎯 Análisis Específico por Categorías**
   - Segmentación por variables categóricas
   - Comparaciones entre grupos
   - Análisis de patrones temporales

5. **📝 Conclusiones y Recomendaciones**
   - Resumen de hallazgos principales
   - Implicaciones prácticas
   - Sugerencias para análisis futuros

## 🛠️ Dependencias Específicas

Las siguientes librerías son utilizadas en el análisis:
- `pandas` - Manipulación y análisis de datos
- `numpy` - Operaciones numéricas
- `matplotlib` - Visualización básica
- `seaborn` - Visualización estadística avanzada
- `openpyxl` - Lectura de archivos Excel
- `scipy` - Funciones estadísticas

## 📋 Estado del Proyecto

- ✅ **Análisis Exploratorio:** Completado
- ✅ **Visualizaciones:** Implementadas
- ✅ **Documentación:** Finalizada
- ✅ **Entrega:** Preparada en `entregable.zip`

## 💡 Tips para la Revisión

1. **Ejecución Completa:** Ejecuta todas las celdas desde el inicio para reproducir resultados
2. **Visualizaciones Interactivas:** Algunas gráficas permiten zoom y exploración
3. **Interpretación:** Presta atención a los comentarios y conclusiones en markdown
4. **Código Limpio:** El notebook incluye comentarios explicativos para facilitar la comprensión

## 🔗 Enlaces del TP1

- Tablero Miro del TP1: https://miro.com/app/board/uXjVJeOThfE=/?share_link_id=504273934715

---

📊 **Análisis Estadístico Avanzado** | 🎓 **CEIA - UBA** | 👩‍🎓 **Eliana Harriet (a2217)** 