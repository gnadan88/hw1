# 신규 과제
## **P2.7**
s-domain에서 커패시터의 임피던스는  
$\frac{1}{Cs}$  

KCL에 의해  

$i_1+i_2=0$  

$\frac{V_1(s)}{R}+Cs(0-V_2(s))=0$  

$V_2(s)=-\frac{1}{RCs}V_1(s)$

transfer function은 다음과 같다.

$\frac{V_2(s)}{V_1(s)}=-\frac{1}{sRC}$

## **P2.12**
transfer function은  

$\frac{Y(s)}{R(s)}=\frac{K}{s+50}$  

r(t)는 unit step input이므로 라플라스 변환에 의해

$R(s)=\frac{1}{s}$  

$Y(s)=\frac{K}{s(s+50)}$  
$Y(s)=\frac{K}{50}\left(\frac{1}{s}-\frac{1}{s+50}\right)$  

위 식을 라플라스 역변환 해주면

$y(t)=\frac{K}{50}(1-e^{-50t})$  

$t\rightarrow\infty$일 때 $y(t)\rightarrow1$이므로  

$K=50$이다.

## **P2.15**
$m\ddot{x}+b\dot{x}+kx=0$  
$\ddot{x}+\frac{b}{m}\dot{x}+\frac{k}{m}x=0$

라플라스 변환  
$s^2X(s)-sx(0)-\dot{x}(0)+\frac{b}{m}(sX(s)-x(0))+\frac{k}{m}X(s)=0$  

$x(0)=0$이고 $\dot{x}(0)=0$이므로  

$


## **P2.26**
$M\ddot{x}+b(\dot{x}-\dot{y})+k(x-y)=F(t)$  
$m\ddot{y}+b(\dot{y}-\dot{x})+k(y-x)=0$  

라플라스 변환

$$\begin{bmatrix} 
   a_{11} & a_{12} & a_{13}  \\
   a_{21} & a_{22} & a_{23}  \\
   a_{31} & a_{32} & a_{33}  \\
   \end{bmatrix}$$


## **P2.37**
