# ISFA

The *ISFA* project is a database of *I*nteger *S*equence *F*ormulas and *A*pplications. The integer sequence formulas are parsed from the [OEIS](http://oeis.org).

A more detailed report can be found [here](https://github.com/MathHubInfo/ISFA/blob/master/docs/Enxhell_Luzhnica_BSC.pdf).

## Parts

The ISFA is currently composed of:

- A parser for math formulas found in the OEIS.
- A program that finds relations between OEIS's sequences. Relations in simple text format (due to space limitations) are available [here](https://kwarc.info/datahost/).
- A [MathWebSearch instance](http://oeissearch.mathweb.org) for OEIS's documents (thanks to Mihnea Iancu).
- A parser for an improved formula language for the OEIS.
- A [SageMath module](https://github.com/MathHubInfo/oeis_gf) for OEIS's generating functions.

Head to [this](https://github.com/MathHubInfo/ISFA/blob/master/docs/Enxhell_Luzhnica_BSC.pdf) thesis to learn more.

## Related papers/reports/thesis

- [BSc thesis](https://github.com/MathHubInfo/ISFA/blob/master/docs/Enxhell_Luzhnica_BSC.pdf)
- Enxhell Luzhnica, Michael Kohlhase - [Formula Semantification and Automated Relation Finding in the On-Line Encyclopedia for Integer Sequences. ICMS 2016: 467-475](https://kwarc.info/kohlhase/papers/icms16-oeis.pdf)
- E. Luzhnica, M. Iancu and M. Kohlhase (2015-10) [Importing the OEIS library into OMDoc. In Proceedings of the LWA 2015 workshops: KDML, FGWM, IR, and FGDB, R. Bergmann, S. Görg and G. Müller (Eds.), pp. 296–303](http://ceur-ws.org/Vol-1458/F13_CRC73_Luzhnica.pdf)
