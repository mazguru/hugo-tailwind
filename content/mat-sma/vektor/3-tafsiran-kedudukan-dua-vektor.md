---
title : "Tafsiran Geometri dari kedudukan dua vektor atau lebih"
description : "Tafsiran Geometri dari kedudukan dua vektor atau lebih, Perbandingan Dua Vektor dan Kolinear"
date : 2022-01-10T19:12:16+07:00
math : true
featured : false
draft : false
comment : true
toc : true
keywords : 
  - matematika
  - vektor
  - vektor geometri
  - vektor aljabar
  - kedudukan dua vektor
  - Tafsiran Geometri dari kedudukan dua vektor atau lebih
kategori : 
  - Aljabar
topik :
  - vektor
  - kedudukan dua vektor
  - kelas X
seri : 
  - Matematika SMA
images : 
 - header/tafsiran-geometri-vektor.jpg
tumbnail : 
 - tumbnail/tafsiran-geometri-vektor.jpg
cover : 
  - images/icon/vektor.svg
---
	
## 1. Vektor segaris (kolinear)
Titik P, N, dan Q dikatakan segaris (kolinear) apabila vektor yang dibangun oleh dua titik di antaranya dapat dinyatakan sebagai perkalian vektor dua titik yang lain. Dengan demikian, jika titik-titik P, N dan Q terletak pada satu garis lurus, N dikatakan membagi ruas garis PQ dengan perbandingan k, apabila $\overrightarrow{PN}~=k\text{ }\overrightarrow{NQ}$.
![Vektor Segaris](/images/matsma/vektor/vektor-segaris.jpg)
### Pengertian titik-titik segaris (kolinear)
Tiga buah titik P, N, dan Q dikatakan segaris (kolinear) jika dan hanya jika $(\Leftrightarrow )$

{{< alert "$\overrightarrow{PN}~=k\text{ }\overrightarrow{ NQ}$ atau $\overrightarrow{PN}~=k\text{ }\overrightarrow{PQ}$ atau $\overrightarrow{NQ}~=k\text{ }\overrightarrow{PQ}$" >}} 
dengan $k$ bilangan real tidak nol.
#### Contoh Pembuktian Kolinear
Vektor posisi P, Q, dan R terhadap O adalah $\overline{p}=3\overline{b}+5\overline{c}-2\overline{a}$, $\overline{q}=\overline{a}+2\overline{b}+3\overline{c}$, dan $\overline{r}=7\overline{a}-c$. Tunjukkan bahwa ketiga titik itu segaris  
**Alternatif penyelesaian**
$$\begin{align*}
\overrightarrow{OP}&=3\overline{b}+5\overline{c}-2\overline{a} \\\\\overrightarrow{OQ}&=\overline{a}+2\overline{b}+3\overline{c} \\\\\overrightarrow{OR}&=7\overline{a}-\overline{c}
\end{align*}$$
$$\begin{align*}
\overrightarrow{PQ}&=\overrightarrow{OQ}-\overrightarrow{OP} \\\\ \overrightarrow{PQ}&=(\overline{a}+2\overline{b}+3\overline{c})-(3\overline{b}+5\overline{c}-2\overline{a}) \\\\ \overrightarrow{PQ}&=3\overline{a}-\overline{b}-2\overline{c}
\end{align*}$$
$$\begin{align*}
\overrightarrow{PR}&=\overrightarrow{OR}-\overrightarrow{OP} \\\\ \overrightarrow{PR}&=(7\overline{a}-\overline{c})-(3\overline{b}+5\overline{c}-2\overline{a}) \\\\ \overrightarrow{PR}&=3(3\overline{a}-\overline{b}-2\overline{c})
\end{align*}$$
Terlihat bahwa $\overrightarrow{PR}=3\overrightarrow{PQ}$ sehingga ada bilangan $k=3$ yang membuat ketiga titik itu segaris. (Terbukti)

## 2. Formula Perbandingan
Pada gambar $PN:NQ=m:n$  
maka $\overrightarrow{PN}=\frac{m}{n}\overrightarrow{NQ}$  
sehingga $k=\frac{m}{n}$
![Vektor Segaris](/images/matsma/vektor/formula-perbandingan.jpg)
Dari perbandingan ini, titik N dapat dinyatakan sebagai vektor posisi n dalam vektor  posisi titik P dan Q. Caranya sebagai berikut
$$\begin{align*}
\overline{n}&=\overline{p}+\overrightarrow{PN} \\\\ \overline{n}&=\overline{p}+\frac{m}{m+n}\overrightarrow{PQ} \\\\ \overline{n}&=\overline{p}+\frac{m}{m+n}(\overline{q}-\overline{p}) \\\\ \overline{n}&=\frac{m\overline{p}+n\overline{p}+m\overline{q}-m\overline{p}}{m+n} \\\\ \overline{n}&=\frac{m\overline{q}+n\overline{p}}{m+n}\\\\ \therefore \overline{n}=\frac{m\overline{q}+n\overline{p}}{m+n}
\end{align*}$$
Jika T merupakan titik tengah PQ dan $m=n$ maka Vektor posisi $\overline{t}$ ditentukan oleh:
$$\overline{t}=\frac{1}{2}(\overline{a}+\overline{b})$$
### Contoh
Diberikan ∆ABC dengan vektor posisi dari A, B, dan C terhadap titik O, yaitu $\overline{a}=3\overline{p}+2\overline{q},$ $\overline{b}=-5\overline{p}-3\overline{q},$dan $\overline{c}=4\overline{p}-\overline{q}$. M titik tengah AB dan titik N pada AC sedemikian sehingga  $\overrightarrow{AN}=\frac{1}{3}\overrightarrow{AC}.$ Tentukan Vektor posisi M dan N dalam bentuk $\overline{p}$ dan $\overline{q}$.

