## Homework 5, due Tuesday, February 25 at 3pm
1. Show that if $\lim a\_n=a$ and $a\neq0$ and $\lim a\_nb\_n=ab$ then $\lim b\_n=b$.
2. Give an example of sequences $a\_n$ such that:
  * $\lim a\_n=\sup a\_n$
  * $\lim a\_n=\inf a\_n$
  * $\lim a\_n$ exists and is neither $\sup a\_n$ nor $\inf a\_n$
3. Let $a\_n$ and $b\_n$ be sequences, and let $c\_n$ be the ``shuffled'' sequence $\{a\_1,b\_1,a\_2,b\_2,\ldots\}$. Show that $c\_n$ is convergent if and only if $a\_n$ and $b\_n$ are both convergent and both have the same limit.
4. ...

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
