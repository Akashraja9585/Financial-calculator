# Financial Calculator 💰

An interactive financial calculator built to compute EMI, SIP returns, Lump Sum investments and FD maturity amounts. Built this to understand how financial formulas work and how to create interactive web tools without any framework.

## What it does

- EMI Calculator — calculate monthly loan payments for home or car loans
- SIP Calculator — estimate returns on monthly mutual fund investments
- Lump Sum Calculator — calculate growth of a one-time investment
- FD Calculator — compute fixed deposit maturity value with quarterly compounding

## Tech used

- HTML
- CSS
- JavaScript (Vanilla)

## Getting started

Clone the repo:

    git clone https://github.com/Akashraja9585/financial-calculator.git
    cd financial-calculator

Open index.html directly in your browser — no installation needed.

## How it works

All calculations use standard financial formulas:

    EMI = P × r × (1+r)^n / ((1+r)^n - 1)
    SIP = M × ((1+r)^n - 1) × (1+r) / r
    Lump Sum = P × (1+r)^n
    FD = P × (1 + r/4)^(4n)

## What I learned

This was a great way to understand how financial products actually work mathematically. Implementing the EMI formula from scratch helped me understand why longer loan tenures reduce monthly payments but increase total interest paid.

Building interactive sliders that update results in real time taught me how DOM manipulation and event handling work in vanilla JavaScript without any framework.

## Future improvements

- Add a comparison mode to compare two loan options side by side
- Add charts to visualize investment growth over time
- Add PPF and NPS calculators

## License

MIT
