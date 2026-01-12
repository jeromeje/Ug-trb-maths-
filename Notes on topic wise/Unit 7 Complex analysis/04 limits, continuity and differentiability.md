
---

# UNIT VII – COMPLEX ANALYSIS  
## Topic 4: Limits, Continuity and Differentiability of Complex Functions

---

## 1. Limit of a Complex Function (Recap)

Let  
\[
f(z) = u(x,y) + iv(x,y)
\]

The limit  
\[
\lim_{z \to z_0} f(z) = w_0
\]
exists if the value of \( f(z) \) approaches the same complex number along **all possible paths**.

---

## 2. Continuity of a Complex Function – Definition

A complex function \( f(z) \) is said to be **continuous at a point \( z_0 \)** if:

1. \( f(z_0) \) exists  
2. \( \lim_{z \to z_0} f(z) \) exists  
3.  
\[
\lim_{z \to z_0} f(z) = f(z_0)
\]

---

## 3. Tamil Meaning (தொடர்ச்சி – Continuity)

ஒரு சிக்கலெண் செயல்பாடு \( f(z) \),  
ஒரு புள்ளி \( z_0 \) இல்,

- அதன் மதிப்பு இருக்க வேண்டும்  
- அதன் limit இருக்க வேண்டும்  
- limit மற்றும் செயல்பாட்டின் மதிப்பு சமமாக இருக்க வேண்டும்  

அப்போது, \( f(z) \) **தொடர்ச்சியானது (Continuous)** எனப்படும்.

---

## 4. Example on Continuity

### Example:
\[
f(z) = z^2
\]

Since polynomial functions are continuous everywhere,

\[
f(z) \text{ is continuous for all } z
\]

---

## 5. Differentiability of a Complex Function – Definition

A function \( f(z) \) is said to be **differentiable at \( z_0 \)** if the limit

\[
\lim_{h \to 0} \frac{f(z_0 + h) - f(z_0)}{h}
\]

exists and is finite.

This limit is called the **derivative of \( f(z) \)** at \( z_0 \).

---

## 6. Tamil Meaning (Differentiability)

ஒரு சிக்கலெண் செயல்பாடு  
\[
f'(z_0) = \lim_{h \to 0} \frac{f(z_0 + h) - f(z_0)}{h}
\]
என்ற limit எல்லாத் திசைகளிலும் ஒரே மதிப்பாக இருந்தால்,  
அந்த புள்ளியில் **Differentiable** எனப்படும்.

---

## 7. Important Difference (TRB Point)

🔹 **Continuity ≠ Differentiability**  
🔹 Differentiability ⇒ Continuity  
🔹 Continuity ⇏ Differentiability

---

## 8. Example Showing Non-Differentiability

### Example:
\[
f(z) = |z|^2 = x^2 + y^2
\]

Though continuous everywhere,  
it is **NOT differentiable** anywhere.

---

## 9. Theorem: Differentiability Implies Continuity

### Statement:
If a complex function \( f(z) \) is differentiable at \( z_0 \),  
then it is continuous at \( z_0 \).

---

## 10. Proof (Outline)

Given:
\[
f'(z_0) = \lim_{h \to 0} \frac{f(z_0 + h) - f(z_0)}{h}
\]

As \( h \to 0 \),
\[
f(z_0 + h) \to f(z_0)
\]

Hence,
\[
\lim_{z \to z_0} f(z) = f(z_0)
\]

Therefore, \( f(z) \) is continuous at \( z_0 \).

---

## 11. Differentiation Using Increment Method

Let  
\[
f(z) = z^2
\]

\[
f(z+h) = (z+h)^2 = z^2 + 2zh + h^2
\]

\[
\frac{f(z+h)-f(z)}{h} = 2z + h
\]

Taking limit \( h \to 0 \),
\[
f'(z) = 2z
\]

---

## 12. Important Results

1. Polynomial functions are differentiable everywhere.
2. Conjugate function \( \bar{z} \) is NOT differentiable.
3. Absolute value functions are not differentiable.

---

## 13. Formula Summary

\[
\frac{d}{dz}(z^n) = nz^{n-1}
\]

\[
\frac{d}{dz}(c) = 0
\]

\[
\frac{d}{dz}(az+b) = a
\]

---

## 14. Previous Year Questions (PYQ – TRB / UG)

1. Define continuity of a complex function.
2. Define differentiability of a complex function.
3. Show that differentiability implies continuity.
4. Test differentiability of a given function.
5. Find derivative of simple complex functions.

---

## 15. Practice Problems

1. Test continuity of \( f(z) = z^3 \).
2. Find derivative of \( f(z) = z^4 + 2z \).
3. Show that \( f(z) = \bar{z} \) is not differentiable.
4. Verify differentiability using limit definition.

---

## 16. TRB Exam Tips ⭐

✔ Write **definition clearly**  
✔ Use **increment method** in answers  
✔ Mention **all-direction limit condition**  
✔ State theorem before proof  

---

✅ **End of Topic 4: Limits, Continuity and Differentiability**


---
