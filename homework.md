---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/480803)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Midterm, due Monday, March 6

**Instructions** You may not consult with any other person or intelligence. Your work must be *completely your own*. You may refer to class notes and materials freely. If you use any outside resources, please *provide citations*. To receive full credit, use only the methods *we learned in our class*. To receive full credit, please *show all work*.

1. Please copy the following paragraph, and sign your name below it: "My solutions are my own original work. I completed this exam without consulting any other person. I followed Boise State University's policies on academic integrity."
2. Suppose $\alpha$ is a real number corresponding to the cut $(A,P,B)$. Describe the cut corresponding to the real number $2\alpha$. You may want to separate into cases based on whether the cut is rational or irrational.
3. Let $A,B$ be infinite sets of real numbers such that $A\cap B=\emptyset$ and $\sup(A)=\sup(B)$. Show that there exists a sequence $x\_n$ which is: monotone, has a subsequence in $A$, and has a subsequence in $B$.
4. Prove that the set is countable: $A=$ the set of irrational numbers of the form $a+b\sqrt{2}$, where $a,b$ are nonzero rational numbers.
5. Prove that the set is uncountable: $A=$ the set of real numbers whose decimals expansion use only the digits $3,5,7$.
6. Use the definition of convergence to verify that the sequence converges to the proposed limit: $a_n=\frac{3n+1}{5n+1}$, $L=3/5$
7. Use the limit calculus laws to find each limit. Justify your steps.  
  * $\lim\frac{(2n+2)(3n-1)}{12n^2+5n+1}$
  * $\lim\frac{\sqrt{4n^3+3n^2+2n+1}}{\sqrt{n^3}+2\sqrt{n}+1}$
8. Decide, with full justification, whether the positive-term series converge or diverge.  
  * $\sum\frac{n^3-n}{n^4\sqrt{n}+2n+2}$
  * $\sum\frac{e^n}{n!}$
9. Let $a_n\geq0$. Show that if $\sum a_n$ converges then $\sum(a_n)^2$ converges. Give an example which shows that the converse is false.
10. Consider the sequence defined by $a_1=2$ and $a_{n+1}=\frac{a_n+3}{4}$.  
  * Use induction to prove the sequence is bounded below by $0$.
  * Use induction to prove the sequence is monotone decreasing.
  * Use the limit calculus laws to find the limit, $L$.

## Week 7, due Wednesday, March 1

1. Use direct comparisons to decide whether the series converge or diverge.
  * $\sum\frac{1+\sin(n)}{n^2}$
  * $\sum\frac{n}{n^2+n}$
2. Use the root or ratio tests to decide whether the series converge or diverge.  
  * $\sum(\frac{3n+1}{2n+4})^{2n}$
  * $\sum\frac{2^{1+3n}(n+1)}{n^25^{1+n}}$
3. Suppose that $a\_n,b\_n\geq0$ and that $\sum a\_n$ and $\sum b\_n$ both converge. Prove that $\sum a\_nb\_n$ converges.


## Week 6, due Wednesday, February 22

1. Consider the sequence defined as follows: $a\_n=$ the reciprocal of the least prime factor of $n$. Write out the first 20 terms of $a\_n$. Find two subsequences of $a\_n$ that converge to two different limits.
2. Find an example of a divergent sequence $a\_n$ which satisfies $\lim(a\_{n+1}-a\_n)=0$, and verify it has these properties.
3. In this exercise you will show MCT implies BWT. Together with our work from class, we can conclude MCT is yet another equivalent to AOC. To begin, we say that a term $a\_n$ of a sequence is a *peak* if for all $n'>n$ we have $a\_n'\leq a\_n$.  
  (a) Assume the sequence $a\_n$ has infinitely many peaks. Show that $a\_n$ has a monotone decreasing subsequence. [Hint: Use the peaks.]  
  (b) Assume the sequence $a\_n$ has finitely many peaks. Show that $a\_n$ has a monotone increasing subsequence. [Hint: What happens after the last peak?]  
  (c) Use parts (a) and (b) together with the MCT to prove the BWT.
4. (Abbott, 2.5.6) Let $b\geq0$. Show that the sequence $b^{1/n}$ is convergent and find the value of the limit.
5. (See Abbott, 2.6.3) Prove directly from the definition of Cauchy sequence that if $x_n$ and $y_n$ are Cauchy sequences, then $x_n+y_n$ is a Cauchy sequence.

## Week 5, due Wednesday, February 15

1. (Abbot, 2.3.4) Suppose that $\lim a\_n=0$. Find, with justification, each of the following limits.  
  * $\lim \frac{1+2a\_n}{1+3a\_n-4a\_n^2}$
  * $\lim \frac{(a\_n+2)^2-4}{a\_n}$
  * $\lim \frac{\frac{2}{a\_n}+3}{\frac{1}{a\_n}+5}$
2. Find, with justification, the following limit.
  * $\lim n-\sqrt{n^2+2n}$
2. Show that if $\lim a\_n=a$ and $a\neq0$ and $\lim a\_nb\_n=ab$ then $\lim b\_n=b$.
3. Let $p$ be any real number. Prove that $\sum\frac1{n^p}$ converges if and only if $p>1$. (This is called the ``$p$-test.'' To solve this problem you may use the well-known fact that a geometric series $\sum r^n$ converges iff $\abs{r}\lt1$.)
4. Let $x\_n$ be the sequence indicated below. Write down a recurrence for the sequence $x\_n$ (that is, a formula for $x\_{n+1}$ in terms of $x\_n$). Use induction to prove that the sequence is both bounded and monotone. Prove that the sequence converges. Finally, find the limit.  
  $x\_1=\sqrt{2},x\_2=\sqrt{2+\sqrt{2}},x\_3=\sqrt{2+\sqrt{2+\sqrt{2}}}$, $\ldots$  

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
