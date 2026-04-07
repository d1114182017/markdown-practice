# markdown-practice
簡單描述
## 📷 圖片內容說明

Initialization:
ĥ(0) = zeros(p)

Computation:
x(n) = [x(n), x(n-1), ..., x(n-p+1)]^T

e(n) = d(n) - ĥ^H(n)x(n)

ĥ(n+1) = ĥ(n) + μ e*(n)x(n) / x^H(n)x(n)
