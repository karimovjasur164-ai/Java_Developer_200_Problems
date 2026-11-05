
# ☕ Java Developer: Uyga Vazifalar Jamlanmasi

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Programming-Exercises-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Learning-success?style=for-the-badge">
</p>

---

**👨‍💻 Muallif:** Rahimjonov Otabek

**📚 Mavzu:** 200 Exam yechib kelish

---

# 💻 Java Programming Exercises 01

### 📝 Masala haqida

- Foydalanuvchidan berilayotgan `(n)` o'zgaruvchini `12` soniga tenglab olyapmiz.
- Keyin `(k)` o'zgaruvchini `8` soniga tenglab olyapmiz.
- Maqsad: `n` sonini `k` ga bo'lish va butun qismini aniqlash.

### ⚙️ Java Code

**1. Quotient — Bo'lish natijasining butun qismi**

```java
static int quotient() {
    int res = 0; // res o'zgaruvchiga 0 belgilayapmiz

    // While bilan tekshiriladi:
    // n >= k bo'lsa, qaytadan tekshirish davom etadi
    while (n >= k) {
        n = n - k;
        res++;
    }

    return res;
}
```

**2. Quotient2 — Bo'lishdan qolgan qoldiq**

```java
static int quotient2() {

    // While bilan tekshiriladi:
    // n >= k bo'lsa, qaytadan tekshirish davom etadi
    while (n >= k) {
        n = n - k;
    }

    return n;
}
```

### 💻 Full Source Code

```java
public class Problem1 {

    static int n = 12;
    static int k = 8;

    static int quotient() {
        int res = 0;

        while (n >= k) {
            n = n - k;
            res++;
        }

        return res;
    }

    static int quotient2() {
        while (n >= k) {
            n = n - k;
        }

        return n;
    }
}
```

---

# 💻 Java Programming Exercises 02

### 📝 Masala haqida

- `n` o'zgaruvchini `43` soniga tenglab olyapmiz.
- Sonning raqamlarini bittadan tekshiramiz.
- Agar raqamlar orasida juft raqam mavjud bo'lsa, `true` qaytaramiz.
- Agar juft raqam topilmasa, `false` qaytaramiz.

### ⚙️ Java Code

**1. Even — Juft raqamni aniqlash**

```java
static boolean Even() {

    // Sonning raqamlarini bittadan tekshiramiz
    while (n > 0) {

        int d = n % 10;

        // Raqam juft ekanligini tekshiramiz
        if (d % 2 == 0) {
            return true;
        }

        // Oxirgi raqamni olib tashlaymiz
        n = n / 10;
    }

    return false;
}
```

### 💻 Full Source Code

```java
class Problem2 {

    static int n = 43;

    static boolean Even() {

        while (n > 0) {
            int d = n % 10;

            if (d % 2 == 0) {
                return true;
            }

            n = n / 10;
        }

        return false;
    }
}
```

---

<p align="center">
  <b>☕ Keep Learning. Keep Coding. Keep Growing.</b>
</p>

<p align="center">
  ⭐ Thanks for visiting my repository! ⭐
</p>
 
 
