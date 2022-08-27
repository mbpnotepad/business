---
title: Effective Annual Rates
weight: 4
---

## Compounding within a year

Generally, we say {{<katex>}}r_a{{</katex>}} is the Stated Annual Interest Rate
(SAIR), a.k.a: Annual Percentage Rate (APR), compounded {{<katex>}}m{{</katex>}}
times a year. Then, our initial investment {{<katex>}}C{{</katex>}} at a given
period in the future becomes:

{{<katex display>}}
FV = C (1 + \frac{r_a}{m})^{mt}
{{</katex>}}

We can also use this formula for discounting. How much do we need to invest to
have {{<katex>}}C{{</katex>}} in {{<katex>}}t{{</katex>}} years at SAIR
{{<katex>}}r_a{{</katex>}}, compounded {{<katex>}}m{{</katex>}} times a year?

{{<katex display>}}
PV = C (1 + \frac{r_a}{m})^{-mt}
{{</katex>}}

The limit of compounding more and more frequently (continuous compounding) is:

{{<katex display>}}
\lim\limits_{m->\infty} (1+\frac{r_a}{m})^m = e^{r_a}
{{</katex>}}

## Effective Annual Rate (EAR)

The rate that, when compounded annually, produces the same return as
{{<katex>}}r_a{{</katex>}}, when {{<katex>}}r_a{{</katex>}} is compounded
{{<katex>}}m{{</katex>}} times a year.

{{<katex display>}}
EAR = (1+\frac{r_a}{m})^m-1
{{</katex>}}

And for continuous compounding:

{{<katex display>}}
EAR = e^{r_a}-1
{{</katex>}}
