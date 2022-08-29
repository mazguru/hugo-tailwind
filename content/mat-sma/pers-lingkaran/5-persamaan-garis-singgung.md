---
title : "Persamaan Garis Singgung Lingkaran"
description : Garis singgung lingkaran merupakan suatu garis yang memotong lingkaran tepat pada satu titik dan berpotongan tegak lurus dengan jari-jari di titik singgungnya.
date : 2022-01-24T19:25:59+07:00
featured : false
draft : false
comment : true
toc : true
reward : false
math : true
keywords : 
  - lingkaran
  - persamaan lingkaran
  - persamaan garis singgung lingkaran
  - melalui titik pada lingkaran
  - pgs gradien m
  - titik diluar lingkaran
  - pgs lingkaran
kategori : 
  - Persamaan Lingkaran
topik :
  - Persamaan lingkaran
seri : 
  - Matematika SMA
images : 
  - header/persamaan-garis-singgung-lingkaran.jpg
tumbnail : 
  - tumbnail/persamaan-garis-singgung-lingkaran.jpg
cover : 
  - cover/persamaan-lingkaran.jpg
---
Garis singgung lingkaran merupakan suatu garis yang memotong lingkaran tepat pada satu titik dan berpotongan tegak lurus dengan jari-jari di titik singgungnya. Untuk memudahkan dalam mempelajari persamaan garis singgung lingkaran, sebaiknya pahami dulu materi persamaan lingkaran. Ada tiga jenis yang diketahui dalam menentukan persamaan garis singgung lingkaran, yaitu : 
- Garis singgung yang melalui suatu titik pada lingkaran, 
- Garis singgung melalui suatu titik di luar lingkaran, dan 
- Garis singgung lingkaran yang diketahui gradien garisnya. 

## 1. Persamaan Garis Singgung (PGS) yang Melalui Suatu Titik pada Lingkaran
Misalkan titik $P(x_1, y_1)$ terletak pada lingkaran dengan pusat $O(0, 0)$ dan berjari-jari $r$. Selanjutnya dibuat suatu
garis singgung yang melalui titik P seperti pada gambar.
![PGS tiitk pada lingkaran](/images/matsma/lingkaran/pgs-titik-pada-lingkaran.jpg)
Persamaan umum garis singgung tersebut adalah $𝑦−𝑦_1=𝑚(𝑥−𝑥_1)$. Kita dapat mencari gradien garis yang menghubungkan
titik $O(0, 0)$ dan titik $P(x_1, y_1)$ dengan 
$$m_{OP}=\frac{\Delta y}{\Delta x}=\frac{y_1-0}{x_1-0}=\frac{y_1}{x_1}$$
Garis singgung lingkaran dan garis $OP$ saling tegak lurus sehingga 
$$\begin{align*}
m\times m_{OP}&=-1\\\\m&=\frac{-1}{m_{OP}}\\\\m&=\frac{-1}{\frac{y_1}{x_1}}\\\\m&=\frac{-x_1}{y_1}
\end{align*}$$
$𝑚 =\frac{−𝑥_1}{𝑦_1}$ disubstitusikan ke persamaan umum garis singgung $𝑦 − 𝑦_1 = 𝑚(𝑥 − 𝑥_1)$, sehingga diperoleh :
$$\begin{align*}
(𝑦 − y_1) &=\frac{−𝑥_1}{𝑦_1}(𝑥 − x_1)\\\\y_1(𝑦 − y_1) &= −x_1(𝑥 − x_1)\\\\y_1𝑦 − {y_1}^2 &= −x_1𝑥 + {x_1}^2\\\\x_1𝑥 + y_1𝑦 &= {x_1}^2 + {y_1}^2\\\\𝒙𝟏𝒙 + 𝒚𝟏𝒚 &= 𝒓^𝟐
\end{align*}$$
Dari penjabaran diatas dapat disimpulkan bahwa
1. Persamaan Garis Singgung di Titik P($x_1, y_1$) pada Lingkaran $x^2 + y^2 = r^2$  
Persamaan garis singgungnya : $$\begin{align*}x_1.x + y_1.y = r^2 \end{align*}$$
2. Persamaan Garis Singgung di Titik P($x_1, y_1$) pada Lingkaran $(x-a)^2 + (y-b)^2 = r^2$ 
Persamaan garis singgungnya :  
$$\begin{align*}(x_1-a)(x-a) + (y_1 - b)(y-b) = r^2 \end{align*}$$ 
3. Persamaan Garis Singgung Melalui Titik Q($x_1, y_1$) pada Lingkaran $x^2 + y^2 + Ax + By + C = 0$ 
Persamaan garis singgungnya :  
$$x_1.x + y_1.y + A. \frac{(x_1+x)}{2} + B\frac{(y_1+y)}{2} + C = 0$$

