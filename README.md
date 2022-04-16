# Cuernavaca

Chess Cuernavaca is an OFL licensed font suitable for making Chess
diagrams.  

Its graphics are mostly based on public domain vector files
available at the Wikimedia commons.  Those vector files are in turn
based on raster PNG images.  The PNG images, in turn, are renderings
of symbols in the open source
[Skak Chess Font](https://github.com/lehoff/skak), but do not, as per
*Eltra Corp. v. Ringer*, fall under the license for that font.
Since the SVG files are derived from raster PNG images,
*Adobe Systems, Inc. v. Southern Software, Inc.* does not apply.

Note that this font is *not* public domain in some jurisdictions which
allow fonts to be copyrighted, but is still available under a different
[open source license](https://github.com/lehoff/skak/blob/master/LICENSE).
Since some jurisdictions which protect fonts only protect them for 
shorter terms, it appears that the Shak font was first published in 
2002, so copyright expired before 2013 in Germany (10 years protection 
without registration), and expired before 2018 in Ireland (15 years 
protection).

To use, install the `ChessCuernavaca.ttf` file in one’s operating
system.

Here is a diagram made with the font:

![Cuernavaca Chess Font](https://raw.githubusercontent.com/samboy/ChessCuernavacaOFL/main/CuernavacaDemoSmall.png)

There is some support for fairy chess pieces.

Note that this font is also available with a different license
at the following location:

https://github.com/samboy/ChessGraphics

# The chess pieces

* A is a white upsidedown bishop
* S is a black upsidedown bishop
* D is a white rook + knight fairy piece
* F is a black rook + knight fairy piece
* G is a white upsidedown knight
* H is a black upsidedown knight
* P is a white pawn
* O (the letter) is a black pawn
* RNBQK are the expected white pieces (as per English algebraic notation)
* TMVWL are the corresponding black pieces
* A `+` is an empty black square
* A ` ` (blank space) is an empty white square

Note that the mapping is (generally) compatible with Chess Merida
and Armando Hernandez Marroquin’s other excellent freeware
Chess fonts.

Uppercase pieces are on black squares; lowercase pieces are on white
squares.

The following text looks like the starting position for Modern Carrera
Chess (where an upsidedown bishop also has the knight’s move, and the
piece which is a knight with rook is the rook + knight piece) in the 
ChessTepoztlan font:

```
!""""""""""#
$tSmVwLvMfT%
$OoOoOoOoOo%
$ + + + + +%
$+ + + + + %
$ + + + + +%
$+ + + + + %
$pPpPpPpPpP%
$RaNbQkBnDr%
/(((((((((()
```

Note that the font works best on a QWERTY keyboard (since the corresponding
black piece is next to the white piece; e.g. `V` is a black bishop where
`B` is a white bishop).  Uppercase is a dark square; lower case is a
light square.
