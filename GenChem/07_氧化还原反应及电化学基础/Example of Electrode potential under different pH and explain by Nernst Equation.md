
Let's consider the example of a hydrogen electrode, where the redox reaction is:

\[ 2H^+ + 2e^- \rightarrow H_2(g) \]

The standard electrode potential for this reaction, \(E^\circ\), is defined at standard conditions, which include a pH of 0 (where \([H^+] = 1 \text{ M}\)) and standard pressure for hydrogen gas (1 atm).

### Nernst Equation Applied to the Hydrogen Electrode
The Nernst equation for this half-cell reaction is:

\[
E = E^\circ - \frac{RT}{nF} \ln \frac{[H_2]}{[H^+]^2}
\]

At standard temperature (\(25^\circ C\) or 298 K), the equation simplifies to:

\[
E = E^\circ - \frac{0.0591}{2} \log \frac{[H_2]}{[H^+]^2}
\]

Since \([H_2]\) is typically at 1 atm (standard condition), the equation further simplifies to:

\[
E = E^\circ - 0.0591 \times \text{pH}
\]

### Example: Electrode Potential at Different pH Values
Let's calculate the electrode potential for the hydrogen electrode at two different pH values.

1. **At pH 0:**
   - \(\text{pH} = 0\), so \([H^+] = 1 \text{ M}\).
   - Substituting into the simplified Nernst equation:
     \[
     E = E^\circ - 0.0591 \times 0 = E^\circ
     \]
   - The electrode potential \(E\) at pH 0 is equal to the standard electrode potential, \(E^\circ = 0.00\) V (by definition for the standard hydrogen electrode).

2. **At pH 7:**
   - \(\text{pH} = 7\), so \([H^+] = 10^{-7} \text{ M}\).
   - Substituting into the Nernst equation:
     \[
     E = 0.00 \text{ V} - 0.0591 \times 7 = -0.4137 \text{ V}
     \]
   - The electrode potential \(E\) at pH 7 is \(-0.4137\) V.

### Explanation:
The Nernst equation shows that the electrode potential is directly influenced by the pH (which reflects the \([H^+]\) concentration). As pH increases (indicating a decrease in \([H^+]\)), the electrode potential becomes more negative. This occurs because the reaction is less favorable at higher pH levels, requiring a more negative potential to drive the reduction of protons to hydrogen gas.

In essence, the Nernst equation demonstrates how changing the concentration of hydrogen ions (as represented by pH) alters the electrode potential, reflecting the shift in equilibrium of the redox reaction.