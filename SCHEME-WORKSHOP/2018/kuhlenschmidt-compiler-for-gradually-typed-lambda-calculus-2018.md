# [An Efficient Compiler for the Gradually Typed Lambda Calculus](kuhlenschmidt-compiler-for-gradually-typed-lambda-calculus-2018.pdf)

By Andre Kuhlenschmidt, Deyaaeldeen Almahallawi, and Jeremy G. Siek

## Abstract

Gradual typing combines static and dynamic typing in the same
program. One would hope that the performance in a gradually typed
language would range between that of a dynamically typed language and
a statically typed language. Existing implementations of gradually
typed languages have not achieved this goal due to overheads
associated with runtime casts.  Takikawa et al. (2016) report up to
100× slowdowns for partially typed programs. In this paper we present
a compiler, named Grift, for evaluating implementation techniques for
gradual typing. We take a straightforward but unexplored
implementation approach for gradual typing, that is, ahead-of-time
compilation to native assembly code using space-efficient coercions.

Our experiments show that this approach achieves performance on par
with OCaml on statically typed programs but is slower than other
dynamically typed languages on untyped programs. On partially typed
code, the speedup with respect to untyped code ranges from 0.42× to
19.90× across the benchmarks. We implement casts using coercions and
show that coercions eliminate catastrophic slowdowns without
introducing significant overhead in all benchmarks. Across the
benchmarks, coercions range from 9% slower (fft) to 13.65× faster
(quicksort) than regular casts. We also implement the monotonic
references and show that they eliminate all overhead in statically
typed code. For partially typed code, they are faster on average than
the traditional proxied references, sometimes up to 1.65×.

## Keywords

- compiler
- gradual type
- lambda calculus
