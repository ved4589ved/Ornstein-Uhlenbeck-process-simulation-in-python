
## Ornstein-Uhlenbeck process simulation in python 
#### The Ornstein-Uhlenbeck process is defined by the following SDE:

$dX_{t} = \theta(\mu-X_t)dt + \sigma(dW_t)$

where $\mu$ is the log term mean, 
$\theta$ is the rate of mean inversion, $\sigma$ is the volatility, $dW_t$ is the Wiener process (or standard Brownian motion)

<B> Solution to the above equation can be estimated by the Euler-Maruyama method :</B>

$X_{t+\delta t } = X_t + \theta (\mu - X_t)dt + \sigma \sqrt{\delta t} Z_t$ 

where $Z_t$ is the gaussian process 

you can play with interactive simulation for the Ornstien process.

## Using the OU process for the pair trading 

coming more .... (better complete this )


​
