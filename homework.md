---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 314 homework

[Submit with gradescope](https://www.gradescope.com/courses/218674)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 1, due Tuesday, January 19 at 12pm

1. Prove or give a counterexample.
  * A rational number times a rational number is a rational number.
  * A rational number plus a rational number is a rational number.
  * A rational number times an irrational number is an irrational number.
  * A rational number plus an irrational number is a irrational number.
  * An irrational number times an irrational number is an irrational number.
2. (Abbott, ex 8.6.2). Suppose that $C$ is a cut, $q\in C$, and that $r$ is a rational number such that $r\notin C$. Show that $q\lt r$.
3. (Abbott, ex 1.2.1)
  * Study the proof that there is no rational number $q$ such that $q^2=2$. Modify this proof to show that there is no rational number $q$ such that $q^2=3$.
  * Obviously there *is* a rational number such that $q^2=4$, so your proof in the previous part cannot work if $3$ is replaced by $4$. But where *exactly* does the proof break down?
4. ...



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
