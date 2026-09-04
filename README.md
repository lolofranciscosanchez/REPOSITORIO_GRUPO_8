<div align="center">

# 📘 REPOSITORIO_GRUPO_8

### Ingeniería y Calidad de Software · Grupo 8 · 2026

Repositorio grupal de la cátedra: materiales de clase, trabajos prácticos,
trabajos de investigación y gestión de configuración del software (SCM).

![Grupo](https://img.shields.io/badge/Grupo-8-success)
![Año](https://img.shields.io/badge/A%C3%B1o-2026-informational)
![Integrantes](https://img.shields.io/badge/Integrantes-13-orange)

</div>

---

## 📑 Tabla de contenidos

- [👥 Integrantes](#-integrantes)
- [📋 Consigna](#-consigna)
- [🗂️ Estructura del repositorio](#️-estructura-del-repositorio)
- [⚙️ Ítems de configuración](#️-ítems-de-configuración)
- [📖 Glosario](#-glosario)
- [🏷️ Criterio de línea base](#️-criterio-de-línea-base)
- [📌 Líneas base disponibles](#-líneas-base-disponibles)

---

## 👥 Integrantes

| # | Apellido | Nombre | Legajo |
|:-:|:---------|:------:|:------:|
| 1 | Alabe | Ulises | 91166 |
| 2 | Amado | Marco | 57572 |
| 3 | Barzola | Augusto | 59247 |
| 4 | Bencivenga | Carlos Martin | 97244 |
| 5 | Blanco | Lisandro | 60634 |
| 6 | Dapuez | Eliseo | 91625 |
| 7 | De Goycoechea | Mateo | 85203 |
| 8 | Malizia Pacheco | Matias | 407901 |
| 9 | Pacheco | Agustin | 92779 |
| 10 | Pahud | Fernando | 61175 |
| 11 | Popoff | Agustin | 88588 |
| 12 | Sanchez | Francisco | 90183 |
| 13 | Sosa | Mateo | 97716 |

---

## 📋 Consigna

| **Elemento** | **Descripción** |
|:-------------|:----------------|
| **Unidad** | Unidad Nro. 3: Gestión del Software como producto |
| **Consigna** | Comprender los conceptos de administración de configuración de software (SCM) expuestos en la clase teórica para aplicarlos en un ejercicio propuesto por la cátedra. |
| **Objetivo** | Que el estudiante sea capaz de realizar actividades básicas de la gestión de configuración mediante el uso de una herramienta tales como la definición de una estructura de repositorio, ingreso y extracción de ítems de configuración del repositorio y definición de líneas base. |
| **Propósito** | Aplicar los conceptos de gestión de configuración estudiados en una herramienta de software específica. |
| **Entradas** | Conceptos teóricos sobre los temas desarrollados en clase. Bibliografía referenciada sobre el tema. |
| **Salida** | URL y credenciales de acceso para el repositorio implementado. Documento con el criterio para la creación de una línea base. Se evaluará lo siguiente: el repositorio debe ser accesible de forma pública, implementación de la estructura de carpetas propuesta y que los archivos se encuentren en la ubicación correspondiente a su definición como ítem de configuración. |
| **Instrucciones** | Realizar el diseño del repositorio y reglas de nombrado de ítems de configuración. Crear un repositorio de acceso público. Crear cuentas de usuario para cada uno de los integrantes del grupo. Implementar la estructura del repositorio propuesta y resguardar el trabajo generado durante el cursado de la materia Ingeniería de Software. Realizar commit (colocar) de cada ítem de configuración disponible al momento. Definir al menos un momento que considere adecuado para marcar una línea base y luego marcar la línea base definida en el repositorio. |
| **Observaciones** | El repositorio implementado debe ser de acceso público utilizando Git o Subversión como motor de control de versiones. |

---

## 🗂️ Estructura del repositorio

```text
└── REPOSITORIO_GRUPO_8
    ├── 📁 catedra/
    │   ├── 📁 informacion_de_catedra/
    │   ├── 📁 practico/
    │   └── 📁 teorico/
    │       ├── 📁 bibliografia/
    │       │   └── 📁 <nombre_tema>/
    │       └── 📁 presentaciones_de_clase/
    │
    ├── 📁 material_propio/
    │   ├── 📁 resumenes/
    │   ├── 📁 trabajos_investigacion_grupal/
    │   └── 📁 trabajos_practicos/
    │       └── 📁 tp<n>/
    |
    └── 📄 README.md
```

---

## ⚙️ Ítems de configuración

Cada ítem de configuración se clasifica en una de dos categorías:

- **De cátedra**: material provisto directamente por la cátedra (programa, cronograma, bibliografía, presentaciones, guías).
- **De producción propia**: material generado por el grupo para aprobar la materia (resúmenes, TPs resueltos, trabajo de investigación).

| Ítem de configuración | Tipo | Regla de nombrado | Ubicación física |
|-----------------------|------|-------------------|------------------|
| Planificación de la asignatura | De cátedra | `rg8_planificacion_asignatura_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Material de apoyo para parciales | De cátedra | `rg8_material_de_apoyo_para_parciales_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Presentación de la cátedra | De cátedra | `rg8_presentacion_de_catedra_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Pautas para enviar mail | De cátedra | `rg8_pautas_para_enviar_mails_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Cronograma de cursada | De cátedra | `rg8_cronograma_isw_2026.xlsx` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Clases grabadas | De cátedra | `rg8_clases_grabadas_2021_isw_2026.xlsx` | `REPOSITORIO_GRUPO_8/catedra/informacion_de_catedra/` |
| Bibliografía | De cátedra | `rg8_<nombre_material>_<apellido_autor>_<año>.pdf` | `REPOSITORIO_GRUPO_8/catedra/teorico/bibliografia/<nombre_tema>/` |
| Presentaciones de clase | De cátedra | `rg8_<n_clase>_<nombre_tema>.pdf` | `REPOSITORIO_GRUPO_8/catedra/teorico/presentaciones_de_clase/` |
| Enunciados de TPs | De cátedra | `rg8_enunciados_tps_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/practico/` |
| Guía de TPs resueltos | De cátedra | `rg8_guia_tps_resueltos_isw_2026.pdf` | `REPOSITORIO_GRUPO_8/catedra/practico/` |
| Templates para ejercicios | De cátedra | `rg8_template_<nombre_ejercicio>.docx/.xlsx` | `REPOSITORIO_GRUPO_8/catedra/practico/` |
| Resúmenes propios del grupo | De producción propia | `rg8_resumen_<nombre_tema>_<apellido_alumno>.docx/.pdf/.xlsx/.jpg/.png/.jpeg` | `REPOSITORIO_GRUPO_8/material_propio/resumenes/` |
| Trabajos prácticos resueltos por el grupo | De producción propia | `rg8_tp<n>_<nombre_tema>_g8.docx/.pdf/.xlsx/.jpg/.png/.jpeg` | `REPOSITORIO_GRUPO_8/material_propio/trabajos_practicos/tp<n>/` |
| Lineamientos para el trabajo de investigación grupal | De cátedra | `rg8_lineamientos_para_trabajos_de_investigacion.pdf` | `REPOSITORIO_GRUPO_8/material_propio/trabajos_investigacion_grupal/` |
| Trabajo de Investigación Grupal | De producción propia | `rg8_tig_<nombre_tema>_g8.docx/.pdf/.xlsx/.jpg/.png/.jpeg` | `REPOSITORIO_GRUPO_8/material_propio/trabajos_investigacion_grupal/` |

---

## 📖 Glosario

| Sigla / Placeholder | Significado |
|---------------------|-------------|
| `<n_clase>` | Número que identifica la clase teórica a la cual corresponde la presentación. Ej: `01`, `02`, etc. |
| `<n>` | Número incremental que identifica el Trabajo Práctico. Ej: `01`, `02`, etc. |
| `<nombre_tema>` | Nombre o título del tema correspondiente al material o trabajo práctico. |
| `<nombre_material>` | Nombre o título del libro/paper de bibliografía. |
| `<apellido_autor>` | Apellido(s) del/los autor(es) del material de bibliografía. |
| `<año>` | Año de publicación del material de bibliografía. |
| `<nombre_ejercicio>` | Nombre o especificación del ejercicio al que está dirigido el template. |
| `<apellido_alumno>` | Apellido del integrante que elaboró el resumen. |
| `isw` | Ingeniería y Calidad de Software. |
| `tp` | Trabajo Práctico. |
| `tig` | Trabajo de Investigación Grupal. |
| `rg8` | Repositorio Grupo 8. |
| **De cátedra** | Ítem provisto directamente por la cátedra (programa, cronograma, bibliografía, presentaciones, guías). |
| **De producción propia** | Ítem generado por el grupo para aprobar la materia (resúmenes, TPs resueltos, trabajo de investigación). |

---

## 🏷️ Criterio de línea base

Como grupo definimos que la **línea base** se establece cada vez que la cátedra **corrige** un Trabajo Práctico evaluable, estableciendo un punto de referencia en el que los trabajos prácticos están terminados y corregidos.

Cada línea base se marca mediante un **tag de Git** en el repositorio y utiliza la nomenclatura **`v[MAJOR]`**.

- **`MAJOR`** → se incrementa cada vez que se recibe la corrección de un nuevo Trabajo Práctico evaluable. El valor `1` corresponde al estado inicial del repositorio (antes de cualquier corrección).

---

## 📌 Líneas base disponibles

| Versión | Tag de Git | Fecha | Descripción |
|:-------:|:----------:|:-----:|-------------|
| v1 | v.1 | 4/09/2026 | Línea base inicial del repositorio para el TP evaluable 4. |
| v2 | v.2 | 4/09/2026 | Línea base del repositorio para el TP evaluable 4 corregido. |


> _Esta tabla se irá completando a medida que la cátedra corrija cada Trabajo Práctico evaluable._

---

<div align="center">

📚 _Universidad Tecnológica Nacional · Ingeniería de Sistemas de Información · Ingeniería y Calidad de Software · 2026_

</div>
