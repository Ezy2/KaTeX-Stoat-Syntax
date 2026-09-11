# KaTeX-Stoat
some help for the katex syntax in stoat.cat

# Basics

The start and the end of your word should start with $$. 

ex. `$$\color{red} test$$`

KaTeX is also meant for math so it is a little weird to use and will be italic by default

The prefix for it is a backslash '\' 

## Types

No Arguments:
  - \huge text
  - \tiny text
  - \big (/[
  - \Big (/[
  - \bigg (/[
  - \Bigg (/[
  - \textsf

One Argument:
  - \color{color} text

### \big, \Big, \bigg, \Bigg

They only support using a parenthesis or a bracket

### \color

the {colour} argument supports html predefined colours and hexadecimal colours

ex. `$$\color{red} text$$ or $$\color{#ffffff} text$$`

### \huge, \tiny

\huge and \tiny support using text after

ex. `$$\tiny text$$`


## Fonts

Stoat does not support many fonts but to remove the italic you can do

`$$\textsf {text}$$`
