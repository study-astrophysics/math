

## Sequence and series

- Sequence: a set of quantities
- Series: a sum of quantities


## Form

In general, an infinite series has a form:


$$ a_1 + a_2 + a_3 + \cdots + a_n + \cdots \ , $$

## Using a summation sign $\sum$

For example, the sum of $n^2$ from $n=1$ to $\infty$:


$$ 1^2 + 2^2 + 3^2 + 4^2 + \cdots = \sum^{\infty}_{n=1}n^2 $$
 

### Example: find $\lim_{n\to\infty} (\frac{1}{n})^{1/n}$.

Put the log first,

$$ \ln \left( \frac{1}{n} \right)^{1/n} = - \frac{1}{n} \ln n. $$

Then put the limit,


$$  \lim_{n\to\infty} \ln \left( \frac{1}{n} \right)^{1/n} = - \lim_{n\to\infty}\frac{1}{n} \ln n = 0. $$

since $\lim_{n\to\infty} \frac{\ln n}{n} = 0$  (By L'Hopital's rule). Now put the exp to restore the original limit,


$$ \lim_{n\to\infty} \left(\frac{1}{n}\right)^{1/n} = \lim_{n\to\infty} e^{\ln \left( \frac{1}{n} \right)^{1/n}} = e^0 = 1.  $$

