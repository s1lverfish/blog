## Welcome to my blog
$$
\begin{align*}
dp_{k, j} + cost(k+1,i)
&amp;= dp_{k, j} + \left( \sum_{l=k+1}^{i} et_i - et_l \right) \\
&amp;= dp_{k, j} + et_i(i-k) - \left( \sum_{l=k+1}^{i} et_l \right) \\
&amp;= dp_{k, j} + i\cdot et_i - k\cdot et_i - sum_i + sum_k \\
&amp;= i\cdot et_i -sum_i + (-k\cdot et_i + sum_k + dp_{k, j}) \\
\end{align*}
$$
