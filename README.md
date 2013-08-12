Compact LaTeX Layout for Summaries
==================================

<code>summary.tex</code> is a LaTeX template originally created to quickly typeset
summaries of lecture content in a very compact three-column layout.

It also contains a variety of commands that make typesetting summaries with many
formulae less of a hassle.

Bold-face Latin and Greek Letters
---------------------------------

The template makes it easy to typeset formulae with many vectors and matrices,
which commonly require bold-face Latin and Greek letters.

The template supports all lowercase and uppercase letters
of the Latin and Greek alphabets with the prefix <code>\b</code>.
For example, use <code>\bA</code> instead of <code>{\mathbf{A}}</code>
and <code>\bsigma</code> instead of <code>{\boldsymbol \sigma}</code>

Based on snippet by [Alexey Malistov](http://stackoverflow.com/questions/2952980/quick-way-to-make-26-macros-one-for-each-letter).
 
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