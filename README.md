# FORM-FB-01 · Fichas bibliográficas

Actividad formativa individual de Aplicaciones Distribuidas (ISR-701), UTEQ. Semana 2, del 2 al 8 de noviembre de 2026. Prepara el informe TA-IND-01.

## Integrantes y entregas

Cada integrante publica sus propias fichas en una carpeta de `docs/`. Los archivos LaTeX, la bibliografía y el PDF de cada entrega van juntos.

| Integrante | Carpeta | PDF |
|---|---|---|
| Melanie Michelle Muñoz Vera | [`docs/melanie-munoz/`](docs/melanie-munoz/) | [Fichas de Melanie](docs/melanie-munoz/fichas.pdf) |
| Steffanny del Rocío Loor Suárez | [`docs/rocio-loor/`](docs/rocio-loor/) | Pendiente |
| Dayver Yahir Rivas Piloso | [`docs/dayver-rivas/`](docs/dayver-rivas/) | Pendiente |

Para subir tu trabajo desde GitHub, abre tu carpeta y elige **Add file → Upload files**. Sube tus archivos desde tu propia cuenta para que tu aporte aparezca con tu usuario en el historial.

## Archivos de Melanie

- [Fichas en PDF](docs/melanie-munoz/fichas.pdf)
- [Fuente LaTeX](docs/melanie-munoz/fichas.tex)
- [Bibliografía BibLaTeX](docs/melanie-munoz/referencias.bib)

Esta versión contiene cinco fuentes verificadas y un dato localizado por fuente. Incluye los resúmenes y las notas personales aportados por la estudiante.

## Compilación

Para las fichas de Melanie, el archivo principal es `docs/melanie-munoz/fichas.tex`. Compilador: `pdfLaTeX`. Motor bibliográfico: `Biber`.

Instala TeX Live o MiKTeX con `biber`, `biblatex`, `biblatex-ieee`, `babel` para español, `geometry`, `microtype`, `csquotes`, `xcolor` y `hyperref`. Desde la raíz del repositorio, ejecuta:

```sh
cd docs/melanie-munoz
pdflatex -interaction=nonstopmode -halt-on-error fichas.tex
biber fichas
pdflatex -interaction=nonstopmode -halt-on-error fichas.tex
pdflatex -interaction=nonstopmode -halt-on-error fichas.tex
```

## Verificación de las fuentes

Los DOI se abrieron y se cotejaron con Crossref y la publicación. Los artículos de Springer usan números de artículo, no rangos de páginas. *IEEE Access* registra el volumen 10 sin número de fascículo para el artículo seleccionado.

- [Empirical Software Engineering, índices de la revista](https://link.springer.com/journal/10664)
- [IEEE Access, índices de la revista](https://ieeeaccess.ieee.org/about/bibliometrics/)
- [Designing Distributed Systems, segunda edición digital](https://www.oreilly.com/library/view/designing-distributed-systems/9781098156343/)
- [Designing Data-Intensive Applications, segunda edición digital](https://www.oreilly.com/library/view/designing-data-intensive/9781098119058/)
