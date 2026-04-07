## 📷 圖片內容說明
<img width="510" height="213" alt="螢幕擷取畫面 2026-04-07 134546" src="https://github.com/user-attachments/assets/324ed0e5-5049-4662-8d4f-26aa4e174b0d" />

Initialization:
ĥ(0) = zeros(p)

Computation: For n = 0,1,2,...

x(n) = [x(n), x(n-1), ..., x(n-p+1)]^T

e(n) = d(n) - ĥ^H(n)x(n)

ĥ(n+1) = ĥ(n) + μ e*(n)x(n) / x^H(n)x(n)
