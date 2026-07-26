# Matrix

Owner: Erov
Status: In progress

Matriks adalah **sekumpulan bilangan yang disusun berdasarkan baris dan kolom, serta ditempatkan di dalam tanda kurung**. Tanda kurung ini bisa berupa kurung biasa “( )” atau kurung siku “[ ]”. Suatu matriks diberi nama dengan huruf kapital, seperti A, B, C, dan seterusnya.
*Baris → Horizontal, Kolom → Vertikal*

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image.png)

Matriks itu punya ukuran. Ukuran matriks disebut **ordo**. Ordo matriks ini berdasarkan dari banyaknya baris dikali banyaknya kolom pada matriks. Jadi, jika suatu matriks A memiliki m baris dan n kolom, maka matriks A tersebut berukuran (berordo) m x n. Supaya lebih sederhana, kita bisa menulisnya dengan $A_{m \times n}$.

Masing-masing bilangan yang terdapat di dalam matriks disebut **elemen matriks**. Elemen-elemen matriks juga ada notasinya sendiri. Jika matriks dinotasikan dengan huruf kapital, maka elemen-elemen matriks dinotasikan dengan huruf kecil dan diberi indeks yang menyatakan **letak baris dan kolomnya**.

Misalnya, pada matriks A di atas, jumlah barisnya kan ada 5 dan jumlah kolomnya juga ada 5, maka ordonya adalah 5 x 5, atau bisa kita tulis $A_{5×5}$. Lalu, untuk elemen-elemen matriks A bisa dinotasikan dengan aij, yang menyatakan elemen matriks A pada baris ke-i dan kolom ke-j.

Kita ambil contoh a11, a12, dan a54, seperti pada gambar.

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%201.png)

- a11 menyatakan elemen matriks A pada baris ke-1 kolom ke-1, nilainya adalah 0.
- a12 menyatakan elemen matriks A pada baris ke-1 kolom ke-2, nilainya adalah 1.
- a54 menyatakan elemen matriks A pada baris ke-5 kolom ke-4, nilainya adalah 2.

> *Matrix dibaca dengan $A_{ij}$, sebenarnya i dan j adalah row dan column, jadi A {row, column}*
> 

# **Jenis-Jenis Matriks**

## Menurut rg_

Selain punya ukuran (ordo), matriks juga terbagi menjadi beberapa bentuk yang mempunyai sifat khusus. Beberapa jenis matriks khusus yang perlu kamu ketahui di antaranya sebagai berikut:

### **a. Matriks Baris**

Matriks baris adalah suatu matriks yang **terdiri dari satu baris aja**. Contoh matriks baris:

