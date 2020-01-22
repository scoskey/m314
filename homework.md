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