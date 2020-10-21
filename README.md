# Mathematic_Note
 This repository stores some mathematical method


## Kalman Filter
<font size="3">
簡單理解 : 加入量測誤差後對下一個狀態位置的估計<br>
簡化公式 : $$ \hat X_k = K_k \cdot Z_k + ( 1 - K_k ) \cdot \hat X_{k-1}$$
          <font size="2">
          $$ \hat X_k : (Current\ Estimmation)\ k狀態下，對X的估計 $$
          $$ K_k : (Kalman\ Gain)\ 卡爾曼增益 $$
          $$ Z_k : (Measured\ Value)\ 真實量測值(有誤差) $$
          $$ \hat X_{k-1} : (Last\ Estimmation)\ 上一個狀態的估計值 $$
    