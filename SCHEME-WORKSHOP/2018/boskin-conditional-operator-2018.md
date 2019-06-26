# A Surprisingly Competitive Conditional Operator: miniKanrenizing the Inference Rules of Pie

By Benjamin Boskin, Weixi Ma, David Thrane Christiansen, and Daniel Friedman

## Abstract

Because miniKanren programs can run forwards and backwards,
interpreters written in miniKanren can perform program
synthesis. Because program synthesis for dependently typed languages
is also proof synthesis, miniKanren implementations of dependently
typed languages can be used for proof search. Unfortunately, `conde`'s
unaided complete interleaving depth-first search does not yield a
practical proof search due to the sheer amount of computation
required. A new conditional operator, called `condp` , gives users a
means to drop irrelevant goals from search. We demonstrate that
`condp` provides sufficient control over the search process to perform
synthesis far more quickly.

## Keywords

- dependent types
- miniKanren
- program synthesis
