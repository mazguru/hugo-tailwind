---
title : "Persamaan Lingkaran Memenuhi Kriteria Tertentu"
description : "Menentukan persamaan suatu lingkaran dapat dengan kriteria tertentu"
date : 2022-01-19T18:10:03+07:00
featured : false
draft : false
comment : true
toc : true
reward : false
math : true
keywords : 
  - lingkaran
  - persamaan lingkaran
  - persamaan lingkaran pusat O
  - persamaan lingkaran pusat a,b
  - persamaan lingkaran kriteria tertentu
kategori : 
  - Persamaan Lingkaran
topik :
  - Persamaan lingkaran
seri : 
  - Matematika SMA
images : 
  - header/persamaan-lingkaran-kriteria-tertentu.jpg
tumbnail : 
  - tumbnail/persamaan-lingkaran-kriteria-tertentu.jpg
cover : 
  - cover/persamaan-lingkaran.jpg
---

Untuk dapat menentukan persamaan suatu lingkaran dapat dilakukan dengan dua cara, yaitu:
1. Tentukan titik pusat dan jari-jari lingkaran
2. Substitusikan ke dalam persamaan lingkaran

Dalam menentukan jari-jari lingkaran, kita harus mengerti tentang formula jarak titik ke titik dan titik ke garis. Berikut ini diberikan beberapa formula untuk menentukan jarak. 
1. Jarak antara dua titik $A(x_1 , y_1)$ dan $B(x_2 , y_2)$, ditentukan oleh $$j = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$$
2. Jarak titik $A(x_1 , y_1)$ terhadap garis lurus $ax + by + c = 0$ dirumuskan $$j=\left| \frac{a{x_1}+b{y_1}+c}{\sqrt{a^2+b^2}} \right|$$

## 1. Lingkaran Menyinggung Garis
### Contoh 1 
Tentukan persamaan lingkaran yang berpusat di $𝑂(0, 0)$ dan menyinggung garis $3𝑥 – 4𝑦 + 5 = 0$

**Pembahasan**  
Nilai jari-jari dari persamaan lingkaran tersebut adalah  
Jarak sembarang titik $(𝑥_1, 𝑦_1)$ ke sebarang garis $𝐴𝑥 + 𝐵𝑦 + 𝐶 = 0$ adalah
$$r=\left| \frac{A{x_1}+B{y_1}+c}{\sqrt{a^2+b^2}} \right|$$
berarti jarak antara titik pusat (0,0) dan garis singgungnya $3𝑥 – 4𝑦 + 5 = 0$ adalah : 
$$r=\left| \frac{3(0)-4(0)+5}{\sqrt{3^2+(-4)^2}} \right|=\left| \frac{5}{\sqrt{9+16}} \right|=\left| \frac{5}{\sqrt{5}} \right|=1$$
persamaan lingkaran yang berpusat di $𝑂(0, 0)$ adalah $𝑥^2+𝑦^2=r^2$  
Jadi, persamaan lingkarannya adalah $𝑥^2+𝑦^2=1$ 
### Contoh 2
Tentukan persamaan lingkaran yang berpusat di $P(-2, 3)$ dan menyinggung garis $2𝑥 – 3𝑦 + 5 = 0$

**Pembahasan**  
jari-jari lingkaran dengan titik pusat $P(-2,3)$ dan menyinggung garis $2𝑥 – 3𝑦 + 5 = 0$ adalah : 
$$\begin{align*}
r&=\left| \frac{A{x_1}+B{y_1}+c}{\sqrt{a^2+b^2}} \right|\\\\&=\left| \frac{2(-2)-3(3)+5}{\sqrt{2^2+(-3)^2}} \right|\\\\&=\left| \frac{-4-9+5}{\sqrt{4+9}} \right|\\\\&=\left| \frac{-8}{\sqrt{13}} \right|\\\\r&=\frac{8}{13}\sqrt{13}\\\\r^2&=\frac{64}{13}
\end{align*}$$
persamaan lingkaran yang berpusat di $P(a, b)$ adalah $(𝑥-a)^2+(𝑦-b)^2=r^2$  
Jadi, persamaan lingkarannya adalah $(𝑥+2)^2+(𝑦-3)^2=\frac{64}{13}$ 

