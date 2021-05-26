# Aprendizaje Automático en Grafos
Repositorio oficial de la materia "Aprendizaje Automático en Grafos", dictada en el contexto de la [Maestría en Data Mining](http://datamining.dc.uba.ar/datamining/) de las facultades de Exactas e Ingeniería de la UBA (Mayo 2021)

Docentes:
- Dr. Martín Elías Costa
- Lic. Gonzalo Barrera Borla

## Ambientes de trabajo

El lenguaje de programación "oficial" del curso será Python, aunque los alumnos son bienvenidos a explorar procedimientos equivalentes en R o cualquier otro. Aquellos estudiantes que se sientan cómodos programando pueden instalar las dependencias necesarias como más lo deseen, pero la recomendación del claustro es que utilicen la versión de [(mini)conda](https://docs.conda.io/en/latest/miniconda.html) correspondiente a su sistema operativo. Una vez instalado Miniconda, pueden crear el ambiente mínimo necesario para correr los scripts de la materia con:

```bash
conda env create --file environment.yml
```

:warning: Como con toda pieza de código desconocida, comience por leer su [documentación](https://conda.io/projects/conda/en/latest/index.html). Si es muy vaga/o, puede descarga de [aquí](https://conda.io/projects/conda/en/latest/user-guide/cheatsheet.html) un resumen de comandos importantes en PDF.

Instalado el ambiente, activarlo es tan sencillo como `conda activate aag`, y desactivarlo, `conda deactivate`. El ambiente de trabajo incluye su propia instalación de Jupyter Lab, con lo cual levantar JupyterLab como servicio web es sencillamente:

```bash
conda activate aag
jupyter lab
```

Usuarios más avanzados pueden preferir simplemente _registrar el kernel_ de python en su propia instalación previa de Jupyter Lab.