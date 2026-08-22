<div align="center">

# 📘 REPOSITORIO_GRUPO_8

### Ingeniería y Calidad de Software · Grupo 8 · 2026

Repositorio grupal de la cátedra: materiales de clase, trabajos prácticos,
trabajos de investigación y gestión de configuración del software (SCM).

![Grupo](https://img.shields.io/badge/Grupo-8-success)
![Año](https://img.shields.io/badge/A%C3%B1o-2026-informational)
![Integrantes](https://img.shields.io/badge/Integrantes-15-orange)
![Última línea base](https://img.shields.io/badge/L%C3%ADnea%20base-Sin%20establecer-lightgrey)

</div>

---

## 📑 Tabla de contenidos

- [👥 Integrantes del equipo](#-integrantes-del-equipo)
- [🗂️ Estructura del repositorio](#️-estructura-del-repositorio)
- [⚙️ Ítems de configuración](#️-ítems-de-configuración)
- [📖 Glosario](#-glosario)
- [🏷️ Criterio de línea base](#️-criterio-de-línea-base)
- [📌 Líneas base disponibles](#-líneas-base-disponibles)

---

## 👥 Integrantes del equipo

| # | Integrante | Legajo |
|:-:|------------|:------:|
| 1 | Alabe, Ulises | 91166 |
| 2 | Dapuez, Eliseo | 91625 |
| 3 | Abaca, Valentina | 97884 |
| 4 | De Goycoechea, Mateo | 85203 |
| 5 | Mercado, Lucas | 82904 |
| 6 | Bencivenga, Carlos Martin | 97244 |
| 7 | Blanco, Lisandro | 60634 |
| 8 | Malizia Pacheco, Matias | 407901 |
| 9 | Sánchez, Francisco | 90183 |
| 10 | Sosa, Mateo | 97716 |
| 11 | Barzola, Augusto | 59247 |
| 12 | Pacheco, Agustin | 92779 |
| 13 | Popoff, Agustin | 88588 |
| 14 | Pahud, Fernando | 61175 |
| 15 | Amado, Marco | 57572 |

---

## 🗂️ Estructura del repositorio

```text
└── REPOSITORIO_GRUPO_8
    ├── 📁 Catedra/
    │   ├── 📁 Informacion_de_catedra/
    │   ├── 📁 Practico/
    │   └── 📁 Teorico/
    │       ├── 📁 Bibliografia/
    │       └── 📁 Presentaciones_de_clase/
    │
    ├── 📁 Material_propio/
    │   ├── 📁 Resumenes/
    │   ├── 📁 Trabajos_practicos/
    │   │   ├── 📁 TP1/
    │   │   ├── 📁 TP2/
    │   │   └── 📁 TP<N>/
    │   └── 📁 Trabajos_Investigacion_Grupal/
    │
    └── 📄 README.md
```

---

## ⚙️ Ítems de configuración

Cada ítem de configuración se clasifica en una de tres categorías:

- **De cátedra**: material provisto directamente por la cátedra que no corresponde a una clase puntual (programa, cronograma, bibliografía, etc.).
- **De clase**: material vinculado a las clases teóricas y prácticas dictadas (presentaciones, guías, teoría, práctica).
- **De producción propia**: material generado por el grupo para aprobar la materia (resúmenes, TPs resueltos, trabajo de investigación).

| Ítem de configuración | Tipo | Regla de nombrado | Ubicación física |
|------------------------|------|-------------------|------------------|
| Programa de la asignatura | De cátedra | `Programa_Asignatura_ISW_2026.pdf` | `REPOSITORIO_GRUPO_8/Catedra/Informacion_de_catedra/` |
| Cronograma de cursada | De cátedra | `Cronograma_ISW_2026.pdf` | `REPOSITORIO_GRUPO_8/Catedra/Informacion_de_catedra/` |
| Bibliografía | De cátedra | `<Nombre_Material>-<Nombre_Autor>-<Año>.pdf` | `REPOSITORIO_GRUPO_8/Catedra/Teorico/Bibliografia/` |
| Presentaciones de clase | De clase | `<N>_<Nombre_Tema>.pdf` | `REPOSITORIO_GRUPO_8/Catedra/Teorico/Presentaciones_de_clase/` |
| Material práctico (guías, enunciados de la cátedra) | De clase | `Guia_TP<N>_<Nombre_Tema>.pdf` | `REPOSITORIO_GRUPO_8/Catedra/Practico/` |
| Templates para ejercicios | De cátedra | `Template_<Nombre_Ejercicio>.docx` | `REPOSITORIO_GRUPO_8/Catedra/Practico/` |
| Resúmenes propios del grupo | De producción propia | `Resumen_<Nombre_Tema>_<Apellido_Alumno>.<Extension>` | `REPOSITORIO_GRUPO_8/Material_propio/Resumenes/` |
| Trabajos prácticos resueltos por el grupo | De producción propia | `TP<N>_<Nombre_Tema>_G8.<Extension>` | `REPOSITORIO_GRUPO_8/Material_propio/Trabajos_practicos/TP<N>/` |
| Trabajo de Investigación Grupal | De producción propia | `TIG_<Nombre_Tema>_G8.<Extension>` | `REPOSITORIO_GRUPO_8/Material_propio/Trabajos_Investigacion_Grupal/` |

---

## 📖 Glosario

| Sigla / Placeholder | Significado |
|---------------------|-------------|
| `<N>` | Número incremental que identifica el Trabajo Práctico o el orden del material. Ej: `01`, `02`, etc. |
| `<Nombre_Tema>` | Nombre o título del tema correspondiente al material o trabajo práctico. |
| `<Nombre_Material>` | Nombre o título del libro/paper de bibliografía. |
| `<Nombre_Autor>` | Nombre del autor del material de bibliografía. |
| `<Año>` | Año de publicación del material de bibliografía. |
| `<Nombre_Ejercicio>` | Nombre o especificación del ejercicio al que está dirigido el template. |
| `<Apellido_Alumno>` | Apellido del integrante que elaboró el resumen. |
| `<Extension>` | Extensión del archivo; puede variar de formato. Ej: `.pdf`, `.docx`, `.xlsx`, `.pptx`, etc. |
| `ISW` | Ingeniería y Calidad de Software. |
| `TP` | Trabajo Práctico. |
| `TIG` | Trabajo de Investigación Grupal. |
| `G8` | Grupo 8. |
| **De cátedra** | Ítem provisto por la cátedra, no ligado a una clase puntual (programa, cronograma, bibliografía). |
| **De clase** | Ítem vinculado a las clases teóricas y prácticas dictadas (presentaciones, guías). |
| **De producción propia** | Ítem generado por el grupo para aprobar la materia (resúmenes, TPs resueltos, trabajo de investigación). |

---

## 🏷️ Criterio de línea base

Como grupo definimos que la **línea base** se establece cada vez que la cátedra **corrige** un Trabajo Práctico evaluable, estableciendo un punto de referencia en el que los trabajos prácticos están terminados y corregidos.

Cada línea base se marca mediante un **tag de Git** en el repositorio y utiliza la nomenclatura **`v[MAJOR].[MINOR]`**, donde:

- **`MAJOR`** → se incrementa cada vez que se recibe la corrección de un nuevo Trabajo Práctico evaluable. El valor `1` corresponde al estado inicial del repositorio (antes de cualquier corrección).
- **`MINOR`** → se incrementa si sobre esa misma corrección se realizan ajustes o ampliaciones adicionales antes de recibir una nueva corrección de otro TP.

---

## 📌 Líneas base disponibles

| Versión | Tag de Git | Fecha | Descripción |
|:-------:|:----------:|:----------:|-------------|
| `v1.0` | `v1.0` | _pendiente_ | Línea base inicial del repositorio, creada por la corrección del TP evaluable 4 (SCM). |

> _Esta tabla se irá completando a medida que la cátedra corrija cada Trabajo Práctico evaluable._

---

<div align="center">

📚 _Universidad Tecnológica Nacional · Ingeniería y Calidad de Software · 2026_

</div>
