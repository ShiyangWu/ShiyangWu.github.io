# Category Theory : Basic Notions

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> <script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: { skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'], inlineMath: [['$','$']] } }); </script>

## What is Category Theory?

Category theory is a branch of mathematics that seeks to generalize all of mathematics in terms of categories and then reveals deep insights and similarities between seemingly different areas of mathematics. Category theory provides an alternative foundation for mathematics to set theory and other proposed axiomatic foundations.

## History

Category theory first appeared in a paper entitled _General Theory of Natural Equivalences_, written by Samuel Eilenberg and Saunders Mac Lane in 1945.$^{[1]}$Categories, functors and natural transformations were discovered by Eilenberg and Mac Lane in their study of limits for universal coefficients theorems in $\check{C}ech$ cohomology. Also in this paper, commutative diagrams for the first time appeared in print.$^{[1]}$

## Basic Notions

**Definition 1(Category)**

A **category** $C$ consists of

1.A class $ob(C)$ of objects

2.A class $hom(C)$ of morphisms between the objects. Each morphism $f$ has a source object $a$ and a target object $b$ where $a$ and $b$ are in $ob(C)$. $f: a \rightarrow b$ denotes **"f is a morphism from a to b"**. $hom(a, b)$ denotes the hom-class of all morphisms from $a$ to $b$. 

For every three objects $a$, $b$ and $c$, a binary operation $hom(a, b) \times hom(b, c) \rightarrow hom(a, c)$ called composition of morphisms; the composition of $f : a → b$ and $g : b → c$ is written as $g ∘ f$.

3.**(associativity)** If $f : a \rightarrow b$, $g : b \rightarrow c$ and $h : c → d$ then $h ∘ (g ∘ f) = (h ∘ g) ∘ f$.

4.**(identity)** For every object $x$, there exists a morphism $1x : x → x$ called **the identity morphism for $x$**, such that for every morphism $f : a → x$ and every morphism $g : x → b$, we have $1x ∘ f = f$ and $g ∘ 1x = g$.

**Definition 2(Functor)**

A **functor** is a morphism of categories.

For categories $C$ and $B$ a **functor** $T: C \rightarrow B$ with domain $C$ and codomain $B$ consists of two suitably related functions. The object function $T$, which assigns to each object $c$ of $C$ an object $Tc$ of $B$ and arrow function which assigns to each arrow $f:c \rightarrow c'$ of $C$ an arrow $Tf: Tc \rightarrow Tc'$ of $B$, then

<center>$T(1_c)=1_{Tc}$</center>


<center>$T(g \circ f)= Tg \circ Tf$</center>

the later whenever the composite $g \circ f$ is defined in $C$.

**Definition 3(Natural Transformation)**

A **natural tranformation** is a morphism of functors.

Given two functors $S,T:C \rightarrow B$, a natural tranformation $\tau : S \rightarrow T$ is a function witch assigns to each object $c$ of $C$ an arrow $\tau_c = \tau c: Sc \rightarrow Tc$ of $B$ in such a way that every arrow $f:c \rightarrow c'$ in $C$ yields a diagram

<center>![NT_01](https://shiyangwu.github.io/Blog/Pictures/CommutativeDiagram/NaturalTransformation_01.png)</center>

<center>![NT_02](https://shiyangwu.github.io/Blog/Pictures/CommutativeDiagram/NaturalTransformation_02.png)</center>

## References

[1] Lane, S. M. (1971), Categories. for the working mathematician. Graduate Texts in Mathematics, 5(9), 349-361.

## Contact me

* Email -> <wusy@fosu.edu.cn>
* Blog -> [ShiyangWu.github.io](https://shiyangwu.github.io/)
* GitHub -> [ShiyangWu@github.io](https://github.com/ShiyangWu/ShiyangWu.github.io/blob/master/README.md)

