# 🎵 Auditoría Musicológica Forense y Perfilamiento Conductual de Preferencias Sonoras (N = 210 Pistas)


**Autores:** Steven & Jairo  
**Unidad Académica:** Proyecto de Ciencia de Datos y Programación Aplicada (Primer Semestre)  
**Edición del Expediente:** Ed. 4.4 Definitiva (Cierre Consolidado)  

---

## 📌 1. Descripción General del Informe

Este repositorio contiene el desarrollo computacional y documental de una **Auditoría Musicológica Forense** aplicada sobre un catálogo digital real exportado desde Spotify, compuesto por **`N = 210` pistas activas** y un universo comparado de **180 artistas y agrupaciones**.

A través de técnicas de análisis exploratorio de datos (EDA), extracción de telemetría acústica de Spotify (`Energy`, `Valence`, `Acousticness`, `Instrumentalness`, `Danceability`, `Tempo`) y clasificación heurística en **Python**, el proyecto transforma preferencias musicales subjetivas en métricas cuantitativas auditables y reproducibles.

---

## 🎯 2. ¿Por qué se realiza este estudio? (Objetivo del Proyecto)

### Objetivo General
Evaluar cuantitativa y cualitativamente la coherencia acústica, estructural y conductual de una biblioteca musical personalizada, demostrando cómo la programación en Python permite modelar criterios humanos de selección artística bajo estándares científicos (APA 7.ª edición).

### Justificación y Propósito Académico
1. **Convergencia de Criterios Evaluadores (Modelo Dual):**  
   Basado en la teoría de correlación entre personalidad y preferencias musicales de *Rentfrow & Gosling (2003)*, el proyecto busca resolver la tensión entre dos perfiles de escucha distintos mediante un sistema de puntuación ponderado:
   - **Eje Evaluador 1 — Steven (`97.0 / 100`):** Evalúa la cohesión melódica, la carga emocional, el "pacifismo sonoro" y el valor de la memoria formativa (infancia/adolescencia).
   - **Eje Evaluador 2 — Jairo (`93.0 / 100`):** Evalúa la complejidad armónica, la instrumentación orgánica/orquestal (*score* de cine, videojuegos y música clásica) y la ausencia de estridencia comercial.
2. **Depuración y Trazabilidad Longitudinal:**  
   El estudio documenta la evolución de la muestra desde una línea base sin depurar (`Ed. 3.4: 66.5 / 100`) hasta alcanzar un catálogo depurado de excelencia (`Ed. 4.4: 95.0 / 100`), aplicando reglas explícitas de inclusión, excepciones funcionales/familiares y veto estricto.
3. **Aplicación Práctica de Ciencia de Datos:**  
   Demuestra el dominio de estructuras de datos tabulares (`pandas`), cálculo vectorial (`numpy`) y visualización estadística (`matplotlib`) en un caso de estudio real, verificable y replicable.

---

## 📊 3. Resultados Consolidados y Taxonomía Forense

El análisis sobre las **210 pistas activas** arroja un **Veredicto Final Consolidado de `95.0 / 100` (`9.5 / 10` — Hall of Fame Absoluto)**:

| Dimensión / Categoría Forense | Cantidad de Pistas | Porcentaje (%) | Puntaje Obtenido | Criterio Técnico y Conductual |
| :--- | :---: | :---: | :---: | :--- |
| **Hall of Fame (Pop / Rock / Synth)** | `112` | `53.3 %` | `98.5 / 100` | Consenso vocal, melódico y retro de élite (Lady Gaga, Michael Jackson, Linkin Park, Britney Spears, Daft Punk, 009 Sound System). |
| **Hall of Fame (Consolidado)** | `48` | `22.9 %` | `94.8 / 100` | Sostén melódico de los 80s/90s/2000s, eurodance clásico, rock alternativo y bandas sonoras formativas. |
| **Zona Gris / Excepción Acotada** | `29` | `13.8 %` | `90.2 / 100` | Excepciones justificadas por entorno familiar (salsa/vallenato clásico), nostalgia de infancia o uso funcional (ejercicio/aseo). |
| **Hall of Fame (Élite Clásica / Score)** | `21` | `10.0 %` | `97.8 / 100` | Cima compositiva e instrumental pura (Bach, Wagner, Beethoven, Vivaldi, Hans Zimmer, John Williams, *Metroid Prime*, *Zelda*). |
| **Lista Negra (Veto Absoluto)** | `0` | `0.0 %` | `0.0 / 100` | Erradicación total del circuito urbano comercial estridente en el catálogo auditado. |
| **TOTAL CONSOLIDADO** | **`210`** | **`100.0 %`** | **`95.0 / 100`** | **Eje Steven: `97.0` • Eje Jairo: `93.0`** |

---

## 📁 4. Estructura del Repositorio

```text
auditoria-musicologica-spotify/
├── data/
│   └── playlist_auditada_210.csv                  # Dataset real exportado de Spotify (N = 210 pistas)
├── docs/
│   └── Dictamen_Pericial_Consolidado_Ed4_4.pdf    # Informe pericial formal en PDF (Normas APA 7.ª Ed.)
├── notebooks/
│   └── Auditoria_Musicologica_Forense_Ed4_4.ipynb # Cuaderno interactivo con código y gráficas renderizadas
├── src/
│   └── auditor_musical.py                         # Script modular en Python para ejecución por consola
├── requirements.txt                               # Dependencias del proyecto
└── README.md                                      # Documentación principal del repositorio
```

---

## 🚀 5. Instrucciones de Ejecución

### Opción A: Visualización directa en GitHub
Abre el archivo `notebooks/Auditoria_Musicologica_Forense_Ed4_4.ipynb` directamente desde la interfaz web de GitHub para inspeccionar el código paso a paso, las tablas estadísticas y las gráficas periciales ya renderizadas.

### Opción B: Ejecución local en tu computador
```bash
# 1. Clonar el repositorio
git clone https://github.com
cd auditoria-musicologica-spotify

# 2. Instalar las librerías necesarias
pip install -r requirements.txt

# 3. Ejecutar el motor de auditoría
python src/auditor_musical.py
```

---

## 📚 6. Referencias Bibliográficas (APA 7.ª Edición)

* American Psychological Association. (2020). *Publication manual of the American Psychological Association* (7.ª ed.). https://doi.org
* Jairo, & Steven. (2026). *Auditoría musicológica forense y depuración de biblioteca digital en Spotify (N = 210)* [Archivo de registro documental y dictamen pericial Ed. 4.4]. Laboratorio de Perfilamiento Conductual y Curaduría Auditiva.
* Rentfrow, P. J., & Gosling, S. D. (2003). The do re mi's of everyday life: The structure and personality correlates of music preferences. *Journal of Personality and Social Psychology*, 84(6), 1236–1256. https://doi.org
