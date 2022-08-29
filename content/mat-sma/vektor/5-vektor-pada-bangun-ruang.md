---
title : "Vektor pada Bangun Ruang R3 (ruang dimensi tiga)"
description : "Vektor pada bangun ruang (dimensi tiga) adalah vektor yang memiliki 3 buah sumbu yaitu X, Y dan Z yang saling tegak lurus dan perpotongan ketiga sumbunya sebagai pangkal"
date : 2022-01-22T16:56:15+07:00
math : true
featured : false
draft : false
comment : true
toc : false
keywords : 
 - matematika
 - vektor bangun ruang
 - vektor dimensi 3
 - vektor
 - vektor geometri
 - vektor aljabar
 - vektor posisi
 - vektor satuan
 - penyajian vektor
 - panjang vektor
kategori : 
 - Aljabar
topik :
 - vektor
 - vektor aljabar
 - kelas X
seri : 
 - Matematika SMA
images : 
 - header/vektor-bangun-ruang.jpg
tumbnail : 
 - tumbnail/vektor-bangun-ruang.jpg
cover : 
 - images/icon/vektor.svg
---
Setelah pada sebelumnya telah mempelajari vektor pada bidang (R2), selanjutnya kita kembangkankan pembahasan kita mengenai vektor pada bangun ruang (R3). Vektor pada bangun ruang (dimensi tiga) adalah vektor yang memiliki 3 buah sumbu yaitu X, Y dan Z yang saling tegak lurus dan perpotongan ketiga sumbunya sebagai pangkal.
## 1.	Penulisan Vektor di R3
Vektor pada ruang adalah vektor yang terletak di dalam ruang dimensi 3. Ruang ini dibentuk oleh 3 sumbu yaitu sumbu X, sumbu Y, dan sumbu Z. Ketiga sumbu ini berpotongan tegak lurus. Hasil perpotongan ini adalah O. Selanjutnya, titik O disebut sebagai sumbu pusat. Perhatikan gambar kaidah jari tangan kanan di samping. 
![kaidah jari tangan kanan](/images/matsma/vektor/kaidah-tangan-kanan.jpg)
Kaidah ini menerangkan beberapa hal, yaitu:
1.	Jari telunjuk menunjukkan sumbu Y. Bilangan-bilangan yang terletak setelah O dan searah telunjuk merupakan bilangan positif. Arah dan letak sebaliknya berarti bilangan negatif.
2.	Ibu jari menunjukkan sumbu X. Bilangan yang searah ibu jari dan terletak setelah O merupakan bilangan positif. Arah dan letak sebaliknya merupakan bilangan negatif.
3.	Jari tengah menunjukkan sumbu Z. Bilangan yang searah jari tengah dan terletak setelah O merupakan bilangan positif. Arah dan letak sebaliknya merupakan bilangan negatif.

Perhatikan contoh gambar vektor ruang di samping. 
![vektor ruang](/images/matsma/vektor/vektor-ruang.jpg)
Vektor $\overrightarrow{OA}$ di samping merupakan vektor ruang dengan pangkal O (0, 0, 0) dan ujung A (1, 1, 1). Vektor osisi $\overrightarrow{OA}$ ini dapat ditulis dengan vektor kolom, menjadi:
$$\overrightarrow{OA}=\begin{pmatrix}
1 \\\\1 \\\\1
\end{pmatrix}$$

Vektor ruang dapat pula ditulis dalam satuan $\widehat{i},\widehat{j}$ dan $\widehat{k}$. Satuan $\widehat{i}$ sesuai dengan sumbu X, satuan $\widehat{j}$ sesuai dengan sumbu Y, dan satuan $\widehat{k}$ sesuai dengan sumbu Z. $\overrightarrow{OB}=\begin{pmatrix} 1 \\\\1 \\\\1 \end{pmatrix}$ dapat ditulis menjadi $1\widehat{i}+1\widehat{j}+1\widehat{k}=\widehat{i}+\widehat{j}+\widehat{k}$.
{{< html >}}
 <p class='alert alert-info' ><b>Catatan</b> <br> Dua vektor atau lebih disebut koplaner jika terletak pada bidang yang sama. <br> Dua vektor atau lebih disebut kolinear jika terletak pada garis yang sama.</p>
{{< /html >}}

## 2.	Modulus atau Besar vektor
Modulus vektor adalah besar atau panjang suatu vektor. Panjang Vektor $\overrightarrow{OP}=\begin{pmatrix} x \\\\y \\\\z\end{pmatrix}$ dirumuskan sebagai berikut. 
$\lvert \overrightarrow{OP} \rvert=\sqrt{x^2+y^2+z^2}$
Jika diketahui titik $A(x_1,y_1,z_1)$ dan $B(x_2,y_2,z_2)$, secara analitis, diperoleh komponen Vektor $\overrightarrow{AB}=\begin{pmatrix} x_2-x_1 \\\\y_2-y_1 \\\\z_2-y_1 \end{pmatrix}$. Sehingga panjang Vektor $\overrightarrow{AB}$ dapat dirumuskan:

$$\lvert \overrightarrow{AB} \rvert=\sqrt{\left( x_2-x_1 \right)^2+\left(y_2-y_1\right)^2+\left( z_2-z_1 \right)^2}$$

Jika vektor $\vec{a}$ disajikan dalam bentuk linear $\vec{a}=a_1\widehat{i}+a_2\widehat{j}+a_3\widehat{k}$, maka modulus Vektor $\vec{a}$ adalah $\lvert \vec{a} \rvert=\sqrt{a_1^{2}+a_2^{2}+a_3^{2}}$

**Contoh:**  
Tentukan modulus/besar vektor berikut!
1.	$\overrightarrow{AB}$ dengan titik A (1, 4, 6) dan B (3, 7, 9)
2.	$\vec{a}=2\widehat{i}+\widehat{j}+3\widehat{k}$

**Alternatif Penyelesaian**  
1.	Diketahui $\vec{a}=\begin{pmatrix}1 \\\\4 \\\\6\end{pmatrix}$ dan 
$\vec{b}=\begin{pmatrix}3 \\\\7 \\\\9 \\\\ \end{pmatrix}$ maka $\overrightarrow{AB}=\vec{b}-\vec{a}$
$$\begin{align*}
\overrightarrow{AB}&=\vec{b}-\vec{a} \\\\\overrightarrow{AB}&=\begin{pmatrix} 3 \\\\7 \\\\9\end{pmatrix}-\begin{pmatrix}1 \\\\4 \\\\6\end{pmatrix} \\\\ \overrightarrow{AB}&=\begin{pmatrix} 3-1 \\\\7-4 \\\\9-6\end{pmatrix}\\\\ \overrightarrow{AB}&=\begin{pmatrix}2 \\\\3 \\\\3\end{pmatrix}
\end{align*}$$
Sehingga panjang vektor
$\lvert \overrightarrow{AB} \rvert=\sqrt{2^2+3^2+3^2}=\sqrt{4+9+9}=\sqrt{22}$  
Jadi, modulus vektor $\overrightarrow{AB}$ adalah $\sqrt{22}.$
2.	$\lvert \vec{a} \rvert=\sqrt{2^2+1^2+3^2}=\sqrt{14}$  
Jadi, modulus vektor $\vec{a}$ adalah $\sqrt{14}.$
## 3.	Vektor Satuan
Vektor satuan adalah vektor yang mempunyai panjang 1 satuan dan dinotasikan sebagai $e$. Vektor satuan dari vektor $\vec{a}$ didefinisikan vektor $\vec{a}$ dibagi dengan besar vektor $\vec{a}$ sendiri, yang dirumuskan dengan $${{e}_{\vec{a}}}=\frac{\vec{a}}{\lvert \vec{a} \rvert}=\frac{1}{\lvert \vec{a} \rvert}\vec{a}$$

### Contoh:
Tentukan vektor satuan dari Vektor $\vec{a}=\begin{pmatrix}2 \\\\4 \\\\\sqrt{5}\end{pmatrix}$

**Alternatif penyelesaian:**  
Terlebih dahulu ditentukan panjang Vektor $\vec{a}$  
$\lvert \vec{a} \rvert=\sqrt{2^2+4^2+(\sqrt{5})^2}=\sqrt{25}=5$  
$e_{\vec{a}}=\frac{1}{5}\begin{pmatrix}
2 \\\\4 \\\\\sqrt{5}
\end{pmatrix}$  
Jadi, Vektor satuan dari $\vec{a}$ adalah $e_{\vec{a}}=\begin{pmatrix} {2}/{5} \\\\{4}/{5} \\\\{\sqrt{5}}/{5} \end{pmatrix}$

Selain vektor satuan terdapat vektor-vektor satuan yang sejajar dengan sumbu-sumbu koordinat antara lain sebagai berikut.
1.	Vektor satuan yang sejajar dengan sumbu X dinotasikan $\widehat{i}=\begin{pmatrix}1 \\\\0 \\\\0\end{pmatrix},$
2. Vektor satuan yang sejajar dengan sumbu Y dinotasikan $\widehat{j}=\begin{pmatrix}0 \\\\1 \\\\0\end{pmatrix}$
3.	Vektor satuan yang sejajar dengan sumbu Z dinotasikan $\widehat{k}=\begin{pmatrix}0 \\\\0 \\\\1 \end{pmatrix}$
## 4.	Vektor Posisi
Vektor posisi titik P yaitu vektor yang berpangkal di titik O (0, 0, 0) dan berujung di titik P (x, y, z). Secara aljabar Vektor posisi $\overrightarrow{OP}$ atau $\vec{p}$ dapat ditulis sebagai berikut.
$$\overrightarrow{OP}=\vec{p}=\begin{pmatrix}x \\\\y \\\\z\end{pmatrix}=x\widehat{i}++y\widehat{j}+z\widehat{k}$$
Vektor $\overrightarrow{AB}$ dengan titik pangkal $A(x_1,y_1,z_1)$ dan titik ujung $B(x_2,y_2,z_2)$, memiliki vektor posisi sebagai berikut.

