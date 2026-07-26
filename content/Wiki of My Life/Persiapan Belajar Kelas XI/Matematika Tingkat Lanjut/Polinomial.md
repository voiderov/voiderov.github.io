# Polinomial

Owner: Erov
Status: Not started

# Pengenalan Monomial

## Pembahasan Aktivitas Aljabar

### Nomor 1

**Pengelompokan Bentuk Aljabar:**

- **Kelompok A (Monomial):**
    
    $2x^2y, \quad -8, \quad 1,24k^4$
    
- **Kelompok B (Bukan Monomial):**
    
    $\sqrt[3]{p}, \quad \frac{2}{m}, \quad 5a^{-6}$
    

**Alasan Pengelompokan:**

Pengelompokan dilakukan berdasarkan eksponen (pangkat) dari variabelnya:

- **Kelompok A** memiliki variabel yang berpangkat bilangan cacah ($0, 1, 2, \dots$). Tidak ada variabel di dalam akar, di penyebut pecahan, ataupun berpangkat negatif.
- **Kelompok B** memiliki variabel yang berada di bawah tanda akar ($\sqrt[3]{p} = p^{\frac{1}{3}}$), di posisi penyebut ($\frac{2}{m} = 2m^{-1}$), atau memiliki pangkat negatif ($5a^{-6}$).

### Nomor 2

Pengelompokan pada nomor 2 didasarkan pada **karakteristik pangkat variabel**:

- **Kelompok 1** terdiri atas bentuk-bentuk aljabar di mana variabelnya memiliki **pangkat bilangan cacah** (pangkat tak-negatif dan bulat).
- **Kelompok 2** terdiri atas bentuk-bentuk aljabar yang variabelnya memiliki **pangkat pecahan atau negatif**, yaitu:
    - $\sqrt[3]{p} = p^{\frac{1}{3}}$ (pangkat pecahan)
    - $\frac{2}{m} = 2m^{-1}$ (pangkat negatif)
    - $5a^{-6}$ (pangkat negatif)

### Nomor 3

**Pengertian Monomial:**

> **Monomial** adalah bentuk aljabar yang terdiri dari satu suku berupa konstanta, variabel, atau hasil kali antara konstanta dan variabel, dengan syarat variabel tersebut harus memiliki **pangkat bilangan cacah** (bilangan bulat non-negatif: $0, 1, 2, 3, \dots$).
> 

Suatu bentuk aljabar **bukan** merupakan monomial jika variabelnya:

1. Berada di bawah tanda akar (pangkat pecahan).
2. Berada di bagian penyebut suatu pecahan (pangkat negatif).
3. Memiliki pangkat bernilai negatif.

# Apa itu monomial?

Monomial adalah suatu bilangan, variabel berpangkat bilangan cacah, atau perkalian bilangan dengan satu atau lebih variabel berpangkat bilangan cacah. Dengan demikian, monomial juga dapat dikatakan sebagai sebuah ekspresi matematika yang terdiri atas satu suku. Konstanta merupakan monomial yang tidak memuat variabel, misalnya –8 dan 25. Adapun faktor numerik dari suatu monomial disebut koefisien.

## Operation

To operate on polynomials, one must apply the fundamental properties of algebra, specifically the commutative, associative, and distributive properties, alongside the rules of exponents. A polynomial is an expression consisting of variables and coefficients, involving only the operations of addition, subtraction, multiplication, and non-negative integer exponents.

Below is a systematic overview of the four primary operations.

## 1. Polynomial Addition

The core principle of polynomial addition is combining "like terms." Like terms are defined as terms that possess the exact same variables raised to the exact same powers.

**Procedure:**

1. Group the terms with identical variable parts.
2. Add their coefficients.
3. Keep the variable part unchanged.

**Example:**

Evaluate $(3x^2 + 4x - 5) + (2x^2 - x + 7)$.

Group the like terms:

$(3x^2 + 2x^2) + (4x - x) + (-5 + 7)$

Combine the coefficients:

$5x^2 + 3x + 2$

## 2. Polynomial Subtraction

Subtraction follows the same logic as addition, with one critical preliminary step: distributing the negative sign. Subtracting a polynomial is equivalent to adding its opposite.

**Procedure:**

1. Distribute the negative sign to every term in the polynomial being subtracted, which reverses the sign of each term.
2. Combine the resulting like terms as done in addition.

**Example:**

Evaluate $(5x^3 - 2x^2 + 4) - (2x^3 + 3x^2 - x)$.

Distribute the negative sign:

$$5x^3 - 2x^2 + 4 - 2x^3 - 3x^2 + x$$

Group and combine like terms:

$$(5x^3 - 2x^3) + (-2x^2 - 3x^2) + x + 4$$

$$3x^3 - 5x^2 + x + 4$$

## 3. Polynomial Multiplication

Multiplication relies heavily on the distributive property and the product rule for exponents, which states that when multiplying expressions with the same base, you add the exponents: $x^a \cdot x^b = x^{a+b}$.

**Procedure:**

1. Multiply every term in the first polynomial by every term in the second polynomial. For two binomials, this is commonly referred to by the mnemonic FOIL (First, Outer, Inner, Last).
2. Multiply the coefficients and add the exponents of corresponding variables.
3. Combine any resulting like terms to simplify the final expression.

**Example:**

Evaluate $(2x - 3)(x^2 + 4x - 1)$.

Distribute $2x$ and then distribute $-3$:

$$2x(x^2 + 4x - 1) - 3(x^2 + 4x - 1)$$

$$(2x^3 + 8x^2 - 2x) - (3x^2 + 12x - 3)$$

Combine like terms:

$$2x^3 + (8x^2 - 3x^2) + (-2x - 12x) + 3$$

$$2x^3 + 5x^2 - 14x + 3$$

## 4. Polynomial Division

Division can be approached in two primary ways: long division and synthetic division. Polynomial long division is the universal method that works for any polynomial divisor.

**Procedure (Long Division):**

1. Ensure both polynomials are written in descending order of their degrees. If a term is missing, insert it with a coefficient of $0$ as a placeholder.
2. Divide the leading term of the dividend by the leading term of the divisor. This yields the first term of the quotient.
3. Multiply the entire divisor by this new term and subtract the result from the dividend.
4. Bring down the next term and repeat the process until the degree of the remainder is strictly less than the degree of the divisor.

**Example:**

Divide $(x^2 + 5x + 6)$ by $(x + 2)$.

1. Divide leading terms: $\frac{x^2}{x} = x$. The first term of the quotient is $x$.
2. Multiply: $x(x + 2) = x^2 + 2x$.
3. Subtract: $(x^2 + 5x) - (x^2 + 2x) = 3x$.
4. Bring down the $6$, leaving $3x + 6$.
5. Divide leading terms: $\frac{3x}{x} = 3$. The next term of the quotient is $3$.
6. Multiply: $3(x + 2) = 3x + 6$.
7. Subtract: $(3x + 6) - (3x + 6) = 0$. The remainder is $0$.

The final quotient is $x + 3$.

To bridge these theoretical concepts with practical application, you may utilize the interactive tool below to input different polynomials and observe the calculated outcomes for these operations.

## Polynomial Division
