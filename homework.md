---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/480803)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 14, due Wednesday, April 26

1. Consider the function $f(x)=1/x$ on the domain $[1,4]$. Find a partition $P$ such that $U(f,P)$ and $L(f,P)$ are less than $0.01$ units apart.
2. Let $h(x)$ be the function on $[0,1]$ defined by  
  $h(x)=\begin{cases}1&x<1\\\\2&x=1\end{cases}$  
  (a) For any $P$, what is the value of $L(f,P)$?  
  (b) Can you find a $P$ such that $U(f,P)$ is within $0.05$ of $L(f,P)$?  
  (c) Is $h$ integrable? Why or why not?
3. A vehicle drives on a freeway with speed limit 70mph. Trooper Millie Van Teeter observes the vehicle pass mile marker 53 at 2pm, and later trooper Miles Von Trotter observes the vehicle pass mile marker 271 at 5pm. Help the troopers prove to the court that the vehicle was speeding for at least some portion of its trip.
4. (Abbott, ex 7.5.4) Let $f$ be a continuous function on $[a,b]$ and assume that $\int_a^xf(t)\,dt=0$ for all $x$. Show that $f=0$.

   Give a counterexample to show that the statement is false if $f$ is not assumed to be continuous.


## Week 13, due Wednesday, April 19

1. Suppose that $f$ is continuous on $[a,b]$ and that for every $n\in\mathbb N$ there exists $x\in[a,b]$ such that $\abs{f(x)}\leq\frac1n$. Show that there exists $x\in[a,b]$ such that $f(x)=0$.
2. Show that the equation $2^x+3^x=4^x$ has a solution. [Hint: apply the Intermediate Value Theorem on an appropriate interval. You may assume we know exponential functions are continuous.]
3. Prove *Rolle's thoerem*, which states that if $f$ is a differentiable function, $a\lt b$, and $f(a)=f(b)$, then there exists $c$ such that $a\lt c\lt b$ and $f'(c)=0$. [Hint: let $c$ be an extreme value of $f$.]
4. Let $f(x)$ be the function:  
  $f(x)=\begin{cases}x^a&x\geq0\\\\0&x<0\end{cases}$  
  (a) For which values of $a$ is $f$ continuous at $0$?  
  (b) For which values of $a$ is $f'(0)$ defined?  
  (c) For which values of $a$ is $f''(0)$ defined?

## Week 12, due Wednesday, April 12

1. Prove part (c) of the funcional limit calculus theorem: If $\lim\_{x\to a}f(x)=L$ and $\lim\_{x\to a}g(x)=M$ then $\lim\_{x\to a}f(x)g(x)=LM$.
2. (Abbott, ex 4.2.11) Prove the squeeze theorem for functional limits: if $f(x)\leq g(x)\leq h(x)$ and $\lim\_{x\to a}f(x)=\lim\_{x\to a}h(x)=L$ then $\lim_{x\to a}g(x)$ exists and $=L$. You may use either characterization of functional limit.
3. Let $f(x)$ be the function defined below. Prove that for every real number $a$, $f$ is discontinuous at $a$.  
  $f(x)=\begin{cases}1&x\in\mathbb Q\\\\0&x\notin\mathbb Q\end{cases}$
4. Find an example of functions $f,g$ such that $f,g$ are both discontinuous at $0$ but $f+g$ is continuous at $0$.
5. (Abbott, ex 4.3.9) Let $f$ be a continuous function and let $Z=\set{x\mid f(x)=0}$ (the zeroes or roots of the function). Prove that $Z$ is closed.

## Week 11, due Wednesday, April 5

1. If $A,B$ are connected subsets of $\mathbb R$, show that $A\cap B$ is connected. Is this true for connected subsets $A,B$ of $\mathbb R^2$? Explain why it is true or draw a counterexample.
2. Let $A$ be a subset of $\mathbb R^n$.  
  (a) Show that any open set which meets $\partial A$ also meets $A$.  
  (b) Show that if $A$ is connected then $A\cup\partial A$ is connected (this set is called the *closure* of $A$).
3. Let $X$ be a metric space with distance function $d$. Show that for any $\epsilon>0$ the neighborhood $N_\epsilon(x)$ is open.
4. Let $X$ be a metric space with distance function $d$. We defined that a set $A$ is closed if $\partial A\subset A$. The text defines that $A$ is closed if every sequence in $A$ which converges has its limit in $A$. Show that the two definitions agree.

## Week 10, due Wednesday, March 29

1. Give an example of a sequence of open sets $A\_n$ such that $\bigcap A\_n$ is *not* open. Give an example of a sequence of closed sets $B\_n$ such that $\bigcup B\_n$ is *not* closed.
2. Show that $A$ is clopen (both open and closed) if and only if $\partial A=\emptyset$.
3. Show that if $A$ is compact then $\sup(A)$ exists and $\sup(A)\in A$.
4. In the following proofs, refer the "subsequential limit" definition of compactness, (not the Heine--Borel characterization).  
  (a) Show that if $A$ and $B$ are both compact then $A\cup B$ is compact.  
  (b) Show that if $A$ is closed, $B$ is compact, and $A\subset B$, then $A$ is compact.  
5. Show that for any set $A$, $\partial A$ is closed. Then, use the previous exercise plus the Heine--Borel theorem to show that if $A$ is compact then $\partial A$ is compact.

## Week 9, due Wednesday, March 15 

1. Give an example of two convergent series $\sum a\_n$ and $\sum b\_n$ such that $\sum a\_nb\_n$ diverges. Why doesn't this contradict Homework 7, exercise 3?
2. Suppose that $\sum a\_n$ converges absolutely and that the sequence $b\_n$ is bounded. Prove that $\sum a\_nb\_n$ converges absolutely.
3. Suppose that $\sum a\_n$ converges conditionally. Show that the series consisting of just the positive terms is divergent.
4. For $0<\alpha<1$, the modified Cantor set $C^\alpha$ is constructed by starting with $B_0=[0,1]$ and recursively letting $B_{n+1}$ be the set obtained by removing the middle $\alpha$ fraction of each interval of $B_n$. Find the length of $C^\alpha$.
5. Find the fractal dimension of $C^\alpha$. Hint: use a scaling factor that grows both intervals in $B_1$ to a length of $1$.

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
