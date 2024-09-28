
Let's consider the redox reaction involving the permanganate ion (\(\text{MnO}_4^-\)) and its reduction to manganese dioxide (\(\text{MnO}_2\)) in different pH environments. This is a classic example in aqueous solutions where the redox potential varies significantly with pH.

### Redox Reaction

In acidic conditions:
\[
\text{MnO}_4^- + 8H^+ + 5e^- \rightarrow \text{Mn}^{2+} + 4H_2O
\]

In neutral or basic conditions:
\[
\text{MnO}_4^- + 2H_2O + 3e^- \rightarrow \text{MnO}_2 + 4OH^-
\]

### Nernst Equation for Acidic and Basic Conditions

#### **1. Acidic Conditions (Low pH)**
In acidic medium, the reduction of permanganate ion to manganese(II) ion involves protons (\(H^+\)):

\[
E = E^\circ - \frac{RT}{nF} \ln \frac{[\text{Mn}^{2+}]}{[\text{MnO}_4^-][H^+]^8}
\]

At 25°C (298 K), this simplifies to:

\[
E = E^\circ - \frac{0.0591}{5} \log \left(\frac{[\text{Mn}^{2+}]}{[\text{MnO}_4^-][H^+]^8}\right)
\]

Given that the pH directly affects \([H^+]\), the electrode potential is highly sensitive to pH changes.

#### **2. Basic or Neutral Conditions (High pH)**
In a basic or neutral environment, permanganate is reduced to manganese dioxide:

\[
E = E^\circ - \frac{RT}{nF} \ln \frac{[\text{MnO}_2][OH^-]^4}{[\text{MnO}_4^-]}
\]

This simplifies to:

\[
E = E^\circ - \frac{0.0591}{3} \log \left(\frac{[\text{MnO}_2][OH^-]^4}{[\text{MnO}_4^-]}\right)
\]

Again, \([OH^-]\) is related to pH (\(pOH = 14 - pH\)), showing that the redox potential varies with the concentration of hydroxide ions, which increase as pH increases.

### Example: Electrode Potential at Different pH Values

#### **1. Acidic Conditions (pH 1):**
- **Conditions:**
  - \(\text{pH} = 1\), so \([H^+] = 10^{-1} \text{ M}\).
  - Assume \([\text{Mn}^{2+}] = [\text{MnO}_4^-] = 1 \text{ M}\) for simplicity.
- **Substituting into the Nernst equation:**
  \[
  E = E^\circ - \frac{0.0591}{5} \log \left(\frac{1}{1 \times (10^{-1})^8}\right)
  \]
  \[
  E = E^\circ - \frac{0.0591}{5} \times (-8) = E^\circ + 0.0946 \text{ V}
  \]

#### **2. Neutral Conditions (pH 7):**
- **Conditions:**
  - \(\text{pH} = 7\), so \([H^+] = 10^{-7} \text{ M}\).
  - Assume \([\text{Mn}^{2+}] = [\text{MnO}_4^-] = 1 \text{ M}\).
- **Substituting into the Nernst equation:**
  \[
  E = E^\circ - \frac{0.0591}{5} \log \left(\frac{1}{1 \times (10^{-7})^8}\right)
  \]
  \[
  E = E^\circ - \frac{0.0591}{5} \times (-56) = E^\circ + 0.663 V
  \]

In basic conditions, where the reduction is to MnO\(_2\), the equation changes accordingly.

#### **Basic Conditions (pH 13):**
- **Conditions:**
  - \(\text{pH} = 13\), so \([OH^-] = 10^{-1} \text{ M}\).
  - Assume \([\text{MnO}_2] = [\text{MnO}_4^-] = 1 \text{ M}\).
- **Substituting into the Nernst equation:**
  \[
  E = E^\circ - \frac{0.0591}{3} \log \left(\frac{1 \times (10^{-1})^4}{1}\right)
  \]
  \[
  E = E^\circ - \frac{0.0591}{3} \times (-4) = E^\circ + 0.0788 \text{ V}
  \]

### Explanation:

- **At low pH (acidic),** the electrode potential is relatively high due to the high proton concentration, making the reduction of permanganate to Mn\(^{2+}\) more favorable.
  
- **At high pH (basic),** the potential shifts depending on whether MnO\(_2\) or Mn\(^{2+}\) is the reduction product. The higher pH lowers the proton concentration, making the reduction less favorable, so the electrode potential is more negative in basic conditions.

This example illustrates how the redox potential for manganese compounds varies significantly with pH, demonstrating the importance of pH in redox chemistry.