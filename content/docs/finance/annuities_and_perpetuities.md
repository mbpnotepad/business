---
title: Annuities and Perpetuities
weight: 3
---

## Annuity

An annuity is an equal and annual series of payments made over a predetermined
time period. Annuities can be used for a variety of purposes, but the most
common one is providing a steady income for retirees.

In the case of retirees, a lump sum of money or assets is exchanged for a series
of smaller payments in the future. This payment is often guaranteed for the life
of the beneficiary, meaning that, for a fee, the seller of an annuity assumes
the longevity risk, or the risk that the beneficiary will outlive the amount
paid.

In general, the present value of a cash flow {{< katex >}}C{{</katex>}}, for {{<
katex >}}t{{</katex>}} years[^1]:

{{< katex display >}}
PV = C\frac{(1+r)^t-1}{r(1+r)^t}
{{</katex>}}

where {{< katex >}}\frac{(1+r)^t-1}{r(1+r)^t}{{</katex>}} is the Annuity factor
{{< katex >}}AF^t_r{{</katex>}}

[^1]: Summation of a geometric series {{<katex>}}S_N = x+x^2+...+x^N =
    \frac{x(1-x^N)}{1-x}{{</katex>}}

### Example

You have taken out a 15-year mortgage for $0.5M. Suppose r = 4%. What must your
annual payment be? Here, we have the PV and r. We need to calculate C.

{{<hint info>}}
 Note: the owner of this
asset is the bank. The cash flows on the asset are your payments to the bank. So
in solving this problem, we set C so that the value to the bank is correct.
{{</hint>}}

{{<katex display>}}
0.5 = C (AF^{15}_{0.04}) \to C = \$45000
{{</katex>}}

The future value of an annuity is:

{{< katex display >}}
FV = C\frac{(1+r)^t-1}{r(1+r)^t}(1+r)^t = C\frac{(1+r)^t-1}{r}
{{</katex>}}

### Example

Invest $2000 at 6% interest for 50 years:

{{< katex display >}}
FV = 2000(\frac{1.06^{50}-1}{.06}) = \$580670
{{</katex>}}

## Perpetuity

A perpetuity is a fixed payment that occurs every year, forever.

{{<katex display>}}
PV = \frac{C}{r}
{{</katex>}}

Preferred Stock (as opposed to common stock): dividends are
guaranteed unless the company defaults on its debt.

The point is that preferred stock offers a perpetual payment that is almost
fixed. Even if the perpetuity formula isn’t exact, we can still use the general
principle of a perpetuity.

What we will see is that the same principle holds for all stocks. This explains
why interest rate matters for stock prices. The stock price is like the present
value of future dividends. When the interest rate goes up, the present value,
and therefore the stock price, goes down.

## Growing Annuities

An asset where the payments grow at rate {{<katex>}}g{{</katex>}} for
{{<katex>}}t{{</katex>}} years

{{<katex display>}}
\underbrace{\text{Cash Flow}}_{\text{Time}} = \underbrace{}_{t_0},
\underbrace{C}_{t_1}, \underbrace{C(1+g)}_{t_2}, ...,
\underbrace{C(1+g)^{t-1}}_{t}
{{</katex>}}

The present value when {{<katex>}}r \not = g{{</katex>}}:

{{<katex display>}}
PV = C \frac{(1+r)^t - (1+g)^t}{(r-g)(1+r)^t}
{{</katex>}}

when {{<katex>}}r = g{{</katex>}}:

{{<katex display>}}
PV = C \frac{t}{1+g}
{{</katex>}}

## Growing Perpetuities

For a growing perpetuity to have a finite value, we need
{{<katex>}}r>g{{</katex>}}, in that case the present value becomes:

{{<katex display>}}
PV = \frac{C}{r-g}
{{</katex>}}

## Delayed Annuities and Perpetuities

One feature of many investments is the cash flows grow very rapidly at the
beginning, then more slowly, or not at all, later. We can value these by
breaking them into building blocks: an annuity plus a delayed perpetuity.

What is the PV of an asset that pays {{<katex>}}C{{</katex>}} in perpetuity
beginning {{<katex>}}s{{</katex>}} years from now?

{{<katex display>}}
PV = \frac{C}{r(1+r)^{s-1}}
{{</katex>}}

What is the PV of an asset that pays {{<katex>}}C{{</katex>}} for
{{<katex>}}t{{</katex>}} years beginning {{<katex>}}s{{</katex>}} years from
now?

{{<katex display>}}
PV = \frac{C(AF^t_r)}{(1+r)^{s-1}}
{{</katex>}}