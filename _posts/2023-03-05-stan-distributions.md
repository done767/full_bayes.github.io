# continuous distributions

|name|probability density function|link|
|---|---|---|
|gamma|$$\textnormal{Gamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{\alpha-1}\exp{(-\beta y)}$$|[stan](https://mc-stan.org/docs/functions-reference/gamma-distribution.html)|
|inverse gamma|$$\textnormal{InvGamma}(y\|\alpha,\beta)=\frac{\beta^{\alpha}}{\Gamma(\alpha)}y^{-(\alpha+1)}\exp{\left(-\beta\frac{1}{y}\right)}$$|[stan](https://mc-stan.org/docs/functions-reference/inverse-gamma-distribution.html)|
|beta|$$\textnormal{Beta}(\theta\|\alpha,\beta)=\frac{1}{\textnormal{B}(\alpha,\beta)}\theta^{\alpha-1}(1-\theta)^{\beta-1}$$|[stan](https://mc-stan.org/docs/functions-reference/beta-distribution.html)<br>[wiki](https://en.wikipedia.org/wiki/Beta_function)|

# discrete distributions

|name|function|link|
|---|---|---|
|dirichlet|$$\textnormal{Dirichlet}(\theta\|\alpha)=\frac{\Gamma\left(\sum\limits_{k=1}^K\alpha_k\right)}{\prod\limits_{k=1}^K\Gamma(\alpha_k)}\sum\limits_{k=1}^K\theta_{k}^{\alpha_k-1}$$|[stan](https://mc-stan.org/docs/functions-reference/dirichlet-distribution.html)<br>[wiki](https://en.wikipedia.org/wiki/Dirichlet_distribution)|
|categorical|$$\textnormal{Categorical}(y\|\theta)=\theta_y$$|[stan](https://mc-stan.org/docs/functions-reference/categorical-distribution.html)|
|poisson|$$\textnormal{Poisson}(n\|\lambda)=\frac{1}{n!}\lambda^n\exp{(-\lambda)}$$|[stan](https://mc-stan.org/docs/functions-reference/poisson.html)<br>[wiki](https://en.wikipedia.org/wiki/Poisson_distribution)|

# reference

* [https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions](https://mc-stan.org/docs/functions-reference/continuous-distributions.html#continuous-distributions)
* [https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions](https://mc-stan.org/docs/functions-reference/discrete-distributions.html#discrete-distributions)