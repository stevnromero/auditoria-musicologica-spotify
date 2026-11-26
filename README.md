# 🎵 Auditoría Musicológica Forense de Preferencias Sonoras (N = 231 Pistas)

**Autores:** Steven & Jairo  
**Unidad Académica:** Proyecto de Ciencia de Datos y Programación Aplicada (Primer Semestre)  
**Versión del Expediente:** Edición 4.5 Definitiva (Cierre Consolidado — 26 de noviembre de 2026)  

---

## 📌 1. Propósito y Alcance del Estudio

Este repositorio documenta el análisis computacional y estadístico de una biblioteca musical real exportada desde Spotify (**`N = 231` pistas activas** y **`n = 184` artistas auditados**). 

El proyecto aplica técnicas de análisis exploratorio de datos (EDA), vectores acústicos de Spotify (`Energy`, `Valence`, `Acousticness`, `Instrumentalness`, `Danceability`, `Tempo`) y clasificación heurística en **Python** (`pandas`, `numpy`, `matplotlib`) bajo estándares **APA (7.ª edición)** para evaluar cuantitativamente la convergencia entre dos perfiles de escucha basados en el modelo de *Rentfrow & Gosling (2003)*:

* **Eje Evaluador 1 — Steven (`97.6 / 100`):** Cohesión melódica, carga emocional y memoria formativa (infancia/adolescencia).
* **Eje Evaluador 2 — Jairo (`94.2 / 100`):** Complejidad estructural, instrumentación clásica/orquestal (*score* de cine y videojuegos), electrónica retro y rechazo al circuito comercial estridente.

---

## 📊 2. Resultados Consolidados (Edición 4.5 Definitiva)

Tras la incorporación de **21 nuevas pistas** el 26 de noviembre de 2026 (bandas sonoras de *Alan Silvestri*, *Metroid*, *The Legend of Zelda*, *Super Mario*, electrónica clásica/*French House* de *Daft Punk*, *Gigi D'Agostino* y *Mauro Picotto*, más pop/rap rock formativo) y la depuración definitiva de exponentes urbanos (erradicación total de *Karol G* y *Manuel Turizo*, manteniendo a *Feid* acotado a 2 excepciones melódicas), el catálogo alcanza un **Veredicto Global de `95.9 / 100` (`9.6 / 10` — Hall of Fame Absoluto)**:

| Categoría Taxonómica | Pistas (`n`) | Porcentaje (%) | Puntaje Promedio | Criterio de Validación |
| :--- | :---: | :---: | :---: | :--- |
| **Hall of Fame (Élite Clásica / Score)** | `28` | `12.1 %` | `98.0 / 100` | Obras académicas (Bach, Wagner, Beethoven, Vivaldi) y bandas sonoras (*Silvestri*, *Zimmer*, *Williams*, *Metroid*, *Zelda*). |
| **Hall of Fame (Pop / Rock / Synth)** | `121` | `52.4 %` | `96.7 / 100` | Núcleo vocal y electrónico de élite (Lady Gaga, Michael Jackson, Linkin Park, Britney Spears, Daft Punk, Gigi D'Agostino). |
| **Hall of Fame (Consolidado)** | `48` | `20.8 %` | `95.4 / 100` | Sostén melódico retro (80s/90s/2000s), eurodance clásico y rock alternativo. |
| **Zona Gris / Excepción Acotada** | `34` | `14.7 %` | `90.6 / 100` | Entorno familiar (salsa y vallenato clásico), nostalgia infantil y uso funcional (ejercicio/aseo). |
| **Lista Negra (Veto Absoluto)** | `0` | `0.0 %` | `0.0 / 100` | Ausencia total de reguetón, trap, guaracha y despecho comercial estridente. |
| **TOTAL CONSOLIDADO** | **`231`** | **`100.0 %`** | **`95.9 / 100`** | **Incremento neto de `+29.4 pts` frente a la línea base (`Ed. 3.4: 66.5`)** |

---

## 📁 3. Estructura del Repositorio

```text
auditoria-musicologica-spotify/
├── data/
│   └── playlist_auditada_231.csv                  # Dataset definitivo exportado de Spotify (N = 231 pistas)
├── docs/
│   └── Dictamen_Pericial_Playlist_Ed_4_5-v2.pdf   # Informe pericial formal en PDF (Normas APA 7.ª Ed.)
├── notebooks/
│   └── Auditoria_Musicologica_Forense_Ed4_5.ipynb # Cuaderno interactivo con código y figuras APA
├── src/
│   └── auditor_musical.py                         # Script modular en Python para auditoría por consola
├── requirements.txt                               # Dependencias del entorno (pandas, numpy, matplotlib)
└── README.md                                      # Documentación principal del proyecto
```

---

## 🚀 4. Guía Rápida de Ejecución

### En Google Colab o GitHub
Abre `notebooks/Auditoria_Musicologica_Forense_Ed4_5.ipynb` para visualizar las tablas estadísticas y figuras renderizadas, o súbelo a **Google Colab** cargando el archivo `data/playlist_auditada_231.csv`.

### En entorno local
```bash
git clone https://github.com
cd auditoria-musicologica-spotify
pip install -r requirements.txt
python src/auditor_musical.py
```

---

## 📚 5. Referencias (APA 7.ª Edición)

American Psychological Association. (2020). *Publication manual of the American Psychological Association* (7.ª ed.). https://doi.org

Jairo, & Steven. (2026). *Auditoría musicológica forense y depuración de biblioteca digital en Spotify (N = 231)* [Archivo de registro documental y dictamen pericial Ed. 4.5 Definitiva]. Laboratorio de Perfilamiento Conductual y Curaduría Auditiva.

Rentfrow, P. J., & Gosling, S. D. (2003). The do re mi's of everyday life: The structure and personality correlates of music preferences. *Journal of Personality and Social Psychology*, *84*(6), 1236–1256. https://doi.org
