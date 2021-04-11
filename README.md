# Probability Homework 2

B10707132——張譽洋

### 3.7

(a)

$S_{X}=\left\{ 2,2,3,3,4,4,4,4 \right\}$

(b)

$P(X=2)=\frac{1}{2}$

$P(X=3)=\frac{1}{4}$

$P(X=4)=\frac{1}{4}$

### 3.10

(a)

$S=\left\{ (H,T)\times(H,T)\times...\times(H,T) \right\}$

$Y=H-T$

$S=\left\{ -n,-(n-2),-(n-4),...,-2,0,2,...,(n-4),(n-2),n \right\}$

Set m=T

$Y=(n-m)-m=n-2m$

(b)

$\because$Y=0

$\therefore$n is even $m=\frac{n}{2}$

$P(Y=0)=P(H=\frac{n}{2})=
\left(\begin{array}{cc}
    n  \\
    \frac{n}{2}  
\end{array}\right)p^{ \frac{n}{2} }(1-p)^{ \frac{n}{2} }
$

(C)

Y=k

$P(Y=K)=P(H=\frac{n+k}{2})=\left(\begin{array}{cc}
    n  \\
    \frac{n}{2}  
\end{array}\right)p^{ \frac{n+k}{2} }(1-p)^{ \frac{n-K}{2} }$

### 3.18

(a)

$P(Y=2)=0.4$

$P(Y=1)=0.3$

$P(Y=0)=0.2$

$P(Y=-1)=0.1$

(b)

$P(Y=2)=0.4$

(c)

$P(Y>0)=0.4+0.3=0.7$

### 3.20

$P(X=k)=\left(\begin{array}{cc}
    3  \\
   k  
\end{array}\right)p^{k}(1-p)^{ 5-k }$

$P(wrong)=P(X \ge 3)=P(X=3)+P(X=4)+P(X=5)=0.0086
$

### 3.30

（a）

$\sum_{k=1}^{15}\frac{p_1}{k}=1$

$p_1=\frac{360360}{1195757}$

$E[g(X)]=\sum_{k=10}^{15}(k-10)\frac{p_1}{k}=1.1074p_1=0.33373$

(b)

$\sum_{k=1}^{15}\frac{p_1}{2^{k-1}}=1$

$p_1=0.5$

$E[g(X)]=\sum_{k=10}^{15}(k-10)\frac{p_1}{2^{k-1}}=3.479\times10^{-3}p_1=1.739\times10^{-3}$

(c)

$E[g(X)]=\sum_{k=10}^{15}(k-10)\frac{p_1}{2^{\frac{k^2-k}{2}}}=1$

$\xRightarrow、p_1$

$E[g(X)]=\sum_{k=10}^{15}(k-10)\frac{p_1}{2^{\frac{k^2-k}{2}}}$

### 3.43

Y=H-T=2H-n

E(Y)=E(2H-n)=n(2p-1)

VAR(Y)=V(2H-n)=4np(1-p)

### 3.53

(a)

P(ERROR FREE)=1-p=0.99

$P(N=n)=0.01(0.99)^n$

(b)

$E(N)=\frac{1-0.01}{0.01}=99$

(c)

$P[N \ge 1000]=0.99$

$1-\sum_{k=0}^{1000}P(N=k)=0.99$

$(1-p)^{1001}=0.99$

$p=1-e^{\frac{ln0.99}{1001}}$

### 3.54

（a）

$ P \left[ N=k|N \le m \right] = \frac{P \left[ N=k \ \cap N \le m \right] }{P \left[ N \le m \right] } = = \frac{P \left[ N=k \right] }{P \left[ N \le m \right] } $

$ P \left[ N=k \right] =p(1-p)^{k-1} $

$ P \left[ N \le m \right] = \sum _{j=1}^{m}p(1-p)^{j-1} = =1-(1-p)^{m} $

$ P \left[ N=k|N \le m \right] = \frac{p(1-p)^{k-1}}{1-(1-p)^{m}} $

(b)

take N=2n

$P(N=2n)=p(1-p)^{2n}$