### Contoh : 
1. Tentukan persamaan garis singgung lingkaran yang melalui titik (6, -8) pada lingkaran $x^2 + y^2 = 100$!  
  **Penyelesaian :**
    1. periksa bahwa titik (6, -8) terletak pada lingkaran $x^2 + y^2 = 100$ , substitusi titik tersebut ke persamaan lingkaran. Jika hasil ruas kiri sama dengan ruas kanan, maka titik tersebut dikatakan terletak pada lingkaran. 
    $$\begin{align*}
    (x,y) = (6,-8) \rightarrow x^2 + y^2 &= 100\\\\ 6^2 + (-8)^2 &= 100\\\\ 36 + 64 &= 100\\\\ 100 &= 100
    \end{align*}$$
    Karena hasil ruas kiri sama dengan ruas kanan, maka titik (6,-8) terletak pada lingkaran $x^2 + y^2 = 100$ dan merupakan titik singgung. 
    2. Menentukan persamaan garis singgung lingkaran 
    $$\begin{align*}
    (x_1,y_1) = (6,-8) \rightarrow x_1.x + y_1.y &= 100\\\\ 6x +(-8)y &= 100\\\\ 6x - 8y &= 100... \text{(bagi 2) } \\\\3x - 4y &= 50
    \end{align*}$$
    Jadi, PGS nya adalah $3x - 4y = 50$ 
2. Tentukan persamaan garis singgung lingkaran $(x + 2)^2 + (y - 3)^2 = 58 $pada titik $Q(1, -4)$.  
  **Penyelesaian :**   
    1. Periksa dahulu apakah titik $Q(1, -4)$ terletak pada lingkaran $(x + 2)^2 + (y - 3)^2 = 58$.
    $$\begin{align*}
    Q(1, -4) \Rightarrow &(1 + 2)^2 + (-4 − 3)^2 ? 58\\\\&3^2 + (-7)^2 = 9 + 49 = 58\text{ (benar)}
    \end{align*}$$
    Berarti titik $Q(1, -4)$ terletak pada lingkaran dan merupakan titik singgung
    2. Menentukan persamaan garis singgungnya di titik $(x_1,y_1)=(1,-4) $
    $$\begin{align*}
    (x_1-a)(x-a) + (y_1 - b)(y-b) &= r^2 \\\\(x_1+2)(x+2) + (y_1 - 3)(y-3) &= 58 \\\\(1+2)(x+2) + (-4 - 3)(y-3) &= 58 \\\\3(x+2) + (-7)(y-3) &= 58 \\\\3x + 6 - 7y + 21 &= 58 \\\\3x- 7y&= 31 
    \end{align*}$$ 
    Jadi, PGS nya adalah $3x- 7y = 31 $
