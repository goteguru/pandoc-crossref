You can define subfigures:

::: {#fig:subfigures .subfigures}
+:------------------:+:------------------:+:------------------:+
| ![a](fig1          | ![b](fig2          | ![c](fig3.         |
| .png){#fig:subfig1 | .png){#fig:subfig2 | png){width="100%"} |
| width="100%"}      | width="100%"}      |                    |
+--------------------+--------------------+--------------------+
| ![d](fig4          | ![e](fig5.         | ![f](fig6          |
| .png){#fig:subfig4 | png){width="100%"} | .png){#fig:subfig6 |
| width="100%"}      |                    | width="100%"}      |
+--------------------+--------------------+--------------------+
| ![g](fig7          | ![h](fig8.         | ![i](fig9          |
| .png){#fig:subfig7 | png){width="100%"} | .png){#fig:subfig9 |
| width="100%"}      |                    | width="100%"}      |
+--------------------+--------------------+--------------------+

Figure 1: Caption. a --- 1, b --- 2, c --- 3, d --- 4, e --- 5, f --- 6,
g --- 7, h --- 8, i --- 9
:::

::: {#fig:subfigures2 .subfigures}
+:--------------------------------------------------------------------:+
| ![a](fig1.png){#fig:subfig21 width="100%"}                           |
+----------------------------------------------------------------------+
| ![b](fig2.png){#fig:subfig22 width="100%"}                           |
+----------------------------------------------------------------------+
| ![c](fig3.png){width="100%"}                                         |
+----------------------------------------------------------------------+
| ![d](fig4.png){#fig:subfig24 width="100%"}                           |
+----------------------------------------------------------------------+
| ![e](fig5.png){width="100%"}                                         |
+----------------------------------------------------------------------+
| ![f](fig6.png){#fig:subfig26 width="100%"}                           |
+----------------------------------------------------------------------+
| ![g](fig7.png){#fig:subfig27 width="100%"}                           |
+----------------------------------------------------------------------+
| ![h](fig8.png){width="100%"}                                         |
+----------------------------------------------------------------------+
| ![i](fig9.png){#fig:subfig29 width="100%"}                           |
+----------------------------------------------------------------------+

Figure 2: Caption. a --- 1, b --- 2, c --- 3, d --- 4, e --- 5, f --- 6,
g --- 7, h --- 8, i --- 9
:::

Figures themselves can be referenced fig. 2, as well as individual
subfigures: figs. 1 (a), 1 (b), 2 (i)