![matriks baris](https://cdn-web.ruangguru.com/landing-pages/assets/hs/matriks%20baris.jpg)

Jika kita lihat, matriks A, matriks P, dan matriks Q, semuanya terdiri dari satu baris dan beberapa kolom. Untuk masing-masing ordonya, berarti A1×3, P1×4, dan Q1×5.

### **b. Matriks Kolom**

Kebalikannya dari matriks baris, matriks kolom adalah suatu matriks yang **terdiri dari satu kolom saja**. Contoh matriks kolom:

![matriks kolom](https://cdn-web.ruangguru.com/landing-pages/assets/hs/matriks%20kolom.jpg)

Matriks R, matriks S, dan matriks T sama-sama terdiri dari satu kolom dan beberapa baris. Oleh karena itu, ordo matriksnya adalah R2×1, S3×1, dan T4×1.

### **c. Matriks Persegi**

Matriks persegi adalah suatu matriks yang **memiliki jumlah baris dan kolom sama**. Itu tandanya, m = n. Karena jumlah baris dan kolomnya sama, maka ordo matriksnya bisa kita tulis menjadi n x n, atau matriks ordo n.

Pada matriks persegi, terdapat **diagonal utama**, yaitu elemen-elemen matriks yang letak barisnya sama dengan letak kolomnya. Selain diagonal utama, ada juga diagonal samping atau diagonal kedua. Jika kita tarik garis di sepanjang diagonal utama matriks, maka diagonal samping ini berada di arah sebaliknya. Contoh matriks persegi:

![matriks persegi](https://cdn-web.ruangguru.com/landing-pages/assets/hs/matriks%20persegi.jpg)

Berdasarkan contoh di atas, matriks A memiliki jumlah baris dan kolom yang sama karena matriks ini merupakan matriks persegi, yaitu sebanyak 2. Maka, matriks ini merupakan matriks berordo 2. Kemudian, elemen-elemen pada diagonal utamanya adalah 8 dan 7.

### **d. Matriks Diagonal**

Matriks diagonal adalah **matriks persegi yang** **elemen-elemen selain diagonal utamanya bernilai nol**. Contoh matriks diagonal:

![matriks diagonal](https://cdn-web.ruangguru.com/landing-pages/assets/hs/matriks%20diagonal.jpg)

Kalo kita perhatikan gambar di atas, elemen-elemen pada diagonal utama matriks Q adalah 3, 8, dan 5. Nah, di **luar** diagonal utama, semua elemennya bernilai 0. Misalnya, elemen Q12 adalah 0, lalu elemen Q21 juga 0.

### **e. Matriks Identitas**

Matriks identitas adalah **matriks persegi yang semua elemen pada diagonal utamanya bernilai satu, sedangkan elemen lainnya bernilai nol**. Umumnya, matriks identitas dinotasikan dengan *I* disertai dengan ordonya. Contoh matriks identitas:

![matriks identitas](https://cdn-web.ruangguru.com/landing-pages/assets/hs/matriks%20identitas.jpg)

### **f. Matriks Nol**

Sesuai namanya, matriks nol adalah **matriks yang semua elemennya bernilai nol**. Matriks nol biasanya dinotasikan dengan huruf O disertai ordonya. Contoh matriks nol:

![contoh matriks nol](https://cdn-web.ruangguru.com/landing-pages/assets/hs/contoh%20matriks%20nol.jpg)

## **Transpose Matriks**

Transpose matriks adalah **suatu matriks yang** **diperoleh dari hasil pertukaran antara elemen baris dan kolomnya**. Jadi, elemen-elemen pada baris akan kita tukar menjadi elemen-elemen pada kolom, atau sebaliknya.

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%202.png)

## 1. Matriks Baris

Matriks baris adalah matriks berordo 1 × n yang terdiri atas satu baris dan memuat n elemen.

$A_{1 \times 2}$ = [85 70], matriks baris yang berordo 1 x 2

$B_{1 \times 5}$ = [65 60 90 95 80], matriks baris yang berordo 1 x 5

## 2. Matriks Kolom

Matriks kolom adalah matriks berordo m x 1 yang terdiri atas satu kolom dan memuat m elemen.

$A_{2 \times 1}$ = $\begin{bmatrix} 68 \\ 79 \end{bmatrix}$, matriks kolom yang berordo 2 x 1

$B_{3 \times 1}$ = $\begin{bmatrix} 70 \\ 68 \\ 92 \end{bmatrix}$, matriks kolom yang berordo 3 x 1

## 3. Matriks Persegi

Matriks persegi adalah matriks berordo m x n dengan m = n.

$A_{2 \times 2}$ = $\begin{bmatrix} 21 & 11 \\ 32 & 25 \end{bmatrix}$, ordo 2 x 2

$B_{3 \times 3}$ = $\begin{bmatrix} 21 & 11 & 12  \\ 10 & 27 & 31 \\ 19 & 17 & 27 \end{bmatrix}$, ordo 3 x 3

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%203.png)

## 4. Matriks datar & tegak

Matriks datar adalah matriks berordo m × n dengan m < n, artinya banyak kolom lebih banyak daripada banyak baris. Matriks tegak adalah matriks berordo m × n dengan m > n, artinya banyak baris lebih banyak daripada banyak kolom. Matriks datar dan matriks tegak kerap disebut matriks persegi panjang. Berikut ini contoh matriks datar dan matriks tegak.

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%204.png)

## 5. Matriks Segitiga

Matriks segitiga adalah matriks persegi dengan elemen-elemen yang berada di bawah diagonal utama atau di atas diagonal utama bernilai nol. Matriks segitiga ada dua macam yaitu sebagai berikut.

1. Matriks segitiga atas adalah matriks yang semua elemen di bawah diagonal utamanya bernilai nol.
    
    ![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%205.png)
    
2. Matriks segitiga bawah adalah matriks yang semua elemen di atas diagonal utamanya bernilai nol.

    
    ![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%206.png)
    

## 6. Matriks Diagonal

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%207.png)

Elemen-elemen pada matriks di atas bernilai nol, kecuali yang terletak pada diagonal utama. Matriks dengan ciri ini disebut matriks diagonal.

## 7. Matriks Identitas (0&1)

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%208.png)

Matriks diagonal dengan elemen-elemen pada diagonal utamanya bernilai satu disebut matriks identitas.

## 8. Matriks Nol

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%209.png)

Semua elemen pada matriks O di atas bernilai nol. Matriks seperti ini dinamakan matriks nol.

## 9. Matriks Simetris ($A \space = \space A_T$)

Matriks simetris adalah matriks persegi dengan elemen-elemen yang letaknya simetris terhadap diagonal utama bernilai sama. Dengan kata lain, elemen aij sama dengan elemen aji dengan i ≠ j. Mudahnya, bentuk dari matriks sama setelah di transpose.

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%2010.png)

## 10. Matriks Transpose

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%2011.png)

# Operasi Matriks

## Penjumlahan

Jika matriks A dan matriks B adalah matriks-matriks yang berordo m × n dengan elemen-elemen aij dan bij, maka ada matriks C yang merupakan hasil penjumlahan matriks A dengan matriks B atau C = A + B . Matriks C juga berordo m × n dengan elemen-elemen cij= aij+ bij (untuk semua i dan j).

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%2012.png)

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%2013.png)