3. Tentukan persamaan garis singgung lingkaran $x^2 + y^2 -8x + 12y +27 = 0 $pada titik A(7, -2).  
    **Penyelesaian :**  
    1. Periksa dahulu apakah titik $A(7, -2)$ terletak pada lingkaran $x^2 + y^2 -8x + 12y +27 = 0$.
    $$\begin{align*}
    A(7, -2) \Rightarrow &7^2+{-2}^2-8(7) + 12(-2) -27 ? 0\\\\&49+4-56-24+27 = 0\text{ (benar)}
    \end{align*}$$
    Berarti titik $A(7, -2)$ terletak pada lingkaran dan merupakan titik singgung 
    2. Menentukan persamaan garis singgungnya di titik $(x_1,y_1)=(7,-2) $
    $$\begin{align*}
    x_1.x + y_1.y + A. \frac{(x_1+x)}{2} + B\frac{(y_1+y)}{2} + C &= 0\\\\ x_1.x + y_1.y -8.\frac{(x_1+x)}{2} + 12.\frac{(y_1+y)}{2} + 27 &= 0\\\\ 7.x -2.y -8.\frac{(7+x)}{2} + 12.\frac{(-2+y)}{2} + 27 &= 0\\\\ 7x - 2y -4(7+x) + 6(-2+y) + 27 &= 0\\\\ 7x - 2y -28 -4x -12 + 6y + 27 &= 0\\\\ 3x-4y - 13 &= 0
    \end{align*}$$
    Jadi, PGS nya adalah $3x-4y - 13=0$ 
## 2. Persamaan Garis Singgung (PGS) Lingkaran dengan gradien $m $
Sebuah garis yang mempunyai gradien $m$ dan melalui titik $(0, c)$ dinyatakan dengan $𝑦 = 𝑚𝑥 + 𝑐$. Jikagaris tersebut menyinggunglingkaran $𝑥^2 + 𝑦^2 = 𝑟^2$, maka persamaan garis singgung lingkaran tersebut dapat diperoleh dengan langkah-langkah berikut.
![PGS gradien m](/images/matsma/lingkaran/pgs-gradien-m.jpg)
Substitusikan $𝑦 = 𝑚𝑥 + 𝑐$ ke dalam prsamaan lingkaran $𝑥^2 + 𝑦^2 = 𝑟^2$, sehingga diperoleh 
$$\begin{align*}
𝑥^2 + (mx+c)^2 &= 𝑟^2\\\\𝑥^2 + m^2x^2+2mx+c^2 &= 𝑟^2\\\\ x^2+m^2x^2+2mcx+c^2-r^2 &= 0\\\\ (1+m^2)x^2+2mcx+c^2-r^2 &= 0
\end{align*}$$
Terlihat persamaan kuadrat dengan variabel $x$. Garis menyinggung lingkaran (memotong lingkaran pada satu titik) jika nilai
diskriminan persamaan kuadrat di atas sama dengan $0$ $(D = b^2 - 4ac = 0)$. Diperoleh $a=1+m^2, b=2mc$ dan $c=c^2-r^2$. Oleh karena itu
$$\begin{align*}
D = 0\\\\b^2 - 4ac = 0\\\\ (2mc)^2 - 4(1+m^2)(c^2-r^2) = 0\\\\4m^2c^2 − 4 (c^2 + m^2c^2 − r^2 − m^2r^2)=0\\\\4m^2c^2 − 4c^2 − 4m^2c^2 + 4r^2 + 4m^2r^2 = 0\\\\− 4c^2 + 4r^2 + 4m^2r^2 = 0\\\\4c^2 = 4r^2 + 4m^2r^2\\\\ c^2 = r^2 + m^2r^2\\\\ c^2 = r^2(1 + m^2)\\\\ c=\pm r\sqrt{m^2+1}
\end{align*}$$
Dari penjabaran diatas diperoleh :
1. Persamaan Garis Singgung dengan Gradien $m $(persamaan umum garis $y=mx+c$) terhadap Lingkaran $x^2 + y^2 = r^2 $
\
Persamaan garis singgungnya : 
$$\begin{align*}y = mx \plusmn r \sqrt{1 + m^2}\end{align*}$$ 

