## 📷 圖片內容說明

<img width="510" height="213" alt="NLMS" src="https://github.com/user-attachments/assets/324ed0e5-5049-4662-8d4f-26aa4e174b0d" />

---

**Initialization:**

$$
\hat{h}(0) = \text{zeros}(p)
$$

---

**Computation:**

$$
\text{For } n = 0,1,2,\ldots
$$

$$
x(n) = [x(n), x(n-1), \ldots, x(n-p+1)]^T
$$

$$
e(n) = d(n) - \hat{h}^H(n)x(n)
$$

$$
\hat{h}(n+1) = \hat{h}(n) + \frac{\mu e^*(n)x(n)}{x^H(n)x(n)}
$$
