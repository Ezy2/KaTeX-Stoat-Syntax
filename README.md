# KaTeX-Stoat
some help for the katex syntax in stoat.chat

# Basics

The start and the end of your word should start with $$. 

ex. `$$\color{red} test$$`

KaTeX is also meant for math so it is a little weird to use and will be italic by default

The prefix for it is a backslash '\' 

## Size and Colour

### \big, \Big, \bigg, \Bigg

#### Types:
  - \big (/[
  - \Big (/[
  - \bigg (/[
  - \Bigg (/[


They only support using a parenthesis or a bracket

### \color

#### Types:
  - \color{color} text

the {colour} argument supports html predefined colours and hexadecimal colours

ex. `$$\color{red} text$$ or $$\color{#ffffff} text$$`

### \huge, \tiny,

#### Types:
  - \huge text
  - \tiny text

\huge and \tiny support using text after

ex. `$$\tiny text$$`


## Fonts

#### Types:
  - \textsf
  - \mathbb text
  - \mathcal text
  - \mathfrak text
  - \mathbf text
  - \mathsf text
  - \mathtt text
  - \mathrm text
  - \mathit text

Now remember KaTeX is for *math* 

fonts:
  - \textsf text
  - \mathbb text
  - \mathcal text
  - \mathfrak text
  - \mathbf text
  - \mathsf text
  - \mathtt text
  - \mathrm text
  - \mathit text

`$$\textsf {text}$$`