2. Persamaan Garis Singgung dengan Gradien $m $(persamaan umum garis $y-b=m(x-a)+c$) terhadap Lingkaran$ (x-a)^2 + (y-b)^2 = r^2 $
\
Persamaan garis singgungnya : $$\begin{align*}y - b = m(x-a) \plusmn r \sqrt{1 + m^2}\end{align*}$$ 

3. Persamaan Garis Singgung dengan Gradien $m $terhadap Lingkaran $x^2 + y^2 + Ax + By + C = 0$ 
\
Untuk persamaan lingkaran dalam bentuk umum $x^2 + y^2 + Ax + By + C = 0$, maka terlebih dahulu diubah ke dalam bentuk baku $(𝑥 − 𝑎)^2 + (𝑦 − 𝑏)^2 = 𝑟^2$ atau langsung menentukan pusat lingkaran $(−\dfrac12 A,−\dfrac12 B )$ dan jari-jari $𝑟 = \sqrt{\dfrac14 A^2+\dfrac14 B^2 -C}$, kemudian menentukan persamaan garis singgungnya dengan rumus di atas.
### Tambahan (hubungan antara dua garis)
Karena ada kaitannya dengan gradien, maka biasanya juga melibatkan hubungan antara dua garis. Misalkan $m_1$ adalah gradien garis $g_1$ dan $m_2$ adalah gradien garis $g_2$
- Dua garis sejajar atau Jika garis $g_1$ sejajar dengan garis $g_2$, maka gradiennya sama : $m_1 = m_2 $
- Dua garis tegak lurus atau Jika garis $g_1$ tegak lurus dengan garis $g_2$ : $m_1 . m_2 = -1 $

### Contoh : 
1. Tentukan persamaan garis singgung dengan gradien $\sqrt{8} \\, $pada lingkaran $x^2 + y^2 = 16 $!  
    **Penyelesaian :**  
    1. Menentukan unsur-unsur lingkaran :  
    $x^2 + y^2 = 16,\, $jari-jari : $r^2 = 16 \rightarrow r = 4 $
    2. Menentukan PGS dengan gradien $m = \sqrt{8} $ 
    $$\begin{align*}
    y &= mx \plusmn r \sqrt{1 + m^2} \\\\ y &= \sqrt{8}x \plusmn 4 \sqrt{1 + (\sqrt{8})^2} \\\\ y &= \sqrt{8}x \plusmn 4 \sqrt{1 + 8} \\\\ y &= \sqrt{8}x \plusmn 4 . 3\\\\ y &= \sqrt{8}x \plusmn 12 
    \end{align*}$$
    Jadi, PGS nya adalah $y= \sqrt{8}x + 12 $dan $y= \sqrt{8}x - 12$ 

2. Tentukan persamaan garis singgung yang sejajar dengan garis $y = 2x - 3 \\, $pada lingkaran $(x-2)^2 + (y+1)^2 = 1 $!  
    **Penyelesaian :**  
    1. Menentukan unsur-unsur lingkaran : 
    $(x-2)^2 + (y+1)^2 = 1$, jari-jari : $r^2 = 1 \rightarrow r = 1 $ 
    Pusatnya : $(a,b) = (2, -1) $
    2. Menentukan gradien garis singgungnya 
    Garis $y = 2x - 3 \rightarrow m_1 = 2 $ 
    Karena sejajar, maka gradiennya sama, sehingga $m = 2 $
    3. Menentukan PGS dengan gradien $m = 2$ 
    $$\begin{align*}
    y - b &= m(x-a) \plusmn r \sqrt{1 + m^2} \\\\ y - (-1) &= 2(x - 2) \plusmn 1. \sqrt{1 + 2^2} \\\\ y + 1 &= 2x - 4 \plusmn\sqrt{5} \\\\ y&= 2x - 4 - 1 \plusmn\sqrt{5} \\\\ y&= 2x - 5 \plusmn\sqrt{5} 
    \end{align*}$$
    Jadi, PGS nya adalah $y= 2x - 5 +\sqrt{5}$ dan $y= 2x - 5 -\sqrt{5}$ 
