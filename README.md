# FORM-FB-01 · Fichas bibliográficas

Actividad formativa individual de Aplicaciones Distribuidas (ISR-701), UTEQ. Semana 2, del 2 al 8 de noviembre de 2026. Prepara el informe TA-IND-01.

**Estudiante:** Melanie Michelle Muñoz Vera.

## Archivos

- [Fichas en PDF](docs/fichas.pdf)
- [Fuente LaTeX](docs/fichas.tex)
- [Bibliografía BibLaTeX](docs/referencias.bib)

Esta versión contiene cinco fuentes verificadas y un dato localizado por fuente. Incluye los resúmenes y las notas personales aportados por la estudiante.

## Compilación

Archivo principal: `docs/fichas.tex`. Compilador: `pdfLaTeX`. Motor bibliográfico: `Biber`.

Instala TeX Live o MiKTeX con `biber`, `biblatex`, `biblatex-ieee`, `babel` para español, `geometry`, `microtype`, `csquotes`, `xcolor` y `hyperref`. Desde la raíz del repositorio, ejecuta:

```sh
cd docs
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
