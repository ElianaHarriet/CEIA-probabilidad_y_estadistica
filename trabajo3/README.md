# 🎯 Trabajo 3 - Tercer Trabajo Práctico

Este directorio contiene el **tercer trabajo práctico** del curso de Probabilidad y Estadística para la Inteligencia Artificial.

## 🧰 Prerrequisitos y Setup

Desde la raíz del repositorio:
```bash
uv sync
```

## 📁 Estructura Actual

```
trabajo3/
├── code/
│   └── analisis_final.ipynb                 # Notebook principal del TP3
├── data/
│   ├── Datos_TP_final_22Co2025_a2217.xlsx   # Datos provistos por cátedra
│   ├── output1.png                          # Gráficas exportadas
│   ├── output2.png
│   └── output3.png
├── docs/
│   ├── Tercer_examen_PEIA_22Co2025.pdf      # Enunciado oficial
│   ├── SolucionTercer_examen_PEIA_22Co2025.tex  # Informe en LaTeX
│   └── SolucionTercer_examen_PEIA_22Co2025.pdf  # Informe compilado
└── README.md
```

## 🚀 Ejecución del Análisis (Notebook)

```bash
cd trabajo3
uv run jupyter lab
# Abrir: code/analisis_final.ipynb
```

El notebook implementa:
- Carga y consolidación de datos desde Excel (5 hojas, unificadas)
- Ejercicio 1: Bootstrap de IC mensuales (95% y 99%) para Santa Ana
- Ejercicio 2: ANOVA con verificación de supuestos (Levene) y visualizaciones
- Ejercicio 3: Comparación de extremos con prueba t (Student/Welch según Levene)

## 📝 Compilación del Informe (LaTeX)

```bash
cd trabajo3/docs
latexmk -pdf SolucionTercer_examen_PEIA_22Co2025.tex
# o con pdflatex en dos pasadas
pdflatex SolucionTercer_examen_PEIA_22Co2025.tex && pdflatex SolucionTercer_examen_PEIA_22Co2025.tex
```

Notas de formato:
- Se utiliza `\usepackage{float}` y `[H]` para fijar tablas y figuras junto a sus títulos.
- Los archivos `output*.png` se generan desde el notebook y se referencian en el informe.

## 📚 Contexto Académico

- **Materia:** Probabilidad y Estadística para la Inteligencia Artificial
- **Institución:** CEIA - Universidad de Buenos Aires
- **Estudiante:** Eliana Harriet (a2217)
- **Cohorte:** 22Co2024

---

📊 **Estadística para IA** | 🎓 **CEIA - UBA** | 👩‍🎓 **Eliana Harriet**
