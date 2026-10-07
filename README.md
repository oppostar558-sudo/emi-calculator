# EMI Calculator

A tiny, dependency-free EMI (Equated Monthly Instalment) calculator that runs entirely in the browser.

## Features

- Monthly EMI for any loan amount, interest rate and tenure
- Total interest and total payment breakdown
- Principal vs interest donut chart (drawn with the Canvas API)
- Sliders synced with number inputs, fully responsive

## Formula

$$
\text{EMI} = \frac{P \cdot r \cdot (1+r)^n}{(1+r)^n - 1}
$$

where `P` = principal, `r` = monthly interest rate (annual / 12 / 100), `n` = number of months.

## Run it

Just open `index.html` in any browser — no build step, no server, no dependencies.

## License

MIT
