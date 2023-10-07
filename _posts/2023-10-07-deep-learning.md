# Feedforward Neural Network

equation

1. $u^{(l+1)}=W^{(l+1)}z^{(l)}+b^{(l+1)}$
1. $z^{(l+1)}=f(u^{(l+1)})$
1. $y\equiv z^{L}$

explanation

* $x$ : input data
* $y$ : output data
* $l$ : the index of layer
* $L$ : the index of final layer
* $f$ : activation function (ex. logistic function)
* $W, b$ : weight

# Regression

function

$$y=f(x)$$

error

$$E(w)=\sum_{n=1}^N{||d_n-y(x_n;w)||^2}$$

* $d_n$ : output

SGD (Stochastic Gradient Descent)

$$\nabla E\equiv \frac{\partial E}{\partial w}$$

$$w_{t+1}=w_t-\epsilon \nabla E$$

* $\epsilon$ : learning rate


$$E_t(w)=\frac{1}{N_t}\sum_{n\in D_t}^NE_n(w)$$

$$w_{t+1}=w_t-\epsilon \nabla E_n$$

* $D_t$ : mini batch
* $t$ : index of batch

momentum SGD

$$w_{t+1}=w_t-\epsilon \nabla E_t+\mu v_t$$

* $\mu = 0.5\sim0.9$ : hyper parameter
* $v_t\equiv w_t-w_{t-1}$ : weight adjustment

so, 

$$v_{t+1}=\mu v_t-\epsilon\nabla E_t$$