> 
> 
> 
> *To add two matrices together, you must follow one strict rule: **the matrices must have the exact same dimensions** (the same number of rows and columns).*
> 
> *Matrix addition is performed **element-wise**, meaning you add the corresponding entries that occupy the same position in each matrix.*
> 

To add two matrices together, you must follow one strict rule: **the matrices must have the exact same dimensions** (the same number of rows and columns).

Matrix addition is performed **element-wise**, meaning you add the corresponding entries that occupy the same position in each matrix.

### The Formula

For two $2 \times 2$ matrices, the operation looks like this:

$\begin{bmatrix} a & b \\ c & d \end{bmatrix} + \begin{bmatrix} e & f \\ g & h \end{bmatrix} = \begin{bmatrix} a+e & b+f \\ c+g & d+h \end{bmatrix}$

#### Concrete Example

Let us add Matrix $A$ and Matrix $B$ together. Both are $2 \times 3$ matrices (2 rows, 3 columns), so the operation is valid.

$A = \begin{bmatrix} 3 & -1 & 4 \\ 2 & 0 & 5 \end{bmatrix}, \quad B = \begin{bmatrix} 1 & 7 & -2 \\ -4 & 3 & 6 \end{bmatrix}$

#### Step-by-Step Calculation

We add the elements matching row-for-row and column-for-column:

- **Top-Left ($a_{11} + b_{11}$):** $3 + 1 = 4$
- **Top-Middle ($a_{12} + b_{12}$):** $-1 + 7 = 6$
- **Top-Right ($a_{13} + b_{13}$):** $4 + (-2) = 2$
- **Bottom-Left ($a_{21} + b_{21}$):** $2 + (-4) = -2$
- **Bottom-Middle ($a_{22} + b_{22}$):** $0 + 3 = 3$
- **Bottom-Right ($a_{23} + b_{23}$):** $5 + 6 = 11$

#### Final Result

$A + B = \begin{bmatrix} 3+1 & -1+7 & 4+(-2) \\ 2+(-4) & 0+3 & 5+6 \end{bmatrix} = \begin{bmatrix} 4 & 6 & 2 \\ -2 & 3 & 11 \end{bmatrix}$

> **Note on Invalid Operations:** If you attempted to add a $2 \times 3$ matrix to a $3 \times 2$ matrix, the operation would be mathematically undefined because certain elements would lack a spatial counterpart. If you absolutely must combine these two matrices via addition, you must apply the **transpose** operator ($T$) to one of them first. Transposing flips the rows and columns, turning a $3 \times 2$ into a $2 \times 3$ (or vice versa).
> 

## Pengurangan

> Misalkan terdapat dua buah matriks, yaitu matriks A dan matriks B. Jika matriks C adalah matriks pengurangan dari A dengan B, maka matriks C dapat diperoleh dengan mengurangkan setiap elemen pada matriks A yang seletak dengan setiap elemen pada matriks B.
> 

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Matematika%20Tingkat%20Lanjut/Matrix_images/image%2014.png)

Matrix subtraction is performed using the exact same spatial mechanics as matrix addition. It is an **element-wise** operation, meaning you subtract each entry of the second matrix from the corresponding entry of the first matrix.

## The Rule of Dimensions

Before performing the calculation, you must verify that **both matrices share the exact same dimensions** (the same number of rows and columns). If the dimensions differ by even one row or column, the subtraction is mathematically undefined.

For two $2 \times 2$ matrices, the general algebraic framework is:

$\begin{bmatrix} a & b \\ c & d \end{bmatrix} - \begin{bmatrix} e & f \\ g & h \end{bmatrix} = \begin{bmatrix} a-e & b-f \\ c-g & d-h \end{bmatrix}$

## Concrete Example

Let us subtract a $2 \times 2$ matrix $B$ from a $2 \times 2$ matrix $A$.

$A = \begin{bmatrix} 8 & 3 \\ -2 & 5 \end{bmatrix}, \quad B = \begin{bmatrix} 4 & -1 \\ 6 & 2 \end{bmatrix}$

### Step-by-Step Calculation

We isolate each coordinate position and compute the difference:

- **Top-Left ($a_{11} - b_{11}$):** $8 - 4 = 4$
- **Top-Right ($a_{12} - b_{12}$):** $3 - (-1) = 3 + 1 = 4$
- **Bottom-Left ($a_{21} - b_{21}$):** $-2 - 6 = -8$
- **Bottom-Right ($a_{22} - b_{22}$):** $5 - 2 = 3$

### Final Result

$A - B = \begin{bmatrix} 8-4 & 3-(-1) \\ -2-6 & 5-2 \end{bmatrix} = \begin{bmatrix} 4 & 4 \\ -8 & 3 \end{bmatrix}$

## Order Matters (Non-Commutative)

Unlike standard scalar subtraction where $5 - 3 \neq 3 - 5$, matrix subtraction is strictly dependent on order ($A - B \neq B - A$). Flipping the order of the matrices will invert the signs of every element in the final result.

## Multiplication