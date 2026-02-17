# Álgebra Lineal - Curso Interactivo con Python

Proyecto para aprender Álgebra Lineal paso a paso con Python y Jupyter Notebooks.

## Estructura del Proyecto

```
linear-algebra/
├── src/                    # Código fuente principal
│   ├── models/             # Clases y estructuras de datos
│   ├── services/           # Lógica y algoritmos
│   └── utils/              # Utilidades y helpers
├── notebooks/              # Jupyter Notebooks del curso
├── data/                   # Datasets de ejemplo
│   ├── raw/                # Datos sin procesar
│   └── processed/          # Datos procesados
├── tests/                  # Tests unitarios
├── requirements.txt        # Dependencias del proyecto
└── .env.example            # Variables de entorno ejemplo
```

## Contenido del Curso

1. **Vectores** - Definición, operaciones básicas, espacios vectoriales
2. **Matrices** - Tipos, operaciones, propiedades
3. **Sistemas de ecuaciones lineales** - Métodos de solución
4. **Determinantes** - Cálculo y propiedades
5. **Espacios vectoriales** - Bases, dimensión, subespacios
6. **Transformaciones lineales** - Núcleo, imagen, matrices
7. **Valores y vectores propios** - Eigenvalues, diagonalización
8. **Aplicaciones** - Rotaciones, proyecciones, ML

## Requisitos

- Python 3.10+
- pip

## Instalación

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
source venv/bin/activate  # macOS/Linux

# Instalar dependencias
pip install -r requirements.txt
```

## Uso

### Local con Jupyter

```bash
# Activar entorno virtual
source venv/bin/activate

# Iniciar Jupyter Notebook
jupyter notebook
```

### Con Google Colab

1. Sube los notebooks de la carpeta `notebooks/` a Google Colab
2. O conecta tu Google Drive y clona este repositorio:

```python
from google.colab import drive
drive.mount('/content/drive')

%cd /content/drive/MyDrive
!git clone <tu-repo-url>
```

## Librerías Principales

- **numpy**: Operaciones con vectores y matrices
- **scipy**: Álgebra lineal avanzada
- **matplotlib**: Visualización de vectores y transformaciones
- **sympy**: Matemáticas simbólicas
- **jupyter**: Notebooks interactivos

## Autor

Omar Martinez

## Licencia

MIT
