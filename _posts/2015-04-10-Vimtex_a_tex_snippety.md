---
layout: post
title:  Vimtex a tex snippety
categories: linux
---

**Skratky pre snippety**

`[<C-l>]` - keď napíšem celý názov snippetu tak cez <C-l> mi snippet
roztiahne automaticky

`[it <C-l>]` - pridá mi automaticky \item

`[tab]` - pridá mi tabular

`[table]` - pridá mi celú table aj s tabular-om

`[fig]` - pridá mi \begin{figure} aj s includegraphics, caption, label

`[enum]` - pridá mi \begin{enumerate} s \item a \end{enumerate}

`[sec]` - pridá mi \section kde zadám názov a navyše môžem aj label aby
som očísloval sekciu

`[sub]` - prida mi \subsection rovnako aj s labelom ako u `sec`

`[ssub]` - je subsubsection a rovnako funguje ako hore

`[subs]` - to iste ako ssub

`[up]` - pridá mi \usepackage aj s {options}{package}

`[ci]` - doplní mi \citep{} takže hned môžem cez <C-space> doĺňať nové
referencie

`[bf]` - doplni mi \textbf{} do zátvorky dávam bold písmo

`[under]` - doplni mi \underline{}

`[emp]` - doplni mi \emph{} na zvýraznenie písma

`[sc]` - doplni mi \textsc{} kde všetko, čo dám do zátvorky je napísané
ako cez Caps lock, všetko sú capital letters.

`[tikz]` - pridá mi \begin{figure} ako cez fig len v centre snippetu je
\begin{tikzpicture}

`[href]` - pridá mi \href{}{} kde na ľavú stranú dám link a pravú názov
linku modrou

`[cr]` - pridá mi \cref{} možnosť aj s doplňovaním

**Vimtex**

`[<C-o> alebo <C-i>]` - pohyb kurzora v latexu v latexu z momentálneho
miesta do predchádzajúceho miesta

`[<C-space>]` - doplňovanie citácii a referencii (tables, figures - ich
čísla)

`[<leader>ly]` - zobrazi mi všetky labels ako tabulky alebo obrazky do
grazov. Vyhodí mi na pravo roletu

`[<leader>lt]` - zobrazi mi hlavný obsah .tex súboru, teda
stromovú štruktúru

`[<leader>le]` - ukáže mi chyby/upozornenie (vypnuté automaticky)

`[<leader>ll]` - stači raz stlačiť a potom sa mi bude meniť pdf hneď po
uložení

`[']]']` - v insert mode stlačím ']]' a pridá mi \end{section} riadok

`[dse]` - vymaže mi prostredie napr. začínajúce \begin{nieco} \end{nieco}

`[cse]` - môžem modifkovať prostredie napr \begin{nieco} a \end{nieco}
môžem cez toggle bar na dolnej strane editovať názov prostredia (niečo na
štýl search and replace)

**Latex funkcie**

`[termin\footnote{nieco o termine}]` - Dá mi nad termín v texte v pravo
hore malú jednotku a v zátvorke je poznámka pod čiarov, kde je
napísané vysvetlenie termínu
