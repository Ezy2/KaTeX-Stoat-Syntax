# KaTeX-Stoat
some help for the katex syntax in stoat.chat

This is based off of https://katex.org/docs/supported I'm simply putting it in easier? to understand words and what works (not all on that site are supported on stoat)

# Basics

The start and the end of your word should start with $$. 

ex. `$$\color{red} test$$`

KaTeX is also meant for math so it is a little weird to use and will be italic by default

The prefix for it is a backslash '\\' 

## Size, Colour, and Position

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

### Centering

You can center by putting $$ and $$ on newlines

ex. 
```
$$
text
$$
```

## Fonts

Now remember KaTeX is for *math* so the fonts aren't normal ones

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

## Accents

#### Types:
  - a'
  - a''
  - a^{\prime}
  - \acute text
  - \bar text
  - \breve text
  - \check text
  - \dot text
  - \ddot text
  - \dddot text
  - \ddddot text
  - \grave text
  - \hat text
  - \tilde text
  - \widetilde text
  - \utilde text
  - \vec text
  - \overleftarrow text
  - \underleftarrow text
  - \overleftharpoon text
  - \overleftrightarrow text
  - \underleftrightarrow text
  - \overline text
  - \underline text
  - \underbar text
  - \widecheck text
  - \widehat
  - \mathring text
  - \overgroup text
  - \undergroup text
  - \Overrightarrow text
  - \overrightarrow text
  - \underrightarrow text
  - \overrightharpoon text
  - \overbrace text
  - \underbrace text
  - \overbracket text
  - \underbracket text
  - \overlinesegment text
  - \underlinesegment text

ex. `$$\ddddot{\underleftarrow{text}}$$`

## Links and normal text

You can put a link in normal text by doing 

ex. `[text](https://example.com)`

You can also remove embeds by putting < and > at the start and end

ex. `<https://youtube.com>`

You can combine them to have a no embed link (Beware of scams using this)

`[text](<https://youtube.com>)`

using "`" at the start and end of a scetence it makes a box around it

using "```" at the start and end makes it a multiline box

If u put ">" at the start of a line it will start a unique bulletin style thing

## Enviroments

This one is hard to explain so I'll just put examples and try my best

#### Types:
  - matrix
  - pmatrix
  - vmatrix
  - Bmatrix
  - cases
  - smallmatrix
  - array
  - bmatrix
  - Vmatrix
  - rcases

ex.
```
$$
\begin{matrix}
   text & text \\
   text & text
\end{matrix}
$$
```

so "\\" means new line like a new row and & means new variable so like text & text & text would have 3 different ones on the same row

#### Odd Ones

Not sure how these ones work so you'll ahve to mess around with it yourself

```
$$
\def\arraystretch{1.5}
   \begin{array}{c:c:c}
   a & b & c \\ \hline
   d & e & f \\
   \hdashline
   g & h & i
\end{array}
$$

$$
\sum_{
\begin{subarray}{l}
   i\in\Lambda\\
   0<j<n
\end{subarray}}
$$

$$
x = \begin{cases}
   a &\text{if } b \\
   c &\text{if } d
\end{cases}
$$
```

# Bugs

Bug: If you do `$$` it will send an invisible line for some reason
