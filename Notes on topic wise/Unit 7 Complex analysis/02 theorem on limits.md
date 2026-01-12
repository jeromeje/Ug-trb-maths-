

# UNIT VII – COMPLEX ANALYSIS  
## Topic 2: Theorems on Limits of Complex Numbers

---

## 1. Definition of Limit of a Complex Function

Let \( f(z) \) be a complex function defined near \( z_0 \).  
We say that **the limit of \( f(z) \) as \( z \to z_0 \) is \( w_0 \)** if  
\[
\lim_{z \to z_0} f(z) = w_0
\]
provided that for every \( \epsilon > 0 \), there exists a \( \delta > 0 \) such that  
\[
|f(z) - w_0| < \epsilon \quad \text{whenever} \quad 0 < |z - z_0| < \delta
\]

---

## 2. Tamil Meaning (தமிழ் விளக்கம்)

ஒரு சிக்கலெண் செயல்பாடு \( f(z) \),  
\( z \to z_0 \) ஆகும் போது \( w_0 \) என்பதைக் அணுகினால்,  
\[
\lim_{z \to z_0} f(z) = w_0
\]
என்று கூறப்படும்.

அதாவது,  
\( z \) எந்த திசையிலிருந்தும் \( z_0 \) ஐ அணுகினாலும்  
\( f(z) \) எப்போதும் \( w_0 \) ஐ அணுக வேண்டும்.

---

## 3. Important Note (TRB Point)

🔹 **Limit exists only if it is same along all paths**.  
🔹 If limits differ along different paths → **limit does not exist**.

---

## 4. Examples for Definition

### Example 1:
\[
f(z) = z^2,\quad z \to 2
\]

\[
\lim_{z \to 2} z^2 = 4
\]

---

### Example 2:
\[
f(z) = \bar{z},\quad z \to z_0
\]

Limit exists only if \( z_0 \) is real.

---

## 5. Theorems on Limits of Complex Numbers

---

### **Theorem 1: Uniqueness of Limit**

If  
\[
\lim_{z \to z_0} f(z) = w_1 \quad \text{and} \quad \lim_{z \to z_0} f(z) = w_2
\]
then  
\[
w_1 = w_2
\]

#### Tamil Meaning:
ஒரு செயல்பாட்டிற்கு **ஒரே ஒரு limit மட்டுமே இருக்கும்**.

---

### **Proof:**

Assume \( w_1 \neq w_2 \)

Using triangle inequality,
\[
|w_1 - w_2| \le |f(z)-w_1| + |f(z)-w_2|
\]

As \( z \to z_0 \), RHS → 0  
⇒ \( |w_1 - w_2| = 0 \)

Hence,  
\[
w_1 = w_2
\]

---

### **Theorem 2: Limit of Sum**

If  
\[
\lim_{z \to z_0} f(z) = w_1,\quad \lim_{z \to z_0} g(z) = w_2
\]
then  
\[
\lim_{z \to z_0} [f(z) + g(z)] = w_1 + w_2
\]

---

### **Theorem 3: Limit of Difference**

\[
\lim_{z \to z_0} [f(z) - g(z)] = w_1 - w_2
\]

---

### **Theorem 4: Limit of Product**

\[
\lim_{z \to z_0} [f(z)g(z)] = w_1 w_2
\]

---

### **Theorem 5: Limit of Quotient**

If \( w_2 \neq 0 \),
\[
\lim_{z \to z_0} \frac{f(z)}{g(z)} = \frac{w_1}{w_2}
\]

---

## 6. Example Using Theorems

### Example:
Find  
\[
\lim_{z \to 1+i} (z^2 + 3z)
\]

### Solution:
\[
= (1+i)^2 + 3(1+i)
\]
\[
= (1 + 2i - 1) + 3 + 3i
\]
\[
= 3 + 5i
\]

---

## 7. Non-Existence of Limit (Path Test)

### Example:
\[
f(z) = \frac{x^2 - y^2}{x^2 + y^2},\quad z = x + iy
\]

- Along \( y = 0 \) → limit = 1  
- Along \( x = 0 \) → limit = -1  

Since limits differ,  
\[
\text{Limit does NOT exist}
\]

---

## 8. Important Results

1. Limit must be independent of path.
2. If limit exists, function is bounded near the point.
3. Algebra of limits works similar to real functions.

---

## 9. Formula Summary

\[
\lim_{z \to z_0} z = z_0
\]

\[
\lim_{z \to z_0} c = c
\]

\[
\lim_{z \to z_0} z^n = z_0^n
\]

---

## 10. Previous Year Questions (PYQ – TRB / UG)

1. Define limit of a complex function.
2. Prove uniqueness of limit.
3. State and prove algebra of limits.
4. Show that limit does not exist using path method.
5. Evaluate limits of given complex functions.

---

## 11. Practice Problems

1. Find  
\[
\lim_{z \to 2} (z^2 - 3z + 1)
\]

2. Test the existence of  
\[
\lim_{z \to 0} \frac{x^2y}{x^2 + y^2}
\]

3. Verify limit laws for  
\[
f(z) = z,\quad g(z) = z^2
\]

---

## 12. TRB Exam Tips ⭐

✔ Always mention **epsilon–delta definition**  
✔ Write **path test clearly**  
✔ State theorem → proof → result  
✔ Use **modulus inequality** in proofs  

---

✅ **End of Topic 2: Theorems on Limits of Complex Numbers**


---
