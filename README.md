# Evalua Análisis Léxico

Se ha suprimido partes de código que han sido sustituídas por 
subguiones (underscores) en los ficheros `tokens.js`y `main.js`

## Hitos

1. Rellene las partes que faltan en `main.js`
2. Rellene las partes que faltan en `tokens.js`
3. Despliegue su aplicación en GitHub Pages

##TDOP, Top Down Operator Precedence Mini JavaScript Parser

## Author

Forked from Douglas Crockford TDOP project.
douglas@crockford.com

The lexycal analyzer is modified to use regular expressions.
Casiano Rodriguez Leon crguezl@ull.edu.es

## Introduction

* A full introduction is in the file [tdop.html](http://crguezl.github.io/ull-etsii-grado-pl-minijavascript/tdop.html) by Douglas Crockford.
It contains a description of Vaughn Pratt's Top Down Operator Precedence,
and describes a parser for Simplified JavaScript in Simplified JavaScript.

* [Deployment at GitHub pages](http://crguezl.github.io/ull-etsii-grado-pl-minijavascript/). 
  The app parses the input file  and displays its AST. 

* The exercise is to understand and improve [tokens.js](tokens.js). The `tokens` function  produces an array with the tokens for a given input string.
