## Homework 9, due Tuesday, April 14

1. In the following proofs, refer the "subsequential limit" definition of compactness, (not the Heine--Borel characterization).  
  (a) Show that if $A$ and $B$ are both compact then $A\cup B$ is compact.  
  (b) Show that if $A$ is closed, $B$ is compact, and $A\subset B$, then $A$ is compact.  
  (c) Show that if $B$ is compact then $\partial B$ is compact. [Hint: Show a boundary is closed, and then use the previous item.]
2. (a) Suppose that $A$ is a closed subset of $\mathbb R$ which is bounded above. Show that $\sup(A)\in A$.  
  (b) Suppose that $A$ is an open subset of $\mathbb R$ which is bounded above. Show that $\sup(A)\notin A$.
3. ...

## Homework 8, due Tuesday, March 31

1. Give an example of two convergent series $\sum a\_n$ and $\sum b\_n$ such that $\sum a\_nb\_n$ diverges. (Compare with the previous homework.)
2. Suppose that $\sum a\_n$ converges absolutely and that the sequence $b\_n$ is bounded. Prove that $\sum a\_nb\_n$ converges absolutely.
3. Suppose that $\sum a\_n$ converges conditionally. Show that the series consisting of just the positive terms is divergent.
4. Give an example of a sequence of open sets $A\_n$ such that $\bigcap A\_n$ is *not* open. Give an example of a sequence of closed sets $B\_n$ such that $\bigcup B\_n$ is *not* closed.
5. Show that $A$ is clopen (both open and closed) if and only if $\partial A=\emptyset$.

## Homework 7, due Tuesday, March 17 at 3pm

1. Suppose that $a\_n,b\_n\geq0$ and that $\sum a\_n$ and $\sum b\_n$ both converge. Prove that $\sum a\_nb\_n$ converges.
2. Give an example of two divergent series $\sum a\_n$ and $\sum b\_n$ such that $\sum a\_nb\_n$ converges.
3. Please complete and polish all activity exercises for Section 12.

## Homework 6, due Tuesday, March 10 at 3pm

1. The following quantifier statement is a small modification of the definition of convergence:  
   $(\forall\epsilon>0)(\forall N\in\mathbb N)(\exists n>N)\,|a\_n-L|<\epsilon$  
   Prove that this statement is true if and only if there exists a subsequence $a\_{n\_k}$ which converges to $L$.
2. Prove or give a counterexample: If $a\_n$ has a subsequence which converges to $a$ and $b\_n$ has a subsequence which converges to $b$ then $a\_n+b\_n$ has a subsequence converging to $a+b$.
3. Consider the sequence defined as follows: $a\_n=$ the reciprocal of the least prime factor of $n$. Write out the first 20 terms of $a\_n$. Find two subsequences of $a\_n$ that converge to two different limits.
4. Find an example of a divergent sequence $a\_n$ which satisfies $\lim(a\_{n+1}-a\_n)=0$.
5. In this exercise you will show MCT implies BWT. Together with our work from class, we can conclude MCT is yet another equivalent to AOC. To begin, we say that a term $a\_n$ of a sequence is a *peak* if for all $n'>n$ we have $a\_n'\leq a\_n$.
  * Assume the sequence $a\_n$ has infinitely many peaks. Show that $a\_n$ has a monotone decreasing subsequence.
  * Assume the sequence $a\_n$ has a last peak. Conclude that $a\_n$ has a monotone increasing subsequence.
  * Use parts (a) and (b) together with the MCT to prove the BWT.

## Homework 5, due Tuesday, March 3 at 3pm

1. Show that if $\lim a\_n=a$ and $a\neq0$ and $\lim a\_nb\_n=ab$ then $\lim b\_n=b$.
2. Give an example of sequences $a\_n$ such that:
  * $\lim a\_n=\sup a\_n$
  * $\lim a\_n=\inf a\_n$
  * $\lim a\_n$ exists and is neither $\sup a\_n$ nor $\inf a\_n$
3. Let $a\_n$ and $b\_n$ be sequences, and let $c\_n$ be the ``shuffled'' sequence $\{a\_1,b\_1,a\_2,b\_2,\ldots\}$. Show that $c\_n$ is convergent if and only if $a\_n$ and $b\_n$ are both convergent and both have the same limit.
4. Let $p$ be any real number. Prove that $\sum\frac1{n^p}$ converges if and only if $p>1$. (This is called the ``$p$-test.'')
5. For each sequence, use induction to prove that the sequence is bounded and monotone. Then, find the limit.
  * The sequence defined by $x\_1=1$ and the recurrence $x\_{n+1}=\frac12x\_n+1$
  * $\sqrt{2},\sqrt{2+\sqrt{2}},\sqrt{2+\sqrt{2+\sqrt{2}}},\ldots$
  * $\sqrt{2},\sqrt{2\sqrt{2}},\sqrt{2\sqrt{2\sqrt{2}}},\ldots$  
  [Note: For the final two you will have to find the recurrence yourself! You may use the fact that $\lim\sqrt{a\_n}=\sqrt{\lim a\_n}$.]

