# USFQ Thesis Template

This is a LaTeX template for the capstone project at Universidad
San Francisco de Quito. It uses LuaLaTeX and supports
[unicode-math][1]. By default, the template will use the [TeX
Gyre Termes][3] font for normal and math text, and [JuliaMono][4]
for monospaced text. TeX Gyre Termes is a Times New Roman clone.
I used it because it supports writing math and it just looks so
much better than Times. Also, it supports unicode-math, which
everyone should be using anyway.

For bibliography, I recommend using [JabRef][6], which is
open-source and quite complete. For compilation, I suggest using
[latexmk][8], for which I provide a latexmkrc file.

Last time I checked the template met the Biblioteca requirements
was for the **202410 semester**. I will try to keep it up to
date. Still, you should always double check the requirements
[here][5].

I will eventually add my tweaked [Metropolis][2] beamer template.

Thanks to Pablo Padilla Ortiz[^pablo] for providing the original
version of this template.

This template was successfully used to typeset my [Math undergrad
thesis][7] in December 2024 at USFQ. If more people use it, I can
add a little list here. Please share it with others!

## Getting it to compile

I recommend using TeX Live. Once you have it installed, clone the
repo. Inside the repo, the following command should compile the
document:

```
latexmk main.tex
```

Make sure you have the JuliaMono font installed. If you want to
use Overleaf, you should upload everything except:

- .gitignore
- LICENSE
- README.md
- latexmkrc

Make sure you select LuaLaTeX as the compiler.

[1]: https://ctan.org/pkg/unicode-math
[2]: https://github.com/matze/mtheme
[3]: https://www.gust.org.pl/projects/e-foundry/tex-gyre/termes
[4]: https://juliamono.netlify.app/
[5]: https://www.usfq.edu.ec/es/biblioteca
[6]: https://www.jabref.org/
[7]: http://repositorio.usfq.edu.ec/handle/23000/14173
[8]: https://ctan.org/pkg/latexmk/

[^pablo]: You may know him as a rather successful math memes
    creator.

