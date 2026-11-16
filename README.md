<img src="logo.svg" alt="ChemTrain logo" height="110" align="right">

# Amino Acid Learn

Amino Acid Learn is a Quizlet-style trainer for the 20 standard amino acids: their structures, names, three- and one-letter codes, net charge at pH 7 and side-chain class. Everything is in one HTML file.

**Play it here:** https://chemtrain.github.io/amino-acid-learn/amino_acid_learn.html

You can also download `amino_acid_learn.html` and open it in any browser.

## What's inside

- The 20 standard amino acids, each drawn as the L-amino acid with its stereocentres
- Seven kinds of question, each one a toggle: name the structure, pick the structure, the three-letter code, the one-letter code, the amino acid behind a code, the net charge at pH 7, and the class of the side chain
- Wrong answers that are easy to mix up: L for lysine, T for tryptophan, the codes of asparagine, aspartic acid and arginine together
- A Learn mode (multiple choice, then typed answers), flashcards, a card list, and My cards for the ones you star
- Sets by one-letter code (the eleven that take their first letter, the nine to remember) and by side chain
- A note on every card: how to remember its one-letter code, and what its side chain does

## Sources

The classes are the five groups of side chains of Lehninger, *Principles of Biochemistry*; side-chain pKa values are from the same book. Net charges at pH 7 are rounded to whole numbers: histidine (side chain pKa 6.0) is in the positively charged group but carries a net charge of about +0.1 at pH 7, counted as 0.

Structures are drawn with [RDKit](https://www.rdkit.org).

## How to cite

If you use Amino Acid Learn in a course, a worksheet or a paper, please cite it:

> Bindschaedler, Q. P. *Amino Acid Learn* (2026). ChemTrain. https://github.com/ChemTrain/amino-acid-learn

GitHub's **Cite this repository** button (from `CITATION.cff`) gives the same reference in APA and BibTeX.

## License

- Code (the HTML, CSS and JavaScript): [MIT](LICENSE).
- Content (the cards, questions, notes and structure drawings): [CC BY 4.0](LICENSE-CONTENT.md). You may reuse and adapt it, as long as you credit Amino Acid Learn.
- Logo (`logo.svg`): the locomotive is adapted from [Twemoji](https://github.com/jdecked/twemoji), © Twitter, Inc and other contributors, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); the benzene-ring smoke was added for ChemTrain.

Quentin P. Bindschaedler and Francesco Sala
