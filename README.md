# FORM-FB-01 · Fichas bibliográficas

Fundamentos de sistemas distribuidos y arquitecturas distribuidas. Aplicaciones Distribuidas (ISR-701), UTEQ.

Semana 2, del 2 al 8 de noviembre de 2026. Actividad preparatoria para TA-IND-01.

## Integrantes y entregas

| Integrante | Archivos | PDF |
|---|---|---|
| Melanie Michelle Muñoz Vera | [Carpeta](docs/melanie-munoz/) | [Ver fichas](docs/melanie-munoz/fichas.pdf) |
| Steffanny del Rocío Loor Suárez | [Carpeta](docs/rocio-loor/) | [Ver fichas](docs/rocio-loor/fichas-steffanny-loor.pdf) |
| Dayver Yahir Rivas Piloso | [Carpeta](docs/dayver-rivas/) | Pendiente |

Cada integrante guarda su investigación, el archivo LaTeX, la bibliografía y el PDF en su carpeta de `docs/`.

## Compilación

Se necesita TeX Live o MiKTeX con pdfLaTeX, Biber, `biblatex`, `biblatex-ieee`, `babel` para español, `csquotes`, `geometry` y `hyperref`.

| Carpeta | Archivo principal | Bibliografía |
|---|---|---|
| `docs/melanie-munoz/` | `fichas.tex` | `referencias.bib` |
| `docs/rocio-loor/` | `fichas-steffanny-loor.tex` | `loor.bib` |

Desde la carpeta de la entrega, ejecuta estos comandos. Sustituye `nombre` por el nombre del archivo principal sin `.tex`.

```sh
pdflatex -interaction=nonstopmode -halt-on-error nombre.tex
biber nombre
pdflatex -interaction=nonstopmode -halt-on-error nombre.tex
pdflatex -interaction=nonstopmode -halt-on-error nombre.tex
```

Las referencias y la declaración de uso de IA se presentan en los documentos de cada entrega.
