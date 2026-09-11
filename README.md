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
  - \tiny text
  - \LARGE text
  - \huge text

\huge and \tiny support using text after

ex. `$$\tiny text$$`


## Fonts

Now remember KaTeX is for *math* so the fonts arent normal ones

#### Types:
  - \textsf text (normal)
  - \mathbb text (blackboard bold)
  - \mathcal text (calligraphic)
  - \mathfrak text (fraktur (gothic))
  - \mathbf text (bold)
  - \mathsf text (sans serif)
  - \mathtt text (typewriter (monspace))
  - \mathrm text (roman)
  - \mathit text (italic)

ex. `$$\textsf text$$`

## Characters

#### Types:
  - \theta
  - \prime
  - \lparen
  - \rparen
  - \lbrack
  - \rbrack
  - \lbrace
  - \rbrace
  - \lBrace
  - \rBrace
  - \langle
  - \rangle
  - \vert
  - \Vert
  - \lVert
  - \rVert
  - \lt
  - \gt
  - \lceil
  - \rceil
  - \lfloor
  - \rfloor
  - \lmoustache
  - \rmoustache
  - \lgroup
  - \rgroup
  - \ulcorner
  - \urcorner
  - \llcorner
  - \lrcorner
  - \llbracket
  - \rrbracket
  - \uparrow
  - \downarrow
  - \updownarrow
  - \Uparrow
  - \Downarrow
  - \Updownarrow
  - \backslash
  - /

You use this also inside text things.

`ex. $$\ddddot \rfloor$$`

## Links and normal text

You can put a link in normal text by doing 

ex. `[text](https://example.com)`

You can also remove embeds by putting < and > at the start and end

ex. <https://youtube.com>

You can combine them to have a no embed link (Beware of scams using this)

`[text](<https://youtube.com>)`

