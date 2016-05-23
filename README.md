# Grid

CSS plugin to make your site responsive.


## Instrutions

Paste this in your page's head:

`<link rel="stylesheet" type="text/css" href="https://rawgit.com/cervgon/grid/master/grid.min.css">`


## Classes

### You can use any fractions of 1,2,3,4,5,6,7,8,9,10,11,12 and 24.
### Listed Low-High:
`g1-24,g2-24,g1-12,g1-11,g1-10,g1-9,g3-24,g1-8,g1-7,g4-24,g2-12,g1-6,g2-11,g2-10,g1-5,g5-24,g2-9,g6-24,g3-12,g2-8,g1-4,g3-11,
g2-7,g7-24,g3-10,g8-24,g4-12,g3-9,g2-6,g1-3,g4-11,g9-24,g3-8,g4-10,g2-5,g10-24,g5-12,g3-7,g4-9,g5-11,g12-24,g6-12,g5-10,g4-8,
g3-6,g2-4,g1-2,g13-24,g6-11,g5-9,g4-7,g14-24,g7-12,g6-10,g3-5,g15-24,g5-8,g7-11,g16-24,g8-12,g6-9,g4-6,g2-3,g7-10,g17-24,g5-7,
g8-11,g18-24,g9-12,g6-8,g3-4,g7-9,g19-24,g8-10,g4-5,g9-11,g20-24,g10-12,g5-6,g6-7,g21-24,g7-8,g8-9,g9-10,g10-11,g22-24,g11-12,
g23-24,g24-24,g12-12,g11-11,g10-10,g9-9,g8-8,g7-7,g6-6,g5-5,g4-4,g3-3,g2-2,g1-1 and g1.`


## Default Media Queries

### From zero onwards
Type **g** + **fraction**.
e.g. `<div class="g1"></div>`

### @media screen and (min-width: 20em)
Type fraction from zero + **gs** + **fraction**.
e.g. `<div class="g1 gs1-2"></div>`

### @media screen and (min-width: 28em)
Type fraction from zero + **gxs** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3"></div>`

### @media screen and (min-width: 35.5em)
Type fraction from zero + **gm** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3 gm1-4"></div>`

### @media screen and (min-width: 35.5em)
Type fraction from zero + **gm** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3 gm1-4"></div>`

### @media screen and (min-width: 48em)
Type fraction from zero + **gxm** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3 gm1-4 gxm1-5"></div>`

### @media screen and (min-width: 64em)
Type fraction from zero + **gl** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3 gm1-4 gxm1-5 gl1-6"></div>`

### @media screen and (min-width: 80em)
Type fraction from zero + **gl** + **fraction**.
e.g. `<div class="g1 gs1-2 gxs1-3 gm1-4 gxm1-5 gl1-6 gxl1-7"></div>`


## License

The MIT License (MIT)

Copyright (c) 2016 Gonzalo Cervantes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Made with ♥ for the people of the internet
