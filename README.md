# Nacidos Vivos en Argentina 2024 — Análisis Exploratorio

**Trabajo Práctico Grupal · Laboratorio de Métodos Cuantitativos Aplicados a la Gestión**
Tecnicatura Universitaria en Gestión y Análisis de Datos en Organizaciones · FCE UBA · 1er Cuatrimestre 2026

---

## Integrantes

| Nombre completo | N.º de registro |  GitHub  |
|-----------------|-----------------|----------|
| Chiara Tundis   | 921264          | @ctundis |


---

## Dataset

**Fuente:** Ministerio de Salud de la Nación Argentina — Estadísticas Vitales  
**Archivo:** `datos_sobre_nacidos_vivos_2024.csv`  
**Período:** Año 2024  
**Registros:** ~21.966 filas agregadas  
**Diccionario de datos:** `descnac.xlsx`

### Variables

| Variable   | Descripción                                              |
|------------|----------------------------------------------------------|
| `PROVRES`  | Provincia de residencia habitual de la madre             |
| `TIPPARTO` | Tipo de parto (simple, múltiple, sin especificar)        |
| `SEXO`     | Sexo del nacido vivo                                     |
| `IMEDAD`   | Intervalo de edad de la madre                            |
| `ITIEMGEST`| Intervalo de tiempo de gestación (en semanas)            |
| `IMINSTRUC`| Máximo nivel de instrucción alcanzado por la madre       |
| `IPESONAC` | Intervalo de peso al nacer (en gramos)                   |
| `CUENTA`   | Cantidad de nacidos vivos                                |

---

## Pregunta de investigación

> *¿existe relación entre el nivel educativo de la madre y la natalidad adolescente por provincia en Argentina durante 2024?*

---

## Estructura del repositorio

```
.
├── datos_sobre_nacidos_vivos_2024.csv   # Dataset principal
├── descnac.xlsx                          # Diccionario de datos
├── notebook.ipynb                        # Análisis en Python (Google Colab)
├── informe.pdf                           # Informe académico
├── presentacion/                         # Diapositivas (PDF)
└── README.md
```
---
