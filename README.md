# CEIA - Probabilidad y Estadística para la Inteligencia Artificial 📊

Este repositorio contiene las soluciones y materiales para los trabajos prácticos del curso de **Probabilidad y Estadística para la Inteligencia Artificial** de la **Carrera de Especialización en Inteligencia Artificial (CEIA)** de la **Universidad de Buenos Aires (UBA)**.

## 👩‍🎓 Información del Estudiante

- **Estudiante:** Eliana Harriet
- **Código SIU:** a2217
- **Cohorte:** 22Co2024

## 📁 Estructura del Proyecto

```
CEIA-probabilidad_y_estadistica/
├── trabajo1/             # Primer Trabajo Práctico - Análisis de Ventas del Supermercado
│   ├── code/             #   Notebook Jupyter con análisis estadístico
│   ├── data/             #   Dataset de ventas del supermercado
│   ├── docs/             #   Documentación y enunciados
│   └── README.md         #   Instrucciones específicas del trabajo 1
├── trabajo2/             # Segundo Trabajo Práctico - Examen Parcial
│   ├── docs/             #   Soluciones en LaTeX y PDF
│   └── README.md         #   Detalles del segundo examen
├── trabajo3/             # Tercer Trabajo Práctico
│   ├── code/             #   analisis_final.ipynb (notebook principal)
│   ├── data/             #   Datos y salidas gráficas (output1/2/3.png)
│   ├── docs/             #   Enunciado (PDF) y solución en LaTeX/PDF
│   └── README.md         #   Instrucciones del trabajo 3
├── clases/               # Material de clases en PDF
├── assets/               # Recursos compartidos (logos, etc.)
├── pyproject.toml        # Configuración del proyecto Python
└── uv.lock               # Lock file de dependencias
```

## 🚀 Configuración del Entorno

Este proyecto utiliza **`uv`** como gestor de dependencias moderno para Python. Para configurar el entorno de desarrollo:

### Prerrequisitos
- Python >= 3.13
- `uv` instalado (https://docs.astral.sh/uv/getting-started/installation/)

### Configuración
```bash
# Clonar el repositorio
git clone <url-del-repositorio>
cd CEIA-probabilidad_y_estadistica

# Instalar dependencias y crear entorno virtual
uv sync

# Activar entorno virtual (opcional, uv run lo maneja automáticamente)
source .venv/bin/activate
```

## 📦 Dependencias Principales

- **Análisis de Datos:** `pandas >= 1.3.0`, `numpy >= 1.21.0`
- **Visualización:** `matplotlib >= 3.4.0`, `seaborn >= 0.11.0`
- **Estadística:** `scipy >= 1.7.0`
- **Notebooks:** `jupyter >= 1.1.1`
- **Archivos Excel:** `openpyxl >= 3.0.0`

## 💻 Ejecución de Trabajos

### Trabajo 3 (actual)
```bash
# Iniciar JupyterLab y abrir el notebook principal del TP3
cd trabajo3
uv run jupyter lab
# Abrir: code/analisis_final.ipynb
```

### Jupyter Notebooks (general)
```bash
uv run jupyter notebook
```

### Scripts Python
```bash
# Ejecutar un script específico
uv run python ruta/al/script.py
```

## 📚 Contenido de los Trabajos

### 🔬 Trabajo 1: Análisis de Ventas del Supermercado
- **Tipo:** Análisis estadístico descriptivo e inferencial
- **Herramientas:** Python, Pandas, Matplotlib, Seaborn
- **Dataset:** Ventas de supermercado con múltiples variables
- **Estado:** ✅ Completado

### 📝 Trabajo 2: Segundo Examen Parcial
- **Tipo:** Ejercicios teórico-prácticos
- **Temas:** Máxima Verosimilitud, Mínimos Cuadrados, Inferencia Bayesiana
- **Herramientas:** LaTeX para documentación matemática
- **Estado:** ✅ Completado

### 🎯 Trabajo 3: Tercer Trabajo Práctico
- **Notebook:** `trabajo3/code/analisis_final.ipynb`
- **Informe:** `trabajo3/docs/SolucionTercer_examen_PEIA_22Co2025.tex` (+ PDF)
- **Enunciado:** `trabajo3/docs/Tercer_examen_PEIA_22Co2025.pdf`
- **Estado:** ✅ En curso

## 📖 Uso del Repositorio

1. **Navegación:** Cada trabajo tiene su propio directorio con README específico
2. **Ejecución:** Consulta el README de cada trabajo para instrucciones detalladas
3. **Documentación:** Los archivos PDF en `docs/` contienen enunciados y soluciones
4. **Código:** Los notebooks Jupyter ofrecen análisis interactivo paso a paso

## 🔗 Enlaces Útiles

- https://docs.astral.sh/uv/
- https://jupyterlab.readthedocs.io/
- https://pandas.pydata.org/docs/
- https://matplotlib.org/stable/gallery/

---

🎓 **CEIA - UBA** | 📊 **Probabilidad y Estadística para IA** | 🚀 **Cohorte 2024** 