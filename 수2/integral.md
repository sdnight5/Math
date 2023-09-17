미분 : $f'(x) = \lim\limits_{\varDelta x \rightarrow 0} {\frac{f(a+\varDelta x)-f(a)} {\varDelta x}}$ ($f'(x)$는 도함수),
> $f(x) = x^n \rightarrow f'(x) = nx^{n-1}$

부정적분 : $\int f(x)dx = F(x)+C$
> $\int x^ndx = {\frac 1 {n+1}}x^{n+1}+C$

정적분 : $\int f(x)dx = F(x)+C \rightarrow \int_a^b f(x)dx = F(b)-F(a)$
> $\lim\limits_{n \rightarrow \infty} \displaystyle\sum_{k=1}^n f(x_k){\frac{b-a} {n}} = F(b)-F(a)$

> $\therefore \int_a^b f(x)dx = \lim\limits_{n \rightarrow \infty} \displaystyle\sum_{k=1}^n f(x_k){\frac{b-a}  {n}} = F(b)-F(a)$

>> $(x_k = a+k{\frac {b-a} {n}})$

정적분을 이용한 넓이 구하기 : $S(x) = \int_a^b |f(x)|dx$ 