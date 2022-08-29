---
title : "Perkalian Cross Vektor (Perkalian Silang)"
description : Suatu hal yang hanya berlaku untuk ruang vektor berdimensi tiga R3 adalah cross vektor (perkalian vektor antara 2 vektor), yakni perkalian antara 2 vektor yang menghasilkan vektor tunggal.
date : 2022-04-13T23:31:26+07:00
math : true
featured : false
draft : false
comment : true
toc : false
keywords : 
 - matematika
 - cross vektor
 - perkalian cross vektor
 - vektor
 - perkalian silang
 - perkalian silang dua vektor
kategori : 
 - Aljabar
topik :
 - vektor
 - vektor aljabar
 - kelas X
seri : 
 - Matematika SMA
images : 
- header/cross-vektor.jpg
tumbnail : 
- tumbnail/cross-vektor.jpg
cover : 
- images/icon/vektor.svg
---

Suatu hal yang hanya berlaku untuk ruang vektor berdimensi tiga R3 adalah cross vektor (perkalian vektor antara 2 vektor), yakni perkalian antara 2 vektor yang menghasilkan vektor tunggal.

*Cross product* atau hasil kali silang merupakan hasil kali antara dua vektor di ruang dimensi tiga (R3) yang menghasilkan vektor tegak lurus terhadap kedua vektor yang dikalikan. Atau dapat juga dikatakan bahwa perkalian silang antara dua vektor akan menghasilkan vektor baru yang arahnya tegak lurus dengan masing-masing vektor. 

Penentuan arah vektor pada perkalian silang dapat menggunakan kaidah tangan kanan yang melibatkan telapak tangan, empat jari, dan jempol/ibu jari. Di mana, telapak tangan menuju arah vektor pertama yang akan dikalikan dan empat jari menuju arah vektor kedua. Kemudian, arah vektor satuan hasil perkalian ditunjukkan oleh ibu jari.
![Kaidah tangan kanan](/images/matsma/vektor/kaidah-tangan.jpg)

## 1.	Definisi
Jika $\vec{u} \ne 0$ dan $\vec{v}\ne 0$ dalam ruang dapat diputar tanpa mengubah besar atau arah masing-masing sehingga titik pangkalnya berimpit, dengan kaidah tangan kanan (ulir kanan) didefinisikan bahwa:
$$\vec{u}\times \vec{v}=\widehat{e}\left| \vec{u} \right|\left| \vec{v} \right|\sin \theta ,\text{ 0}\le \theta \le \pi $$

$\widehat{e}$= vektor satuan yang tegak lurus $\vec{u}$ dan $\vec{v}$  
$\vec{u}\times \vec{v}$ dibaca “vektor u kros vektor v” atau cukup dengan “u kros v” saja.

### Rumus determinan cross vektor
Perkalian vektor dua vektor ditulis dengan $\vec{u}\times \vec{v}$ dirumuskan dengan determinan matriks sebagai berikut.

Jika $\vec{u}=a_1\widehat{i}+a_2\widehat{j}+a_3\widehat{k}$ dan $\vec{v}=b_1\widehat{i}+b_2\widehat{j}+b_3\widehat{k}$ maka
$$\vec{u}\times \vec{v}=\left| \begin{matrix}\widehat{i} & \widehat{j} & \widehat{k}\\\\ a_1 & a_2 & a_3\\\\ b_1 & b_2 & b-3  \end{matrix} \right|$$
dengan aturan Sarrus akan diperoleh hasil perkalian sebagai berikut.
![aturan sarrus](/images/matsma/vektor/aturan-sarrus.jpg)
$$\vec{u}\times \vec{v}=(a_2b_3-a_3b_2)\widehat{i}+(a_3b_1-a_1b_3)\widehat{j}+(a_1b_2-a_2b_1)\widehat{k}$$
## 2.	Sifat 
1. Sifat 1: $\vec{u}\times \vec{v}$  merupakan vektor yang tegak lurus vektor $\vec{u}$ dan tegak lurus vektor $\vec{v}$.
2. Sifat 2: $\vec{u}\times \vec{v}$  berlawanan arah dengan $\vec{v}\times \vec{u}$ sehingga $\vec{u}\times \vec{v}=-\vec{v}\times \vec{u}$

