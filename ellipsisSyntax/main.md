---
title: Topics in the syntax of ellipsis
author: Patrick D. Elliott
date: 25.06.2018
theme: metropolis 
bibliography: main.bib
biblio-title: Bibliography
biblatexoptions: "bibstyle=biblatex-sp-unified,citestyle=sp-authoryear-comp,language=auto,sorting=nyt,maxcitenames=3,maxbibnames=99,natbib=true,autocite=plain,isbn=false,doi=false,url=false,hyperref=auto,uniquename=false,uniquelist=false"
header-includes:
- |
  ```{=latex}
  \usefonttheme[onlymath]{serif}
  \input{../common/fontSetup.tex}
  \input{../common/lingMacros.tex}
  \input{../common/extraPackages.tex}
  ```
...

# Class 1: Sluicing and silent structure

## Overview

- This class is about the syntax of *ellipsis*.

## Ellipsis

- In *elliptical constructions*, linguistic material is left unpronounced, but
  is nevertheless understood.
  
- Ellipsis is therefore a classical example of a *form-meaning mismatch*.
  
- Some canonical examples of ellipsis (some of which we'll be covering in this
  class).
  
  (@) *Sluicing*  
      Someone stayed out until 7am,  
      but I have no idea who \elide{stayed out
      until 7 am}.
  
  (@) *VP ellipsis*  
      Elin stayed out until 7am, and Fraser did \elide{stay out until 7 am} too.
      
  (@) *Fragment answers*  
      Q: Who stayed out until 7am?  
      A: Elin \elide{stayed out until 7am}
      
## Ellipsis ii

- Some other phenomena which have been (controversially) analysed as ellipsis:

    (@) *Comparative deletion*  
    Fraser stayed out later than Elin \elide{stayed out}.

    (@) *Pronouns*  
    A woman walked in. [She$_{\text{D}}$ \elide{woman}] sat down.

    (@) *Conjunction reduction*  
    Patrick talked to Elin and \elide{Patrick talked to} Fraser.

## Ellipsis iii

- Ellipsis should be distinguished from other phenomena where linguistic
  material is missing but nevertheless understood, such as, e.g. implicature.
  

  (@) Fraser danced with some of the people at the party.  
  $\rightsquigarrow$ *Fraser danced with some of the people at the party and he
  didn't dance with all of the people at the party* 
  
- Here, what is *understood* deviates from what we would expect based on the
  compositional semantics.
  
- There is little to suggest that there was ever a stage in the derivation at
  which this linguistic material was present, however.
  
- Elliptical phenomena display a distinct signature: the syntax betrays that
  the linguistic material is *missing*, and the missing material must be
  *recoverable* based on the context of utterance.
  
## Non-recoverable deletion

## Terminology

\begin{center}
\begin{forest}
[{TP}
    [{Elin}]
    [{T'}
        [{T\\-ed}]
        [{VP},tikz={\node [draw,red,fit=()(!1)(!ll)] {};}
            [{dance}]
            [{PP} [{until 7 am},roof]]
        ]
    ]
]
\end{forest}
%
\begin{forest}
[{TP}
    [{Fraser}]
    [{T'}
        [{T\\did}]
        [{VP},tikz={\node [draw,dashed,fit=()(!1)(!ll)] {};}
            [{dance}]
            [{PP} [{until 7am},roof]]
        ]
    ]
]
\end{forest}
\end{center}

- \textcolor{red}{A(ntecedent)}
- \dashuline{E(llipsis) site}

## Three questions

- The *structure* question
- The *identity* question
- The *licensing* question

See @merchant2018. 

## The structure question

(@) In elliptical constructions, is there syntactic structure that is unpronounced?

## The identity question

(@) What is the relationship between the understood material and its antecedent?

## The licensing question

(@) What heads or structures allow for *ellipsis*, and what are the locality
conditions on the relation between these structures and ellipsis?

## The identity and licensing conditions

 - *The identity question*  
 To what extent must an elided constituent be identical to its antecedent? At
 what level is the identity condition enforced – the narrow syntax, the
 semantics, or some other level?
 
 - *The licensing question*  
 What are the *syntactic licensing conditions* governing ellipsis (not
 everything *recoverable* can necessarily be elided). Can only syntactic
 constituents be elided?

## Guess who! 

- Since @Ross 

(@) guess who Δ.

## Terminology



