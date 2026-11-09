# CV · Maicel E. Monzón-Pérez

Plantilla `pagedown::html_resume` (la misma del CV anterior), con fuente única en R Markdown.

```r
rmarkdown::render("cv_wfp_en.Rmd")          # → cv_wfp_en.html
pagedown::chrome_print("cv_wfp_en.html")    # → cv_wfp_en.pdf (usa Chrome/Chromium; sin conexión)
```

| Archivo | Variante | Uso |
|---|---|---|
| `cv_wfp_en.Rmd` | L1 delante (encuestas, nutrición, fortificación) | WFP, UNICEF, FAO, GAIN, GNC |
| _pendiente_ `cv_trials_en.Rmd` | L2 delante (ensayos clínicos, regulación) | OPS/OMS, CRO, freelance |

Estilo: `custom.css` (colores y ancho de la barra lateral). Foto: `photo.jpg`.
Fechas y títulos: tomados de bioestadisticaedu.com/experience (fuente de verdad).

## Por confirmar antes de enviar
- [ ] Nivel de inglés (hoy: «working knowledge») y de portugués («basic»).
- [ ] Título exacto del puesto WFP (hoy: «Consultant, Programme Policy (Nutrition)»).
- [ ] Que el CV quepa en 2 páginas al imprimir; si no, quitar la última publicación.
