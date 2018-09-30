+++
title = "The Conditional Probability Theorem"
description = ""
date = 2017-07-11
weight = 0
draft = false
in_search_index = true
template = "proof_page.html"
# The taxonomies for that page. The keys need to be the same as the taxonomies
# name configured in `config.toml` and the values an array of String like
# tags = ["rust", "web"]
[taxonomies]

[extra]
+++
A simple proof by contradiction - the one you see in most analysis textbooks.

#### Hypothesis
$\sqrt{2}$ is an irrational number.

#### Proof
We'll use proof by contradiction. 

Assume that $\sqrt{2}$ is a rational number. Then there exist two intergers $a$ and $b$ such that $\sqrt{2} = \frac{a}{b}$, $b \ne 0$, and $a$ does not divide $b$ (in other words, the fraction is in "lowest terms").

Then it follows that $\sqrt{2}^2 = \frac{a^2}{b^2}$. Thus $\frac{a^2}{b^2} = 2$.

But now we see that we have $a^2 = 2b^2$. This contradicts our assumption that $a$ does not divide $b$. 

Therefore, $\sqrt{2}$ is an irrational number.

$\blacksquare$