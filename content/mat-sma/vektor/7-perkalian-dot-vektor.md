---
title : "Perkalian Titik (Dot Product)-Perkalian Skalar Dua Vektor"
description : 
date : 2022-01-28T15:35:32+07:00
math : true
featured : false
draft : false
comment : true
toc : true
keywords : 
 - matematika
 - dot vektor
 - perkalian dot vektor
 - vektor
 - dot product
 - perkalian skalar dua vektor
kategori : 
 - Aljabar
topik :
 - vektor
 - vektor aljabar
 - kelas X
seri : 
 - Matematika SMA
images : 
- header/perkalian-dot-vektor.jpg
tumbnail : 
- tumbnail/perkalian-dot-vektor.jpg
cover : 
- images/icon/vektor.svg
---
Pada artikel ini kita akan belajar tentang operasi pada vektor yaitu perkalian vektor atau dot product atau perkalian titik. Setelah sebelumnya kita belajar operasi pada vektor yaitu [penjumlahan dan pengurangan pada vektor](/operasi-vektor-dalam-matematika) dan [perkalian vektor dengan skalar](/aljabar-vektor-pada-bangun-datar-ruang-dimensi-2/#c-perkalian-skalar-dengan-vektor), maka kali ini kita lanjutkan dengan pembahasan **Perkalian Dot Vektor *(Dot Product)***. Vektor dapat kita sajikan dalam bentuk aljabar dan bentuk geometri dimana dua vektor akan membentuk besar sudut tertentu. Nah, sudut antar dua vektor tersebut bisa kita hitung salah satunya dengan menerapkan konsep Perkalian Dot Vektor. Sebelum lanjut kuasai materi [panjang vektor](/aljabar-vektor-pada-bangun-datar-ruang-dimensi-2/#3-modulus-atau-besar-vektor) dulu ya.

**Dot vektor** disebut pula sebagai perkalian skalar antara dua vektor, sebab meskipun kedua unsur yang dikalikan berupa vektor namun hasil kalinya berupa skalar. Lambang perkaliannya digunakan tanda titik (.).

## Definisi:
**Secara geometri Perkalian Dot (perkalian titik)**  
{{< alert "$$\vec{u}\cdot\vec{v}=\lvert \vec{u}\rvert \lvert \vec{v}\rvert \cos{\theta}$$ dengan $\vec{u}\cdot \vec{v}$ dibaca ”vektor u dot vektor v” atau cukup dengan “$\vec{u}$ dot $\vec{v}$” saja." >}}
### Contoh Perkalian Dot Vektor secara geometri:
Tentukan $\vec{u}\cdot \vec{v}$ jika $\vec{u}=\left( \begin{matrix} 0\\\\ 2\end{matrix} \right)$ dan $\vec{v}=\left( \begin{matrix} 4\\\\ 4\end{matrix} \right)$!

**Alternatif Penyelesaian**  
Berdasarkan gambar dan definisi dot vektor,
![Alternatif jawaban soal 1](/images/matsma/vektor/vektor-7-penyelesaian-soal-1.jpg)
$\vec{u}=\left( \begin{matrix} 0\\\\ 2\\\\\end{matrix} \right)$, $\vec{v}=\left( \begin{matrix} 4\\\\ 4\end{matrix} \right)$ dan tentu $\theta =45{}^\circ $. Maka
$$\begin{align*}
\vec{u}\cdot \vec{v}&=\left| \vec{u} \right|\left| \vec{v} \right|\cos \theta \to \text{Definisi}\\\\ \vec{u}\cdot \vec{v}&=\left| \left( \begin{matrix}0\\\\ 2\end{matrix} \right) \right|\left| \left( \begin{matrix} 4\\\\ 4\end{matrix} \right) \right|\cos 45{}^\circ\\\\ \vec{u}\cdot \vec{v}&=\sqrt{{{0}^{2}}+2^2}.\sqrt{4^2+4^2}.\frac{1}{2}\sqrt{2}\\\\ \vec{u}\cdot \vec{v}&=2.4\sqrt{2}.\frac{1}{2}\sqrt{2}\\\\ \vec{u}\cdot \vec{v}&=8
\end{align*}$$

## Dalil
**Secara aljabar Perkalian Dot (perkalian titik)**  
{{< alert "Jika $\vec{u}=(a_1,a_2,a_3,...,a_n)$ dan $\vec{v}=(b_1,b_2,b_3,...,b_n)$ adalah sebarang Vektor pada ${{R}^{n}},$ maka hasil kali dalam atau perkalian skalarnya adalah $$\vec{u}\cdot \vec{v}=a_1b_1+a_2b_2+a_3b_3+...+a_nb_n$$" >}}

Dari dalil diatas, maka berlaku perkalian yang langsung melibatkan unsur-unsur vektornya, yaitu :  
1.	{{< alert "Jika $\vec{u}=\left( \begin{matrix}a_1\\\\ a_2\\\\ \end{matrix} \right)$ dan $\vec{v}=\left( \begin{matrix} b_1\\\\ b_2\\\\\end{matrix} \right)$ Vektor-vektor pada ${{R}^{2}}$ maka $$\vec{u}\cdot \vec{v}=a_1b_1+a_2b_2$$" >}}
2.	{{< alert "Jika $\vec{u}=\left( \begin{matrix} a_1\\\\a_2\\\\ a_3\\\\ \end{matrix} \right)$ dan $\vec{v}=\left( \begin{matrix} b_1\\\\b_2\\\\ b_3\\\\\end{matrix} \right)$ Vektor-vektor pada ${{R}^{3}}$ maka $$\vec{u}\cdot \vec{v}=a_1b_1+a_2b_2+a_3b_3$$" >}}

Catatan :  
- Secara geometri, arah kedua vektor adalah menjauh dari sudut yang terbentuk.  
- Perkalian dot dua vektor menghasilkan skalar.
## Sifat Perkalian Skalar (Perkalian Titik/Dot Product) Dua Vektor:
- $\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$
- $\vec{a} \cdot (\vec{b}+\vec{c)} = \vec{a}\cdot\vec{b} + \vec{a}\cdot\vec{c}$
- $\vec{a}\cdot\vec{a}=|\vec{a}|^2$
- $\vec{a}\perp\vec{b}\Rightarrow\vec{a}\cdot\vec{b}=0$
### Contoh Soal Perkalian Dot Vektor 1
Diketahui vektor $  \vec{a} = (-1,2,3) $ , $  \vec{b} = (2,0,-2) $ , dan $  \vec{c}= (1, -3, 4 ) $. Tentukan hasil perkalian dot vektor-vektor berikut: 
1. $  \vec{a}. \vec{b} $ dan $  \vec{b}. \vec{c} $ 
2. $  \vec{a}( \vec{b}- \vec{c}) $ 
3. $  \vec{b}( \vec{a}- \vec{c}) $ 
4. $ ( \vec{a}- \vec{b}).( \vec{b}+ \vec{c}) $ 

**Penyelesaian :**
1. Menentukan $  \vec{a}. \vec{b} $ dan $  \vec{b}. \vec{c}$
$$\begin{align*} \vec{a}. \vec{b} &= (-1,2,3).(2,0,-2)\\\\&= -1.2 + 2.0 + 3.(-2)\\\\&= -2 + 0 - 6\\\\&= -8\\\\\vec{b}. \vec{c} &= (2,0,-2) . (1, -3, 4 )\\\\&=2.1 + 0. (-3) + -2.4\\\\&= 2 + 0 - 8\\\\&= - 6 \end{align*}$$ 
2. Menentukan $  \vec{a}( \vec{b}- \vec{c}) $ 
$$\begin{align*}
\vec{b}- \vec{c} &= (2,0,-2) - (1, -3, 4 )\\\\&= ( 2 - 1 , 0 - (-3) , -2 - 4 )\\\\&= (1 , 3, -6 )\\\\\vec{a}( \vec{b}- \vec{c}) &= (-1,2,3) . (1 , 3, -6 )\\\\&= -1.1 + 2. 3 + 3. (-6)\\\\&= -1 + 6 - 18\\\\&= -13 
\end{align*}$$ 
3. Menentukan $  \vec{b}( \vec{a}- \vec{c}) $ 
$$\begin{align*}
\vec{a}- \vec{c} &=  (-1,2,3) - (1, -3, 4 )\\\\&= ( -2, 5, -1 )\\\\ \vec{b}( \vec{a}- \vec{c})  &= (2,0,-2).( -2, 5, -1 )\\\\ &= 2.(-2) + 0.5 + -2. (-1) \\\\ &= -4 + 0  + 2 \\\\&= -2 
\end{align*}$$ 
4. Menentukan $ ( \vec{a}- \vec{b}).( \vec{b}+ \vec{c}) $ 
$$\begin{align*}
\vec{a}-\vec{b} &= (-1,2,3) - (2,0,-2)\\\\&= ( -3, 2, 5 ) \\\\\vec{b}+ \vec{c} &= (2,0,-2) + (1, -3, 4 )\\\\&= (3, -3, 2)\\\\( \vec{a}- \vec{b}).( \vec{b}+ \vec{c}) &= ( -3, 2, 5 ) . (3, -3, 2)\\\\&= -9 + -6 + 10\\\\&= -5
\end{align*}$$ 
### Contoh Soal Perkalian Dot Vektor 2
Jika $ \vec{p} $ dan $ \vec{q} $ membentuk sudut $ 60^\circ $, dengan $ |\vec{p}| = 6 $ , $ |\vec{q}| = 5 $ , maka tentukan nilai 
$ \vec{p}.\vec{q} $! 

**Penyelesaian :** 
$$\begin{align*}
\vec{p}.\vec{q}  &= |\vec{p}||\vec{q} | \cos \theta \\\\&= 6 . 5. \cos 60^\circ\\\\&= 30. \frac{1}{2}\\\\&= 15 
\end{align*}$$ 
### Contoh Soal Perkalian Dot Vektor dengan Syarat Ada Vektor yang Tegak Lurus
Diketahui vektor $\vec{a} = \begin{pmatrix}k\\\\2\\\\2\end{pmatrix},\vec{b} = \begin{pmatrix}2\\\\-5\\\\3\end{pmatrix}$ dan $\vec{c}= \begin{pmatrix}2\\\\1\\\\-1\end{pmatrix}$. Jika vektor $\vec{a}$ tegak lurus dengan vektor $\vec{b}$, maka tentukan nilai dari $2\vec{a}\cdot (\vec{b}-3\vec{c})$

**Penyelesaian :** 
$$\begin{align*}
\vec{a}\perp\vec{b}&\Rightarrow &\vec{a}\cdot\vec{b}&=0\\\\&\Leftrightarrow&\begin{pmatrix}k\\\\2\\\\2\end{pmatrix}\cdot\begin{pmatrix}2\\\\-5\\\\3\end{pmatrix}&=0\\\\&\Leftrightarrow&2k-10+6&=0\\\\&\Leftrightarrow&2k+4&=0\\\\ &\Leftrightarrow&2k&=4\\\\&\Leftrightarrow&k&=2
\end{align*}$$
Dengan demikian diperoleh:
$\vec{a}=\begin{pmatrix}2\\\\2\\\\2\end{pmatrix}$

Dengan menggunakan sifat perkalian titik dua vektor, diperoleh:
$$\vec{a}\perp\vec{b}=0\\\\\begin{align*}
\vec{a}\cdot\vec{c}&=\begin{pmatrix}2\\\\2\\\\2\end{pmatrix}\cdot\begin{pmatrix}2\\\\1\\\\-1\end{pmatrix}\\\\&=(2\cdot2)+(2\cdot1)+(2\cdot{-1})\\\\&=4+2-2=4\end{align*}\\\\\begin{align*}2\vec{a}\cdot(\vec{b}-3\vec{c})&=2\vec{a}\cdot\vec{b}-2\vec{a}\cdot3\vec{c}\\\\&=2(\vec{a}\cdot\vec{b})-6(\vec{a}\cdot\vec{c})\\\\&=2(0)-6(4)=-24\end{align*}$$
Jadi nilai $2\vec{a}\cdot(\vec{b}-3\vec{c})=-24$
### Contoh Soal Perkalian Dot Vektor yang Tegak Lurus
Diketahui vektor-vektor $ \vec{p} = ( m, 2, 6 ) $ , $ \vec{q} = (-1,n,0) $ dan $ \vec{r} = (6k,3,7) $. Jika $ \vec{p} \bot \vec{q} $ dan $ \vec{q} \bot \vec{r} $ , maka tentukan nilai $ 16\left( \frac{n^2 + k^2}{m^2} \right) + 2012 $ !  
Keterangan : simbol $ \bot $ artinya tegak lurus.  
**Penyelesaian :**  
- Menentukan hubungan $ m , n , $ dan $ k $ : 
    - $ \vec{p} $ tegak lurus $ \vec{q} $ 
    $$ \vec{p}.\vec{q} = 0 \rightarrow -m + 2n + 0 = 0 \rightarrow m = 2n ....(1)$$
    - $ \vec{q} $ tegak lurus $ \vec{r} $ 
    $$ \vec{q}.\vec{r} = 0 \rightarrow -6k + 3n + 0 = 0 \rightarrow k = \frac{n}{2} ....(2)$$ 
- Menentukan hasil akhir dengan pers(1) dan pers(2) : 
$$\begin{align*}
16\left( \frac{n^2 + k^2}{m^2} \right) + 2012  &= 16\left( \frac{n^2 + (\frac{n}{2})^2}{(2n)^2} \right) + 2012\\\\&= 16\left( \frac{n^2 + \frac{n^2}{4} }{4n^2} \right) + 2012\\\\&= 16\left( \frac{n^2 + \frac{n^2}{4} }{4n^2}  \times \frac{4}{4} \right) + 2012\\\\&= 16\left( \frac{4n^2 + n^2}{16n^2}  \right) + 2012\\\\&= 16\left( \frac{5n^2}{16n^2}  \right) + 2012\\\\&= 16\left( \frac{5 }{16 }  \right) + 2012\\\\&= 5 + 2012 = 2017 
\end{align*}$$ 
Jadi, nilai $ 16\left( \frac{n^2 + k^2}{m^2} \right) + 2012  = 2017 $.
## Sudut Antara 2 Vektor
Dari definisi dan dalil diatas maka kita dapat mencari besar sudut antara dua vektor. 
### Contoh:
Tentukan besar sudut yang dibentuk oleh vektor $\vec{u}=\left( \begin{matrix}6\\\\2\end{matrix} \right)$ dan $\vec{v}=\left( \begin{matrix}3\\\\4\\\\\end{matrix} \right)$!

**Alternatif Penyelesaian:**  
$$\begin{align*}
& \vec{u}=\left( \begin{matrix}6\\\\2\end{matrix} \right)\to u_1=6,u_2=2\\\\ & \vec{v}=\left( \begin{matrix}3\\\\4\end{matrix} \right)\to v_1=6,v_2=2
\end{align*}$$
$$\begin{align*}& \cos \theta =\frac{\vec{u}\cdot \vec{v}}{\left| \vec{u} \right|\left| \vec{v} \right|}\\\\ & \cos \theta =\frac{u_1v_1+u_2v_2}{\left| \vec{u} \right|\left| \vec{v} \right|}\\\\ & \cos \theta =\frac{6.3+2.4}{\sqrt{6^2+2^2}.\sqrt{3^2+4^2}}\\\\ & \cos \theta =\frac{26}{\sqrt{40}.\sqrt{15}}\\\\ & \cos \theta =\frac{26}{10\sqrt{10}}\approx \frac{26}{31,62}\approx 0,822\\\\ & \theta \approx \arccos (0,822)\\\\ & \theta \approx 34,71
\end{align*}$$
Jadi, besar sudut yang dibentuk oleh vektor $\vec{u}$ dan $\vec{v}$ adalah $37,41^\circ $
