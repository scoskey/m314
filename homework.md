---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/480803)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 4, due Wednesday, February 8

1. Use the definition of limit to prove $\lim\frac{3n-1}{2n+5}=\frac32$.
2. Use the negation of the definition of limit to prove $\lim\frac{(-1)^n}{100}\neq0$.
3. (a) Let $a\_n$ be a sequence and assume $\alpha=\sup\set{a_n\mid n\in\mathbb N}$ exists. Explain why for any $\epsilon$, there exists a term of the sequence $a\_n$ such that $a\_n>\alpha-\epsilon$.  
  (b) Now assume that $a\_n\leq a\_{n+1}$ for all $n$. Show that for any $\epsilon$, there are infinitely many terms of the sequence such that $a\_n>\alpha-\epsilon$.
4. (Abbott, ex 2.2.1) Suppose we swap the first two quantifiers in the definition of convergence, and write $x\_n$ *verconges* to $L$ if:  
   $(\exists\epsilon>0)\;(\forall N\in\mathbb N)\;(\forall n\geq N)\;|x_n-L|<\epsilon$.  
   Give an example of a vercongent sequence that is not convergent. What exactly is being described in this definition?
<!--5. Suppose that $A\subset\mathbb R$ is bounded and that $\alpha=\sup(A)$.  This exercise shows how to prove that there exists a sequence in $A$ which converges to $\alpha$.  
  (a) Prove that for each $n\in\mathbb N$ there exists $a\_n\in A$ such that $a_n>\alpha-1/n$.  
  (b) Use the definition of convergence to conclude that $\lim a\_n=\alpha$.-->

## Week 3, due Wednesday, February 1

1. Recall $\mathbb N^3$ consists of all triples of the form $(a,b,c)$, where $a,b,c\in\mathbb N$. Prove $\mathbb N^3$ is countable by showing how to write its elements in a list. (Write the first 10+ elements, explain how you would continue, and explain why the completed list would include every element).
2. Let $S\_\text{fin}$ be the set of all *finite* words made with the letters $a,b$. So $S$ contains elements like $ab$, $abb$, $ababa$, $aabbbbaa$, and so forth. Prove $S\_\text{fin}$ is countable. (Write the first 10+ elements, explain how you would continue, and explain why the completed list would include every element).
3. Let $\epsilon>0$. Let $I\_n$ be a sequence of bounded intervals of width $\geq\epsilon$. Assume $I\_n$ are nested, that is $I\_n\supset I\_{n+1}$. Prove that $\bigcap I\_n\neq\emptyset$.
4. Read your proof from the activity that $S\_{\infty}$ is uncountable. Why doesn't this proof work for $S_\text{fin}$? Explain precisely where and why it fails.
5. (Abbott, ex 1.5.10(a)) Let $A\subset[0,1]$ and assume that $A$ is uncountable. Show that there exists $a>0$ such that $A\cap[a,1]$ is uncountable.


## Week 2, due Wednesday, January 25

1. (Abbott, ex 1.4.4) Let $a\lt b$ and $T=\mathbb{Q}\cap[a,b]$. Show $\sup(T)=b$.
2. Prove or give a counterexample: If $A$ and $B$ are sets of real numbers such that $a\lt b$ for all $a\in A$ and $b\in B$, then $\sup(A)\lt\inf(B)$.
3. (Abbott, ex 1.4.6) We say that a set $D$ is *dense* in $\mathbb{R}$ if between any two real numbers we can find an element of $D$. Which of the following sets are dense, and why?  
  * The set of rational numbers $p/q$ with $q\leq10$
  * The set of rational numbers $p/q$ with $q$ a power of $2$
  * The set of rational numbers $p/q$ with $q\leq10\abs{p}$

## Week 1, due Wednesday, January 18

1. (Abbott, ex 1.2.1)  
  * Study the proof that there is no rational number $q$ such that $q^2=2$. Modify this proof to show that there is no rational number $q$ such that $q^2=3$.
  * Obviously there *is* a rational number such that $q^2=4$, so your proof in the previous part cannot work if $3$ is replaced by $4$. Point out *exactly* which part of your proof would fail and explain why.
2. (See Abbott, ex 8.6.2). Suppose that $(A,P,B)$ is a cut, $r\in A$, and that $q$ is a rational number such that $q\lt r$. Show that $q\in A$.
3. (Abbott, ex 8.6.3). Read the five properties of a field listed in Definition 8.6.4. Which of these properties are possessed by $\mathbb N$? By $\mathbb Z$? By $\mathbb Q$? Explain your answers.
4. Show that the set $\set{q\in\mathbb Q\mid q^3\lt 2}$ has no greatest element. (Copy a proof idea from the notes.)
5. Let $A$ and $B$ be nonempty bounded sets of real numbers, and assume every element of $A$ is less than every element of $B$.  
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