3. Tentukan persamaan garis singgung yang tegak lurus dengan garis $-3x + 4y - 1 = 0, \\, $pada lingkaran $x^2 + y^2 + 4x - 2y + 1 = 0 $!  
    **Penyelesaian :**  
    1. Menentukan unsur-unsur lingkaran : 
    $x^2 + y^2 + 4x - 2y + 1 = 0,\rightarrow A = 4, B = -2, C = 1 $ 
    Pusatnya : $(a,b) = \left( -\frac{A}{2} , - \frac{B}{2} \right) = \left( -\frac{4}{2}, - \frac{-2}{2} \right) = (-2,1)$  
    Jari-jari : $r = \sqrt{a^2 + b^2 - C} = \sqrt{(-2)^2 + 1^2 - 1} = 2 $
    2. Menentukan gradien garis singgungnya 
    Garis $-3x + 4y - 1 = 0\rightarrow m_1 = -\frac{-3}{4} = \frac{3}{4} $ 
    Karena tegak lurus, maka $m.m_1 = -1 \rightarrow m . \frac{3}{4} = -1 \rightarrow m = - \frac{4}{3} $
    3. Menentukan PGS dengan gradien $m = - \frac{4}{3}$  
    $$\begin{align*}
    y - b &= m(x-a) \plusmn r \sqrt{1 + m^2} \\\\ y - 1 &= - \frac{4}{3}.(x - (-2)) \plusmn 2. \sqrt{1 + (- \frac{4}{3})^2} \\\\ y - 1 &= - \frac{4}{3}.(x + 2) \plusmn 2 \sqrt{1 + \frac{16}{9}} \\\\ y - 1 &= - \frac{4}{3}x - \frac{8}{3} \plusmn 2 \sqrt{ \frac{25}{9}} \\\\ y - 1 &= - \frac{4}{3}x - \frac{8}{3} \plusmn 2 . \frac{5}{3} \\\\ y - 1 &= - \frac{4}{3}x - \frac{8}{3} \plusmn\frac{10}{3}\\, \\, \text{(kali 3)} \\\\ 3y - 3 &= - 4x - 8 \plusmn10 \\\\3y&= - 4x - 8 + 3 \plusmn10 \\\\ 3y&= - 4x - 5 \plusmn10 \\\\ \text{(PGS I) } : 3y&= - 4x - 5 +10 \\\\ 3y &= -4x + 5 \\\\ 4x + 3y &= 5\\\\ \text{(PGS II) } : 3y&= - 4x - 5 -10 \\\\ 3y &= -4x - 15 \\\\ 4x + 3y &= -15
    \end{align*}$$
    Jadi, PGS nya adalah $4x + 3y= 5 \\, $dan $4x + 3y= -15$ 
## 3. Persamaan Garis Singgung Melalui Suatu Titik di Luar Lingkaran
Misalkan titik yang dilalui adalah titik D($x_d,y_d$) di luar lingkaran. Dari titik yang tersebut bisa ditarik dua garis singgung melalui titik pada lingkaran misalnya A($x_a,y_a$) dan titik B($x_b,y_b$). 

Ada tiga cara menentukan persamaan garis singgungnya, yaitu : 
1. Menggunakan diskriminan persamaan kuadrat sekutu.  
    Langkah-langkah penyelesaian :  
    1. Misalkan garis singggungnya $y-y_d = m(x-x_d)$ , 
    2. Substitusi titik D($x_d,y_d$) ke garis $y-y_d = m(x-x_d)$, terbentuk persamaan garis singgung baru. 
    3. Substitusi garis yang baru ke persamaan lingkaran, lalu tentukan nilai diskriminannya ($D$). 
    4. Tentukan nilai $m$ dengan syarat garis menyinggung lingkaran : $D = 0$. 
    5. Substitusi nilai $m$ yang diperoleh ke garis baru yang terbentuk. 
