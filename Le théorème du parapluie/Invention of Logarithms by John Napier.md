
### John Napier and the Invention of Logarithms

**John Napier (1550–1617)**, a Scottish mathematician, is credited with inventing logarithms. His work on logarithms began around 1594, and he published his findings in 1614 in a book titled _Mirifici Logarithmorum Canonis Descriptio_ (Description of the Wonderful Canon of Logarithms).

#### Napier’s Motivation

Napier's motivation for developing logarithms was to simplify complex arithmetic operations, particularly those involving large numbers, which were common in astronomy. By transforming multiplication into addition, division into subtraction, and exponentiation into multiplication, Napier’s logarithms significantly reduced the time and effort required for calculations.

#### Napier’s Concept of Logarithms

Napier’s original logarithms were not like the base-10 or natural logarithms (base eee) that we commonly use today. Instead, Napier constructed his logarithms based on geometric progressions.

- **Geometric Progression**: Napier considered a point moving along a line segment at a speed proportional to its distance from a fixed endpoint. The position of this moving point after a given time could then be represented by a logarithm.
- **Conceptual Basis**: His logarithms were designed such that multiplying two numbers corresponded to adding their logarithms, thus simplifying the calculation process.

Certainly! Let’s dive deeper into John Napier’s original concept of logarithms and his method of describing them through a geometric and kinematic analogy.

### Napier's Conceptual Model for Logarithms

John Napier, in his invention of logarithms, used a conceptual model involving motion along a line segment. This analogy helped him define logarithms in terms of ratios of distances, which aligns with the multiplicative properties of logarithms. Here’s how his model works:

1. **Line Segment and Points in Motion:**
   - Imagine a line segment extending infinitely in one direction.
   - Place two points, \(A\) and \(P\), on this line such that \(A\) is fixed and \(P\) is moving along the line away from \(A\).

2. **Speed Proportional to Distance:**
   - Let’s consider that the point \(P\) starts moving from point \(A\) with a certain speed.
   - Napier’s idea was to have the speed of \(P\) be inversely proportional to its distance from point \(A\). In other words, as \(P\) moves further away from \(A\), it moves slower and slower.
   - Mathematically, if the distance from \(A\) to \(P\) at any time \(t\) is \(x(t)\), then the speed (or rate of movement) of \(P\) could be defined as being proportional to \(\frac{1}{x(t)}\).

3. **Relationship to Logarithms:**
   - Napier was essentially setting up a situation where, as time progresses, the position of \(P\) represents the logarithm of a number.
   - If we assume that \(P\) starts at \(x(0) = 1\), then as \(t\) increases, \(x(t)\) grows in such a way that the distance it covers grows according to a logarithmic scale. 

4. **Logarithmic Growth:**
   - Let’s say that after some time \(t\), the point \(P\) reaches a position \(x(t)\). The key idea is to define the logarithm of \(x(t)\) based on the time \(t\) taken to reach that point.
   - Napier effectively created a logarithmic scale where the time taken to reach a certain distance from \(A\) corresponds to the logarithm of that distance.

### How This Relates to Logarithms

To better understand Napier’s method, let’s put this into the context of modern logarithms:

- **Differential Equation Representation:**
  Napier’s idea can be framed as a differential equation where the rate of change of \(x(t)\) with respect to time \(t\) is inversely proportional to \(x(t)\):
  
  \[
  \frac{dx}{dt} = \frac{-1}{x(t)}
  \]

  Solving this differential equation gives us:

  \[
  x(t) = e^{-t}
  \]

  which means that \(t = -\ln(x(t))\). Here, \( \ln(x) \) represents the natural logarithm.

- **Logarithmic Proportions:**
  If we rearrange for \(t\), it shows that the time \(t\) it takes for point \(P\) to move to a distance \(x(t)\) is proportional to the logarithm of \(x(t)\). In this model, the logarithmic relationship emerges naturally from the rate of change being inversely proportional to the distance.

- **Transition from Napier’s Logarithms to Common Logarithms:**
  Napier’s logarithms were not logarithms in the base-10 or base-\(e\) sense but instead were formulated in a similar fashion. They represented the idea of logarithms as a tool for converting multiplication into addition by capturing growth rates and proportional changes. Henry Briggs later refined this idea to create the base-10 logarithms (common logarithms), which were easier to use with decimal numbers and became widely adopted.

### Summary

Napier's innovative use of a moving point on a line to conceptualize logarithms was a profound idea because it turned a complex multiplication problem into an addition problem by using motion and rates of change. His approach relied on understanding how quantities change over time and translating those changes into a new numerical scale — the logarithmic scale. This fundamentally changed how calculations were performed, especially in the context of scientific and astronomical computations, and laid the foundation for the logarithmic functions we use today.

*It is amazing to notice Napier adopt a calculus idea at time when differential had not been invented*

