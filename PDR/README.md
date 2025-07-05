# Proyecto LAMBDA - Revisión de Diseño Preliminar

Este repositorio contiene el documento técnico del Proyecto LAMBDA, elaborado en LaTeX.

## 📦 Requisitos

Para compilar correctamente este documento, es necesario tener instalados:

- [`texlive-full`](https://www.tug.org/texlive/) (incluye todos los paquetes necesarios)
- [`biber`](https://ctan.org/pkg/biber) (para procesar la bibliografía con `biblatex`)
- [`latexmk`](https://ctan.org/pkg/latexmk) (automatiza la compilación)

En sistemas basados en Debian/Ubuntu, se pueden instalar con:

```bash
sudo apt update
sudo apt install texlive-full biber latexmk
## 🛠️ Compilación

Para compilar el documento PDF, ejecutá el siguiente comando:

```bash
latexmk -pdf main.tex

