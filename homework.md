---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/218674)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Weeks 6-7, due Tuesday, March 2

1. TBA

## Week 5, due Thursday, February 18

1. (Abbot, 2.3.4) Suppose that $\lim a\_n=0$. Find, with justification, each of the following limits.  
  * $\lim \frac{1+2a\_n}{1+3a\_n-4a\_n^2}$
  * $\lim \frac{(a\_n+2)^2-4}{a\_n}$
  * $\lim \frac{\frac{2}{a\_n}+3}{\frac{1}{a\_n}+5}$
2. Show that if $\lim a\_n=a$ and $a\neq0$ and $\lim a\_nb\_n=ab$ then $\lim b\_n=b$.
3. (Abbot, 2.3.6) Let $a\_n=n-\sqrt{n^2+2n}$. Find the limit of $a\_n$.
4. Let $p$ be any real number. Prove that $\sum\frac1{n^p}$ converges if and only if $p>1$. (This is called the ``$p$-test.'')
5. Let $x\_n$ be the sequence indicated below. Write down a recurrence for the sequence $x\_n$ (that is, a formula for $x\_{n+1}$ in terms of $x\_n$). Use induction to prove that the sequence is both bounded and monotone. Prove that the sequence converges. Finally, find the limit.  
  $x\_1=\sqrt{2},x\_2=\sqrt{2+\sqrt{2}},x\_3=\sqrt{2+\sqrt{2+\sqrt{2}}}$, $\ldots$  


## Week 4, due Tuesday, February 9

1. Use the definition of limit to prove $\lim\frac{3n-1}{2n+5}=\frac32$.
2. Use the negation of the definition of limit to prove $\lim\frac{(-1)^n}{100}\neq0$.
3. Let $a\_n$ be a sequence of real numbers and assume that $a\_n\leq a\_{n+1}$ for all $n$. Let $\alpha=\sup\set{a_n\mid n\in\mathbb N}$. Show that for all $\epsilon$, just finitely many terms of the sequence are $\leq\alpha-\epsilon$.
4. (Abbott, ex 2.2.1) Suppose we swap the first two quantifiers in the definition of convergence, and write $x\_n$ *verconges* to $L$ if:  
   $(\exists\epsilon>0)\;(\forall N\in\mathbb N)\;(\forall n\geq N)\;|x_n-L|<\epsilon$.  
   Give an example of a vercongent sequence that is not convergent. What exactly is being described in this definition?
5. Suppose that $A\subset\mathbb R$ is bounded and that $\alpha=\sup(A)$.  This exercise shows how to prove that there exists a sequence in $A$ which converges to $\alpha$.  
  (a) Prove that for each $n\in\mathbb N$ there exists $a\_n\in A$ such that $a_n>\alpha-1/n$.  
  (b) Use the definition of convergence to conclude that $\lim a\_n=\alpha$.


## Weeks 2-3, due Tuesday, February 2

1. Prove or give a counterexample: If $A$ and $B$ are sets of real numbers such that $a\lt b$ for all $a\in A$ and $b\in B$, then $\sup(A)\lt\inf(B)$.
2. Show that the set $\mathbb N^3$ is countable. Here $\mathbb N^3$ consists of all triples of the form $(a,b,c)$, where $a,b,c\in\mathbb N$.
3. Let $S\_\text{fin}$ be the set of all *finite* words made with the letters $a,b$. So $S$ contains elements like $ab$, $abb$, $ababa$, $aabbbbaa$, and so forth. Prove that $S\_\text{fin}$ is countable.
4. Read your proof from the activity that $S\_{\infty}$ is uncountable. Why doesn't this proof work for $S_\text{fin}$? Explain precisely where and why it fails.
5. (Abbott, ex 1.5.10(a)) Let $A\subset[0,1]$ and assume that $A$ is uncountable. Show that there exists $a>0$ such that $A\cap[a,1]$ is uncountable.

## Week 1, due Thursday, January 21

1. (Abbott, ex 1.2.1)  
  * Study the proof that there is no rational number $q$ such that $q^2=2$. Modify this proof to show that there is no rational number $q$ such that $q^2=3$.
  * Obviously there *is* a rational number such that $q^2=4$, so your proof in the previous part cannot work if $3$ is replaced by $4$. Point out *exactly* which part of your proof would fail and explain why.
2. (Abbott, ex 8.6.2). Suppose that $C$ is a cut, $q\in C$, and that $r$ is a rational number such that $r\notin C$. Show that $q\lt r$.
3. (Abbott, ex 8.6.3). Read the five properties of a field listed in Definition 8.6.4. Which of these properties are possessed by $\mathbb N$? By $\mathbb Z$? By $\mathbb Q$? Explain your answers.
4. Modify a proof given in class to instead show that the cut $\set{q\in\mathbb Q\mid q^3<2}$ has no last element.
5. Let $A$ and $B$ be sets of real numbers, and assume every element of $A$ is less than every element of $B$.  
   * Prove that $\sup(A)\leq\sup(B)$.
   * Give an example showing it is possible that $\sup(A)=\sup(B)$.



<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true,
      macros: {
        set: ["{\\left\\{ #1 \\right\\}}", 1],
        abs: ["{\\left| #1 \\right|}", 1],
        lt: ["<"]
      }
    }
  };
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
