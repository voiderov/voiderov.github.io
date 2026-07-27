# Vektor

Owner: Erov
Status: In progress

# Konsep Vektor

> *Vektor adalah besaran yang memiliki nilai (besar) dan arah. Dalam fisika dan matematika, ini digunakan untuk menggambarkan fenomena seperti kecepatan, perpindahan, dan gaya. Secara grafis, vektor digambarkan sebagai ruas garis berarah dengan panjang garis menunjukkan nilai dan anak panah menunjukkan arahnya.*
> 

Besaran fisika dapat dibedakan atas besaran vektor dan besaran skalar. Besaran vektor mempunyai nilai dan arah sedangkan besaran skalar hanya mempunyai nilai saja. Vektor dinyatakan dengan anak panah. Panjang anak panah menyatakan besar vektor sedangkan arahnya dapat dinyatakan oleh sudut. Sebuah vektor digambarkan dengan anak panah yang memiliki pangkal dan ujung.

Hal khusus tentang vektor :

1. Vektor nol yaitu vektor yang bernilai nol. Pemahaman vektor nol diulas dalam pengurangan vektor.
2. Vektor satuan yaitu vektor dengan besar 1 dan arah tertentu.
Vektor satuan diulas dalam komponen vektor.

## **Sifat-Sifat Vektor**

Vektor adalah besaran yang memiliki **nilai (magnitudo)** dan **arah**. Berikut adalah sifat-sifat utama vektor dalam matematika dan fisika:

### 1. **Sifat Dasar Vektor**

