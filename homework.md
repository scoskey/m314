---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/480803)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 2, due Wednesday, January 25

1. (Abbott, ex 1.4.4) Let $a\lt b$ and $T=\mathbb{Q}\cap[a,b]$. Show $\sup(T)=b$.
2. TBA
3. TBA

## Week 1, due Wednesday, January 18

1. (Abbott, ex 1.2.1)  
  * Study the proof that there is no rational number $q$ such that $q^2=2$. Modify this proof to show that there is no rational number $q$ such that $q^2=3$.
  * Obviously there *is* a rational number such that $q^2=4$, so your proof in the previous part cannot work if $3$ is replaced by $4$. Point out *exactly* which part of your proof would fail and explain why.
2. (See Abbott, ex 8.6.2). Suppose that $(A,P,B)$ is a cut, $r\in A$, and that $q$ is a rational number such that $q\lt r$. Show that $q\in A$.
3. (Abbott, ex 8.6.3). Read the five properties of a field listed in Definition 8.6.4. Which of these properties are possessed by $\mathbb N$? By $\mathbb Z$? By $\mathbb Q$? Explain your answers.
4. Show that the set $\set{q\in\mathbb Q\mid q^3\lt 2}$ has no greatest element. (Copy a proof idea from the notes.)
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