## 2. Hubungan dua titik pada lingkaran yang merupakan diameter
### Contoh 3
Tentukan persamaan lingkaran yang diameternya merupakan ruas garis yang menghubungkan titik $P(3, −2)$ dan $Q(−5, -4)$.

**Jawab**  
Sketsa di samping menunjukkan titik pusat M adalah titik tengah garis PQ.
Koordinat titik tengah dari sebuah garis PQ dengan $P(x_P, y_P)$ dan $Q(x_Q, y_Q)$ adalah
$$\left (  \frac{x_Q-x_P}{2},\frac{y_Q-y_P}{2} \right )$$
Sehingga koordinat titik M adalah :
$$M\left (  \frac{-5-3}{2},\frac{-4-(-2)}{2} \right )=M\left (  \frac{-8}{2},\frac{-2}{2} \right )=M\left (  -4,-1 \right )$$
Panjang garis PQ
$$\begin{align*}
PQ&=\sqrt{(x_Q-x_P)^2+(y_Q-y_P)^2}\\\\&=\sqrt{(-5-3)^2+(-4-(-2))^2}\\\\&=\sqrt{(-8)^2+(-2)^2}\\\\&=\sqrt{64+4}\\\\&=\sqrt{68}\\\\PQ&=2\sqrt{17}
\end{align*}$$
Jari – jari $r = \frac{1}{2}PQ=\frac{2\sqrt{17}}{2}=\sqrt{17}$

Persamaan lingkaran dengan pusat $M(−4, −1)$ dan jari – jari $\sqrt{17}$ adalah 
$$\begin{align*}
(x+4)^2+(y+1)^2&=(\sqrt{17})^2\\\\(x+4)^2+(y+1)^2&=17
\end{align*}$$

## 3. Tiga titik pada lingkaran
### Contoh 4
Tentukan persamaan lingkaran yang melalui titik (3, -1), (2, 0), dan (-1, –1). 

**Alternatif Penyelesaian**  
Misalkan persamaan lingkaran yang melalui titik-titik tersebut adalah
$x^2 + y^2 + Ax + By + C = 0$.
Kita akan menentukan nilai A, B, dan C dengan substitusi titik ke persamaan lingkaran sebagai berikut

- (3, -1) pada lingkaran, maka
$$\begin{align*}
x^2 + y^2 + Ax + By + C &= 0\\\\ 3^2 + (-1)^2 + 3A-B + C &= 0\\\\10+3A-B+C&=0\\\\3A-B+C&=-10......(1)
\end{align*}$$
- (2, 0) pada lingkaran, maka
$$\begin{align*}
x^2 + y^2 + Ax + By + C &= 0\\\\ 2^2 + (0)^2 + 2A-(0)B + C &= 0\\\\4+2A+C&=0\\\\2A+C&=-4......(2)
\end{align*}$$
- (-1, -1) pada lingkaran, maka
$$\begin{align*}
x^2 + y^2 + Ax + By + C &= 0\\\\ (-1)^2 + (-1)^2 -A-B + C &= 0\\\\2-A-B+C&=0\\\\-A-B+C&=-2......(3)
\end{align*}$$

Eliminasi C pada persamaan (1) dan (3) diperoleh
$$\begin{aligned}  \begin{aligned} 3A-B+C&=-10 \\\\ -A-B+C&=-2 \end{aligned} \\\\ \rule{3.5 cm}{0.5pt} - \\\\ \begin{aligned} 4A & = -8 \\\\ A & = -2 \end{aligned} \end{aligned}$$

Substitusi $A = –2$ ke persamaan (2)  
diperoleh $2A+C=-4\Harr2(-2)+C=-4\Harr C=0$

Substitusi $A = –2$ dan $C = 0$ ke persamaan (3)  
diperoleh $-A-B+C=-2\Harr-(-2)-B+0=-2\Harr B=4$

Jadi, persamaan lingkaran yang melalui titik (3, -1), (2, 0), dan (-1, –1) adalah $x^2 + y^2 -2x + 4y= 0$.