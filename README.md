# Plantilla No Oficial para Tesis USFQ

Esta es una plantilla LaTeX no oficial para el proyecto de titulación de la
Universidad San Francisco de Quito. Utiliza LuaLaTeX y es compatible con [unicode-math][1]. Por defecto, la plantilla usa la fuente [TeX
Gyre Termes][3] para el texto normal y fórmulas, y [JuliaMono][4]
para el texto monoespaciado. TeX Gyre Termes es un clon de Times New Roman que utilizo porque es compatible nativamente con escritura matemática y porque se ve mucho mejor que Times. Además, permite utilizar unicode-math, que todos deberíamos estar usando de cualquier manera.

Para la bibliografía, recomiendo usar [JabRef][6], que es
de código abierto y bastante completo. Para compilar, sugiero usar
[latexmk][8], para el cual proporciono un archivo latexmkrc.

La última vez que revisé que la plantilla cumplía con los requisitos de
la Biblioteca fue en el **semestre 202410**. Intentaré mantenerla
actualizada. Aun así, siempre deberías verificar los requisitos
[aquí][5].

Gracias a Pablo Padilla Ortiz[^pablo] por proporcionar la versión
original de esta plantilla.

Esta plantilla fue usada exitosamente para componer mi [tesis de
pregrado en Matemáticas][7] en diciembre de 2024 en la USFQ. Si más
personas la usan, puedo agregar una pequeña lista aquí. ¡Por favor
compártela con otros!

## Cómo compilar el documento

### Usando TeX Live (o similares)

Una vez que tengas instalado TeX Live, clona el repositorio. Dentro del repositorio, el siguiente comando debería compilar el documento:

```
latexmk main.tex
```

**Asegúrate de tener la fuente JuliaMono instalada, o en su defecto [sigue estas instrucciones][10].**

### Usando Overleaf

> **NOTA:** Yo recomiendo trabajar la tesis localmente, con git para el manejo de versiones, porque una tesis implica escribir y reescribir el documento varias veces. Herramientas en línea como Overleaf no tienen un buen manejo de versiones y pueden fracasar al compilar documentos grandes como una tesis. Por lo tanto, les recomiento usar una distribución de TeX como [TeX Live][9].

Si quieres usar Overleaf, sube todos los archivos excepto:

- .gitignore
- LICENSE
- README.md
- latexmkrc

Además, asegúrate de seleccionar LuaLaTeX como compilador en el menú desplegable de la izquierda en el documento. Overleaf puede no ser compatible con la fuente JuliaMono. Si te sale un error, [sigue estas instrucciones][10].

[1]: https://ctan.org/pkg/unicode-math
[2]: https://github.com/matze/mtheme
[3]: https://www.gust.org.pl/projects/e-foundry/tex-gyre/termes
[4]: https://juliamono.netlify.app/
[5]: https://www.usfq.edu.ec/es/biblioteca
[6]: https://www.jabref.org/
[7]: http://repositorio.usfq.edu.ec/handle/23000/14173
[8]: https://ctan.org/pkg/latexmk/
[9]: https://tug.org/texlive/
[10]: https://github.com/adricamilo/USFQ-Thesis-Template/wiki/Desactivar-JuliaMono

[^pablo]: Puede que lo conozcas como un creador bastante exitoso
    de memes de matemáticas en Instagram.