$$\overrightarrow{AB}=\overrightarrow{OB}-\overrightarrow{OA}=\begin{pmatrix}
x_2 \\\\y_2 \\\\z_2
\end{pmatrix}-\begin{pmatrix}
x_1 \\\\y_1 \\\\z_1
\end{pmatrix}=\begin{pmatrix}
x_2-x_1 \\\\y_2-y_1 \\\\z_2-z_1
\end{pmatrix}$$
### Contoh:
Diketahui titik $A(-5, 3, 4)$ dan titik $B(-2, 9, 1)$. Garis AB memotong bidang datar XY dititik C. Tentukan koordinat titik C!

**Alternatif penyelesaian:**  
Diketahui:  
$A(-5,3,4)\Rightarrow \vec{a}=\begin{pmatrix}-5 \\\\3 \\\\4 \end{pmatrix}$, $B(-2,9,1)\Rightarrow \vec{b}=\begin{pmatrix} -2 \\\\ 9 \\\\1 \end{pmatrix}$ C pada AB, sehinga vektor $\overrightarrow{AC}$ segaris dengan Vektor $\overrightarrow{AB}$. Oleh karena itu,
$$\begin{align*}
\overrightarrow{AC}&=k.\overrightarrow{AB} \\\\ \vec{c}-\vec{a}&=k(\vec{b}-\vec{a}) \\\\ \begin{pmatrix}x \\\\ y \\\\ z \end{pmatrix}-\begin{pmatrix}-5 \\\\ 3 \\\\ 4 \end{pmatrix}&=k\left( \begin{pmatrix}-2 \\\\9 \\\\1 \end{pmatrix}-\begin{pmatrix}-5 \\\\3 \\\\4 \end{pmatrix} \right) \\\\ \begin{pmatrix}x+5 \\\\ y-3 \\\\ z-4 \end{pmatrix}&=\begin{pmatrix} 3k \\\\ 6k \\\\ -3k \end{pmatrix} 
\end{align*}$$
Karena AB berada di bidang XY maka $z=0$ sehingga
$$\begin{align*}
z-4&=-3k \\\\ 0-4&=-3k \\\\ k&=\frac{4}{3}
\end{align*}$$
$$\begin{align*}
x+5&=3k \\\\ x+5&=3.\frac{4}{3} \\\\ x&=-1
\end{align*}$$
$$\begin{align*}
y-3&=6k \\\\ y-3&=6.\frac{4}{3} \\\\ y&=11
\end{align*}$$
Jadi, Vektor posisi $\vec{c}=\begin{pmatrix}-1 \\\\11 \\\\0 \end{pmatrix}$ sehingga koordinat titik C adalah $C(-1,11,0)$
 
## Latihan 4
1.	Tentukan modulus dari vektor-vektor berikut :
    1.	$\vec{a} = \begin{pmatrix}4 \\\\-5 \\\\-3 \end{pmatrix}$
    2.	$\vec{AB}$ dengan titik $A (-2 , 3 , -1)$ dan titik $B (2 , 1 , -4)$

2.	Diketahui vektor $\vec{PQ}$ dengan titik P $(2 , 5 , -4)$ dan $Q (1 , 0 , -3)$. Tentukan :
    1.	Koordinat titik R jika $\vec{SR}$ sama dengan vektor $\vec{PQ}$ jika titik $S (2 , -2 , 4)$
    2.	Koordinat titik N jika $\vec{MN}$ merupakan negatif vektor $\vec{PQ}$ jika titik $M (-1 , 3 , 2)$
3.	Tentukan vektor satuan dari vektor-vektor berikut :
    1. $\vec{u} = \begin{pmatrix} 0 \\\\ 0 \\\\ -1 \end{pmatrix}$	
    2. $\vec{v} = \begin{pmatrix} 1 \\\\ 1 \\\\ 1 \end{pmatrix}$	
    3. $\vec{KL}$ dengan $K (3 , -2 , 1)$ dan $L (2 , -2 , 1)$
    4. $\vec{MN}$ dengan $M (2 , 1 , 2)$ dan $N (2 , 0 , 3)$
4.	Gambarlah vektor dengan titik $P (2 , -3 , 1)$ dan $Q (1 , 3 , -2)$
    1.	Hitung modulus vektor $\vec{PQ}$
    2.	Buat vektor negatif dari $\vec{PQ}$, kemudian hitung modulusnya/besarnya !
    3.	Apa yang dapat Anda simpulkan dari pekerjaan di atas ?
5.	Jika titik $P (1 , 1 , 1)$ dan titik $Q (-1 , 4 , -6)$, tentukanlah :
    1. vektor posisi titik P dan titik Q 		
    2. komponen vektor $\vec{PQ}$
    3. negatif vektor $\vec{PQ}$
    4. vektor satuan $\vec{PQ}$
6.	Tentukan besar vektor berikut beserta vektor satuannya !
    1. $\vec{u} = \begin{pmatrix}2 \\\\4 \\\\1 \end{pmatrix}$		
    2. $\vec{w} = -\widehat{i} + 5\widehat{j} + \widehat{k}$		
    3. $\vec{PQ} = \begin{pmatrix} -3 \\\\0 \\\\5 \end{pmatrix}$

