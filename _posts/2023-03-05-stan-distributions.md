# Gamma distribution

$$
Gamma(y|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{\alpha-1}\exp{(-\beta y)}
$$

|name|probability density function|command|
|---|---|---|
|[Gamma](https://mc-stan.org/docs/functions-reference/gamma-distribution.html)|$$\textnormal{Gamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{\alpha-1}\exp{(-\beta y)}$$|`gamma`|
|[InvGamma](https://mc-stan.org/docs/functions-reference/inverse-gamma-distribution.html)|$$\textnormal{InvGamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{-(\alpha+1)}\exp{\left(-\beta\frac{1}{y}\right)}$$|`inv_gamma`|

# reference

* [https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions](https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions)
* [https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions](https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions)