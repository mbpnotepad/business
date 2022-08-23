---
title: Present Value
weight: 1
---

## Future Value

The future value of {{<katex>}}C_0{{</katex>}} at interest rate
{{<katex>}}r{{</katex>}} in 1 year is:

{{< katex display >}}
FV = C_0(1 + r).
{{</katex>}}

Example: assume you deposit $1000 in a bank account that pays 10% interest. The
future value of your investment is:

{{< katex display >}}
FV = 1000 (1 + .1) = 1100
{{</katex>}}

{{< hint info >}}
We are moving the cash flow forwards in time
{{< /hint >}}

## Preset Value

Suppose you will have a cash flow of {{<katex>}}C_1{{</katex>}} in one year. The
present value of {{<katex>}}C_1{{</katex>}} at interest rate
{{<katex>}}r{{</katex>}} is:

{{< katex display >}}
PV = \frac{C_1}{(1 + r)}
{{</katex>}}

Example: Suppose you need {{<katex>}}\$1000{{</katex>}} in one year. What do you
need to put aside today ({{<katex>}}r = 10\%{{</katex>}})?

{{< katex display >}}
PV = \frac{1000}{(1 + .1)} = 909.09
{{</katex>}}

## Net Present Value

Consider an investment that pays a cash flow of {{<katex>}}C1{{</katex>}} in 1
year and costs {{<katex>}}C0{{</katex>}} today. Interest rate is
{{<katex>}}r{{</katex>}}. The NPV of the investment is:

{{< katex display >}}
NPV = C_0 + \frac{C_1}{(1 + r)}
{{</katex>}}

Example: You are a software developer. You see an opportunity to develop a
software for a specific client. The investment has a cost (required investment)
of {{<katex>}}$0.5M{{</katex>}} and will pay you {{<katex>}}$0.54M{{</katex>}}
in one year. Interest rate is {{<katex>}}5%{{</katex>}}.

{{< katex display >}}
NPV = -0.5 + \frac{0.54}{1.05} = 0.0143
{{</katex>}}

## NPV Rule

{{< hint info >}}
Accept projects with {{<katex>}}NPV > 0{{</katex>}} and reject projects
{{<katex>}}NPV < 0{{</katex>}}
{{< /hint >}}

### Separation Theorem

Investment decision does not depend on preferences of individual investors for
current vs. future income. The NPV rule maximizes value.