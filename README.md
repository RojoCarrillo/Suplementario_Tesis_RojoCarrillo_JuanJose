# Material Suplementario de Tesis Doctoral

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Este repositorio alberga el material suplementario, tablas de datos relacionales, niveles de expresión génica y catálogos mutacionales correspondientes a la tesis doctoral de **Juan José Rojo Carrillo**.

El material se proporciona en doble formato:
* **CSV (`.csv`):** Formato de texto plano delimitado por comas para previsualización interactiva directa desde la interfaz de GitHub y procesamiento automatizado por pipelines bioinformáticos.
* **Excel (`.xlsx`):** Formato estructurado para consulta en hojas de cálculo.

---

## Estructura del Repositorio

```text
├── README.md
├── figures/
│   └── Modelo_Celular_Coagulacion.png
├── Capitulo_3/
│   ├── csv/
│   │   ├── Tabla suplementaria 1. Identificación de 1685 genes antisentido en Ensembl.csv
│   │   ├── Tabla suplementaria 2. Identificación de 1556 genes sentido a partir de su gen antisentido.csv
│   │   ├── Tabla suplementaria 3. Tabla relacional de los 1685 genes antisentido con su correspondiente gen sentido.csv
│   │   ├── Tabla suplementaria 4. Genes antisentido que solapan con dos o más genes sentido.csv
│   │   ├── Tabla suplementaria 5. Genes antisentido y su solapamiento respecto a gen sentido.csv
│   │   ├── Tabla suplementaria 6. Relación de los 111 pares de genes antisentido-sentido identificados en hígado humano.csv
│   │   ├── Tabla suplementaria 7. Expresión de los transcritos de los 696 genes sentido que no coexpresaron su correspondiente gen antisentido esperado.csv
│   │   ├── Tabla suplementaria 8. Identificación de 51 transcritos de 40 genes antisentido que no coexpresaron su correspondiente gen sentido.csv
│   │   └── Tabla suplementaria 9. Datos brutos de expresión de los genes nombrados como gen antisentido en TPM.csv
│   └── excel/
│       ├── Tabla suplementaria 1. Identificación de 1685 genes antisentido en Ensembl.xlsx
│       ├── Tabla suplementaria 2. Identificación de 1556 genes sentido a partir de su gen antisentido.xlsx
│       ├── Tabla suplementaria 3. Tabla relacional de los 1685 genes antisentido con su correspondiente gen sentido.xlsx
│       ├── Tabla suplementaria 4. Genes antisentido que solapan con dos o más genes sentido.xlsx
│       ├── Tabla suplementaria 5. Genes antisentido y su solapamiento respecto a gen sentido.xlsx
│       ├── Tabla suplementaria 6. Relación de los 111 pares de genes antisentido-sentido identificados en hígado humano.xlsx
│       ├── Tabla suplementaria 7. Expresión de los transcritos de los 696 genes sentido que no coexpresaron su correspondiente gen antisentido esperado.xlsx
│       ├── Tabla suplementaria 8. Identificación de 51 transcritos de 40 genes antisentido que no coexpresaron su correspondiente gen sentido.xlsx
│       └── Tabla suplementaria 9. Datos brutos de expresión de los genes nombrados como gen antisentido en TPM.xlsx
└── Anexo_1/
    ├── csv/
    │   └── Anexo 1. Relación de 2720 variantes identificadas en el gen F11 según gnomAD.csv
    └── excel/
        └── Anexo 1. Relación de 2720 variantes identificadas en el gen F11 según gnomAD.xlsx
```

---

## Figuras Suplementarias

### Figura 1. Modelo celular de la coagulación sanguínea

![Modelo celular de la coagulación](figures/Modelo_Celular_Coagulacion.png)

> **Leyenda:** Representación esquemática del modelo celular de la coagulación en tres fases solapadas:
> * **(a) Iniciación:** Expresión del Factor Tisular (FT) en la superficie de la célula portadora y ensamblaje del complejo FT-VIIa, catalizando la activación inicial de Factor X (Xa) y Factor IX (IXa). El Xa activa cantidades limitadas de protrombina a trombina (IIa) antes de su inhibición por el inhibidor de la vía del factor tisular (TFPI) y la antitrombina (AT).
> * **(b) Amplificación:** La trombina residual (IIa) promueve la activación plaquetaria, escinde el complejo factor VIII/factor von Willebrand (vWF), y activa a los cofactores V (Va), VIII (VIIIa) y al Factor XI (XIa).
> * **(c) Propagación:** Sobre la membrana de fosfolípidos aniónicos de la plaqueta activada, el Factor XIa optimiza la activación continuada de IX a IXa. Se estructuran los complejos catalíticos de alta afinidad: el **Complejo Tenasa** (VIIIa-IXa, responsable de la generación a gran escala de Xa) y el **Complejo Protrombinasa** (Va-Xa), responsables del estallido masivo (*burst*) de trombina (IIa) indispensable para la generación de fibrina polimérica y la consolidación hemostática.