- **Magnitudo (Panjang)**: Selalu bernilai positif atau nol. Dilambangkan dengan `|v|` atau `‖v‖`.
- **Arah**: Ditentukan oleh sudut terhadap sumbu koordinat.
- **Vektor Nol (Zero Vector)**: Vektor dengan magnitudo 0, tidak memiliki arah tertentu. Ditulis **0**.
- **Vektor Satuan (Unit Vector)**: Vektor yang magnitudonya = 1. Ditulis dengan topi (̂`)`, contoh: î**,** ĵ**,** k̂**.**

### 2. **Sifat Operasi Penjumlahan Vektor**

- **Komutatif**: **A + B = B + A**
- **Asosiatif**: **(A + B) + C = A + (B + C)**
- **Identitas**: **A + 0 = A**
- **Invers**: **A + (-A) = 0** (vektor berlawanan arah, magnitudo sama)

### 3. **Sifat Perkalian Skalar (dengan bilangan riil)**

- **Distributif terhadap penjumlahan vektor**:
    - `k(A + B) = kA + kB`
- **Distributif terhadap penjumlahan skalar**:
    - `(k + m)A = kA + mA`
- **Asosiatif**:
    - `k(mA) = (km)A`
- **Identitas**: `1 · A = A`

### 4. **Sifat Produk Dot (Perkalian Titik)**

- **A · B = |A| |B| cosθ**
- **Komutatif**: **A · B = B · A**
- **Distributif**: **A · (B + C) = A·B + A·C**
- Jika **A · B = 0** dan A, B ≠ 0, maka A dan B **saling tegak lurus (ortogonal)**.

### 5. **Sifat Produk Cross (Perkalian Silang) di Ruang 3D**

- **A × B = |A| |B| sinθ n̂** (n̂ adalah vektor unit tegak lurus terhadap A dan B)
- **Anti-komutatif**: **A × B = - (B × A)**
- **Distributif**: **A × (B + C) = A×B + A×C**
- **A × A = 0**
- **A × B = 0** jika A dan B sejajar (parallel).

### 6. **Sifat Lainnya**

| Sifat | Keterangan |
| --- | --- |
| **Vektor Sejajar** | Satu vektor adalah kelipatan skalar dari vektor lain |
| **Vektor Berlawanan** | Magnitudo sama, arah berlawanan |
| **Dekomposisi** | Vektor dapat diuraikan menjadi komponen (i, j, k) |
| **Proyeksi** | Proyeksi vektor A ke B: `(A·B / |

### Contoh Sederhana

Misal **A = (3, 4)**:

- Magnitudo: `|A| = √(3² + 4²) = 5`
- Vektor satuan: **Â = (3/5, 4/5)**

| Vectors | Scalars |
| --- | --- |
| Magnitude/size | Magnitude/size |
| Direction | - |

If someone say, 5 meters → Scalar
If someone say 5 meters north → Vector

**Tabel Perbandingan Besaran Skalar dan Besaran Vektor**

| No | Besaran (Indonesia) | Quantity (English) | Jenis | Simbol Umum | Rumus / Contoh | Keterangan |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Massa | Mass | Skalar | $( m )$ | $( m = \frac{F}{a} )$ | Hanya memiliki nilai (magnitude), tidak ada arah |
| 2 | Waktu | Time | Skalar | $( t )$ | $( t = \frac{s}{v} )$ | Hanya besaran |
| 3 | Suhu | Temperature | Skalar | $( T )$ | $( T )$ dalam Kelvin/Celsius | Hanya magnitude |
| 4 | Jarak | Distance | Skalar | $( s )$ atau ( d ) | $( s = )$ total lintasan | Panjang lintasan (tidak peduli arah) |
| 5 | Kecepatan | Speed | Skalar | $( v )$ | $( v = \frac{s}{t} )$ | Besar kecepatan (tanpa arah) |
| 6 | Energi | Energy | Skalar | $( E ) \space atau \space( K )$ | $( E_k = \frac{1}{2}mv^2 )$ | Energi kinetik, potensial, dll. |
| 7 | Daya | Power | Skalar | $( P )$ | $( P = \frac{W}{t} = F \cdot v )$ | Kerja per satuan waktu |
| 8 | Muatan listrik | Electric Charge | Skalar | $( Q )$ | $( Q = ne )$ | Hanya jumlah muatan |
| 9 | Massa jenis | Density | Skalar | $( \rho )$ | $( \rho = \frac{m}{V} )$ | Massa per volume |
| 10 | Tekanan | Pressure | Skalar | $( P ) \space atau \space ( p )$ | $( p = \frac{F}{A} )$ | Gaya per luas (magnitude saja) |

### Besaran Vektor

| No | Besaran (Indonesia) | Quantity (English) | Jenis | Simbol Umum | Rumus / Contoh | Keterangan |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Perpindahan | Displacement | Vektor | $( \vec{s} ) \space atau \space ( \vec{d} )$ | $( \vec{s} = \vec{r}_f - \vec{r}_i )$ | Jarak dengan arah tertentu |
| 2 | Kecepatan | Velocity | Vektor | $( \vec{v} )$ | $( \vec{v} = \frac{\Delta \vec{s}}{\Delta t} )$ | Kecepatan + arah |
| 3 | Percepatan | Acceleration | Vektor | $( \vec{a} )$ | $( \vec{a} = \frac{\Delta \vec{v}}{\Delta t} )$ | Perubahan kecepatan (besar + arah) |
| 4 | Gaya | Force | Vektor | $( \vec{F} )$ | $( \vec{F} = m\vec{a} )$ (Hukum Newton II)
 | Memiliki besar dan arah |
| 5 | Momentum | Momentum | Vektor | $( \vec{p} )$ | $( \vec{p} = m\vec{v} )$ | Massa × kecepatan vektor |
| 6 | Impuls | Impulse | Vektor | $( \vec{J} ) \space atau \space( \vec{I} )$ | $( \vec{J} = \vec{F} \Delta t )$ | Perubahan momentum |
| 7 | Medan listrik | Electric Field | Vektor | $( \vec{E} )$ | $( \vec{E} = \frac{\vec{F}}{Q} )$ | Gaya per muatan uji |
| 8 | Medan magnet | Magnetic Field | Vektor | $( \vec{B} )$ | $( \vec{F} = q(\vec{v} \times \vec{B}) )$ | Memiliki arah (aturan tangan kanan) |
| 9 | Kecepatan sudut | Angular Velocity | Vektor | $( \vec{\omega} )$ | $( \vec{\omega} = \frac{\Delta \vec{\theta}}{\Delta t} )$ | Arah sesuai sumbu rotasi |
| 10 | Percepatan sudut | Angular Acceleration | Vektor | $( \vec{\alpha} )$ | $( \vec{\alpha} = \frac{\Delta \vec{\omega}}{\Delta t} )$ | - |

### Ringkasan Perbedaan Utama

| Aspek | Besaran Skalar | Besaran Vektor |
| --- | --- | --- |
| **Komponen** | Hanya **magnitude** (nilai) | **Magnitude + Arah** |
| **Operasi Matematika** | Penjumlahan biasa | Penjumlahan dengan **aturan segitiga** atau **metode komponen** |
| **Simbol** | Huruf biasa (m, t, v) | Huruf dengan tanda panah $( \vec{v} )$ atau cetak tebal |
| **Contoh Operasi** | $( 5\,\text{kg} + 3\,\text{kg} = 8\,\text{kg} )$ | $( \vec{v}_1 + \vec{v}_2 )$ (bukan penjumlahan biasa) |

# Karakteristik Vektor

1. “Dua vektor dikatakan sama jika keduanya mempunyai besar dan arah yang sama.”

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Fisika/Vektor_images/image.png)

1. “Vektor negatif sama besar tetapi berlawanan arah dengan suatu vektor.”

![image.png](Wiki%20of%20My%20Life/Persiapan%20Belajar%20Kelas%20XI/Fisika/Vektor_images/image%201.png)

# Representasi Vektor

Vektor direpresentasikan dengan dua cara yaitu melalui cara penggambaran anak panah yang menyatakan besar dan arah serta dalam komponen-kom- ponen pembentuknya yang merupakan hasil penguraian dari vektor tersebut.

| Quadrant | Angle ($\theta^\circ$) | Angle ($\theta\text{ rad}$) | $\sin(\theta)$ | $\cos(\theta)$ | $\tan(\theta)$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Quadrantal** | $0^\circ$ | $0$ | $0$ | $1$ | $0$ |
| **Quadrant I** | $30^\circ$ | $\frac{\pi}{6}$ | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{3}}{3}$ |
| | $45^\circ$ | $\frac{\pi}{4}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$ |
| | $60^\circ$ | $\frac{\pi}{3}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |
| **Quadrantal** | $90^\circ$ | $\frac{\pi}{2}$ | $1$ | $0$ | $\text{Undefined}$ |
| **Quadrant II** | $120^\circ$ | $\frac{2\pi}{3}$ | $\frac{\sqrt{3}}{2}$ | $-\frac{1}{2}$ | $-\sqrt{3}$ |
| | $135^\circ$ | $\frac{3\pi}{4}$ | $\frac{\sqrt{2}}{2}$ | $-\frac{\sqrt{2}}{2}$ | $-1$ |
| | $150^\circ$ | $\frac{5\pi}{6}$ | $\frac{1}{2}$ | $-\frac{\sqrt{3}}{2}$ | $-\frac{\sqrt{3}}{3}$ |
| **Quadrantal** | $180^\circ$ | $\pi$ | $0$ | $-1$ | $0$ |
| **Quadrant III** | $210^\circ$ | $\frac{7\pi}{6}$ | $-\frac{1}{2}$ | $-\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{3}}{3}$ |
| | $225^\circ$ | $\frac{5\pi}{4}$ | $-\frac{\sqrt{2}}{2}$ | $-\frac{\sqrt{2}}{2}$ | $1$ |
| | $240^\circ$ | $\frac{4\pi}{3}$ | $-\frac{\sqrt{3}}{2}$ | $-\frac{1}{2}$ | $\sqrt{3}$ |
| **Quadrantal** | $270^\circ$ | $\frac{3\pi}{2}$ | $-1$ | $0$ | $\text{Undefined}$ |
| **Quadrant IV** | $300^\circ$ | $\frac{5\pi}{3}$ | $-\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $-\sqrt{3}$ |
| | $315^\circ$ | $\frac{7\pi}{4}$ | $-\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $-1$ |
| | $330^\circ$ | $\frac{11\pi}{6}$ | $-\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $-\frac{\sqrt{3}}{3}$ |
| **Quadrantal** | $360^\circ$ | $2\pi$ | $0$ | $1$ | $0$ |
