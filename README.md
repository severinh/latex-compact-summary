Compact LaTeX Layout for Summaries
==================================

<code>summary.tex</code> is a LaTeX template originally created to quickly typeset
summaries of lecture content in a very compact three-column layout.


Bold-face Letters and Symbols
-----------------------------

The template makes it easy to typeset formulae with many vectors and matrices,
which commonly require bold-face letters and symbols.

The template makes it possible to use <code>\bA</code> instead of
<code>{\textbf{A}}</code>.

Labels
------

Use labels to highlight stuff that is still unclear or to refer to slides,
exercises or the literature. Labels are typeset with a red or blue background,
denoting unclear content or a reference, respectively.
Use the following commands to create a label:

    \unclear
    \seeslides
    \seeexercise
    \seeliterature

You can supply custom text as an option parameter to each of the above commands,
for instance <code>\unclear[Proof]</code>.

Labels only appear in the verbose variant of the summary.