# continuous distributions

|name|probability density function|command|
|---|---|---|
|[Gamma](https://mc-stan.org/docs/functions-reference/gamma-distribution.html)|$$\textnormal{Gamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{\alpha-1}\exp{(-\beta y)}$$|`gamma`|
|[InvGamma](https://mc-stan.org/docs/functions-reference/inverse-gamma-distribution.html)|$$\textnormal{InvGamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{-(\alpha+1)}\exp{\left(-\beta\frac{1}{y}\right)}$$|`inv_gamma`|

# discrete distributions

|name|function|link|
|---|---|---|
|dirichlet|$$\textnormal{Dirichlet}(\theta\|\alpha)=\frac{\Gamma\left(\sum_{k=1}^K\alpha_k\right)}{\prod_{k=1}^K\Gamma(\alpha_k)}\sum_{k=1}^K\theta_{k}^{\alpha_k-1}$$|[stan](https://mc-stan.org/docs/functions-reference/dirichlet-distribution.html) [wiki](https://en.wikipedia.org/wiki/Dirichlet_distribution)|

$$\textnormal{Dirichlet}(\theta\|\alpha)=\frac{\Gamma\left(\sum\limits_{k=1}^K\alpha_k\right)}{\prod\limits_{k=1}^K\Gamma(\alpha_k)}\sum\limits_{k=1}^K\theta_{k}^{\alpha_k-1}$$

# reference

* [https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions](https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions)
* [https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions](https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions)