# Category Theory : Basic Notions

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> <script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: { skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'], inlineMath: [['$','$']] } }); </script>

## What is Category Theory?

Category theory is a branch of mathematics that seeks to generalize all of mathematics in terms of categories and then reveals deep insights and similarities between seemingly different areas of mathematics. Category theory provides an alternative foundation for mathematics to set theory and other proposed axiomatic foundations.

## History

## Basic Notions

**Definition 1(Category)**

A **category** $C$ consists of

1.A class $ob(C)$ of objects

2.A class $hom(C)$ of morphisms between the objects. Each morphism $f$ has a source object $a$ and a target object $b$ where $a$ and $b$ are in $ob(C)$. $f: a \rightarrow b$ denotes **"f is a morphism from a to b"**. $hom(a, b)$ denotes the hom-class of all morphisms from $a$ to $b$. 

For every three objects $a$, $b$ and $c$, a binary operation $hom(a, b) \times hom(b, c) \rightarrow hom(a, c)$ called composition of morphisms; the composition of $f : a → b$ and $g : b → c$ is written as $g ∘ f$.

3.**(associativity)** If $f : a \rightarrow b$, $g : b \rightarrow c$ and $h : c → d$ then $h ∘ (g ∘ f) = (h ∘ g) ∘ f$.

4.**(identity)** For every object $x$, there exists a morphism $1x : x → x$ called **the identity morphism for $x$**, such that for every morphism $f : a → x$ and every morphism $g : x → b$, we have $1x ∘ f = f$ and $g ∘ 1x = g$.

## References

[1] Lane, S. M. (1971), Categories. for the working mathematician. Graduate Texts in Mathematics, 5(9), 349-361.

## Contact me

* Email -> <wusy@fosu.edu.cn>
* Blog -> [ShiyangWu.github.io](https://shiyangwu.github.io/)
* GitHub -> [ShiyangWu@github.io](https://github.com/ShiyangWu/ShiyangWu.github.io/blob/master/README.md)

