# Problem 001 — A simple example in structure breakdown

**Problem:**  
Find all integer solutions to  
\[ x^2 - 5x + 6 = 0. \]

---

## 1. Standard solution  
Factor:
\[
x^2 - 5x + 6 = (x-2)(x-3)
\]
Solutions:  
\[
x = 2,\quad x = 3.
\]

---

## 2. Why standard solution feels trivial (but still structural)  
Most students memorize:
- "factor if possible"
- "use quadratic formula"

But they rarely see *why factoring works*.

---

## 3. Structural breakdown (my method)

### 🔹 Step 1 — Detect the **energy minimum**  
Quadratics always form a **single well**.  
The question is:  
> “Where does the path hit zero?”

### 🔹 Step 2 — Look for **two symmetric steps** around the parabola  
We want:
\[
x^2 - 5x + 6 = 0
\]

Rewrite as:
\[
x(x-5) = -6
\]

This equation says:

> *Find a number and its shift by 5 whose product equals -6.*  
This forces the pair to come from factors of -6:
\[
(-1,6),\ (-2,3),\ (-3,2),\ (-6,1)
\]

Only the middle two pair satisfy distance = 5 →  
\[
2,3
\]

This is the **structural reason** factoring works here:
- the "5" forces distance  
- the "6" forces product  
- only one pair matches both constraints

---

## 4. Why humans get stuck  
Because they try to recall:
- “Which trick applies?”
Instead of asking:
- “What structure restricts the solution space?”

---

## 5. Key Insight  
Quadratics = 1D wells.  
Solving them = finding where the well hits zero.  
Factoring = matching **distance vs product constraints**.

Even the simplest problem has clean structure under it.
