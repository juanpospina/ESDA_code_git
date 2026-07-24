<a name="readme-top"></a>

<p align="center">
  <img src="./logo/logo.png" alt="Logo EAFIT"  width="150">
</p>

  <h3 align="center"> CM0866 · Análisis Exploratorio de Datos Espaciales y Econometría Espacial</h3>

Repositorio académico correspondiente al curso **Análisis Exploratorio de Datos Espaciales y Econometría Espacial**, desarrollado como parte del programas de postgrado de la **Universidad EAFIT**.

## Información del curso

| Campo | Detalle |
|:------|:--------|
| Profesores | Juan Pablo Ospina Zapata (jospinaz@eafit.edu.co)<br>Juan Carlos Duque Cardona (jduquec1@eafit.edu.co) |
| Horario | Martes 17:00 - 19:00, 15-106 |
| Periodo académico | 2026-02 |
| Software | Python / QGIS / R |

## Contenido

- [Sesión 1 → El territorio como dato](/Clase_01/)
    - Exploración capas de datos geográficos.
    - Primer mapa temático.

- [Sesión 2 → Análisis Exploratorio de Datos Espaciales](/Clase_02/)
    - Distancia Euclidea y distancia de red.
    - MAUP.
    - AEDE y descarga de datos de Open Street Maps.

- [Sesión 3 → Análisis Exploratorio de Datos Espaciales](/Clase_03/)
    - Test.
    - TEst2

## Configuración del entorno virtual

Se recomienda utilizar un entorno virtual para instalar las librerías del repositorio.

1. Crear el entorno virtual

Desde la carpeta principal del proyecto, ejecuta:

```bash
python -m venv .venv
```

2. Activar el entorno virtual

En Linux o macOS:

```bash
source .venv/bin/activate
```

En Windows con PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Cuando el entorno esté activo, aparecerá `(.venv)` al inicio de la línea de la terminal.

3. Instalar las dependencias

Con el entorno virtual activo, ejecuta:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Las librerías y sus versiones están definidas en el archivo `requirements.txt`.

4. Desactivar el entorno virtual

Cuando termines de trabajar, puedes desactivar el entorno con:

```bash
deactivate
```

## Preparación de los datos

Después de clonar el repositorio, los archivos de datos están en formato comprimido (.zip). No es necesario descomprimirlos para ejecutar los notebooks.

Los archivos comprimidos están ubicados en:

```text
datos/morfologia/
```

## Recursos computacionales complementarios
Para la ejecución de los script del curso, se recomienda crear cuentas (gratuitas) en las siguientes plataformas:
  - [Google Colaboratory](https://colab.research.google.com/)
  