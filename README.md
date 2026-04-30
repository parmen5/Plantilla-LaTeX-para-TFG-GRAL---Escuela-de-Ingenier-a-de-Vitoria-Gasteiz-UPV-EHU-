# Plantilla para la memoria de un TFG

Plantilla para la creación del Trabajo de Fin de Grado siguiendo la normativa de la Escuela de Ingeniería de Vitoria-Gasteiz (UPV/EHU) y la [guía de expresión de marca de la UPV/EHU](https://www.ehu.eus/documents/10136/3950780/GUIA_EXPRESION_UPV_es.pdf/4d538337-2577-4260-ae02-d0fed29a26b5).

> [!IMPORTANT]
> Se recomienda usar XeLaTeX como compilador para que las fuentes oficiales se carguen correctamente.

## Personalización de la portada

En el archivo `main.tex` se deben introducir los datos de la portada del TFG:

```latex
% ------------------------------------------------------------ %
% DATOS DEL DOCUMENTO                                          %
% ------------------------------------------------------------ %

% Título:
\newcommand{\titulo}{<Título del trabajo>}
% Curso académico:
\newcommand{\curso}{<XXXX-XXXX>}
% Carrera:
\newcommand{\carrera}{Grado en XXXXXXXX}
% Alumno/Alumna:
\newcommand{\alumno}{<apellido 1, apellido 2, nombre>}
% Dirección 1 del TFG:
\newcommand{\direccionA}{<apellido 1, apellido 2, nombre>}
% Dirección 2 del TFG (si no la hay, comentar la línea aquí y también en preamble.tex):
\newcommand{\direccionB}{<apellido 1, apellido 2, nombre>}
% Fecha:
\newcommand{\fecha}{<XXXX, día, mes, año>}
% ------------------------------------------------------------ %