**Dalil:** $\left| \vec{u}\times \vec{v} \right|=\left| \vec{u} \right|\left| \vec{v} \right|\sin \theta $

Buktikanlah sifat cross vektor diatas sebagai latihan!

## Contoh Soal Cross Vektor:
Diketahui  vektor $\vec{a}=2\widehat{i}-\widehat{j}+3\widehat{k}$ dan $\vec{b}=3\widehat{i}-2\widehat{j}+\widehat{k}.$ Tentukan hasil operasi 
1.	$\vec{a}\times \vec{b}$ 
2.	$\vec{b}\times \vec{a}$
3.	$\left| \vec{b}\times \vec{a} \right|$

**Alternatif Penyelesaian:**
1.	Hasil operasi $\vec{a}\times \vec{b}$
$$\begin{align*} & \vec{a}\times \vec{b}=\left| \begin{matrix}\widehat{i} & \widehat{j} & \widehat{k}\\\\ 2 & -1 & 3\\\\ 3 & -2 & 1\end{matrix} \right| \\\\ & \vec{b}\times \vec{a}=\left| \begin{matrix} \widehat{i} & \widehat{j} & \widehat{k}\\\\ 2 & -1 & 3\\\\ 3 & -2 & 1\end{matrix} \right|\left. \text{  }\begin{matrix}\widehat{i} &\widehat{j}\\\\2 & -1\\\\3 & -2\end{matrix} \right| \\\\ & \vec{b}\times \vec{a}=-\widehat{i}+9\widehat{j}-4\widehat{k}-(-3)\widehat{k}-(-6)\widehat{i}-2\widehat{j} \\\\ & \vec{a}\times \vec{b}=5\widehat{i}+7\widehat{j}-\widehat{k}\end{align*}$$
2.	Hasil operasi $\vec{b}\times \vec{a}$
$$\begin{align*} & \vec{b}\times \vec{a}=\left| \begin{matrix} \widehat{i} & \widehat{j} & \widehat{k}\\\\ 3 & -2 & 1\\\\ 2 & -1 & 3\end{matrix} \right| \\\\ & \vec{b}\times \vec{a}=\left| \begin{matrix} \widehat{i} & \widehat{j} & \widehat{k}\\\\ 3 & -2 & 1\\\\ 2 & -1 & 3\end{matrix} \right|\left. \text{  }\begin{matrix}\widehat{i} & \widehat{j}\\\\ 3 & -2\\\\ 2 & -1\end{matrix} \right| \\\\ & \vec{b}\times \vec{a}=-6\widehat{i}+2\widehat{j}-3\widehat{k}-(-4)\widehat{k}-(-1)\widehat{i}-9\widehat{j}\\\\ & \vec{b}\times \vec{a}=-5\widehat{i}-7\widehat{j}+\widehat{k} \\\\ \end{align*}$$
3.	Hasil operasi $\left| \vec{b}\times \vec{a} \right|$
$$\begin{align*} & \left| \vec{b}\times \vec{a} \right|=\sqrt{{{(-5)}^{2}}+{{(-7)}^{2}}+{{1}^{2}}} \\\\ & \left| \vec{b}\times \vec{a} \right|=\sqrt{25+49+1} \\\\ & \left| \vec{b}\times \vec{a} \right|=\sqrt{75} \\\\ & \left| \vec{b}\times \vec{a} \right|=5\sqrt{3}\end{align*}$$

## Contoh 2 Soal Cross Vektor
Diketahui Sudut antara vektor $ \vec{p} $ dan $ \vec{q} $ adalah $ 30^\circ $. Jika $ |\vec{p}| = 4 $ dan $ |\vec{q}| = 5 $ , maka tentukan 
$ |\vec{p} \times \vec{q}| $ !  
**Penyelesaian :**

Menentukan hasil $ |\vec{p} \times \vec{q}| $ :
$$\begin{align*}|\vec{p} \times \vec{q}|& = |\vec{p} | |\vec{q}| \sin \theta \\\\& = 4 \times 5  \sin 30^\circ \\\\& = 20 \times  \frac{1}{2} \\\\& = 10 \end{align*} $$  
Jadi, hasil dari $ |\vec{p} \times \vec{q}| = 10 $.