
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']]
    }
  };
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

---

[Vissza](../matematika.md)

---

1. Feladat
$$
\begin{array}{|c|c|c|c|c|c|}
\hline
a & b & c & \alpha & \beta & \gamma \\
\hline
10\text{ cm}  & 6\text{ cm} & & & 30^{\circ} & \\
\hline
\end{array}
$$
$$
\begin{aligned}
\\[1em]
\frac{\sin\alpha}{a} &= \frac{\sin\beta}{b} \\
\frac{\sin\alpha}{10} &= \frac{\sin30^{\circ}}{6} \quad / \cdot 10 \\
\sin\alpha &= \frac{10 \cdot \sin 30^{\circ}}{6} \\
\sin\alpha &= 0.833 \\[2em]
c^{2} &= 10^{2} + 6^{2} - 2 \cdot 10 \cdot 6 \cdot \cos93.6^{\circ} = 136 - 120 \cdot 0.062 = 136 + 7.44 = 143.44 \\
c &= \sqrt{143.44} = 11.97
\end{aligned}
$$

---

2. Feladat
$$
\begin{array}{|c|c|c|c|c|c|}
\hline
a & b & c & \alpha & \beta & \gamma \\
\hline
10 & 15 & & & & 60^{\circ} \\
\hline
\end{array}
$$
$$
\begin{aligned}
\\[1em]
c^{2} &= a^{2} + b^{2} - 2ab \cdot \cos\gamma = 10^{2} + 15^{2} - 2 \cdot 10 \cdot 15 \cdot \cos60^{\circ} = 325 - 300 \cdot 0.5 = 325 - 150 = 175 \\
c &= \sqrt{175} = 13.23 \\
\frac{\sin}{a} &= \frac{\sin\gamma}{c} = \frac{\sin\alpha}{10} = \frac{\sin60^{\circ}}{13.23} \quad / \cdot 10 \\
\sin\alpha &= \frac{10 \cdot \sin60^{\circ}}{13.23} = \frac{10 \cdot 0.866}{13.23} = \frac{8.66}{13.23} = 0.65 \\
\alpha &= \sin^{-1}(0.65) = 40.54^{\circ}
\end{aligned}
$$

---

## Háromszög Terület
$T = \frac{a \cdot b \cdot \sin\gamma}{2}$

### feladat
$$
\begin{array}{|c|c|c|c|c|c|}
\hline
a & b & c & \alpha & \beta & \gamma \\
\hline
& 5 & 6 & 70^{\circ} & & \\
\hline
\end{array}
$$
$$
\begin{aligned}
\\[1em]
a^{2} &= b^{2} + c^{2} - 2bc \cdot \cos\alpha = 5^{2} + 6^{2} - 2 \cdot 5 \cdot 6 \cdot \cos70^{\circ} = 61 - 60 \cdot 0.342 = 61 - 20.52 = 40.48 \\
a = \sqrt{40.48} &= 6.36 [1em]\\
\frac{\sin\beta}{b} &= \frac{\sin\alpha}{a} = \frac{\sin\beta}{5} = \frac{\sin70^{\circ}}{6.36} \quad / \cdot 5 \\
\sin\beta = \frac{5 \cdot \sin70^{\circ}}{6.36} = \frac{4.699}{6.36} = 0.74 \\
\beta = \sin^{-1}(0.74) = 47.73^{\circ} \\[1em]
\gamma = 180^{\circ} - ('70^{\circ} + 47.73^{\circ}) = 62.27^{\circ} \\[1em]
T = \frac{6.36 \cdot 5 \cdot \sin0.62.27^{\circ}}{2} = \frac{28.15}{2} = 14.075 \\
\text{paralelogramma terület} = 2 \cdot 14.075 = 28.15
\end{aligned}
$$
