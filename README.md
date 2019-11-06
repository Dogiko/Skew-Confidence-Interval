# Skew-Confidence-Interval

An algorithm to estimate CI for distribution with high skew.

Generate a distribution $X~\exp{(N(\mu, \sigma))}+b$ with unique $\mu, \sigma, b$ match given $m, v, s$ (mean, variance and skewness).

### ps:

Only work when $s > 0$

Use normal when $s := 0$

Input $-s, -m$ when $s < 0$ and consider $-X$ finally.