2. Menggunakan rumus persamaan garis singgung dengan gradien diketahui.  
    Langkah-langkah penyelesaian :  
    1. Misalkan garis singggungnya $y-y_d = m(x-x_d)$, 
    2. Ingat garis singggung lingkaran dengan gradien $m$ adalah $y = mx \plusmn r \sqrt{1 + m^2}$ untuk pusat $P(0,0)$, 
    3. samakan persamaan pada langkah 1 dan 2, maka diperoleh gradien $m$
    4. Substitusikan nilai $m$ ke dalam persamaan pada langkah 1 
3. Menggunakan garis kutub (polar).  
    Jika titik D($x_d, y_d$) di luar lingkaran ditarik dua buah garis singgung pada lingkaran dengan titik singgungnya A($x_a, y_a$) dan B($x_b, y_b$), maka persamaan garis AB disebut garis kutub pada lingkaran dan titik D($x_d, y_d$) disebut titik kutub. 
    ![Persamaan garis Kutub](/images/matsma/lingkaran/persamaan-garis-kutub.jpg)
    Garis singgung $g_1$ dan $g_2$ melalui titik $D(x_d,y_d)$, maka berlaku:
    $x_ax_d+y_ay_d=r^2$ dan $x_bx_d+y_by_d=r^2$ jika pusat lingkaran adalah $O(0,0)$.
    Dari dua persamaan di atas, dapat disimpulkan bahwa koordinat-koordinat titik $A(x_a,y_a)$ dan $B(x_b,y_b)$ memenuhi persamaan $x_dx+y_dy=r^2$.  
    Dari uraian diatas dapat disimpulkan
    1. Persamaan garis kutub/polar dari titik $D(x_d,y_d)$ terhadap lingkaran $L:x^2+y^2=r^2$ adalah $$x_dx+y_dy=r^2$$
    2. Persamaan garis kutub/polar dari titik $D(x_d,y_d)$ terhadap lingkaran $(x-a)^2+(y-b)^2=r^2$, adalah $$(x_d-a)(x-a)+(y_d-b)(y-b)=r^2$$
    3. Persamaan garis kutub/polar dari titik $D(x_d,y_d)$ terhadap lingkaran $x^2+y^2+Ax+By+C=0$ adalah $$x_dx+y_dy+\frac{1}{2}A(x_d+x)+\frac{1}{2}B(y_d+y)+C=0$$
    Untuk menyelesaikan persamaan garis singgung dengan menggunakan garis kutub ikuti langkah-langkah penyelesaian berikut : 
    1. Membuat persamaan garis kutub dari titik D($x_d, y_d$) terhadap lingkaran. 
    2. Substitusi garis kutub yang terbentuk ke persamaan lingkaran, lalu selesaikan untuk menentukan nilai $x \\, $. 
    3. Substitusi nilai $x$ atau $y$ yang diperoleh ke persamaan garis kutub untuk menentukan titik B dan C. 
    4. Titik A dan B adalah titik pada lingkaran yang dilalui oleh garis singgung, selanjutnya gunakan cara menentukan persamaan garis singgung lingkaran melalui titik pada lingkaran.

