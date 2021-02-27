Links to pages with values computed to 25 decimal places of continued fractions with terms that are polynomial in their index.
These are intended for people to find by search engine if they have a value and they're wondering if there's an expression that
explains it. Some of these are in [OEIS](https://oeis.org) but many are not.

There are 10,000 polynomials per page, sorted by absolute value of highest-degree coefficients within each page. Polynomials are
generated in "score" order before being grouped into pages. The score of a polynomial is

$$
\begin{align}
score&=deg(P) + \sum_{i=0}^{i\le deg(P)} \left|a_i\right| \\
P &= \sum_{i=0}^{i\le deg(P)}a_i x^i
\end{align}
$$

Only polynomials up to degree 6 are included.
Some polynomials producing negative fractional terms are excluded.

* [Polynomials from 1 through 5𝑛⁶ with scores up to 12](polycf1.html)
* [Polynomials from 13 through 6𝑛⁶ with scores up to 13](polycf2.html)
* [Polynomials from −3 + 2𝑛² + 2𝑛³ + 2𝑛⁴ through 7𝑛⁶ with scores up to 13](polycf3.html)
* [Polynomials from 14 through −𝑛⁵ + 6𝑛⁶ with scores up to 14](polycf4.html)
* [Polynomials from 5 − 𝑛² + 𝑛³ + 3𝑛⁴ through 9𝑛⁵ with scores up to 14](polycf5.html)
* [Polynomials from −2 − 𝑛 + 3𝑛³ + 3𝑛⁵ through 8𝑛⁶ with scores up to 14](polycf6.html)
* [Polynomials from 1 − 𝑛 − 2𝑛² − 𝑛⁴ + 2𝑛⁵ + 𝑛⁶ through −3𝑛⁵ + 5𝑛⁶ with scores up to 14](polycf7.html)
* [Polynomials from 15 through −𝑛⁵ + 7𝑛⁶ with scores up to 15](polycf8.html)
* [Polynomials from 2 + 5𝑛 + 𝑛² + 𝑛³ + 𝑛⁵ through 8𝑛⁴ + 2𝑛⁵ with scores up to 15](polycf9.html)
* [Polynomials from 𝑛 + 3𝑛² + 3𝑛³ + 𝑛⁴ + 2𝑛⁵ through 9𝑛⁶ with scores up to 15](polycf10.html)
* [Polynomials from 4 − 𝑛 + 3𝑛³ + 𝑛⁶ through 8𝑛⁵ + 𝑛⁶ with scores up to 15](polycf11.html)
* [Polynomials from −1 + 2𝑛 + 2𝑛² + 𝑛³ − 2𝑛⁵ + 𝑛⁶ through 7𝑛⁵ + 2𝑛⁶ with scores up to 15](polycf12.html)
* [Polynomials from −1 + 𝑛 − 𝑛² + 2𝑛³ + 𝑛⁴ + 𝑛⁵ + 2𝑛⁶ through 5𝑛⁵ + 4𝑛⁶ with scores up to 15](polycf13.html)
* [Polynomials from 16 through −𝑛⁵ + 8𝑛⁶ with scores up to 16](polycf14.html)
* [Polynomials from −𝑛 − 5𝑛² + 4𝑛³ + 2𝑛⁴ through 11𝑛⁵ with scores up to 16](polycf15.html)
* [Polynomials from 2 + 4𝑛 − 3𝑛³ − 𝑛⁴ + 𝑛⁵ through 9𝑛⁴ + 2𝑛⁵ with scores up to 16](polycf16.html)
* [Polynomials from 2 − 𝑛 − 3𝑛² + 2𝑛³ + 𝑛⁴ + 2𝑛⁵ through 7𝑛³ + 4𝑛⁵ with scores up to 16](polycf17.html)
* [Polynomials from 1 − 3𝑛 − 2𝑛² + 𝑛³ + 4𝑛⁵ through 10𝑛⁶ with scores up to 16](polycf18.html)
* [Polynomials from −1 + 2𝑛 + 2𝑛² − 3𝑛³ − 𝑛⁴ + 𝑛⁶ through 9𝑛⁵ + 𝑛⁶ with scores up to 16](polycf19.html)
* [Polynomials from −4 − 2𝑛² − 2𝑛⁴ + 𝑛⁵ + 𝑛⁶ through 6𝑛² − 3𝑛⁵ + 𝑛⁶ with scores up to 16](polycf20.html)
* [Polynomials from −2 − 𝑛 − 3𝑛² + 3𝑛⁵ + 𝑛⁶ through −8𝑛⁴ + 2𝑛⁶ with scores up to 16](polycf21.html)
* [Polynomials from 1 − 2𝑛 − 2𝑛³ + 3𝑛⁴ + 2𝑛⁶ through 8𝑛⁵ + 2𝑛⁶ with scores up to 16](polycf22.html)
* [Polynomials from 𝑛 + 2𝑛² − 3𝑛⁴ + 2𝑛⁵ + 2𝑛⁶ through 7𝑛⁵ + 3𝑛⁶ with scores up to 16](polycf23.html)
* [Polynomials from 2 − 2𝑛 − 𝑛² − 2𝑛⁵ + 3𝑛⁶ through −5𝑛⁵ + 5𝑛⁶ with scores up to 16](polycf24.html)
* [Polynomials from 17 through −𝑛⁵ + 9𝑛⁶ with scores up to 17](polycf25.html)
* [Polynomials from −2 + 𝑛 − 7𝑛² − 𝑛³ + 2𝑛⁴ through 12𝑛⁵ with scores up to 17](polycf26.html)
* [Polynomials from −2 + 𝑛 + 8𝑛² + 𝑛⁵ through 11𝑛⁴ + 𝑛⁵ with scores up to 17](polycf27.html)
* [Polynomials from 1 + 3𝑛 − 𝑛² + 4𝑛³ + 2𝑛⁴ + 𝑛⁵ through 10𝑛⁴ + 2𝑛⁵ with scores up to 17](polycf28.html)
* [Polynomials from −1 − 4𝑛 − 3𝑛² + 𝑛³ − 𝑛⁴ + 2𝑛⁵ through 9𝑛³ + 3𝑛⁵ with scores up to 17](polycf29.html)
* [Polynomials from 1 + 4𝑛² − 4𝑛³ + 3𝑛⁵ through −8𝑛⁴ + 4𝑛⁵ with scores up to 17](polycf30.html)
* [Polynomials from −3 − 3𝑛² − 2𝑛⁴ + 4𝑛⁵ through 11𝑛⁶ with scores up to 17](polycf31.html)
* [Polynomials from 1 − 4𝑛 + 4𝑛² − 𝑛³ + 𝑛⁶ through 10𝑛⁴ + 𝑛⁶ with scores up to 17](polycf32.html)
* [Polynomials from −1 − 𝑛² + 3𝑛³ − 5𝑛⁴ + 𝑛⁶ through 10𝑛⁵ + 𝑛⁶ with scores up to 17](polycf33.html)
* [Polynomials from −2 + 3𝑛 − 2𝑛³ + 2𝑛⁴ + 𝑛⁵ + 𝑛⁶ through −8𝑛⁴ + 2𝑛⁵ + 𝑛⁶ with scores up to 17](polycf34.html)
* [Polynomials from 2 + 𝑛 − 𝑛² + 3𝑛³ − 𝑛⁴ − 2𝑛⁵ + 𝑛⁶ through 6𝑛 − 4𝑛⁵ + 𝑛⁶ with scores up to 17](polycf35.html)
* [Polynomials from 5 − 𝑛 + 4𝑛⁵ + 𝑛⁶ through 9𝑛⁴ + 2𝑛⁶ with scores up to 17](polycf36.html)
* [Polynomials from 3 − 3𝑛² + 𝑛³ + 2𝑛⁴ + 2𝑛⁶ through 9𝑛⁵ + 2𝑛⁶ with scores up to 17](polycf37.html)
* [Polynomials from −2 + 𝑛 − 𝑛² − 2𝑛³ − 2𝑛⁴ + 𝑛⁵ + 2𝑛⁶ through 6𝑛⁴ − 3𝑛⁵ + 2𝑛⁶ with scores up to 17](polycf38.html)
* [Polynomials from −1 + 4𝑛² − 𝑛⁴ − 3𝑛⁵ + 2𝑛⁶ through 8𝑛⁵ + 3𝑛⁶ with scores up to 17](polycf39.html)
* [Polynomials from −4 − 𝑛 + 𝑛² + 𝑛³ − 𝑛⁵ + 3𝑛⁶ through 5𝑛⁴ + 3𝑛⁵ + 3𝑛⁶ with scores up to 17](polycf40.html)
* [Polynomials from 3 − 𝑛³ + 𝑛⁴ − 3𝑛⁵ + 3𝑛⁶ through 7𝑛⁵ + 4𝑛⁶ with scores up to 17](polycf41.html)
* [Polynomials from −1 + 𝑛 + 2𝑛³ + 𝑛⁴ + 2𝑛⁵ + 4𝑛⁶ through −4𝑛⁵ + 7𝑛⁶ with scores up to 17](polycf42.html)
* [Polynomials from 18 through −𝑛⁵ + 10𝑛⁶ with scores up to 18](polycf43.html)
* [Polynomials from 2 + 5𝑛 − 5𝑛² + 2𝑛⁴ through 9𝑛³ + 5𝑛⁴ with scores up to 18](polycf44.html)
* [Polynomials from 1 − 3𝑛 + 4𝑛² + 𝑛³ + 5𝑛⁴ through 13𝑛⁵ with scores up to 18](polycf45.html)
* [Polynomials from −1 + 7𝑛 + 2𝑛² + 𝑛³ + 𝑛⁴ + 𝑛⁵ through 9𝑛³ + 3𝑛⁴ + 𝑛⁵ with scores up to 18](polycf46.html)
* [Polynomials from −1 + 4𝑛 + 3𝑛² + 𝑛³ + 3𝑛⁴ + 𝑛⁵ through 11𝑛³ + 2𝑛⁵ with scores up to 18](polycf47.html)
* [Polynomials from −1 − 𝑛 + 5𝑛² − 4𝑛³ + 2𝑛⁵ through 11𝑛⁴ + 2𝑛⁵ with scores up to 18](polycf48.html)
* [Polynomials from 3 − 3𝑛² + 2𝑛³ + 3𝑛⁴ + 2𝑛⁵ through 10𝑛⁴ + 3𝑛⁵ with scores up to 18](polycf49.html)
* [Polynomials from −1 + 𝑛 − 2𝑛² + 5𝑛³ − 𝑛⁴ + 3𝑛⁵ through 9𝑛⁴ + 4𝑛⁵ with scores up to 18](polycf50.html)
* [Polynomials from 4 + 𝑛² − 3𝑛³ + 𝑛⁴ + 4𝑛⁵ through 8𝑛⁴ + 5𝑛⁵ with scores up to 18](polycf51.html)
* [Polynomials from 2 + 𝑛³ + 5𝑛⁴ + 5𝑛⁵ through 12𝑛⁶ with scores up to 18](polycf52.html)
* [Polynomials from 2 − 𝑛 − 2𝑛² + 6𝑛³ + 𝑛⁶ through 11𝑛⁴ + 𝑛⁶ with scores up to 18](polycf53.html)
* [Polynomials from −2 − 𝑛 − 2𝑛² − 3𝑛³ + 3𝑛⁴ + 𝑛⁶ through 11𝑛⁵ + 𝑛⁶ with scores up to 18](polycf54.html)
* [Polynomials from 7 + 𝑛² − 𝑛³ + 𝑛⁴ − 𝑛⁵ + 𝑛⁶ through 8𝑛³ + 2𝑛⁴ + 𝑛⁵ + 𝑛⁶ with scores up to 18](polycf55.html)
* [Polynomials from 1 + 𝑛² + 6𝑛³ + 2𝑛⁴ + 𝑛⁵ + 𝑛⁶ through 9𝑛³ − 2𝑛⁵ + 𝑛⁶ with scores up to 18](polycf56.html)
* [Polynomials from 3 − 𝑛 + 𝑛² − 4𝑛³ + 2𝑛⁵ + 𝑛⁶ through 9𝑛⁴ + 2𝑛⁵ + 𝑛⁶ with scores up to 18](polycf57.html)
* [Polynomials from −1 + 2𝑛 − 𝑛² + 2𝑛³ − 3𝑛⁴ − 2𝑛⁵ + 𝑛⁶ through 8𝑛⁴ + 3𝑛⁵ + 𝑛⁶ with scores up to 18](polycf58.html)
* [Polynomials from −1 − 𝑛 − 𝑛² − 3𝑛³ − 2𝑛⁴ − 3𝑛⁵ + 𝑛⁶ through −6𝑛⁴ + 5𝑛⁵ + 𝑛⁶ with scores up to 18](polycf59.html)
* [Polynomials from −𝑛 − 2𝑛² + 2𝑛³ + 𝑛⁴ + 5𝑛⁵ + 𝑛⁶ through 10𝑛⁴ + 2𝑛⁶ with scores up to 18](polycf60.html)
* [Polynomials from 4 − 𝑛 + 2𝑛² − 𝑛³ + 2𝑛⁴ + 2𝑛⁶ through 10𝑛⁵ + 2𝑛⁶ with scores up to 18](polycf61.html)
* [Polynomials from −6 + 𝑛² − 𝑛³ − 𝑛⁴ − 𝑛⁵ + 2𝑛⁶ through −5𝑛³ + 4𝑛⁴ − 𝑛⁵ + 2𝑛⁶ with scores up to 18](polycf62.html)
* [Polynomials from 1 + 3𝑛² + 𝑛³ + 4𝑛⁴ − 𝑛⁵ + 2𝑛⁶ through 8𝑛⁴ − 2𝑛⁵ + 2𝑛⁶ with scores up to 18](polycf63.html)
* [Polynomials from 2 − 2𝑛² − 𝑛³ + 3𝑛⁴ + 2𝑛⁵ + 2𝑛⁶ through −6𝑛⁴ + 4𝑛⁵ + 2𝑛⁶ with scores up to 18](polycf64.html)
* [Polynomials from −2 − 𝑛 + 𝑛² − 2𝑛⁴ + 4𝑛⁵ + 2𝑛⁶ through 9𝑛⁴ + 3𝑛⁶ with scores up to 18](polycf65.html)
* [Polynomials from −3 + 2𝑛² − 𝑛³ − 3𝑛⁴ + 3𝑛⁶ through 9𝑛⁵ + 3𝑛⁶ with scores up to 18](polycf66.html)
* [Polynomials from 3 − 2𝑛 + 3𝑛⁴ + 𝑛⁵ + 3𝑛⁶ through −6𝑛⁴ − 3𝑛⁵ + 3𝑛⁶ with scores up to 18](polycf67.html)
* [Polynomials from 3 − 2𝑛² − 𝑛⁴ + 3𝑛⁵ + 3𝑛⁶ through 8𝑛⁴ + 4𝑛⁶ with scores up to 18](polycf68.html)
* [Polynomials from −1 − 𝑛 + 2𝑛² + 4𝑛⁴ + 4𝑛⁶ through 8𝑛⁵ + 4𝑛⁶ with scores up to 18](polycf69.html)
* [Polynomials from −2 + 𝑛² − 𝑛³ − 2𝑛⁴ + 2𝑛⁵ + 4𝑛⁶ through 7𝑛⁵ + 5𝑛⁶ with scores up to 18](polycf70.html)
* [Polynomials from 1 − 2𝑛 + 𝑛² − 2𝑛⁴ + 𝑛⁵ + 5𝑛⁶ through −5𝑛³ + 7𝑛⁶ with scores up to 18](polycf71.html)
* [Polynomials from 1 − 𝑛 + 3𝑛³ + 7𝑛⁶ through −𝑛⁵ + 11𝑛⁶ with scores up to 19](polycf72.html)