**Alternatif penyelesaian**  
M titik tengah AB, berarti:
$$\begin{align*}
\overline{m}&=\overrightarrow{OM} \\\\ \overline{m}&=\frac{\overline{a}+\overline{b}}{2} \\\\ \overline{m}&=\frac{3\overline{p}+2\overline{q}-5\overline{p}-3\overline{q}}{2} \\\\ \overline{m}&=\frac{-2\overline{p}-\overline{q}}{2} \\\\ \therefore \overline{m}&=\overline{p}-\frac{1}{2}\overline{q}
\end{align*}$$	

$\overrightarrow{AN}=\frac{1}{3}\overrightarrow{AC}$ berarti N membagi AC dengan rasio 1:2

$\therefore \overrightarrow{ON}=\frac{2\overrightarrow{OA}+1\overrightarrow{OC}}{1+2}$
$$\begin{align*}
\overline{n}&=\frac{2(3\overline{p}+2\overline{q})+4\overline{p}-\overline{q}}{3} \\\\ 
\overline{n}&=\frac{10\overline{p}+3\overline{q}}{3} \\\\ \overline{n}&=\frac{10}{3}\overline{p}+\overline{q}
\end{align*}$$
## 3. Pengertian tentang kombinasi linear dan basis
Jika $ \overline{v_1},\overline{v_2},\overline{v_3},...,\overline{v_n}$ adalah Vektor-vektor dalam ruang $R^2$. Maka untuk setiap Vektor $\overline{v}\in R^2$, Vektor $\overline{v}$ dapat dinyatakan sebagai kombinasi linear dalam $\overline{v_1},\overline{v_2},\overline{v_3},...,\overline{v_n}$ yaitu: 

$\vec{v}=k_1\vec{v}_1+k_2\vec{v}_2+k_3\vec{v}_3+...+k_n\vec{v}_n$ dengan $k_1,k_2,k_3,...,k_n$ adalah skalar-skalar real. Jika $k_1,k_2,k_3,...,k_n$ tunggal, maka Vektor-vektor $\vec{v}_1,\vec{v}_2,\vec{v}_3,...,\vec{v}_n$ itu disebut basis dalam ruang $R^2$

Perhatikan gambar berikut, menunjukkan dua Vektor tak sejajar dan tak searah $\overline{u}$ dan $\overline{v}.$
![kombinasi linear basis](/images/matsma/vektor/kombinasi-linear-basis.jpg)
Jika $\overrightarrow{OC}=q.\overline{v}$ dan $\overrightarrow{OB}=p.\overline{u}$ dengan $p$dan $q$ konstanta, berdasarkan aturan jajargenjang diperoleh:
$\overrightarrow{OA}=\overline{a}=p.\overline{u}+q.\overline{v}$
Hal ini berarti Vektor $\overline{a}$ dibentuk dari kombinasi linear $p.\overline{u}$ dan $q.\overline{v}$ dengan $\overline{u}$ dan $\overline{v}$ basis untuk Vektor $\overline{a}.$

### Contoh
Dari ∆OAB diketahui C pada AB dan D pada OB. T pada perpotongan OC dan AD. Perbandingan AC:CB = 2:1 dan OD:DB = 1:3. Tentukan OT:TC !

**Alternatif penyelesaian**  
Karena OAB berikut komponen-komponennya terletak sebidang, maka ia berdimensi 2 (dua). Untuk itu setiap 2 vektor yang tak searah akan merupakan basis untuk R. Akibatnya setiap vektor dapat dinyatakan sebagai kombinasi linear dari kedua basis itu secara tunggal.   
Misalkan basisnya adalah OA dan OB (vektor OA = a dan OB = b), maka
$$\begin{align*}
\overrightarrow{AC}&=\frac{2}{3}\overrightarrow{AB} \\\\ \overrightarrow{AC}&=\frac{2}{3}(\overrightarrow{AO}+\overrightarrow{OB}) \\\\ \overrightarrow{AC}&=\frac{2}{3}(-\overline{a}+\overline{b}).........(1)
\end{align*}$$

$$\begin{align*}
\overrightarrow{AD}&=\overrightarrow{AO}+\overrightarrow{OD} \\\\ \overrightarrow{AD}&=\overrightarrow{AO}+\frac{1}{4}\overrightarrow{OB}) \\\\ \overrightarrow{AC}&=-\overline{a}+\frac{1}{4}\overline{b}..........(2)
\end{align*}$$