### Contoh
Tentukan persamaan garis singgung melalui titik (7, 1) di luar lingkaran $x^2 + y^2 = 25 $!  
**Penyelesaian :**  
**Cara I :Menggunakan diskriminan persamaan kuadrat sekutu.**
- Titik (7, 1) berada di luar lingkaran $x^2 + y^2 = 25 $sebab jika titik (7, 1) disubstitusikan
ke persamaan lingkaran tersebut diperoleh $7^2+1^2 = 49 + 1 = 50 > 25 $. 
- Misalkan persamaan garis singgungnya : $y-y_1 = m(x-x_1)$ 
- Titik (7,1) dilalui oleh garis singgung, sehingga bisa disubstitusi ke garis singgung : 
$$\begin{align*}
(x,y)=(7,1) \rightarrow y-y_1&= m(x-x_1)\\\\y-1 &= m(x-7)\\\\ y-1 &= mx-7m\\\\ y&=mx-7m+1...(1)
\end{align*}$$
- Substitusi garis singgung baru (1) ke lingkaran : 
$$\begin{align*}
y = mx-7m+1 \rightarrow x^2 + y^2 &= 25\\\\ x^2 + (mx-7m+1)^2 &= 25 \\\\ x^2 + m^2x^2 -49m^2+1-14m^2x+2mx-14m &= 25 \\\\(m^2+1)x^2 +(2m-14m^2)x + (-49m^2-14m-24) &= 0
\end{align*}$$
diperoleh $a = m^2 + 1, \\, b = 2m - 14m^2 , \\, c = -49m^2-14m-24$
- Menentukan nilai Diskriminan ($D$): 
$$\begin{align*}
D &= b^2 - 4ac \\\\&= (2m-14m^2)^2 - 4.(m^2+1).(-49m^2-14m-24)\\\\&= 4m^2 - 56m^3 + 196m^4 - 4(49m^2 - 14m - 24 + 49m^4 - 14m^3 - 24m^2)\\\\&= -96m^2 + 56m + 96
\end{align*}$$
  - Agar garis menyinggung lingkaran, maka diskriminan persamaan kuadrat sekutu sama dengan nol $( D = 0 )$  
  $$\begin{align*}
  D&=0 \\\\-96m^2 + 56m + 96&= 0 \\, \\, \\, \\, \text{(bagi -8)}\\\\12m^2 - 7m - 12 &= 0 \\\\(4m + 3)(3m - 4) &= 0\\\\ m = - \frac{3}{4} \vee m&=\frac{4}{3} 
  \end{align*}$$
  - Substitusi nilai $m \\, $ke garis singgung baru (1) : 
  $$\begin{align*}
  m = - \frac{3}{4} \rightarrow y &= mx -7m+1\\\\ y &= - \frac{3}{4} . x -7.(- \frac{3}{4})+1\\\\ y &= - \frac{3}{4} . x + \frac{21}{4}+1\\\\ y &= - \frac{3}{4} . x +\frac{25}{4} \\, \\, \\, \\, \text{(kali 4)}\\\\4y &= -3x + 25 \\\\3x + 4y &= 25\\\\m = \frac{4}{3} \rightarrow y &= mx -7m+1\\\\ y &= \frac{4}{3} . x -7.(\frac{4}{3})+1\\\\ y &= \frac{4}{3} . x - \frac{28}{3}+1\\\\ y &= \frac{4}{3} . x - \frac{25}{3} \\, \\, \\, \\, \text{(kali 3)}\\\\3y &= 4x- 25 \\\\4x - 3y &= 25 
  \end{align*}$$
Jadi, PGS nya adalah $3x + 4y= 25$ dan $4x - 3y= 25 $. 