## Homework 4, due Thursday, February 13 at 3pm

1. Let $A$ be a set of real numbers and suppose that $A$ is bounded above. Let $B$ be the set of upper bounds for $A$. Show that $\sup(A)=\inf(B)$.
2. Let $a\_n$ be a sequence of real numbers and assume that $a\_n\leq a\_{n+1}$ for all $n$. Let $\alpha=\sup\set{a_n\mid n\in\mathbb N}$. Show that for all $\epsilon$, just finitely many terms of the sequence are $\leq\alpha-\epsilon$.
3. (Abbott, ex 2.2.1) Suppose we swap the first two quantifiers in the definition of convergence, and write $x\_n$ *verconges* to $L$ if:  
   $(\exists\epsilon>0)\;(\forall N\in\mathbb N)\;(\forall n\geq N)\;|x_n-L|<\epsilon$.  
   Give an example of a vercongent sequence that is not convergent. What exactly is being described in this definition?
4. Suppose that $A\subset\mathbb R$ is bounded and that $\alpha=\sup(A)$.  This exercise shows how to prove that there exists a sequence in $A$ which converges to $\alpha$.
  * Prove that for each $n\in\mathbb N$ there exists $a\_n\in A$ such that $a_n>\alpha-1/n$.
  * Use the definition of convergence to conclude that $\lim a\_n=\alpha$.

## Homework 3, due Tuesday, February 4 at 3pm

1. Suppose that for every $n$, the set $A\_n$ is countable. Show that the set $A=\bigcup A\_n$ is countable. [See the hint described in Exercise~1.5.3(c).]
2. Show that the set $\mathbb N^3$ is countable. Here $\mathbb N^3$ consists of all triples of the form $(a,b,c)$, where $a,b,c\in\mathbb N$.
3. Let $S\_\text{fin}$ be the set of all *finite* words made with the letters $a,b$. So $S$ contains elements like $ab$, $abb$, $ababa$, $aabbbbaa$, and so forth. Prove that $S\_\text{fin}$ is countable.
4. Read your proof from the activity that $S\_{\infty}$ is uncountable. Why doesn't this proof work for $S_\text{fin}$? Explain precisely where and why it fails.
5. (Abbott, ex 1.5.10(a)) Let $A\subset[0,1]$ and assume that $A$ is uncountable. Show that there exists $a>0$ such that $A\cap[a,1]$ is uncountable.

## Homework 2, due Tuesday, January 28 at 3pm

1. Prove or give a counterexample: If $A$ and $B$ are sets of real numbers such that $a\lt b$ for all $a\in A$ and $b\in B$, then $\sup(A)\lt\inf(B)$.
2. Read the characterization of supremum described in Abbott, Lemma~1.3.8. Then, give a thorough proof that $1/2$ is the supremum of the set $\set{n/(2n+1)\mid n\in\mathbb N}$. Point out the exact moment in the proof when the Archimedean Property is used.
3. Consider the sequence defined by $x\_1=0$ and $x\_{n+1}=\sqrt{2+x\_n}$. Prove using induction that for all $n$, $x\_n\lt 2$. Prove using induction that for all $n$, $x\_n\lt x\_{n+1}$.

## Homework 1, due Thursday, January 23 at 3pm

1. (Abbott, ex 8.6.2). Suppose that $C$ is a cut, $q\in C$, and that $r$ is a rational number such that $r\notin C$. Show that $q\lt r$.
2. (Abbott, ex 1.2.1)
  * Study the proof that there is no rational number $q$ such that $q^2=2$. Modify this proof to show that there is no rational number $q$ such that $q^2=3$.
  * Obviously there *is* a rational number such that $q^2=4$, so your proof in the previous part cannot work if $3$ is replaced by $4$. But where *exactly* does the proof break down?
3. Let $A$ and $B$ be points in the plane.
  * Suppose that $A$ is $3$ units away from the origin and $B$ is $5$ units away from the origin. What is the farthest $A$ and $B$ can be from each other? The closest?
  * Now generalize. Suppose that $A$ is $\abs{A}$ units away from the origin and that $B$ is $\abs{B}$ units away from the origin.  Use the notation $\abs{A-B}$ for the distance between $A$ and $B$. Can you write two rules that generalize your two answers from the previous part? (Explain your answer with a picture. You do not need to give a proof.)
4. Modify a proof given in class to instead show that the cut $\set{q\in\mathbb Q\mid q^3<2}$ has no last element.
5. (Abbott, ex 8.6.3) Read the definition of a "field" of numbers and note the list of properties which must be true of a field. Which of these properties are satisfied in $\mathbb N$? In $\mathbb Z$? In $\mathbb Q$?


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
