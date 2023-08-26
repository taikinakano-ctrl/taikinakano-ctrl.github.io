---
permalink: /about/
layout: home
---

<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML">
</script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true},
      jax: ["input/TeX","input/MathML","input/AsciiMath","output/CommonHTML"],
      extensions: ["tex2jax.js","mml2jax.js","asciimath2jax.js","MathMenu.js","MathZoom.js","AssistiveMML.js", "[Contrib]/a11y/accessibility-menu.js"],
      TeX: {
      extensions: ["AMSmath.js","AMSsymbols.js","noErrors.js","noUndefined.js"],
      equationNumbers: {
      autoNumber: "AMS"
      }
    }
  });
</script>

![Alt text](https://assets.digitalocean.com/articles/alligator/boo.svg "a title")

This is an inline equation: $$V_{sphere} = \frac{4}{3}\pi r^3$$,<br>
followed by a display style equation:

$$V_{sphere} = \frac{4}{3}\pi r^3$$

\begin{align}
  V_{sphere} = \frac{4}{3}\pi r^3 \label{eq:test1}
\end{align}

In Eq. $\eqref{eq:test1}$ you can see...while in Eq. $\eqref{eq:test2}$...

\begin{align}
  V_{cube} = l w h \label{eq:test2}
\end{align}