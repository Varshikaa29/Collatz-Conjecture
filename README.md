# The Collatz Conjecture — Interactive Explorer

**Pick any number. Follow the rule. It always reaches 1 — but nobody has ever proved why.**

The rule is two lines long. The problem has stumped mathematicians for nearly a century. This project lets you play with it yourself.

---

## What this is

An interactive explorer for one of the most famous unsolved problems in mathematics. You type a number, the app follows the Collatz rule step by step, plots the full journey on a graph, and shows you every step colour coded so you can see the pattern. A compare grid lets you jump between famous starting numbers and see how wildly different their journeys can be.

It was built as part of a portfolio exploring how mathematical concepts can be taught through interaction and curiosity rather than memorisation.

---

## The rule

```
If n is even  →  n = n / 2
If n is odd   →  n = 3n + 1
Repeat until n = 1
```

That is the entire thing. The conjecture says that no matter what positive integer you start with you will always eventually reach 1. It has been verified for every number up to roughly 2 to the power of 68 — about 295 quintillion — and it holds every time. Yet no one has ever proved it must always work.

Paul Erdős, one of the greatest mathematicians of the 20th century, said about this problem: mathematics is not yet ready for such problems.

---

## Features

- Type any number or hit the random button to get a surprise
- A live Chart.js line graph plotting the full sequence journey
- Colour coded step tokens showing each value green for even and purple for odd
- Four stat cards showing starting number, steps to reach 1, highest peak hit, and even to odd step ratio
- A compare grid of famous starting numbers with their step counts, all clickable
- Hover tooltips on the graph showing the exact value and which rule was applied at each step
- The full sequence displayed as tokens with a show more indicator for long runs

---

## Interesting numbers to try

| Number | Why it is interesting |
|--------|----------------------|
| 27 | Takes 111 steps and peaks at 9232 before collapsing |
| 97 | Another long journey with a dramatic peak |
| 256 | A power of 2 — reaches 1 in exactly 8 steps |
| 871 | One of the most dramatic journeys under 1000 |
| 6171 | Takes 261 steps, one of the longest under 10000 |

---

## What it teaches

- Iterative sequences and how simple rules can produce complex behaviour
- The difference between verified and proved in mathematics
- How exponential growth appears inside a simple rule (3n+1 grows fast, n/2 shrinks slow)
- Why some problems that look trivial are actually deeply hard
- Number theory and the structure of even and odd numbers

---

## Built with

HTML, CSS, JavaScript and Chart.js for the line graph. Everything else is vanilla with no dependencies.

---

## How to run

Download the file and open it in any browser. Or visit the live version at

```
https://varshikaa29.github.io/collatz-conjecture/
```

---

## About

Made by Varshika Jain as part of a mathematics education portfolio for CCL, IIT Gandhinagar.

BS Data Science and Applications, IIT Madras

varshikajain2920@gmail.com