---

## Capítulo 3: Tablas Suplementarias

| Tabla | Título y Descripción | Vista directa (CSV) | Archivo Excel |
| :--- | :--- | :---: | :---: |
| **Tabla Suplementaria 1** | Identificación de 1685 genes antisentido en Ensembl | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 1. Identificación de 1685 genes antisentido en Ensembl.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 1. Identificación de 1685 genes antisentido en Ensembl.xlsx>) |
| **Tabla Suplementaria 2** | Identificación de 1556 genes sentido a partir de su gen antisentido | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 2. Identificación de 1556 genes sentido a partir de su gen antisentido.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 2. Identificación de 1556 genes sentido a partir de su gen antisentido.xlsx>) |
| **Tabla Suplementaria 3** | Tabla relacional de los 1685 genes antisentido con su correspondiente gen sentido | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 3. Tabla relacional de los 1685 genes antisentido con su correspondiente gen sentido.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 3. Tabla relacional de los 1685 genes antisentido con su correspondiente gen sentido.xlsx>) |
| **Tabla Suplementaria 4** | Genes antisentido que solapan con dos o más genes sentido | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 4. Genes antisentido que solapan con dos o más genes sentido.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 4. Genes antisentido que solapan con dos o más genes sentido.xlsx>) |
| **Tabla Suplementaria 5** | Genes antisentido y su solapamiento respecto a gen sentido | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 5. Genes antisentido y su solapamiento respecto a gen sentido.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 5. Genes antisentido y su solapamiento respecto a gen sentido.xlsx>) |
| **Tabla Suplementaria 6** | Relación de los 111 pares de genes antisentido-sentido identificados en hígado humano | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 6. Relación de los 111 pares de genes antisentido-sentido identificados en hígado humano.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 6. Relación de los 111 pares de genes antisentido-sentido identificados en hígado humano.xlsx>) |
| **Tabla Suplementaria 7** | Expresión de los transcritos de los 696 genes sentido que no coexpresaron su correspondiente gen antisentido esperado | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 7. Expresión de los transcritos de los 696 genes sentido que no coexpresaron su correspondiente gen antisentido esperado.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 7. Expresión de los transcritos de los 696 genes sentido que no coexpresaron su correspondiente gen antisentido esperado.xlsx>) |
| **Tabla Suplementaria 8** | Identificación de 51 transcritos de 40 genes antisentido que no coexpresaron su correspondiente gen sentido | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 8. Identificación de 51 transcritos de 40 genes antisentido que no coexpresaron su correspondiente gen sentido.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 8. Identificación de 51 transcritos de 40 genes antisentido que no coexpresaron su correspondiente gen sentido.xlsx>) |
| **Tabla Suplementaria 9** | Datos brutos de expresión de los genes nombrados como gen antisentido en TPM | [Ver CSV](<Capitulo_3/csv/Tabla suplementaria 9. Datos brutos de expresión de los genes nombrados como gen antisentido en TPM.csv>) | [Descargar XLSX](<Capitulo_3/excel/Tabla suplementaria 9. Datos brutos de expresión de los genes nombrados como gen antisentido en TPM.xlsx>) |

---

## Discusión General: Anexos

| Anexo | Título y Descripción | Vista directa (CSV) | Archivo Excel |
| :--- | :--- | :---: | :---: |
| **Anexo 1** | Relación de 2720 variantes identificadas en el gen *F11* según gnomAD | [Ver CSV](<Anexo_1/csv/Anexo 1. Relación de 2720 variantes identificadas en el gen F11 según gnomAD.csv>) | [Descargar XLSX](<Anexo_1/excel/Anexo 1. Relación de 2720 variantes identificadas en el gen F11 según gnomAD.xlsx>) |

---

## Cómo citar este repositorio

Si utilizas estos datos, tablas o recursos en investigaciones derivadas, por favor cita este trabajo como:

```bibtex
@misc{RojoCarrillo_Tesis_Suplementario_2026,
  author       = {Rojo Carrillo, Juan Jos{\'e}},
  title        = {Material Suplementario: Tesis Doctoral},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.XXXXXXX},
  url          = {[https://doi.org/10.5281/zenodo.XXXXXXX](https://doi.org/10.5281/zenodo.XXXXXXX)}
}
```

---

## Licencia

El material recogido en este repositorio (tablas de datos, catálogos mutacionales, figuras y documentación) está distribuido bajo la licencia **[Creative Commons Reconocimiento 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es)**.

Se autoriza la copia, redistribución, consulta y adaptación del material bajo la condición de proporcionar la atribución correspondiente al autor y el enlace formal al DOI del recurso.