**Cara II : Menggunakan rumus persamaan garis singgung dengan gradien diketahui.**
- Persamaan garis singgung melalui titik P(7, 1) dimisalkan 
$$\begin{align*}
y-y_1 &= m(x-x_1)\\\\y-1 &= m(x-7)\Leftrightarrow y=mx-7m+1....(1)
\end{align*}$$
- Persamaan garis singgung lingkaran $x^2 + y^2 = 25$ dengan gradien $m$ diperoleh $r^2=25\Rightarrow r=5$ adalah  
$$\begin{align*}
y &= mx \plusmn r \sqrt{1 + m^2}\\\\y &= mx \plusmn 5 \sqrt{1 + m^2}....(2)
\end{align*}$$
- Selanjutnya ruas kanan persamaan (1) dan (2) disamakan, sehingga diperoleh
$$\begin{align*}
mx \plusmn 5 \sqrt{1 + m^2}&=mx-7m+1\\\\ \plusmn 5 \sqrt{1 + m^2}&=-7m+1...\text{dikuadratkan}\\\\ 25(1+m^2)&=49m^2-14m+1\\\\25+25m^2&=49m^2-14m+1\\\\24m^2-14m-24&=0...\text{bagi 2}\\\\12m^2-7m-12&=0\\\\(3m-4)(4m+3)&=0\\\\ m = \dfrac43 \vee m&= -\dfrac34
\end{align*}$$
- Selanjutnya nilai $m$ disubstitusikan ke dalam persamaan (2) sehingga diperoleh dua garis singgung seperti pada cara diskriminan, yaitu
$$\begin{align*}
m = - \frac{3}{4} \rightarrow y &= mx -7m+1\\\\ y &= - \frac{3}{4} . x -7.(- \frac{3}{4})+1\\\\ y &= - \frac{3}{4} . x + \frac{21}{4}+1\\\\ y &= - \frac{3}{4} . x +\frac{25}{4} \\, \\, \\, \\, \text{(kali 4)}\\\\4y &= -3x + 25 \\\\3x + 4y &= 25\\\\m = \frac{4}{3} \rightarrow y &= mx -7m+1\\\\ y &= \frac{4}{3} . x -7.(\frac{4}{3})+1\\\\ y &= \frac{4}{3} . x - \frac{28}{3}+1\\\\ y &= \frac{4}{3} . x - \frac{25}{3} \\, \\, \\, \\, \text{(kali 3)}\\\\3y &= 4x- 25 \\\\4x - 3y &= 25 
\end{align*}$$
Jadi, PGS nya adalah $3x + 4y= 25$ dan $4x - 3y= 25 $.

**Cara III : Menggunakan garis kutub (polar)**
- Menentukan persamaan garis kutub di titik (7,1) : 
$$\begin{align*}
x_1x + y_1y &= r^2\\\\7.x + 1.y &= 25\\\\y &= 25 - 7x\\\\y &= 25 - 7x
\end{align*}$$
- Substitusi $y = 25 - 7x$ ke $x^2 + y^2 = 25 $
$$\begin{align*}
x^2 + y^2 &= 25\\\\x^2 + (25 - 7x)^2 &= 25\\\\x^2 + 49x^2 - 350x + 625&= 25\\\\x^2 + 49x^2 - 350x + 600&= 0\\\\50x^2 - 350x + 600&= 0\, \\, \\, \\, \text{(bagi 50)} \\\\x^2 - 7x + 12&= 0 \\\\(x - 3 )(x - 4) &=0 \\\\
x = 3\vee x&= 4
\end{align*}$$
- Menentukan titik singgungnya : 
$$\begin{align*}
x = 3 \rightarrow y &= 25 - 7x\\\\ y &= 25 - 7.3\\\\ y &= 4\\\\x = 4 \rightarrow y &= 25 - 7x\\\\ y &= 25 - 7.4\\\\ y &= -3 
\end{align*}$$
Titik singgungnya : $(3,4)$ dan $(4,-3)$ . 
- Menentukan PGS dengan cara melalui titik pada linkaran 
titik $(x_1,y_1) = (3,4) $
$$\begin{align*}
x^2 + y^2 &= 25\\\\x_1x + y_1y &= 25\\\\3x + 4y&=25
\end{align*}$$
titik $(x_1,y_1) = (4,-3) $
$$\begin{align*}
x^2 + y^2 &= 25\\\\x_1x + y_1y &= 25\\\\4x -3y&=25
\end{align*}$$
Jadi, PGS nya adalah $3x + 4y= 25\, $dan $4x - 3y= 25 $. 



