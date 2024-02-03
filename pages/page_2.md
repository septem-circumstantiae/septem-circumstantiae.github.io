# Page 2
{% include lib/mathjax.html %}
Utilize Bayesian probability for iterative updates:

$$ P(A | B) = \frac{P(B | A) \cdot P(A)}{P(B)} $$

Incorporate feedback with Bayes' rule:

$$ P(A | B_1, B_2, ..., B_n) \propto P(A) \cdot \prod_{i=1}^{n} P(B_i | A) $$