Karena $\overrightarrow{OT}$  searah dengan $\overrightarrow{OC}$  maka $\overrightarrow{OT}=\lambda \overrightarrow{OC}$ ,  $\lambda $ suatu Scalar
$$\begin{align*}
\overrightarrow{OT}&=\lambda \overrightarrow{OC} \\\\ 
\overrightarrow{OT}&=\lambda (\overrightarrow{OA}+\overrightarrow{AC}) \\\\ 
\overrightarrow{OT}&=\lambda (\overline{a}+\frac{2}{3}(-\overline{a}+\overline{b}) \\\\ 
\overrightarrow{OT}&=\frac{1}{3}\lambda \overline{a}+\frac{2}{3}\lambda \overline{b}...........(3)
\end{align*}$$
Dilain pihak $\overrightarrow{AT}$  searah dengan $\overrightarrow{AD}$  maka $\overrightarrow{AT}=\mu \overrightarrow{AD}$ ,  $\lambda $ suatu Scalar
$$\begin{align*}
\overrightarrow{OT}&=\overrightarrow{OA}+\overrightarrow{AT} \\\\ 
\overrightarrow{OT}&=\overline{a}+\mu (-\overline{a}+\frac{1}{4}\overline{b}) \\\\ 
\overrightarrow{OT}&=(1-\mu )\overline{a}+\frac{1}{4}\mu \overline{b}..............(4)
\end{align*}$$
Dengan menyamakan koefisien $\overline{a}$ dan $\overline{b}$ pada (3) dan (4) yaitu:  
Koefisien $\overline{a}$ diperoleh $1-\mu =\frac{1}{3}\lambda $  
Koefisien $\overline{b}$ diperoleh $\frac{1}{4}\mu =\frac{2}{3}\lambda $ maka $\mu =\frac{8}{3}\lambda $  
$\mu =\frac{8}{3}\lambda $ disubstitusikan ke $1-\mu =\frac{1}{3}\lambda $ diperoleh 
$$\begin{align*}
1-\frac{8}{3}\lambda &=\frac{1}{3}\lambda  \\\\ 1&=\frac{9}{3}\lambda  \\\\ \lambda &=\frac{1}{3}
\end{align*}$$
$\lambda =\frac{1}{3}$ disubstitusikan ke $\mu =\frac{8}{3}\lambda $ diperoleh
$$\begin{align*}
\mu &=\frac{8}{3}.\frac{1}{3} \\\\ 
\mu &=\frac{8}{9} \end{align*}$$
Karena $\overrightarrow{OT}=\lambda \overrightarrow{OC}$dan  $\lambda =\frac{1}{3}$ maka $\overrightarrow{OT}=\frac{1}{3}\overrightarrow{OC}$  

Selanjutnya karena $\overrightarrow{OT}=\frac{1}{3}\overrightarrow{OC}$ maka  $\left| \overrightarrow{OT} \right|=\frac{1}{3}\left| \overrightarrow{OC} \right|$atau  $\frac{OT}{OC}=\frac{1}{3}$  
Terakhir karena $\frac{OT}{OC}=\frac{1}{3}$ maka $\frac{OT}{TC}=\frac{1}{(3+1)}=\frac{1}{2}$ atau $OT:TC=1:2$  
Jadi, perbandingan OT:TC adalah 1:2

### Latihan 2
1. Diketahui  ABC 
Titik D pada BC  sehingga BD:DC = 2:1.
Titik E pada pertengahan AB 
Jika Z adalah titik potong AD dan CE , tentukan AZ:ZD = … dan   CZ:ZE = ….
![Soal 1](/images/matsma/vektor/soal-c1.jpg)

2. Diketahui persegi panjang ABCD, titik M dan N berturut-turut terletak pada pertengahan AB  dan DC. Titik P dan Q berturut-turut merupakan titikpotong diagonal AC  dengan ruas-ruas garis DM dan BN. 
![Soal 2](/images/matsma/vektor/soal-c2.jpg)
Buktikan bahwa AP = PQ = QC = $\frac{1}{3}$AC.

3. Dalil Menelaus  
Diketahui ∆ABC dengan transversal (garis yang memotong sisi-sisi segitiga atau perpanjangannya) PR. 
![Soal 3](/images/matsma/vektor/soal-c3.jpg)
Buktikan bahwa $\frac{AR}{RB}\times \frac{BQ}{QC}\times \frac{CP}{PA}=1$

4. Dalil De Ceva  
Segitiga ∆ABC dengan AQ, BR,  dan CP berpotongan di titik Z. Titik P, Q, dan R berturut-turut terletak pada ruas garis AB, BC, dan CA. 
![Soal 4](/images/matsma/vektor/soal-c4.jpg) 
Buktikan bahwa $\frac{AP}{PB}\times \frac{BQ}{QC}\times \frac{CR}{RA}=1$
 

