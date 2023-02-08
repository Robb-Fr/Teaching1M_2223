# Teaching 1M3

This repository contains some of the files that I created for teaching to first year Maturity school following the new Computer Science program. See [Modulo project](https://modulo-info.ch/) for the main source.

## tex-slides

You can find the [slides1M3.tex](tex-slides/slides1M3.tex) file that contains the slides document.

By commenting and uncommenting the lines of the header, you can adapt the rendering after pdflatex compilation.

```tex
\documentclass{beamer}
%\documentclass[handout]{beamer}
%\includeonlyframes{current}
%\includeonlylecture{week-XX}
```

Renders the full slides set with the overlay animations.

```tex
%\documentclass{beamer}
\documentclass[handout]{beamer}
%\includeonlyframes{current}
%\includeonlylecture{week-XX}
```

Renders the full slides set but cancels the overlay animations and just renders the final slides.

```tex
\documentclass{beamer}
%\documentclass[handout]{beamer}
%\includeonlyframes{current}
\includeonlylecture{week-XX}
```

Renders the full slides set with the overlay animations and includes only the slides of lecture XX (tagged by the `\lecture{}{week-XX}` in the source code).

## evaluations

The [evaluations](/evaluations) folder contains the evaluations proposed to students.
